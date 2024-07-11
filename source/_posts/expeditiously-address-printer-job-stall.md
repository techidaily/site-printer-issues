---
title: Expeditiously Address Printer Job Stall
date: 2024-07-10T17:16:03.923Z
updated: 2024-07-11T17:16:03.923Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expeditiously Address Printer Job Stall
excerpt: This Article Describes Expeditiously Address Printer Job Stall
keywords: Printer Job Stall,Fixing Printer Issues,Printer Troubleshooting Guide,Quick Fix Printer Halt,Printer Error Resolution,Overcoming Printer Job Freeze,Improving Print Output Speed
thumbnail: https://thmb.techidaily.com/1b6976dc536a482a8440b6155a5c6ffdb602672c280e778006363b18d82c63d3.jpg
---

## Expeditiously Address Printer Job Stall

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
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-error/"><u>Mended Printer Network Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-ultimate-guide-to-installing-and-configuring-hp-printers/"><u>The Ultimate Guide to Installing and Configuring HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-setting-up-hp-laserjet-compact-connectivity/"><u>Guide to Setting Up HP LaserJet Compact Connectivity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-integration-update-mf4770n-drivers-on-w11w8w7-os/"><u>Smooth Integration: Update MF4770n Drivers on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-repair-success/"><u>Epson Printer Repair Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ceased-non-printer-error-on-hp-laserjet-pro-m637/"><u>Ceased Non-Printer Error on HP LaserJet Pro M637</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-laser-troubleshooting/"><u>Streamlining Laser Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-your-windows-11-printer-problems/"><u>Solve Your Windows 11 Printer Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/erase-print-task-queue-pause/"><u>Erase Print Task Queue Pause</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hasten-printer-job-advancement/"><u>Hasten Printer Job Advancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-searching-for-driver-on-win11/"><u>Canon Pixma MP620: Searching for Driver on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-disappearing-act-in-windows-910/"><u>Print Device Disappearing Act in WIndows 9/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-d1360-printer-drivers-not-working-on-windows-7-10/"><u>[Fix] D1360 Printer Drivers Not Working on Windows 7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-error-code-oxc4eb827f-on-hp-printers/"><u>How to Fix Error Code OXC4EB827F on HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-online-functionality-regained/"><u>Epson Online Functionality Regained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-wireless-printer-setup-tutorial/"><u>HP Wireless Printer Setup Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-cant-print-spooler-disabled/"><u>[ISSUE] Can't Print - Spooler Disabled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-printer-error-alert/"><u>Unexpected Printer Error Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-inactivity-post-sleep-fix-guide/"><u>Win7 Printer Inactivity Post-Sleep: Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-mend-printer-queue-errors-on-windows-pcs/"><u>How to Mend Printer Queue Errors on Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rehabilitating-erratic-scanning-units/"><u>Rehabilitating Erratic Scanning Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-hp-photosmart-205n-printer-functions/"><u>Repaired HP Photosmart 205N Printer Functions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-guide-to-mfc-9330cdw-setup/"><u>Simple Guide to MFC-9330CDW Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tactics-for-uninstalling-windows-printers/"><u>Tactics for Uninstalling Windows Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-and-performance-boost-officejet-pro-8600-windows-version/"><u>Compatibility & Performance Boost: Officejet Pro 8600, Windows Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-11-printer-power-reset-issues/"><u>Fix Windows 11 Printer Power Reset Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-the-gap-when-printer-is-offline/"><u>Bridging the Gap When Printer Is Offline</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlock-potential-the-best-hr-vlogs-1-10-for-2024/"><u>Unlock Potential  The Best HR Vlogs #1-10 for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a15-5g-bootloader-easily-by-drfone-android/"><u>How to Unlock Samsung Galaxy A15 5G Bootloader Easily</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-live-obs-video-on-instagram/"><u>[Updated] Live OBS Video on Instagram</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-a2plus-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Xiaomi Redmi A2+ Phone without Any Data Loss</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-becoming-a-pro-streaming-on-youtube-and-twitch-via-obs/"><u>[New] 2024 Approved  Becoming a Pro  Streaming on YouTube & Twitch via OBS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-13-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 13 without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/celebrating-a-decade-and-half-of-free-lessons/"><u>Celebrating a Decade & Half of Free Lessons</u></a></li>
<li><a href="https://fox-helps.techidaily.com/after-effects-textwork-essentials-the-10-best-presets-for-2024/"><u>After Effects Textwork Essentials  The 10 Best Presets for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-mobile-animation-made-easy-best-free-3d-apps-for-android-and-ios/"><u>Updated Mobile Animation Made Easy Best Free 3D Apps for Android and iOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-7-pulse-pounding-workouts-that-gain-traction-on-social-media/"><u>[Updated] 2024 Approved  7 Pulse-Pounding Workouts That Gain Traction on Social Media</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-secrets-to-preserving-online-broadcasts-professionally/"><u>[Updated] In 2024, Secrets to Preserving Online Broadcasts Professionally</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/bring-back-the-sparkle-applying-instagram-effects-retro-style-for-2024/"><u>Bring Back the Sparkle  Applying Instagram Effects Retro Style for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-spark-interest-and-boost-views-on-instagram-videos-for-2024/"><u>[Updated] How to Spark Interest & Boost Views on Instagram Videos for 2024</u></a></li>
</ul></div>
