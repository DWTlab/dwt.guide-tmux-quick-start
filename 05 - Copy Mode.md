---
tags:
  - tmux
  - cheatsheet
  - copy-mode
---

# TMUX Copy Mode

TMUX's copy mode allows you to scroll back through the buffer and copy text.

## Entering and Exiting Copy Mode

| Keystroke | Description |
| --- | --- |
| `Ctrl+b [` | Enter copy mode. |
| `q` | Exit copy mode. |

## Navigation in Copy Mode

| Keystroke | Description |
| --- | --- |
| `Up` or `k` | Move up one line. |
| `Down` or `j` | Move down one line. |
| `Left` or `h` | Move left one character. |
| `Right` or `l` | Move right one character. |
| `w` | Move to the next word. |
| `b` | Move to the previous word. |
| `g` | Go to the top of the buffer. |
| `G` | Go to the bottom of the buffer. |
| `Ctrl+u` | Move up half a screen. |
| `Ctrl+d` | Move down half a screen. |

## Text Selection and Copying

| Keystroke | Description |
| --- | --- |
| `space` | Start selection. |
| `Enter` | Copy selection and exit copy mode. |
| `y` | Copy selection. |
| `Ctrl+w` | Copy the current word. |
| `v` | Select the entire line. |
| `V` | Select the entire line (and move to the next). |
| `C` | Select the current word. |
| `D` | Select to the end of the line. |
| `Y` | Copy the entire line. |

## Pasting

| Keystroke | Description |
| --- | --- |
| `Ctrl+b ]` | Paste the most recent buffer. |
