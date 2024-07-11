---
title: Troubleshooting Recurring Printer Errors in Win10/Win7
date: 2024-07-10T17:09:27.420Z
updated: 2024-07-11T17:09:27.420Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Troubleshooting Recurring Printer Errors in Win10/Win7
excerpt: This Article Describes Troubleshooting Recurring Printer Errors in Win10/Win7
keywords: Printer Troubleshoot,Recurring Printer Errors Fix,Print Spooler Problems,Win10 Printer Driver Update,Fax Errors Troubleshoot Win7,Inkjet Printer Error Solutions,Error Code Paper Jam Win10
thumbnail: https://thmb.techidaily.com/0f5fc285546b265c973fbaa96cd3591b73387ac3a0f71577bc77fa3f28f478c0.jpg
---

## Troubleshooting Recurring Printer Errors in Win10/Win7

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
<li><a href="https://printer-issues.techidaily.com/error-fixing-unable-to-add-hp-d1360-drivers-in-windows-oses/"><u>[Error Fixing] Unable to Add HP D1360 Drivers in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-failure-not-recognizing-canon-model/"><u>Printer Failure: Not Recognizing Canon Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-due-to-current-domain-services-outage/"><u>Print Issue Due to Current Domain Services Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-disconnected-swift-fix/"><u>Printer Disconnected: Swift Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-scanner-on-windows-11/"><u>Fixing Non-Operational Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-hp-printing-issue-0xoxc4eb827f/"><u>Mending HP Printing Issue 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-solutions-for-brother-printer-print-problems-in-windows-1011/"><u>Quick Solutions for Brother Printer Print Problems in Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/convenient-canon-printer-wireless-integration/"><u>Convenient Canon Printer Wireless Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-printer-drivers-for-better-output-win10-edition/"><u>Upgrade Printer Drivers for Better Output, WIN10 Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-hp-printer-connectivity-issues/"><u>Unlocking HP Printer Connectivity Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-printing-glitch-error-0x00000709-resolved/"><u>Fixed the Printing Glitch - Error 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restarting-network-drivers-fixes-hp-printer/"><u>Restarting Network Drivers Fixes HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-and-resolve-printer-spooling-trouble/"><u>Steps to Stop and Resolve Printer Spooling Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-art-of-configuring-your-hp-printer-on-pcs/"><u>Mastering the Art of Configuring Your HP Printer on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-puzzle-resolved-error-0x00000709/"><u>Printer Setup Puzzle: Resolved Error 0X00000709</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-canon-device-that-wont-react/"><u>Reviving a Canon Device That Won't React</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-secrets-to-dell-scanner-issues/"><u>Unlocking Secrets to Dell Scanner Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-unboxed-to-printed-the-complete-win-hp-printer-guidebook/"><u>From Unboxed to Printed: The Complete Win HP Printer Guidebook</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/effective-ways-to-design-fb-ad-videos-for-2024/"><u>Effective Ways to Design FB Ad Videos for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-high-end-8-cam-modifiers-for-crystal-clear-feeds/"><u>[Updated] 2024 Approved  High-End 8 Cam Modifiers for Crystal Clear Feeds</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unleash-the-power-of-first-impressions-with-top-30-youtube-intra-craftsmen/"><u>[New] Unleash the Power of First Impressions with Top 30 YouTube Intra Craftsmen</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-insights-for-optimal-iphone-x-animoji-use/"><u>Comprehensive Insights for Optimal iPhone X Animoji Use</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-mobile-app-dev-editing-systems/"><u>Best Mobile App Dev Editing Systems</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-unveiling-the-secret-for-instantaneous-deletion-of-youtube-feedbacks/"><u>[Updated] 2024 Approved  Unveiling the Secret for Instantaneous Deletion of Youtube Feedbacks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-in-depth-look-at-gecata-capture-tool/"><u>In 2024, In-Depth Look at Gecata Capture Tool</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-hero5-black-vs-hero5-the-duel-for-durability/"><u>[New] Hero5 Black vs Hero5, The Duel for Durability</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-essential-editing-tricks-for-peak-obs-performance/"><u>In 2024, Essential Editing Tricks for Peak OBS Performance</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-leveraging-technology-tools-for-accurate-and-efficient-market-analysis/"><u>[New] Leveraging Technology Tools for Accurate and Efficient Market Analysis</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-c55-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Realme C55 Bootloader Easily</u></a></li>
</ul></div>
