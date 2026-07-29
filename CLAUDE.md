# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

task-board is a task board (kanban-style) application. The project is in its initial setup stage — no source code exists yet. Planned tech stack: **React + TypeScript** for the frontend, with a Node.js backend to be added if/when needed.

As the codebase grows, this file should be updated with concrete build/lint/test commands and architecture notes once they exist. Do not invent commands that aren't backed by actual config files (`package.json` scripts, etc.) — check for them before documenting them here.

## Git Workflow Rules

- **Every time code is changed, push the change to GitHub.** After completing an edit (or a small logical group of edits), commit and push immediately rather than batching many unrelated changes into one push.
- Remote: `origin` → https://github.com/koji4243/task-board.git, branch `main`.
- Write clear, concise commit messages describing *why* the change was made, not just what changed.
- Do not force-push, rewrite history, or skip commit hooks unless the user explicitly asks for it.
- Only commit and push when the user has approved the change (or has given standing approval for autonomous work) — confirm before pushing if there's any doubt.
