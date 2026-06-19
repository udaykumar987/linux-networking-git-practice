# Linux Commands Documentation

## 1. pwd
Purpose: Display the current working directory.

Example:
```bash
pwd
```

---

## 2. ls
Purpose: List files and directories.

Example:
```bash
ls
ls -l
ls -a
```

---

## 3. cd
Purpose: Change the current directory.

Example:
```bash
cd /home/user
cd ..
cd ~
```

---

## 4. mkdir
Purpose: Create a new directory.

Example:
```bash
mkdir project
mkdir -p demo/test
```

---

## 5. touch
Purpose: Create an empty file.

Example:
```bash
touch file1.txt
```

---

## 6. cp
Purpose: Copy files or directories.

Example:
```bash
cp file1.txt file2.txt
cp -r dir1 dir2
```

---

## 7. mv
Purpose: Move or rename files.

Example:
```bash
mv file1.txt backup/
mv old.txt new.txt
```

---

## 8. rm
Purpose: Remove files or directories.

Example:
```bash
rm file.txt
rm -r folder
```

---

## 9. cat
Purpose: Display file contents.

Example:
```bash
cat file.txt
```

---

## 10. grep
Purpose: Search for text inside files.

Example:
```bash
grep "error" app.log
grep -i "linux" notes.txt
```

---

## 11. find
Purpose: Search for files and directories.

Example:
```bash
find . -name "*.txt"
find /tmp -type f
```

---

## 12. chmod
Purpose: Change file permissions.

Example:
```bash
chmod 755 script.sh
chmod +x deploy.sh
```

---

## 13. chown
Purpose: Change file ownership.

Example:
```bash
sudo chown user:user file.txt
```

---

## 14. ps
Purpose: Display running processes.

Example:
```bash
ps -ef
ps aux
```

---

## 15. top
Purpose: Monitor system resource usage.

Example:
```bash
top
```
#Additional Commands for Practice

df -h          # Check disk usage
du -sh *       # Check directory sizes
free -m        # Check memory usage
uname -a       # Display system information
hostname       # Show server hostname
whoami         # Display current user
history        # Show previously executed commands
tail -f file.log   # Monitor log file in real time
head -5 file.txt   # Show first 5 lines
wc -l file.txt     # Count lines in a file
