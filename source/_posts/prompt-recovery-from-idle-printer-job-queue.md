---
title: Prompt Recovery From Idle Printer Job Queue
date: 2024-07-10T16:45:02.774Z
updated: 2024-07-11T16:45:02.774Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Prompt Recovery From Idle Printer Job Queue
excerpt: This Article Describes Prompt Recovery From Idle Printer Job Queue
keywords: Idle Printer Management,Printer Job Queue Optimization,Recovering Stalled Print Jobs,Faster Printer Processing,Idle Printer Solutions,Streamline Print Job Queue,Prevent Printer Idle State
thumbnail: https://thmb.techidaily.com/b26ebe6269139cbbd405443b637f006fbb51cb0816412b85d5c12d4c87d21986.jpg
---

## Prompt Recovery From Idle Printer Job Queue

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
<li><a href="https://printer-issues.techidaily.com/correct-windows-11-printer-connection-fails/"><u>Correct Windows 11 Printer Connection Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-for-windows-print-system/"><u>Driver Search Failed for Windows Print System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-win-11-printer-hiccup-after-update/"><u>Resolved Win 11 Printer Hiccup After Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-connectivity-crunch-windows-7-usb-printer-dormancy/"><u>[Resolved] Connectivity Crunch: Windows 7 USB Printer Dormancy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-non-responding-printer-on-windows-me-version/"><u>Revitalize Non-Responding Printer on Windows ME Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-setting-up-hp-projetronics-with-pc/"><u>Guide: Setting up HP Projetronics with PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reestablish-links-essential-steps-to-solve-printer-woes/"><u>Reestablish Links: Essential Steps to Solve Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-no-print-after-win7-device-suspend/"><u>[Solved] No Print After Win7 Device Suspend</u></a></li>
<li><a href="https://printer-issues.techidaily.com/not-all-colors-printing-as-expected/"><u>Not All Colors Printing as Expected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-efficiency-install-dell-printer-driver-update-in-win7/"><u>Boost Efficiency: Install Dell Printer Driver Update in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-hp-printer-connectivity-issues/"><u>Unlocking HP Printer Connectivity Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimizing-mf4770n-driver-for-w11-w8-w7/"><u>Optimizing MF4770n Driver for W11, W8, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reach-new-horizons-in-printer-functionality-4630-driver-upgrade-guide/"><u>Reach New Horizons in Printer Functionality: 4630 Driver Upgrade Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/another-computer-is-using-the-printer-solved/"><u>Another Computer Is Using the Printer [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-inkjet-error-on-windows-7/"><u>Resolved Inkjet Error on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-integrating-printer-model-8720-in-pc/"><u>How-To: Integrating Printer Model 8720 in PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-epson-error-codes-halt/"><u>Avoiding Epson Error Codes Halt</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-hurdle-installation-of-hp-d1360-printer-drivers/"><u>Compatibility Hurdle: Installation of HP D1360 Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-re-enable-scanned-device-connection/"><u>Windows 10: Re-Enable Scanned Device Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-hp-printers-oxc4eb827f-error/"><u>Resolving HP Printer's OXC4EB827F Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-pathway-attaching-hp-8720-to-computer-systems/"><u>Setup Pathway: Attaching HP 8720 to Computer Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-upgrade-streamline-mf4770n-in-windows/"><u>Drive Upgrade: Streamline MF4770n in WIndows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-eliminated/"><u>Error B200 Eliminated</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-audio-enhancement-for-videos-without-breaking-the-bank-exploring-three-free-approaches/"><u>New In 2024, Audio Enhancement for Videos Without Breaking the Bank Exploring Three Free Approaches</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-create-impact-with-intro-excellence-best-free-services-reviewed-for-2024/"><u>[New] Create Impact with Intro Excellence  Best Free Services Reviewed for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/audio-editing-mastery-l-cuts-and-j-cuts-in-final-cut-pro-x-for-2024/"><u>Audio Editing Mastery L-Cuts and J-Cuts in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-lost-and-found-30-free-speech-to-text-mac-hits/"><u>2024 Approved  Lost and Found  30 Free Speech-to-Text Mac Hits</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-detailed-review-of-obss-video-capturing-tools-for-2024/"><u>[New] Detailed Review of OBS's Video Capturing Tools for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-a-complete-resource-for-aspiring-xbox-streaming-pros/"><u>[Updated] In 2024, A Complete Resource for Aspiring Xbox Streaming Pros</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-oppo-reno-8t-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Oppo Reno 8T Screen | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-the-ultimate-guide-to-free-video-playback-vlc-or-mpc/"><u>[New] In 2024, The Ultimate Guide to Free Video Playback  VLC or MPC?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-expert-tips-to-master-camera-snap-in-zoom-calls/"><u>[Updated] 2024 Approved  Expert Tips to Master Camera Snap in Zoom Calls</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/enhance-your-medias-exposure-on-the-platform-for-2024/"><u>Enhance Your Media's Exposure on the Platform for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-win11-and-nvidia-7025-conflict/"><u>Resolved: Win11 & Nvidia 7025 Conflict</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-samsung-galaxy-s8-setting-new-standards-for-4k-video/"><u>2024 Approved  Samsung Galaxy S8  Setting New Standards for 4K Video</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-game-changing-impact-of-tiktok-in-modern-business-marketing/"><u>2024 Approved  The Game-Changing Impact of TikTok in Modern Business Marketing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-audio-anomalies-top-disruptive-apps-on-the-go/"><u>[Updated] In 2024, Audio Anomalies  Top Disruptive Apps on the Go</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-the-quintessential-compilation-3-aplus-online-services-for-elevated-sound-in-media/"><u>Updated 2024 Approved The Quintessential Compilation 3 A+ Online Services for Elevated Sound in Media</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-blueprint-to-instagram-profit-partnerships-beyond-likes-and-shares/"><u>[Updated] In 2024, The Blueprint to Instagram Profit Partnerships  Beyond Likes and Shares</u></a></li>
</ul></div>
