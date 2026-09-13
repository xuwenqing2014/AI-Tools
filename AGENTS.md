# Repository Instructions

## Git remotes

This repository is mirrored to three remotes:

- `origin`: `https://github.com/xuwenqing2014/AI-Tools.git`
- `codeberg`: `https://codeberg.org/mintnow/AI-Tools.git`
- `huggingface`: `https://huggingface.co/mintnow/AI-Tools.git`

Whenever a change is committed and the user asks to push it, push the same branch to all three remotes. Verify that every push succeeds. Do not remove, rename, or overwrite any remote without explicit user approval.

Typical push commands:

```bash
git push origin <branch>
git push codeberg <branch>
git push huggingface <branch>
```
