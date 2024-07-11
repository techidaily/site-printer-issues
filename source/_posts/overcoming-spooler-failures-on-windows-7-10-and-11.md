---
title: Overcoming Spooler Failures on Windows 7, 10 & 11
date: 2024-07-10T17:48:38.512Z
updated: 2024-07-11T17:48:38.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Overcoming Spooler Failures on Windows 7, 10 & 11
excerpt: This Article Describes Overcoming Spooler Failures on Windows 7, 10 & 11
keywords: Spooler Failure Solution,Windows 7 Spooler Troubleshooting,Spooler Errors on Windows 10,Overcoming Print Service Manager Issues,Spooler Troubleshooting Guide for Windows,Troubleshoot Spooler Failure in Windows,Preventing Print Service Manager Errors
thumbnail: https://thmb.techidaily.com/79f38eb573cc99e5f54bf7180a8b2f400aa646add73d8ccbbc068b9cd2192911.jpg
---

## Overcoming Spooler Failures on Windows 7, 10 & 11

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
<li><a href="https://printer-issues.techidaily.com/celebrating-clear-documentation-with-every-page/"><u>Celebrating Clear Documentation with Every Page</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-jammed-printers/"><u>Unlocking Jammed Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-xp-vs-mp620-printer-compatibility-questions/"><u>Windows XP vs MP620 Printer Compatibility Questions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-unresponsive-xp-printer-jobs-without-delay/"><u>Fix Unresponsive XP Printer Jobs Without Delay</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domain-disabled-resulting-in-print-errors/"><u>Domain Disabled: Resulting in Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-successful-driver-installation-for-hp-d1360/"><u>Hardware Setup: Successful Driver Installation for HP D1360?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-hp-printers-error-0xoxc4eb827f/"><u>Disabling HP Printer's Error 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-hibernate-usb-print-issues-on-windows-7-devices/"><u>Post-Hibernate USB Print Issues on Windows 7 Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-clearing-print-job-queue/"><u>Accelerate Clearing Print Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-output-issue-on-printer/"><u>Color Output Issue on Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-no-longer-exists/"><u>Error B200 No Longer Exists</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-missing-mp620-printer-unresponsive-in-win11/"><u>Driver Missing: MP620 Printer Unresponsive in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-page-problem-persists-on-new-epson-printer-model/"><u>Blank Page Problem Persists on New Epson Printer Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brew-the-latest-printer-driver-potion-in-windows-7/"><u>Brew the Latest Printer Driver Potion in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-brother-printer-printing-obstructions-in-windows/"><u>Overcoming Brother Printer Printing Obstructions in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-print-job-failures-on-windows-11/"><u>Rectify Print Job Failures on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-paperless-print-error-rectified/"><u>Post-Upgrade, Paperless Print Error Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-printer-malfunction-code-0x97/"><u>Mending Printer Malfunction: Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/healed-printer-communication-link/"><u>Healed Printer Communication Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-fixes-for-epson-error-0x97/"><u>Mastering Fixes for Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-all-pages-now-available/"><u>Perfect Print: All Pages Now Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/all-page-printer-issues-resolved/"><u>All-Page Printer Issues Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solidify-printing-integrity-fixing-issues-on-win10/"><u>Solidify Printing Integrity, Fixing Issues on Win10</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/restoring-macos-sierra-to-os-x-10101-environment-for-2024/"><u>Restoring MacOS Sierra to OS X 10.10.1 Environment for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimal-series-professional-webcam-stabilizers/"><u>2024 Approved  Optimal Series  Professional Webcam Stabilizers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-enhance-your-video-meetings-with-snap-shots-on-zoom/"><u>In 2024, Enhance Your Video Meetings with Snap Shots on Zoom</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-apple-iphone-6s-plus-by-drfone-ios/"><u>How to Fix Locked Apple ID on Apple iPhone 6s Plus</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-on-the-iphone-13-mini-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock On the iPhone 13 mini Without Previous Owner?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/igniting-the-fires-of-engagement-with-viral-instagram-videos-for-2024/"><u>Igniting the Fires of Engagement with Viral Instagram Videos for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ng-edge-design-top-5-3d-intro-makers/"><u>Cutting-Edge Design  Top 5 3D Intro Makers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-broadcast-your-google-meet-directly-to-youtubes-stage/"><u>[New] 2024 Approved  Broadcast Your Google Meet Directly to YouTube's Stage</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-zte-nubia-z60-ultra-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to ZTE Nubia Z60 Ultra FRP Bypass With Best Methods</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-honor-play-40c-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Honor Play 40C</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-ignite-your-artistic-spirit-find-the-premier-android-drawing-tools/"><u>[New] 2024 Approved  Ignite Your Artistic Spirit  Find the Premier Android Drawing Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/green-up-your-cta-game-subscribe-and-screen-for-2024/"><u>Green Up Your CTA Game  Subscribe & Screen for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-itel-p40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Itel P40 | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-complete-guide-to-mp3-customization-from-editing-basics-to-professional-touches-for-2024/"><u>The Complete Guide to MP3 Customization From Editing Basics to Professional Touches for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-supercharge-your-yi-4k-videos-with-pro-gear-for-2024/"><u>[New] Supercharge Your YI 4K Videos with Pro Gear for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-sony-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Sony FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-s-top-rated-free-wmv-video-concatenation-software/"><u>In 2024, S Top-Rated Free WMV Video Concatenation Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-realme-narzo-60-pro-5g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Realme Narzo 60 Pro 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-step-by-step-journey-of-becoming-an-ez-grabber-user/"><u>[New] In 2024, The Step-By Step Journey of Becoming an EZ Grabber User</u></a></li>
</ul></div>
