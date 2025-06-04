# CN and OS 🌐🖥️
This repository Consists of my codes and The knowledge I've gained on CN and OS lab. This repository is for my future references.  

# 🖥️ OS Lab – VMware Installation Guide

This guide helps you install **VMware Workstation Player**, which is required to run virtual machines for your Operating Systems Lab.

---

## ✅ What is VMware?

**VMware Workstation Player** is a free virtualization software that lets you create and run virtual machines on your system—ideal for OS lab experiments using Linux/Unix systems.

---

## 📥 Step-by-Step: Install VMware Workstation Player on Windows

### Step 1: Download VMware Workstation Player

1. Visit the official VMware download page:  
   👉 [https://www.vmware.com/products/workstation-player.html](https://www.vmware.com/products/workstation-player.html)

2. Click **“Download Now”** under the *Workstation Player for Windows* section.

3. Save the `.exe` installer file to your system.

---

### Step 2: Run the Installer

1. Double-click the downloaded `.exe` file to launch the installer.

2. Click **“Next”** on the welcome screen.

3. Accept the **License Agreement**, then click **Next**.

4. On the **User Experience Settings** screen, you may choose to:
   - Check or uncheck “Check for product updates on startup.”
   - Uncheck “Join VMware Customer Experience Program” if you don’t want to participate.

5. Choose the default installation path (or change it if required), and click **Next**.

6. Click **Install** to begin the installation.

---

### Step 3: Complete the Installation

1. Once installed, click **Finish**.

2. You may need to restart your system.

3. You’ll now see **VMware Workstation Player** in your Start Menu.

---

### Step 4: Launch VMware Workstation Player

1. Open **VMware Workstation Player**.

2. On first launch, you may be asked:
   - Whether you’re using the software for **personal non-commercial use** – select this option (it’s free for students).

3. Click **Continue**, then **Finish**.

---

## 💡 Ready to Go!

You’ve successfully installed VMware! You can now:
- Create new virtual machines
- Install operating systems like Ubuntu, Kali Linux, etc.
- Run OS-level experiments for lab work

---

##  Recommended Next Step

👉 Download an ISO (e.g., Ubuntu):  
[https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)  
You can use this ISO to create a virtual machine in VMware.


## 🛠️ Need Help.?

If you face any issues:
- Double-check system requirements (Windows 10+, 64-bit)
- Run installer as administrator
- Check if virtualization is enabled in BIOS

---
# 🌐🤖 Operating Systems & Computer Networks Lab 

This repository contains implementations of various lab experiments related to **Computer Networks** and **Operating Systems** using C, Shell scripting, and basic networking protocols.

---

## 📋 List of Experiments

### 🔗 Computer Networks Experiments

1. **Framing Methods (Character Stuffing & Bit Stuffing)**
   - Implement data link layer framing methods:
     - Character Stuffing
     - Bit Stuffing

2. **CRC Implementation**
   - Perform error detection using:
     - CRC-12
     - CRC-16 polynomial on a character dataset

3. **Stop and Wait Protocol**
   - Implement a reliable communication protocol using stop-and-wait mechanism.

4. **Sliding Window Protocol**
   - Simulate data transmission using the sliding window protocol.

5. **Dijkstra’s Algorithm**
   - Compute the shortest path in a graph using Dijkstra's algorithm.

6. **Broadcast Tree Generation**
   - Generate a broadcast tree for a given subnet of hosts.

7. **Collision-Free Protocol**
   - Implement a network communication protocol with collision avoidance.

---

### 🐧 Linux System & Shell Scripting

8. **Linux Commands Practice**
   - a) Study basic Linux utilities:
     - File handling, Process control, Disk usage, Networking tools, Filters
   - b) Implement the following commands:
     - `cp` (copy)
     - `mv` (move/rename)

9. **Shell Scripting and IPC**
   - a) Shell script to find factorial of a given integer  
   - b) C program to create a child process:
     - Parent displays `"parent"`  
     - Child displays `"child"`
   - c) C program using a pipe:
     - Parent writes message to pipe  
     - Child reads and displays the message

---

### ⚙️ Operating Systems Simulations

10. **CPU Scheduling – Part 1**
   - Simulate the following algorithms using C:
     - First Come First Serve (FCFS)
     - Priority Scheduling

11. **CPU Scheduling – Part 2**
   - Simulate:
     - Shortest Job First (SJF)
     - Round Robin (RR)

12. **File Allocation Strategies**
   - Simulate:
     - Sequential Allocation
     - Linked Allocation
     - Indexed Allocation

13. **Memory Management Techniques**
   - Simulate:
     - Paging
     - Segmentation

14. **Page Replacement Algorithms**
   - Simulate:
     - FIFO (First In First Out)
     - LRU (Least Recently Used)
     - Optimal Replacement

---

## 🛠 Technologies Used

- 💻 C Programming
- 🐚 Bash Shell Scripting
- 🐧 Linux (Ubuntu/VM-based)
- 🧮 Graph Algorithms
- 📡 Networking Protocols
