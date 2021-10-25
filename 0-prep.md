---
title: 0-Prep
nav: true
---

# Prep and Installation 

To join the wonderful world of version control, please create a [GitHub](github.com) account and [install Git](https://git-scm.com/download) on your system.

## 1. Get a GitHub Account

[GitHub](https://github.com/){:target="_blank"} is a Git repository hosting service, a place to store and sync your work in the cloud. 
Take a minute to create a [free account](https://github.com/join){:target="_blank"}.
They provide some great introductory [tutorials](https://guides.github.com/){:target="_blank"}, for additional reference.

### Text Editor 

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for most cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/){:target="_blank"}, Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for working on projects and can often integrate with Git to make your life easier. I highly recommend [Visual Studio Code](https://code.visualstudio.com/){:target="_blank"}.

## 2. Install Git

Git version control system is a piece of software you install on your computer. 
Installing it is pretty easy:

- **Windows:** install [Git for Windows](https://gitforwindows.org/){:target="_blank"} using the default options, except: 
    - when setup asks you to choose the default editor used by Git, select the Visual Studio Code option (or your preferred text editor). 
    - when asked about "checkout style," select "checkout as-is, commit unix style" for cross platform compatibility
This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands and utilities on Windows.
- **Mac:** check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads){:target="_blank"}.
- **Linux:** install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

### Git Graphical User Interfaces (GUI)

This tutorial introduces the basic Git workflow using the command line and GitHub web interface. 
However, you may prefer a GUI application for your future day-to-day work with Git.
There are a variety of [GUI apps available](https://git-scm.com/downloads/guis){:target="_blank"} for managing and visualizing Git repositories.

On Windows and Mac machines, I recommend installing [GitHub Desktop](https://desktop.github.com/){:target="_blank"} using the default options. On Linux [gitg](https://wiki.gnome.org/Apps/Gitg/){:target="_blank"} and [GitKraken](https://www.gitkraken.com/){:target="_blank"} are good options.
