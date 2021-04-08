---
title: 'Dual Booting my laptop'
date: 2021-03-12
permalink: /posts/2021/03/Dual-booting-my-laptop
  - How to Guide

---

Having used a linux machine exclusively for the past three years, I would be lying to say that I was thrilled about switching to Windows when I got my new laptop. As Windows 10 came pre-installed I decided to see how far I could get adjusting to using the 'user-friendly' OS.  There are certain aspects of using Windows that are definitely appealing, for instance Microsoft Teams now having more than 4 people on display, and how easy it is to install some software is absolutely delightful, and don't get me started on the Matlab GUI! However, I do miss the ability to customize the GUI within lubuntu, and using Git through terminal is just easier, though I do now understand the desktop app at least. 
I decided that three months was enough,though, and I'm now attempting to dual boot my machine. My previous installs of linux were relatively simplistic, since in my first machine I simply wiped the windows OS and replaced it with linux (it was a tiny hard drive and windows no longer fit: thus the switch), and then my last machine I managed to install a micro SSD allowing a dual hard drive run, so no partitioning was required. This time however, needs must I partition my SSD before dual booting, but I've already got windows installed. this post is to document my method should I need to replicate my movements. 

## Backing up windows
* Have an external hard drive ready with enough storage space on it (it doesn't wipe whats currently on there). 
* In settings, go to Update and Security. 
* In the sidebar, select Backup. 
* Click on 'Go to Backup and Restore (Windows 7)'. 
* Select 'Create a system image'. 
* Choose the external hard drive and click 'OK'. 

I don't know how to reinstall from this, but this should be a copy of the current files etc on windows.

## Creating a live USB
 * You need a USB that you can completely rewrite, with at least 4GB of storage (I went for an 8GB USB with an old boot I want to wipe on it).
 * First I installed [rufus](https://rufus.ie/), which is a software that allows you write bootable USBs. 
 * Download Ubuntu [here](https://releases.ubuntu.com/20.04/) by selecting the desktop image. Choose to save to downloads on your computer. DON'T SAVE TO THE USB. 
 * Open rufus and select the USB in 'Device'. 
 * Leave boot selection on 'Disk or ISO image (Please select)' and click the button SELECT next to it. 
 * Choose the iso Ubuntu file you downloaded in your Downloads folder. 
 * Hit the 'START' button at the bottom of the window.
 * Select 'Yes'
 * Click 'Ok' (should be on 'Write in ISO Image mode(Recommended)') - This will then wipe anything on the USB so move it before this point! 
 * It will take a while to copy all the files across so don't panic. Once the Status bar turns green, the USB is ready, so click 'Close' and remove the USB. 

 ## Dual Booting
  * It'll help if you turn off 'fast setup' in Windows first. Go into Control Panel; Power Options; Choose what power options do; Change settings that are currently available; and then unselect 'turn on fast start-up'. 
  * You might also have to disable BitLocker so the installer can see the hard-drive set up. To do this go into Control Panel; System and Security; BitLocker Drive Encryption; then turn BitLocker off. It might take a while to Decrypt the hard-drive but don't worry. From here you really should reboot your device and check everything works okay before continuing. 
  * With the newer (18 upwards?) Ubuntu installers there is an option inbuilt for installing alongside an already running windows boot. So you don't have to worry about pre-partitioning the hard drive since the installer will do that for you. 
  * Restart the laptop with the live USB plugged in and interrupt the usual start menu. It helps if you turn off 'fast boot' in Windows before doing this. On my Thinkpad X1C8, interrupting is hitting 'Enter' as soon as the lenovo logo appears. 
  * Choose to boot from the USB
  * You'll have an option then to select language, 'Try Ubuntu', or 'Install Ubuntu'. If you want to have a look around Ubuntu first then choose try ubuntu and it will load up an environment without writing to your device. (I plan on changing desktop environment once it's installed, but you can always change the USB so it installs to your preferred DE to start with).
  * Once you choose to install click the installer. 
  * Choose keyboard layout and click continue, there is an option to test out the keyboard if you're unsure it's the right option. 
  * It's often easier to choose to to install the other options alongside the install, but up to you. 
  * Now you want to choose 'Install Ubuntu alongside Windows 10/Windows boot'. If you want to customise partitions etc then you choose something else. 
  * If you need to disable BitLocker this is the point where it will tell you. 
  * You'll next be shown a slider bar to choose how much space you want to give to the Ubuntu partition. Different people say different things, some have a minimum of 10GB, others say 30GB. I have a 512GB hard-drive and when this page loaded it was set to 180GB for Ubuntu. Seeing as one of my previous issues was lack of storage I figured this seemed like a good split. Especially when I want to keep windows for recreation (gaming and online calls) thiis seemed like a good amount of storage for all the software/storage I need for work. I may be completely wrong but we'll see what happens. 
  * Once you're comfortable with the space allocation, hit install now. 
  * The installation, for me, only took 10 minutes, but can take a while, so don't worry. 
  * You need to answer general questions about the timezone, username, passwords etc. 
  * Once the install in complete you need to reboot. It should launch into GRUB loader, but ifyou don't select anything it will default to Ubuntu. 

  Enjoy!
  Next time, we look at different desktop environments, and customising linux to something I want to use! 