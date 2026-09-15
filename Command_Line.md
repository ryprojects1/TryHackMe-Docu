# Windows Command Line: Part 1

## Why Use Command Line Interface (CLI) Over GUI?

- ⚡ **Speed** - Faster execution of tasks
- 📈 **Efficiency** - Accomplish more with fewer steps
- 💾 **Lower Resource Usage** - Minimal memory and CPU consumption
- 🤖 **Automation** - Script repetitive tasks
- 🌐 **Remote Management** - Manage systems over network connections

---

## System Information Commands

### Ver
Display Windows version information.
```powershell
ver
```

### Systeminfo
List comprehensive system details including OS info, processor, memory, and hardware specifications.
```powershell
systeminfo
```

---

## Network Troubleshooting Commands

### Ipconfig
Show current network configuration.
```powershell
ipconfig
```

### Ipconfig /All
Display detailed network information including MAC address, DHCP settings, and DNS servers.
```powershell
ipconfig /all
```

### Ping
Check whether a connection to a host can be established.
```powershell
ping (target_name)
ping google.com
```

### Tracert
Display the route/path your data takes to reach a destination, showing each hop.
```powershell
tracert (target_name)
tracert google.com
```

![Tracert Command Output](./screenshots/treeCLI.png)
*Network path visualization showing route to destination*

### Nslookup
Look up a host or domain name and return its IP address.
```powershell
nslookup google.com
```

### Netstat
Display current network connections and listening ports.
```powershell
netstat
```

### Netstat -Abon
Show detailed network statistics including process IDs and associated applications.
```powershell
netstat -abon
```

---

## File Management Commands

### Dir
List child directories and files in current location.
```powershell
dir
```

![Directory Listing](./screenshots/changingDirectory.png)
*Navigating and listing directories*

### Dir /A
Display hidden files and directories along with normal ones.
```powershell
dir /a
```

### Copy
Copy files from one location to another.
```powershell
copy (source) (destination)
copy file.txt C:\backup\
```

---

## Process Management Commands

### Tasklist
Display all currently running processes with their Process IDs (PIDs).
```powershell
tasklist
```

![Running Processes](./screenshots/tasklist.png)
*List of active processes running on the system*

### Taskkill
Terminate a running process by name or Process ID.
```powershell
taskkill /im (process_name)
taskkill /pid (process_id)
```

---

## System Management Commands

### Shutdown
Control system shutdown and restart operations.
```powershell
shutdown /s    # Shutdown
shutdown /r    # Restart
shutdown /h    # Hibernate
```

![Shutdown Details](./screenshots/shutdownDetail.png)
*Shutdown command options and parameters*

---

## Key Takeaways

✅ CLI provides faster and more efficient system management  
✅ Network troubleshooting tools help diagnose connectivity issues  
✅ Process management allows control of running applications  
✅ File operations can be automated via command line  
✅ System information commands provide detailed diagnostics  

---

**Last Updated:** 2026-09-15  
**Status:** 📚 Active Learning
