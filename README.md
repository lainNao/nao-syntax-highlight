# nao-syntax-highlight

## Description

VSCode extension for `.nao` and `.txt` extension file (super simple markdown for me).

```
//...
■...
＜...＞
```

## Install from local
1. clone
    - `git clone https://github.com/lainNao/nao-syntax-highlight`
2. build
    - `npx vsce package`
3. install
    - `code --install-extension <now-created-file-name>`

## Install from
search `nao-syntax-highlight` in vscode extension
## Local development
- `F5` to open debugging window

## Releases
- `0.0.1` 
    - `.nao`対応
- `0.0.2`
    - `.txt`対応

## Update extension
1. get access token from `dev.azure.com`
2. upload
   - `vsce publish [major|minor|patch]`