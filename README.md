# Dev Log

A running record of what I work on, learn, and read as a developer. One entry per day, kept in [`logs/`](logs).

Entries are scaffolded each morning by [Helios](https://github.com/shubhransh-gupta/helios), a small CLI I wrote for exactly this. It creates the day's file and commits it only when there is something new, so the history reflects real entries rather than empty churn.

## Layout

```
logs/
  2026-08-12.md
  2026-08-13.md
  ...
```

Every entry has the same three sections:

| Section | What goes in it |
|---------|-----------------|
| **Focus** | What I actually worked on |
| **Learned** | Something new, however small |
| **Links** | PRs, articles, and repos worth keeping |

## Adding to today's entry

```bash
helios log "Tracked down a race condition in the upload queue"
```

That appends the note, timestamps it, and commits.

## Why keep this

Writing down the day's work forces me to articulate what I did and why, which is a different skill from doing it. The archive also turns out to be a genuinely useful thing to search when I hit a problem I have seen before.

---

Tooling: [Helios](https://github.com/shubhransh-gupta/helios) · MIT
