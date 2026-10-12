# Automation Research

## Bash Script
A Bash script is a text file that contains Linux commands. When you run the file, the computer executes those commands one by one automatically.  
The first line `#!/bin/bash` is called the **shebang**. It tells the system to use the Bash interpreter to run the script.

## Variables
Variables are like boxes that store information. Instead of typing the same long folder path many times, we put the path inside a variable (example: `SOURCE_DIR="app-data"`).  
This makes the script easier to read and change later. If the folder name changes, you only edit one place.

## Cron Job
A cron job is a scheduled task in Linux. You tell the computer “run this command at this exact time.”  
It is very important in the cloud because servers must do backups, clean logs, or restart services automatically every day without a human typing the command.
