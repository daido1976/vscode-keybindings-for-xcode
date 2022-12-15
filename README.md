# vscode-keybindings-for-xcode

VS Code keybindings for Xcode.

## Installation

Download the file to `~/Library/Developer/Xcode/UserData/KeyBindings/VSCode.idekeybindings`. Then select `VSCode` in `Xcode > Settings > Key Bindings`.

```sh
$ curl https://raw.githubusercontent.com/daido1976/vscode-keybindings-for-xcode/main/VSCode.idekeybindings -o ~/Library/Developer/Xcode/UserData/KeyBindings/VSCode.idekeybindings
```

And apply `Show Previous Tab/Show Next Tab` shortcuts for tab switching in `System Settings > Keyboard Shortcuts > App Shortcuts`.

<img src='https://user-images.githubusercontent.com/35087200/207867604-e4006d8f-de1a-41a8-a808-8ef7a2e2518a.png' width=480>

See below for why it is necessary to go to System Settings.

[Unable to use option key in some Xcode keyboard shortcuts \- Stack Overflow](https://stackoverflow.com/questions/73185455/unable-to-use-option-key-in-some-xcode-keyboard-shortcuts/73225466)

## Development

Change the keybindings on Xcode and export the configuration file.

```sh
$ git clone https://github.com/daido1976/vscode-keybindings-for-xcode.git <CLONE_DIR_PATH>
# Change the keybindings on Xcode...
$ \cp -f ~/Library/Developer/Xcode/UserData/KeyBindings/VSCode.idekeybindings <CLONE_DIR_PATH>/VSCode.idekeybindings
```
