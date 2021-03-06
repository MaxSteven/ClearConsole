# ClearConsole
> "Clear" the console by printing a bunch of new lines.

This plugin was inspired from [this answer](http://stackoverflow.com/a/24760927/4361297) on StackOverflow by [@MattDMo](https://github.com/MattDMo), and is simply a means of convenience around it that allows you to clear the console by just using some hotkeys.

## Installation
1. Open the Command Palette by pressing <kbd>⌘</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac or <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Windows
2. Type in `Package Control: Install Package` and press <kbd>Enter</kbd>
3. Type `ClearConsole` and hit <kbd>Enter</kbd>

## Usage
By default, the hotkey to clear the console is <kbd>alt</kbd>+<kbd>k</kbd>. You can change which keys you want to use by going to `Preferences > Key Bindings - User` and adding this line:

```
[
    ...
    { "keys": ["alt+k"], "command": "clear_console" }
]
```

Simply replace `alt+k` with the key combination you want to use.
