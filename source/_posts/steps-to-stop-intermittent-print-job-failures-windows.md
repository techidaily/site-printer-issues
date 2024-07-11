---
title: Steps to Stop Intermittent Print Job Failures (Windows)
date: 2024-07-10T17:32:07.365Z
updated: 2024-07-11T17:32:07.365Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Steps to Stop Intermittent Print Job Failures (Windows)
excerpt: This Article Describes Steps to Stop Intermittent Print Job Failures (Windows)
keywords: Stop Intermittent Print Jobs,Windows Printer Troubleshooting,Print Job Failure Fix,Intermittent Printing Issues Windows,Stop Printer Errors (Windows),Windows Print Problem Solutions,Resolve Intermittent Printer Failure (Windows)
thumbnail: https://thmb.techidaily.com/99d21901c046ee167dc651651f4c0a4a5fcaa0180bc67e42c2265df29bcc90c2.png
---

## Steps to Stop Intermittent Print Job Failures (Windows)

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
<li><a href="https://printer-issues.techidaily.com/windows-10-printer-spooler-non-responsive/"><u>Windows 10 Printer Spooler Non-Responsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-snafu-printer-configuration-gone-awry/"><u>Technical Snafu: Printer Configuration Gone Awry</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-w11-printer-response-times/"><u>Enhance W11 Printer Response Times</u></a></li>
<li><a href="https://printer-issues.techidaily.com/master-brother-printer-print-issues-a-win1011-fix-guide/"><u>Master Brother Printer Print Issues: A Win10/11 Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversed-printing-mishaps-hp-printer-now-solid-and-sure/"><u>Reversed Printing Mishaps: HP Printer Now Solid and Sure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-missing-hp-support-in-windows-1110/"><u>[Print] Missing HP Support in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-advice-make-hidden-network-printer-visible-again/"><u>[Windows Advice] Make Hidden Network Printer Visible Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-printers-availability-with-these-tips/"><u>Regain Printer's Availability with These Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-single-printer-page-solution/"><u>Print Every Single Printer Page [Solution]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-upgrade-instructions/"><u>HP Printer Driver, Upgrade Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-printer-error-what-windows-users-can-do/"><u>Network Printer Error: What Windows Users Can Do</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/method-linking-hp-printer-to-personal-computer/"><u>Method: Linking HP Printer to Personal Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-inkjet-4630-firmware-enhancement-guide/"><u>HP Inkjet 4630 Firmware Enhancement Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-turn-on-your-disconnected-canon-printer/"><u>Quick Guide: Turn On Your Disconnected Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-intermittent-printing-on-hp-deskjet-305dn/"><u>Fixed Intermittent Printing on HP DeskJet 305Dn</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-0x97-unravelled-and-solved/"><u>Epson 0X97 - Unravelled & Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-steps-for-windows-11/"><u>Printer Not Responding: Steps for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-clogged-toner-cartridges/"><u>Addressing Clogged Toner Cartridges</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hasten-printer-job-advancement/"><u>Hasten Printer Job Advancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breakthrough-techniques-joining-your-laptop-and-hp-in-156-characters-or-less/"><u>Breakthrough Techniques: Joining Your Laptop and HP in 156 Characters or Less</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-correct-unresponsive-hp-color-copiers/"><u>Strategies to Correct Unresponsive HP Color Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-of-the-line-for-non-printed-pages/"><u>End of the Line for Non-Printed Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-not-responding/"><u>Mended Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-solving-epson-printing-anomalies/"><u>Understanding and Solving Epson Printing Anomalies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-officejet-paper-jams-step-by-step-solution/"><u>Win11 OfficeJet Paper Jams: Step-by-Step Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-inkjet-non-operational/"><u>Repaired Inkjet Non-Operational</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systematic-update-for-enhanced-mf4770n-performance-windows/"><u>Systematic Update for Enhanced MF4770n Performance Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-removal-guide-for-external-devices/"><u>Win Removal Guide for External Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/break-free-from-stuck-print-queue/"><u>Break Free From Stuck Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compreeed-software-bundle-officejet-pro-8600-windows-integration/"><u>Compreeed Software Bundle: OfficeJet Pro 8600, Windows Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-ink-cartridge-disasters/"><u>Preventing Ink Cartridge Disasters</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-compatible-with-online-scanner-again/"><u>Win11 Compatible with Online Scanner Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-hp-printers-critical-error-0xoxc4eb827f/"><u>Correcting HP Printer's Critical Error 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-service-disabled-trouble-in-windows/"><u>Printer Service Disabled: Trouble in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-and-propel-printers-fast/"><u>Unblock and Propel Printers Fast</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-captivating-content-creation-the-best-10-igtv-strategies-for-brands/"><u>[New] Captivating Content Creation  The Best 10 IGTV Strategies for Brands</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-pause-perfection-how-to-freeze-frame-in-videos-like-a-pro/"><u>2024 Approved Pause Perfection How to Freeze Frame in Videos Like a Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-snickel-and-snicker-5-best-meme-generating-apps/"><u>In 2024, Snickel & Snicker  5 Best Meme Generating Apps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-snapshotpro-365-year-round-windowsmac-snapshots-for-2024/"><u>[New] SnapshotPro 365  Year-Round Windows/Mac Snapshots for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/end-live-recording-mode-immediately-in-qt-app-for-2024/"><u>End Live Recording Mode Immediately in QT App for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-v29e-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo V29e to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-funniest-punchlines-reddit-vs-twitter-memes-for-2024/"><u>[Updated] Funniest Punchlines  Reddit Vs. Twitter Memes for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-effortless-video-editing-8-top-picks-for-low-cost-hardware/"><u>New 2024 Approved Effortless Video Editing 8 Top Picks for Low-Cost Hardware</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/avoidance-techniques-no-more-fb-vlogs/"><u>Avoidance Techniques  No More FB Vlogs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-simplify-your-workflow-gopro-quik-video-editing-made-easy-on-macbook-for-2024/"><u>New Simplify Your Workflow GoPro Quik Video Editing Made Easy on MacBook for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-earnings-empire-constructing-a-profitable-youtube-channel-for-2024/"><u>[New] Earnings Empire  Constructing a Profitable YouTube Channel for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/direct-screens-capture-chromeos-edition-for-2024/"><u>Direct Screens Capture ChromeOS Edition for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hero-session-generations-compared/"><u>In 2024, Hero Session Generations Compared</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-high-quality-sound-recording-via-audacity-for-2024/"><u>The Art of High-Quality Sound Recording via Audacity for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-discovering-ideal-hashtags-for-your-youtube-videos-for-2024/"><u>[New] Discovering Ideal Hashtags for Your YouTube Videos for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/streamline-your-workflow-with-the-top-5-pc-screen-grabbers/"><u>Streamline Your Workflow with the Top 5 Pc Screen Grabbers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-infinix-smart-7-hd-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Infinix Smart 7 HD Unlock Without Password</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unlock-efficiency-the-editors-guide-to-speed-control/"><u>2024 Approved  Unlock Efficiency  The Editor's Guide to Speed Control</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-easy-techniques-for-archiving-group-discussions/"><u>In 2024, Easy Techniques for Archiving Group Discussions</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-installing-windows-movie-maker-a-detailed-download-and-setup-tutorial/"><u>Updated In 2024, Installing Windows Movie Maker A Detailed Download and Setup Tutorial</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-most-immersive-iphone-vr-games-ever-for-2024/"><u>[New] The Most Immersive iPhone VR Games Ever for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-iphone-14-pro-max-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass iPhone 14 Pro Max Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimizing-inner-spaces-with-sunshine-for-2024/"><u>Optimizing Inner Spaces with Sunshine for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-make-your-facebook-profile-cover-video-more-attractive/"><u>[Updated] How to Make Your Facebook Profile Cover Video More Attractive</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/add-music-to-gif-on-win-for-2024/"><u>Add Music To Gif On Win for 2024</u></a></li>
</ul></div>
