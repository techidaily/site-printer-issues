---
title: "Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
date: 2024-06-28T07:15:15.206Z
updated: 2024-06-29T07:15:15.206Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
excerpt: "This Article Describes Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
keywords: Windows Cleanup Guide,Cease Spooler Fix for Windows 7/10/11,Windows Spooler Halt Tutorial,Speed Up Windows 7/10/11,Windows Performance Boost Guide,Resolve Windows 7/10/11 Bloatware Issue,Optimize System Resources Windows 7/10/11
thumbnail: https://thmb.techidaily.com/31170fc82b47adef76e35b1dbe5e6312865cece8cca3cd844fe92c1c213c87ec.jpg
---

## Quick Guide: Cease Spooler Halt on W7/10, 11 Windows

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
<li><a href="https://printer-issues.techidaily.com/triumph-over-print-issue-winerror-0x00000709-remedied/"><u>Triumph Over Print Issue: WinError 0X00000709 Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-scan-to-computer-is-no-longer-activated-on-windows-10/"><u>Solved: Scan to Computer Is No Longer Activated on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanned-device-connection-issue-on-win10/"><u>Fixing Scanned Device Connection Issue on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unclogging-xerox-paper-path-errors/"><u>Unclogging Xerox Paper Path Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-print-job-stuck-in-queue-quickly/"><u>Fix ‘Print Job Stuck in Queue’ Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-manual-hp-smartoffice-800-series/"><u>Installation Manual: HP SmartOffice 800 Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addsvc-not-responding-printer-error-reported/"><u>ADDSVC Not Responding: Printer Error Reported</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-networked-printer-issues/"><u>Navigating Through Networked Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dont-let-offline-be-the-end-for-your-canon-printer/"><u>Don’t Let Offline Be the End for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-link-between-sibling-and-online-printer/"><u>Restoring Link Between Sibling and Online Printer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-the-secrets-to-blurring-iphone-photos-a-comprehensive-guide-for-2024/"><u>Unveiling the Secrets to Blurring iPhone Photos  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-craft-your-first-impactful-facebook-phenomenon-giveaway/"><u>[Updated] In 2024, Craft Your First Impactful Facebook Phenomenon Giveaway</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-buy-youtube-subscribers-hundreds-of-subscribers-for-5/"><u>[New] Buy YouTube Subscribers - Hundreds of Subscribers for $5?</u></a></li>
<li><a href="https://extra-information.techidaily.com/discover-a-world-of-creative-slide-show-patterns-at-no-cost/"><u>Discover a World of Creative Slide Show Patterns at No Cost</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-analyzing-the-impact-of-reduced-photo-jiggles-in-adobe/"><u>[Updated] Analyzing the Impact of Reduced Photo Jiggles in Adobe</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-next-day-evaluation-beyond-tradition/"><u>In 2024, Next Day Evaluation  Beyond Tradition</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-ipod-and-apple-iphone-15-pro-max-the-right-way-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock On iPod and Apple iPhone 15 Pro Max The Right Way</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-refreshing-woes-in-tiktok-reclaim-your-content-for-2024/"><u>[New] Refreshing Woes in TikTok – Reclaim Your Content for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-mastering-tempo-sync-adjusting-video-clips-with-premiere-pros-audio-beatmap/"><u>Updated Mastering Tempo Sync Adjusting Video Clips with Premiere Pros Audio Beatmap</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-oneplus-11r-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on OnePlus 11R | Dr.fone</u></a></li>
</ul></div>
