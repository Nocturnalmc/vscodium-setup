# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/DOCS.md#howto-vscode-marketplace

1. Auto Rename Tag by Jun Han
2. DotENV by mikestead
3. Expo Tools by Cedric van Putten
4. Live Server by Ritwick Dey
5. Material Icon Theme by Philipp Kief
6. MongoDB for VS Code by MongoDB
7. NativeBase VS Code Extension by NativeBase
8. One Dark Pro by binaryify
9. Prettier - Code formatter by Prettier
10. Tailwind CSS IntelliSense by Tailwind Labs

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
