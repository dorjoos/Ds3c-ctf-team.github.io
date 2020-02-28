
https://superuser.com/questions/446827/configure-the-windows-powershell-to-display-only-the-current-folder-name-in-the

Function Prompt { "$( Split-Path -leaf -path (Get-Location) )>" }
