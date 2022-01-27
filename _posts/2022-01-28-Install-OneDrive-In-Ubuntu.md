---
layout: post
title: "Installing Onedrive on Ubuntu 20.04"
author: "Bagus Wilar"
categories: tutorial
tags: [onedrive,ubuntu,software,cloudstorage,microsoft365]
image:onedrive command1.jpg
---




# Installing Onedrive on Ubuntu 20.04
## Objective

Installing microsoft onedrive desktop version on ubuntu is not simple as on windows. Microsoft never port it into linux ecosystem. So workaround have to be done. This will give you the easiest way to achieve it.

## Step by Step

Open terminal, then do the following step:

1. Update<br>
    type 'sudo apt-get update'<br>
2. Put a ppa respository<br>
     type 'sudo add-apt-repository ppa:yann1ck/onedrive'<br>
3. Install onedrive<br>
     type 'sudo apt-get install onedrive'<br>
4. Run onedrive<br>
     type 'onedrive'<br>
5. Link will appear on microsoft online for login to your account. Block the link and right click then open the link.<br>
6. Blank page of browser will appear then you have to copy the link in the address bar to the terminal<br>
7. To know the command used for onedrive<br>
     type 'onedrive --h'<br>
	 
## Troubleshoot

1. When tried to execute onedrive --syncronize-display it says that the destination folder is home/bagus/OneDrive but the OneDrive folder doesn't exist 
    
	Solve:
	
	1) open home/bagus/
	2) create folder name OneDrive

2. When tried to execute onedrive --monitor it says that the destination folder var/log/onedrive doesn't exist

    Solve:
	
	1) open terminal
	2) type 'cd var/log'
	3) type 'sudo mkdir onedrive'


Source:<br>
[How to Install Microsoft OneDrive on Ubuntu](https://linuxhint.com/install-microsoft-onedrive-ubuntu/)<br>
[How to create files and directorys in var/www? [duplicate]](https://askubuntu.com/questions/181481/how-to-create-files-and-directorys-in-var-www)
