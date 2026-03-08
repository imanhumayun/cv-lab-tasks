# Python, Anaconda and Jupyter Notebook Installation Guide

This guide explains how to install Python, Anaconda, and Jupyter Notebook on your computer. It is written for beginners who want to set up a Python programming environment for development, data analysis, or coursework.

---

## Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Step 1: Install Python](#step-1-install-python)
- [Step 2: Install Anaconda](#step-2-install-anaconda)
- [Step 3: Launch Jupyter Notebook](#step-3-launch-jupyter-notebook)
- [Step 4: Create Your First Notebook](#step-4-create-your-first-notebook)
- [Step 5: Verify the Installation](#step-5-verify-the-installation)
- [Common Issues and Solutions](#common-issues-and-solutions)
- [Conclusion](#conclusion)

---

## Introduction

Python is a widely used programming language suitable for web development, automation, data analysis, artificial intelligence, and many other fields. Anaconda is a distribution that bundles Python with a large collection of libraries commonly used in data science and scientific computing. Jupyter Notebook is an interactive, browser-based environment that allows you to write, run, and document Python code in a single file.

If you install Anaconda, Python and Jupyter Notebook are already included. You do not need to install Python separately unless your project specifically requires a standalone installation.

---

## System Requirements

Before starting, make sure your system meets the following requirements:

- Windows 10 or later, macOS 10.13 or later, or a modern Linux distribution
- At least 4 GB of RAM (8 GB recommended)
- At least 5 GB of free disk space
- An active internet connection for downloading installers

---

## Step 1: Install Python

If you prefer a standalone Python installation rather than using Anaconda, follow these steps.

1. Visit the official Python website at https://www.python.org/downloads/
2. Click the Download button for the latest stable version.
3. Run the installer once the download is complete.
4. On Windows, check the box that says **Add Python to PATH** before proceeding.
5. Click **Install Now** and follow the on-screen instructions.

Once the installation is complete, open Command Prompt or Terminal and run the following command to confirm the installation:

````bash
python --version

Step 2: Install Anaconda
Anaconda is the recommended option for beginners and students because it includes Python, Jupyter Notebook, and many useful packages all in one installation.

1. Visit the official Anaconda website at https://www.anaconda.com/download
2. Download the installer that matches your operating system.
3. Run the installer.
4. Follow the on-screen instructions to complete the setup.
5. When prompted, allow Anaconda to be added to your system PATH or use the Anaconda Prompt for running commands.

After the installation is complete, open Anaconda Navigator from your Start menu or applications folder to confirm that it launches without errors.

Step 3: Launch Jupyter Notebook
There are two ways to open Jupyter Notebook after installing Anaconda.
Method 1: Using Anaconda Navigator

1. Open Anaconda Navigator.
2. Find Jupyter Notebook in the list of available applications.
3. Click Launch.

Jupyter Notebook will open automatically in your default web browser.
Method 2: Using the Command Line
Open Command Prompt, Terminal, or Anaconda Prompt and type the following command:
bashDownloadCopy codejupyter notebook
This will start the Jupyter server and open it in your browser. If the browser does not open automatically, copy the URL displayed in the terminal and paste it into your browser manually.

Step 4: Create Your First Notebook
Once Jupyter Notebook is open in your browser, follow these steps to create and run your first notebook:

1. Navigate to the folder where you want to save your work.
2. Click New in the top right corner.
3. Select Python 3 from the dropdown menu.
4. A new notebook will open with an empty cell.
5. Click inside the cell and type the following code:

pythonDownloadCopy codeprint("Hello, World")

1. Press Shift + Enter to run the cell.

If the output appears below the cell, your setup is working correctly.

Step 5: Verify the Installation
To confirm that everything is set up properly, check the following:

* Python responds with a version number when you run python --version in the terminal.
* Anaconda Navigator opens without errors.
* Jupyter Notebook launches successfully in the browser.
* Python code runs correctly inside a notebook cell.


Common Issues and Solutions
Python is not recognized as a command
This usually happens when Python was not added to the system PATH during installation. Uninstall Python and reinstall it, making sure to check the Add Python to PATH option before proceeding.
Jupyter Notebook does not open
Try launching Jupyter Notebook from the Anaconda Prompt instead of the regular Command Prompt or Terminal. If the issue persists, restart your computer and try again.
The browser does not open automatically
Copy the URL shown in the terminal output and paste it directly into your browser. It will usually look something like http://localhost:8888.
Permission or access errors during installation
Run the installer as an administrator by right-clicking on it and selecting Run as Administrator. Also check whether your antivirus software is interfering with the installation.
Conda command not found
If the conda command is not recognized after installing Anaconda, make sure Anaconda was added to your PATH environment variable. You can also use the Anaconda Prompt as an alternative to the regular terminal.

Conclusion
You have successfully installed Python, Anaconda, and Jupyter Notebook. Your environment is now ready for Python programming, data analysis, and machine learning projects.
Anaconda is the recommended choice for most students and beginners because it simplifies package management and includes everything you need to get started without additional configuration.
