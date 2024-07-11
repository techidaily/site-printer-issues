---
title: Unblocking Printer Service on Windows 10, 11, 7
date: 2024-07-10T17:28:32.224Z
updated: 2024-07-11T17:28:32.224Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unblocking Printer Service on Windows 10, 11, 7
excerpt: This Article Describes Unblocking Printer Service on Windows 10, 11, 7
keywords: Windows Unblock Printer Service,Printer Service Troubleshooting in Windows,Windows 10 Printer Service Fixes,Windows 11 Unblock Printer Service,Unblocking Printer Service on PC,Windows Printing Issues Guide,How To Unblock Printer Service in Windows
thumbnail: https://thmb.techidaily.com/11dcf4b0c6e46020efb7e29f6284c6b2311802a84bad6c07d2660d7d7c1f1386.jpg
---

## Unblocking Printer Service on Windows 10, 11, 7

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
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wizard-disconnecting-all-printers/"><u>Windows Wizard: Disconnecting All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-10-printer-software/"><u>Troubleshoot Windows 10 Printer Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnected-disabled-printer-service/"><u>Reconnected Disabled PRINTER Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-paper-jams-swiftly/"><u>Clearing Paper Jams Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-restoration-of-active-print-queue/"><u>Quick Restoration of Active Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-epsons-error-x97/"><u>Fixing Epson's Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-eliminated-post-windows-revamp/"><u>Print Issue Eliminated Post Windows Revamp</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-interruptions-on-win7win10/"><u>Avoiding Constant Printer Service Interruptions on Win7/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-laser-troubleshooting/"><u>Streamlining Laser Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-all-pages-now-available/"><u>Perfect Print: All Pages Now Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dell-inkjet-errors-immediately/"><u>Fixing Dell Inkjet Errors Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-established-printer-connections/"><u>Success: Established Printer Connections</u></a></li>
<li><a href="https://printer-issues.techidaily.com/full-colors-unavailable-on-printout/"><u>Full Colors Unavailable on Printout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-phantom-error-messages-on-printers/"><u>Repairing Phantom Error Messages on Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-your-printing-experience-with-canon-windows-10-tips/"><u>Enhance Your Printing Experience with Canon, Windows 10 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-no-0x97-resolved/"><u>Epson Fault No: 0X97 - Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-error-correction/"><u>Mastering Printer Error Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-restored-scan-operation/"><u>Windows 11: Restored Scan Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-right-hp-d1360-print-drivers-in-windows-ecosystems/"><u>Finding the Right HP D1360 Print Drivers in Windows Ecosystems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-leveraging-high-roi-crafting-dynamic-animated-ads-for-fb/"><u>[New] Leveraging High ROI  Crafting Dynamic Animated Ads for FB</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-rotate-your-videos-without-cost-top-10-free-video-flipper-software/"><u>Updated Rotate Your Videos Without Cost Top 10 Free Video Flipper Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-revolutionize-your-virtual-engagements-with-advanced-google-meet-customization-for-2024/"><u>[Updated] Revolutionize Your Virtual Engagements with Advanced Google Meet Customization for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-vivo-v27-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Vivo V27 Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leading-edits-from-image-to-engrossing-video-journey/"><u>In 2024, Leading Edits  From Image to Engrossing Video Journey</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebook-hack-get-your-account-back/"><u>Facebook Hack? Get Your Account Back</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-approach-what-to-evaluate-before-purchasing-a-handheld-game-console/"><u>A Step-by-Step Approach: What to Evaluate Before Purchasing a Handheld Game Console</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-instant-access-to-12-high-quality-livestreams/"><u>2024 Approved  Instant Access to 12 High-Quality Livestreams</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-iphone-8-plus-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For iPhone 8 Plus?</u></a></li>
<li><a href="https://howto.techidaily.com/reliable-user-guide-to-fix-realme-12-proplus-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Realme 12 Pro+ 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-multiangle-exploration-guide-for-2024/"><u>[Updated] MultiAngle Exploration Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-download-instagram-highlights-in-2-ways-in-2024/"><u>[Updated] How to Download Instagram Highlights in 2 Ways, In 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-easy-setup-making-a-direct-path-for-youtube-subscribers/"><u>[New] 2024 Approved  Easy Setup  Making a Direct Path for YouTube Subscribers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-revolutionary-alternative-tools-for-fbx-file-capture/"><u>[New] In 2024, Revolutionary Alternative Tools for FBX File Capture</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastery-in-purchasing-pristine-stock-images/"><u>[Updated] Mastery in Purchasing Pristine Stock Images</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oppo-find-x7-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Oppo Find X7 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-transform-your-videos-with-slow-motion-on-kapwing-a-beginner-friendly-guide/"><u>Updated Transform Your Videos with Slow Motion on Kapwing A Beginner-Friendly Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-digital-arena-100plus-titles-for-the-true-gamer-for-2024/"><u>[New] Digital Arena  100+ Titles for the True Gamer for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-vivo-v29-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Vivo V29 to iPhone (13/14/15) | Dr.fone</u></a></li>
</ul></div>
