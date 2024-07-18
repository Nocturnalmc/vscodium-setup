# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/docs/index.md#how-to-use-a-different-extension-gallery

Create product.json inside "~/.var/app/com.vscodium.codium/config/VSCodium" for VSCodium Flatpak

1. Atom One Light Theme by Mahmoud Ali
2. Auto Rename Tag by Jun Han
3. Better Comments by Aaron Bond
4. DotENV by mikestead
5. Git Blame by Wade Anderson
6. Material Icon Theme by Philipp Kief
7. Material Theme by Equinusocio
8. Material Theme Icons by Equinusocio
9. One Dark Pro by binaryify
10. Prettier - Code formatter by Prettier
11. shell-format by foxundermoon
12. Tailwind CSS IntelliSense by Tailwind Labs

### Download JetBrainsMono Nerd Font from https://www.nerdfonts.com/font-downloads

### Extras

Add these at end of settings.json

```json
  "editor.fontSize": "number your desired font size",
  "window.zoomLevel": "number your desired zoom level"
```

### Set custom keyboard shortcut (not needed anymore)

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
