---
title: Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)
date: 2024-06-28T07:06:35.477Z
updated: 2024-06-29T07:06:35.477Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)
excerpt: This Article Describes Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)
keywords: Print Spooler Troubleshooting,Resolve Print Spooler Shutdown,Fix Windows 10 Print Service,Spooler Error Solutions (Win 10, 11 & 7),Printer Service Restart Guide,How to Unblock Print Spooler (Windows),Stop Windows 10 Print Problems
thumbnail: https://thmb.techidaily.com/a54e5c701c009258ccb5e3ebc68c482a0352d900bfe7620286533aaa04ebdf62.png
---

## Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)

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
<li><a href="https://printer-issues.techidaily.com/steering-clear-obstacles-onboard-brother-printer-again/"><u>Steering Clear Obstacles: Onboard Brother Printer Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-drive-issue-cant-connect-on-pc/"><u>Printer Drive Issue: Can't Connect on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-white-printouts-deciphering-the-epson-mishap/"><u>Endless White Printouts: Deciphering the Epson Mishap</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-silence-to-service-restoring-online-status-in-printer/"><u>From Silence to Service: Restoring Online Status in Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-print-error-solved-online-and-offline/"><u>HP Print Error: Solved - Online & Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-printers-life-with-windows-11-fixes/"><u>Revive Your Printer's Life with Windows 11 Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/all-page-printer-issues-resolved/"><u>All-Page Printer Issues Resolved</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-next-decades-digital-marketing-shifts-in-facebook-advertising/"><u>In 2024, Next Decade's Digital Marketing Shifts in Facebook Advertising</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-tecno-spark-10-pro-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-guiding-you-to-untainted-stock-visuals/"><u>[New] In 2024, Guiding You to Untainted Stock Visuals</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unlocking-your-youtube-comment-tracking-on-multiple-devices/"><u>Unlocking Your YouTube Comment Tracking on Multiple Devices</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-top-video-editing-software-with-ai-reframing/"><u>Updated 2024 Approved Top Video Editing Software with AI Reframing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-how-to-make-time-lapse-videos-with-gopro-studio/"><u>[New] 2024 Approved  How to Make Time Lapse Videos With GoPro Studio</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-complete-breakdown-of-color-tuning-methods/"><u>A Complete Breakdown of Color Tuning Methods</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleash-zooms-full-potential-with-essential-3-methods/"><u>2024 Approved  Unleash Zoom's Full Potential with Essential 3 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-130-music-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from 130 Music</u></a></li>
</ul></div>
