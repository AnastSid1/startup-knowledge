# Contributing to Startup Knowledge

Thank you for helping improve this open knowledge base. The goal is simple: make startup fundamentals clearer, more practical, and more useful for founders and learners.

Anyone can contribute — founders, operators, investors, students, and curious readers.

## Ways to contribute

This repo works like an [awesome list](https://github.com/sindresorhus/awesome): the root [README](README.md) is the browsable index (jump links + curated resources), and deeper guides live under [`guides/`](guides/).

1. **Add curated links** — high-quality resources under the right README section (short description, no fluff).
2. **Fix mistakes** — correct inaccurate definitions, outdated ranges, or broken links.
3. **Improve clarity** — rewrite confusing sections without changing the meaning.
4. **Add practical examples** — realistic numbers, scenarios, and “how founders use this.”
5. **Add related concepts** — new guide pages that fill an important gap, then link them from the README.
6. **Improve navigation** — better cross-links, glossary entries, and README anchors.
7. **Open issues** — report gaps, request topics, or flag ambiguity.

### Awesome-list link style

Prefer:

```markdown
- [Resource name](https://example.com) — one-line why it is useful
```

Only add resources you would recommend to a founder. Prefer primary sources (YC, essays, reputable operator writing) over thin SEO posts.

## Contribution standards

Every concept page should help a smart beginner actually use the idea. Prefer substance over slogans.

### Content quality

- Explain **what it means**, **why it matters**, and **when founders should care**.
- Include practical examples with realistic startup numbers when useful.
- Distinguish commonly confused concepts.
- Use formulas only when they improve understanding.
- Cross-link related pages instead of repeating entire explanations.
- Write original explanations. Summarize outside sources; do not paste them.
- Avoid hype, motivational filler, and unnecessary jargon.
- Prefer precise modern startup language over vague corporate language.

### Formatting

Use this structure for new concept pages unless a different structure is clearly better:

```markdown
# Concept Name

> One-sentence definition in plain language.

## What it means
## Why it matters
## When founders should care
## How it works
## Practical example
## Common confusion
## Related concepts
## Further reading
```

Additional guidelines:

- Prefer relative Markdown links between pages.
- Use tables for comparisons when they help.
- Keep headings scannable.
- Avoid emoji-heavy formatting.
- Add new terms to [`guides/glossary/INDEX.md`](guides/glossary/INDEX.md).
- Update the relevant section `README.md` and the root [`README.md`](README.md) table of contents when adding pages.

### Sources

Good sources include Y Combinator, Paul Graham essays, Sequoia, a16z, First Round Review, Stripe Atlas/Press, OpenView, reputable academic/business research, and well-regarded startup books.

When citing:

- Link to the original source when possible.
- Prefer primary or widely trusted secondary sources.
- Do not invent citations.
- Do not copy copyrighted text verbatim.

## How to submit a change

1. Fork the repository (or create a branch if you have write access).
2. Create a focused branch for your change.
3. Make the edit.
4. Open a pull request with:
   - what you changed
   - why the change improves the knowledge base
   - any sources you relied on
5. Keep PRs focused. One concept improvement is better than a giant mixed PR.

## Issue guidelines

When opening an issue, say:

- which page or concept is involved
- what is wrong, missing, or unclear
- what a better version would look like (if you know)

## Scope

This repository is a **founder knowledge base**, not:

- legal advice
- personalized fundraising advice
- investment advice
- a hype blog
- a dump of unreviewed AI-generated stubs

If a topic needs professional advice (law, tax, securities), say so clearly and keep the page educational.

## Review criteria

Maintainers look for:

- accuracy
- clarity
- practical usefulness
- consistent structure
- good cross-linking
- respectful, inclusive tone

## License

By contributing, you agree that your contributions are licensed under [CC BY 4.0](guides/LICENSE).

## Questions

Open an issue if you are unsure whether a topic belongs here or how to structure a page. Ambiguity is normal — ask.
