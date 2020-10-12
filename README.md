
> Hecks

> An easy to use terminal-based hex editor written in Python.

# Usage

## Global key bindings

- Escape: Cancel any active prompts and go back to edit mode.
- Ctrl-C: Quit.

## Editing (byte and ASCII)

- Ctrl-B: Change numerical base.
- Ctrl-S: Search.
- Ctrl-G: Goto byte.
- Ctrl-R: Reload file.
- Ctrl-W: Write file.

- Up/down/left/right: Move cursor.
- Pgup/pgdn: Previous/next page.

- Tab: Toggle between byte and ASCII editing.
- Insert: Toggle overwrite mode.
- Ctrl-Q: Capture next key press and insert as character.

- Backspace: Delete (or zero) the byte before the cursor and move the cursor left.
- Delete: Delete (or zero) the byte under the cursor.

## Editing (byte)

- Space: Clear active numerical input

## Search

- Ctrl-S: Find next match.
- Ctrl-R: Find previous match.
- Enter: Exit search mode.
