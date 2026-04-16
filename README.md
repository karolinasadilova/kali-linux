# Kali Linux

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

## Files && Folders

| Command | Description | Example |
|---------|-------------|---------|
| ls | list files | ls file.txt |
| ls -a | list all files (including hidden) | ls -a file.txt |
| ls -l | long format listing | ls -l file.txt |
| mkdir | create folder | mkdir folderName |
| touch | create file | touch fileName.txt |
| cp | copy file | cp file1.txt file2.txt |
| cp file /path | copy file to another folder | cp file.txt /home/root/Documents/ |
| mv | move or rename file/folder | mv file.txt folder/ |
| rm | remove file | rm file |
| rm -rf | remove folder and all contents | rm -rf folderName |

---

## Viewing

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

## Tree

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

