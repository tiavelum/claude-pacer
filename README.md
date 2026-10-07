# claude-pacer

claude-pacer runs long Claude work unattended, mostly overnight, in chunks that start only when the 5-hour and weekly usage limits of a Pro or Max plan leave room for them. It is for someone who wants Claude to work while they sleep without drawing on usage credits or using up the week's limit before the day starts.

## What it is for

Long work left running on its own either stops at a usage limit in the middle of a task or spends the weekly limit that daytime use needs. claude-pacer splits the work into chunks and checks the limits before each, so a limit hit loses at most the chunk in progress.

It does not use usage credits or API-key billing, schedule anything other than Claude work, or guarantee that no limit is ever hit.

## Getting started

The runner is not built yet, so there is nothing to install or run. Read the tracking issue [tiavelum/claude-pacer#1](https://github.com/tiavelum/claude-pacer/issues/1) first: it holds the design, the facts it rests on, and the steps in order.

## Files

| Path | Contains |
|---|---|
| `README.md` | This description |
| `project-instructions.md` | The rules Claude follows when working in this repository |
| `CLAUDE.md` | Imports `project-instructions.md` for Claude Code |
| `.editorconfig` | Formatting baseline for every file |
| `.gitignore` | Files git leaves out |
| `LICENSE` | The license |

## License

MIT. See [LICENSE](LICENSE).
