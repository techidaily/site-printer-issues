---
title: Rapid Fixation of Stuck Print Workqueue
date: 2024-06-28T06:51:31.951Z
updated: 2024-06-29T06:51:31.951Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Fixation of Stuck Print Workqueue
excerpt: This Article Describes Rapid Fixation of Stuck Print Workqueue
keywords: Rapid Workflow Solutions,Stuck Print Queue Remediation,Print Workflow Optimization,Quick Stuck Print Queue Resolution,Effective Print Queue Management,Workflow Bottleneck Solutions in Printing,Streamlining Stuck Print Processes
thumbnail: https://thmb.techidaily.com/443fa3d21137649dff0319f1c3c3070702e32a7b2f673e094959a8fdb4cdbd5b.jpg
---

## Rapid Fixation of Stuck Print Workqueue

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
<li><a href="https://printer-issues.techidaily.com/overcoming-inkjet-breakdowns-quickly/"><u>Overcoming Inkjet Breakdowns Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-missing-printers-from-the-network/"><u>Troubleshooting Missing Printers From the Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-post-update-fix/"><u>Printer Error Post-Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-compatible-with-online-scanner-again/"><u>Win11 Compatible with Online Scanner Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-status-online-on-windows-11/"><u>HP OfficeJet Status: Online on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-canon-printers-functionality-with-these-top-5-fixes-for-windows-11-users/"><u>Boost Your Canon Printer's Functionality with These Top 5 Fixes for Windows 11 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-installation-of-multi-function-printer/"><u>Successful Installation of Multi-Function Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-scanner-activation-issue-after-installing-updates/"><u>Fix Scanner Activation Issue After Installing Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-link-to-computer-post-update/"><u>Reactivating Scanner Link to Computer Post-Update</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-path-to-digital-fame-on-youtube-begins-here/"><u>[Updated] The Path to Digital Fame on YouTube Begins Here</u></a></li>
<li><a href="https://video-capture.techidaily.com/a-list-screen-recorders-for-expert-users-for-2024/"><u>A-List Screen Recorders for Expert Users for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oneplus-nord-ce-3-lite-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track OnePlus Nord CE 3 Lite 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-what-is-public-domain-art/"><u>2024 Approved  What Is Public Domain Art</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/maximizing-profits-from-a-million-viewer-baseline/"><u>Maximizing Profits From a Million-Viewer Baseline</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-nubia-red-magic-8s-pro-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Nubia Red Magic 8S Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-pova-6-pro-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Pova 6 Pro 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-handbook-obspluszoom-collaboration-for-2024/"><u>[New] The Ultimate Handbook  OBS+Zoom Collaboration for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-create-a-sports-highlight-video/"><u>[New] 2024 Approved  How to Create a Sports Highlight Video</u></a></li>
</ul></div>