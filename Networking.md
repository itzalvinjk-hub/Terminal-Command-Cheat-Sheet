# Networking Commands

Common networking commands used for troubleshooting.

## Windows

### `ipconfig`

View IP configuration.

```cmd
ipconfig /all
```
### `ping`

Test connectivity.

```cmd
ping 8.8.8.8
```
### `tracert`

Trace the network path.

```cmd
tracert google.com
```
### `nslookup`

Check DNS resolution.

```cmd
nslookup google.com
```
### `netstat`

Display network connections.

```cmd
netstat -ano
```

## PowerShell

### `Test-NetConnection`

Test connectivity to a host and port.

```powershell
Test-NetConnection google.com -Port 443
```

## Linux

### `ip addr`

View network interfaces and IP addresses.

```bash
ip addr
```
### `ping`

Test connectivity.

```bash
ping 8.8.8.8
```
### `ss`

View network connections and listening ports.

```bash
ss -tuln
```
