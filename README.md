# bmax-emacs

**bmax-emacs** is an Emacs inspired keymap for Visual Studio Code on macOS.

## Features

This extension provides the following keybindings:

### Editor Navigation

- `ctrl+tab`: Next editor
- `ctrl+shift+tab`: Previous editor
- `alt+g alt+g`: Go to line

### Text Selection

- `alt+h`: Expand selection (when editor text is focused)
- `shift+alt+f`: Select to the end of the word (when text input is focused)
- `shift+alt+b`: Select to the start of the word (when text input is focused)
- `ctrl+shift+alt+b`: Select to the start of the word part (when text input is focused)
- `ctrl+shift+alt+f`: Select to the end of the word part (when text input is focused)
- `shift+ctrl+a`: Select to the start of the line
- `shift+ctrl+e`: Select to the end of the line
- `shift+ctrl+n`: Select down a line (when text input is focused)
- `shift+ctrl+p`: Select up a line (when text input is focused)

### Text Editing

- `ctrl+/`: Undo
- `ctrl+shift+/`: Redo
- `ctrl+w`: Delete word to the left (when text input is focused and editor is not read-only)
- `alt+d`: Delete word to the right (when text input is focused and editor is not read-only)
- `alt+m`: Move line down (when editor text is focused and editor is not read-only)
- `alt+p`: Move line up (when editor text is focused and editor is not read-only)
- `alt+w`: Copy
- `ctrl+y`: Paste

### Cursor Movement

- `alt+f`: Move cursor to the end of the word (when text input is focused)
- `alt+b`: Move cursor to the start of the word (when text input is focused)
- `ctrl+alt+b`: Move cursor to the start of the word part (when text input is focused)
- `ctrl+alt+f`: Move cursor to the end of the word part (when text input is focused)
- `alt+v`: Move cursor down a page (when text input is focused)
- `shift+alt+v`: Move cursor up a page (when text input is focused)

### Terminal Navigation

- `ctrl+tab`: Focus next terminal (when terminal is focused and terminal has been created or terminal process is supported)
- `shift+ctrl+tab`: Focus previous terminal (when terminal is focused and terminal has been created or terminal process is supported)

### Other

- `Ctrl+c Ctrl+n`: Rename symbol (when editor has rename provider, editor text is focused, and editor is not read-only)
- `ctrl+cmd+k`: Show definition preview hover

## Installation

1. Download and install Visual Studio Code.
2. Copy the extension into the `<user home>/.vscode/extensions` folder.
3. Restart Visual Studio Code.

## Usage

1. Press `F5` to open a new window with your extension loaded.
2. Use the keybindings listed above to navigate and edit your code.

## Contributing

Contributions are welcome! Please check the [CHANGELOG.md](CHANGELOG.md) for notable changes and follow the guidelines in the [vsc-extension-quickstart.md](vsc-extension-quickstart.md) to get started.

## License

MIT License