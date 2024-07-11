---
title: Bypass Printer Job Queue Delay Instantly
date: 2024-07-10T16:44:10.136Z
updated: 2024-07-11T16:44:10.136Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Bypass Printer Job Queue Delay Instantly
excerpt: This Article Describes Bypass Printer Job Queue Delay Instantly
keywords: Instant Print Queue Bypass,Printer Job Speed Up,Avoid Printer Wait Time,Fast Print Processing,Printer Queue Optimization,Real-Time Printer Job Management,Eliminate Print Job Latency
thumbnail: https://thmb.techidaily.com/850c193e7db5e5c0dafad83a501e0d012a7f8ab4be61e59f0459fea3e866d702.png
---

## Bypass Printer Job Queue Delay Instantly

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
<li><a href="https://printer-issues.techidaily.com/unused-printer-new-machine-alert/"><u>Unused Printer: New Machine Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-error-code-oxc4eb827f/"><u>Overcoming HP Printer Error Code: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-issue-unable-to-locate-hp-print-drivers-on-win11/"><u>[System Issue] - Unable to Locate HP Print Drivers on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smoothed-out-printer-connection-hurdles/"><u>Smoothed Out Printer Connection Hurdles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-load-printer-driver-not-detected-by-win/"><u>Cannot Load Printer: Driver Not Detected by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-due-to-current-domain-services-outage/"><u>Print Issue Due to Current Domain Services Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-glitch-resolution-0x97/"><u>Epson Glitch Resolution: 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dispelling-hp-printers-fatal-mistake-0xoxc4eb827f/"><u>Dispelling HP Printer's Fatal Mistake 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/saving-day-printer-function-reclaimed-post-update-crisis/"><u>Saving Day: Printer Function Reclaimed Post-Update Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-without-problems/"><u>Printer Setup: Completed Without Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winme-printer-no-response-how-to-remedy-it/"><u>WinME Printer No Response - How to Remedy It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-windows-7-printer-unresponsive/"><u>Resolved: Windows 7 Printer Unresponsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-code-0x97-uncovered-and-resolved/"><u>Epson Fault Code 0X97 Uncovered & Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-disconnected-scanner-issue-in-windows-10/"><u>Resolving Disconnected Scanner Issue in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-the-road-for-printer-errors-with-windows-update/"><u>The End of the Road for Printer Errors with Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-white-paper-output-on-hp-printer/"><u>Resolving White Paper Output on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smart-strategies-for-effective-windows-based-hp-printer-setups/"><u>Smart Strategies for Effective Windows-Based HP Printer Setups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-resumption-of-prints/"><u>Immediate Resumption of Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-inaccessible-for-windows-print/"><u>Driver Inaccessible for Windows Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-fixes-for-non-starting-print-spooler-on-pcs/"><u>Essential Fixes for Non-Starting Print Spooler on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printing-speed-instantly/"><u>Boost Printing Speed Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-maintenance-causing-print-errors/"><u>AD DS Maintenance Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-missing-hp-support-in-windows-1110/"><u>[Print] Missing HP Support in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-for-broken-feeders/"><u>Quick-Fix for Broken Feeders</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-a-step-by-step-guide-to-professionalizing-your-personal-brand-on-fb-stories-for-2024/"><u>[Updated] A Step-by-Step Guide to Professionalizing Your Personal Brand on FB Stories for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-inventory-types-of-fb-video-ratios-for-2024/"><u>[New] Inventory  Types of FB Video Ratios for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-6-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone 6 Plus | Stellar</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/issecting-youtubes-selection-of-trending-video-responses/"><u>[New] Dissecting YouTube's Selection of Trending Video Responses</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-download-video-as-mp3-with-vimeo-step-by-step-guide-for-2024/"><u>[Updated] Download Video as MP3 with Vimeo - Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-music-syncing-for-iphones-and-androids-in-fb/"><u>[New] Music Syncing for iPhones & Androids in FB</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-best-performance-at-a-glance-top-4k-laptops/"><u>2024 Approved  Best Performance at a Glance - Top 4K Laptops</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-samsung-galaxy-s24-ultra-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Samsung Galaxy S24 Ultra Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tailored-timeline-management-best-twitter-unfollow-tools-ranked/"><u>[Updated] In 2024, Tailored Timeline Management  Best Twitter Unfollow Tools Ranked</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-increasing-roi-mastering-the-art-of-fb-animation-ads/"><u>[New] 2024 Approved  Increasing ROI  Mastering the Art of FB Animation Ads</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-video-capturing-step-by-step-manual/"><u>[Updated] 2024 Approved  Mastering Video Capturing  Step-by-Step Manual</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-hdr-standards-meeting-or-surpassing-with-aurora/"><u>2024 Approved  HDR Standards  Meeting or Surpassing with Aurora?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-ultimate-guide-to-selecting-a-reliable-youtube-to-mp4-converter/"><u>2024 Approved The Ultimate Guide to Selecting a Reliable YouTube to MP4 Converter</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-tips-uploading-to-apple-podcast-network-for-2024/"><u>Quick Tips  Uploading to Apple Podcast Network for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/imate-live-streaming-apps-for-iphone-and-android-users-on-youtube-for-2024/"><u>7 Ultimate Live Streaming Apps for iPhone and Android Users on YouTube for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-journey-into-the-creative-realm-top-25-tiktok-anime-ideas/"><u>2024 Approved  Journey Into the Creative Realm  Top 25 TikTok Anime Ideas</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimize-your-media-output-with-our-top-10-online-subtitles-tools/"><u>In 2024, Optimize Your Media Output With Our Top 10 Online Subtitles Tools</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Realme 11X 5G | Dr.fone</u></a></li>
</ul></div>
