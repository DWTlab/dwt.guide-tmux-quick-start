---
tags:
  - tmux
  - cheatsheet
  - windows
---

# TMUX Window Management

A TMUX window is a single screen that can be split into multiple panes.

## Window Commands

| Command | Description |
| --- | --- |
| `tmux new-window` | Create a new window. |
| `tmux new-window -n <name>` | Create a new window with the given name. |
| `tmux list-windows` | List all windows in the current session. |
| `tmux select-window -t <number>` | Switch to a window by its number. |
| `tmux rename-window <new-name>` | Rename the current window. |
| `tmux kill-window -t <number>` | Kill a window by its number. |

## Window Keystrokes

| Keystroke | Description |
| --- | --- |
| `Ctrl+b c` | Create a new window. |
| `Ctrl+b w` | List all windows. |
| `Ctrl+b n` | Switch to the next window. |
| `Ctrl+b p` | Switch to the previous window. |
| `Ctrl+b <number>` | Switch to a window by its number (e.g., `Ctrl+b 1`). |
| `Ctrl+b ,` | Rename the current window. |
| `Ctrl+b &` | Close the current window. |
| `Ctrl+b f` | Find a window by its name. |
| `Ctrl+b .` | Move a window to a different position. |
