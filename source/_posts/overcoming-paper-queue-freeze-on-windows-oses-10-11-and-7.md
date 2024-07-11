---
title: Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)
date: 2024-07-10T16:41:41.863Z
updated: 2024-07-11T16:41:41.863Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)
excerpt: This Article Describes Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)
keywords: Overcoming Paper Jams on Windows,Paper Jams Solutions in Windows Operating Systems,Troubleshooting Print Queue Errors,Prevent Paper Jams on Different Windows Versions,Efficient Paper Handling,Resolve Print Queue Issues,Paper Printing Troubleshooting
thumbnail: https://thmb.techidaily.com/19cc3daca0ae766efaf5a0d940f51eeacf8f6380658cff3e15c9f29d7f7d98eb.jpg
---

## Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)

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
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-reconfigured-wrongly/"><u>Gear-Up Glitch: Printer Reconfigured Wrongly?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-setup-brothers-mfc-9330cdw-fan/"><u>Guide to Setup Brother's MFC-9330CDW Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-the-mystery-of-non-printing-machines/"><u>Dismantling the Mystery of Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-post-windows-update-printer-workflow/"><u>Revived Post Windows Update Printer Workflow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-rev-fixes-resurrected-non-printing-printer/"><u>Win11 Rev Fixes: Resurrected Non-Printing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-intermittent-printer-spooler-halt-in-win-117/"><u>Resolving Intermittent Printer Spooler Halt in Win 11/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-link-between-printer-and-network/"><u>Re-Establishing Link Between Printer & Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-device-interaction-with-mf4770n-upgrade-in-windows-1187/"><u>Streamline Device Interaction with MF4770n Upgrade in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-your-canons-wireless-capability/"><u>Unlocking Your Canon's Wireless Capability</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-white-printouts-deciphering-the-epson-mishap/"><u>Endless White Printouts: Deciphering the Epson Mishap</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-ink-cartridge-disasters/"><u>Preventing Ink Cartridge Disasters</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-linked-in-seconds/"><u>Printer Linked in Seconds</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-print-spooler-keeps-stopping-on-windows-11-and-7/"><u>How to Fix Print Spooler Keeps Stopping on Windows 11 & 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-efficiency-printer-software-update-for-dell-and-win7/"><u>Enhance Efficiency: Printer Software Update for Dell & Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-for-finding-your-missing-printers-ip-address/"><u>Strategies for Finding Your Missing Printer's IP Address</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-cartridge-non-dispensing-errors/"><u>Correcting Cartridge Non-Dispensing Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-locate-missing-print-server-device/"><u>How to Locate Missing Print Server Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domain-services-unreachable-print-issue/"><u>Domain Services Unreachable, Print Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-cascading-error-messages-with-printers/"><u>Fixing Cascading Error Messages with Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-tech-merging-8720-printer-into-pc-system/"><u>Step by Step Tech: Merging 8720 Printer Into PC System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dj-1360-driver-issue-on-various-windows-os/"><u>DJ-1360 Driver Issue on Various Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-connection-routes-between-hp-printers-and-laptops/"><u>Enhanced Connection Routes Between HP Printers and Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-the-blank-page-mystery-in-printers/"><u>Clearing Up the Blank Page Mystery in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-the-cause-of-hp-printers-white-sheets/"><u>Zeroing In on the Cause of HP Printer’s White Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-hp-printing-issue-0xoxc4eb827f/"><u>Mending HP Printing Issue 0xOXC4EB827F</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/recording-revolution-tactics-for-extracting-live-data/"><u>Recording Revolution  Tactics for Extracting LIVE Data</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-mastering-facebook-video-covers-a-step-by-step-guide-to-sizing-for-2024/"><u>Updated Mastering Facebook Video Covers A Step-by-Step Guide to Sizing for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-fcp-x-green-screen-masterclass-from-basics-to-advanced/"><u>Updated 2024 Approved FCP X Green Screen Masterclass From Basics to Advanced</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-the-game-changer-for-tiktok-creators-advanced-editing-in-pro-tools-mac-edition/"><u>[Updated] 2024 Approved  The Game Changer for TikTok Creators  Advanced Editing in Pro Tools, Mac Edition</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-webp-converters-convert-webp-to-jpg-for-2024/"><u>Best WebP Converters  Convert WebP to JPG for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-samsung-galaxy-f34-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Samsung Galaxy F34 5G? Here is How | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-tecno-spark-10-pro-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Tecno Spark 10 Pro Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-converting-audio-files-like-a-pro-the-wav-converter-guide/"><u>In 2024, Converting Audio Files Like a Pro The Wav Converter Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-add-music-to-facebook-story-for-2024/"><u>[New] How to Add Music to Facebook Story for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ideal-steadicams-for-capturing-quality-uav-visuals/"><u>Ideal Steadicams for Capturing Quality UAV Visuals</u></a></li>
<li><a href="https://article-helps.techidaily.com/premium-mini-drones-for-enthusiasts/"><u>Premium Mini-Drones for Enthusiasts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/peeling-back-layers-the-hidden-meanings-of-everyday-emojis-for-2024/"><u>Peeling Back Layers  The Hidden Meanings of Everyday Emojis for 2024</u></a></li>
</ul></div>
