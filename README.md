# agent-guidelines

A Karpathy-style wiki for AI development guidelines.  
Raw, minimal, and structured for LLM consumption.

---

## Structure

```
/
├── wiki/          # Curated wiki pages (one topic per file)
├── raw/           # Raw notes, transcripts, references (unprocessed)
└── guidelines/    # Distilled development guidelines for AI agents
```

---

## Wiki Index

> Pages live in `wiki/`. Each file covers one concept, pattern, or decision.

| File | Topic |
|------|-------|
| *(empty — add pages as needed)* | |

---

## Guidelines Index

> Distilled rules in `guidelines/`. These are fed directly to AI agents.

| File | Scope |
|------|-------|
| [coding.md](guidelines/coding.md) | General coding standards |
| [architecture.md](guidelines/architecture.md) | Architecture decisions |
| [testing.md](guidelines/testing.md) | Testing practices |
| [git.md](guidelines/git.md) | Git workflow |
| [ai-usage.md](guidelines/ai-usage.md) | How to work with AI agents |

---

## Raw Index

> Unprocessed material lives in `raw/`. Promote content to `wiki/` once curated.

*(empty — add raw notes as needed)*

---

## Conventions

- **wiki/** — one file per concept, present tense, concise
- **raw/** — free-form, dated if possible (`YYYY-MM-DD-topic.md`)
- **guidelines/** — imperative tone, bullet lists, no fluff
- All files are Markdown
- No nested directories unless strictly necessary
