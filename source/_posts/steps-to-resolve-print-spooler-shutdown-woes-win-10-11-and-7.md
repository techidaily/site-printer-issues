---
title: Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)
date: 2024-07-10T17:15:04.538Z
updated: 2024-07-11T17:15:04.538Z
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
<li><a href="https://printer-issues.techidaily.com/updated-system-disabled-printer-reports/"><u>Updated System, Disabled Printer Reports</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/managing-paper-tray-sensor-problems/"><u>Managing Paper Tray Sensor Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-removal-guide-for-external-devices/"><u>Win Removal Guide for External Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-installation-made-simple-image-driven/"><u>Canon Printer Installation Made Simple (Image-Driven)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/saving-day-printer-function-reclaimed-post-update-crisis/"><u>Saving Day: Printer Function Reclaimed Post-Update Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-v305-aio-printer-driver-update-in-windows-7/"><u>Dell V305 AIO Printer Driver Update in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/process-for-adding-connecting-8720-printer-model-to-pc/"><u>Process for Adding: Connecting 8720 Printer Model to PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reach-new-horizons-in-printer-functionality-4630-driver-upgrade-guide/"><u>Reach New Horizons in Printer Functionality: 4630 Driver Upgrade Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dead-paper-output-in-hp-printers/"><u>Fixing Dead Paper Output in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/confused-settings-your-printer-misconfigured/"><u>Confused Settings: Your Printer Misconfigured</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-non-response-solved-windows-9x-fix-guide/"><u>HP Printer Non-Response Solved: Windows 9X Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-silent-canon-printer/"><u>Reviving a Silent Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-wireless-printing-issue-with-hp-envy-5680v5/"><u>Fixed Wireless Printing Issue with HP Envy 5680V5</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-functionality-upgrading-mf4770n-on-w11w8w7-os/"><u>Optimize Functionality: Upgrading MF4770n on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-output-v305-aio-driver-enhancement-in-win7/"><u>Boost Your Output: V305 AIO Driver Enhancement in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-ink-cartridge-errors-in-printers/"><u>Decoding Ink Cartridge Errors in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-with-hp-print-on-w7-resolved/"><u>Connectivity Woes with HP Print on W7 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-full-potential-of-hp-printers-in-windows/"><u>Unlocking the Full Potential of HP Printers in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574049626-fix-print-job-stuck-in-queue-quickly/"><u>Fix 'Print Job Stuck in Queue' Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-non-responsive-printer-service-windows/"><u>Immediate Fixes for Non-Responsive Printer Service (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcame-ink-depletion-problem-in-hp-officejet/"><u>Overcame Ink Depletion Problem in HP Officejet</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-nozzle-necessity-neglected/"><u>Post-Update, Nozzle Necessity Neglected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-installation-of-upgraded-printer-drivers/"><u>Correct Installation of Upgraded Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-overcome-unresponsive-hp-devices/"><u>Strategies to Overcome Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-elimination-windows-printer-setback-0x00000709/"><u>Error Elimination: Windows Printer Setback (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-jams-and-more-win810-hp-printer-help-needed/"><u>Paper Jams & More: Win8/10 HP Printer Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-windows-hp-printer-offline/"><u>Resolving Windows HP Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-printer-alert/"><u>Fixing: Offline PRINTER Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-performance-officejet-pro-8600-driver-for-windows/"><u>Enhanced Performance: Officejet Pro 8600 Driver for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-due-to-current-domain-services-outage/"><u>Print Issue Due to Current Domain Services Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-printer-driver-bugs-in-win10/"><u>Address Printer Driver Bugs in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-imprinter-malfunctions-in-windows-11/"><u>Address Imprinter Malfunctions in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-print-services-for-your-canon-device/"><u>Reclaiming Print Services for Your Canon Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-link-your-laptop-and-hp-printer-with-these-fixes/"><u>Effortlessly Link Your Laptop and HP Printer with These Fixes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-gamings-finest-top-12-tycoon-games-ensuring-hours-of-fun/"><u>[New] 2024 Approved  Gaming's Finest - Top 12 Tycoon Games Ensuring Hours of Fun</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-xs-max-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone XS Max in the Best Ways</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-content-delivery-assessment/"><u>2024 Approved  Exclusive Content Delivery Assessment</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Xiaomi 13T Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/concealed-video-streaming-background-youtube-watch/"><u>Concealed Video Streaming  Background YouTube Watch</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlock-optimal-performance-with-these-key-tricks/"><u>[Updated] Unlock Optimal Performance with These Key Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-not-just-carjacking-fun-the-best-non-gta-games/"><u>[New] Not Just Carjacking Fun  The Best Non-GTA Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-navigate-meeting-arrangements-with-zoom-ease/"><u>[Updated] In 2024, Navigate Meeting Arrangements with Zoom Ease</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-how-to-fade-audio-in-lumafusion/"><u>[Updated] How To Fade Audio In Lumafusion</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-elite-psd-text-flourishes/"><u>[Updated] Elite PSD Text Flourishes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/audience-alchemy-converting-shorts-to-sensations-for-2024/"><u>Audience Alchemy  Converting Shorts to Sensations for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-from-audio-to-words-on-youtube-a-comprehensible-free-guide/"><u>[New] From Audio to Words on YouTube  A Comprehensible Free Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-5-best-ps1-emulators-for-pc/"><u>[Updated] 2024 Approved  5 Best PS1 Emulators for PC</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-next-level-content-creation-tools-post-vimeo/"><u>[New] Next-Level Content Creation Tools, Post-Vimeo</u></a></li>
</ul></div>
