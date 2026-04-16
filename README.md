# kali-linux
# Kali Linux Commands Cheat Sheet

---

## Navigation

| Command | Description |
|---------|-------------|
| pwd | print working directory |
| cd | change directory |
| cd .. | go one level up |
| cd . | stay in current directory |
| cd ~ | go to home directory |

---

## File & Folder Management

| Command | Description |
|---------|-------------|
| ls | list files |
| ls -a | list all files |
| ls -l | long format list files |
| mkdir | create folder (mkdir folderName) |
| touch | create file (touch file.txt) |
| cp | copy file (cp file1 file2) | cp password1.txt password2.txt...creates copy file and names it password2.txt
| cp file /path | copy file to another folder | cp file.txt /home/root/Documents...copies into that folder
| mv | move file or folder |
| rm | remove file |
| rm -rf | remove folder and content inside |

---

## File Viewing

| Command | Description |
|---------|-------------|
| cat | display file content |
| less | view file page by page |
| head | show first 10 lines |
| tail | show last 10 lines |

---

## Controls

| Key | Action |
|-----|--------|
| Space | next page |
| q | quit |

---

## Tree structure

| Command | Description |
|---------|-------------|
| tree | show tree folder && file structure |

---

## Help

| Command | Description |
|---------|-------------|
| man | detailed manual |
| --help | short help |

---

## Searching

| Command | Description |
|---------|-------------|
| find . -type f -name "*.txt" | find all .txt files |
| find . -type f -name "passwords" | find file named passwords |
| find . -type d -name Desktop | find folder Desktop |
| find . -type f -name "pass*" | find files starting with "pass" |
| find . -type f -mtime -1 | files modified in last 24h |

---

## Updates 

| Command | Description |
|---------|-------------|
| apt-get update | refresh package list |
| apt-get upgrade | install available updates |

---

## Users

| Command | Description |
|---------|-------------|
| passwd root | change root password |
