# CLAUDE.md — d0ngfann.github.io

## Project Overview
Personal portfolio and journal site for a student. Primary purpose is showcasing projects and experiences (portfolio), with secondary use as a personal record/blog. The site owner is not a developer — Claude handles all code, design, and technical implementation. The owner provides content and direction.

## Tech Stack
- Jekyll static site generator
- Hydejack v9 theme (via `jekyll-remote-theme: hydecorp/hydejack@v9`)
- Hosted on GitHub Pages, deployed via GitHub Actions (`.github/workflows/jekyll.yml`)
- Live URL: https://d0ngfann.github.io

## Key Files
- `_config.yml` — site-wide settings, theme config, navigation, plugins
- `_posts/` — blog/journal posts (filename must follow `YYYY-MM-DD-title.md`)
- `about.md` — personal intro page
- `blog.md` — blog index page
- `projects.md` — projects showcase page
- `resume.md` — resume / CV page
- `til.md` — TIL (Today I Learned) page
- `review.md` — reviews page
- `Gemfile` — Ruby gem dependencies

## Site Menu (Navigation)
1. Blog — general posts
2. Projects — project showcase
3. TIL — short learning notes
4. Review — book/course/tool reviews
5. Resume — CV and background
6. About — personal intro

## Content Language
- Primary language: **English**
- Korean may appear occasionally (mixed is okay, but English is the default)

## Blog Post Format
```
---
layout: post
title: "Post Title"
date: YYYY-MM-DD
---

Content here.
```

## How to Work With This Project
- The owner provides content (text, ideas, what they want) — Claude does all the implementation
- Keep explanations non-technical; avoid jargon when communicating with the owner
- Prefer editing existing files over creating new ones unless clearly necessary
- Always add new files to the `exclude` list in `_config.yml` if they are not meant to be published as site pages (e.g., CLAUDE.md, README.md)
- Stick with the Hydejack theme — do not suggest switching themes
- Keep the site clean and minimal; avoid unnecessary complexity

## Current Theme Settings
- Accent color: `rgb(79,177,186)`
- Theme color: `rgb(25,55,71)`
- Dark mode: dynamic (sunrise 6, sunset 18)
