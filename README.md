# Visual Studio Code User Settings

To apply this configuration, press `CTRL+SHIFT+P` and enter "user settings".

![image](https://user-images.githubusercontent.com/25396567/212573966-8932ff82-23dd-41a7-a6c1-02e27a8a2a39.png)

This configuration applies the following changes to Visual Studio Code:
- Uses Git Bash as the default terminal.
- Applies the Default Dark Theme.
- Changes the zoom level to "-2".

```
{
    "angular.enable-strict-mode-prompt": false,
    "githubPullRequests.ignoredPullRequestBranches": [
        "develop"
    ],
    "terminal.integrated.shell.windows": "C:\\Git\\bin\\bash.exe",
    "terminal.integrated.shellArgs.windows": [],
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
            "path": ["C:\\Git\\bin\\bash.exe"],
            "icon": "terminal-bash"
        }
    },
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "diffEditor.ignoreTrimWhitespace": false,
}
```
