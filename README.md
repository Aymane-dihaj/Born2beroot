# Born2beroot


- **What is LMV?**

LMV (Logical Volume Manager) is an abstraction layer between a storage device and a file system. it takes a group of physical disks and creates a volume group, and from then from within that volume group, you create logical volumes(swap, root, home...).

- the main advantage of using LMV: we have much more flexibility in the management of partitions.

> NB: By using LMV we can expand the storage of any partition(with a logical volume).
> 
- **Physical Volume (PV):** physical storage device. it can be a hard disk, an SD card, etc...

 Volume Group (VG): to use the space provided by a PV, it must be allocated in a volume group.

- **Logical Volume (LV):** These devices will be the ones we will use to create file systems, swap virtual machines, etc...

> NB: If the VG is the storage disk the LV are the partitions that are made on the disk.
> 
- Differences between Debian and CentOS:
    1. Debian it easier the install and use.
    - CentOS is not easy the install.
    
     2. Debian has a GUI **(graphical user interface).**
    
    - CentOS does not have an easy GUI.
- **What is the difference between software and operating system?**
    - System software is the software that manages the resources and allows a user to interact with the system.
    - The operation system acts as the interface between the user and the computer hardware
- **What is APT (Advanced Package Tool)?**
    
    used to install all the necessary dependencies when installing a program.
    
- **Differences between apt and aptitude:**
    
    When you want to install packages using the apt then apt if found a wrong Advantage, does nothing unlike aptitude if he finds any wrong Advantages update them and install the package without any problem.
    
- **What is '/dev' in Linux?**
    
    The front "/" is the root in Linux, and "dev" is a directory file containing device files under root, the root file system contains all the tools to keep the system on.
    
- **\boot:**
    
    the boot partition is the disk partition that contains the operating system folder, and also a primary partition that contains the boot loader.
    
- **What is /dev/sda in Linux ?**
    
    The term ' sd ' stands for SCSI (Small System Computer Interface) disk, so ' sda ' mean means the first SCSI hard disk, each partition in the disk takes names such as 'sda1',  'sda2', etc...
    
- **MAJ:MIN :**
    
    "Major and Minor numbers", the Major number is the device driver number, and the Minor number is the number of the device itself.
    
- **Ext4 :**
    
    The ext4 file system is an upgraded version of the ext3 file system and can support files and file systems up to 16 terabytes in size.
    
- **difference between primary and logical partition?**
    
    only 4 primary partitions can exist on a single disk, the. number of logical partitions that can exist on a disk is unlimited.
    
- **What is a mount point?**
    
    a mount point is a directory on a file system that is logically linked to another file system.
    
- **Swap area:**
    
    Swap space in Linux is used when the amount of physical memory (RAM) is full. If the system needs more memory resources and the RAM is full, inactive pages in memory are moved to the swap space.
    
- **SSH :**
    
    ssh or Secure Shell is a network communication protocol that enables two computers to communicate.
    
- **SSH layers:**
    
    **Transport layer:** ensure secure communication between the server and the client, monitoring data encryption/decryption.
    
    **authentication layer:** Conducts the client authentication procedure.
    
    **Connection layer:** Manages communication channels after the authentication.
    
- **what is a server?**
    
    a server is a computer program or device that provides a service to another computer program and its users.
    
- **/etc :**
    
    contains all the system configuration files. whenever you want to change something that affects all users of your computer - such as how you connect to the internet, or what kind of video card you have - you'll probably have to log on as root and change a file in /etc.
    
- **What is a port?**
    
    a port is NOT a physical connection.
    
    It’s a logical connection that's used by programs and servers to exchange information.
    
    it specifically determines which program or service on a computer or server is going to be used.
    
- **what is a hypervisor?**
    
    -A hypervisor is the virtual machine monitor, which is software that creates and runs a virtual machine.
    
    -A hypervisor allows one host computer to support multiple guest virtual machines by virtually sharing its resources like memory, CPU…
    
- **what is the server?**
    
    A server is a computer program or device that provides a service to another computer program.
    
    > **NB:** The kernel has 4 jobs :
    > 
    > 
    > Memory management, Process management, Device drivers, System calls, and security.
    > 
- **what is AppArmor?**
    
    AppArmor is an app that allows us to restrict access to some apps, and programs… and allow access to only some parts of the system.
    
- **What is TCP?**
    
    TCP stands for Transmission Control Protocol a communications standard that enables applications, programs.. and computer devices to exchange messages over a network.
    
- **What is IP?**
    
    An IP (Internet Protocol) address uniquely identifies a computer/server on the Internet.
    
- **What is TTY:**
    
    Linux operating system represents everything in a file system,  The terminal is also represented as a file. There’s a command exists called tty which displays information related to the terminal.
    
- **what is UFW?**
    
    A firewall, which stands for **uncomplicated firewall**, a firewall is a network security system that prevents unauthorized access from entering a private network.
    
- **what is cron and crontab**?
    - **Cron:** comes from chron, the Greek prefix for ‘time’.  Cron is a method to automatically run commands on a schedule. A scheduled job is called a **cronjob**, and it’s created in a file called crontab. it’s the easiest and oldest way for computer users to automate their tasks.
- **What is Wall command?**
    
    wall command in linux used to write a message to all users. This command display a message, or the content of a file.
    

✏️**By Nozel**
