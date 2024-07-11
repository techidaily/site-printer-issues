---
title: Stop Windows Print Service From Frequently Stopping
date: 2024-07-10T17:19:04.417Z
updated: 2024-07-11T17:19:04.417Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop Windows Print Service From Frequently Stopping
excerpt: This Article Describes Stop Windows Print Service From Frequently Stopping
keywords: Windows Print Spooler Troubleshooting,Stop Printer Service Restarts,Fix Print Spooler Errors,Windows Print Service Stability Improvement,Prevent Windows Printer Hangs,Enhance Print Service Performance in Windows,Windows Printer Spooling Issues Fix Guide
thumbnail: https://thmb.techidaily.com/6110f59d84b8b2836afe3cb9128ab55b4983bac7c041837cad5f3c0f9163df97.jpg
---

## Stop Windows Print Service From Frequently Stopping

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
<li><a href="https://printer-issues.techidaily.com/windows-10-cant-find-the-pixma-mp620-printer-driver/"><u>Windows 10 Can't Find the Pixma MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-print-spooler-keeps-stopping-on-windows-11-and-7/"><u>How to Fix Print Spooler Keeps Stopping on Windows 11 & 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fix-scanner-disconnection-in-windows-10/"><u>Guide to Fix Scanner Disconnection in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stay-current-with-the-latest-driver-release-for-hp-4630/"><u>Stay Current with the Latest Driver Release for HP 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-connection-between-printer-and-wifi/"><u>Re-Establishing Connection Between Printer & WiFi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-corrective-action-complete/"><u>B200 Corrective Action Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-connectivity-disconnection/"><u>Solved Connectivity Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-connection-setting-up-hp-laserlife-connectivity/"><u>Secure Connection: Setting Up HP LaserLife Connectivity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-missing-hp-support-in-windows-1110/"><u>[Print] Missing HP Support in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unwillingness-for-full-color-printing/"><u>Printer's Unwillingness for Full-Color Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unravel-offline-mystery-with-easy-fixes-for-your-canon-printer/"><u>Unravel Offline Mystery with Easy Fixes for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-interruptions-on-win7win10/"><u>Avoiding Constant Printer Service Interruptions on Win7/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-print-performance-dells-latest-aio-upgrades-in-win7/"><u>Optimize Print Performance: Dell's Latest AIO Upgrades in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-missing-hp-print-drivers-unfound/"><u>Windows Missing: HP Print Drivers Unfound</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-blank-pages-no-more-fixing-printer-issues/"><u>Endless Blank Pages No More: Fixing Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-paper-jamming-in-w11-laser-printers/"><u>Solve Paper Jamming in W11 Laser Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halftone-problem-with-color-prints/"><u>Halftone Problem with Color Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-connectivity-now-functional/"><u>Epson Connectivity Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-efficiency-printer-software-update-for-dell-and-win7/"><u>Enhance Efficiency: Printer Software Update for Dell & Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cease-print-slowdown-in-winxp-solution-found/"><u>Cease Print Slowdown in WinXP - Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-printer-error-alert/"><u>Unexpected Printer Error Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/securely-link-disconnected-printer-quickly/"><u>Securely Link Disconnected Printer Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-white-paper-output-on-hp-printer/"><u>Resolving White Paper Output on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pixma-mp620-drivers-lost-on-win11-systems/"><u>Pixma MP620 Drivers Lost on Win11 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-internet-connectivity-for-brother-printer/"><u>Reclaiming Internet Connectivity for Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-maximize-meeting-success-top-recording-tools-for-2024/"><u>[New] Maximize Meeting Success  Top Recording Tools for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-achieve-pro-level-results-with-these-top-obs-edits/"><u>[New] Achieve Pro-Level Results with These Top OBS Edits</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-make-a-killer-gaming-intro-best-software-for-pc-and-mac/"><u>New 2024 Approved Make a Killer Gaming Intro Best Software for PC and Mac</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-25-best-real-time-voice-changers-full-review-should-i-use-them/"><u>2024 Approved 25 Best Real-Time Voice Changers Full Review - Should I Use Them?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-surrender-to-serenity-top-10-game-guides-for-2024/"><u>[New] Surrender to Serenity  Top 10 Game Guides for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-mastering-gopro-timelapse-a-step-by-step-guide/"><u>2024 Approved  Mastering GoPro Timelapse  A Step-by-Step Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unveiling-sharex-analyses-and-options-for-2024/"><u>[New] Unveiling ShareX  Analyses & Options for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-capturing-kinetic-energy-in-iphone-images/"><u>[New] The Art of Capturing Kinetic Energy in iPhone Images</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-razr-40-ultra-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Razr 40 Ultra</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-learn-to-convert-your-vids-into-music-on-instagram-today/"><u>[Updated] 2024 Approved  Learn to Convert Your Vids Into Music on Instagram Today</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-elite-streamers-guide-for-secure-viewing-for-2024/"><u>[Updated] Elite Streamer’s Guide for Secure Viewing for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-motorola-moto-g23-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Motorola Moto G23 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-chart-wolfs-sonorous-call-pattern/"><u>Updated Chart Wolfs Sonorous Call Pattern</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-how-to-use-the-blending-modes-to-composite-clips/"><u>2024 Approved  How to Use The Blending Modes To Composite Clips</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-harmonizing-sights-with-itunes-acoustics/"><u>[New] In 2024, Harmonizing Sights with iTunes Acoustics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-exclusive-list-of-8-best-apps-to-enhance-facebook-likes-for-2024/"><u>[New] Exclusive List of 8 Best Apps To Enhance Facebook Likes for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-applications-of-virtual-reality/"><u>2024 Approved  Applications of Virtual Reality</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-youtube-video-edits-with-imovie-a-step-by-step-guide/"><u>In 2024, Mastering YouTube Video Edits with iMovie  A Step-by-Step Guide</u></a></li>
</ul></div>
