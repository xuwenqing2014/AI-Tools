---
name: dual-remote-push
description: Commit and push this repository to both its GitHub and Codeberg remotes when the user asks to publish changes.
---

# Dual Remote Push

Use this skill for Git publishing tasks in this repository.

The repository has two required mirrors: `origin` (GitHub) and `codeberg` (Codeberg). After creating a requested commit, push the current branch to both remotes and verify that each push succeeds.

Before pushing, inspect `git remote -v` and the current branch. Preserve both remotes and do not force-push, delete branches, or change remote URLs unless the user explicitly requests it.

