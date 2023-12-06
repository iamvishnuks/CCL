# Guide to Install Linux 

## Option 1: Linux on a Virtual Machine (VM)

1. *Step 1*: Download and install a VM software like [VirtualBox](https://www.howtogeek.com/796988/how-to-install-linux-in-virtualbox/) or [VMware](https://www.makeuseof.com/tag/install-linux-windows-vmware-virtual-machine/).
2. *Step 2*: Download the ISO file for the Linux distribution you want to use.
3. *Step 3*: Create a new VM in your VM software and select the downloaded ISO file as the installation source.
4. *Step 4*: Follow the prompts to install Linux.

## Option 2: [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/linux/install)

1. *Step 1*: Open PowerShell or Windows Command Prompt in administrator mode.
2. *Step 2*: Enter the command wsl --install, then restart your machine.
3. *Step 3*: The first time you launch a newly installed Linux distribution, a console window will open and you'll be asked to wait for files to de-compress and be stored on your machine.
4. *Step 4*: Change the default Linux distribution installed using the -d flag. To change the distribution installed, enter: wsl --install -d <Distribution Name>.
5. *Step 5*: Set up your Linux user info. Once the process of installing your Linux distribution with WSL is complete, open the distribution (Ubuntu by default) using the Start menu. You will be asked to create a User Name and Password for your Linux distribution.

## Option 3: Direct Linux [Installation](https://www.howtogeek.com/693588/how-to-install-linux/)

1. *Step 1*: Choose a Linux distribution and download its ISO file.
2. *Step 2*: Create a bootable USB drive with the downloaded ISO file.
3. *Step 3*: Boot the system from the USB drive.
4. *Step 4*: Follow the prompts to install Linux.

Each method has its own advantages and trade-offs. Choose the one that best fits your  objectives and the technical capabilities.
