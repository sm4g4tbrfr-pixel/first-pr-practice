# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

`first-pr-practice` is a practice repository for learning the basic git/GitHub PR workflow (init → commit → push → PR) with Claude Code. It intentionally contains no application code, build system, tests, or lint configuration — there is nothing to build, run, or test. Do not assume or invent tooling that isn't present.

Note: the repository name and its own README state that it contains no confidential company information, despite living under a company-named local directory path.

## Workflow

The intended usage, per the README, is:

1. Create a branch: `git checkout -b <branch-name>`
2. Make changes and commit: `git commit -m "説明"`
3. Push and open a PR: `git push -u origin <branch-name>` → `gh pr create`

## Structure

- [README.md](README.md) — repository purpose and usage instructions (in Japanese)
- [.gitignore](.gitignore) — excludes macOS `.DS_Store`, Obsidian workspace/cache files, and local `.claude/` session files
