# voidshine hacks for Schism Tracker

## Note name system (TNKS)x(aiu) = Ta Ti Tu Na Ni Nu Ka Ki Ku Sa Si Su

## Chromatic MIDI keyboard note mapping

## General workflow keys
- Space plays; Shift+Space stops; Ctrl+Space sets playback start mark

## Navigation mode and many modifier-free keybindings
- `;` toggles edit mode between normal and navigation modes.
- Arrow keys move one line or column at a time regardless of skip value
- `'` jumps to selection beginning (or end if shift is pressed)
- `w` jumps to next row *with* a note after first seeking to next row without a note
- `e` jumps to next row that's fully *empty* after first seeking to next nonempty row

### Selection
- In navigation mode, `v` controls "visual" selection.
- Press `v` while nothing is selected to begin selection.
- Move to the other side (before or after current position) and press `v` again to finish selection.
- Pressing `v` a third time in a new position will move the nearest endpoint to current position.
- Pressing `v` while positioned exactly at a selection endpoint will deselect all.

### Editing
- Press `y` to "yank" selection to clipboard.
- Press `p` to paste with insertion behavior (existing notes move down to make room for pasted rows).
- Press `o` to paste with overwrite behavior (no movement of existing notes).
