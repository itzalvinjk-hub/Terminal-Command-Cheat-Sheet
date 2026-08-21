# Linux Commands

Common Linux terminal commands for beginners and IT support.

## Navigation

### `pwd`

Displays the current directory.

```bash
pwd
```
### `ls`

Lists files and directories.

```bash
ls
```
### `cd`

Changes directories.

```bash
cd /home/user
```

## Files & Directories

### `mkdir`

Creates a directory.

```bash
mkdir test
```
### `touch`

Creates an empty file.

```bash
touch example.txt
```
### `cp`

Copies files.

```bash
cp example.txt backup.txt
```
### `mv`

Moves or renames files.

```bash
mv example.txt backup/
```
### `rm`

Removes files.

```bash
rm example.txt
```

## System Information

### `ps`

Displays running processes.

```bash
ps
```
### `top`

Displays running processes and system activity.

```bash
top
```
### `df`

Displays available disk space.

```bash
df -h
```
### `free`

Displays memory usage.

```bash
free -h
```

## Networking

### `ip`

Displays and manages network information.

```bash
ip addr
```
### `ping`

Tests network connectivity.

```bash
ping google.com
```

### `ss`

Displays network connections and listening ports.

```bash
ss -tuln
```

## Permissions

### `chmod`

Changes file permissions.

```bash
chmod 755 script.sh
```
### `chown`

Changes file ownership.

```bash
chown user:user file.txt
```
