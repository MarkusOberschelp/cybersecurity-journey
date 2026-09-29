# Cybersecurity Journey

Documenting my path from zero to Offensive Security.

## Progress

### Linux & Terminal
- [x] Navigation, file system, permissions
- [x] File operations (mkdir, touch, cp, mv, rm)
- [x] Piping and redirection
- [x] OverTheWire Bandit Levels 0-21

### Tools Learned
- `xxd` – hexdump ↔ binary
- `file` – identify file types
- `strings` – extract readable text from binaries
- `grep` – search text in files
- `base64` – encode/decode Base64
- `tr` – translate/rotate characters (ROT13)
- `tar`, `gzip`, `bzip2` – compression
- `openssl s_client` – TLS connections
- `nc` – netcat, raw network connections
- `nmap` – port scanning
- `scp` – secure file transfer
- `diff` – compare files
- `find` – search files by properties
- `sort`, `uniq` – text processing

### Networking
- [x] localhost, ports, services
- [x] TLS/SSL basics
- [x] SSH keys vs. passwords
- [x] setuid binaries (privilege escalation)

## Goals
- Junior Penetration Tester 
- OSCP certification
- Specialization: Multimedia Forensics (Audio/Video/Image Steganography)

## Daily Practice

## Progress Update – Bandit 16-23

### New Tools Learned
- `openssl s_client` – TLS connections
- `nmap` – port scanning
- `scp` – secure file transfer
- `diff` – compare files
- `nc -l` – netcat listener
- `ssh -i` – SSH with key file
- `md5sum` – MD5 hashing
- `cut` – cut text fields

### New Concepts
- TLS/SSL handshake and certificates
- Port scanning and service identification
- SSH keys vs passwords
- File comparison and change detection
- Running remote commands via SSH
- setuid binaries (privilege escalation)
- Two-process communication over localhost
- **cron jobs** – scheduled tasks
- **Reading and analyzing shell scripts**
- Command substitution `$(...)`
- Piping and chaining commands

### Bandit Levels Completed
- Level 0-23 ✅ (24 levels)

### Scripts Analyzed
- `/usr/bin/cronjob_bandit22.sh` – writes password to `/tmp/<fixed-name>`
- `/usr/bin/cronjob_bandit23.sh` – writes password to `/tmp/<md5-hash>`

### Next Steps
- Bandit 24+
- TryHackMe Pre-Security
- Python basics
