---
title: Hasten Reconnecting Print Queued Jobs
date: 2024-07-10T17:21:47.165Z
updated: 2024-07-11T17:21:47.165Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Hasten Reconnecting Print Queued Jobs
excerpt: This Article Describes Hasten Reconnecting Print Queued Jobs
keywords: Print Job Processing,Queue Management in Printing,Faster Job Reconnection,Printing Systems Optimization,Efficient Print Workflows,Optimized Printing Queues,Improved Printer Connectivity
thumbnail: https://thmb.techidaily.com/14595ce84d31d38abb3ed2fa0891687712e003ea9a69810e6bfa5725263bbf33.jpg
---

## Hasten Reconnecting Print Queued Jobs

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
<li><a href="https://printer-issues.techidaily.com/navigate-and-rectify-brother-printer-not-print-issue-on-windows-10/"><u>Navigate and Rectify Brother Printer Not Print Issue on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-service-down-action-required/"><u>Local Printer Spooler Service Down, Action Required</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-operation-revamping-mf4770n-on-w11-w8-w7-platforms/"><u>Seamless Operation: Revamping MF4770n on W11, W8, W7 Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-non-responsive-printer-in-windows-11/"><u>Resolve Non-Responsive Printer in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-office-printer-breakdowns/"><u>Overcoming Office Printer Breakdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recognition-failure-hp-driver-missing-in-win1011/"><u>Printer Recognition Failure: HP Driver Missing in WIN10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-overcome-unresponsive-hp-devices/"><u>Strategies to Overcome Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-software-revamp-for-windows-108-upgrades/"><u>MF4770n Software Revamp for WIndows 10/8 Upgrades</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-missing-printers-from-the-network/"><u>Troubleshooting Missing Printers From the Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-fixing-epson-error-x97/"><u>Understanding & Fixing Epson Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-fix-hp-printer-network-errors/"><u>Steps to Fix HP Printer Network Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-out-error-0x97-in-epson-units/"><u>Zeroing Out Error 0X97 in Epson Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-out-error-0x00000709-for-printer-settings/"><u>Zeroing Out Error 0X00000709 for Printer Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-simple-steps-to-make-your-canon-printer-work-again/"><u>5 Simple Steps to Make Your Canon Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-network-communication-issue/"><u>Repaired Network Communication Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-are-my-documents-black-and-white/"><u>Why Are My Documents Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-shared-printer-usage-concern/"><u>Resolved: Shared Printer Usage Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-print-problem-devices-unresponsive-post-sleep/"><u>Win7 Print Problem: Devices Unresponsive Post-Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-perfect-document-output/"><u>Restoring Perfect Document Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-fixing-unable-to-add-hp-d1360-drivers-in-windows-oses/"><u>[Error Fixing] Unable to Add HP D1360 Drivers in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-revolutionary-fix-for-frustrating-printers/"><u>The Revolutionary Fix for Frustrating Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silent-shutdown-wake-up-with-these-troubleshooting-steps/"><u>Silent Shutdown? Wake Up With These Troubleshooting Steps</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-realme-gt-3-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Realme GT 3 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-3-easy-ways-to-boosterincrease-volume-on-windows-for-free/"><u>In 2024, 3 Easy Ways to Booster/Increase Volume on Windows for Free</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensive-durecorder-manual-review/"><u>Comprehensive DuRecorder Manual Review</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/optimal-youtube-video-formats-a-comprehensive-guide-for-2024/"><u>Optimal YouTube Video Formats  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-audacity-workshop-eloquent-silent-transitions/"><u>[New] Audacity Workshop  Eloquent Silent Transitions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-webm-audio-extraction-from-twitta-vids/"><u>2024 Approved  WebM Audio Extraction From Twitta Vids</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-top-8-ai-titles-generators-for-creating-catchy-titles-for-all-platforms/"><u>New 2024 Approved Top 8 AI Titles Generators for Creating Catchy Titles For All Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-autofocus-plus-next-gen-hdr-image-processing-explained/"><u>[New] Autofocus Plus  Next-Gen HDR Image Processing Explained</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ising-stars-in-content-creation-lawful-view-boosting-methods/"><u>[New] Rising Stars in Content Creation  Lawful View Boosting Methods</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-making-your-mark-with-instagram-videos/"><u>2024 Approved  Making Your Mark with Instagram Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/captivating-collage-creations-ig/"><u>Captivating Collage Creations IG</u></a></li>
</ul></div>
