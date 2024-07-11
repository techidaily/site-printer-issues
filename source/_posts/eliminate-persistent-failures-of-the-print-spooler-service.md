---
title: Eliminate Persistent Failures of the Print Spooler Service
date: 2024-07-10T16:51:39.113Z
updated: 2024-07-11T16:51:39.113Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Eliminate Persistent Failures of the Print Spooler Service
excerpt: This Article Describes Eliminate Persistent Failures of the Print Spooler Service
keywords: Print Spooler Service Failure,Stop Printer Print Queue Error,Spooler Service Troubleshooting,Print Spooler Recovery Steps,Preventing Print Spooler Crashes,Print Server Management Tips,Spooler Service Update Guidelines
thumbnail: https://thmb.techidaily.com/a84f233e2df716933c1def7036ee5f60e5a298fe75b79753bbc6bfd2f6d9a6e5.jpg
---

## Eliminate Persistent Failures of the Print Spooler Service

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
<li><a href="https://printer-issues.techidaily.com/solutions-for-halted-hp-print-operations/"><u>Solutions for Halted HP Print Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-saturation-dropped-in-prints/"><u>Color Saturation Dropped in Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-searching-for-missing-windows-driver/"><u>MP620 Printer: Searching for Missing Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-outputs-ceased-on-epson-model/"><u>Halted Outputs Ceased on Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-out-of-service/"><u>Fixed Epson Out Of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-duplicate-documents-in-w11-printer-spool/"><u>Resolve Duplicate Documents in W11 Printer Spool</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-0x97-unravelled-and-solved/"><u>Epson 0X97 - Unravelled & Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-hp-d1360-drivers-success-on-windows-versions/"><u>Installing HP D1360 Drivers: Success on Windows Versions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alert-windows-10-print-queue-offline/"><u>[ALERT] Windows 10: Print Queue Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574058416-5-easy-ways-to-fix-canon-printer-wont-print-in-windows-10/"><u>5 Easy Ways to Fix Canon Printer Won’t Print in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-unfreeze-an-offline-brother-printer-online/"><u>How To Unfreeze an Offline Brother Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/squashing-hp-printers-mistake-oxc4eb827f/"><u>Squashing HP Printer's Mistake: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-empty-pages-a-printers-success-story/"><u>Eliminating Empty Pages: A Printer's Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-cure-printer-blank-screens/"><u>Guidelines to Cure Printer Blank Screens</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-performance-with-new-hp-officejet-driver/"><u>Optimize Performance with New HP Officejet Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-reports-with-paper-less-prints/"><u>Revolutionizing Reports with Paper-Less Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-no-access-to-printer-drivers/"><u>Windows: No Access to Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expedite-jammed-print-queue/"><u>Expedite Jammed Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigate-and-rectify-brother-printer-not-print-issue-on-windows-10/"><u>Navigate and Rectify Brother Printer Not Print Issue on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-restore-printer-functionality/"><u>Steps to Restore Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unify-mf4770n-with-windows-environment-in-win11win87/"><u>Unify MF4770n with Windows Environment in Win11/Win8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-path-perfection-error-0x0-cooked-in-windows-fix/"><u>Paper Path Perfection - Error 0X0 Cooked in Windows Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winning-against-the-new-windows-printing-issue/"><u>Winning Against the New Windows Printing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-inkjet-non-operational/"><u>Repaired Inkjet Non-Operational</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mastering-your-influence-amidst-changing-social-media-ecosystem-for-2024/"><u>[Updated] Mastering Your Influence Amidst Changing Social Media Ecosystem for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-integrating-smooth-crossfades-into-your-sound-design/"><u>In 2024, Integrating Smooth Crossfades Into Your Sound Design</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-restoring-sound-linkage-in-obs-broadcasts-for-2024/"><u>[Updated] Restoring Sound Linkage in OBS Broadcasts for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-best-bites-in-a-byte-top-tiktok-foodies/"><u>In 2024, Best Bites in a Byte  Top TikTok Foodies</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-6-best-movie-intro-maker-to-custom-your-intro-videos/"><u>Updated 6 Best Movie Intro Maker to Custom Your Intro Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-renowned-makers-exquisite-insta-hlv-designers-online/"><u>[Updated] In 2024, Renowned Makers  Exquisite Insta HLV Designers Online</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-mealtime-magnates-on-tiktok-platform/"><u>[Updated] In 2024, Mealtime Magnates on TikTok Platform</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-new-windows-11-insiders-edge-techniques/"><u>[New] New Windows 11 Insider's Edge Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/complete-tiktok-termination-protocol-unveiled-for-2024/"><u>Complete TikTok Termination Protocol Unveiled for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-enhancing-imagery-a-step-by-step-guide-to-crop-videos-on-instagram/"><u>[New] In 2024, Enhancing Imagery  A Step-by-Step Guide to Crop Videos on Instagram</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-overlooked-masterpieces-unique-free-speech-to-text-apps-for-mac/"><u>In 2024, Overlooked Masterpieces  Unique Free Speech-to-Text Apps for Mac</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-instructions-turn-on-windows-11s-adaptive-hdr/"><u>[Updated] Instructions  Turn on Windows 11'S Adaptive HDR</u></a></li>
</ul></div>
