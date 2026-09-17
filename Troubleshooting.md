
# IT Troubleshooting Guide

A beginner-friendly guide to diagnosing common computer and network issues.

## 1. Network Connectivity

### Problem
The computer cannot access the internet.

### Basic Checks
1. Check whether Wi-Fi or Ethernet is connected.
2. Check the IP configuration.
3. Test connectivity using ping.
4. Check DNS resolution.

### Windows Commands

```cmd
ipconfig /all
ping 8.8.8.8
nslookup google.com
```

### Linux Commands

```bash
ip addr
ping 8.8.8.8
```

## 2. Slow Computer

### Basic Checks
1. Check running processes.
2. Check memory usage.
3. Check available disk space.
4. Review recently installed applications.

### Windows PowerShell

```powershell
Get-Process
Get-CimInstance Win32_OperatingSystem
```

### Linux

```bash
top
free -h
df -h
```

## 3. DNS Troubleshooting

### Problem
A website cannot be reached by its domain name.

### Basic Checks
1. Test connectivity to an IP address.
2. Query the DNS server.
3. Compare results with another DNS server.

### Windows

```cmd
nslookup google.com
ipconfig /flushdns
```

### Linux

```bash
resolvectl status
```

## Troubleshooting Methodology

1. Identify the problem.
2. Gather information.
3. Test one possible cause at a time.
4. Apply a solution.
5. Verify the result.
6. Document what happened.
