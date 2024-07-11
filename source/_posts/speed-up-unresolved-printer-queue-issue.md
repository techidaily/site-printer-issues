---
title: Speed Up Unresolved Printer Queue Issue
date: 2024-07-10T17:05:44.196Z
updated: 2024-07-11T17:05:44.196Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speed Up Unresolved Printer Queue Issue
excerpt: This Article Describes Speed Up Unresolved Printer Queue Issue
keywords: Unresolved Printer Queue,Print Spooler Problems,Printer Service Restart,Faster Printer Queue Processing,Print Job Acceleration Tips,Printer Queue Management,Optimize Printer Performance,Unresolved Printer Queue Solutions and Fixes,How to Troubleshoot Print Spooler Issues in Windows,Quickly Restarting the Print Service for Faster Print Processing,Tips for Accelerating Your Printer's Job Throughput,Effective Printer Queue Management Strategies,Improving Overall Printer Performance and Speed,Eliminating Latency in Unresolved Print Queues
thumbnail: https://thmb.techidaily.com/79f8247109e3ede5c749bfadee103c2b769f1b6d964f687393a932568d85d036.jpg
---

## Speed Up Unresolved Printer Queue Issue

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
<li><a href="https://printer-issues.techidaily.com/fixed-printer-malfunctions-post-win11-rollout/"><u>Fixed: Printer Malfunctions Post Win11 Rollout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/default-printer-dilemma-windows-error-0x00000709-squashed/"><u>Default Printer Dilemma: Windows Error (0X00000709) Squashed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-print-problems-canon-printer-guide-in-windows-10/"><u>Fixing Print Problems: Canon Printer Guide in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11s-online-scanning-no-longer-inactive/"><u>Win11's Online Scanning No Longer Inactive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-os-struggles-hp-driver-not-available/"><u>Windows OS Struggles: HP Driver Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-constant-spooler-crashes-a-guide-for-windows-users/"><u>Preventing Constant Spooler Crashes: A Guide for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mp620-printer-driver-unavailable-on-windows-10/"><u>Canon MP620 Printer Driver Unavailable on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-print-issue-with-brother-printer-in-windows-oses/"><u>Resolving No-Print Issue with Brother Printer in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-solve-offline-canon-printer-issues/"><u>Connectivity Woes? Solve Offline Canon Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-inactive-print-devices/"><u>Solutions for Inactive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-updates-for-sluggish-printers/"><u>Speedy Updates for Sluggish Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-elimination-windows-printer-setback-0x00000709/"><u>Error Elimination: Windows Printer Setback (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-errors-the-cure-for-windows-xp7/"><u>HP Laserjet Errors: The Cure for Windows XP/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-canon-printer-fixes-for-windows-users/"><u>Effortless Canon Printer Fixes for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-colored-output-not-rendered/"><u>Printer's Colored Output Not Rendered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-stopped-printing-fixed-now/"><u>HP LaserJet Stopped Printing - Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/defeating-paper-jams-fixing-spooler-issues-win-1011/"><u>Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-epson-paper-jam/"><u>Overcome Epson Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversing-printer-freezes/"><u>Reversing Printer Freezes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-printer-drivers-for-better-output-win10-edition/"><u>Upgrade Printer Drivers for Better Output, WIN10 Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recovering-windows-hp-printer-status/"><u>Recovering Windows HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-access-sister-brother-printer-offline-fix-guide/"><u>Regain Access: Sister-Brother Printer Offline Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-forget-a-connected-printer-in-win-1011/"><u>Strategies to Forget a Connected Printer in Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-fixes-five-steps-to-ensure-your-canon-works-in-windows-11/"><u>Quick Printer Fixes: Five Steps to Ensure Your Canon Works in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reengage-the-printing-pro-saving-brother-printer-from-isolation/"><u>Reengage the Printing Pro: Saving Brother Printer From Isolation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pot-player-review/"><u>2024 Approved  POT Player Review</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oneplus-nord-ce-3-lite-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your OnePlus Nord CE 3 Lite 5G</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-amplify-your-vision-audio-interface-for-richer-media-experience/"><u>2024 Approved Amplify Your Vision-Audio Interface For Richer Media Experience</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-capture-clarity-high-end-gyroscopic-tripod-gear/"><u>In 2024, Capture Clarity  High-End Gyroscopic Tripod Gear</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-power-of-precision-an-in-depth-tutorial-for-using-the-background-eraser-in-ps/"><u>In 2024, The Power of Precision  An In-Depth Tutorial for Using the Background Eraser in PS</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-pioneering-success-innovative-youtube-strategies/"><u>[New] In 2024, Pioneering Success  Innovative YouTube Strategies</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/addressing-youtube-shorts-no-image-upload-issue-for-2024/"><u>Addressing YouTube Shorts  No Image Upload Issue for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-download-fb-links-8-free-online-tools/"><u>[New] 2024 Approved  Download FB Links  8 FREE, Online Tools</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/video-editing-software-similar-to-virtualdub-features-and-pricing-for-2024/"><u>Video Editing Software Similar to VirtualDub Features and Pricing for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovating-with-color-a-complete-look-at-ps-3d-luts/"><u>Innovating with Color  A Complete Look at PS 3D LUTs</u></a></li>
</ul></div>
