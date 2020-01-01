# iTerm2

iTerm2 is a better terminal application for macOS.

## Instalation

To install iTerm2 use the command:
```zsh
brew cask install iterm2
```

## Configuration

- General
  - Closing
    - Quit When all windows are closed: On
    - Confirm closing multiple sessions: On
    - Confirm "Quit iTerm2": Off
  - Selection
    - Applications in terminal may acess clipboard: On
- Appearance
  - Windows
    - Disable transparency for fullscreen windows by default
- Profiles
  - Colors
    - Color Presents: Solarized Dark
  - Text
    - Cursor
      - Vertical Bar: On
      - Blinking cursor: On
    - Text Rendering
      - Use buildt-in Powerline glyphs: On
    - Font
      - Name: Menlo
      - Size: 13
  - Window
    - Transparency: Some (Example: 0.033)
    - Columns: 125
  - Terminal
    - Silence bell: on
    - Show bell icon in tabs: off
  - Keys
    - Key Mappings:
      - Move curser forward/backward one word
        * ⌥+← — Send Escape Sequence: b
        * ⌥+→ — Send Escape Sequence: f
      - Move cursor to the start/end of the line
        * ⌘+← — Send Hex Codes: 0x01
        * ⌘+→ — Send Hex Codes: 0x05
      - Delete last/next word
        * ⌥+Backspace — Send Hex Codes: 0x17
        * ⌥+Del — Send Escape Sequence: d
      - Delete to start of line
        * ⌘+Backspace — Send Hex Codes: 0x15
      - Enable "undo"
        * ⌘+z - Send Hex Codes: 0x1f
    - Hotkey window: On
      - Hotkey: Option + Space
      - Floating window: off

