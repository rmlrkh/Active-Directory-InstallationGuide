# Active Directory Installation Guide
This project provides a comprehensive guide to installing and configuring Active Directory using VirtualBox. 
It includes steps for setting up a Windows Server 2022 as a domain controller and connecting a client PC to the domain.

# Prerequisites

- [VirtualBox](https://www.virtualbox.org/) installed on your computer.
- ISO files for [Windows Server 2022](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022) and Windows client (e.g., [Windows 10](https://www.microsoft.com/en-ca/software-download/windows10)).
- Basic understanding of networking concepts.

## Setting Up VirtualBox

### Installing VirtualBox

Download and install VirtualBox from [here](https://www.virtualbox.org/).
![VirtualBox installation](/images/1.png)

## Creating Virtual Machines

### Create a Domain Controller (Windows Server 2022) VM

1. Open VirtualBox and click on `New`.
2. Name the VM (e.g., `DC-01`) and select `Microsoft Windows` and `Windows 2022 (64-bit)`.
3. Allocate at least 2GB of RAM.
4. Create a virtual hard disk (VDI) with at least 20GB of storage.
5. Attach the Windows Server ISO to the VM's optical drive.

### Create a Client PC (Windows 10) VM

1. Follow similar steps to create another VM (e.g., `Client-PC`).
2. Allocate at least 2GB of RAM.
3. Attach the Windows 10 ISO to the VM's optical drive.

