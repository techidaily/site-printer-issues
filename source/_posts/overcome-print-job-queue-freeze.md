---
title: Overcome Print Job Queue Freeze
date: 2024-07-10T17:33:10.427Z
updated: 2024-07-11T17:33:10.427Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Overcome Print Job Queue Freeze
excerpt: This Article Describes Overcome Print Job Queue Freeze
keywords: Print Job Management,Prevent Print Queue Bottlenecks,Resolve Printer Queue Errors,Print Job Optimization Techniques,Overcoming Printer Queue Halt Issues,Synchronized Printing Processes,Advanced Print Queue Management
thumbnail: https://thmb.techidaily.com/fb4a67269b09db2a7f2f5849b8bae34d180258d63241c7d8da96fca41cce9da8.jpg
---

## Overcome Print Job Queue Freeze

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
<li><a href="https://printer-issues.techidaily.com/intuitive-firmware-update-process-for-hp-printers-especially-4630/"><u>Intuitive Firmware Update Process for HP Printers, Especially 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-recurring-printer-errors-on-windows-systems/"><u>Quick Remedies for Recurring Printer Errors on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-hp-printer-not-responding/"><u>How to Fix HP Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-reviving-inactive-hp-copiers/"><u>Techniques for Reviving Inactive HP Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-life-into-your-dying-windows-11-printer/"><u>Breathe Life Into Your Dying Windows 11 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driving-performance-mf4770n-on-windows-oss/"><u>Driving Performance: MF4770n on Windows OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-network-settings-on-printers/"><u>Resetting Network Settings on Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-disconnected-print-service/"><u>Fixing Disconnected Print Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-and-resume-a-step-by-step-guide-for-printers/"><u>Reconnect and Resume: A Step-by-Step Guide for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-printer-software-solution-officejet-pro-8600-for-windows-pcs/"><u>Unified Printer Software Solution: Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-white-sheet-saga-with-hp-printer-fix/"><u>Ending White Sheet Saga with HP Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnose-and-cure-win10-print-spooler-hiccups/"><u>Diagnose & Cure WIN10 Print Spooler Hiccups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-lexmark-printer-glitches/"><u>Addressing Lexmark Printer Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brew-the-latest-printer-driver-potion-in-windows-7/"><u>Brew the Latest Printer Driver Potion in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-fixation-of-stuck-print-workqueue/"><u>Rapid Fixation of Stuck Print Workqueue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-activation-and-setup-for-windows-users/"><u>HP Printer Activation & Setup for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-missing-driver-in-windows-os/"><u>HP Printer Setup: Missing Driver in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-your-silent-canon-printer-now/"><u>Reconnect Your Silent Canon Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-hidden-cause-of-blank-printouts/"><u>Unveiling the Hidden Cause of Blank Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt2000-reactivate-sluggish-printer-response/"><u>WinNT/2000: Reactivate Sluggish Printer Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/refining-drive-functionality-mf4770n-windows-update/"><u>Refining Drive Functionality: MF4770n Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-wireless-printer-setup-tutorial/"><u>HP Wireless Printer Setup Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disconnecting-all-print-devices-at-once-on-pc/"><u>Disconnecting All Print Devices at Once on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-windows-11-8-7-upgrade-guide/"><u>MF4770n Drivers - Windows 11, 8, 7 Upgrade Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-disconnect-resolved/"><u>Epson Disconnect Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unforeseen-setup-snag-found/"><u>Printer's Unforeseen Setup Snag Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-duplicate-printer-usage-detection/"><u>Resolved: Duplicate Printer Usage Detection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restart-hp-printer-for-online-status/"><u>Restart HP Printer for Online Status</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-digital-sound-effects-on-demand-a-compilation-of-the-best-websites-to-download-ding-noises/"><u>New 2024 Approved Digital Sound Effects on Demand A Compilation of the Best Websites to Download Ding Noises</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-galaxy-s23-tactical-edition-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Samsung Galaxy S23 Tactical Edition Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://driver-install.techidaily.com/fresh-beats-new-software-tips-for-scarlett-6i6-driver-update/"><u>Fresh Beats, New Software: Tips for Scarlett 6I6 Driver Update</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revolutionizing-your-gaming-with-advanced-controller-software/"><u>In 2024, Revolutionizing Your Gaming with Advanced Controller Software</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-ios-and-android-photo-editing-face-tools/"><u>2024 Approved  Best iOS and Android Photo-Editing Face Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-live-footage-at-its-best-gamers-recording-tips/"><u>[New] 2024 Approved  Live Footage at Its Best  Gamers' Recording Tips</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-create-glitch-text-effect/"><u>New Create Glitch Text Effect</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-inside-the-tech-a-comprehensive-review-of-apowersofts-recorder/"><u>[Updated] Inside the Tech  A Comprehensive Review of Apowersoft’s Recorder</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-essential-blueprint-for-srt-file-adaptability/"><u>[New] The Essential Blueprint for SRT File Adaptability</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-elevate-engagement-cutting-edge-hashtags-for-hit-making-videos/"><u>[Updated] Elevate Engagement  Cutting-Edge Hashtags for Hit-Making Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-boost-virtual-engagement-select-top-10-recorder-software/"><u>[New] 2024 Approved  Boost Virtual Engagement  Select Top 10 Recorder Software</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-finns-fiscal-flow-income-insights-from-youtube-icon/"><u>2024 Approved  Finn's Fiscal Flow  Income Insights From YouTube Icon</u></a></li>
<li><a href="https://audio-editing.techidaily.com/advanced-audio-format-switcher-instant-mp3-generation-for-modern-listeners-for-2024/"><u>Advanced Audio Format Switcher Instant MP3 Generation for Modern Listeners for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-this-article-is-actually-the-guide-regarding-editing-the-videos-through-veed-as-a-substitute-wondershare-filmora-is-also-under-discussion-that-is-also-a/"><u>New This Article Is Actually the Guide Regarding Editing the Videos Through VEED. As a Substitute, Wondershare Filmora Is Also Under Discussion that Is Also Available for the Same Purpose</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/the-best-of-breed-top-10-tiktok-reactions/"><u>The Best of Breed  Top 10 TikTok Reactions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/gaming-history-told-by-top-video-makers/"><u>Gaming History Told by Top Video Makers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-add-video-filters-in-zoom/"><u>In 2024, How To Add Video Filters In Zoom</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-from-screen-shots-to-speech-navigating-the-best-37-applications-for-video-to-text-translation/"><u>[New] In 2024, From Screen Shots to Speech  Navigating the Best 37 Applications for Video-to-Text Translation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pinnacle-performance-discover-the-top-8-webcams-today/"><u>Pinnacle Performance  Discover the Top 8 Webcams Today</u></a></li>
</ul></div>
