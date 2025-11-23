# Contributing to Hyperlink Theme

First off, thank you for considering contributing to Hyperlink Theme! It's people like you that make this theme better for everyone.

## 🎯 Ways to Contribute

### 1. Reporting Bugs

If you find a bug, please create an issue and include:

- **Theme version** you're using
- **VS Code version**
- **Operating system**
- **Screenshots** showing the issue (if applicable)
- **Steps to reproduce** the problem
- **Expected behavior** vs **actual behavior**

### 2. Suggesting Enhancements

Have an idea to make the theme better? We'd love to hear it!

- Check if the enhancement has already been suggested
- Create a detailed issue explaining:
  - What you want to add/change
  - Why it would be useful
  - Examples or mockups (if applicable)

### 3. Improving Colors

If you notice a language or file type that doesn't look quite right:

- Specify the **language/file type**
- Provide a **code sample** demonstrating the issue
- Suggest what colors should be used (refer to our color palette)
- Include **before/after screenshots** if possible

### 4. Documentation

Help improve our documentation:

- Fix typos or clarify instructions
- Add examples
- Improve installation guides
- Translate documentation

## 🔧 Development Process

### Setting Up Your Environment

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/hyperlink-vscode.git
   cd hyperlink-vscode
   ```

3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

### Making Changes

1. **Edit the theme file**: `theme/hyperlink-color-theme.json`

2. **Test your changes**:
   - Press `F5` in VS Code to open a new Extension Development Host window
   - Your changes will be applied automatically
   - Test with multiple languages (JavaScript, Python, HTML, CSS, etc.)

3. **Follow the color palette**:
   - Yellow/Gold `#FDD46B` - Keywords, strings, booleans
   - Cyan `#53E0FC` - Types, classes, HTML tags
   - Orange/Red `#F08261` - Variables, arguments
   - Green `#B8E97B` - Functions, methods
   - Purple `#C67BE9` - Properties
   - Light Gray `#A8ADB7` - Comments
   - White `#FFFFFF` - Text, operators

### Submitting Changes

1. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   ```

   Use clear commit messages:
   - `fix: correct Python string color`
   - `feat: add support for Rust syntax`
   - `docs: update installation instructions`

2. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request**:
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill out the PR template
   - Wait for review

## 📋 Pull Request Guidelines

- Keep PRs focused on a single issue or feature
- Update documentation if needed
- Include screenshots for visual changes
- Test your changes thoroughly
- Follow the existing code style
- Reference any related issues

## 🎨 Theme Structure

```json
{
  "colors": {
    // UI colors (backgrounds, borders, text)
  },
  "tokenColors": [
    // Syntax highlighting rules
  ]
}
```

### Common Token Scopes

- `keyword` - Language keywords (if, else, return)
- `string` - String literals
- `comment` - Code comments
- `variable` - Variable names
- `function` - Function names
- `constant` - Constants and enums
- `storage.type` - Type declarations
- `entity.name.class` - Class names
- `support.function` - Built-in functions

## ❓ Questions?

Feel free to:
- Open an issue with the "question" label
- Check existing issues and discussions
- Reach out to the maintainers

## 📜 Code of Conduct

Please be respectful and constructive. We're all here to make a great theme together!

---

Thank you for contributing! 🙌
