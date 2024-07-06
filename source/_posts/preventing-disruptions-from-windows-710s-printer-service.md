---
title: Preventing Disruptions From Windows 7/10'S Printer Service
date: 2024-06-28T07:14:23.556Z
updated: 2024-06-29T07:14:23.556Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventing Disruptions From Windows 7/10'S Printer Service
excerpt: This Article Describes Preventing Disruptions From Windows 7/10'S Printer Service
keywords: Windows 7 Printer Issues,Windows 10 Printer Service Troubleshooting,Printer Connectivity Errors in Windows 7/10,Troubleshoot Windows 7 Printer Service Disruptions,Printer Errors in Windows 10 OS,Prevent Printer Service Downtimes on Windows 7/10,Windows 7/10 Printer Service Maintenance Tips
thumbnail: https://thmb.techidaily.com/f0eb15dbd4d3bc9550ae7ac5d466cfd7136ebba5996edeb6f057c08fddaa5f37.jpg
---

## Preventing Disruptions From Windows 7/10'S Printer Service

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
<li><a href="https://printer-issues.techidaily.com/overcome-print-spooler-failure/"><u>Overcome Print Spooler Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-access-granted-after-troubleshooting/"><u>[PRINT] Access Granted After Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silent-shutdown-wake-up-with-these-troubleshooting-steps/"><u>Silent Shutdown? Wake Up With These Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-problem-discovered/"><u>Unexpected Print Problem Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/full-colors-unavailable-on-printout/"><u>Full Colors Unavailable on Printout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fine-tune-your-prints-install-new-v305-driver-in-win7/"><u>Fine-Tune Your Prints: Install New V305 Driver in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-swift-printers/"><u>Quick Tips for Swift Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-hp-inkjet-on-windows-11-offline/"><u>Unblocking HP Inkjet on Windows 11 Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-windows-7-printer-unresponsive/"><u>Resolved: Windows 7 Printer Unresponsive</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-vivo-y100a-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Vivo Y100A PC | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-a-step-by-step-guide-to-creating-stunning-stop-motion-videos-on-instagram/"><u>Updated 2024 Approved A Step-by-Step Guide to Creating Stunning Stop Motion Videos on Instagram</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-nord-n30-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Nord N30 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-7-plus-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone 7 Plus</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-revisiting-old-memories-how-to-upload-them-on-snapchat/"><u>In 2024, Revisiting Old Memories  How to Upload Them on Snapchat</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-a-countdown-effect-is-widely-used-in-gaming-and-report-videos-so-how-to-create-your-own-countdown-video-this-article-will-tell-you-some-ideas-about-/"><u>In 2024, A Countdown Effect Is Widely Used in Gaming and Report Videos. So How to Create Your Own Countdown Video? This Article Will Tell You some Ideas About Contdown Video Editing</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-strategies-to-increase-views-via-thumbnails/"><u>[Updated] 2024 Approved  Strategies to Increase Views via Thumbnails</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-10-innovative-ideas-to-shield-your-webcam-for-2024/"><u>[Updated] 10 Innovative Ideas to Shield Your Webcam for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ssential-insights-for-asmr-aficionados-for-2024/"><u>[New] Essential Insights for ASMR Aficionados for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instastars-academy-how-to-amass-1000plus-followers-each-month/"><u>In 2024, InstaStars Academy  How to Amass 1,000+ Followers Each Month</u></a></li>
</ul></div>
