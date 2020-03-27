# WindowsTerminalSettings

This requires [git for Windows](https://gitforwindows.org/).

```
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

In PowerShell, type: 
```
notepad $PROFILE
```
Then:
```
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Paradox
```

Install the Cascadia Code PL font from their [Release page](https://github.com/microsoft/cascadia-code/releases).
