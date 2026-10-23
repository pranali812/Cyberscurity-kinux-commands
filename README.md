# Cyberscurity-kinux-commands
Essential Linux and Kali Linux commands for cybersecurity learning and interview preparation.
# Cybersecurity Linux Commands Cheat Sheet

## About
This repository contains essential Linux commands for cybersecurity beginners, ethical hacking practice, and interview preparation.

## Topics Covered
- Basic Linux Commands
- File and Directory Management
- Linux File Permissions
- Networking Commands
- Nmap Scanning
- Process Management
- Log Analysis
- File Hashing
- Kali Linux Security Tools

# Cybersecurity Linux Commands Cheat Sheet

A beginner-friendly collection of Linux commands for cybersecurity learning, Kali Linux practice, and interview preparation.

## 1. Basic Commands

| Command | Purpose |
|---|---|
| `pwd` | Show current directory |
| `ls -la` | List all files |
| `cd` | Change directory |
| `whoami` | Show current username |
| `clear` | Clear terminal |
| `history` | Show command history |
| `uname -a` | Show system information |

## 2. File Management

| Command | Purpose |
|---|---|
| `touch file.txt` | Create a file |
| `mkdir project` | Create a directory |
| `cat file.txt` | Display file contents |
| `cp a.txt b.txt` | Copy a file |
| `mv old.txt new.txt` | Rename a file |
| `rm file.txt` | Delete a file |

## 3. Networking Commands

| Command | Purpose |
|---|---|
| `ip addr` | Display IP addresses |
| `ip route` | Display routing information |
| `ping 127.0.0.1` | Test local network stack connectivity |
| `ss -tuln` | Show listening ports |
| `dig example.com` | Query DNS |
| `curl -I https://example.com` | Inspect HTTP headers |

## 4. Permissions and Users

| Command | Purpose |
|---|---|
| `ls -l` | View permissions |
| `chmod +x script.sh` | Make a script executable |
| `id` | Display user and group IDs |
| `groups` | Display group memberships |
| `sudo command` | Run a command with elevated privileges |

## 5. Cybersecurity Tools

| Tool | Purpose |
|---|---|
| Nmap | Network discovery and port scanning |
| Wireshark | Network packet analysis |
| tcpdump | Capture network packets |
| Burp Suite | Web application security testing |
| John the Ripper | Password hash auditing |

## 6. File Integrity

```bash
sha256sum file.txt
file document.pdf
stat file.txt
```

- `sha256sum`: Calculates a file's SHA-256 hash.
- `file`: Identifies a file type.
- `stat`: Displays file metadata.

## 7. Package Management

```bash
sudo apt update
apt search nmap
sudo apt install nmap
```

## Practice Guidelines

- Practise commands in your Kali Linux virtual machine.
- Test security tools only on systems you own or have permission to assess.
- Never upload passwords, private keys, or sensitive logs.

## Learning Goals

Linux fundamentals, networking, file permissions, log analysis, and cybersecurity tool basics.
