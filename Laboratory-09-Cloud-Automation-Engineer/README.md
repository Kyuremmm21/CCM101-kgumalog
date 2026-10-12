# Laboratory 09 – Cloud Automation Engineer

## Mission Overview
In this laboratory, I learned how to write a Bash script that automatically backs up a folder and how to schedule it with Cron so it runs every night without human help.

## Objectives
- Understand Bash script syntax and variables
- Use nano to write and save scripts
- Change file permissions with chmod
- Schedule tasks with crontab
- Document everything in Markdown

## Commands Executed
```bash
mkdir app-data
echo "This is critical client data." > app-data/data.txt
nano backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
crontab -l
env EDITOR=nano crontab -e
crontab -l
```
