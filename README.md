# Vibe Code Starter

A lightweight MVP starter kit for vibe coding with AI coding agents such as Claude Code, Gemini CLI, and local/on-prem agents.

이 저장소는 AI 코딩 에이전트와 함께 작은 MVP를 빠르게 만들기 위한 스타터킷입니다.

## What this is

This is not a large framework.

It is a small starter kit for quickly choosing the right first project shape.

- no-install-html: single-file browser MVP
- local-tkinter: local PC / on-prem friendly desktop MVP
- Vite/React: deployable web app MVP

## MVP Principle

MVP does not mean a toy screen.

MVP means the smallest version where the core user flow works end-to-end.

A good MVP should let the user:

1. enter or provide something
2. run one clear action
3. see a useful result
4. reset or try again

## Available Templates

### no-install-html

Use this when you want the fastest local MVP.

- No npm install
- No build step
- Open index.html directly in a browser
- Good for quick UI and interaction checks

### local-tkinter

Use this for local PC or on-prem workflows.

- Python-based local GUI
- Good for internal tools
- Good for local/on-prem API workflows
- Do not expose API keys in frontend code

### Vite/React

Use this when the MVP may grow into a deployable web app.

- Requires npm install
- Good for frontend apps
- Good for Vercel or web deployment

## Agent Guidance

Before starting a new project, ask:

> Do you want to use this starter kit as the base, or should I adapt the current project structure?

Do not assume this starter kit should always be used.

If the user says yes:

- use this starter kit workflow
- choose the right template for the target environment
- keep the first version lightweight but end-to-end usable

If the user says no:

- preserve the existing project structure
- apply only the MVP principles where helpful

## Security Notes

- Do not hardcode API keys
- Do not expose secrets in browser-side JavaScript
- For local or on-prem API calls, prefer environment variables or local config files excluded from Git
- Keep internal endpoints, app IDs, and credentials out of public repositories

## Quick Start

For no-install HTML:

```text
open no-install-html/index.html
```

For Vite/React:

```bash
npm install
npm run dev
```

## Conclusion

This starter kit is meant to reduce project-starting friction.

The goal is not to make the smallest possible screen.
The goal is to create the smallest useful end-to-end flow.
