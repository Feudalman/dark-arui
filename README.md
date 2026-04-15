# Dark-Arui

[中文文档](README-zh.md)

**Black enough**

Dark-Arui is a dark theme designed for long coding sessions, featuring a unified deep black background and low-contrast design to create an immersive development experience. The syntax highlighting, primarily based on green and cyan tones, is both gentle and distinctive, making code reading more comfortable.

![example](example.png)

## 🎨 Color Scheme

### Primary Colors

- **Background**: `#0a0a0a` - Deep Black
- **Text**: `#e0e0e0` - Soft Light Gray

### Syntax Highlighting

- **Strings**: `#7fb069` - Soft Green
- **Keywords**: `#5dbcd2` - Cyan
- **Functions**: `#52b788` - Bright Green
- **Numbers/Constants**: `#d4a574` - Soft Yellow
- **Types/Classes**: `#6db3d4` - Soft Blue
- **Comments**: `#6b7d7d` - Gray-Cyan, balanced visibility

### Status Colors

- **Error**: `#d46a6a` - Soft Red
- **Warning**: `#d4a574` - Yellow-Orange
- **Info**: `#6db3d4` - Blue

## 📦 Installation

### Install from VS Code Marketplace

1. Open VS Code
2. Press `Cmd+Shift+X` (macOS) or `Ctrl+Shift+X` (Windows/Linux) to open Extensions panel
3. Search for "Dark-Arui"
4. Click Install

### Manual Installation

#### Get the Extension

You can obtain the `.vsix` file in two ways:

##### Direct Download

Download the appropriate version directly from the [`release`](https://github.com/Feudalman/dark-arui/releases) page on GitHub.

##### Build from Source

1. Install `vsce` via `npm install -g vsce`
2. Clone this repository and run `vsce package` in the root directory
3. The `dark-arui-0.0.1.vsix` file will be generated in the root directory

#### Manual Installation - Method 1

1. Open VS Code
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Windows/Linux)
3. Type "Extensions: Install from VSIX..."
4. Select the target `.vsix` file

#### Manual Installation - Method 2

1. Check if the `code` command (for managing VS Code) exists: `code --version`
2. If not, open VS Code and use the shortcut to open the Extensions panel:

- macOS: `Cmd+Shift+X`
- Windows/Linux: `Ctrl+Shift+X`

3. In the Extensions panel, execute: `Shell Command: Install 'code' command in PATH`, then check again if the `code` command exists
4. Install the `.vsix` file as an extension via `code`: `code --install-extension dark-arui-0.0.1.vsix`

## 🚀 Usage

1. After installing the theme, press `Cmd+K Cmd+T` (macOS) or `Ctrl+K Ctrl+T` (Windows/Linux)
2. Select "Dark-Arui" from the list

Or via settings:

```json
{
  "workbench.colorTheme": "Dark-Arui"
}
```

## 🤝 Feedback & Contribution

If you have any suggestions or find issues, feel free to:

- Submit an Issue
- Create a Pull Request
- Share your experience

**Enjoy coding in the dark!** 🌙

## 📄 License

Copyright 2024-2025 Emotion Machine (Beijing) Technology Co., Ltd.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
