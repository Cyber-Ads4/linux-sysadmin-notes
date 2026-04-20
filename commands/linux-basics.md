# Linux Basic Commands Reference

## Navigation
| Command | What It Does |
|---|---|
| `pwd` | Print working directory — shows where you are |
| `ls` | List files in current directory |
| `ls -la` | List all files including hidden with details |
| `cd /path` | Change directory |
| `cd ..` | Go up one directory |
| `cd ~` | Go to home directory |

## File Management
| Command | What It Does |
|---|---|
| `touch filename` | Create empty file |
| `mkdir foldername` | Create new directory |
| `cp file1 file2` | Copy a file |
| `mv file1 file2` | Move or rename a file |
| `rm filename` | Delete a file |
| `rm -rf folder` | Delete folder and everything in it |

## Viewing Files
| Command | What It Does |
|---|---|
| `cat filename` | Display file contents |
| `less filename` | View file page by page |
| `head filename` | Show first 10 lines |
| `tail filename` | Show last 10 lines |
| `tail -f filename` | Watch file update in real time |

## System Info
| Command | What It Does |
|---|---|
| `uname -a` | Show system information |
| `df -h` | Show disk space usage |
| `free -h` | Show RAM usage |
| `top` | Show running processes |
| `htop` | Better version of top |
| `uptime` | How long system has been running |

## Networking
| Command | What It Does |
|---|---|
| `ip addr` | Show network interfaces and IP addresses |
| `ping google.com` | Test network connectivity |
| `ssh user@ip` | Connect to remote server |
| `curl ifconfig.me` | Show your public IP address |

## File Permissions
| Command | What It Does |
|---|---|
| `chmod 755 file` | Change file permissions |
| `chown user file` | Change file owner |
| `ls -la` | View file permissions |

---
*These commands will be practiced live on Dell PowerEdge R630 
running Ubuntu Server 24.04 LTS*
