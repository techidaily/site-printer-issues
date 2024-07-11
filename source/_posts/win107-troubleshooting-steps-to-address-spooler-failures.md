---
title: Win10/7 Troubleshooting Steps to Address Spooler Failures
date: 2024-07-10T17:43:35.633Z
updated: 2024-07-11T17:43:35.633Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Win10/7 Troubleshooting Steps to Address Spooler Failures
excerpt: This Article Describes Win10/7 Troubleshooting Steps to Address Spooler Failures
keywords: Windows 10 Troubleshooting Guide,Windows 7 Spooler Failure Resolution,System Spooler Repair Steps,Solve Spooler Issues on Win10/7,Troubleshooting Spooler Errors in Windows,Fixing Spooler Failures in Windows OS,Addressing System Spooler Problems (Win10/7)
thumbnail: https://thmb.techidaily.com/c5a835a587cbde63390ec7ae0f646f52f65cc154a66fb89768e9cd878c5a4c7b.jpg
---

## Win10/7 Troubleshooting Steps to Address Spooler Failures

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-24.jpg)

 If you’re on Windows 7 or 10, and you’re seeing this error saying your**print spooler isn’t running** , you’re not alone. Many Windows users are reporting it. But the good news is you can fix it. This article gives you 5 solutions to try.

## What’s the print spooler?

 The print spooler is a Windows service that manages all the print jobs you send to your printer. If the service isn’t running, your printer won’t work.

## How do I fix print spooler keeps stopping?

 Here are 5 solutions you can try to fix this problem. You may not have to try them all; just work your way down the list until you find the one that works.**Note:** The screens shown below are from Windows 10, but all the fixes also apply to Windows 7 too.

1. **[Restart the Print Spooler service](#F1)**
2. **[Check if the Print Spooler service is set to Automatic](#F2)**
3. **[Change the Print Spooler Recovery options](#F3)**
4. **[Delete your print spooler files](#F4)**
5. **[Update your printer driver](#F5)**

### Method 1: Restart the Print Spooler service

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type **services.msc** and press **Enter** to open the **Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Click **Print Spooler** , then **Restart** .  

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a515fac43cb.jpg)

4) Check to see if your printer works.

### Method 2: Check if the Print Spooler service is set to Automatic

 If the print spooler service isn’t set to automatic, it won’t turn on when Windows starts, and your printer won’t work until you manually start the service.

To set it to auto:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

3) Right-click **Print Spooler** , then click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a54177dc82e.jpg)

 4) Make sure Startup type is set to **Automatic**  , then click**Apply** \> **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a51825cb795.png)

5) Check to see if your printer works.

### Method 3: Change the Print Spooler Recovery options

 If your print spooler recovery settings are incorrect, your print spooler won’t automatically restart if it fails for some reason.

 To set your recovery settings correctly:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click **Print Spooler** , then click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a54177dc82e.jpg)

 4) Click **Recovery** , ensure all **three** **failure fields** are set to **Restart the Service**  and click**Apply** \> **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a51c37d1a84.png)

 5) Check to see if your printer works.  

### Method 4: Delete your print spooler files

 If your pending print jobs are not few, they can cause your print spooler to stop. Deleting your print spooler files to clear pending print jobs sometimes resolve the problem.

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

3) Click **Print Spooler** , then **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a5269d7216e.jpg)

 4) Click**—** to minimize the Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/minimize.jpg)

 5) On your keyboard, press the   **Windows logo key**  and **E**  at the same time to open Windows File Explorer.  

 6) Go to **C:\\Windows\\System32\\spool\\PRINTERS** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS.jpg)

 If you’re prompted about permission, click **Continue** .

 7)**Delete all the files** in PRINTERS folder.You should then see **This folder is empty** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/empty.jpg)

8) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

9) Type control and press**Enter** to open Control Panel:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a53a72eb0b7.png)

 10) On the open window, choose to view by**Catalog** . Then click**View devices and printers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/04/control-Panel.jpg)

 11) Right-click on your printer and click **Remove device** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/REMOVE.jpg)

 12) Click**Services** icon in your taskbar to return to Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/SETTINGS-WINDOW.jpg)

 13) Click on**Print Spooler** then**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a538386c9a4.jpg)

 14)Click the **Devices and Printers icon**  in your taskbar to return to the Devices and Printers window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS-ICON.jpg)

 15) **Right-click on the blank area** and click **Add a printer**  , then follow the on-screen instructions to re-add your printer:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a542a63d1d0.png)

16) Check to see if your printer works.

### Method 5: Update your printer driver

 This error may also be caused by an old or incorrect printer driver. You can update your printer driver manually or, if you’re not confident playing around with drivers, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975af310cda9.jpg)

