# Developer Environment Setup Guide

## Window System Installation

### Step 1: Download and Install Windows 11

 **Link:** [Windows 11 Download Page](https://www.microsoft.com/software-download/windows11)
**Instructions:**
1.  Download the installer for Windows, run it, and follow the setup instructions.


## Install and Link Git and Github 

### Step 1: Greate a Github account

**Link:** [Github Page](hhttps://github.com/)
**Instructions:** 
1. Go to GitHub and sign up for a new account.

### Step 2: Install Git 

**Link:** [Git download page](https://git-scm.com/downloads)
**Instructions:** 
1. Visit Git download page and download the installer for Windows.

### Step 3: Link your Git and Github

**Instructions:** 
1. Open the Git Bash terminal.
2. Link your Github username and email using the following commands:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


## Install Necessary Programming Languages 

### Step 1: Install Python

**Link:** [Python download page](http://www.python.org/)
**Instructions:**
1. Download the latest version.
2. Install and make sure you check "Add Python to PATH" during installation.

## Configure a Database (MySQL)

### Step 1: Download and install MySQL.

**Link:** [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html)
**Instructions:**
1. Install
2. Follow the installation instructions.
3. Set up your database.

## Explore Extensions

### Step 1: Explore available extensions in VS Code

**Instructions:**
1. Open VS Code and go to the Extensions by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
2. Search for and install useful extensions.

## Reflection

When configuring the PATH environment variable for Python during the setup, I faced some problems. To fix this, I had to manually add a Python installation path to the system variable PATH via System Properties. Also, configuring MySQL entailed some issues with the firewall, which I fixed by enabling MySQL through the firewall.

## Final Thoughts

This process was time-consuming, particularly because of the decisions that had to be made when configuring the PATHs and opening firewalls. It was a good learning experience and was also a good reminder that having a good configuration setup is very beneficial.