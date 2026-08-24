# agent-guidelines

A curated source of development guidelines and an indexed wiki for AI agents.

---

## Structure

```
/
├── raw/           # Canonical, curated source material
│   └── guidelines/ # Rules and decisions before wiki indexing
└── wiki/          # Derived, normalized pages optimized for retrieval
```

`raw/` is the source of truth. Keep its content precise and well-structured;
it is not a dump for unprocessed notes. Generate or update `wiki/` from it
without changing the meaning of the source.

---

## Wiki Index

> Pages in `wiki/` are generated from the curated sources in `raw/`.
> Each file covers one concept, pattern, or decision and is optimized for
> search and LLM retrieval.

| File | Topic |
|------|-------|
| *(empty — add pages as needed)* | |

---

## Curated Sources

> Development rules belong in `raw/guidelines/` and are the canonical input
> for the corresponding wiki pages.

| File | Scope |
|------|-------|
| [coding.md](raw/guidelines/coding.md) | General coding standards |
| [architecture.md](raw/guidelines/architecture.md) | Architecture decisions |
| [testing.md](raw/guidelines/testing.md) | Testing practices |
| [git.md](raw/guidelines/git.md) | Git workflow |
| [ai-usage.md](raw/guidelines/ai-usage.md) | How to work with AI agents |

---

## Update Flow

1. Curate and validate the source in `raw/`.
2. Split information into atomic pages in `wiki/`.
3. Preserve links from each wiki page to its raw source.
4. Update the wiki whenever its source changes.

---

## Conventions

- **raw/** — canonical source, explicit headings, imperative rules where applicable
- **raw/guidelines/** — curated development rules and decisions
- **wiki/** — one file per concept, concise, stable headings, search-friendly terms
- All files are Markdown
- Keep nesting limited to the `raw/guidelines/` source group
