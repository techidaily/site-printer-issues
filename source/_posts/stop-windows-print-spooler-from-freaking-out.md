---
title: Stop Windows Print Spooler From Freaking Out
date: 2024-07-10T17:37:22.316Z
updated: 2024-07-11T17:37:22.316Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop Windows Print Spooler From Freaking Out
excerpt: This Article Describes Stop Windows Print Spooler From Freaking Out
keywords: Stop Windows Print Spooler Errors,Prevent Print Spooler Glitches,Fix Printer Spooler Issues,Resolve Windows Print Spooler Crashing,Stop Windows Print Service Disruption,Improve Print Spooler Performance,Troubleshoot Windows Print Spooler Failures
thumbnail: https://thmb.techidaily.com/f07bcde69983933cb76ff9d178455e2b69ef74b8fc7b5950817350ad54cf2512.png
---

## Stop Windows Print Spooler From Freaking Out

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
<li><a href="https://printer-issues.techidaily.com/overcoming-epsons-ink-failure/"><u>Overcoming Epson's Ink Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-network-print-problems/"><u>Resolving Network Print Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-the-frequent-failure-of-print-spooler-service/"><u>Resolving the Frequent Failure of Print Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-driver-update-win32-officejet-pro-8600-utility-bundle/"><u>Streamlined Driver Update: Win32 Officejet Pro 8600 Utility Bundle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guiding-through-printer-malfunction-fixes/"><u>Guiding Through Printer Malfunction Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-eliminating-pcl-xl-issues/"><u>Step-by-Step: Eliminating PCL XL Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-scanner-on-windows-11-os/"><u>Reviving Scanner on Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-canon-printer-a-visual-walkthrough/"><u>How to Set Up a Canon Printer: A Visual Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/updating-mf4770n-drivers-in-win11win8win7/"><u>Updating MF4770n Drivers in Win11/Win8/Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-connection-fix-canon-printer-offline/"><u>Restore Connection: Fix Canon Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-error-code-following-device-suspend-w7/"><u>[Solved] Printer Error Code Following Device Suspend, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-duplicate-printer-usage-detection/"><u>Resolved: Duplicate Printer Usage Detection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-interruptions-on-win7win10/"><u>Avoiding Constant Printer Service Interruptions on Win7/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-printing-success-setting-up-your-hp-smartoffice-x127e/"><u>Instant Printing Success: Setting Up Your HP SmartOffice X127e</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-win10-printer-performance-and-speed/"><u>Optimize WIN10 Printer Performance and Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574151519-canon-printer-is-offline-heres-how-to-fix-it/"><u>Canon Printer Is Offline? Here's How to Fix It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-errors-detected-during-printer-setup/"><u>No Errors Detected During Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-workspace-setup-with-easy-fixes-for-print-laptop-linkage/"><u>Revolutionizing Workspace Setup with Easy Fixes for Print-Laptop Linkage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstated-default-printer-post-error-0x00000709-fix/"><u>Reinstated Default Printer Post-Error 0X00000709 Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-scan-to-computer-is-no-longer-activated-on-windows-11/"><u>Solved: Scan to Computer Is No Longer Activated on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/tips-for-quickerslower-video-in-instagram-stories-for-2024/"><u>Tips for Quicker/Slower Video in Instagram Stories for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-players-showcased-10-mvps-on-tiktok-for-2024/"><u>[New] Top Players Showcased  10 MVPs on TikTok for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-compare-and-contrast-best-6-hdmi-monitor-models-in-detail/"><u>2024 Approved  Compare & Contrast  Best 6 HDMI Monitor Models in Detail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-the-lost-bluetooth-9-effective-solutions-to-find-your-connection/"><u>Win 11 and the Lost Bluetooth: 9 Effective Solutions to Find Your Connection</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-capture-and-store-5-best-ways-to-save-your-favorite-facebook-videos/"><u>[Updated] 2024 Approved  Capture & Store  5 Best Ways to Save Your Favorite Facebook Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleashing-creativity-essential-angles-in-mobile-shooting-for-2024/"><u>Unleashing Creativity  Essential Angles in Mobile Shooting for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-a-complete-breakdown-of-changing-discord-imagery/"><u>[Updated] A Complete Breakdown of Changing Discord Imagery</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-broadcasting-solo-youtube-live-from-your-smartphone/"><u>[Updated] 2024 Approved  Broadcasting Solo  YouTube Live From Your Smartphone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-6-plus-passcode-screen-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 6 Plus Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-prime-gold-toned-text-interactive-3d-sites-reviewed/"><u>In 2024, Prime Gold-Toned Text Interactive 3D Sites Reviewed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimal-series-premium-webcam-grips/"><u>2024 Approved  Optimal Series  Premium Webcam Grips</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ideal-8-support-systems-for-high-res-4k-cameras/"><u>Ideal 8 Support Systems for High Res 4K Cameras</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-meizu-21-pro-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/breakthrough-techniques-in-iphone-hdr-image-making-for-2024/"><u>Breakthrough Techniques in iPhone HDR Image Making for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beyond-basics-how-mondly-advanced-my-language-learning-top-10-insights/"><u>Beyond Basics: How Mondly Advanced My Language Learning - Top 10 Insights</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-step-by-step-guide-inserting-captions-in-instagram-clips-for-2024/"><u>[Updated] Step-by-Step Guide  Inserting Captions in Instagram Clips for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mac-users-top-4-choices-for-exquisite-music-editing-software-for-2024/"><u>Mac Users Top 4 Choices for Exquisite Music Editing Software for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-high-revenue-video-visionaries/"><u>2024 Approved  High-Revenue Video Visionaries</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-apple-iphone-14-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On Apple iPhone 14?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-roadmap-to-becoming-an-excellent-interviewer/"><u>In 2024, The Roadmap To Becoming An Excellent Interviewer</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-apple-iphone-6-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your Apple iPhone 6 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-how-to-rip-audio-from-videos-without-sacrificing-quality/"><u>Updated In 2024, How to Rip Audio From Videos without Sacrificing Quality</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-expert-guide-crafting-the-perfect-hdr-portrait-image/"><u>2024 Approved  Expert Guide  Crafting the Perfect HDR Portrait Image</u></a></li>
</ul></div>
