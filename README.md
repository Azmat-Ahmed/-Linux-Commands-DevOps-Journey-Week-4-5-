# 🐧 Linux Commands – DevOps Journey (Week 4 & 5)

Welcome to my Linux learning repository, where I documented everything I learned during **Week 4 & 5** of my DevOps journey. This is part of my commitment to becoming a **professional DevOps engineer**.

> 🎓 I started this after completing my 4th semester exams (BS Computer Science) on **1st July**.  
> 📅 I dedicated the following **2 weeks** to learning **Linux from scratch to advanced**.  
> 🧱 Linux is the foundation of DevOps, and this journey is now complete ✅

---

## 📚 What I Learned

✅ What Linux is and how it works internally  
✅ Filesystem hierarchy and Linux architecture  
✅ File and folder management  
✅ Process and memory management  
✅ Networking and disk utilities  
✅ Package management (`apt`, `yum`)  
✅ Permissions, ownerships, and groups  
✅ System services with `systemctl`  
✅ Transferring files between systems  
✅ Monitoring logs, CPU, memory, disk  
✅ Preparing for shell scripting (coming Week 6)

---

## 💻 Linux Commands I Practiced

### 🔸 File & Directory Management
```bash
ls        # list files and directories
cd        # change directory
pwd       # print working directory
mkdir     # make new directory
rmdir     # remove empty directory
rm        # remove file or directory
cp        # copy files
mv        # move or rename files
touch     # create empty file
cat       # view file content
less      # scroll through file
head      # show first N lines
tail      # show last N lines
nano      # edit file (CLI text editor)
🔸 User & Permission Management
bash
Copy
Edit
whoami       # current user
id           # user ID and group ID
chmod        # change file permissions
chown        # change ownership
groups       # list groups
useradd      # add new user
usermod      # modify user
passwd       # set or change password
groupadd     # create new group
🔸 Process Management
bash
Copy
Edit
ps           # show running processes
top          # real-time system info
htop         # advanced top (if installed)
kill         # stop a process by PID
killall      # stop all by name
nice         # set priority
jobs         # show background jobs
fg / bg      # bring job to foreground/background
🔸 Disk & Filesystem
bash
Copy
Edit
df -h        # disk space usage
du -sh       # directory size
mount        # mount a drive
umount       # unmount drive
lsblk        # list block devices
fdisk -l     # list partitions
mkfs.ext4    # format partition
🔸 Package Management
bash
Copy
Edit
apt update           # update repo (Debian/Ubuntu)
apt install <pkg>    # install package
apt remove <pkg>     # remove package
yum install <pkg>    # (RedHat/CentOS)
🔸 Networking
bash
Copy
Edit
ping            # test connectivity
ifconfig        # view IP config (older)
ip addr         # view IP config (modern)
netstat -tulpn  # show network ports
ss -tuln        # modern netstat
curl            # fetch web content
wget            # download files
hostname        # show/set hostname
🔸 Archiving & Compression
bash
Copy
Edit
tar -cvf        # create tar
tar -xvf        # extract tar
zip/unzip       # compress/extract zip
gzip/gunzip     # compress/extract gzip
🔸 File Search & Filters
bash
Copy
Edit
find         # search for files
grep         # search inside files
locate       # fast file finder
which        # show binary path
whereis      # locate binaries and man pages
🔸 System Monitoring & Logging
bash
Copy
Edit
uptime          # show how long system is up
free -h         # memory usage
dmesg           # kernel messages
journalctl      # systemd logs
history         # view command history
watch           # run command repeatedly
🔸 File Transfer & Remote Access
bash
Copy
Edit
scp             # secure copy
rsync           # sync directories/files
ssh             # remote login
🔸 Misc
bash
Copy
Edit
man <cmd>       # manual page for command
alias           # shortcut for commands
echo            # print to terminal
date            # show date & time
cal             # calendar
clear           # clear terminal
📌 Folder Structure (optional for repo)
bash
Copy
Edit
📁 linux-commands-devops-journey
│
├── 📄 README.md         # This file
├── 📁 notes/            # Optional personal notes
├── 📁 cheatsheets/      # Custom cheatsheets
├── 📁 examples/         # Bash practice scripts or sample outputs
🔜 What's Next?
➡️ Week 6 of DevOps Journey: Shell Scripting
I'll be learning how to automate Linux tasks with powerful bash scripts.

🧠 Final Words
Linux is not just a tool — it's the foundation of all DevOps work.
From EC2 to Kubernetes, everything runs on Linux in the backend.
I now feel confident to move forward in my journey toward becoming a DevOps engineer. 💪

🌐 Connect with me
🔗 LinkedIn

🧠 Hashnode Blog

🧑‍💻 Dev.to

📅 Completed: July 1 – July 13, 2025
📘 Status: ✅ Finished Linux Fundamentals
🛠️ Author: Azmat Awan

📌 License
This repository is for learning and documentation purposes. Feel free to use or fork.

markdown
Copy
Edit

---

## ✅ What to Do Next:

1. **Create a new GitHub repository** (name suggestion: `linux-commands-devops-journey`)
2. Add a `README.md` file.
3. Paste the content above.
4. Optionally add:
   - A folder with notes or screenshots
   - Shell script samples later in your journey

Let me know if you want help with creating GitHub folders, sample `.sh` files, or badges like `Linux Mastery
