---
title: Accelerate Clearing Print Job Queue
date: 2024-07-10T17:24:56.769Z
updated: 2024-07-11T17:24:56.769Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Clearing Print Job Queue
excerpt: This Article Describes Accelerate Clearing Print Job Queue
keywords: Accelerated Print Job Processing,Print Job Queue Optimization,High-Speed Print Job Management,Rapid Printing Solutions,Print Queue Acceleration Techniques,Efficient Print Job Prioritization,Streamline Print Management
thumbnail: https://thmb.techidaily.com/4e313b1018e0c2499cbd20182728d1887cb747f9b7e2192f6f1e12c2015f85ae.jpg
---

## Accelerate Clearing Print Job Queue

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
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-your-hp-laserjet-remote-connection/"><u>Setting Up Your HP LaserJet Remote Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-configuring-officejet-pro-in-your-pc/"><u>Tutorial: Configuring OfficeJet Pro in Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-sibling-print-device-from-online-standby-mode/"><u>Reviving Sibling Print Device From Online Standby Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-dell-printer-offline-error-on-windows-7/"><u>Resolved Dell Printer Offline Error on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-print-functionality-after-win-11-update/"><u>Restored Print Functionality After Win 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-release-of-stuck-prints/"><u>Rapid Release of Stuck Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-for-languishing-printer-jobs/"><u>Quick Fix for Languishing Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-solved-for-epson-model/"><u>Print Issue Solved for Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-system-cannot-retrieve-printer-drivers/"><u>Win System: Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-prevent-print-service-interruptions-on-w7w10w11/"><u>How to Prevent Print Service Interruptions on W7/W10/W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-order-a-printers-tale-after-windows-update/"><u>Restoring Order: A Printer's Tale After Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-component-pixma-mp620-driver-on-windows-10/"><u>[Missing Component] Pixma MP620 Driver on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-jolt-to-halted-print-queues/"><u>Swift Jolt to Halted Print Queues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-connectivity-restored/"><u>[PRINT] Connectivity Restored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-software-revamp-for-windows-108-upgrades/"><u>MF4770n Software Revamp for WIndows 10/8 Upgrades</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-repeated-print-job-failures-guide-for-windows-107-users/"><u>End Repeated Print Job Failures: Guide for Windows 10/7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-offline-canon-printer-immediately/"><u>Revive Offline Canon Printer Immediately</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/high-speed-replicas-best-racing-games-for-2024/"><u>High-Speed Replicas  Best Racing Games for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-list-top-android-video-editing-apps-for-chromebook/"><u>2024 Approved The Ultimate List Top Android Video Editing Apps for Chromebook</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-a-compreenas-guide-to-auto-and-advanced-camera-exposure-methods/"><u>[New] A Compreenas Guide to Auto and Advanced Camera Exposure Methods</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-embrace-freedom-with-easy-watermark-free-tiktok-videos/"><u>[Updated] Embrace Freedom with Easy, Watermark-Free TikTok Videos</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-y27-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-visual-blueprint-understanding-social-media-aspect-ratios-for-success/"><u>Updated The Visual Blueprint Understanding Social Media Aspect Ratios for Success</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-photo-hdr-techniques-in-adobe-ps/"><u>Mastering Photo HDR Techniques in Adobe PS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-motorola-moto-g23-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola Moto G23 Unlock Without Password</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-top-best-fast-photo-viewer-for-windows-10-in-2024/"><u>[New] Top Best Fast Photo Viewer for Windows 10, In 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unveiling-the-true-income-potential-in-podcasting-for-2024/"><u>[New] Unveiling the True Income Potential in Podcasting for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-youtube-brand-partnerships-with-famebit-tools-for-2024/"><u>Mastering YouTube Brand Partnerships with FameBit Tools for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-complete-zoomers-handbook-for-captivating-video-and-audio-content/"><u>[New] 2024 Approved  The Complete Zoomer's Handbook for Captivating Video and Audio Content</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-crafting-an-epic-tiktok-farewell-sequence/"><u>2024 Approved  Crafting An Epic TikTok Farewell Sequence</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-image-improvement-masterclass-top-apps-decoded/"><u>2024 Approved  Image Improvement Masterclass - Top Apps Decoded</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-navigating-to-past-facebook-stories-a-step-by-step-mobile-and-laptop-guide/"><u>[New] 2024 Approved  Navigating to Past Facebook Stories  A Step-by-Step Mobile & Laptop Guide</u></a></li>
</ul></div>
