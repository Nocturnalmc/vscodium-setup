# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/DOCS.md#howto-vscode-marketplace

1. Auto Rename Tag by Jun Han
2. DotENV by mikestead
3. Live Server by Ritwick Dey
4. Material Icon Theme by Philipp Kief
5. MongoDB for VS Code by MongoDB
6. NativeBase VS Code Extension by NativeBase
7. One Dark Pro by binaryify
8. Prettier - Code formatter by Prettier
9. Tailwind CSS IntelliSense by Tailwind Labs

### Download JetBrainsMono Nerd Font from https://www.nerdfonts.com/font-downloads

### Extras

Add these to settings.json

```json
  "editor.fontSize": "your desired font size"
  "window.zoomLevel": "your desired zoom level"
```

### Set custom keyboard shortcut

Shift+Ctrl+Alt+D :

```
codium --enable-features=UseOzonePlatform --ozone-platform=wayland
```

### VSCode on Windows Specific

Add these to settings.json :

```json
"terminal.integrated.defaultProfile.windows": "Git Bash",
"telemetry.telemetryLevel": "off"
```
