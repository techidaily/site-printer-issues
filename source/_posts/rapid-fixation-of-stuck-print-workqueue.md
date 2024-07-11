---
title: Rapid Fixation of Stuck Print Workqueue
date: 2024-07-10T16:43:15.496Z
updated: 2024-07-11T16:43:15.496Z
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
<li><a href="https://printer-issues.techidaily.com/hp-d1360-overcoming-driver-installation-obstacles-in-multiple-os-environments/"><u>HP D1360: Overcoming Driver Installation Obstacles in Multiple OS Environments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-active-directory-domain-services-is-currently-unavailable-printer-error/"><u>Fixed: The Active Directory Domain Services Is Currently Unavailable Printer Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rescue-mission-for-my-non-reactive-printer/"><u>Rescue Mission for My Non-Reactive Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-troubles-try-these-5-simple-ways-to-help-your-canon-print-on-windows-11/"><u>Print Troubles? Try These 5 Simple Ways to Help Your Canon Print on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-for-non-operational-post-upgrade-printer/"><u>Fix for Non-Operational Post-Upgrade Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-unblocked-scan-functionality/"><u>Windows 11: Unblocked Scan Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-steps-to-setup-canon-printer-in-pictures/"><u>Quick Steps to Setup - Canon Printer in Pictures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-connection-of-print-device/"><u>Successful Connection of Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-quick-fix-for-scanner-errors/"><u>Windows 11: Quick Fix for Scanner Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-access-a-guide-for-offline-printers/"><u>Regaining Access: A Guide for Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-windows-11-8-7-upgrade-guide/"><u>MF4770n Drivers - Windows 11, 8, 7 Upgrade Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-link-functional-print-device/"><u>Quick Link: Functional Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-jam-no-more-epson-printer-fixed/"><u>Paper Jam No More: Epson Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-persistent-spooler-problems-in-windows-systems/"><u>Remedying Persistent Spooler Problems in Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-operations-hp-officejet-pro-8600-windows-printer-driver/"><u>Smooth Operations: HP Officejet Pro 8600 Windows Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-link-issues-fastly/"><u>Fixing Printer Link Issues Fastly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-epsons-puzzling-error-x97/"><u>Tackling Epson's Puzzling Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-mended-hp-printer-no-output/"><u>Successfully Mended HP Printer No Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-resolving-non-printing-issues/"><u>Troubleshooting: Resolving Non-Printing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2-steps-to-set-up-canon-printer-with-pictures/"><u>2 Steps to Set up Canon Printer (With Pictures)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-print-processes-revealed/"><u>Brisk Print Processes Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-driver-quick-installation-steps/"><u>MFC-9330 Driver: Quick Installation Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-unjamming-of-print-workqueue/"><u>Rapid Unjamming of Print Workqueue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unexpected-configuration-blunder/"><u>Printer's Unexpected Configuration Blunder</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgraded-os-resolved-printer-disruption/"><u>Upgraded OS, Resolved Printer Disruption</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-internet-connectivity-for-brother-printer/"><u>Reclaiming Internet Connectivity for Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wins-overprint-taming-the-post-update-beast/"><u>Wins Overprint: Taming the Post-Update Beast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problems-windows-xp-10-printer-vanishes/"><u>[Network Problems] Windows XP-10, Printer Vanishes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensuring-smooth-performance-mf4770n-in-win11win8w7/"><u>Ensuring Smooth Performance: MF4770n in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-resolve-print-spooler-shutdown-woes-win-10-11-and-7/"><u>Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dell-inkjet-errors-immediately/"><u>Fixing Dell Inkjet Errors Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-driver-compatibility-with-multiple-windows-oses/"><u>HP Deskjet D1360 Driver Compatibility with Multiple Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-the-spell-of-paper-misfeeding/"><u>Breaking the Spell of Paper Misfeeding</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-freeing-up-youtube-views-no-more-grey-lines/"><u>[Updated] In 2024, Freeing Up YouTube Views  No More Grey Lines</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-on-your-apple-iphone-13-pro-max-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID On your Apple iPhone 13 Pro Max without Security Questions?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-capturing-online-seminars/"><u>In 2024, Capturing Online Seminars</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-innovative-insights-a-curated-list-s-pivotal-social-media-and-marketing-podcasts/"><u>Updated Innovative Insights A Curated List S Pivotal Social Media and Marketing Podcasts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-streamlined-techniques-to-record-screen-dialogue/"><u>2024 Approved  Streamlined Techniques to Record Screen Dialogue</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/capture-the-moment-smartphone-snapchat-recording-101-for-2024/"><u>Capture the Moment  Smartphone Snapchat Recording 101 for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-elevate-your-storytelling-with-strategic-video-callouts/"><u>[Updated] 2024 Approved  Elevate Your Storytelling with Strategic Video Callouts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/essential-mc-edifices-a-starter-collection-of-domiciles/"><u>Essential MC Edifices  A Starter Collection of Domiciles</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/examining-vlc-for-screen-capture-for-2024/"><u>Examining VLC for Screen Capture for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-inside-out-top-tips-for-windows-11-pros-for-2024/"><u>[Updated] Inside Out  Top Tips for Windows 11 Pros for 2024</u></a></li>
</ul></div>
