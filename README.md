# polsys.net

Personal academic home page of Bernhard Rieder, built with [Hugo](https://gohugo.io) and published on GitHub Pages.

## Updating content

| What | Where |
|---|---|
| Publications | `data/publications.yaml` |
| Research tools (current and archive) | `data/tools.yaml` |
| Mac apps (`hidden: true` keeps one off the site) | `data/apps.yaml` |
| Tutorial videos | `data/videos.yaml` |
| Home, research, software and apps texts | `content/*.md` |
| Links, email, talks playlist | `hugo.toml` |

The latest blog posts and the talks playlist are fetched when the site is built. The site is rebuilt on every push to `main` and once a day, so new posts and talks appear without a commit.

## Local preview

```bash
hugo server
```

Then open http://localhost:1313.
