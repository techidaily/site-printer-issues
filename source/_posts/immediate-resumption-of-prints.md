---
title: Immediate Resumption of Prints
date: 2024-07-10T16:46:21.395Z
updated: 2024-07-11T16:46:21.395Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Resumption of Prints
excerpt: This Article Describes Immediate Resumption of Prints
keywords: Print On Demand Services,Rapid Printing Solutions,Quick Resume Printers,Efficient Print Backup Services,Urgent Prints Providers,Continuous Printing Support,Instant Resumption Printers (IRP)
thumbnail: https://thmb.techidaily.com/cb2689090616a1ba21a99aa6be50929e603a0dc8061abd47262715b07e4d29cd.jpg
---

## Immediate Resumption of Prints

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
<li><a href="https://printer-issues.techidaily.com/how-to-prevent-print-service-interruptions-on-w7w10w11/"><u>How to Prevent Print Service Interruptions on W7/W10/W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win2k-printer-response-error-resolution-guide/"><u>Win2K Printer Response: Error Resolution Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-driver-not-compatible-with-multiple-windows-systems-for-hp-d1360/"><u>Print Device Driver Not Compatible with Multiple Windows Systems for HP D1360</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-quick-fix-for-scanner-errors/"><u>Windows 11: Quick Fix for Scanner Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-issues-quick-solutions-needed/"><u>Windows 11 Printer Issues - Quick Solutions Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-hp-printer-on-dos-systems/"><u>Unblocking Offline Status: HP Printer on DOS Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-performance-upgrade-dell-inkjet-aio-on-windows-7/"><u>Drive Performance: Upgrade Dell Inkjet AIO on WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/transforming-empty-sheets-into-essential-data/"><u>Transforming Empty Sheets Into Essential Data</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-white-pages-a-printers-triumph-story/"><u>No More White Pages: A Printer's Triumph Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-installation-wizard-officejet-pro-8600-windows-printer-suite/"><u>Seamless Installation Wizard: Officejet Pro 8600 Windows Printer Suite</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-queue-hang-up-promptly/"><u>Resolve Print Queue Hang-Up Promptly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-inkjet-now-functioning-correctly/"><u>Epson Inkjet, Now Functioning Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unite-your-workspace-3-cutting-edge-solutions-for-hp-and-laptop-connection/"><u>Unite Your Workspace: 3 Cutting-Edge Solutions for HP and Laptop Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-perfect-document-output/"><u>Restoring Perfect Document Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-tangle-printer-reconfigured-incorrectly/"><u>Technical Tangle: Printer Reconfigured Incorrectly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-printers-availability-with-these-tips/"><u>Regain Printer's Availability with These Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cure-non-engagement-in-older-windows-versions-printers/"><u>Cure Non-Engagement in Older Windows Versions' Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-network-printer-how-to-restore-visibility/"><u>Missing Network Printer - How to Restore Visibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-default-problem-error-0x00000709-fixed/"><u>Unraveling Printer Default Problem - Error 0X00000709 Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-printing-malfunction-detected/"><u>Color Printing Malfunction Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-found-inkjet-not-printing-epson/"><u>Fix Found: Inkjet Not Printing [Epson]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-barriers-reconnecting-brothers-networked-printer/"><u>Breaking Barriers: Reconnecting Brother's Networked Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-hp-printer-error-code-oxc4eb827f/"><u>Purging HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/proactive-measures-immediate-resolution-of-pcl-xl-problems/"><u>Proactive Measures: Immediate Resolution of PCL XL Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-locate-canon-pixma-mp620-drivers-on-win10/"><u>Unable to Locate Canon Pixma MP620 Drivers on WIN10</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/1715860151582-in-2024-a-stepwise-approach-for-creating-an-interactive-skype-conversation-among-users-from-multiple-operating-systems/"><u>In 2024, A Stepwise Approach for Creating an Interactive Skype Conversation Among Users From Multiple Operating Systems.</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-stretching-out-youtube-video-quality/"><u>[Updated] Stretching Out YouTube Video Quality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/efficient-recording-techniques-for-itunes-media/"><u>Efficient Recording Techniques for iTunes Media</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-visualize-freely-premium-no-cost-screen-capture-tools/"><u>[New] 2024 Approved  Visualize Freely  Premium No-Cost Screen Capture Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enjoy-a-seamless-streaming-experience-unveiling-the-potential-of-pip-on-netflix/"><u>Enjoy a Seamless Streaming Experience  Unveiling the Potential of PIP on Netflix</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/channel-conversion-secrets-yt-vs-igtv-for-2024/"><u>Channel Conversion Secrets  YT Vs IGTV for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-steps-for-finding-absent-registry-program/"><u>Immediate Steps for Finding Absent Registry Program</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-lava-yuva-3-pro-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Lava Yuva 3 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/xcellent-video-and-picture-capture-for-iphones-and-androids-here/"><u>[New] Excellent Video & Picture Capture for iPhones & Androids Here!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-mix-memes-with-a-smile/"><u>[Updated] 2024 Approved  Mix Memes with a Smile</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-steps-for-turning-pin-videos-into-music-files/"><u>[New] Ultimate Steps for Turning Pin Videos Into Music Files</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-vivo-t2x-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Vivo T2x 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-learn-to-initiate-harmonious-group-conversations-on-skype-for-both-pc-and-mac-users/"><u>[New] In 2024, Learn to Initiate Harmonious Group Conversations on Skype for Both PC & Mac Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-make-screenshots-and-recordings-on-imac-simple/"><u>2024 Approved  Make Screenshots & Recordings on iMac Simple</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unveiling-figmas-bg-elimination-mastery/"><u>[Updated] In 2024, Unveiling Figma's BG Elimination Mastery</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-ultimate-canon-video-editing-handbook-software-tips-and-trends/"><u>2024 Approved The Ultimate Canon Video Editing Handbook Software, Tips, and Trends</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-builds-for-a-thriving-mc-village-homes-for-2024/"><u>Best Builds for a Thriving MC Village Homes for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-pro-tips-for-efficient-and-effective-use-of-siri-on-tiktok-for-2024/"><u>[Updated] Pro Tips for Efficient and Effective Use of Siri on TikTok for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-secret-to-perfectly-sizing-your-vertical-videos-for-social-platforms-for-2024/"><u>The Secret to Perfectly Sizing Your Vertical Videos for Social Platforms for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-breaking-down-this-years-latest-tiktok-wave/"><u>[Updated] 2024 Approved  Breaking Down This Year's Latest TikTok Wave</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/broadcasting-vids-directly-from-phone-twitter-without-retweets-for-2024/"><u>Broadcasting Vids Directly From Phone – Twitter, Without Retweets for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-expert-strategies-to-elevate-your-video-recordings/"><u>In 2024, Expert Strategies to Elevate Your Video Recordings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-internet-capture-devices/"><u>[New] Best Internet Capture Devices</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-from-photos-to-masterpieces-5-recommended-slideshow-creators/"><u>2024 Approved From Photos to Masterpieces 5 Recommended Slideshow Creators</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 To Other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-anime-inspired-makeup-and-costume-ideas-for-tiktoks/"><u>[New] 2024 Approved  Anime-Inspired Makeup & Costume Ideas for TikToks</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-best-5-tiktok-voice-generators-you-should-try-for-2024/"><u>New Best 5 TikTok Voice Generators You Should Try for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/comprehensive-guide-to-youtubes-best-anime-stations-for-2024/"><u>Comprehensive Guide to YouTube's Best Anime Stations for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-cross-service-song-matching-sharing-your-musical-journey/"><u>[New] 2024 Approved  Cross-Service Song Matching  Sharing Your Musical Journey</u></a></li>
</ul></div>
