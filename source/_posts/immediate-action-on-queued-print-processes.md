---
title: Immediate Action on Queued Print Processes
date: 2024-07-10T17:25:26.996Z
updated: 2024-07-11T17:25:26.996Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Action on Queued Print Processes
excerpt: This Article Describes Immediate Action on Queued Print Processes
keywords: Queue Reduction,Print Queue Management,Printer Processing Time,Fast Print Resolution,Print Queue Optimization,Rapid Print Processing,Print Queue Cancellation
thumbnail: https://thmb.techidaily.com/2e7cadf9e7c8396ddc846863b7d8b8551ba6b8c7abac3eec6dd5274d2d66a517.jpg
---

## Immediate Action on Queued Print Processes

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
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-without-hurdles-for-printer/"><u>Installation Without Hurdles for Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574150252-unexpected-printer-error-alert/"><u>Unexpected Printer Error Alert!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-windows-7-software-for-dell-inkjet-aios/"><u>Cutting Edge: Windows 7 Software for Dell Inkjet AIOs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-connected-successfully/"><u>Resolved: PRINTER Connected Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pixma-mp620-searching-for-driver-on-win11-repository/"><u>Pixma MP620: Searching for Driver on Win11 Repository</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-print-job-responsiveness-on-xp-edition/"><u>Enhance Print Job Responsiveness on XP Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-ink-cartridge-errors-in-printers/"><u>Decoding Ink Cartridge Errors in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-scanner-now-functional/"><u>Windows 11: Scanner Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silent-shutdown-wake-up-with-these-troubleshooting-steps/"><u>Silent Shutdown? Wake Up With These Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-completely-erase-a-windows-printer/"><u>Guide: Completely Erase a Windows Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hack-your-way-through-pcl-xl-troubles/"><u>Hack Your Way Through PCL XL Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-dilemma-ends-after-new-windows-installation/"><u>Print Dilemma Ends After New Windows Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-hp-printer-seamlessly-in-windows-environment/"><u>Integrate HP Printer Seamlessly in Windows Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-misaligned-images-from-w11-printers/"><u>Correct Misaligned Images From W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-network-issue-resolved-in-win7-pro/"><u>Printer Network Issue Resolved in Win7 Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-puzzle-resolved-error-0x00000709/"><u>Printer Setup Puzzle: Resolved Error 0X00000709</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-epson-paper-jam-signals/"><u>Navigating Through Epson Paper Jam Signals</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-hp-paper-jam-resolved/"><u>Win11 HP Paper Jam Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/erase-print-task-queue-pause/"><u>Erase Print Task Queue Pause</u></a></li>
<li><a href="https://printer-issues.techidaily.com/black-and-white-only-mode-engaged-by-printer/"><u>Black & White Only Mode Engaged by Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-response-to-queued-prints/"><u>Rapid Response to Queued Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-scanner-activation-issue-after-installing-updates/"><u>Fix Scanner Activation Issue After Installing Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-center-finding-hidden-network-devices-in-win-10/"><u>[Solution Center] Finding Hidden Network Devices in Win 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-drivers-and-utilities-officejet-pro-8600-for-pc-users/"><u>Unified Drivers & Utilities: OfficeJet Pro 8600 for PC Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-printer-driver-setup-for-hp-deskjet-d1360-on-pcs/"><u>Trouble with Printer Driver Setup for HP Deskjet D1360 on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-issue-mp620-unavailable-in-win10/"><u>Printer Driver Issue: MP620 Unavailable in WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixation-local-network-printer-spooler-stuck/"><u>[FIXATION] Local Network Printer Spooler Stuck</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resume-printing-with-online-canon-printer-tips/"><u>Resume Printing with Online Canon Printer Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-offline-not-responding-errors/"><u>Printer Offline, Not Responding Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-offline-print-slot/"><u>Repaired Offline Print Slot</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-hp-d1360-drivers-success-on-windows-versions/"><u>Installing HP D1360 Drivers: Success on Windows Versions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-driven-print-screws/"><u>Unblocking Driven Print Screws</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-learn-how-to-extract-sound-from-video-using-the-different-online-and-software-tools-details-about-their-features-proscons-and-more-are-given.m/"><u>2024 Approved Learn How to Extract Sound From Video Using the Different Online and Software Tools. Details About Their Features, Pros/Cons, and More Are Given</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-discover-the-best-zero-cost-4k-video-editors/"><u>Updated In 2024, Discover the Best Zero-Cost 4K Video Editors</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-intuitive-speech-alteration-capabilities-overview-rules-and-substitutes/"><u>Updated 2024 Approved Intuitive Speech Alteration Capabilities Overview, Rules, & Substitutes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-8-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 8 Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-lava-yuva-2-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Lava Yuva 2 Without PUK Codes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-15-stunning-gif-splitter-examples-you-need-to-bookmark/"><u>2024 Approved 15 Stunning GIF Splitter Examples You Need to Bookmark</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-zoom-into-action-capturing-your-desktop-ezvide-style/"><u>In 2024, Zoom Into Action  Capturing Your Desktop, EZvide Style</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-unmarked-tiktok-video-access-for-iphone-users/"><u>2024 Approved  Unmarked TikTok Video Access for iPhone Users</u></a></li>
<li><a href="https://youtube-web.techidaily.com/xplore-the-best-15-youtube-sources-for-sci-education-for-2024/"><u>[New] Explore the Best 15 YouTube Sources for Sci-Education for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-chart-success-using-youtube-statistics-to-grow-engagement/"><u>[Updated] 2024 Approved  Chart Success  Using YouTube Statistics to Grow Engagement</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-sonyfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your SonyFRP Lock</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-lava-yuva-2-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Lava Yuva 2</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-advanced-tips-for-mastering-color-grading-via-3d-luts-in-photoshop/"><u>[Updated] Advanced Tips for Mastering Color Grading via 3D LUTs in Photoshop</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-apple-iphone-14-pro-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Apple iPhone 14 Pro iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/quick-and-detailed-guide-to-iphoneipad-for-youtube-video-uploading/"><u>Quick & Detailed Guide to iPhone/iPad for YouTube Video Uploading</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-light-and-shadow-masterful-edits-that-transform-images/"><u>[Updated] Light & Shadow  Masterful Edits That Transform Images</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-10-best-webcam-recorders-windows-11/"><u>[Updated] 10 Best Webcam Recorders Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-saving-made-easy-a-step-by-step-final-cut-pro-guide/"><u>Updated In 2024, Saving Made Easy A Step-by-Step Final Cut Pro Guide</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-turn-onoff-motion-blur-in-dying-light-2/"><u>Updated 2024 Approved How to Turn On/Off Motion Blur in Dying Light 2?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-5-high-end-drones-for-professionals/"><u>In 2024, Best 5 High-End Drones for Professionals</u></a></li>
</ul></div>
