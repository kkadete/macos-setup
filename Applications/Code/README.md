# Visual Studio Code

Visual Studio Code is a lightweight code editor with support for many programming languages

## Installation

To install VSCode use the following command:

```zsh
brew cask install visual-studio-code
```

## Install 'code' command

- Launch VSCode
- Open the Command Palette via (⇧⌘P) and type **'shell command'**:
- Select Install 'code' command in PATH\*\* command.
  ![Install Code Command](/Applications/Code/images/install-code-command.png)
- Restart the terminal for the new \$PATH value to take effect.

## Command Line Integration

To launch VSCode from the command line:

- `code .` will open VSCode in the current directory
- `code file.txt` will open `file.txt` in VSCode

## Settings Configuration

```zsh
cp settings.json ~/Library/Application\ Support/Code/User
```

## Extensions Configuration

- Install VSCode Extensions

```zsh
cat extensions.list | xargs -n 1 code --install-extension
```

- Backup VSCode Extensions
```zsh
code --list-extensions > extensions.list
```
