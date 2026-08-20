# Windows CMD Commands

Common Windows Command Prompt commands for IT support and troubleshooting.

## File & Directory Commands

### `dir`

Displays files and folders in the current directory.

```cmd
dir
```
### `cd`

Changes the current directory.

```cmd
cd C:\Users
```
### `mkdir`

Creates a new directory.

```cmd
mkdir TestFolder
```
### `rmdir`

Removes a directory.

```cmd
rmdir TestFolder
```
## Networking Commands

### `ipconfig`

Displays network configuration information.

```cmd
ipconfig
```
More detailed information:
```cmd
ipconfig /all
```
### `ping`

Tests connectivity to another device.

```cmd
ping google.com
```

### `tracert`

Shows the route packets take to a destination.

```cmd
tracert google.com
```
### `nslookup`

Queries DNS information.

```cmd
nslookup google.com
```
## System Commands

### `hostname`

Displays the computer's hostname.

```cmd
hostname
```
### `whoami`

Displays the currently logged-in user.

```cmd
whoami
```
### `systeminfo`

Displays detailed Windows system information.

```cmd
systeminfo
```
### `tasklist`

Displays currently running processes.

```cmd
tasklist
```
### `taskkill`

Terminates a running process.

```cmd
taskkill /PID 1234 /F
```
## Troubleshooting

### `sfc`

Checks Windows system files for corruption.

```cmd
sfc /scannow
```
### `chkdsk`

Checks a disk for file-system errors.

```cmd
chkdsk
```
