nux Filesystem Navigation

### Objective
Practice navigating and understanding the Linux filesystem using the command line.

### Commands

```bash
pwd
ls
ls -l
ls -a
cd <directory>
cd ..
cd ~

### 2. File & Directory Operations

```markdown
## 2. File & Directory Operations

### Objective
Practice creating, copying, moving, and managing files and directories.

### Commands

```bash
mkdir -p /app/src/main
touch index.html
cp source destination
mv old new
ls -R /appi

### 4. File & Directory Deletion

```markdown
## 4. File & Directory Deletion

### Objective
Practice removing files and directories while following safe deletion procedures.

### Commands

```bash
pwd
ls
rm -i filename
rm -rf directory


### 5. Log Inspection

```markdown
## 5. Log Inspection

### Objective
Inspect files and logs using Linux command-line tools.

### Commands

```bash
cat filename
less filename
head filename
tail filename


### 6. Real-Time Log Monitoring

```markdown
## 6. Real-Time Log Monitoring

### Objective
Monitor new log entries as they are generated.

### Command

```bash
tail -f /var/log/syslog


### 7. User & Group Identification

```markdown
## 7. User & Group Identification

### Objective
Identify the current Linux user and inspect user/group information.

### Commands

```bash
whoami
id


### 8. Linux File Permissions

```markdown
## 8. Linux File Permissions

### Objective
Understand and modify Linux file permissions.

### Commands

```bash
ls -l
chmod 754 filename

### 9. File Ownership

```markdown
## 9. File Ownership

### Objective
Inspect and manage file ownership in Linux.

### Commands

```bash
ls -l filename
chown user:group filename
ls -l filename


### 10. Web Application Setup Mission

```markdown
## 10. Web Application Setup Mission

### Objective
Apply the Linux command-line skills to create and manage a basic application structure.

### Commands

```bash
mkdir -p /app/logs
touch /app/config.conf
echo "Started" > /app/logs/server.log
pwd
ls -R /app
mv /app/logs/server.log /app/logs/server.bak
ls -l /app/config.conf  
