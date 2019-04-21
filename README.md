# fcitx_toggle.vim
simple script to automatically toggle your beloved fcitx in vim

## Installation
This plugin is pretty simple, you can install it using any plugin manager you like.Or else just put `plugin/fcitx.vim` and `autoload/fcitx.vim` in your runtime `plugin` and `autoload` folder respectively.

## Usage
This script ships two command: `FcitxEnable` and `FcitxDisable`.

call `FcitxEnable` and fcitx will be launched in insert mode and disabled in other mode, while calling `FcitxDisable` will stop this behavior.

## Requirement
Of course you need fcitx. check if you have the `fcitx-remote` cli tool.

## License
MIT
