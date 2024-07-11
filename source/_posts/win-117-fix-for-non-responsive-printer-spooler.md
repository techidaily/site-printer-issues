---
title: Win 11/7 Fix for Non-Responsive Printer Spooler
date: 2024-07-10T17:37:52.732Z
updated: 2024-07-11T17:37:52.732Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Win 11/7 Fix for Non-Responsive Printer Spooler
excerpt: This Article Describes Win 11/7 Fix for Non-Responsive Printer Spooler
keywords: Win 11 Troubleshooting Guide,Printer Spooler Fix,Non-Responsive Printer Issues,Windows 11/7 Spooler Error,Fix Non-Responsive Printer,Resolve Windows 11/7 Printer Spooler Problems,How To Fix Non-Responsive Printer Spooler (Step by Step)
thumbnail: https://thmb.techidaily.com/d9427c61032284cb88ab156d6c103f9d31f7d2686f689f4e79141572fa04ae5d.jpg
---

## Win 11/7 Fix for Non-Responsive Printer Spooler

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
<li><a href="https://printer-issues.techidaily.com/revived-networked-printer-access/"><u>Revived Networked Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-compatible-driver-release/"><u>Officejet Pro 8600 Windows Compatible Driver Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-duplicate-documents-in-w11-printer-spool/"><u>Resolve Duplicate Documents in W11 Printer Spool</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-debugged-successfully/"><u>Code B200 Debugged Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-after-wake-from-sleep-in-windows-7/"><u>[Resolved] Printer Error After Wake From Sleep in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-paper-jams-and-misprints-on-windows-10/"><u>Resolve Paper Jams & Misprints on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-printer-problem-5-quick-steps-to-enable-print-on-canon-and-windows-11-combo/"><u>Resolve Printer Problem: 5 Quick Steps to Enable Print on Canon & Windows 11 Combo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-removal-from-printer-job-backlog/"><u>Rapid Removal From Printer Job Backlog</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-revolutionary-fix-for-frustrating-printers/"><u>The Revolutionary Fix for Frustrating Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-blueprint-hp-officejet-pro-in-personal-computer/"><u>Installation Blueprint: HP OfficeJet Pro in Personal Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-installation-for-new-printer-model/"><u>Resolved Installation for New Printer Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-tangle-printer-reconfigured-incorrectly/"><u>Technical Tangle: Printer Reconfigured Incorrectly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-errors-resolving-them-in-windows-11/"><u>Printer Errors: Resolving Them in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-my-printer-skips-colors/"><u>Why My Printer Skips Colors?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-and-connecting-your-canon-printer/"><u>Efficiently Setting Up and Connecting Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-network-printer-how-to-find-it-on-your-os/"><u>Hidden Network Printer: How to Find It on Your OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-unnecessary-printers-in-os/"><u>Purging Unnecessary Printers in OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-printer-from-jamming-in-windows-11/"><u>Stop Your Printer From Jamming in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canons-error-b200/"><u>Fixed Canon's Error: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connectivity-win1110-cant-find-hp-driver/"><u>[Printer Connectivity] Win11/10 Can't Find HP Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-printing-glitch-error-0x00000709-resolved/"><u>Fixed the Printing Glitch - Error 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-flat-out-print-fiasco-windows-error-0x00000709-resolved/"><u>Fixing Flat-Out Print Fiasco: Windows Error 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-issue/"><u>Mended Printer Network Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-when-print-devices-go-offline/"><u>Connectivity Woes: When Print Devices Go Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-jam-no-more-epson-printer-fixed/"><u>Paper Jam No More: Epson Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-error-unresponsive-on-win7-restart/"><u>USB Printer Error: Unresponsive on Win7 Restart</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstated-default-printer-on-winerror-0x00000709/"><u>Reinstated Default Printer on WinError (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-seamless-transition-update-mf4770n-on-w11win8w7/"><u>Achieve Seamless Transition: Update MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-paper-shortage-2024-printer-update/"><u>Ending Paper Shortage: 2024 Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-non-responsive-printers/"><u>Reviving Non-Responsive Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-missing-printers-from-the-network/"><u>Troubleshooting Missing Printers From the Network</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-virtual-verification-a-new-look-at-app-quality-for-2024/"><u>[New] Virtual Verification  A New Look at App Quality for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-eclectic-compilation-of-irresistible-youtube-sounds/"><u>2024 Approved Eclectic Compilation of Irresistible YouTube Sounds</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-12-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 12 Device from iCloud</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-the-art-of-engaging-viral-tiktok-reaction-videos-for-2024/"><u>Mastering the Art of Engaging Viral TikTok Reaction Videos for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-vivo-y100-5g-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Vivo Y100 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximizing-engagement-10-tips-for-stellar-yt-shorts-content/"><u>[Updated] Maximizing Engagement  10 Tips for Stellar YT Shorts Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-expert-windows-and-macos-screen-capture-tools/"><u>[New] In 2024, Expert Windows & macOS Screen Capture Tools</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-unblocking-tiktok/"><u>[Updated] 2024 Approved  Mastering the Art of Unblocking TikTok</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-enable-silence-mode-and-incorporate-custom-tracks-via-windows-movie-maker/"><u>2024 Approved Enable Silence Mode & Incorporate Custom Tracks via Windows Movie Maker</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-boost-creativity-with-free-audio-effects-online/"><u>[Updated] In 2024, Boost Creativity with Free Audio Effects Online</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-shaping-tomorrow-celebrating-the-top-6-in-nft-artistry/"><u>[New] Shaping Tomorrow  Celebrating the Top 6 in NFT Artistry</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-microscope-effect-for-enhanced-video-conferencing/"><u>In 2024, Mastering the Microscope Effect for Enhanced Video Conferencing</u></a></li>
<li><a href="https://games-able.techidaily.com/slimmer-smartphones-tecnos-exciting-showcase/"><u>Slimmer Smartphones: Tecno’s Exciting Showcase</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-pcmacs-leading-game-recording-apps-ranked-15plus/"><u>[New] 2024 Approved  PC/Mac's Leading Game Recording Apps Ranked #15+</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-a-video-slideshow-in-imovie-for-2024/"><u>How to Create a Video Slideshow in iMovie for 2024</u></a></li>
</ul></div>
