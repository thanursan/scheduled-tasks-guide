# ChatGPT Scheduled Tasks: A Practical Guide

A concise, task-oriented guide to planning and maintaining recurring tasks in ChatGPT.

**Live site:** https://thanursan.github.io/scheduled-tasks-guide/

## About the project

A practical documentation project demonstrating a docs-as-code workflow. Content is written in Markdown, maintained with Git and published as a static documentation site.

## Technology stack

| Tool | Purpose |
|---|---|
| Markdown | Documentation authoring |
| Zensical | Static documentation site generation |
| Git | Version control |
| GitHub | Source code hosting |
| GitHub Actions | Automated build and deployment |
| GitHub Pages | Website hosting |

## Workflow

1. Write and edit documentation in Markdown.
2. Preview changes locally using `zensical serve`.
3. Build the site using `zensical build`.
4. Stage and commit changes with Git.
5. Push commits to GitHub.
6. GitHub Actions automatically builds and deploys the site to GitHub Pages.

## Run locally

Install dependencies with `py -m pip install -r requirements.txt`.

Preview locally with `zensical serve`.

Build the site with `zensical build`.

The generated website is written to `site/`.

## Project structure

- `.github/workflows/` — automated deployment workflow
- `docs/` — Markdown documentation
- `requirements.txt` — project dependencies
- `zensical.toml` — site configuration

## Scope

This is an independent learning project. It is not affiliated with or endorsed by OpenAI.
