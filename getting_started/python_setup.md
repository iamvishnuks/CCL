# Python Installation Guide

## Windows

1. Download the Python installer from the official website: **https://www.python.org/downloads/**
2. Run the installer file and follow the instructions.
3. Make sure to check the box that says **"Add Python to PATH"** before you click on Install Now.

## macOS

1. Python comes pre-installed on macOS. To upgrade, you can use Homebrew.
2. If you don't have Homebrew, install it with 
```
 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
4. Then, install Python with `brew install python`

## Linux

1. Python comes pre-installed on most Linux distributions.
2. To upgrade, you can use your distribution's package manager. Here are the commands for some popular distributions:
   - **Ubuntu, Debian**: `sudo apt-get install python3`
   - **Fedora**: `sudo dnf install python3`
   - **Arch Linux**: `sudo pacman -S python`

# Verifying Installation

To verify that Python was installed correctly, open a command prompt (Windows) or terminal (macOS or Linux) and type `python --version`. This should display the version of Python that you installed.
