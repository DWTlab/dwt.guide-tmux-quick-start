---
tags:
  - tmux
  - cheatsheet
  - panes
---

# TMUX Pane Management

A TMUX pane is a single command prompt within a window. You can have multiple panes in a single window.

## Pane Commands

| Command | Description |
| --- | --- |
| `tmux split-window` | Split the current pane horizontally. |
| `tmux split-window -h` | Split the current pane vertically. |
| `tmux select-pane -t <number>` | Switch to a pane by its number. |
| `tmux kill-pane -t <number>` | Kill a pane by its number. |

## Pane Keystrokes

| Keystroke | Description |
| --- | --- |
| `Ctrl+b %` | Split the current pane vertically. |
| `Ctrl+b "` | Split the current pane horizontally. |
| `Ctrl+b o` | Switch to the next pane. |
| `Ctrl+b q` | Display pane numbers. |
| `Ctrl+b x` | Close the current pane. |
| `Ctrl+b <arrow-key>` | Switch to the pane in the direction of the arrow key. |
| `Ctrl+b z` | Toggle zoom for the current pane. |
| `Ctrl+b [` | Enter copy mode. |
| `Ctrl+b ]` | Paste the most recent buffer. |
| `Ctrl+b {` | Swap the current pane with the previous pane. |
| `Ctrl+b }` | Swap the current pane with the next pane. |
| `Ctrl+b space` | Cycle through the available pane layouts. |
