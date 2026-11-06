# ChatGPT Scheduled Tasks: A Practical Guide

A concise, task-oriented guide to planning and maintaining recurring or one-time tasks in ChatGPT.

This project is built with [Zensical](https://zensical.org/) and Markdown. The source is version-controlled with Git and can be published to GitHub Pages using the workflow in `.github/workflows/docs.yml`.

## Run locally

Install the pinned documentation tool:

```powershell
py -m pip install -r requirements.txt
```

Preview the documentation:

```powershell
zensical serve
```

Build the static site:

```powershell
zensical build
```

The generated site is written to `site/`.

## Project structure

```text
.
├── .github/
│   └── workflows/
│       └── docs.yml
├── docs/
│   ├── index.md
│   ├── create-a-task.md
│   ├── prompt-design.md
│   └── case-study-misha-monitor.md
├── requirements.txt
└── zensical.toml
```

## Scope

This is an independent learning project. It is not affiliated with or endorsed by OpenAI. Product interfaces and capabilities can change; consult the official ChatGPT Help Center for current behaviour.
