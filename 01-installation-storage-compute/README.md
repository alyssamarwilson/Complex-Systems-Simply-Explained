# Installation, Storage, and Compute with Windows Server

## Building the foundation before everything else runs

This section is part of **Complex Systems, Simply Explained** — a beginner-friendly technical project designed to make core IT concepts easier to understand through analogies, visuals, PowerShell breakdowns, and practical examples.

When people hear “installation, storage, and compute,” it can sound dry or intimidating. But really, this is the foundation layer of IT. It is about setting up the environment, giving systems the resources they need, organizing storage, and making sure everything can run reliably.

---

## What this section covers

- Windows Server installation basics
- Server roles and features
- Virtualization and Hyper-V
- CPU, memory, and storage fundamentals
- Disks, volumes, and file systems
- Storage optimization
- High availability, fault tolerance, and redundancy
- Snapshots, checkpoints, and recovery tools

---

## Why it matters

Before users can sign in, files can be shared, or services can run, the system needs a strong foundation.

This topic helps explain:

- how servers get set up
- how resources are used
- how storage is organized
- how virtualization makes infrastructure more flexible
- how systems stay available and recover when something goes wrong

---

## Core concepts made simple

### Server roles = rooms in a building
A server role is like a room in a building with a specific purpose. One room might act like a front desk, another like security, and another like a mailroom.

### Virtual machines = apartments inside a building
A physical server can host multiple virtual machines, just like one building can contain separate apartments. Each one has its own purpose, space, and setup.

### CPU, memory, and storage = a kitchen workspace
- **CPU** = the cook doing the work  
- **Memory (RAM)** = the counter space for what is being used right now  
- **Storage** = the pantry where things are kept long term  

### RAID = storing items across multiple shelves
RAID helps organize data across multiple disks for better speed, protection, or both.

### Storage optimization = organizing a closet
This is about cleaning up, removing duplicates, and making the best use of available space.

### Hyper-V = multiple houses on one piece of land
Hyper-V allows one physical system to host multiple virtual systems, each running like its own separate machine.

### Server Core vs Desktop Experience
- **Server Core** = only the essentials, lightweight and efficient  
- **Desktop Experience** = the full visual environment with windows and menus  

### High availability vs fault tolerance vs redundancy
- **Redundancy** = extra backup parts  
- **High availability** = little to no downtime  
- **Fault tolerance** = keeps working even when something fails  

### Snapshots/checkpoints = save points in a game
They let you go back to an earlier state if something breaks during testing or changes.

### Volume Shadow Copy = restore point for files
This helps recover earlier versions of files without rebuilding everything from scratch.

---

## Suggested learning path

1. Start with Windows Server installation basics  
2. Learn what server roles and features do  
3. Understand virtualization and Hyper-V  
4. Study CPU, memory, and storage together  
5. Learn how disks, volumes, and file systems are organized  
6. Explore storage optimization and redundancy concepts  
7. Finish with checkpoints, snapshots, and recovery tools  

---

## PowerShell examples

These are beginner-friendly commands that connect to this section:

```powershell
Get-ComputerInfo #helps you gather overall system details
Get-WindowsFeature #shows server roles and features
Get-Disk #displays physical disk information
Get-Volume #shows volumes and storage space
Get-VM #lists virtual machines in Hyper-V 
Get-Service #checks the status of system services 
