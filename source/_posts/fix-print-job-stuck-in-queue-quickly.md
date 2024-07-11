---
title: Fix ‘Print Job Stuck in Queue’ Quickly
date: 2024-07-10T17:31:05.733Z
updated: 2024-07-11T17:31:05.733Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fix ‘Print Job Stuck in Queue’ Quickly
excerpt: This Article Describes Fix ‘Print Job Stuck in Queue’ Quickly
keywords: Quick Print Job Fix,Resolve Stuck Printer Queue,Stop Printing Errors Immediately,Print Queue Troubleshooting Steps,Prevent Print Job Delays,Printer Queue Management Tips,Expeditious Printer Issue Resolution
thumbnail: https://thmb.techidaily.com/3cd047344d86e8920c72e515095d66dfd7e255dbcb41fa2030513ad2ed26d835.jpg
---

## Fix ‘Print Job Stuck in Queue’ Quickly

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
<li><a href="https://printer-issues.techidaily.com/breathe-new-life-into-non-printing-brother-printer-in-windows-1011/"><u>Breathe New Life Into Non-Printing Brother Printer in Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-print-functionality-top-5-tips-and-tricks-for-a-working-canon-printer-in-windows-11/"><u>Revive Print Functionality: Top 5 Tips & Tricks for a Working Canon Printer in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-instant-ink-into-your-networked-devices/"><u>Integrating HP Instant Ink Into Your Networked Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-windows-11-8-7-and-mf4770n-for-efficiency/"><u>Harmonizing Windows 11, 8, 7 & MF4770n for Efficiency</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-are-missing/"><u>Printer OS Error: Drivers Are MISSING</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-without-hurdles-for-printer/"><u>Installation Without Hurdles for Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-and-tricks-connecting-your-canon-instantly/"><u>Tips & Tricks: Connecting Your Canon Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-print-driver-missing-in-windows-1110/"><u>HP Print Driver Missing in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-solved-error-avoided/"><u>Printer Puzzle Solved: Error Avoided</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-locate-missing-print-server-device/"><u>How to Locate Missing Print Server Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-link-between-sibling-and-online-printer/"><u>Restoring Link Between Sibling and Online Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-compatibility-boosting-mf4770n-performance-in-win11win8w7/"><u>Enhance Compatibility: Boosting MF4770n Performance in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-d1360-printer-setup-failure-in-multiple-windows-versions/"><u>HP D1360 Printer Setup Failure in Multiple Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-blank-page-error-in-your-homes-epson-printer/"><u>Fix Blank Page Error in Your Home's Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-paper-refilling-for-hp-officejet-pro-m574dw/"><u>Wireless Paper Refilling for HP Officejet Pro M574dw</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-windows-setup-for-your-new-hp-device/"><u>Navigating Through Windows Setup for Your New HP Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-enhancement-mf4770n-software-upgrade-windows/"><u>System Enhancement: MF4770n Software Upgrade WIndows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/search-for-printer-device-failed-on-pc-os/"><u>Search for Printer Device Failed on PC OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-scanner-windows-10-troubleshooting-tips/"><u>Reconnect Scanner: Windows 10 Troubleshooting Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-older-printer-drivers-for-modern-windows-10/"><u>Revitalize Older Printer Drivers for Modern Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-restoration-completed-for-win11/"><u>Scanner Restoration Completed for Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-windows-10s-canon-printer-operation-success-rate/"><u>Boost Windows 10'S Canon Printer Operation Success Rate</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canons-error-b200/"><u>Fixed Canon's Error: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-sheet-woes-end-with-hp-printer-update-fixed/"><u>White Sheet Woes End with HP Printer Update Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-intermittent-print-job-failures-windows/"><u>Steps to Stop Intermittent Print Job Failures (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-driver-upgrade-for-w11w8w7/"><u>MF4770n Driver Upgrade for W11/W8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-network-failure/"><u>Resolved Printer Network Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-non-operational-driver-missing/"><u>Printer Non-Operational: Driver Missing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-steps-for-setting-up-your-canon-printer-visual-aids/"><u>Quick Steps for Setting up Your Canon Printer (Visual Aids)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-protect-your-privacy-top-webcam-shields-ranked/"><u>[New] Protect Your Privacy - Top Webcam Shields Ranked</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-from-confusion-to-clarity-why-this-mp3-converter-article-is-a-must-read/"><u>2024 Approved From Confusion to Clarity Why This Mp3 Converter Article Is a Must-Read</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-from-scratch-to-screen-video-editing-with-youtube-and-others/"><u>[Updated] From Scratch to Screen  Video Editing with YouTube & Others</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-express-corporate-essence-designing-emblems-on-the-go/"><u>[New] Express Corporate Essence - Designing Emblems on the Go</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-anime-for-your-lifes-highlights-todays-most-captivating-streaming-channels-2023-new/"><u>2024 Approved  Anime for Your Life’s Highlights  Today's Most Captivating Streaming Channels [2023 New]</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-the-art-of-import-in-windows-10-photo-space/"><u>Mastering the Art of Import in Windows 10 Photo Space</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-various-methods-to-transfer-pictures-from-apple-iphone-12-mini-to-pc-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Various Methods to Transfer Pictures from Apple iPhone 12 mini to PC | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-make-video-fade-to-black-in-movie-maker-easily/"><u>How to Make Video Fade to Black in Movie Maker Easily</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-filter-flash-explore-the-most-popular-snap-filters/"><u>[Updated] Filter Flash  Explore the Most Popular Snap Filters</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-ultimate-guide-to-filmora-discounts-4-top-secrets-revealed/"><u>New The Ultimate Guide to Filmora Discounts 4 Top Secrets Revealed</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-capturing-the-essence-of-hits-shortform-music-video-tips/"><u>2024 Approved  Capturing the Essence of Hits  Shortform Music Video Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unveiling-the-financial-dynamics-of-youtube-shorts/"><u>[Updated] Unveiling the Financial Dynamics of YouTube Shorts</u></a></li>
<li><a href="https://facebook.techidaily.com/advent-of-more-crypto-posts-on-fb-and-insta/"><u>Advent of More Crypto Posts on FB & Insta</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-get-free-followers-on-tiktok-in-10-ways/"><u>[Updated] In 2024, Get Free Followers on TikTok in 10 Ways</u></a></li>
</ul></div>
