# blog.kibb.dev

Personal blog for [kibb.dev](https://blog.kibb.dev) built with [Zola](https://www.getzola.org/) and a custom **burnt orange neon** theme inspired by [neon-tube](https://neon-tube.github.io).

## ⚡ Features

- **Burnt Orange Gas Palette**: Glowing `#ff5e3a` neon accents, obsidian glass backdrop, and subtle violet tones.
- **Pure CSS & Zero Bloat**: No JavaScript frameworks, no external CSS dependencies, sub-50ms builds.
- **Glassmorphism Header**: Sticky blurred navigation bar with glowing brand mark and pulse indicator.
- **Wordmark Glow**: Animated neon title with flickering letter effects.
- **Developer First**: Code blocks styled with Catppuccin Mocha syntax highlighting, clean typography, and tag filtering.
- **Atom Feeds**: Automatic feed generation for syndication.

## 🚀 Getting Started

### Prerequisites

- [Zola](https://www.getzola.org/documentation/getting-started/installation/) >= 0.23.0

### Run Locally

Start the local development server with live reload:

```bash
zola serve
```

Then visit [http://127.0.0.1:1111](http://127.0.0.1:1111) in your browser.

### Build

```bash
zola build
```

## 📁 Directory Structure

```text
.
├── config.toml           # Site configuration & neon theme settings
├── content/              # Blog posts and content pages
│   ├── _index.md         # Homepage
│   └── blog/             # Posts section
│       ├── _index.md
│       └── hello-world.md
└── themes/
    └── neon/             # Custom burnt orange neon theme
        ├── static/css/   # neon.css stylesheet
        ├── templates/    # Tera templates (base, index, page, section, tags, 404)
        └── theme.toml    # Theme metadata
```

## 📝 Writing Posts

Add new markdown files to `content/blog/`:

```markdown
+++
title = "Post Title"
date = 2026-09-21
description = "Brief post description"
taxonomies = { tags = ["tech", "systems"] }
+++

Post content goes here...
```
