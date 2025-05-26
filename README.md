# Neovim Commands I Recently Learned

## Basic Navigation
- `:q` → to quit nvim
- `h` → arrow left
- `j` → arrow down
- `k` → arrow up
- `l` → arrow right

## Word Selection & Navigation
- `*` → select the same words
- `Shift + n` → to back words we select
- `n` → to go that words we select first
- `N` → to go that words we select latest

## Text Editing
- `c + i + w` → change in words we select
- `.` → replace same words when we do `c + i + w`

## Undo/Redo
- `u` → undo the last modification
- `Ctrl + r` → redo the last modification

## Search & Replace
- `:%s/argument/argument` → to search words and replace it
- `:%s/argument/argument/gc` → to search words and replace it or not

## Copy & Paste
- `v + i + w` → to select words and then press `y` to copy and press `p` to paste
