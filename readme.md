# windows 11

```
Set-ExecutionPolicy Bypass -Scope Process -Force
powershell -Command "Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/mattyatea/dotfiles/refs/heads/main/windows-app-install.bat' -Method Get | Invoke-Expression"
Set-ExecutionPolicy Restricted -Scope Process -Force
```
