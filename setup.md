---
layout: page
title: Computer Setup 
permalink: /setup/
menu: true
order: 4
description: > 
  To fully participate in the hands-on sections of this course you will need access to the software described below on your **own laptop**. Note that you may need Administrator privileges/permissions to install some of these.

comments: true
---

Students in this course will learn that Bioinformatics frequently requires analyzing large complex datasets. The recommended approach to such analysis is to work with a computer that offers **UNIX** integration. Together we will lean the fundamentals of the UNIX command line and the R environment for data analysis and graphics.


### Student Computers & Software Setup Instructions
To fully participate in this course students will need access to a modern computer to which they have administrator privileges (that is a computer where they can install software without restriction).  

I much prefer **Mac** and Linux based computers as they already have a UNIX base.  If you can, please use one of these.  However, don't worry if you are running Windows as we will be able to login to a campus based UNIX machine from your laptop or windows desktop for classwork. Chromebooks and iPads will not work for this class.

Regardless of your computer type you will need to install the software described below.

### An up-to-date **web browser** 
Current versions of [Chrome](https://www.google.com/chrome/), [Firefox](http://www.mozilla.org/firefox/) and [Safari](Safari) are preferred.

### The Zoom virtual meeting software  
We will use [Zoom](https://ucsd.zoom.us) on a weekly basis for office hours and other meetings. Please make sure you have Zoom installed and running to allow you to join these meetings.   

### The data analysis environment **R** and **RStudio**
R Binaries for Windows, MacOSX and Linux can be downloaded and installed from [CRAN](http://cran.r-project.org/index.html) (Comprehensive R Archive Network). If possible download the latest binary version of R for your operating system. As of course launch (Sept 21) the latest release (2021-08-10, "Kick Things") is R 4.1.1.

After installing R itself we recommend installing [RStudio Desktop](https://www.rstudio.com/products/rstudio/download/#download) (version 1.1.456 or above), a slick visual interface for R. **N.B.** You will want the Open Source **FREE** desktop version.



### The Bash Shell
Bash is a commonly-used UNIX shell that gives you the power to do simple tasks more quickly.

**Mac OS X:** You do not need to install anything. You can access bash from the **Terminal** (found in `/Applications/Utilities`). You may want to keep Terminal in your dock for this class.

**Linux:** There is no need to install anything.

**Windows:** Install *Git for Windows* from <https://gitforwindows.org> by downloading their latest .exe installer file, double click on the installer file, click "Next" and follow their default setup (latest version).  

If you have a particularly old PC and require an older version (2.16 or below) for comparability with your OS version then follow the steps bellow:
- Run your downloaded installer file (e.g. `Git-2.16.3-32-bit.exe`) by double clicking on it.
- Click on "Next".
- Click on "Next".
- Select "*Use Git from the Windows Command Prompt*" and click on "Next".
- Click on "Next".
- Keep "*Checkout Windows-style, commit Unix-style line endings*" selected and click "Next".
- Select "*Use Windows default console window*" selected and click on "Next".
- Click on "Install" (this may take a little while).
- Once done click on "Finish".

To check if your install worked you can click on the "*Windows Menu button*" > "*All Apps*" and scroll down to **Git** and click to expand and select **Git Bash**. This should open a mostly black command line window. Success!! We can go ahead and close this for now.    

### XQuartz (Mac only)
Please install [XQuartz](https://www.xquartz.org) a windowing environment required by some R packages. **N.B. This is only required on macs**. Download the linked DMG file (e.g. `XQuartz-2.8.1.dmg`). Once fully downloaded, double click to launch the installer and follow the regular steps.


### (Optional) Apple Xcode Developer Tools (Mac only)
Only a subset of folks who wish to install R packages from source code (rather than the default binary packages) will need to have Apple's command line tools. I can walk you through this process in class or office hours. Essentially, it boils down to opening a terminal and typing the following command: `xcode-select --install`  Don't worry if you don't know what this means yet as I will explain when we get to this point in the course. 



<!-- 
### Text Editor
When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like automatic color-coding of key words. The default text editor on Mac OS X and Linux is usually set to Vim, which is not famous for being intuitive. if you accidentally find yourself stuck in it, try typing the **escape key**, followed by **:q!** (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell. Nano is a basic editor and the default that we will use during this course. 


**Mac OS X:** nano should be pre-installed.

**Linux:** nano should be pre-installed.

**Windows:** Nano can be installed as a plugin to mobaxterm (see above). First start mobaxterm and then in the mobaxterm terminal type: `mobapt` Pressing Return will bring up a panel listing available additions. Please select **nano** by clicking on its entry and then the “Install/Update” button.
 --> 

### (Optional) Using Jetstream

Jetstream is a cloud-based on-demand virtual machine system funded by the National Science Foundation. It will provide us with UNIX based computers (what we call “virtual machine instances”) that look and feel just like a regular Linux workstation but with thousands of times the computing power!  

We will cover configuring and connecting to Jetstream in class. You can also find detailed *step-by-step* instructions for:

 - [Starting a Jetstream Computer Instance]({{ site.baseurl }}/jetstream/boot/),
 - [Logging in to jetstream from your local terminal]({{ site.baseurl }}/jetstream/login/),
 - [Adding password to a Jetstream instance]({{ site.baseurl }}/jetstream/ssh_changepassword/). 

We will cover all of these together in class.  

<!--- Still to complete...
### Why this class

### The semi-flipped classroom
-->
