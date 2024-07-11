---
title: Essential Fixes for Non-Starting Print Spooler on PCs
date: 2024-07-10T17:14:02.237Z
updated: 2024-07-11T17:14:02.237Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Essential Fixes for Non-Starting Print Spooler on PCs
excerpt: This Article Describes Essential Fixes for Non-Starting Print Spooler on PCs
keywords: Windows Print Spooler Troubleshoot,Non-Starting Spooler Fixes on PCs,Print Spooler Service Restart Tips,Resolve Printer Hangup Windows 10/8,Spooler Service Error Diagnosis,PC Print Spooler Not Starting Help,Fix Non-Responsive Printer on Windows
thumbnail: https://thmb.techidaily.com/8ff514e7ae8e73f00c632257f00b6aefbc08dc01d831c81a6f2628b843ff494a.jpg
---

## Essential Fixes for Non-Starting Print Spooler on PCs

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
<li><a href="https://printer-issues.techidaily.com/solved-printer-communication-not-available-issue/"><u>[Solved] Printer Communication Not Available Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574058416-5-easy-ways-to-fix-canon-printer-wont-print-in-windows-10/"><u>5 Easy Ways to Fix Canon Printer Won’t Print in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnecting-scanner-to-windows-10-post-update/"><u>Reconnecting Scanner to Windows 10 Post-Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-glitch-printer-no-longer-functions/"><u>Post-Update Glitch: Printer No Longer Functions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-pages-be-gone-hp-printer-now-fully-functional/"><u>Blank Pages Be Gone: HP Printer Now Fully Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-pcl-xl-hurdles-quickly-and-smoothly/"><u>Decoding PCL XL Hurdles Quickly and Smoothly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guiding-through-printer-malfunction-fixes/"><u>Guiding Through Printer Malfunction Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problem-hp-printer-driver-issues-across-windows-versions/"><u>[Network Problem] HP Printer Driver Issues Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-hiccup-discovered/"><u>Unexpected Print Hiccup Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-upgrade-streamline-mf4770n-in-windows/"><u>Drive Upgrade: Streamline MF4770n in WIndows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-inkjet-puzzled-printing/"><u>Resolving Inkjet: Puzzled Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-canon-wi-fi-connection-process/"><u>Mastering the Canon-Wi-Fi Connection Process</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-streamline-of-hindered-printer-jobs/"><u>Quick Streamline of Hindered Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restarting-non-functional-usb-devices-post-sleep-windows-7/"><u>Restarting Non-Functional USB Devices Post Sleep, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantle-disconnection-get-your-printer-printing-again/"><u>Dismantle Disconnection: Get Your Printer Printing Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-access-a-guide-for-offline-printers/"><u>Regaining Access: A Guide for Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-spooler-failure/"><u>Overcome Print Spooler Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-network-printer-not-showing-up-in-windows-1110/"><u>[Fixed] Network Printer Not Showing up in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-problem-windows-10-cant-find-mp620-printer-driver/"><u>[Driver Search] Problem: Windows 10 Can't Find MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-queue-error-messages-on-windows-11/"><u>Fix Printing Queue Error Messages on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-setup-software-package-hp-officejet-pro-8600-for-pcs/"><u>Quick Setup Software Package: HP OfficeJet Pro 8600 for PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drivers-canon-mp620-not-found-on-11th-edition-windows/"><u>[Drivers] Canon MP620 Not Found on 11Th Edition Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-cover-video-essentials-for-facebook-professionals/"><u>[New] 2024 Approved  Cover Video Essentials for Facebook Professionals</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/reality-check-for-popular-year-end-commitments/"><u>Reality Check for Popular Year-End Commitments</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-customizing-your-watch-the-art-of-altering-youtube-video-pace/"><u>[New] In 2024, Customizing Your Watch  The Art of Altering YouTube Video Pace</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-kinemaster-tutorial-seamless-integration-of-green-screen-techniques-for-2024/"><u>[Updated] Kinemaster Tutorial  Seamless Integration of Green Screen Techniques for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-14-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone 14 | Stellar</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pick-the-best-top-8-srt-tools-without-payment/"><u>In 2024, Pick the Best  Top 8 SRT Tools Without Payment</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-top-8-sites-for-sharing-and-downloading-free-3d-text-psds-for-2024/"><u>The Top 8 Sites for Sharing and Downloading Free 3D Text PSDs for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-10-drones-for-high-quality-cinematography/"><u>In 2024, Best 10 Drones for High-Quality Cinematography</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-oppo-k11-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Oppo K11 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/passfab-apple-iphone-xs-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>PassFab Apple iPhone XS Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-code-commanders-elite-females-on-yt/"><u>[Updated] 2024 Approved  Code Commanders  Elite Females on YT</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-key-steps-to-successfully-infiltrating-your-dream-discord-server/"><u>2024 Approved  Key Steps to Successfully Infiltrating Your Dream Discord Server</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-revolutionize-tiktok-live-top-techniques-from-desktop-viewers/"><u>[Updated] Revolutionize TikTok Live  Top Techniques From Desktop Viewers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/how-mycam-changes-video-recording-at-home-an-in-depth-review-for-2024/"><u>How MyCam Changes Video Recording at Home – An In-Depth Review for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-quick-ways-to-reshuffle-youtube-tracks-on-pcphonetv/"><u>In 2024, Quick Ways to Reshuffle YouTube Tracks on PC/Phone/TV</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-step-by-step-guide-to-adding-frames-on-instagram-photos/"><u>[Updated] In 2024, Step-by-Step Guide to Adding Frames on Instagram Photos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-cyclings-finest-gaming-experiences-for-2024/"><u>[New] Cycling's Finest Gaming Experiences for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-correcting-missed-audio-segments-in-obs-recordings/"><u>[Updated] 2024 Approved  Correcting Missed Audio Segments in OBS Recordings</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-5-best-laugh-inducing-voice-alteration-methods-for-enthralling-calls/"><u>The 5 Best Laugh-Inducing Voice Alteration Methods for Enthralling Calls</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-video-dimensions-for-instagram-a-beginners-guide/"><u>New In 2024, Video Dimensions for Instagram A Beginners Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-display-after-upgrade/"><u>No Display After Upgrade</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-engaging-your-audience-with-fb-live/"><u>In 2024, Engaging Your Audience with FB Live</u></a></li>
<li><a href="https://games-able.techidaily.com/reconnecting-steps-for-windows-to-solve-ps4-controller-dropping-out/"><u>Reconnecting: Steps for Windows to Solve PS4 Controller Dropping Out</u></a></li>
</ul></div>
