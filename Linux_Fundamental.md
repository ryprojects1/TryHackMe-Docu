# Linux Fundamentals

## Part 1 (9/9/2026)

### Basic Commands

| Command | Description |
|---------|-------------|
| `whoami` | Tells you who you are on the system |
| `echo` | Output text that you provided |
| `ls` | List out what's in the current folder |
| `cd` | Change directory |
| `cat` | Show content of a file |
| `pwd` | Print the current directory you are in |
| `find` | Search for files based on name (e.g., `find -name passwords.txt`) |
| `grep` | Search inside for text |

### Operators

| Operator | Description |
|----------|-------------|
| `&` | Runs the command and does not wait for it to finish |
| `&&` | Runs both commands but waits for the first to finish before next instruction |
| `>` | Redirect output - overwrites existing file |
| `>>` | Redirect output - appends instead (doesn't overwrite) |

---

## Part 2 (9/9/2026)

### SSH
Secure Shell - allows you to connect to remote systems securely

### File & Directory Commands

| Command | Description |
|---------|-------------|
| `ls -a` | Show hidden folders |
| `ls --help` | Gives brief description of possible ls options |
| `touch` | Create file |
| `mkdir` | Create a folder |
| `cp` | Copy a file or folder |
| `mv` | Move file or folder |
| `rm` | Remove file or folder |

### System Directories

| Directory | Description |
|-----------|-------------|
| `/etc` | Commonplace location where system and program files are stored |
| `/var` | Stores data that services and applications write to or read often (like log files) |
| `/root` | Actual home directory |
| `/tmp` | Store temporary files |

### File Permissions

| Permission | Symbol | Description |
|-----------|--------|-------------|
| Read | `r` | Open the file |
| Write | `w` | Make changes to the file |
| Execute | `x` | Run the file (scripts or applications) |

### User Management

| Command | Description |
|---------|-------------|
| `su` | Switch users |

---

## Part 3 (10/9/2026)

### Text Editors

| Editor | Description |
|--------|-------------|
| `nano` | One of the terminal text editors |
| `nano [filename]` | Create or edit a file using nano |
| `vim` | A more advanced text editor |

### File Transfer

| Command | Description |
|---------|-------------|
| `wget` | Download files |
| `scp` | Secure copy - transfer files between computers using SSH (authentication & encryption) |

**SCP Example:**
```bash
scp important.txt ubuntu@192.168.1.30:/home/ubuntu/transferred.txt
```

### Process Management

| Command | Description |
|---------|-------------|
| `ps` | Provides a list of running processes (like task manager) |
| `ps aux` | See processes run by other users and those without session |
| `kill` | Terminate processes |
| `fg` | Bring background process back to terminal foreground |

### System Service Management

| Command | Description |
|---------|-------------|
| `systemctl` | Interact with systemd process/daemon |

**Syntax:**
```bash
systemctl [option] [service]
```

**Available Options:**

| Option | Description |
|--------|-------------|
| `start` | Start a service |
| `stop` | Stop a service |
| `enable` | Enable a service (auto-start on boot) |
| `disable` | Disable a service |
| `status` | Check status of a service |

**Example:**
```bash
systemctl start nginx
systemctl enable nginx
systemctl status nginx
```


