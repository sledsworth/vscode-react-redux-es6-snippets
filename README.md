# React and Redux ES6 Snippets

This extension for Visual Studio Code adds snippets for React and Redux using ES6 for JavaScript. Supports both `.js` and `.jsx` file extensions.

## Usage

Type part of a snippet, press `enter`, and the snippet unfolds. Camel Cased identifiers allows for abbreviations.
For example: `rae` will match `reduxActionExport`.

|      Shortcut Identifier |     | Description                                        |
| -----------------------: | --- | :------------------------------------------------- |
|        **importDefault** | →   | ES6 Default Import                                 |
|        **importAliased** | →   | ES6 Import with Alias                              |
|          **importNamed** | →   | ES6 Named Import                                   |
|                   **pc** | →   | React Presentational Component                     |
|                   **cc** | →   | React Container Component                          |
|                  **rcc** | →   | Redux Connected Container Component                |
|                  **hoc** | →   | Higher-order Component                             |
|             **setState** | →   | React Set Component State                          |
|        **compWillMount** | →   | React Lifecycle Hook: Component Will Mount         |
|         **compDidMount** | →   | React Lifecycle Hook: Component Did Mount          |
|     **compShouldUpdate** | →   | React Lifecycle Hook: Should Component Update      |
| **compWillReceiveProps** | →   | React Lifecycle Hook: Component Will Receive Props |
|      **compWillUnmount** | →   | React Lifecycle Hook: Component Did Unmount        |
|         **defaultProps** | →   | React Default Props                                |
|            **proptypes** | →   | React Proptypes                                    |
|              **reducer** | →   | Redux reducer                                      |
|                  **rms** | →   | Redux Map State to Props                           |
|                  **rmd** | →   | Redux Map Dispatch to Props                        |
|                  **rec** | →   | Redux export connected component                   |
|         **exportAction** | →   | Redux Action Export                                |

Alternatively, press `Ctrl`+`Space` to activate snippets from within the editor.

## Installation

1.  Install Visual Studio Code 0.10.1 or higher
2.  Launch VS Code
3.  From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (macOS)
4.  Select `Install Extension`
5.  Choose the extension `React Redux ES6 Snippets`
6.  Reload VS Code
