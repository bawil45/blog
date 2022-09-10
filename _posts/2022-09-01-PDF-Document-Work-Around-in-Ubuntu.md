---
layout: post
title: "PDF Document Work Around in Ubuntu"
author: "Bagus Wilar"
categories: tutorial
tags: [onedrive,ubuntu,software,pdf,document,office]
image: Densify.jpg
---



# Background
As i am work in Indonesia, Ubuntu is just out of sight Operating System (even though it's free) which everybody are never heard about. The consequences are, we have to make an extra effort for make it work, especially on searching for the subsitution tools which we conviniencely use on Windows. For administration area, deal with tons document, have no tools for modified pdf documents is worst nightmare.  There is several function we usually use and search when working with pdf document:

1. Input and edit on top of pdf document.
2. Re-Arrange the structure of pdf document page by page.
3. Compress the size of pdf document.

The fartest i know, there are no apps that have all function at one single software. the condition i have maybe commonly faced by ubuntu user in Indonesia. This article will focused on diccussing the tools effective to cripple all those problems. So, please enjoy.  

# Objective
1. Find the effective tools on input and edit text on PDF Document
2. Change the structure of PDF Document
3. Make the pdf size as small as posible while maintaining the readable of the document

# How We Get There

## Input Text On PDF

Many ways to edit or input text on pdf document, but on this article i will discuss the two easy way to do that:

1. LibreOffice Draw <br>

    This apps is the lighter than inkscape in term of memory management. But, sometimes cannot handle the pdf file better thank inkscape. For using this apps you may       follow the step below:
    
    A. Where to get it?
    
         1) From ubuntu software, just search on the store with keyword "LibreOffice". Then Install it, after that you will get LibreOffice Draw on your Ubuntu.<br>
         2) From terminal, for this, you have to do this step:
              a) type: sudo apt-get update
              b) type: sudo apt-get install libreoffice
              
    B. How to use it?
    
         1) Input Text and Edit Text On Top of PDF Document
         2) Input Text Image and Overlay On Top Of PDF File
         
3. Inkscape

    Inkscape is an replacement apps for photoshop in windows, you can even use it on windows. Pretty handy apps, but if you not yet familiar with it, the adaptation       will takes time. On Ubuntu, inkscape could help you for editing an PDF Document. The step is as follow:
    
    A. Where to get it?
    
         1) From ubuntu software, just search on the store with keyword "Inkscape". Then Install it, after that you will get Inkscape on your Ubuntu.<br>
         2) From terminal, for this, you have to do this step:
              a) type: sudo apt-get update
              b) type: sudo apt-get install inkscape
              
    B. How to use it?
    
         1) Input Text and Edit Text On Top of PDF Document
         2) Input Text Image and Overlay On Top Of PDF File
   
## Re-Arange Structure of PDF

Many program available to open and view a pdf document, but not so many have ability to re arrange the order of document pages. So, i recommend this program to do that task:

1. PDF Arranger

    A. How to install it?
    
         1. open terminal
         2. Type : 
              > sudo apt-get install python3-distutils-extra python3-wheel python3-gi python3-gi-cairo gir1.2-gtk-3.0 gir1.2-poppler-0.18 python3-setuptools 
         3. Once the installation is finished, the type:
              > pip3 install --user -r https://raw.githubusercontent.com/jeromerobert/pdfarranger/master/requirements.txt 
         4. When requierement is set, we will begin the installation. First type:
               > sudo add-apt-repository ppa:linuxuprising/apps 
               then: 
               > sudo apt update 
               the last: 
               > sudo apt install pdfarranger
                
    B. How to use it? 
    
         1. The user guidance for this apps is as image below. 
    
## Optimize Size of PDF 

For this purpose, i only could find one program that working smoothly and also the most efficient on memory usage. The apps name is Densify. 

A. Where to get it?

    Please download the latest version on [Desify](https://github.com/hkdb/Densify/releases) 

B. How to install 

    This is the best part of using Ubuntu, the things is easy and simple, after download the desify .AppImage file, just do this few simple step: 
    1. Right click on densify file you've just downloaded. 
    2. Click Properties-> Permission-> Execute-> Check-> Close. 

C. How to use it? 

     1. Simply just click 2 time on the .AppImage file you have set before. 
     2. When densify is open, the user guidance is as image below. 
     ![Densify Interface](https://github.com/bawil45/blog/blob/gh-pages/assets/img/Densify.jpg "Densify Interface") 
