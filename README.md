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

- ## Progress Update – Bandit 22-26

### New Tools Learned
- `md5sum` – MD5 hashing
- `cut` – cut text fields
- `cron` / `crontab` – scheduled tasks
- `more` / `less` – pagers
- `vi` – editor (shell escape)

### New Concepts
- **cron jobs** – scheduled tasks
- **Reading and analyzing shell scripts**
- **Command substitution** `$(...)`
- **Writing my first shell script**
- **Brute-force scripting** – trying all combinations
- **setuid binaries** – privilege escalation
- **Shell escape** – breaking out of a pager into a shell
- **Terminal size matters** – affects program behavior

### Bandit Levels Completed
- Level 0-26 ✅ (27 levels)

### Challenges I Faced
- Shell escape from `more`/`less` took several attempts
- Understanding script logic required careful reading
- Brute-force script needed patience and testing

- An manchen Tagen denke ich, dass ich überhaupt nichts verstehe...  dann gibt es aber glücklicherweise Tage wie heute, an denen es "runder" läuft

alles in allem also keine gleichförmige Entwicklung in Bezug auf meine Lernkurve :P

### Next Steps
- Bandit 27+ (Git)
- TryHackMe Pre-Security
- Python basics
