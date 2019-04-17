# Welcome to [AlmostNomads](http://almostnomads.xyz) 

![Blog Logo](/assets/images/logo.jpg)

Here is where I've decided to post some of my favorie travel stories. First, I feel I need to lay out a disclaimer to reveal myself as a novice to Git and [GitHub](http://github.com).  The main reason for developing a blog here was not only how to use Git, but more specifically, to dive in and create [GitHub Pages](https://pages.github.com/).

## How I Got Started

Before diving into gh-pages, I had to first learn how to install and run Git.  Having some experience with Linux I went ahead and wiped the old Windows 7 image on my Lenovo Thinkpad and install an iso image of [Ubuntu](https://ubuntu.com).  Then, I rummaged through loads of links and how-to's via Google to create the local development environment I needed to build a gh-pages site on my local computer.

## How this Blog is Built
The files in this respository have been created on a Windows 10 computer with [Windows Susbystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install-win10) installed.  The WSL compatability engine runs all the binaries required to build a a local blog on your home computer. Listed below are the steps the I followed:

1. Prepare WSL

Before navigating to the Windows Store to install a WSL binary, the WSL feature should be enabled. Open PowerShell and enter the following:

> **Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux**

2. Install your favorite Linux Distribution

> Select the Windows Key + S to open Cotana search and enter 'store.'  From there, select the Linux distribution to install.
