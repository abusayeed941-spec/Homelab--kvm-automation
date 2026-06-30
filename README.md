
# Nested Linux Lab & Bash Gateway Automation

An automated, multi-layered Red Hat Certified System Administrator (RHCSA) practice infrastructure environment. This project uses nested virtualization, secure shell automation, and custom bash interface scripts to simulate enterprise terminal testing environments.

## 🏗️ Architecture Layout
* **Host Layer:** Windows 11 Hypervisor Engine (VMware Workstation)
* **Workstation Desktop Layer:** antiX Linux (Lightweight Client Desktop Environment)
* **Enterprise Target Layer:** Kernel-based Virtual Machines (KVM/QEMU via `virt-manager`) hosting Rocky Linux 9 nodes (`servera` & `serverb`)

## 🛠️ Tech Stack & Skills Showcased
* **Virtualization:** KVM, QEMU, libvirt (`virsh`), VMware Workstation
* **Automation & Scripting:** Linux Bash Scripting (`case` blocks, terminal routing)
* **Networking:** Private virtual bridges, SSH Key pair authentication (`ed25519`), static IP routing, `/etc/hosts` resolution
* **Desktop Engineering:** X11 Application Launchers (`.desktop` system configurations)

## 📁 Repository Structure
* `/bin/exam-terminal.sh` - The interactive terminal connection manager gateway script.
* `/desktop/` - Custom GUI launcher shortcut profiles (`.desktop` configurations).
* `/html/rhcsa_exam.html` - Local task management presentation dashboard template.

## 🚀 Key Features Implemented
1. **Automated SSH Bridge:** Secure keyless pass-through linking management stations to virtual targets via shared `authorized_keys`.
2. **Terminal Session Management:** Custom wrapper-friendly routing scripts that sidestep strict desktop environment D-Bus permission blocks.
3. **Isolated Testing Architecture:** Complete sandbox configurations where all virtual services, file permission changes, and operations survive full reboots.
## 💾 Project Downloads & Media
* 📁 **[Download the antiX ISO System Backup here] [(https://drive.google.com/drive/folders/16y6ctboccNbmYVeIaGHvZyz3dEZd-9WH)**
  

