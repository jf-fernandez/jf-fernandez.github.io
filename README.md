# jf-fernandez.github.io

Personal website of **Julián F. Fernández** — biomolecular modeling & AI for drug
discovery. Live at <https://jf-fernandez.github.io>.

## Stack

Static [Jekyll](https://jekyllrb.com/) site, built and served automatically by
GitHub Pages from the `main` branch (root).

## Structure

| Path | Contents |
|------|----------|
| `index.html` | Home — the Publications list |
| `contact/` | Contact page |
| `_data/publications.yml` | The chronological list (papers, talks, blogposts) |
| `_layouts/default.html` | Sidebar + page shell |
| `assets/` | CSS and images |
| `_config.yml` | Site config and public profile links |

## Adding an entry

Add a block to `_data/publications.yml` (most recent first):

```yaml
- when: "2026"
  type: paper            # paper · conference talk · conference presentation · blogpost
  title: "Title here"
  venue: "Journal / venue (optional)"
  desc: "One or two sentences."
  link: "https://…"      # leave "" for no link
```

## Local preview

```bash
gem install jekyll
jekyll serve
# → http://127.0.0.1:4000
```
