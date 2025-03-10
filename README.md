# ESPEasy Rules Highlighter

![ESPEasy Logo](images/logo.png)

This Visual Studio Code extension provides syntax highlighting for ESPEasy rules files.

## Features

- Syntax highlighting for ESPEasy rules syntax
- Command and event recognition
- Variable highlighting
- Code folding for event blocks

## Usage

Open any .txt file containing ESPEasy rules. The extension will automatically activate for these files.

## Supported Syntax Elements

- Comments (`//`)
- Events (`On System#Boot do ... Endon`)
- Commands (`asyncevent`, `publish`, `timerset`, etc.)
- Variables (`%variable%` and `[Task#Value]`)
- String literals
- Numeric literals
- Conditional statements (`if`, `elseif`, `endif`)

## Issues and Contributions

Please report any issues on the [GitHub repository](https://github.com/kakha13/espeasy-rules-highlighter).
