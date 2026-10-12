---
# Notes for writing log-it posts. Not published.
_build: { render: never, list: never }
---

## Add a post

```bash
hugo new content log-it/02-journey/02-my-post-title/index.md
```

1. Pick a folder (`01-my-papers`, `02-journey`, `03-deep-learning`, …) and give the post a numbered folder; the number sets the order and never shows in the link.
2. Write in `index.md`. Put images and a `.bib` file in the same folder; cite with `\cite{key}`.
3. Preview with `hugo server -D`, then delete `draft: true` and push to `main`.

## Add a folder

Create `content/log-it/06-name/_index.md` with a `title` and `description`.
