# PowerShell Commands

Common PowerShell commands for IT support and system administration.

## System Information

### `Get-ComputerInfo`

Displays detailed computer information.

```powershell
Get-ComputerInfo
```
### `Get-Process`

Displays running processes.

```powershell
Get-Process
```
### `Get-Service`

Displays Windows services.

```powershell
Get-Service
```

## Networking

### `Get-NetIPConfiguration`

Displays network configuration.

```powershell
Get-NetIPConfiguration
```
### `Test-Connection`

Tests network connectivity.

```powershell
Test-Connection google.com
```
### `Test-NetConnection`

Tests network connectivity and specific ports.

```powershell
Test-NetConnection google.com -Port 443
```

## Files

### `Get-ChildItem`

Lists files and directories.

```powershell
Get-ChildItem
```
### `Copy-Item`

Copies files or directories.

```powershell
Copy-Item file.txt C:\Backup\
```
### `Move-Item`

Moves files or directories.

```powershell
Move-Item file.txt C:\Backup\
```
### `Remove-Item`

Removes files or directories

```powershell
Remove-Item file.txt
```
