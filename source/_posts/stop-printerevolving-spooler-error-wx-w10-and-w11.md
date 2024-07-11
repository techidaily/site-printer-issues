---
title: Stop Printer'evolving Spooler Error (WX, W10 & W11)
date: 2024-07-10T16:43:35.623Z
updated: 2024-07-11T16:43:35.623Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop Printer'evolving Spooler Error (WX, W10 & W11)
excerpt: This Article Describes Stop Printer'evolving Spooler Error (WX, W10 & W11)
keywords: Windows Spooler Error,Printer Spooler Troubleshooting,Spooler Error Fixes,Printer Spooler W10/W11,Spooler Error X/W10,Printer Error X/W10/11,Printer Spooler X/W10 Troubleshooting,Written By,Printer Spooler X/W10/11
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## Stop Printer'evolving Spooler Error (WX, W10 & W11)

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
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-configuration-error/"><u>Gear Up Glitch: Printer Configuration Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-restored-scan-operation/"><u>Windows 11: Restored Scan Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-print-server-disconnect/"><u>Overcoming Print Server Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-removal-of-drivers-for-printer-devices/"><u>Secure Removal of Drivers for Printer Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-troubleshoot-unseen-network-printer-on-windows-pcs/"><u>[OS Troubleshoot] Unseen Network Printer on Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-lags-in-printing/"><u>Immediate Fixes for Lags in Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/transforming-empty-sheets-into-essential-data/"><u>Transforming Empty Sheets Into Essential Data</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-epson-printer-error-codes-on-w11/"><u>Troubleshoot Epson Printer Error Codes on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-over-printing-white-paper/"><u>Epson Photo Printer: Over-Printing White Paper</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-unresponsive-printers/"><u>Repairing Unresponsive Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-pages-be-gone-hp-printer-now-fully-functional/"><u>Blank Pages Be Gone: HP Printer Now Fully Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-brother-printer-no-output/"><u>Reviving Brother Printer No Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-mp620-not-recognized-by-windows/"><u>[Update Required] MP620 Not Recognized by Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-system-cannot-retrieve-printer-drivers/"><u>Win System: Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574032401-trouble-printing-on-windows-11-lets-fix-it/"><u>Trouble Printing on Windows 11? Let's Fix It!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-epson-ink-problem-now-prints/"><u>Corrected Epson Ink Problem, Now Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hiccup-configuration-issue-surfaced/"><u>Printer Hiccup: Configuration Issue Surfaced</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-visual-process-guide-on-setting-up-your-canon-printer/"><u>A Visual Process Guide on Setting up Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-printer-solutions-unveiled/"><u>Speedy Printer Solutions Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alert-windows-10-print-queue-offline/"><u>[ALERT] Windows 10: Print Queue Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/what-to-do-when-your-printer-is-offline/"><u>What To Do When Your Printer Is Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-methods-quickly-connect-hp-to-laptops/"><u>New Methods: Quickly Connect HP to Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-mf4770n-integration-on-windows-platforms/"><u>Elevate MF4770n Integration on Windows Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantle-disconnection-get-your-printer-printing-again/"><u>Dismantle Disconnection: Get Your Printer Printing Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-your-v305-printing-fresh-with-windows-updates/"><u>Keep Your V305 Printing Fresh with WIndows Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-non-responsive-hp-printers/"><u>Resolving Non-Responsive HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driving-performance-mf4770n-on-windows-oss/"><u>Driving Performance: MF4770n on Windows OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-incorporating-hp-printer-in-pc-network/"><u>Step-by-Step: Incorporating HP Printer in PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-software-conflicts-in-printing-hardware/"><u>Resolving Software Conflicts in Printing Hardware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-stopped-printing-fixed-now/"><u>HP LaserJet Stopped Printing - Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt98-restore-efficient-printer-responsiveness/"><u>WinNT/98: Restore Efficient Printer Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-mf4770n-integration-with-win-1087/"><u>Boosting MF4770n Integration with Win 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-no-9008e/"><u>Resolved: Printer Error No. 9008E</u></a></li>
<li><a href="https://printer-issues.techidaily.com/limited-color-range-in-output-documents/"><u>Limited Color Range in Output Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7810-networking-guide-for-inkjet-hp-issues/"><u>Win7/8/10 Networking Guide for Inkjet HP Issues</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-mastery-of-transferring-multitudes-of-tiktok-videos/"><u>2024 Approved  Mastery of Transferring Multitudes of TikTok Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/social-synergy-blueprint-for-ig-and-tiktok-pairing-for-2024/"><u>Social Synergy Blueprint for IG & TikTok Pairing for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-how-to-improve-sound-quality-on-a-home-recorded-video/"><u>Updated How to Improve Sound Quality on a Home Recorded Video?</u></a></li>
<li><a href="https://howto.techidaily.com/google-pixel-8-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Pixel 8 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-common-pitfalls-with-proper-use-of-youtube-tags-for-2024/"><u>Avoid Common Pitfalls with Proper Use of YouTube Tags for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhance-visibility-the-most-effective-30-freefire-tags-for-video-marketing/"><u>[Updated] Enhance Visibility  The Most Effective 30 FreeFire Tags for Video Marketing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-breakthrough-in-video-production-advanced-techniques-for-uploading-360-content-on-youtube/"><u>[New] In 2024, Breakthrough in Video Production  Advanced Techniques for Uploading 360° Content on YouTube</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719576102131-master-bangla-in-just-10-mins-a-day/"><u>Master Bangla in Just 10 Mins a Day!</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-how-to-maximize-your-impact-with-snapchat-spotlight/"><u>[New] How to Maximize Your Impact with Snapchat Spotlight</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-htc-vive-headset-review/"><u>[New] HTC Vive Headset Review</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/a-lifetime-of-learning-why-add-a-second-or-third-language-to-your-skill-set-after-40/"><u>A Lifetime of Learning: Why Add a Second (or Third) Language to Your Skill Set After 40</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-perfecting-game-capture-techniques-and-tricks/"><u>[Updated] In 2024, Perfecting Game Capture  Techniques & Tricks</u></a></li>
</ul></div>
