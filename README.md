# Hopeless - C++ Theme

![Theme Preview](https://via.placeholder.com/800x400?text=Hopeless+C%2B%2B+%26+Python+Theme)

## Description

**Hopeless - C++** is a visually appealing dark theme for Visual Studio Code, tailored primarily for C++ and Python development. It provides a harmonious blend of colors that enhance code readability and aesthetics, making long coding sessions more comfortable.

### Key Features:
- **Dark Background:** A soothing dark background (`#263238`) with a light foreground (`#EEFFFF`) ensures reduced eye strain.
- **Rich Syntax Highlighting:** Distinct color schemes for various elements such as comments, keywords, strings, functions, variables, etc., provide clear differentiation and improve code comprehension.
- **Language Support:** Extensive support for C++, Python, Markdown, JSON, HTML, CSS, and more.
- **Consistent UI Elements:** Customized colors for editor components like the activity bar, side bar, status bar, and tabs ensure a cohesive look and feel across the IDE.

## Installation

### Via Visual Studio Code Marketplace
1. Open **Visual Studio Code**.
2. Go to the **Extensions** view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
3. Search for **"Hopeless - C++"**.
4. Click **Install**.

### Manual Installation
1. Download the latest release from the [GitHub Repository](https://github.com/emonislive/hopeless-theme-vscode-extention.git).
2. Extract the contents of the ZIP file.
3. Copy the extracted folder to your VS Code extensions directory:
   - **Windows:** `%USERPROFILE%\.vscode\extensions`
   - **macOS/Linux:** `~/.vscode/extensions`
4. Restart Visual Studio Code.

## Usage

After installation, activate the theme by following these steps:

1. Open the **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS).
2. Type **"Preferences: Color Theme"** and select it.
3. Choose **"Hopeless - C++** from the list of available themes.

## Customization

While the default settings should work well out of the box, you can further customize the theme to suit your preferences:

1. Open the **settings.json** file:
   - Go to **File > Preferences > Settings**.
   - Click on the `{}` icon in the top right corner to open the JSON file.
2. Add or modify any specific color settings under the `"workbench.colorCustomizations"` section. For example:

```json
"workbench.colorCustomizations": {
    "[Hopeless - C++]": {
        "editor.background": "#263238",
        "editor.foreground": "#EEFFFF",
        "activityBarBadge.background": "#007ACC",
        "sideBarTitle.foreground": "#BBBBBB"
    }
}

```
For token-specific customizations, use the `"editor.tokenColorCustomizations"` section:
```json
"editor.tokenColorCustomizations": {
    "[Hopeless - C++]": {
        "comments": "#546E7A",
        "keywords": "#C792EA",
        "strings": "#C3E88D",
        "functions": "#82AAFF"
    }
}
```

## Contributing
Contributions are welcome! If you have suggestions for improvements or encounter any issues, please feel free to open an issue or submit a pull request on the GitHub Repository .
