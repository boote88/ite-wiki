# Information Transfer Economics Wiki — Schema

This is a research wiki built from Jason Smith's "Information Transfer Economics" blog (~1,555 posts, 2013–2023). The blog applies information theory and statistical mechanics to macroeconomics.

## Three Layers

### Raw sources (`raw/`)
Immutable blog posts. Symlinked to `/Users/alex/Code/infotrecon/posts/`. Organized by `YYYY/MM/post-slug.md`. Each post has YAML frontmatter:
```yaml
title: "Post Title"
date: 2013-04-24T15:57:00.001-07:00
updated: 2013-04-24T16:19:22.230-07:00
author: Jason Smith
originalUrl: https://informationtransfereconomics.blogspot.com/...
```
**Never modify raw sources.**

### The wiki (`wiki/`)
LLM-generated and LLM-maintained markdown. The user reads; the LLM writes.

### The schema (`CLAUDE.md`)
This file. Defines conventions, workflows, and structure. Co-evolved with the user over time.

## Directory Structure

```
wiki/
├── index.md        # Catalog of all wiki pages
├── log.md          # Chronological record of all operations
├── overview.md     # High-level overview of the research program
├── concepts/       # Core theoretical concepts
├── entities/       # People, institutions, data series, models
├── topics/         # Thematic pages
├── sources/        # Legacy source summaries (early ingest only; no longer created)
├── media/          # Images copied from raw/ for Obsidian rendering
└── synthesis/      # Cross-cutting analyses, comparisons
```

### Page types
- **concept**: A core theoretical idea (e.g., information equilibrium, non-ideal information transfer)
- **entity**: A person, institution, data series, or model (e.g., Fielitz & Borchardt, JOLTS, the Fed)
- **topic**: A thematic area (e.g., inflation, labor markets, monetary policy)
- **source**: (Legacy) Summary of one or more blog posts. No longer created — cite raw posts directly in frontmatter `sources:` lists
- **synthesis**: Cross-cutting analysis, comparison, or timeline

## Page Format

Every wiki page uses this structure:

```markdown
---
title: Page Title
type: concept|entity|topic|source|synthesis
tags: [tag1, tag2]
sources:
  - raw/YYYY/MM/post-slug.md
created: YYYY-MM-DD
last_updated: YYYY-MM-DD
---

Page content here. Use [[wikilinks]] for cross-references to other wiki pages.

Cite source posts as: [Post Title (YYYY-MM-DD)](../raw/YYYY/MM/post-slug.md)
```

- Filenames: kebab-case (e.g., `information-equilibrium.md`)
- Wikilinks: `[[page-name]]` without path prefixes — Obsidian resolves these automatically
- Tags: lowercase, hyphenated
- **Images**: copy referenced images from `raw/YYYY/MM/media/` into `wiki/media/YYYY-MM/`, then embed with `![alt text](<../media/YYYY-MM/filename.png>)`. Use angle brackets `<>` for filenames with spaces. The `raw/` symlink points outside the vault, so Obsidian can't resolve paths to it.
- Source posts reference images as `![](<media/filename.png>)` — copy the image to `wiki/media/YYYY-MM/` and use the wiki-local path

## index.md

The content catalog. Organized by category. Each entry is one line:

```markdown
## Concepts
- [[information-transfer-model]] — Core framework applying Shannon information theory to supply and demand

## Entities
- [[fielitz-borchardt]] — Physicists whose information transfer framework inspired the ITM

## Topics
- [[inflation]] — ITM analysis of price level changes and monetary policy

## Sources
- [[2013-04-batch]] — April 2013: founding posts establishing the ITM framework

## Synthesis
- [[framework-evolution]] — How the ITM evolved from 2013 to 2023
```

Updated on every ingest or page creation. The LLM reads this first when answering queries.

## log.md

Append-only chronological record. Newest entries at bottom.

```markdown
## [YYYY-MM-DD] operation | description
```

Operations: `ingest`, `query`, `lint`, `create`, `update`

Example:
```markdown
## [2026-04-07] ingest | April 2013 batch (8 posts) — established ITM framework
## [2026-04-07] create | concepts/information-transfer-model.md
```

Parseable: `grep "^## \[" wiki/log.md | tail -5`

## Workflows

### Ingest (chronological order, one post at a time)
Sources are ingested in chronological order because posts build on each other. Each post is read individually and its content **synthesized** into existing wiki pages.

1. Read source post
2. Identify which concept, entity, and topic pages the post adds to (or whether a new page is needed)
3. **Integrate** new content into those pages — write coherent articles, not source-reference lists
4. Add the raw post path to the page's frontmatter `sources:` list
5. Copy any referenced images from `raw/YYYY/MM/media/` to `wiki/media/YYYY-MM/`
6. Update `wiki/index.md` if new pages were created
7. Append entry to `wiki/log.md`
8. Do NOT create standalone source summary pages — cite `raw/` posts directly

### Query
1. Read `wiki/index.md` to find relevant pages
2. Read those pages
3. Synthesize answer with citations to both wiki pages and source posts
4. Optionally file valuable answers as new pages in `wiki/synthesis/` or `wiki/topics/`

### Lint
Periodically check for:
- Contradictions between pages
- Stale claims superseded by newer sources
- Orphan pages (no inbound wikilinks)
- Concepts mentioned but lacking their own page
- Missing cross-references
- Gaps that suggest new sources to seek out

## Conventions

- When a new concept first appears in the blog, create a concept page for it
- When a concept page already exists and a new source adds to it, update the page and add the source to its `sources` list
- Keep source summaries factual — save interpretation and synthesis for concept/topic/synthesis pages
- Use relative links to raw sources: `[title](../raw/YYYY/MM/slug.md)`
- The overview page should be updated periodically as the wiki grows to reflect the current state of understanding
