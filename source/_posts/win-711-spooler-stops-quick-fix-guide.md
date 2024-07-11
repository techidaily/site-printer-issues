---
title: "Win 7/11 Spooler Stops: Quick Fix Guide"
date: 2024-07-10T17:43:33.619Z
updated: 2024-07-11T17:43:33.619Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Win 7/11 Spooler Stops: Quick Fix Guide"
excerpt: "This Article Describes Win 7/11 Spooler Stops: Quick Fix Guide"
keywords: Win XP/Vista Spooler Stops,Windows 7/8.1 Spooler Troubleshooting,Quick Fix Guide for Spooler Issue,Stop Windows System Error (Win 7),Remedying Spooler Crashes in Windows Operating Systems,Solutions to Resolve Spooler Stops in Win XP/Vista,Optimize Spooler Performance on Windows OS
thumbnail: https://thmb.techidaily.com/ef64597bda93820e24d8ab2d0a8cbf446e80301b9ceb1303c686c48229c6eca3.jpg
---

## Win 7/11 Spooler Stops: Quick Fix Guide

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
<li><a href="https://printer-issues.techidaily.com/from-unboxed-to-printed-the-complete-win-hp-printer-guidebook/"><u>From Unboxed to Printed: The Complete Win HP Printer Guidebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-epsons-error-0x97-maze/"><u>Navigating Epson's Error 0X97 Maze</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-operational-efficiency-with-mf4770n-on-w11w8w7-windows/"><u>Boost Operational Efficiency with MF4770n on W11/W8/W7 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanned-device-functionality-in-windows-10/"><u>Enable Scanned Device Functionality in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-output-v305-aio-driver-enhancement-in-win7/"><u>Boost Your Output: V305 AIO Driver Enhancement in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-page-failure-resolved/"><u>HP Printer: Page Failure Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-hp-printer-oxc4eb827f-fatality-problem/"><u>Solving HP Printer OXC4EB827F Fatality Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-online-functionality-regained/"><u>Epson Online Functionality Regained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanned-device-connection-issue-on-win10/"><u>Fixing Scanned Device Connection Issue on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-print-no-hassle-method/"><u>Reconnect Print: No Hassle Method</u></a></li>
<li><a href="https://printer-issues.techidaily.com/nozzle-clog-in-hp-printer-cleared-successfully/"><u>Nozzle Clog in HP Printer Cleared Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-inkjet-printer-unresponsive/"><u>Post Upgrade, Inkjet Printer Unresponsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win107-troubleshooting-steps-to-address-spooler-failures/"><u>Win10/7 Troubleshooting Steps to Address Spooler Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-errors-windows-10-solutions/"><u>Overcome Print Errors: Windows 10 Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-issue-hp-not-found-for-windows-os/"><u>Driver Issue: HP Not Found for Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-issue-canon-pixma-mp620-unsupported-by-win10/"><u>[Driver Issue] Canon Pixma MP620 Unsupported by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-on-latest-win10-os/"><u>Reactivating Scanner on Latest Win10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-117-solved/"><u>HP Printer Offline Status on Windows 11/7 [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-plug-in-for-print-devices/"><u>Immediate Plug-In for Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-hp-printer-driver-not-in-windows-os/"><u>Hardware Setup: HP Printer Driver Not in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-fix-windows-810-printer-missing-issue/"><u>[Network Fix] Windows 8/10 Printer Missing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-the-printer-after-updating-woes/"><u>Triumph over the Printer After Updating Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dont-let-offline-be-the-end-for-your-canon-printer/"><u>Don’t Let Offline Be the End for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-recognized-missing-hp-drivers-on-win1011/"><u>Printer Not Recognized: Missing HP Drivers on Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-connection-routes-between-hp-printers-and-laptops/"><u>Enhanced Connection Routes Between HP Printers and Laptops</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-mastering-pip-navigating-netflixs-floating-screen-functionality/"><u>[Updated] Mastering PIP  Navigating Netflix's Floating Screen Functionality</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-apply-video-filters-mobile-and-desktop-for-2024/"><u>Updated How to Apply Video Filters Mobile and Desktop for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-to-mp4-for-redmi-note-12r-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD MTS to MP4 for Redmi Note 12R?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-decoding-youtubes-legal-framework-for-video-creators/"><u>[New] Decoding YouTube's Legal Framework for Video Creators</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-unshakeable-footage-a-beginners-guide-to-video-stabi/"><u>Updated Unshakeable Footage A Beginners Guide to Video Stabi</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-editing-competitors-ranked-top-5-non-youtube-sites-list/"><u>2024 Approved  YouTube Editing Competitors Ranked  Top 5 Non-YouTube Sites List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-audio-alchemy-free-perfectly-crafted-dj-template-videos/"><u>[New] Audio Alchemy  Free, Perfectly Crafted DJ Template Videos</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-countdown-magic-in-fcpx-a-3-step-tutorial-for-beginners-for-2024/"><u>New Countdown Magic in FCPX A 3-Step Tutorial for Beginners for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-enhancing-iphone-image-clarity-and-focus/"><u>[New] Enhancing iPhone Image Clarity and Focus</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/selecting-the-top-5-youtube-grabber-software-for-2024/"><u>Selecting the Top 5 YouTube Grabber Software for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-tier-psd-artistry-tweaks/"><u>[New] Top-Tier PSD Artistry Tweaks</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-craft-engaging-videos-insights-into-youtube-movie-maker/"><u>[New] 2024 Approved  Craft Engaging Videos  Insights Into YouTube Movie Maker</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-picture-pieces-proposals-radiate-positivity-and-creativity/"><u>[Updated] Picture Pieces Proposals  Radiate Positivity and Creativity</u></a></li>
</ul></div>
