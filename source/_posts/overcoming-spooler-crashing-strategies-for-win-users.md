---
title: "Overcoming Spooler Crashing: Strategies for Win Users"
date: 2024-07-10T17:12:55.984Z
updated: 2024-07-11T17:12:55.984Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Overcoming Spooler Crashing: Strategies for Win Users"
excerpt: "This Article Describes Overcoming Spooler Crashing: Strategies for Win Users"
keywords: Overcoming Spooler Crashes,Strategies for Win Users,Spooler Crash Fixes,Stop Windows Spooler Errors,Win User Spooler Troubleshooting,How to Resolve Spooler Crashes,Preventing Spooler Crashes in Win OS
thumbnail: https://thmb.techidaily.com/f1f88a30ef6a6045fdd8de1ae1bff22298ec89fff91a1dcd9baaedda62548cb2.jpg
---

## Overcoming Spooler Crashing: Strategies for Win Users

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
<li><a href="https://printer-issues.techidaily.com/1719574154094-no-more-unprinted-pages-on-hp-printer-now/"><u>No More Unprinted Pages on HP Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-compatibility-windows-11-and-canons-mp620/"><u>Printer Compatibility: Windows 11 and Canon's MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-print-process-uncover-these-simple-steps-for-non-printing-canon-on-windows-11/"><u>Streamline Print Process: Uncover These Simple Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-error-code-oxc4eb827f/"><u>Overcoming HP Printer Error Code: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-printing-malfunction-detected/"><u>Color Printing Malfunction Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024s-guide-to-perfectly-pairing-hp-printer-with-laptops/"><u>2024'S Guide to Perfectly Pairing HP Printer with Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cure-non-engagement-in-older-windows-versions-printers/"><u>Cure Non-Engagement in Older Windows Versions' Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-intermittent-print-service-disruptions-in-win-oss/"><u>Fixing Intermittent Print Service Disruptions in Win OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wins-overprint-taming-the-post-update-beast/"><u>Wins Overprint: Taming the Post-Update Beast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-issue-unable-to-get-hp-d1360-up-and-running-in-windows-8-10/"><u>[Installation Issue] Unable to Get HP D1360 Up and Running in Windows 8-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-10/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unknown-computer-known-printer-case-closed/"><u>Unknown Computer, Known Printer - Case Closed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-problem-resolved/"><u>B200: Problem Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-wireless-setup-guide-for-brother-fans/"><u>MFC-9330 Wireless Setup Guide for Brother Fans</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-issue/"><u>Mended Printer Network Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-fixing-unable-to-add-hp-d1360-drivers-in-windows-oses/"><u>[Error Fixing] Unable to Add HP D1360 Drivers in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-installation-guide-for-windows/"><u>HP Printer Installation Guide for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/five-easy-ways-to-make-your-canon-printer-start-printing-again-in-windows-11/"><u>Five Easy Ways to Make Your Canon Printer Start Printing Again in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printer-output-5-effective-steps-for-non-printing-canon-on-windows-11/"><u>Reignite Printer Output: 5 Effective Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-driven-print-screws/"><u>Unblocking Driven Print Screws</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-ensuring-smooth-streaming-solutions-for-fb-livestream-problems/"><u>[Updated] Ensuring Smooth Streaming  Solutions for FB Livestream Problems</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagram-filter-application-guide-tips-and-tricks/"><u>[New] 2024 Approved  Instagram Filter Application Guide - Tips & Tricks</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-top-iphones-video-editors-face-off-cameo-vs-filmorago/"><u>[Updated] In 2024, Top iPhones' Video Editors Face-Off  Cameo Vs. FilmoraGo</u></a></li>
<li><a href="https://extra-skills.techidaily.com/iphoneandroid-stabilization-elite-photo-tripods-for-2024/"><u>IPhone/Android Stabilization  Elite Photo Tripods for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-12-pro-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-psd-shadow-gradient-for-2024/"><u>Ultimate PSD Shadow Gradient for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-v30-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo V30 Pro</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/accelerate-your-videos-a-quicktime-player-guide-for-windows-and-mac/"><u>Accelerate Your Videos A QuickTime Player Guide for Windows and Mac</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/optimize-your-streaming-quality-with-these-top-4-video-boosters/"><u>Optimize Your Streaming Quality with These Top 4 Video Boosters</u></a></li>
<li><a href="https://screen-recording.techidaily.com/elevate-your-farming-adventures-with-stardews-top-7-mods/"><u>Elevate Your Farming Adventures with Stardew's Top 7 Mods</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-elevating-your-presence-on-tiktok-essential-7-must-haves-for-2024/"><u>[Updated] Elevating Your Presence on TikTok  Essential 7 Must-Haves for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-instantpause-live-video-cutout-tips/"><u>[Updated] InstantPause  Live Video Cutout Tips</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-best-budget-video-players-across-operating-systems/"><u>In 2024, The Best Budget Video Players Across Operating Systems</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-critical-platforms-offering-twitter-like-interaction/"><u>[Updated] In 2024, Critical Platforms Offering Twitter-Like Interaction</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-motorola-moto-g34-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-assessing-inshots-superiority-in-the-editing-arena/"><u>[Updated] Assessing InShot's Superiority in the Editing Arena</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-dynamic-unpriced-visual-bonding-games/"><u>[New] 2024 Approved  Dynamic Unpriced Visual Bonding Games</u></a></li>
<li><a href="https://techidaily.com/solved-microsoft-excel-2000-file-error-the-document-cannot-be-saved-by-stellar-guide/"><u>Solved Microsoft Excel 2000 File Error The document cannot be saved</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-convert-like-a-pro-tips-tricks-and-reviews-of-youtube-to-mp3-tools/"><u>2024 Approved Convert Like a Pro Tips, Tricks, and Reviews of YouTube to MP3 Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-pair-monitor-logging-process/"><u>[Updated] In 2024, Pair Monitor Logging Process</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-battle-of-bros-hero5-black-and-virb-ultra-face-off/"><u>In 2024, Battle of Bros  Hero5 Black & VIRB Ultra Face Off</u></a></li>
</ul></div>
