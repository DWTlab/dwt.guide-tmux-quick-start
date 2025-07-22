---
tags:
  - tmux
  - cheatsheet
  - getting-started
---

# Getting Started with TMUX

This page covers the absolute basics to get you started with TMUX.

## Starting and Attaching

| Command | Description |
| --- | --- |
| `tmux` | Start a new TMUX session. |
| `tmux new -s <session-name>` | Start a new named TMUX session. |
| `tmux ls` | List all running TMUX sessions. |
| `tmux a` | Attach to the last used session. |
| `tmux a -t <session-name>` | Attach to a specific named session. |

## Basic Keystrokes

All TMUX commands are prefixed with a special key combination. By default, this is `Ctrl+b`.

| Keystroke | Description |
| --- | --- |
| `Ctrl+b d` | Detach from the current session. |
| `Ctrl+b %` | Split the current pane vertically. |
| `Ctrl+b "` | Split the current pane horizontally. |
| `Ctrl+b o` | Switch to the next pane. |
| `Ctrl+b q` | Display pane numbers. |
| `Ctrl+b x` | Close the current pane. |
| `Ctrl+b c` | Create a new window. |
| `Ctrl+b w` | List all windows. |
| `Ctrl+b n` | Switch to the next window. |
| `Ctrl+b p` | Switch to the previous window. |
| `Ctrl+b ,` | Rename the current window. |
| `Ctrl+b &` | Close the current window. |
