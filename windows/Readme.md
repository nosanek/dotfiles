# Windows configs

- Create the Windows Terminal settings symbolic link:

```console
New-Item -Type SymbolicLink -Path $HOME\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState -Name settings.json -Target $HOME\.dotfiles\windows\windows-terminal\settings.json
```

- Create the PowerShell profile symbolic link:

```console
New-Item -Type SymbolicLink -Path $HOME\Documents\PowerShell -Name Microsoft.PowerShell_profile.ps1 -Target $HOME\.dotfiles\windows\powershell\profile.ps1
```