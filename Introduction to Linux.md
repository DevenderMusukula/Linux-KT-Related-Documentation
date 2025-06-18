
![image](https://github.com/user-attachments/assets/f7083417-27a7-4486-b573-c3435767aff3)


# Table of contents

- What is Linux?
- What Makes Linux So Popular Among DevOps?
- Advantages of Linux
- Architecture of Linux
- Linux File System Hierarchy
- Linux Distributions (Distros)
- Linux Basic Commands

## **What is Linux?**

- Linux is a free and open-source Operating System based on Unix.

- It was originally created by Linus Torvalds with the assistance of developers in 1991.

- Linux is free to download, edit, and distribute.

- Linux is a very powerful operating system and today after so many years Linux has now become one of the most popular operating systems.

## **What Makes Linux So Popular Among DevOps?**


**$${\color{orange}**Open \space Source \space and \space Customizability**:}$$** The source code of Linux falls under the FOSS (Free and Open Source Software) category and the developers, who are its members can always view and modify the source however they want. Around the world, several countries are developing their own version of Linux and this will help all such countries to strategically develop their own OSs for specialized and strategic areas such as defense, communications, government, etc.

**$${\color{orange}**Stability \space and \space Reliability**:}$$:** Linux has a high standard as compared to other Operating Systems because there is no need to reboot the server to maintain the performance levels. Linux is famously reliable compared to other operating systems, with most users experiencing fewer issues. Part of this reliability is because Linux strongly focuses on background process management.

**$${\color{orange}**Security**:}$$:** Some people may fear that since anyone can access Linux’s source code, the OS is prone to hackers. But that’s not the case  — since so many eyes are on the source code, one can identify vulnerabilities and deal with them promptly. The result is a more robust code that’s less susceptible to cyber-attacks.

Linux also has clearly defined privileges to restrict access to those who don’t belong. Root-level access, the equivalent of administrator privileges in other operating systems, is hyper-specific to the developer. Every other user of the system is only given lower-level, limited access.

**$${\color{orange}**Scalability**:}$$:** Scalability is key to the continuity of a DevOps operation. You need to be able to grow without having to change your operating system. To do so would be expensive and time-consuming. Fortunately, Linux is scalable. The Linux kernel can store and process huge amounts of memory, and the requisite hard disk drive (HDD) capacity. You can run it on anything from IoT devices to supercomputers, and keep modifying the OS so it fits your needs.

**$${\color{orange}**Automation \space  and \space Scripting**:}$$:** Automation is the key for modern enterprises and that is one reason why companies hiring DevOps professionals are asking for Linux knowledge. Linux makes it much easier to efficiently carry the server-side work. Once the scripts are written to install server software ((MySQL, Apache, SSH, FTP, etc)), configure them, and maintain them, everything is taken care of automatically.

**$${\color{orange}**High \space Endurance**:}$$:** The uptime and availability of Linux servers are very high. Linux has the highest number of servers running on the Internet.



## **Advantages of Linux**

**$${\color{orange}**Open \space Source \space Nature**:}$$:** Open Source means the source code of the Linux software is freely available to the public. Anyone can see, modify, and distribute the software.

**$${\color{orange}**Multiuser \space and \space Multitasking**:}$$:** It is a multiuser & multitasking operating system as it can run multiple tasks simultaneously without affecting the system speed.

**$${\color{orange}**Flexibility**:}$$:** The Linux operating system is very flexible. It can be used for desktop applications, embedded systems, and server applications too. It also provides various restriction options for specific computers. We can install only the necessary components for a system.

**$${\color{orange}**Stability \space and \space Reliability**:}$$:** Linux is more stable than other operating systems. Linux does not require to reboot of the system to maintain performance levels. It rarely hangs up or slows down. It has big uptimes.

**$${\color{orange}**Security**:}$$:** The Linux security feature is the main reason that it is the most favorable option for developers. It is not completely safe, but it is less vulnerable than others. Each application needs to be authorized by the admin user. The virus is not executed until the administrator provides the access password. Linux systems do not require any antivirus program.

**$${\color{orange}**Compatibility**:}$$:** Linux is compatible with a large number of file formats as it supports almost all file formats and is compatible with most of the programming languages.

**$${\color{orange}**Portable**:}$$:** Linux OS can perform different types of hardware and the kernel of Linux supports the installation of any type of hardware environment.

**$${\color{orange}**Community \space Support**:}$$:** Linux provides large community support. We can find support from various sources. There are many forums available on the web to assist users. Further, developers from the various open-source communities are ready to help us. A vast community of users and developers regularly contribute to its improvement and are always ready to assist new users.

**$${\color{orange}**Variety \space of \space Distributions**:}$$:** There are many Linux distributions available in the market. It provides various options and flavors of Linux to the users. We can choose any distros according to our needs. Some popular distros are Ubuntu, Fedora, Debian, Linux Mint, Arch Linux, and many more.


## **_Architecture of Linux_**

![image](https://github.com/user-attachments/assets/6af2c5f2-c4bc-4bdf-91b6-edda2eb94004)


The Linux operating system's architecture mainly contains some of the components:** Hardware Layer, Kernel, System Library, System,** and **Shell utility**.

**$${\color{orange}**Hardware \space Layer**:}$$:** The Linux operating system contains a hardware layer that consists of several peripheral devices like CPU,HDD, and RAM

**$${\color{orange}**Kernel**:}$$:** The kernel is one of the core sections of an operating system. It directly interacts with system hardware and manages resources. It is responsible for each of the major actions of the Linux OS. This operating system contains distinct types of modules and cooperates with underlying hardware directly. The kernel facilitates the required abstraction for hiding details of low-level hardware or application programs in the system. There are some of the important kernel types which are mentioned below:

- Monolithic Kernel

- Microkernels

- Exo kernels

- Hybrid kernels

**$${\color{orange}**Shell**:}$$:**   It is an interface between the kernel and the user. It can afford the services of kernel. It can take commands through the user and run the functions of the kernel. The shell is available in distinct types of OSes. These operating systems are categorized into two different types, which are the graphical shells and command-line shells.

The graphical line shells facilitate the graphical user interface, while the command line shells facilitate the command line interface. Thus, both of these shells implement operations. However, the graphical user interface shells work slower as compared to the command-line interface shells.

There are a few types of these shells which are categorized as follows:

- Korn shell
  
- Bourne shell
  
- C shell
  
- POSIX shell

**$${\color{orange}**System \space Utility \space Programs**:}$$:** It is responsible for doing specialized level and individual activities.

**$${\color{orange}**System \space Libraries**:}$$:** These libraries can be specified as some special functions. These are applied for implementing the operating system's functionality and don't need code access rights for the modules of the kernel.

## **Linux File System Hierarchy**


![image](https://github.com/user-attachments/assets/3fd36d76-12ee-4589-8f0a-7cad5f81060d)


The Linux File Hierarchy Structure or the Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Unix-like operating systems. In the FHS, all files and directories appear under the root directory /, even if they are stored on different physical or virtual devices.

In Linux, everything is represented as a file system including a hardware program, files are stored in a directory and every directory contains a file with a tree structure this is called File System Hierarchy.

Root Directory represents with / (forward slash) and it is a top-level directory in Linux.

 $${\color{red} / -}$$ The base of the Linux directory is the root. This is the starting point of FSH. every directory arises from the root directory. it is represented by a forward slash (/). If someone says to look into the slash directory, they refer to the root directory

 $${\color{red} /root -}$$  Home directory for the administrative superuser, root.

 $${\color{red} /bin -}$$   user binaries

Essential command binaries that need to be available in single-user mode; for all users, e.g., cat, ls, cp.

- Contains binary executables.

- Common Linux commands you need to use in single-user modes are located under this directory.

- Commands used by all the users of the system are located here e.g. ps, ls, ping, grep, cp

 $${\color{red} /sbin -}$$   system binaries

Essential system binaries, e.g., fsck, init, route.

- Just like /bin, /sbin also contains binary executables.

- The Linux commands located under this directory are used typically by system administrators, for system maintenance purposes.

- Example: iptables, reboot, fdisk, ifconfig, swapon

 $${\color{red} /dev -}$$  device files

Essential device files, e.g., /dev/null.

- These include terminal devices, USB, or any device attached to the system.

- Example: /dev/tty1, /dev/usbmon0

$${\color{red} /var -}$$   Variable Files

- Files that dynamically change (e.g. databases, cache directories, log files, printer-spooled documents, and website content) may be found under /var

- Example: /dev/tty1, /dev/usbmon0

$${\color{red} /mnt -}$$   Temporarily mounted filesystems.

- Temporary mount directory where sysadmins can mount filesystems.

$${\color{red} /media -}$$   Mount points for removable media such as CD-ROMs

- Temporary mount directory for removable devices.

- Examples, /media/cdrom for CD-ROM; /media/floppy for floppy drives; /media/cdrecorder for CD writer

$${\color{red} /usr -}$$   Secondary hierarchy for read-only user data; contains the majority of (multi-)user utilities and applications.

- Contains binaries, libraries, documentation, and source-code for second level programs.

- **/usr/bin** - contains binary files for user programs. If you can’t find a user binary under /bin, look under /usr/bin. For example: at, awk, cc, less, scp

- **/usr/sbin** - contain binary files for system administrators. If you can’t find a system binary under /sbin, look under /usr/sbin. For example: atd, cron, sshd, useradd, userdel

- **/usr/lib** - contains libraries for /usr/bin and /usr/sbin

- **/usr/local** - contains user’s programs that you install from source. For example, when you install apache from source, it goes under /usr/local/apache2

- **/usr/src** - holds the Linux kernel sources, header files and documentation.

$${\color{red}  /etc -}$$  Host-specific system-wide configuration files.

- Contains configuration files required by all programs.

- This also contains startup and shutdown shell scripts used to start/stop individual programs.

- Example: /etc/resolv.conf, /etc/logrotate.conf.

$${\color{red} /boot -}$$  Boot loader files, e.g., kernels, initrd.

- Kernel initrd, vmlinux, grub files are located under /boot

$${\color{red} /opt  -}$$  Optional application software packages.

- Contains add-on applications from individual vendors.

- Add-on applications should be installed under either /opt/ or /opt/ sub-directory.

$${\color{red} /home  -}$$   Users’ home directories, containing saved files, personal settings, etc.

- Home directories for all users to store their personal files.

- example: /home/kishlay, /home/kv

$${\color{red}/tmp   -}$$  Temporary files. Often not preserved between system reboots and may be severely size-restricted.

- The directory contains temporary files created by the system and users.

- Files under this directory are deleted when the system is rebooted.

# Linux Distributions (Distros)


**$${\color{orange}**Ubuntu**:}$$:** A user-friendly distribution that's popular for desktop and server use.

**$${\color{orange}**Linux \space  Mint**:}$$:** Mint is based on Ubuntu and uses its repository software so some packages are common in both.

**$${\color{orange}**Debian**:}$$:** Known for its stability and strong commitment to free software principles. Ubuntu is based on Debian and was founded to improve the core bits of Debian more quickly and make it more user-friendly. Every release name of Debian is based on the name of the movie Toy Story.

**$${\color{orange}**Red \space Hat \space Enterprise \space Linux \space (RHEL)**:}$$:** Red Hat is a commercial Linux distributor. Their products are Red Hat Enterprise Linux (RHEL). Red Hat uses trademark law to prevent its software from being redistributed

**$${\color{orange}**Fedora**:}$$:** It is a project that mainly focuses on free software and provides the latest version of the software. It doesn't make its own desktop environment but uses 'upstream' software. By default, it has a GNOME3 desktop environment. It is less stable but provides the latest stuff.

**$${\color{orange}**CentOS**:}$$:**  A free and community-supported version of RHEL.CentOS is a community project that uses red hat enterprise Linux code but removes all its trademarks and makes it freely available. In other words, it is a free version of RHEL and provides a stable platform for a long time.

**$${\color{orange}**OpenSUSE**:}$$:**  It works the same as Fedora but is slightly older and more stable.

**$${\color{orange}**Arch Linux**:}$$:**  Arch Linux is an independently developed system built from scratch.

# Linux Basic Commands

**ls** – lists a directory’s content.

**pwd** – shows the current working directory’s path.

**cd** – changes the working directory.

**mkdir** – creates a new directory.

**rmdir** – removes a folder or path.

**rm** – deletes a file.

**cp** – copies files and directories, including their content.

**mv** – moves or renames files and directories.

**touch** – creates a new empty file.

**file** – checks a file’s type.

**zip** **and** **unzip** – creates and extracts a ZIP archive.

**tar** – archives files without compression in a TAR format.

**nano**, **vi** – edits a file with a text editor.

**cat** – lists, combines, and writes a file’s content as a standard output.

**grep** – searches a string within a file.

**sed** – finds, replaces, or deletes patterns in a file.

**head** – displays a file’s first ten lines.

**tail** – prints a file’s last ten lines.

**awk** – finds and manipulates patterns in a file.

**sort** – reorders a file’s content.

**cut** – sections and prints lines from a file.

**diff** – compares two files’ content and their differences.

**tee** – prints command outputs in Terminal and a file.

**locate** – finds files in a system’s database.

**find** – outputs a file or folder’s location.

**sudo** – runs a command as a superuser.

**su** – runs programs in the current shell as another user.

**chmod** – modifies a file’s read, write, and execute permissions.

**chown** – changes a file, directory, or symbolic link’s ownership.

**useradd** **and** **userdel** – creates and removes a user account.

**df** – displays the system’s overall disk space usage.

**du** – checks a file or directory’s storage consumption.

**top** – displays running processes and the system’s resource usage.

**htop** – works like top but with an interactive user interface.

**ps** – creates a snapshot of all running processes.

**uname** – prints information about your machine’s kernel, name, and hardware.

**hostname** – shows your system’s hostname.

**time** – calculates commands’ execution time.

**systemctl** – manages system services.

**watch** – runs another command continuously.

**jobs** – displays a shell’s running processes with their statuses.

**kill** – terminates a running process.

**shutdown** – turns off or restarts the system.

**ping** – checks the system’s network connectivity.

**wget** – downloads files from a URL.

**curl** – transmits data between servers using URLs.

**scp** – securely copies files or directories to another system.

**rsync** – synchronizes content between directories or machines.

**ifconfig** – displays the system’s network interfaces and their configurations.

**netstat** – shows the system’s network information, like routing and sockets.

**traceroute** – tracks a packet’s hops to its destination.

**nslookup** – queries a domain’s IP address and vice versa.

**dig** – displays DNS information, including record types.

**history** – lists previously run commands.

**man** – shows a command’s manual.

**echo** – prints a message as a standard output.

**ln** – links files or directories.

**alias** **and** **unalias** – sets and removes an alias for a file or command.

**cal** – displays a calendar in Terminal.

**apt-get** – manages Debian-based distros package libraries
