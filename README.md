# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/DOCS.md#howto-vscode-marketplace

1. Auto Rename Tag by Jun Han
2. DotENV by mikestead
3. Live Server by Ritwick Dey
4. Material Icon Theme by Philipp Kief
5. One Dark Pro by binaryify
6. Prettier - Code formatter by Prettier
7. Tailwind CSS IntelliSense by Tailwind Labs

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
