# B3ast Dark Theme Extension - Quickstart Guide

Welcome to **B3ast Dark Theme** – a customizable dark theme for Visual Studio Code. This quickstart guide will walk you through how to install, activate, and customize the theme in VS Code.

## Features

- A visually appealing dark theme optimized for coding.
- High contrast with smooth colors for readability.
- Supports various file types and syntax highlighting.
- Customizable via VS Code's built-in theme settings.

## Installation

### 1. **From the VS Code Marketplace**

1. Open **Visual Studio Code**.
2. Navigate to the **Extensions** view by clicking on the square icon in the Activity Bar or by using the shortcut `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS).
3. Search for `"B3ast Dark Theme"`.
4. Click **Install** to install the theme.

### 2. **From VSIX file (Local Installation)**

1. Download the latest `.vsix` file of the theme from [GitHub](https://github.com/ShohorabHShawon/VS-Code-Dark-Theme.git) or a trusted source.
2. In **VS Code**, open the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`).
3. Click on the ellipsis (`...`) at the top-right of the Extensions view.
4. Choose **Install from VSIX...** and select the downloaded `.vsix` file.
5. After installation, the theme will be available for activation.

## Usage

### Activating the Theme

1. Open **Command Palette** using `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS).
2. Type and select `Preferences: Color Theme`.
3. Choose **"B3ast Dark Theme"** from the list of available themes.

### Customizing the Theme

You can further tweak and personalize the theme using VS Code's built-in settings:

1. Go to **Settings** (`Ctrl+,` / `Cmd+,`).
2. Search for "workbench color customization."
3. Add your custom color overrides in the `settings.json` file under the `"workbench.colorCustomizations"` field.

Example:

```json
"workbench.colorCustomizations": {
  "editor.background": "#1E1E1E",
  "editor.foreground": "#D4D4D4"
}
```

## Development

To modify or contribute to this theme:

1. Clone the repository:

   ```bash
   git clone https://github.com/ShohorabHShawon/VS-Code-Dark-Theme.git
   ```

2. Open the folder in Visual Studio Code:

   ```bash
   cd theme-name
   code .
   ```

3. Edit the theme JSON files in the `themes/` directory to modify colors, fonts, or syntax highlighting.

4. Test your theme by running the extension locally:

   - Press `F5` to open a new VS Code window with the extension enabled.
