# Zeeplay
This repo is for learning zee editor.
- https://github.com/zee-editor/zee

## Rule
- Write this repo using only zee editor.

## Save & Quit
- Save
  - `C-x C-s`
- Quit
  - `C-x C-c`

## Cancel
- Cancel
  - `C-g`

## File
- Open file using dir level picker
  - `C-x C-f`
- Search recursivery
  - `C-x C-v`
- Go to parent directory
  - `C-l`
- Complete path
  - `Tab`

## Editing

## Cursor move
- Basics
  - Up `C-p`
  - Down `C-n`
  - Left `C-b`
  - Right `C-f`
- Word
  - forward a word
    - `A-f`
  - backward a word
    - `A-b`
- Paragraph
  - forward a paragraph
    - `A-n`
  - backward a paragraph
    - `A-p`
- Line
  - Move to line start
    - `C-a`
  - Move to line end
    - `C-e`
- Page
  - PageDown `C-v`
  - PageUp `A-v`
  - move to page start
    - `A-<`
  - move to page end
    - `A->`
  - Centre the cursor visually
    - `C-l`
- Focus
  - focus to next buffer
    - `C-x o`, `C-x C-o`

## Window
- Split
  - horizontal `C-x 2`, `C-x C-2`
  - vertical `C-x 3`, `C-x C-3`
- Close
  - Close the focused window
    - `C-x 0`, `C-x C-0`

## Buffer
- Switch the current window to another buffer
  - `C-x b`
- Close
  - choose a buffer to close
    - `C-x k`

## Theme
- Cycle themes
  - `C-x C-t`

## Configuration
- Config file
  - `config.ron`
- Directory
  - default
    - Unix `~/.config/zee`
    - Windows `%AppData%/zee`
  - or
    - set env var `ZEE_CONFIG_DIR`
