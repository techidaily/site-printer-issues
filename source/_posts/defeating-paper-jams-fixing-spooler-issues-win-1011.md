---
title: "Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)"
date: 2024-07-10T17:21:23.972Z
updated: 2024-07-11T17:21:23.972Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)"
excerpt: "This Article Describes Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)"
keywords: Paper Jam Fixation,Spooler Troubleshooting Windows 10/11,Printer Problems Win 10/11,Print Spooler Solutions for PC Users,Prevent Paper Jams in Win 10/11 Printers,Windows Print Spooler Fixes (Tips & Tricks),Troubleshoot Paper Jams in Modern Windows
thumbnail: https://thmb.techidaily.com/c54c6148123e508341809a9f8c11fb6ca2958cb786ab2471b34202053c6a9248.jpg
---

## Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)

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
<li><a href="https://printer-issues.techidaily.com/boost-print-speed-and-quality-download-hp-officejet-firmware/"><u>Boost Print Speed & Quality - Download HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canons-error-b200/"><u>Fixed Canon's Error: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/offline-printer-issue-resolved-in-win7/"><u>Offline Printer Issue Resolved in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/farewell-to-printer-frustration-win-10s-solution-found/"><u>Farewell to Printer Frustration: Win 10'S Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-canons-print-to-wi-fi-journey/"><u>Navigating Canon's Print to Wi-Fi Journey</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-steps-for-brothers-printer-resuming-normalcy-online/"><u>Easy Steps for Brother's Printer Resuming Normalcy Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-white-paper-trap-how-to-prevent-it/"><u>Epson's White Paper Trap: How to Prevent It?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-queue-hang-up-promptly/"><u>Resolve Print Queue Hang-Up Promptly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-and-activating-scanner-seamlessly-on-windows-11/"><u>Disabling & Activating Scanner Seamlessly on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-setup-for-a-brand-new-canon-printer/"><u>Effortless Setup for a Brand-New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fully-functional-page-to-page-printer-printing/"><u>Fully Functional, Page-to-Page Printer Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cure-print-issues-with-windows-11-advice/"><u>Cure Print Issues with Windows 11 Advice</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-the-whiteout-from-our-print-sources/"><u>Banishing the Whiteout From Our Print Sources</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-refusing-to-use-all-colors/"><u>Printer Refusing to Use All Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-printer-online-error-fixed-on-win7/"><u>Dell Printer Online: Error Fixed on Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-wireless-setup-guide-for-brother-fans/"><u>MFC-9330 Wireless Setup Guide for Brother Fans</u></a></li>
<li><a href="https://printer-issues.techidaily.com/updating-drives-with-mf4770n-for-windows-1087/"><u>Updating Drives with MF4770n for Windows 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-prints-install-latest-v305-driver-in-win7/"><u>Revitalize Your Prints: Install Latest V305 Driver in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drivers-canon-mp620-not-found-on-11th-edition-windows/"><u>[Drivers] Canon MP620 Not Found on 11Th Edition Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-mishap-printer-setup-misstep/"><u>Technical Mishap: Printer Setup Misstep!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574163521-windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/growth-and-profitability-in-the-digital-marketplace-explore-these-top-15-facebook-insights-for-2024/"><u>Growth & Profitability in the Digital Marketplace  Explore These Top 15 Facebook Insights for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-are-you-in-a-funny-chat-with-a-friend-and-want-to-send-a-gif-but-couldnt-find-one-here-we-will-provide-you-with-the-top-image-for-gif-converters-so-let-/"><u>New Are You in a Funny Chat with a Friend and Want to Send a GIF but Couldnt Find One? Here We Will Provide You with the Top Image for GIF Converters. So, Let Us See How to Turn Images Into GIFs Very Quickly</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-from-apple-iphone-11-pro-without-password-by-drfone-ios/"><u>How to Delete iCloud Account From Apple iPhone 11 Pro without Password?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-ace-discord-conversations-with-effective-pinning-tips/"><u>In 2024, Ace Discord Conversations with Effective Pinning Tips</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-ultimate-guidelines-to-help-you-better-use-vlc-media-player/"><u>2024 Approved Ultimate Guidelines to Help You Better Use VLC Media Player</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/addressing-over-encoded-obs-media-for-2024/"><u>Addressing Over-Encoded OBS Media for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-itel-p55plus-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Itel P55+ to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-art-of-stability-fcpx-techniques-for-smoother-video/"><u>Updated The Art of Stability FCPX Techniques for Smoother Video</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/how-to-remove-background-music-from-video/"><u>How to Remove Background Music From Video?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-discover-the-top-5-mp3-tag-management-software-for-optimal-audio-organization-for-2024/"><u>New Discover the Top 5 MP3 Tag Management Software for Optimal Audio Organization for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-triple-check-for-profitability-guiding-principles-for-measuring-youtube-income/"><u>2024 Approved  Triple Check for Profitability  Guiding Principles for Measuring YouTube Income</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-making-an-impression-professional-pc-editing-strategies-for-youtube/"><u>In 2024, Making an Impression  Professional PC Editing Strategies for YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/opening-playing-and-organizing-your-srt-files-efficiently-for-2024/"><u>Opening, Playing, and Organizing Your SRT Files Efficiently for 2024</u></a></li>
</ul></div>
