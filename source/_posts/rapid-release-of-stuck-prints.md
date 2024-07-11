---
title: Rapid Release of Stuck Prints
date: 2024-07-10T17:09:04.423Z
updated: 2024-07-11T17:09:04.423Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Release of Stuck Prints
excerpt: This Article Describes Rapid Release of Stuck Prints
keywords: Stuck Prints Removal,Quick Unsticking Methods,Gummed Prints Solution,Print Release Techniques,Sticky Backing Board Removal,Non-Destructive Stick Print Release,How to Unstick Prints
thumbnail: https://thmb.techidaily.com/80de444cb408ef81f4728e2850b723591d8016d7f4cd61445fe263111407c51f.jpg
---

## Rapid Release of Stuck Prints

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
<li><a href="https://printer-issues.techidaily.com/quick-guide-linking-your-canon-to-wi-fi/"><u>Quick Guide: Linking Your Canon to Wi-Fi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-error-canon-print-misfires/"><u>Remedying Error: Canon Print Misfires</u></a></li>
<li><a href="https://printer-issues.techidaily.com/top-off-your-printing-experience-latest-aio-updates-in-windows-7/"><u>Top Off Your Printing Experience: Latest AIO Updates in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-epson-printer-error-codes-on-w11/"><u>Troubleshoot Epson Printer Error Codes on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-updates-for-enhanced-hp-officejet-performance/"><u>Effortless Updates for Enhanced HP Officejet Performance</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-win-11-printer-hiccup-after-update/"><u>Resolved Win 11 Printer Hiccup After Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-inkjet-aio-updater-for-win7/"><u>Dell Inkjet AIO Updater for Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expediting-clogged-print-order/"><u>Expediting Clogged Print Order</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-woes-issue-fixed/"><u>Epson Printer Woes, Issue Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-your-hp-laserjet-remote-connection/"><u>Setting Up Your HP LaserJet Remote Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-scanner-activation-on-windows-10-system/"><u>Resetting Scanner Activation on Windows 10 System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-mfc-9330cdw-wireless-effortlessly/"><u>Install MFC-9330CDW Wireless Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problem-unable-to-install-hp-d1360-printer-driver-in-various-oses/"><u>[Network Problem] Unable to Install HP D1360 Printer Driver in Various OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winprint-woes-successfully-fixing-error-0x00000709/"><u>WinPrint Woes: Successfully Fixing Error 0X00000709</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-hook-up-a-canon-printer-step-by-step-illustration/"><u>How To Hook Up a Canon Printer: Step-by-Step Illustration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-brother-printer-no-print-errors-windows-style/"><u>Addressing Brother Printer No-Print Errors, Windows Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-error-b200/"><u>Eradicated Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-the-erratic-behavior-of-print-spooler-windows/"><u>Troubleshooting the Erratic Behavior of Print Spooler (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connection-guide-integrating-hp-printer-with-pc-network/"><u>Connection Guide: Integrating HP Printer with PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-paperjam-error-by-deleting-printer/"><u>Eliminate PaperJam Error by Deleting Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-printing-blank-pages/"><u>[Solved] Printer Printing Blank Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/healed-printer-communication-link/"><u>Healed Printer Communication Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-stops-printing-post-win11-installation/"><u>Printer Stops Printing Post Win11 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-cant-find-driver-on-windows-os/"><u>HP Printer Setup Error: Can't Find Driver on Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-in-effect-for-b200/"><u>Fix In Effect for B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-recovery-from-common-pcl-xl-failures/"><u>Rapid Recovery From Common PCL XL Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-confounding-error-0x97-explained/"><u>Epson's Confounding Error 0X97 Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-busted-fixing-error-0x00000709-in-windows/"><u>Print Issue Busted: Fixing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-restarting-brother-printer-for-windows/"><u>Troubleshooting: Restarting Brother Printer for Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comparing-cloud-space-charges-methods-and-results/"><u>2024 Approved  Comparing Cloud Space Charges  Methods and Results</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-exclusion-dilemma-is-someone-hidden-on-snapchat/"><u>In 2024, The Exclusion Dilemma  Is Someone Hidden On Snapchat?</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-power-of-photos-a-comprehensive-polarr-guide-for-2024/"><u>Unveiling the Power of Photos  A Comprehensive Polarr Guide for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-iphone-15-pro-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, iPhone 15 Pro iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comedy-gold-examining-the-goofy-vhs-experience/"><u>'Comedy Gold'  Examining the Goofy VHS Experience</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-content-extractor-the-best-of-the-rest/"><u>[New] Instagram Content Extractor  The Best of the Rest</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-lava-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Lava IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-concealed-chronicle-watchers-5-premier-application-choices/"><u>[Updated] In 2024, Concealed Chronicle Watchers  5 Premier Application Choices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-connect-and-share-youtube-in-instagrams-ecosystem/"><u>[New] Connect & Share  YouTube in Instagram's Ecosystem</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-laughter-lines-timely-meme-trends-to-share/"><u>2024 Approved  Laughter Lines  Timely Meme Trends to Share</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-add-the-popular-video-text-effects-to-your-video-in-2024/"><u>Updated How to Add the Popular Video Text Effects to Your Video, In 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-expert-strategies-for-success-on-ginger-island/"><u>[New] 2024 Approved  Expert Strategies for Success on Ginger Island</u></a></li>
</ul></div>
