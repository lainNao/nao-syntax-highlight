# nao-syntax-highlight

## Description

VSCode syntax highlight extension for `.nao` and `.txt` extension file (super simple markdown for me).

![usage](https://i.imgur.com/kZiJ5O2.png)

Syntax:

```txt
// some text
■ some text
＜some text＞
```

## Install from local

1. clone
    - `git clone https://github.com/lainNao/nao-syntax-highlight`
2. build
    - `npx vsce package`
3. install
    - `code --install-extension <now-created-file-name>`

## Install from Marketplace

search `nao-syntax-highlight` in vscode extension

## Local development

- `F5` to open debugging window

## Update extension

1. get access token from `dev.azure.com`
2. upload
    - `vsce publish [major|minor|patch]`
