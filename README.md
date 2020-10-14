
> An easy to use terminal-based hex editor written in Python.

***

**Warning!** This software is very much experimental and still has issues; use at your own risk.

# Usage

## Global key bindings

- Escape: Cancel any active prompts and go back to edit mode.
- Ctrl-C: Quit.
- Ctrl-L: Refresh screen.

## Editing (byte and ASCII)

Actions:

- Ctrl-E: Change endian.
- Ctrl-B: Change numerical base.
- Ctrl-S: Search.
- Ctrl-G: Goto byte.
- Ctrl-R: Reload file.
- Ctrl-W: Write file.

***

Cursor/scrolling:

- Up/down/left/right: Move cursor.
- Pgup/pgdn: Previous/next page.
- Ctrl-L: Scroll cursor to center/top/bottom.

***

Mode switching:

- Tab: Toggle between byte and ASCII editing.
- Insert: Toggle overwrite mode.
- Ctrl-Q: Capture next key press and insert as character.
- Ctrl-M: Modify current byte.
- Ctrl-N: Modify current byte in binary mode.

***

Editing:

- Backspace: Delete (or zero) the byte before the cursor and move the cursor left.
- Delete: Delete (or zero) the byte under the cursor.
- Ctrl-K: Delete from cursor to end of file.

## Editing (byte)

- Any non-digit key: Reset any active numerical digits which have not yet been written.

## Search

- Ctrl-S: Find next match.
- Ctrl-R: Find previous match.
- Enter: Exit search mode.

# Known bugs/missing features

- Large files (30MB+) get pretty slow (just blame Python.)
- No undo/redo.
- No structure decoding.

# License

See file _LICENSE.txt_ for more information.
