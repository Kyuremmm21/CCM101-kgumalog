# Laboratory 08 – Cloud Security Engineer

## Mission Overview
In this laboratory, I acted as a Cloud Security Engineer at CloudNova Technologies. A junior developer deployed an Ubuntu server without proper security. My task was to lock down the server using the Uncomplicated Firewall (UFW), apply the Default Deny policy, and only allow the necessary ports (SSH and 8080) for the web application.

## Objectives
- Understand the Principle of Least Privilege and Attack Surface
- Perform a basic security audit of open ports
- Configure UFW with a Default Deny policy
- Allow only SSH and HTTP traffic on port 8080
- Document firewall rules and security best practices
- Continue building my GitHub Cloud Computing Portfolio

## Commands Executed
```bash
# Deploy the web application
docker run -d --name secure-web-app -p 8080:80 nginx
```
# Allow SSH
```
sudo ufw allow ssh
```
# Set Default Deny policy
```
sudo ufw default deny incoming
sudo ufw default allow outgoing
```
# Enable the firewall
```
sudo ufw enable
```
# Allow web traffic
```
sudo ufw allow 8080/tcp
```
# Check status
```
sudo ufw status verbose
sudo ufw status numbered
```
