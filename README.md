# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/DOCS.md#how-to-use-a-different-extension-gallery

1. Atom One Light Theme by Mahmoud Ali
2. Auto Rename Tag by Jun Han
3. Better Comments by Aaron Bond
4. DotENV by mikestead
5. Git Blame by Wade Anderson
6. Material Icon Theme by Philipp Kief
7. One Dark Pro by binaryify
8. Prettier - Code formatter by Prettier
9. Tailwind CSS IntelliSense by Tailwind Labs

### Download JetBrainsMono Nerd Font from https://www.nerdfonts.com/font-downloads

### Extras

Add these at end of settings.json

```json
  "editor.fontSize": "number your desired font size",
  "window.zoomLevel": "number your desired zoom level"
```

### Set custom keyboard shortcut (currently not working)

Shift+Ctrl+Alt+D :

```
codium --enable-features=UseOzonePlatform --ozone-platform=wayland
```

or

```
flatpak run com.vscodium.codium --enable-features=UseOzonePlatform --ozone-platform=wayland
```

### VSCode on Windows Specific

Add these to settings.json :

```json
"terminal.integrated.defaultProfile.windows": "Git Bash",
"telemetry.telemetryLevel": "off"
```
