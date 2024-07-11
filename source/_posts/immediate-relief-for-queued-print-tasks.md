---
title: Immediate Relief for Queued Print Tasks
date: 2024-07-10T17:18:19.011Z
updated: 2024-07-11T17:18:19.011Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Relief for Queued Print Tasks
excerpt: This Article Describes Immediate Relief for Queued Print Tasks
keywords: Print Job Priority,Rapid Print Solutions,Queue Management for Printers,Print Task Optimization,Accelerated Print Job Processing,Immediate Printer Task Handling,Efficient Print Queue Management Software
thumbnail: https://thmb.techidaily.com/f9de1b8537995642a992ee19d4d561ae28b96c9f39e2e2df9627023fc6a490d6.jpg
---

## Immediate Relief for Queued Print Tasks

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
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-print-job-errors/"><u>Eliminating Ghost Print Job Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ease-into-plc-error-resolution/"><u>Ease Into PLC Error Resolution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systematic-update-for-enhanced-mf4770n-performance-windows/"><u>Systematic Update for Enhanced MF4770n Performance Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-installation-woes-on-windows-11/"><u>MP620 Printer Installation Woes on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-no-response-issues-with-hp-printers/"><u>Overcoming No Response Issues with HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-peak-performance-in-officejets-by-latest-driver-update/"><u>Achieve Peak Performance in Officejets by Latest Driver Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-glitch-printer-no-longer-functions/"><u>Post-Update Glitch: Printer No Longer Functions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-spooler-error-affects-print-output/"><u>[WARNING] Spooler Error Affects Print Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scan-activation-successful-in-windows-11/"><u>Scan Activation Successful in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-disabled-printer-problem-detected/"><u>Active Directory Disabled - Printer Problem Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-errors-resolving-them-in-windows-11/"><u>Printer Errors: Resolving Them in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silencing-the-silent-printouts-in-your-device/"><u>Silencing the Silent Printouts in Your Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-unprintable-feature-fixed-quickly/"><u>Epson's Unprintable Feature Fixed Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/intuitive-firmware-update-process-for-hp-printers-especially-4630/"><u>Intuitive Firmware Update Process for HP Printers, Especially 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-cure-printer-blank-screens/"><u>Guidelines to Cure Printer Blank Screens</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-networked-printer-issues/"><u>Navigating Through Networked Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-wireless-printer-setup-tutorial/"><u>HP Wireless Printer Setup Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unused-printer-new-machine-alert/"><u>Unused Printer: New Machine Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-canon-printer-wi-fi-setup/"><u>Mastering Canon Printer Wi-Fi Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-printer-configuration-errors-in-w11/"><u>Correct Printer Configuration Errors in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expedite-jammed-print-queue/"><u>Expedite Jammed Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-windows-hp-printer-offline/"><u>Resolving Windows HP Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-color-in-black-and-white-outputs/"><u>No Color in Black and White Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problem-hp-printer-driver-issues-across-windows-versions/"><u>[Network Problem] HP Printer Driver Issues Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-print-job-responsiveness-on-xp-edition/"><u>Enhance Print Job Responsiveness on XP Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-paper-jamming-problem/"><u>Overcome Paper Jamming Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dead-paper-output-in-hp-printers/"><u>Fixing Dead Paper Output in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-hp-xp-paper-issue/"><u>Troubleshooting Offline HP XP Paper Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-printer-not-responding-spooler-issue/"><u>Windows Printer Not Responding: Spooler Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-printer-link-to-spooler/"><u>Restored PRINTER Link to Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-hp-printer-oxc4eb827f-fatality-problem/"><u>Solving HP Printer OXC4EB827F Fatality Problem</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/igital-artisans-exclusive-summit/"><u>[New] Digital Artisans' Exclusive Summit</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-quick-fixes-screen-recording-snapchat-hacks/"><u>2024 Approved  Quick Fixes  Screen Recording Snapchat Hacks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-samsung-galaxy-a25-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Samsung Galaxy A25 5G Phone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/an-insiders-view-on-creating-effective-slug-lines/"><u>An Insider's View on Creating Effective Slug Lines</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-vidtwitter-effortless-video-downloads-from-social-sites/"><u>[Updated] In 2024, VidTwitter  Effortless Video Downloads From Social Sites</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-audio-amplification-for-impressive-instagram-reels/"><u>[New] Audio Amplification for Impressive Instagram Reels</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-how-to-recover-hidden-shorts-thumbnails-in-videos/"><u>[New] How to Recover Hidden Shorts' Thumbnails in Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/tlessly-convert-youtube-audio-top-4-low-cost-apps-for-2024/"><u>Effortlessly Convert YouTube Audio - Top 4 Low-Cost Apps for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-guide-to-blending-multiple-exposures-into-a-single-hdr-in-lightroom/"><u>In 2024, The Ultimate Guide to Blending Multiple Exposures Into a Single HDR in Lightroom</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-how-to-use-green-screen-for-streaming/"><u>2024 Approved  How to Use Green Screen for Streaming</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-vortex-keywords-that-propel-you-into-social-media-spotlight/"><u>Viral Vortex  Keywords that Propel You Into Social Media Spotlight</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-maximize-mobile-viewing-sharper-chromebook-and-phone-videos/"><u>2024 Approved  Maximize Mobile Viewing  Sharper Chromebook and Phone Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-live-stream-archive-a-users-blueprint-to-downloadability-for-2024/"><u>[New] Live Stream Archive  A User's Blueprint to Downloadability for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-chorus-cache-secure-and-inspect-audio-recordings/"><u>[New] In 2024, Chorus Cache  Secure & Inspect Audio Recordings</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-essential-list-of-leading-mp3-metadata-editors-in-the-cloud-for-2024/"><u>New The Essential List of Leading MP3 Metadata Editors in the Cloud for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-2024-general-facts-challenge-videos/"><u>[New] Top 2024 General Facts Challenge Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-cutting-edge-mac-hd-screen-and-sound-mastery/"><u>In 2024, Cutting-Edge Mac HD Screen and Sound Mastery</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/recording-voice-overs-like-a-pro-top-tips-for-final-cut-pro-users-for-2024/"><u>Recording Voice Overs Like a Pro Top Tips for Final Cut Pro Users for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Honor Magic 5 Pro | Dr.fone</u></a></li>
</ul></div>
