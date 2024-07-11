---
title: Troubleshooting Non-Starting Spooler on Your PC (Windows)
date: 2024-07-10T16:58:19.755Z
updated: 2024-07-11T16:58:19.755Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Troubleshooting Non-Starting Spooler on Your PC (Windows)
excerpt: This Article Describes Troubleshooting Non-Starting Spooler on Your PC (Windows)
keywords: Windows Spooler Troubleshooting Guide,Fix Non-Starting Spooler (Windows),How to Troubleshoot Windows Services,Fixing Spooler Service Failure (Windows),Windows Spooler Errors Resolution,Reasons for Non-Starting Windows Spooler,Troubleshoot Spooler Service (Windows)
thumbnail: https://thmb.techidaily.com/db339cfb71ad17e704275f446976657b74bdf593b2c3464a856c74dd3bbe549b.jpg
---

## Troubleshooting Non-Starting Spooler on Your PC (Windows)

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
<li><a href="https://printer-issues.techidaily.com/tackle-printer-connectivity-issues-in-w11/"><u>Tackle Printer Connectivity Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/joining-process-attaching-hp-officejet-to-desktop-pcs/"><u>Joining Process: Attaching HP Officejet to Desktop PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-compatibility-boosting-mf4770n-performance-in-win11win8w7/"><u>Enhance Compatibility: Boosting MF4770n Performance in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-unresponsive-hp-devices/"><u>Troubleshooting Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-b200-pc-error/"><u>Resolved: B200 PC Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-local-print-spooler-service-not-running-on-windows/"><u>[SOLVED] Local Print Spooler Service Not Running on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-error-unable-to-locate-printer-drivers/"><u>[WIN ERROR] Unable to Locate Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigate-and-rectify-brother-printer-not-print-issue-on-windows-10/"><u>Navigate and Rectify Brother Printer Not Print Issue on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-manual-hp-smartoffice-800-series/"><u>Installation Manual: HP SmartOffice 800 Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-driver-missing-please-help/"><u>Canon Pixma MP620: Driver Missing, Please Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-halting-repeated-print-job-errors-windows/"><u>Quick Guide: Halting Repeated Print Job Errors (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-canon-printer-to-wifi-easily/"><u>How to Connect Canon Printer to Wifi Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-your-brother-printer-to-print-on-windows-1011-successfully/"><u>Enable Your Brother Printer to Print on Windows 10/11 Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-unresponsive-xp-printer-jobs-without-delay/"><u>Fix Unresponsive XP Printer Jobs Without Delay</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-install-a-new-canon-printer-step-by-step/"><u>How To Install a New Canon Printer (Step-by-Step)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-w11-scanner-output-issues/"><u>Fix W11 Scanner Output Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-blank-pages-on-active-epson/"><u>No More Blank Pages on Active Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-printers-victory-over-the-white-paper-plague/"><u>A Printer's Victory Over the White Paper Plague</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-white-sheet-saga-with-hp-printer-fix/"><u>Ending White Sheet Saga with HP Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secret-behind-empty-printouts/"><u>Unveiling the Secret Behind Empty Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-connection-routes-between-hp-printers-and-laptops/"><u>Enhanced Connection Routes Between HP Printers and Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inability-to-print-in-full-colors/"><u>Inability to Print in Full Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-driver-compatibility-with-multiple-windows-oses/"><u>HP Deskjet D1360 Driver Compatibility with Multiple Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-inkjet-workflows-new-printer-software-update-for-windows-7/"><u>Streamline Inkjet Workflows: New Printer Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-laser-printer-errors/"><u>Decoding Laser Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-stuck-printer-operations/"><u>Accelerate Stuck Printer Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-all-pages-print-glitch/"><u>Fix All-Pages Print Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-repairs-for-pcl-xl-glitches/"><u>Streamlining Repairs for PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573904602-local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fault-ad-services-out-of-service/"><u>Printer Fault: AD Services Out of Service</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-creating-impactful-youtube-conclusion/"><u>[Updated] In 2024, Creating Impactful YouTube Conclusion</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-aggregated-compendium-of-podcast-publishing-services/"><u>Updated Aggregated Compendium of Podcast Publishing Services</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-list-of-windows-movie-maker-substitutes/"><u>The Ultimate List of Windows Movie Maker Substitutes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-cracking-the-code-of-true-instagram-photos/"><u>[Updated] 2024 Approved  Cracking the Code of True Instagram Photos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-the-insiders-guide-to-tiktok-wealth-filmora-edition-for-2024/"><u>[Updated] The Insider's Guide to TikTok Wealth - Filmora Edition for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-tecno-camon-20-pro-5g-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Tecno Camon 20 Pro 5G.</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-captivating-content-top-three-channel-growth-strategies-for-2024/"><u>[New] Captivating Content  Top Three Channel Growth Strategies for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-jumpstart-your-recording-with-this-obs-mac-setup-guide/"><u>[New] 2024 Approved  Jumpstart Your Recording with This OBS Mac Setup Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-ultimate-guide-to-live-video-comparing-obs-and-twitch-studio/"><u>The Ultimate Guide to Live Video  Comparing OBS & Twitch Studio</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-top-gaming-destinations-on-android-the-elite-15-simulations/"><u>2024 Approved  Top Gaming Destinations on Android  The Elite 15 Simulations</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-monochrome-to-masterpiece-pro-photo-hue-harmony/"><u>From Monochrome to Masterpiece  Pro Photo Hue Harmony</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-best-asmr-youtube-channels-for-2024/"><u>The Best ASMR YouTube Channels for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-finding-solid-video-editing-software-can-be-hard-thankfully-we-have-produced-a-top-five-list-of-the-best-free-mp4-video-editing-toolscheck-now/"><u>2024 Approved Finding Solid Video Editing Software Can Be Hard. Thankfully, We Have Produced a Top Five List of the Best Free MP4 Video Editing tools.Check Now</u></a></li>
</ul></div>
