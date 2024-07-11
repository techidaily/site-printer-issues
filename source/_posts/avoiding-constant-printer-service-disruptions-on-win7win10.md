---
title: Avoiding Constant Printer Service Disruptions on Win7/Win10
date: 2024-07-10T17:36:12.657Z
updated: 2024-07-11T17:36:12.657Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Avoiding Constant Printer Service Disruptions on Win7/Win10
excerpt: This Article Describes Avoiding Constant Printer Service Disruptions on Win7/Win10
keywords: Printer Service Disruption,Windows 7 Printer Issues,Printer Troubleshooting for Win7/Win10,Printing Errors on Windows 10,Prevent Printer Downtime in Win7/Win10,Troubleshoot Constant Windows 7/10 Print Failures,Best Practices to Avoid Win7/Win10 Printer Issues
thumbnail: https://thmb.techidaily.com/0770f30dd9bee193a5501427eba7dec20121fd86c94f50442733727b65ca9aad.jpg
---

## Avoiding Constant Printer Service Disruptions on Win7/Win10

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
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-ultimate-guide-to-installing-and-configuring-hp-printers/"><u>The Ultimate Guide to Installing and Configuring HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-sheetless-anxiety-to-confident-printing/"><u>From Sheetless Anxiety to Confident Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-printer-halt-after-update-successfully/"><u>Resolving Printer Halt After Update Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-in-effect-for-b200/"><u>Fix In Effect for B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-engage-withprinter-online-troubleshooting-steps/"><u>Re-Engage Withprinter: Online Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-users-print-request-on-printer-noticed/"><u>Hidden User's Print Request on Printer Noticed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/lighten-up-on-slow-prints-quickly/"><u>Lighten Up on Slow Prints Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-for-post-update-printer-failure/"><u>Fix for Post-Update Printer Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-network-reestablished-windows-7/"><u>Printer Network Reestablished, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-online-functionality-regained/"><u>Epson Online Functionality Regained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574135496-enhance-printer-velocity-now/"><u>Enhance Printer Velocity Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-prints-blank-pages-solved/"><u>HP Printer Prints Blank Pages [SOLVED]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-to-brother-wireless-mfc-9330c/"><u>Quick Guide to Brother Wireless MFC-9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024s-guide-to-perfectly-pairing-hp-printer-with-laptops/"><u>2024'S Guide to Perfectly Pairing HP Printer with Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-paperless-print-error-rectified/"><u>Post-Upgrade, Paperless Print Error Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brew-the-latest-printer-driver-potion-in-windows-7/"><u>Brew the Latest Printer Driver Potion in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-plug-in-for-print-devices/"><u>Immediate Plug-In for Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-networked-windows-7-success/"><u>Printer Networked: Windows 7 Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-the-whiteout-from-our-print-sources/"><u>Banishing the Whiteout From Our Print Sources</u></a></li>
<li><a href="https://printer-issues.techidaily.com/manual-setting-up-hp-officejet-on-desktop-system/"><u>Manual: Setting up HP Officejet on Desktop System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-compatibility-windows-11-and-canons-mp620/"><u>Printer Compatibility: Windows 11 and Canon's MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-reunite-disconnected-printer/"><u>Swiftly Reunite Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-setup-for-rapid-prints/"><u>Speedy Setup for Rapid Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-117-solved/"><u>HP Printer Offline Status on Windows 11/7 [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fully-functional-page-to-page-printer-printing/"><u>Fully Functional, Page-to-Page Printer Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-new-life-into-non-printing-brother-printer-in-windows-1011/"><u>Breathe New Life Into Non-Printing Brother Printer in Windows 10/11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-anime-inspired-makeup-and-costume-ideas-for-tiktoks/"><u>[New] In 2024, Anime-Inspired Makeup & Costume Ideas for TikToks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-young-yachtsmens-playtime-pleasures/"><u>[Updated] 2024 Approved  Young Yachtsmen's Playtime Pleasures</u></a></li>
<li><a href="https://facebook.techidaily.com/mastery-of-mourning-disconnecting-your-fb-commerce-profile/"><u>Mastery of Mourning: Disconnecting Your FB Commerce Profile</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-many-attempts-to-unlock-iphone-xr-drfone-by-drfone-ios/"><u>How Many Attempts To Unlock iPhone XR | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-script-to-screen-youtube-studio-editing-workshop-guide/"><u>[Updated] In 2024, From Script to Screen  YouTube Studio Editing Workshop Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-newbies-roadmap-to-successful-podcast-editing/"><u>Updated In 2024, The Newbies Roadmap to Successful Podcast Editing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pioneering-scripts-reflecting-diverse-genre-themes/"><u>Pioneering Scripts Reflecting Diverse Genre Themes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-excellent-10-tech-choices-for-livestream-monitoring/"><u>[Updated] Excellent 10 Tech Choices for Livestream Monitoring</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-realme-c51-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Realme C51 FRP</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-proven-methods-to-elevate-your-filmora-editing-skills/"><u>[New] Proven Methods to Elevate Your Filmora Editing Skills</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-unbrand-your-videos-removing-filmora-watermark-made-easy/"><u>New 2024 Approved Unbrand Your Videos Removing Filmora Watermark Made Easy</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-high-fidelity-playback-of-games-using-obs/"><u>[Updated] In 2024, High Fidelity Playback of Games Using OBS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-melodycut-studio-high-quality-video-and-audio-editing/"><u>2024 Approved  MelodyCut Studio  High-Quality Video & Audio Editing</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unleash-your-creativity-easy-gopro-video-editing-for-beginners/"><u>New Unleash Your Creativity Easy GoPro Video Editing for Beginners</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-9-live-stream-enhancers-ultimate-filter-guide/"><u>In 2024, Top 9 Live-Stream Enhancers  Ultimate Filter Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-from-unnoticed-to-noteworthy-building-a-viral-fb-presence-for-2024/"><u>[New] From Unnoticed to Noteworthy  Building a Viral FB Presence for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-smart-way-to-choose-an-aiff-converter-tips-and-recommendations/"><u>New 2024 Approved The Smart Way to Choose an Aiff Converter Tips and Recommendations</u></a></li>
</ul></div>
