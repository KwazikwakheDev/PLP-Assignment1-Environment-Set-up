# Developer Environment Setup Guide

This is the how I set up my environment for Power Learn Project(PLP)

## Table of Contents
1. [Select Your Operating System (OS)](#1-select-your-operating-system-os)
2. [Install a Text Editor or Integrated Development Environment (IDE)](#2-install-a-text-editor-or-integrated-development-environment-ide)
3. [Set Up Version Control System](#3-set-up-version-control-system)
4. [Install Necessary Programming Languages and Runtimes](#4-install-necessary-programming-languages-and-runtimes)
5. [Install Package Managers](#5-install-package-managers)
6. [Configure a Database (MySQL)](#6-configure-a-database-mysql)
7. [Set Up Development Environments and Virtualization (Optional)](#7-set-up-development-environments-and-virtualization-optional)
8. [Explore Extensions and Plugins](#8-explore-extensions-and-plugins)
9. [Document Your Setup](#9-document-your-setup)
10. [Sample Project and Reflection](#10-sample-project-and-reflection)

## 1. Select Your Operating System (OS)
Chose an operating system that best suits my preferences and project requirements which was windows 11
**Downloade and Installed Windows 11**: [Windows 11 Download](https://www.microsoft.com/software-download/windows11)

## 2. Installed a Integrated Development Environment (IDE)
Select and install a text editor or IDE suitable for your programming languages and workflow.
I choose the Visual Studio code because of it user interface.
**Download and Install Visual Studio Code**: [Visual Studio Code Download](https://code.visualstudio.com/Download)

## 3. Set Up Version Control System
Installed Git and configured it into my local machine. I already had a GitHub account for hosting my repositories. Initialized a Git repository for my project and made my  first commit.

**GitHub**: [GitHub](https://github.com)
### Steps:
1. **Install Git**:
    - Windows: Downloaded the Git installer from [git-scm.com](https://git-scm.com/download/win) and followed the installation instructions.
2. **Configure Git**:
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    
3. **Create a GitHub Account**:
    - Sign up at [GitHub](https://github.com).
4. **Initialize a Git Repository**:
    mkdir my-project
    cd my-project
    git init
    echo "# My Project" > README.md
    git add README.md
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin https://github.com/yourusername/my-project.git
    git push -u origin main

## 4. Install Necessary Programming Languages and Runtimes
Install programming languages required for your project and their respective compilers, interpreters, or runtimes.

**Install Python**: [Python Download](http://www.python.org)
### Steps:
1. **Download Python** from the official [Python website](http://www.python.org).
2. **Install Python**:
    - Run the installer and follow the instructions, ensuring you check the option to add Python to your PATH.

## 5. Install Package Managers
Installed package managers like pip (for Python).
### Steps:
1. **Verify pip installation**:
    pip --version
2. **Upgrade pip** (if necessary):
    python -m pip install --upgrade pip

## 6. Configure a Database (MySQL)
Downloaded and Installed MySQL database.
But my problem is that i could not configure it 
**Download MySQL**: [MySQL Installer](https://dev.mysql.com/downloads/windows/installer/5.7.html)
### Steps:
1. **Download the MySQL Installer** from the [MySQL website](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. **Run the installer**

## 7. Set Up Development Environments and Virtualization (Optional)
I dont know much about Virtulization.
But this are the following virtualization tools
### Tools:
- **Docker**: [Docker Download](https://www.docker.com/products/docker-desktop)
- **VirtualBox**: [VirtualBox Download](https://www.virtualbox.org/wiki/Downloads)

## 8. Explore Extensions and Plugins
I chose to installed the following extensions and Plugins

### Installed Extensions and Plugins Explore Visual Studio Code:
- **Python**: [Python Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- **GitLens**: [GitLens Extension](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- **Prettier**: [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
-**Live Server**:[Live Server]()
-Code Runner:
-Live Server:
-Live Preview:
-**ESLint**: [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-**Error Lens**: [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)


### Reflection:
I couldn't configure MySQL and I couldnt set Up Development Environments and Virtualization.


