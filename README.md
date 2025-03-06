# Hyperlink

A dark theme with great colors for VS Code inspired by Stef Kors' Hyperlink theme for Nova editor.

## Features

The Hyperlink theme has been carefully converted from the original Nova editor theme to VS Code, maintaining all the original colors and styling. The theme features:

- A dark blue background (#1C2639) with lighter elements (#28344B)
- Vibrant syntax highlighting with the following color palette:
  - Yellow/Gold: #FDD46B (keywords, strings, boolean values)
  - Cyan: #53E0FC (types, classes, HTML tags)
  - Orange/Red: #F08261 (variables, arguments)
  - Green: #B8E97B (functions, methods)
  - Purple: #C67BE9 (properties)
  - Light Gray: #A8ADB7 (comments)
  - White: #FFFFFF (text, operators)
- Customized UI elements that match the code styling
- Terminal colors that complement the editor theme

## VS Code Installation

### Manual Installation
1. Download or clone this repository
2. Copy the entire folder to your VS Code extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions`
   - macOS: `~/.vscode/extensions`
   - Linux: `~/.vscode/extensions`
3. Restart VS Code
4. Select the Hyperlink theme: `Code > Preferences > Color Theme > Hyperlink`

### Building a VSIX Extension
You can also build a VSIX extension file:

1. Install vsce: `npm install -g @vscode/vsce`
2. Run `vsce package` in the theme directory
3. Install the generated .vsix file in VS Code: `Extensions > ... > Install from VSIX`

## Feedback and Contributions

If you notice any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License and Attribution

This theme is released under the MIT License. The VS Code adaptation was created by Nik Kale.

Theme colors are heavily inspired by [Stef Kors' Hyperlink theme](https://github.com/StefKors/Hyperlink-Nova-Theme) for the Nova editor.
