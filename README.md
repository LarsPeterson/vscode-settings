# vscode-settings

This configuration applies the following changes to Visual Studio Code:
- Applies the Default Dark Theme.
- Uses Git Bash as the default terminal.
- Changes the zoom level to "-2".

```
{
    "workbench.colorTheme": "Default Dark+",
    "window.zoomLevel": -2,
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash",
            "path": ["C:\\Program Files\\Git\\bin\\bash.exe"],
            "icon": "terminal-bash"
        }
    },
    "terminal.integrated.defaultProfile.windows": "Git Bash",
}
```
