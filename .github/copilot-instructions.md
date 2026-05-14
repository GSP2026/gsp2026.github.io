# GSP Workshop 2026 — Workspace Guidelines

This is the official website for the Graph Signal Processing Workshop 2026, built with [Jekyll](https://jekyllrb.com/) + [al-folio theme](https://github.com/alshedivat/al-folio).

## Quick Start

### Local Development
Run the local development server using Docker:
```powershell
./run_local.ps1
```
This spins up a Docker container and serves the site at `http://localhost:8080` with live reload.

**First run note**: Initial build takes several minutes to download dependencies.

### Deployment
Push to `main`/`master` and GitHub Actions automatically builds and deploys to GitHub Pages (`gh-pages` branch). Track deployment status in the [Actions tab](https://github.com/gsp2026/gsp2026.github.io/actions).

## Project Structure

| Folder | Purpose |
|--------|---------|
| `_pages/` | Content pages (about, schedule, registration, venue, call_for_papers, submit) |
| `_data/` | YAML config for dynamic content (staff, speakers, venues, coauthors) |
| `_includes/` | Reusable HTML components (header, footer, speaker cards, staff lists) |
| `_layouts/` | Jekyll templates for pages, posts, CV, archives |
| `assets/` | CSS, JavaScript, images, PDFs, slides |
| `_plugins/` | Custom Jekyll extensions |
| `bin/` | Build and deployment scripts |

## Common Tasks

### Update Speakers or Organizing Committee
Edit [`_data/staff.yml`](../_data/staff.yml). Each person entry includes:
```yaml
- name: "Full Name"
  affiliation: "University/Organization"
  url: "https://personal-website.com"
  image: assets/img/people/lastname.jpg
  topic: "Talk Title" # for speakers only
  abstract: "Short abstract" # for speakers only
  bio: "Paragraph about the person" # optional
```

The includes files (`_includes/staff.html`, `_includes/speakers.html`, `_includes/local_team.html`) automatically render these.

### Edit Event Pages
Pages are markdown files in [`_pages/`](../_pages/):
- **schedule.md** — Program, session times, speaker order
- **registration.md** — Registration deadlines, payment info, links
- **call_for_papers.md** — CFP dates, topics, submission instructions
- **venue.md** — Location, accommodation, travel directions
- **about.md** — Event overview and key information

Each page uses Jekyll front matter:
```yaml
---
layout: page
title: Page Title
permalink: /url-path/
nav: true
nav_order: 3
---
```

### Add News/Announcements
Create a new `.md` file in [`_news/`](../_news/) with front matter like:
```yaml
---
layout: post
date: 2026-04-15
inline: true
---
Your announcement text here.
```

### Upload Images
- **Speaker/staff photos**: `assets/img/people/`
- **Banner/hero images**: `assets/img/banners/`
- **Content images**: `assets/img/` (organize in subfolders as needed)

YAML reference: Use relative paths like `assets/img/people/lastname.jpg`.

## Content Conventions

| Element | Pattern |
|---------|---------|
| **Markdown links** | `[Link text](https://url.com)` or relative paths `[text](../path/file.md)` |
| **Page URLs** | Set via `permalink:` in front matter; must start/end with `/` |
| **Navigation order** | Use `nav_order:` (integer) in front matter for sidebar menu |
| **Italics/emphasis** | Use `*italic*` or `**bold**` in markdown |
| **Lists** | Use `-` for unordered, spaces for proper indentation |
| **YAML indentation** | Use **2 spaces** (never tabs); check syntax carefully |

## Design Principles

- **Content-first**: Pages should be readable as plain markdown; HTML is a fallback
- **DRY (Don't Repeat Yourself)**: Reuse includes and data files; avoid duplicating content
- **Accessible**: Use semantic HTML, alt text for images, proper heading hierarchy
- **Mobile-responsive**: Test layouts on phone/tablet sizes
- **Minimal styling**: Keep custom CSS in `_sass/` organized by purpose

## Build System

**Jekyll 4.x** processes:
1. Reads source files (`_pages/`, `_data/`, templates)
2. Renders markdown with Liquid templating
3. Outputs static HTML to `_site/` folder

**Custom plugins** in `_plugins/`:
- `external-posts.rb` — Pulls external blog posts
- `hideCustomBibtex.rb` — Bibliography processing

## Important Notes

- **Don't edit `_site/` directly** — it's auto-generated; changes will be overwritten during build
- **YAML syntax matters** — Invalid YAML (bad indentation, unquoted special chars) breaks the build
- **Image paths** — Always use relative paths in YAML; Jekyll handles URL construction
- **Special characters in YAML** — Quote values containing `:`, `{`, `}`, `#`, etc.

## Useful References

- [LOCAL_GUIDE.md](../LOCAL_GUIDE.md) — Troubleshooting Docker build issues
- [README.md](../README.md) — Project overview and al-folio theme documentation
- [_config.yml](../_config.yml) — Site-wide settings (title, email, social links, theme options)
- [Jekyll Docs](https://jekyllrb.com/docs/) — Official Jekyll documentation
- [Liquid Syntax](https://shopify.github.io/liquid/) — Template language reference

## Getting Help

For template/theme questions, refer to the [al-folio documentation](https://github.com/alshedivat/al-folio). For Jekyll-specific issues, check the [Jekyll docs](https://jekyllrb.com/docs/).
