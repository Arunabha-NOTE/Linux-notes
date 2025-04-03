# How to Install a Linux Distro (using ubuntu for example)

This guide highlights three major methods to install Ubuntu. 
*(For other distributions of linux consult google or youtube.)*

---

## Overview

Ubuntu is one of the most popular Linux distributions. You can install it using:

1. **Windows Subsystem for Linux (WSL)**
2. **Virtual Machine (VM) Installation** (e.g., VirtualBox or VMware)
3. **Dual Boot Installation**

Choose the method that best suits your needs and follow the instructions below.

---

## 1. Windows Subsystem for Linux (WSL)

**Overview:**  
WSL allows you to run a Linux environment directly on Windows without the need for a full virtual machine.

**Basic Steps:**

- Verify your Windows version supports WSL (Windows 10 version 2004 and later).
- Enable the WSL feature via the "Turn Windows features on or off" settings.
- Install Ubuntu from the Microsoft Store.
- Launch Ubuntu and complete the initial setup (username, password, etc.).

**Tutorial Link:**  
[YouTube Tutorial for WSL Installation](https://www.youtube.com/watch?v=7Sym3uL6YWo&ab_channel=TroubleChute)

---

## 2. Virtual Machine (VM) Installation

**Overview:**  
Install Ubuntu in a virtualized environment using software like VirtualBox or VMware. This method allows you to run Ubuntu concurrently with your primary OS.

**Basic Steps:**

- Download and install VirtualBox or VMware.
- Download the latest Ubuntu ISO from the official website.
- Create a new virtual machine and allocate resources (RAM, disk space, etc.).
- Mount the Ubuntu ISO and start the VM.
- Follow the on-screen instructions to install Ubuntu within the virtual machine.

**Tutorial Link:**  
[YouTube Tutorial for installation of Ubuntu on VMware](https://www.youtube.com/watch?v=SgfrHKg81Qc&ab_channel=ProgrammingKnowledge)


---

## 3. Dual Boot Installation

**Overview:**  
Dual booting lets you install Ubuntu alongside your current OS (e.g., Windows) so you can choose which one to boot into at startup.

**Basic Steps:**

- **Backup:** Always back up your data before modifying partitions.
- **Create a Bootable USB:** Download the Ubuntu ISO and use a tool like Rufus to create a bootable USB drive.
- **Partitioning:** In Windows, shrink your primary partition to create space for Ubuntu.
- **Boot and Install:** Boot from the USB drive and select "Install Ubuntu alongside Windows" or "Something else" to manually partition.
- Follow the installation prompts to complete the setup.

**Tutorial Link:**  
[YouTube Tutorial for Dual Boot Installation of Ubuntu and Windows](https://www.youtube.com/watch?v=mXyN1aJYefc&ab_channel=Robtech)

---

## Additional Resources

- [Ubuntu Official Installation Guide](https://ubuntu.com/tutorials/install-ubuntu-desktop)
- [Ubuntu Community Support](https://askubuntu.com/)


