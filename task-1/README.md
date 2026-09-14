## 1. Linux Filesystem Navigation

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
```

<img width="870" height="374" alt="Navigation-command" src="https://github.com/user-attachments/assets/79e570ed-3a49-4af3-898f-333d1057980d" />



## 2. File & Directory Operations

### Objective
Practice creating, copying, moving, and managing files and directories.

### Commands

```bash
mkdir -p /app/src/main
touch index.html
cp source destination
mv old new
ls -R /app
```

<img width="918" height="525" alt="SS6" src="https://github.com/user-attachments/assets/41f700c5-c98f-43d8-8340-05d87e88fbd9" />


## 3. File Creation & Management

### Objective
Practice creating and managing files using basic Linux commands.

### Commands

```bash
touch filename
cat filename
cp source destination
mv old new
ls -l
```

<img width="946" height="475" alt="SS7" src="https://github.com/user-attachments/assets/eedaa633-27c4-4550-82c0-fea198671bc2" />



## 4. File & Directory Deletion

### Objective
Practice removing files and directories while following safe deletion procedures.

### Commands

```bash
pwd
ls
rm -i filename
rm -rf directory
```
<img width="923" height="535" alt="SS8" src="https://github.com/user-attachments/assets/3476ba59-62e3-4009-aa31-996d2bb9d2d3" />


## 5. Log Inspection

### Objective
Inspect files and logs using Linux command-line tools.

### Commands

```bash
cat filename
less filename
head filename
tail filename
```
<img width="923" height="535" alt="SS8" src="https://github.com/user-attachments/assets/46ed4efe-53ee-4ae4-b6c4-b4b06829e4e8" />



## 6. Real-Time Log Monitoring

### Objective
Monitor new log entries as they are generated.

### Command

```bash
tail -f /var/log/syslog
```

![Real-Time Log Monitoring](


## 7. User & Group Identification

### Objective
Identify the current Linux user and inspect user/group information.

### Commands

```bash
whoami
id
```

<img width="329" height="259" alt="ss9" src="https://github.com/user-attachments/assets/046eb374-3d8e-415a-98b4-767aa3d2b225" />



## 8. Linux File Permissions

### Objective
Understand and modify Linux file permissions.

### Commands

```bash
ls -l
chmod 754 filename
```

<img width="329" height="259" alt="ss9" src="https://github.com/user-attachments/assets/ededff9a-0f00-4ccd-aa16-04ff82bc9523" />



## 9. File Ownership

### Objective
Inspect and manage file ownership in Linux.

### Commands

```bash
ls -l filename
chown user:group filename
ls -l filename
```

<img width="329" height="259" alt="ss9" src="https://github.com/user-attachments/assets/b2539890-8438-434d-b61b-bd12972ef57b" />



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
```
