---
title: "Preventing Constant Spooler Crashes: A Guide for Windows Users"
date: 2024-07-10T17:23:46.596Z
updated: 2024-07-11T17:23:46.596Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Preventing Constant Spooler Crashes: A Guide for Windows Users"
excerpt: "This Article Describes Preventing Constant Spooler Crashes: A Guide for Windows Users"
keywords: Preventing Windows Spooler Crashes,Windows System Stability Tips,Windows Spooler Troubleshooting Guide,Avoiding Spooler Crashes in Windows,Optimizing Spooler Performance,Spooler Error Diagnosis on Windows,Windows Spooler Crash Solutions
thumbnail: https://thmb.techidaily.com/18d989e548104708bf52f53d39fea00818139641241145ab7026454dd288c9b9.jpg
---

## Preventing Constant Spooler Crashes: A Guide for Windows Users

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
<li><a href="https://printer-issues.techidaily.com/quick-guide-releasing-a-stuck-printer-from-windows/"><u>Quick Guide: Releasing A Stuck Printer From Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-visual-process-guide-on-setting-up-your-canon-printer/"><u>A Visual Process Guide on Setting up Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-service-from-frequently-stopping/"><u>Stop Windows Print Service From Frequently Stopping</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-wireless-connectivity-for-hp-print/"><u>Enabling Wireless Connectivity for HP Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-alert-unable-to-locate-on-windows-10/"><u>[Printer Driver Alert]: Unable to Locate on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-printer-error-code-e-0x97/"><u>Resolving Printer Error Code E-0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-printer-vanishes-whats-the-remedy/"><u>Network Printer Vanishes, What's the Remedy?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-scanner-after-windows-10-update/"><u>Enabling Scanner After Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-over-printing-white-paper/"><u>Epson Photo Printer: Over-Printing White Paper</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-canon-printer-seamless-wireless-hookup/"><u>Stepwise Canon Printer: Seamless Wireless Hookup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-printer-service-spooler-issues/"><u>Fixing Non-Operational Printer Service (Spooler) Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/visual-guide-configure-your-new-canon-printer/"><u>Visual Guide: Configure Your New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win2k-printer-response-error-resolution-guide/"><u>Win2K Printer Response: Error Resolution Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-support-steps-to-fix-vanished-printer-on-pcs/"><u>[Tech Support] Steps to Fix Vanished Printer on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-non-functional-printers/"><u>Solutions for Non-Functional Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-compatibility-upgrade-for-windows-os/"><u>MF4770n Compatibility Upgrade for Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-queue-hang-up-promptly/"><u>Resolve Print Queue Hang-Up Promptly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-stop-and-repair-spooler-on-windows-versions-7-11/"><u>How to Stop and Repair Spooler on Windows Versions 7-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-tale-of-triumph-over-theoretical-paper-trails/"><u>A Tale of Triumph Over Theoretical Paper Trails</u></a></li>
<li><a href="https://some-skills.techidaily.com/television-or-projector-for-peak-4k-performance-for-2024/"><u>Television or Projector for Peak 4K Performance for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/10-best-no-cost-video-calls-for-remote-collaboration/"><u>10 Best No-Cost Video Calls for Remote Collaboration</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-churn-memetic-content-for-gif-hub/"><u>2024 Approved  Churn Memetic Content for GIF Hub</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-leveraging-imovie-features-to-upgrade-your-youtube-content-quality/"><u>[New] Leveraging iMovie Features to Upgrade Your YouTube Content Quality</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-add-shimmer-to-photos-illustrators-motion-blur-guide/"><u>[Updated] Add Shimmer to Photos  Illustrator's Motion Blur Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-hue-harmony-the-definitive-guide-to-video-coloring-for-2024/"><u>[Updated] Hue Harmony  The Definitive Guide to Video Coloring for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-honor-90-pro-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transitioning-from-imovie-editing-suite-to-youtube-showcase-for-2024/"><u>Transitioning From iMovie Editing Suite to YouTube Showcase for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-inside-disruptive-designers-of-discords-visual-lexicon-for-2024/"><u>[Updated] Inside Disruptive Designers of Discord's Visual Lexicon for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-delving-into-the-world-of-mukbang-videos/"><u>[Updated] Delving Into the World of Mukbang Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-universal-synchronization-zoom-on-phones-tablets-pcs-all/"><u>In 2024, Universal Synchronization  Zoom on Phones, Tablets, PCs All</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-unleash-creativity-premier-vimeo-editors-deliver/"><u>[Updated] 2024 Approved  Unleash Creativity  Premier Vimeo Editors Deliver</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/unveiling-the-most-reliable-websites-for-precision-mp3-tagging-and-organizing/"><u>Unveiling the Most Reliable Websites for Precision MP3 Tagging and Organizing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-no-cost-creative-corner-finding-the-finest-tiktok-backgrounds/"><u>[New] No-Cost Creative Corner  Finding the Finest TikTok Backgrounds</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-history-in-action-top-7-engaging-civilization-wars/"><u>[Updated] History in Action  Top 7 Engaging Civilization Wars</u></a></li>
</ul></div>
