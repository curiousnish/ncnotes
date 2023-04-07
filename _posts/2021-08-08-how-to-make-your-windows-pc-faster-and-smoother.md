---
layout: post
title: How to make your Windows PC Faster and Smoother
author: self
categories: [PC]
tags: ["Windows 10", "PC", "Bloatware", "Tools"]
date: 2021-08-08 12:00:00 +0530
---

An article written by an eight year old PC to help it’s successors lead a better life.

![Desktop View](/assets/img/windows.jpg){: .shadow .rounded-10 w="700" h="400" }
*Updates are Unavoidable (Source: [Unsplash](https://unsplash.com/photos/-jCY4oEMA3o))*

Windows 11 is on the horizon and most of the people are excited to get a worthy update, but not every PC in the market is eligible for Windows 11 upgrade (not even a 3 year old hardware) due to some security requirements which Microsoft thinks are crucial for running Windows 11. So, we have to run Windows 10 till these requirement issues are sorted out.

## About Me:

I am an eight year old Dell all-in-one PC running second generation Intel core i3 with 4 GB ram (DDR3) and still running Windows 10 and able to handle all the daily tasks. That’s it with my intro, let’s get to the juicy part...

## Making your PC faster

To improve the performance of a Windows PC, you need to ask your owner to follow some steps:

### Step 1: Format/Reset/Refresh your PC (even if it’s brand new)

The best way to get rid of all the non-required applications that are buried deep down the OS is to reset the PC. Nowadays, it easy to Reset a PC without losing data. So got for it!

[This](https://support.microsoft.com/en-us/windows/how-to-refresh-reset-or-restore-your-pc-51391d9a-eb0a-84a7-69e4-c2c1fbceb8dd) guide will help you reset the PC properly.

### Step 2: Uninstall apps you don’t use (there are a ton of bloatware)

After resetting the PC or installing a fresh copy of Windows 10, we are now ready to clean it even more, because there are a lot of preloaded apps (bloatware) that comes with the installation of windows. We can uninstall most of the apps by navigating to **Settings > Apps > Apps & Features**, and selecting the apps which we don’t need and can be uninstalled.

In my case, if I see an “**Uninstall**” button, I’ll click it.

Most of the users will be pretty happy with the performance increase after doing these 2 steps, but if you want more performance then the next step can help you achieve that.

### Step 3: Use Windows 10 De-bloater

This step is not required, but if done properly can give you up to 10–20% boost in performance. **Warning! – Perform this step at your own risk to squeeze the last bit of performance from you PC.**

In this step, we’ll be using a program called [Windows10Debloater](https://github.com/Sycnex/Windows10Debloater) developed by [Richard Newton (Sycnex](https://github.com/Sycnex)). It is a powerful script and can be used to remove any system apps including Microsoft Store, Photos app and so on.

The steps are pretty simple…

- Visit [Sycnex/Windows10Debloater](https://github.com/Sycnex/Windows10Debloater)
- Download the zip file of the code
- Extract the zip file
- Run the “Windows10DebloaterGUI.ps1”: to run this program, right click the file and select “Run With PowerShell”
- This will open the window for running the scripts and disabling some unwanted stuff from Microsoft.
- These are the buttons I click after running the script:

![Desktop View](/assets/img/debloat.png){: .shadow .rounded-10 }
*Debloater Running (Source: Author)*

*Credits —Richard Newton (Sycnex) is an awesome guy to provide these scripts for free and open sourcing the project. Much love to him and the team that made it possible.*