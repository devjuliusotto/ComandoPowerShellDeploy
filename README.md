# ComandoPowerShellDeploy

Alguns comandos de configuração de PowerShell pra dar Deploy em WebSites.



```Comandos

## Ativa
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass
Set-ExecutionPolicy -Scope LocalMachine -ExecutionPolicy Bypass

## Desativa
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Restricted
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted
Set-ExecutionPolicy -Scope LocalMachine -ExecutionPolicy Restricted

## Listagem
Get-ExecutionPolicy -List
