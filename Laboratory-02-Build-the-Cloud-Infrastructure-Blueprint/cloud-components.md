# Cloud Infrastructure Components

## 1. Compute Resources
**Purpose:**  
Compute resources are the processing power of a system. This includes the CPU model and the number of cores that perform calculations and run applications.

**Importance in Cloud Computing:**  
Compute resources are important because they determine how fast applications and services can run. In the cloud, users can easily scale compute power up or down depending on demand without buying physical servers.

**Relation to KillerCoda:**  
In the KillerCoda Linux environment, the compute resources are the CPU model and the number of CPU cores that I checked using the `lscpu` and `nproc` commands.

## 2. Storage Resources
**Purpose:**  
Storage resources are used to save and keep data, files, and applications. This includes the hard disk capacity and the mounted file systems.

**Importance in Cloud Computing:**  
Storage is important because data needs a place to be stored securely and accessed when needed. Cloud storage allows data to be available anytime and can be expanded easily.

**Relation to KillerCoda:**  
In KillerCoda, the storage resources are the disk capacity and mounted file systems that I checked using the `df -h` and `lsblk` commands.

## 3. Networking Resources
**Purpose:**  
Networking resources allow computers and services to communicate with each other and with the internet. This includes the IP address and network interfaces.

**Importance in Cloud Computing:**  
Networking is important because cloud services need to connect users, applications, and data across different locations. Without networking, cloud resources cannot communicate.

**Relation to KillerCoda:**  
In the KillerCoda environment, the networking resources are the IP address and network configuration that I checked using the `ip addr` and `hostname -I` commands.

## 4. Operating System
**Purpose:**  
The operating system manages all the hardware and software resources of the computer. It acts as the bridge between the user and the hardware.

**Importance in Cloud Computing:**  
The operating system is important because it provides the environment where applications and cloud services run. Most cloud servers use Linux because it is stable, secure, and efficient.

**Relation to KillerCoda:**  
In KillerCoda, the operating system is the Linux distribution and kernel version that I checked using the `cat /etc/os-release` and `uname -r` commands.




