# bmax-emacs

An Emacs-inspired keymap for Visual Studio Code.

## Features

This extension brings Emacs-like keybindings to VS Code, making navigation and editing more familiar to Emacs users. It provides keybindings for cursor movement, text selection, editing, and window navigation.

## Installation

1. Open Visual Studio Code.
2. Go to the Extensions Marketplace (`Cmd+Shift+X`).
3. Search for `bmax-emacs`.
4. Click "Install".

Alternatively, install it manually via the command line:
```sh
code --install-extension Bhanukamax.bmax-emacs
```

## Keybindings

### Cursor Movement
- `Ctrl+A`: Move to beginning of line
- `Ctrl+Shift+A`: Select to beginning of line
- `Ctrl+E`: Move to end of line
- `Ctrl+Shift+E`: Select to end of line
- `Alt+F`: Move forward one word
- `Shift+Alt+F`: Select forward one word
- `Alt+B`: Move backward one word
- `Shift+Alt+B`: Select backward one word
- `Ctrl+Alt+F`: Move forward one word part
- `Ctrl+Shift+Alt+F`: Select forward one word part
- `Ctrl+Alt+B`: Move backward one word part
- `Ctrl+Shift+Alt+B`: Select backward one word part

### Editing
- `Ctrl+/`: Undo
- `Ctrl+Shift+/`: Redo
- `Ctrl+W`: Delete word before cursor
- `Alt+D`: Delete word after cursor
- `Alt+J`: Move line down
- `Alt+K`: Move line up
- `Shift+Ctrl+D`: Duplicate line
- `Shift+Alt+J`: Copy line down
- `Shift+Alt+K`: Copy line up
- `Alt+W`: Copy selection
- `Ctrl+Y`: Paste selection

### Selection
- `Alt+H`: Expand selection
- `Shift+Ctrl+Right`: Remove default expand selection
- `Shift+Ctrl+N`: Select line down
- `Shift+Ctrl+P`: Select line up
- `Shift+Ctrl+A`: Select to beginning of document
- `Shift+Ctrl+E`: Select to end of document

### Window & Terminal Navigation
- `Ctrl+Tab`: Next editor
- `Ctrl+Shift+Tab`: Previous editor
- `Shift+Cmd+]`: Remove default next editor
- `Shift+Cmd+[`: Remove default previous editor
- `Alt+G Alt+G`: Go to line
- `Ctrl+Tab`: Next terminal
- `Shift+Ctrl+Tab`: Previous terminal

### Page Navigation
- `Alt+V`: Page down
- `Shift+Alt+V`: Page up

### Code Navigation & Actions
- `Shift+Ctrl+K`: Show definition preview
- `Ctrl+C Ctrl+N`: Rename symbol

For a full list of keybindings, check the `keybindings.json` file in your VS Code settings.

## Repository

Find the source code and contribute at:
[GitHub Repository](https://github.com/Bhanukamax/bmax-emacs-vsc)