3) Click the **Update**  button next to a flagged printer driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5976a910cca49.jpg)

 After you update your printer driver, restart your PC and check if your printer works.

 Hopefully your printer is now working. Please feel free to leave a comment below if you have any problems.

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
<li><a href="https://printer-issues.techidaily.com/why-are-my-documents-black-and-white/"><u>Why Are My Documents Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-your-non-printing-canon-into-a-reliable-device-with-tips/"><u>Turn Your Non-Printing Canon Into a Reliable Device with Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-printer-added-operation-without-issues/"><u>New Printer Added: Operation Without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-back-life-to-dead-printer/"><u>Bringing Back Life to Dead Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-print-queue-disruption-in-multiple-oss/"><u>Preventing Print Queue Disruption in Multiple OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-your-brother-printers-print-function-on-windows-1011/"><u>Reignite Your Brother Printer's Print Function on Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-windows-11-printer-work-again/"><u>Make Windows 11 Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-windows-10-printer-setup-woes/"><u>Tackle Windows 10 Printer Setup Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-printer/"><u>Successfully Installed Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-navigate-canons-wireless-print-setup/"><u>Effortlessly Navigate Canon's Wireless Print Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-job-queue-freeze/"><u>Overcome Print Job Queue Freeze</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addsvc-not-responding-printer-error-reported/"><u>ADDSVC Not Responding: Printer Error Reported</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-connect-my-printer-help-required/"><u>Cant Connect My Printer - Help Required</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-all-pages-print-glitch/"><u>Fix All-Pages Print Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-problem-hp-printer-driver-unavailable-in-winxo/"><u>[Windows Problem] HP Printer Driver Unavailable in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-paper-jams-and-misprints-on-windows-10/"><u>Resolve Paper Jams & Misprints on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-solve-stuck-printer-job-queue/"><u>Swiftly Solve Stuck Printer Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-117-fix-for-non-responsive-printer-spooler/"><u>Win 11/7 Fix for Non-Responsive Printer Spooler</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/quick-fix-for-clearer-focus-in-google-meet/"><u>Quick Fix for Clearer Focus in Google Meet</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-unveiling-the-top-9-revolutionary-ai-driven-audio-simulators-set-for-2024/"><u>Updated Unveiling the Top 9 Revolutionary AI-Driven Audio Simulators Set for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-memetic-engineering-techniques-for-2024/"><u>10 Memetic Engineering Techniques for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktok-speak-up-a-step-by-step-instructional-guide-for-2024/"><u>TikTok Speak Up  A Step-by-Step Instructional Guide for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-meme-making-made-simple-without-cost/"><u>[Updated] Meme-Making Made Simple, Without Cost</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-apple-id-from-iphone-7-by-drfone-ios/"><u>How To Unlink Apple ID From iPhone 7</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-perfecting-slow-motion-cinematography-for-social-media-engagement-on-instagram/"><u>2024 Approved  Perfecting Slow Motion Cinematography for Social Media Engagement on Instagram</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-securely-growing-your-channels-popularity-a-one-million-goal-guide/"><u>[Updated] Securely Growing Your Channel's Popularity  A One-Million Goal Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-transform-videos-with-these-premium-free-sound-options/"><u>[Updated] 2024 Approved  Transform Videos with These Premium, Free Sound Options</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-comprehensive-insight-into-simple-high-dynamic-range-capture/"><u>[Updated] Comprehensive Insight Into Simple High-Dynamic Range Capture</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tips-for-producing-high-quality-hdr-photographs-with-lightroom/"><u>In 2024, Tips for Producing High-Quality HDR Photographs with Lightroom</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-how-to-add-subtitlescaptions-in-final-cut-pro-x-in-2024/"><u>New How to Add Subtitles/Captions in Final Cut Pro X, In 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-prevent-youtube-spam-channel-blocking-guide-for-all-platforms/"><u>[New] 2024 Approved  Prevent Youtube Spam  Channel Blocking Guide for All Platforms</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-infinix-note-30-vip-racing-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-mastering-windows-10-the-hidden-paths-for-importation/"><u>[Updated] 2024 Approved  Mastering Windows 10  The Hidden Paths for Importation</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/expert-curated-win-screenshot-and-recorders-list-for-2024/"><u>Expert-Curated Win Screenshot and Recorders List for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/benchmark-analysis-djis-drone-phantom-3/"><u>Benchmark Analysis  DJI's Drone Phantom 3</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/making-the-most-of-your-youtube-thumbnail-space-for-2024/"><u>Making the Most of Your YouTube Thumbnail Space for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-immediate-techniques-for-instagram-video-audio-extraction-mp3/"><u>[Updated] Immediate Techniques for Instagram Video Audio Extraction (MP3)</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
</ul></div>
