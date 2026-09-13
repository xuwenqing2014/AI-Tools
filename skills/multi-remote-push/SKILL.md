---
name: multi-remote-push
description: Commit and push this repository to its GitHub, Codeberg, and Hugging Face remotes when the user asks to publish changes.
---

# Multi-Remote Push

Use this skill for Git publishing tasks in this repository.

The repository has three required destinations: `origin` (GitHub), `codeberg` (Codeberg), and `huggingface` (Hugging Face). After creating a requested commit, push the current branch to all three remotes and verify that every push succeeds.

Before pushing, inspect `git remote -v` and the current branch. Preserve all remotes and do not force-push, delete branches, or change remote URLs unless the user explicitly requests it.
