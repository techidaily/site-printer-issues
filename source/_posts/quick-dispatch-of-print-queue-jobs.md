---
title: Quick Dispatch of Print Queue Jobs
date: 2024-07-10T17:20:30.221Z
updated: 2024-07-11T17:20:30.221Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Dispatch of Print Queue Jobs
excerpt: This Article Describes Quick Dispatch of Print Queue Jobs
keywords: Quick Print Job Dispatch,Fast Print Queue Processing,Efficient Print Service,Rapid Print Job Execution,Reduced Print Job Wait Times,Speedy Printer Queue Management,High-Speed Print Job Handling
thumbnail: https://thmb.techidaily.com/d1baf3dfbbd327d9cbcf98353df44476f218395c1d3282d729e920baf2edbea8.jpg
---

## Quick Dispatch of Print Queue Jobs

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
2. In the Command Prompt window, enter the following commands separately:

net stop spooler

del %systemroot%\System32\spool\printers\* /Q **/F /S**

net start spooler

This will clear all of your print jobs stuck in a queue.

#### Option 3: Create a Bat file for permanent use

 If you don’t want to go through all the trouble again, there’s a permanent fix for you to do this. Create your own batch file and you just need to open it every time you want to clear the print queue. Here is how to do it:

1. Open Notepad or Notepad++ (but not a word processor like Microsoft Word.)
2. Enter the following lines:  
 **net stop spooler**  
 **del %systemroot%\\System32\\spool\\printers\* /Q /F /S**  
 **net start spooler**  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

### Fix 2: Reinstall the printer driver

 If your print jobs still get stuck in a queue, the main cause is a wrong or outdated printer driver. So you should update your printer driver to see if it fixes your problem.

 There are two ways to update your printer driver: manually or automatically.

#### Option 1: Install the printer driver manually

 Printer manufacturers such as HP, Canon, Brother, Dell, and Epson keep releasing new printer drivers to fix bugs and improve performance. To get them, you can go to your printer manufacturer’s website (always in the Support or Download section) and download the latest driver and install it manually.

* HP:[HP software and Driver Downloads](https://support.hp.com/us-en/drivers)
* Canon:[Canon Drivers & Downloads](https://www.usa.canon.com/internet/portal/us/home/support/drivers-downloads)
* Brother:[Brother Driver Downloads](https://www.brother-usa.com/brother-support/driver-downloads)
* Dell:[Dell Drivers & Downloads](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fsupport%2Fhome%2Fus%2Fen%2F04%3Fapp%3Ddrivers)
* Epson:[Epson Products & Drivers](https://global.epson.com/products%5Fand%5Fdrivers/)

![](https://images.drivereasy.com/wp-content/uploads/2020/01/kisspng-pixel-illustration-printer-5a983b8a6f6aa4.5830009615199261544564.png)

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
5. Try printing again. Your printer should be working properly now.

---

 Hopefully, your printer can work like a charm now. However, if none of the fixes above solved your printer stuck in a queue, please check the USB or Wireless connection to make sure that your printer is communicating well with your computer or mobile phone.

Feel free to drop us a comment if you have any questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [printer](https://tools.techidaily.com/drivereasy/download/)
* [printer driver](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://printer-issues.techidaily.com/advanced-drives-mf4770n-software-upgrade-windows/"><u>Advanced Drives: MF4770n Software Upgrade Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-wi-fi-directly-for-canon-printers/"><u>Enabling Wi-Fi Directly for Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-barriers-reconnecting-brothers-networked-printer/"><u>Breaking Barriers: Reconnecting Brother's Networked Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-dell-aio-printer-software-in-windows-7/"><u>Upgrade: Dell AIO Printer Software in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-cartridge-replacement-failures/"><u>Troubleshooting Cartridge Replacement Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-release-for-queued-printer-work/"><u>Accelerate Release for Queued Printer Work</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-windows-hp-print-link/"><u>Fixing Offline Windows-HP Print Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/black-and-white-only-mode-engaged-by-printer/"><u>Black & White Only Mode Engaged by Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-without-problems/"><u>Printer Setup: Completed Without Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-text-only-paper-the-epson-printer-glitch/"><u>No Text, Only Paper: The Epson Printer Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-to-fix-silent-hp-multi-fax-printers/"><u>Techniques to Fix Silent HP Multi-Fax Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-scanner-connection-on-newly-installed-windows-10/"><u>Enabling Scanner Connection on Newly Installed Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/complete-pages-printed-by-printers-now/"><u>Complete Pages Printed by Printers Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-issue-hp-printer-not-recognized-by-os/"><u>Hardware Issue: HP Printer Not Recognized by OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domain-services-unreachable-print-issue/"><u>Domain Services Unreachable, Print Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-down-print-operation-fails/"><u>Active Directory Down - Print Operation Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-operation-windows-compatible-driver-for-officejet-pro-8600/"><u>Efficient Operation: Windows Compatible Driver for Officejet Pro 8600</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-intermittent-print-job-failures-windows/"><u>Steps to Stop Intermittent Print Job Failures (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-problem-hp-printer-driver-unavailable-in-winxo/"><u>[Windows Problem] HP Printer Driver Unavailable in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-successful/"><u>Printer Setup: Successful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstate-scanner-connection-on-windows-10-machine/"><u>Reinstate Scanner Connection on Windows 10 Machine</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/incorporating-sound-techniques-for-embedding-audio-in-quicktime-media-for-2024/"><u>Incorporating Sound Techniques for Embedding Audio in QuickTime Media for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-hashtag-hits-videoviral-trends-on-twitter-for-2024/"><u>[New] Hashtag Hits  #VideoViral Trends on Twitter for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-master-guide-implementing-chapters-in-vimeo-for-2024/"><u>[Updated] Master Guide  Implementing Chapters in Vimeo for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pinnacle-cloud-space-for-enterprise-success/"><u>Pinnacle Cloud Space for Enterprise Success</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-incredible-browser-game-hacks/"><u>[Updated] Top Incredible Browser Game Hacks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-cutting-edge-alternatives-to-obs-for-recording-for-2024/"><u>[Updated] Cutting-Edge Alternatives to OBS for Recording for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-captivate-viewers-earn-accolades-tips-for-staff-picks-on-vimeo/"><u>[New] 2024 Approved  Captivate Viewers, Earn Accolades  Tips for Staff Picks on Vimeo</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-easily-unlock-vivo-screen-by-drfone-android/"><u>In 2024, How To Easily Unlock Vivo Screen?</u></a></li>
</ul></div>
