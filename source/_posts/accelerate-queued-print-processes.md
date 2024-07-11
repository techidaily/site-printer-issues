---
title: Accelerate Queued Print Processes
date: 2024-07-10T16:51:12.625Z
updated: 2024-07-11T16:51:12.625Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Queued Print Processes
excerpt: This Article Describes Accelerate Queued Print Processes
keywords: Accelerate Printing Speed,Improve Print Workflow Efficiency,Queue Management for Printers,Reduce Queued Printing Times,Optimize Print Job Scheduling,Enhance Printer Process Speed,Streamline Printing Workflows
thumbnail: https://thmb.techidaily.com/2453bc5c0249af0de921ee166f14d8e128b375913b07ba9cca730be764e6c410.jpg
---

## Accelerate Queued Print Processes

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
<li><a href="https://printer-issues.techidaily.com/foreign-processors-print-job-revealed/"><u>Foreign Processor's Print Job Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/v305-dell-printer-driver-fix-for-windows-7/"><u>V305 Dell Printer Driver Fix for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-adding-hp-printer-to-computer-network/"><u>Tutorial: Adding HP Printer to Computer Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-alert-unable-to-locate-on-windows-10/"><u>[Printer Driver Alert]: Unable to Locate on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win9598-printer-non-engagement-a-fix-guide/"><u>Win95/98 Printer Non-Engagement: A Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-inkjet-hp-not-printing-error/"><u>Solved: Inkjet HP Not Printing Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-and-remedying-paper-misalignment/"><u>Preventing and Remedying Paper Misalignment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-printer-connection-swiftly/"><u>Restore Printer Connection Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fixed-version-printing-whole-documents/"><u>New Fixed Version: Printing Whole Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-navigate-canons-wireless-print-setup/"><u>Effortlessly Navigate Canon's Wireless Print Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-offline-print-slot/"><u>Repaired Offline Print Slot</u></a></li>
<li><a href="https://printer-issues.techidaily.com/another-computer-is-using-the-printer-solved/"><u>Another Computer Is Using the Printer [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-link-between-printer-and-network/"><u>Re-Establishing Link Between Printer & Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fixing-silent-hp-toner-units/"><u>Guide to Fixing Silent HP Toner Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-driver-update-win32-officejet-pro-8600-utility-bundle/"><u>Streamlined Driver Update: Win32 Officejet Pro 8600 Utility Bundle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-network-print-problems/"><u>Resolving Network Print Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wins-overprint-taming-the-post-update-beast/"><u>Wins Overprint: Taming the Post-Update Beast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-scanner-now-functional/"><u>Windows 11: Scanner Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-issue-printer-drivers-failing-on-w7-10-need-solution/"><u>[Technical Issue] Printer Drivers Failing on W7-10, Need Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-fedex-printer-connectivity-troubles/"><u>Rectifying FedEx Printer Connectivity Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-error/"><u>Mended Printer Network Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-clear-document-reception-from-hp-printer/"><u>Restoring Clear Document Reception From HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-prints-new-dell-v305-windows-enhancements/"><u>Streamline Prints: New Dell V305 WIndows Enhancements</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-iphone-12-mini-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your iPhone 12 mini on MetroPCS</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-itel-a60s-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Itel A60s Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/boost-engagement-with-effective-wirecast-broadcasts-on-fb/"><u>Boost Engagement with Effective Wirecast Broadcasts on FB</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-how-to-edit-recorded-video/"><u>2024 Approved How to Edit Recorded Video</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-m4r-converter-101-what-you-need-to-know-to-get-started-for-2024/"><u>New M4R Converter 101 What You Need to Know to Get Started for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-master-classes-online-top-ten-subscriber-leaders/"><u>2024 Approved  Master Classes Online  Top Ten Subscriber-Leaders</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-x100-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo X100</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-from-your-iphone-13-mini-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID From your iPhone 13 mini?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-archive-of-awe-high-quality-gif-preservation-for-tweeters-for-2024/"><u>[Updated] Archive of Awe  High-Quality GIF Preservation for Tweeters for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leapfrogging-to-photo-editing-mastery-with-lunapic/"><u>In 2024, Leapfrogging to Photo Editing Mastery with LunaPic</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-lava-blaze-2-5g-frp-by-drfone-android/"><u>Full Guide to Bypass Lava Blaze 2 5G FRP</u></a></li>
</ul></div>
