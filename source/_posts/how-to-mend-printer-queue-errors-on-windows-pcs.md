---
title: How to Mend Printer Queue Errors on Windows PCs
date: 2024-07-10T16:49:54.084Z
updated: 2024-07-11T16:49:54.084Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Mend Printer Queue Errors on Windows PCs
excerpt: This Article Describes How to Mend Printer Queue Errors on Windows PCs
keywords: Printer Queue Error Fix,Windows Print Troubleshooting,Resolve Printer Errors (Windows),Stop Printer Queue Delays (PC),Fix Windows Print Spooler Errors,Troubleshoot Printer Queue Issues (Windows),Print Error Resolution Guide (Windows)
thumbnail: https://thmb.techidaily.com/2759ed3d822d64726b5041a7dfa5154bfc20081c37343fab709d27bf02b2be55.jpg
---

## How to Mend Printer Queue Errors on Windows PCs

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
<li><a href="https://printer-issues.techidaily.com/windows-xp-vs-mp620-printer-compatibility-questions/"><u>Windows XP vs MP620 Printer Compatibility Questions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-and-mp620-printer-wheres-the-compatibility/"><u>Win11 & MP620 Printer: Where's the Compatibility?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-the-no-content-print-jobs-on-an-epson-device/"><u>Fixing the 'No Content' Print Jobs on an Epson Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-inkjet-aio-updater-for-win7/"><u>Dell Inkjet AIO Updater for Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-ink-level-sensor-failures-in-w11/"><u>Address Ink Level Sensor Failures in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-solved-for-epson-model/"><u>Print Issue Solved for Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-canon-pixma-mp620-unseen-in-win11/"><u>[Driver Difficulty] Canon Pixma MP620 Unseen in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-incompatible-printer-drivers-for-hp-d1360-in-windows/"><u>Resolving Incompatible Printer Drivers for HP D1360 in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-windows-2000-xp-print-errors-quickly/"><u>Resolve Windows 2000 XP Print Errors Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prevent-windows-10-printer-malfunctions-and-fails/"><u>Prevent Windows 10 Printer Malfunctions and Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-the-blank-page-mystery-in-printers/"><u>Clearing Up the Blank Page Mystery in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secret-behind-empty-printouts/"><u>Unveiling the Secret Behind Empty Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-error-only-blank-sheets-from-epson/"><u>Printer Setup Error: Only Blank Sheets From Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-compatibility-issue-hp-drivers-not-found-on-win1110/"><u>Hardware Compatibility Issue: HP Drivers Not Found on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-rectified/"><u>Code B200 Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574049626-fix-print-job-stuck-in-queue-quickly/"><u>Fix 'Print Job Stuck in Queue' Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-around-canons-no-prints-with-these-5-effective-fixes-for-windows-11/"><u>Turn Around Canon's No-Prints with These 5 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-connection-solutions-joining-your-laptop-and-hp-printer/"><u>Streamlined Connection Solutions: Joining Your Laptop and HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-printer-manager-for-windows-systems/"><u>HP Officejet Pro 8600 Printer Manager for Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-fixes-for-epson-error-0x97/"><u>Mastering Fixes for Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-laser-print-glitches/"><u>Clearing Up Laser Print Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-inkjet-non-operational/"><u>Repaired Inkjet Non-Operational</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-printer-malfunction-code-0x97/"><u>Mending Printer Malfunction: Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-powerhouse-latest-updates-for-dell-printer-windows-7/"><u>Printing Powerhouse: Latest Updates for Dell Printer WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-removal-of-drivers-for-printer-devices/"><u>Secure Removal of Drivers for Printer Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://audio-editing.techidaily.com/inspirational-audio-bridges-to-current-affairs-volume-15-for-2024/"><u>Inspirational Audio Bridges to Current Affairs Volume 15 for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastering-the-art-of-profile-video-lure/"><u>[New] 2024 Approved  Mastering the Art of Profile Video Lure</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-vivo-g2-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Vivo G2</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-prime-strategies-for-constructing-mcc-homes/"><u>[Updated] Prime Strategies for Constructing MCC Homes</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-organic-scenes-essential-free-templates-to-elevate-filmmaking-art/"><u>[Updated] Organic Scenes  Essential, Free Templates to Elevate Filmmaking Art</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-boxing-brilliance-versus-broadband-bonanza/"><u>2024 Approved  Boxing Brilliance versus Broadband Bonanza</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-get-your-swap-on-the-best-face-swap-apps-for-mobile-devices/"><u>New 2024 Approved Get Your Swap On The Best Face Swap Apps for Mobile Devices</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/trouble-with-apple-iphone-14-plus-swipe-up-try-these-11-solutions-by-drfone-ios/"><u>Trouble with Apple iPhone 14 Plus Swipe-Up? Try These 11 Solutions</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-beyond-popularity-youtube-earnings-for-1m-viewer-base/"><u>In 2024, Beyond Popularity – YouTube Earnings for 1M Viewer Base</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/best-webcams-unveiled-a-youtube-livestreamers-handbook-for-2024/"><u>Best Webcams Unveiled  A YouTube Livestreamer's Handbook for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-innovations-highlighted-in-s3700s-2023-review/"><u>[Updated] Innovations Highlighted in S3700's 2023 Review</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-tiktok-feasts-current-favorites-explored/"><u>[Updated] In 2024, TikTok Feasts  Current Favorites Explored</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/stay-in-the-limelight-how-to-keep-youtube-cc-and-boost-views-for-2024/"><u>Stay in the Limelight  How to Keep YouTube CC and Boost Views for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-strategies-for-maximizing-your-video-footprint-in-instagram/"><u>[New] 2024 Approved  Strategies for Maximizing Your Video Footprint in Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unlock-the-power-of-video-delays-with-this-snapchat-guide/"><u>[New] Unlock the Power of Video Delays with This Snapchat Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-no-more-watermarks-iphones-and-tiktok-downloads/"><u>[Updated] In 2024, No More Watermarks  IPhones and TikTok Downloads</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-download-your-wish-unwatermarked-tiktok-files/"><u>[New] 2024 Approved  Download-Your-Wish  Unwatermarked TikTok Files</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-visual-testimonial-advantage/"><u>In 2024, The Visual Testimonial Advantage</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-poco-f5-pro-5g-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Poco F5 Pro 5G FRP In 3 Different Ways</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-streamline-video-using-vimeo-record-for-live-captures-for-2024/"><u>[Updated] Streamline Video  Using Vimeo Record for Live Captures for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unveiling-the-secret-sauce-for-astonishing-gifs-from-vimeo-videos-for-2024/"><u>[Updated] Unveiling the Secret Sauce for Astonishing GIFs From Vimeo Videos for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-thriving-as-a-digital-creator/"><u>A Guide to Thriving as a Digital Creator</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-getting-started-with-hd-video-understanding-pixel-size-and-resolution/"><u>In 2024, Getting Started with HD Video Understanding Pixel Size and Resolution</u></a></li>
</ul></div>
