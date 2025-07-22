---
tags:
  - tmux
  - cheatsheet
  - sessions
---

# TMUX Session Management

A TMUX session is a single process that manages one or more windows. You can detach from a session and leave it running in the background, then re-attach to it later.

## Session Commands

| Command | Description |
| --- | --- |
| `tmux new` | Create a new session. |
| `tmux new -s <name>` | Create a new session with the given name. |
| `tmux ls` | List all existing sessions. |
| `tmux a` | Attach to the most recently used session. |
| `tmux a -t <name>` | Attach to a session with the given name. |
| `tmux rename -t <old-name> <new-name>` | Rename a session. |
| `tmux kill-session -t <name>` | Kill a session with the given name. |
| `tmux kill-server` | Kill all sessions. |

## Session Keystrokes

| Keystroke | Description |
| --- | --- |
| `Ctrl+b d` | Detach from the current session. |
| `Ctrl+b s` | List all sessions. |
| `Ctrl+b $` | Rename the current session. |
