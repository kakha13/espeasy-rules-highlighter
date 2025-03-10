# ESPEasy Rules Highlighter - Development

## Development Setup

1. Make sure you have Node.js installed
2. Install the VS Code Extension CLI:
   ```
   npm install -g vsce
   ```

## Testing Your Extension

1. Open this folder in VS Code
2. Press F5 to launch a new window with the extension loaded
3. Open a file with a `.txt` extension containing ESPEasy rules
4. Verify that syntax highlighting is working correctly

## Packaging the Extension

To package the extension:

```
vsce package
```

This will generate a `.vsix` file that can be installed in VS Code.

## Installing the Extension

To install the extension:

1. Open VS Code
2. Press Ctrl+Shift+P to open the command palette
3. Type "Extensions: Install from VSIX" and select it
4. Navigate to the generated `.vsix` file and select it

## Publishing the Extension

To publish the extension to the VS Code Marketplace:

1. Create a publisher account at https://marketplace.visualstudio.com/
2. Get a Personal Access Token
3. Run:
   ```
   vsce login <publisher>
   vsce publish
   ```
