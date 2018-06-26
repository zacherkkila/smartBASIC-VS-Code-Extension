# smartBASIC VS Code Extension

This is a syntax highlighting extension for the Laird<sup>TM</sup> smartBASIC Lanugage. Based largely on the default VB extension here - https://github.com/Microsoft/vscode/tree/master/extensions/vb

It is most certainly a work in progress but this should cover most of the basics

## Installation

1. [Download the latest release](https://github.com/zacherkkila/smartBASIC-VS-Code-Extension/releases/latest)

2. Extract files and move folder to the following directory

    Windows: `%USERPROFILE%\.vscode\extensions`
 
    macOS/Linux: `$HOME/.vscode/extensions`

3. Restart VS Code

   `CMD/CTRL+SHIFT+P` -> `Reload Window`
   
### If syntax highlighting doesn't happen automatically after restarting you may need to set the language mode for the file

4. Change language mode for `.sb` files

   https://code.visualstudio.com/docs/languages/overview#_changing-the-language-for-the-selected-file

5. Choose `smartBASIC` from the language list

## Known Issues

$ at the end of string variables not recongized as part of the variable

## Release Notes

### 0.0.1

Initial release of smartBASIC Language Extension
