# Flowstate Design System

Minimal design-system codebase for **Flowstate**, a productivity app (used as the
demo brand in the Claude Design course, Lecture 2).

This repo exists purely so you can practice Claude Design's **"import from GitHub"**
flow: link this repo as a design system, then generate a project and watch Claude
pick up these colors, type scale, and component patterns instead of using generic
defaults.

## What's in here

- `src/styles/tokens.css` — color palette, typography scale, spacing scale as CSS variables
- `src/components/Button.jsx` — primary/secondary button variants using the tokens
- `src/components/Card.jsx` — a basic card component
- `src/components/Badge.jsx` — a small status badge component

## How to use this in the demo

1. Create a new repository on GitHub (e.g. `flowstate-design-system`).
2. Upload all files in this folder, preserving the folder structure
   (`src/styles/...`, `src/components/...`).
3. In Claude Design, when creating or editing a project, choose **"Link a
   codebase"** / **"Import from GitHub"** and point it at this repo.
4. Prompt something like: *"Design a settings page for Flowstate using our
   existing design system."* — and see the tokens and component patterns show
   up in the output.
