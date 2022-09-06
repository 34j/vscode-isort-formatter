
# VSCode Extension for isort

[![GitHub](https://img.shields.io/github/license/34j/vscode-isort-formatter?logo=github&logoColor=%23181717)](https://github.com/34j/vscode-isort-formatter)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/mikoz.isort-formatter?logo=visual-studio-code&logoColor=%23007ACC)](https://marketplace.visualstudio.com/items?itemName=mikoz.isort-formatter)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/mikoz.isort-formatter)](https://marketplace.visualstudio.com/items?itemName=mikoz.isort-formatter)

VSCode extension for sorting Python imports using isort.

[![Install Now](https://img.shields.io/badge/-Install%20Now-107C10?style=for-the-badge&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=mikoz.isort-formatter)

Consider using [Composite Formatter](https://marketplace.visualstudio.com/items?itemName=mikoz.composite-formatter) to run multiple formatters at once as a single formatter.

## Requirements

1. VS Code 1.64.0 or greater
1. Python 3.7 or greater
1. node >= 14.19.0
1. npm >= 8.3.0 (`npm` is installed with node, check npm version, use `npm install -g npm@8.3.0` to update)
1. Python extension for VS Code

## Extension Settings

|Name|Description|
|----|-----------|
|`isort.logLevel`| The log level the extension logs at, defaults to 'error'.|
| `isort.args`| Additional arguments passed in. Each argument is a separate item in the array.|
| `isort.path`| When set to a path to isort binary, extension will use that. NOTE: Using this option may slowdown server response time.|
| `isort.importStrategy`| Defines where `isort` is imported from. This setting may be ignored if `isort.path` is set.|
| `isort.interpreter`| When set to a path to python executable, extension will use that to launch the server and any subprocess.|
| `isort.showNotification`| Controls when notifications are shown by this extension.|

## Extension Commands

`isort: Restart Server`: Restart Server.

<!--## Known Issues-->