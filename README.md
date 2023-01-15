# vscode-settings

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
