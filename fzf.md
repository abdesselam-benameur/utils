# Linux

```bash
sudo apt install fzf
```
To set up shell integrations check this : [https://github.com/junegunn/fzf?tab=readme-ov-file#setting-up-shell-integration](https://github.com/junegunn/fzf?tab=readme-ov-file#setting-up-shell-integration)

# Windows

```powershell
scoop install fzf
Install-Module -Name PSFzf -Scope CurrentUser
Add-Content $PROFILE "Import-Module PSFzf`nSet-PsFzfOption -PSReadlineChordProvider 'Ctrl+t' -PSReadlineChordReverseHistory 'Ctrl+r'"
```

