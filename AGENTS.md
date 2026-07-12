# AGENTS.md

This is a public personal AI engineering learning fork.

## Purpose

- Maintain public-safe AI engineering learning/reference material.
- Add polished notes, mini-labs, examples, and reusable project artifacts.
- Keep the fork easy to pull from upstream when needed.

## Rules

- If the private `nckhemanth/workspace` hub is available, read its
  `AGENTS.md` and `context/repos/AI-Engineering/` notes before changing this
  repo. Treat that workspace as the primary continuity source.
- Do not assume changes are intended for the upstream project.
- Do not create upstream pull requests unless the repo owner explicitly asks.
- If the private workspace is available, keep rough notes, private planning,
  drafts, and other private material in
  `workspace/context/repos/AI-Engineering/personal/`.
- If the private workspace is unavailable, `personal/` in this repo is a
  temporary ignored fallback only.
- Do not commit secrets, `.env` files, tokens, cookies, or private material.
- Prefer small practical additions over large restructuring.
- Preserve the repo's readable field-guide style.

## Learning Content Standard

When adding public learning content, keep it concise and useful:

- intuition / mental model
- practical example or pseudocode when it improves understanding
- failure modes and tradeoffs
- metrics, evals, cost, security, or reliability notes when relevant
- project connection
- 60-second interview answer or speakable summary

Put heavier runnable work in `labs/` instead of bloating concept chapters.

## Handoff

If continuing another agent's work:

1. First check the private workspace hub when available:
   `../workspace/AGENTS.md` and
   `../workspace/context/repos/AI-Engineering/`.
2. Read `README.md` for the public repo spine.
3. Read `PROGRESS.md` for public fallback focus and next tasks.
4. Check `git status --short --branch`.
5. Make small, reviewable changes.
6. After work, update the workspace changelog if available. Update
   `PROGRESS.md` only when the public next tasks or focus changed.

Do not copy private workspace notes or planning details into this public repo.
Promote only polished, reusable learning material.
