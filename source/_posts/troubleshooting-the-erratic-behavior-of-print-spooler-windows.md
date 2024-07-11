---
title: Troubleshooting the Erratic Behavior of Print Spooler (Windows)
date: 2024-07-10T17:22:48.899Z
updated: 2024-07-11T17:22:48.899Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Troubleshooting the Erratic Behavior of Print Spooler (Windows)
excerpt: This Article Describes Troubleshooting the Erratic Behavior of Print Spooler (Windows)
keywords: Print Spooler Errors,Windows Print Service Troubleshoot,Print Spooler Troubleshooting Guide,Windows Print Service Error Fixes,Spooler Management Tips,Resolving Print Spooler Glitches,Optimizing Windows Print Service Performance
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

## Troubleshooting the Erratic Behavior of Print Spooler (Windows)

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
<li><a href="https://printer-issues.techidaily.com/rapid-fixation-of-stuck-print-workqueue/"><u>Rapid Fixation of Stuck Print Workqueue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-phantom-error-messages-on-printers/"><u>Repairing Phantom Error Messages on Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-windows-setup-for-your-new-hp-device/"><u>Navigating Through Windows Setup for Your New HP Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-for-restoring-hp-print-functionality/"><u>Tips for Restoring HP Print Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-resolving-non-printing-issues/"><u>Troubleshooting: Resolving Non-Printing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-the-whiteout-from-our-print-sources/"><u>Banishing the Whiteout From Our Print Sources</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-unprintable-to-perfect-hp-printers-recovery-story/"><u>From Unprintable to Perfect: HP Printer's Recovery Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-guide-reconnect-missing-print-devices-windows-xp-7-10/"><u>[Network Guide] Reconnect Missing Print Devices Windows-XP-7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-blank-page-problem-solved/"><u>HP Printer Blank Page Problem Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-recognized-missing-hp-drivers-on-win1011/"><u>Printer Not Recognized: Missing HP Drivers on Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-back-life-to-dead-printer/"><u>Bringing Back Life to Dead Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/search-for-printer-device-failed-on-pc-os/"><u>Search for Printer Device Failed on PC OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-mystery-printer-works-after-win-10-patch/"><u>Unraveling the Mystery: Printer Works After Win 10 Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-hp-printers-blank-sheet-mystery/"><u>Clearing Up HP Printer's Blank Sheet Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setback-configuration-conundrum/"><u>Print Setback: Configuration Conundrum</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-active-directory-domain-services-is-currently-unavailable-printer-error/"><u>Fixed: The Active Directory Domain Services Is Currently Unavailable Printer Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-tip-revive-missing-windows-xp10-printer/"><u>[Tech Tip] Revive Missing Windows XP/10 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574127184-printers-wont-print-all-pages-2024-fix/"><u>Printers Won’t Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-driver-suite-for-windows-enhancement/"><u>HP Officejet Pro 8600 Driver Suite for Windows Enhancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-hibernate-usb-print-issues-on-windows-7-devices/"><u>Post-Hibernate USB Print Issues on Windows 7 Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-successful-driver-installation-for-hp-d1360/"><u>Hardware Setup: Successful Driver Installation for HP D1360?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/high-performance-drivers-hp-officejet-pro-8600-for-windows-pcs/"><u>High-Performance Drivers: HP Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-printer-paper-jams-and-errors/"><u>Overcoming Printer Paper Jams and Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-status-online-on-windows-11/"><u>HP OfficeJet Status: Online on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-scanner-error-cleared-in-win11/"><u>Disabling Scanner Error Cleared in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-hang-up-swiftly/"><u>Resolve Print Hang-Up Swiftly</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-enhancing-communication-adding-emojis-to-disco-statuses/"><u>[Updated] Enhancing Communication  Adding Emojis to Disco Statuses</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-leading-selection-no-cost-outstanding-lut-links-for-2024/"><u>The Leading Selection  No-Cost, Outstanding LUT Links for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-breaking-down-barriers-to-inaccessible-youtube-content/"><u>[New] 2024 Approved  Breaking Down Barriers to Inaccessible YouTube Content</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-infinix-smart-8-pro-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Infinix Smart 8 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instant-drive-shedding-guide-for-graphics-removal/"><u>Instant Drive Shedding - Guide for Graphics Removal</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/audience-growth-secrets-top-50plus-tiktok-hashtags/"><u>Audience Growth Secrets  Top 50+ TikTok HashTags</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-get-creative-with-ubuntu-10-free-video-editing-tools-to-explore/"><u>In 2024, Get Creative with Ubuntu 10 Free Video Editing Tools to Explore</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-evaluating-every-aspect-of-du-recorder-design-and-function/"><u>In 2024, Evaluating Every Aspect of Du Recorder Design & Function</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-vivo-v29e-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Vivo V29e.</u></a></li>
<li><a href="https://audio-editing.techidaily.com/professional-audio-editing-essentials-voice-suppression-and-video-quality-improvement-for-2024/"><u>Professional Audio Editing Essentials Voice Suppression and Video Quality Improvement for 2024</u></a></li>
</ul></div>
