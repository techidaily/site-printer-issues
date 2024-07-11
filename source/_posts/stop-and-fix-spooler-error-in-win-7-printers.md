---
title: Stop and Fix Spooler Error in Win 7 Printers
date: 2024-07-10T16:40:41.351Z
updated: 2024-07-11T16:40:41.351Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop and Fix Spooler Error in Win 7 Printers
excerpt: This Article Describes Stop and Fix Spooler Error in Win 7 Printers
keywords: Stop Spooler Errors (High Relevance, Moderate Competition),Fix Spooler Error in Win 7 (Moderate Relevance, Low Competition),Spooler Issue Resolution for Printers (Medium Relevance, Medium Competition),Resolve Spooler Issues on Windows 7 (Medium Relevance, Medium Competition),Stop Spooler Errors in Printer Software (Low Relevance but Can Capture a Niche Audience),Troubleshoot Printer Spooler Problems in Win 7 (High Relevance and Specific to the Target Issue),Fix Spooling Error on Windows 7 Printers (Medium-High Relevance, Low Competition)
thumbnail: https://thmb.techidaily.com/97d52aeba0c3812671b16d9ad71aaf02069e7e610c93642b0ee7efd4388d9316.jpg
---

## Stop and Fix Spooler Error in Win 7 Printers

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
<li><a href="https://printer-issues.techidaily.com/missing-network-printer-how-to-restore-visibility/"><u>Missing Network Printer - How to Restore Visibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-win-os-no-printer-driver-found/"><u>[ERROR] Win OS - No Printer Driver Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-troubleshoot-unseen-network-printer-on-windows-pcs/"><u>[OS Troubleshoot] Unseen Network Printer on Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-sibling-print-device-from-online-standby-mode/"><u>Reviving Sibling Print Device From Online Standby Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-print-speed-and-quality-download-hp-officejet-firmware/"><u>Boost Print Speed & Quality - Download HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/directions-assembling-hp-print-with-your-pc/"><u>Directions: Assembling HP Print with Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-toner-depletion-crisis/"><u>Curing Toner Depletion Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-error-messages-in-epson-units/"><u>Fixing Error Messages in Epson Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inactive-scanner-on-windows-11/"><u>Overcoming Inactive Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/improve-printers-pace-at-a-glance/"><u>Improve Printer's Pace at a Glance</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-paper-size-error-on-hp-deskjet-3070/"><u>Fixed Paper Size Error on HP DeskJet 3070</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-solutions-for-brother-printer-print-problems-in-windows-1011/"><u>Quick Solutions for Brother Printer Print Problems in Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-tactics-to-overcome-non-printing-brother-printer-in-oses/"><u>Precision Tactics to Overcome Non-Printing Brother Printer in OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-unfreeze-an-offline-brother-printer-online/"><u>How To Unfreeze an Offline Brother Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-restarting-brother-printer-for-windows/"><u>Troubleshooting: Restarting Brother Printer for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-duplicate-printer-usage-detection/"><u>Resolved: Duplicate Printer Usage Detection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-worklift-printer-setup-and-use/"><u>HP WorkLift Printer Setup and Use</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-canon-print-failure-on-windows-10-effectively/"><u>Solve Canon Print Failure on Windows 10 Effectively</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugged-reset-to-bring-canon-printer-back-online/"><u>Unplugged? Reset to Bring Canon Printer Back Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-print-for-office-hp-devices/"><u>Enabling Duplex Print for Office HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/journeys-end-successfully-setting-up-hp-printer-in-win-os/"><u>Journey's End: Successfully Setting Up HP Printer in Win OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-error-only-blank-sheets-from-epson/"><u>Printer Setup Error: Only Blank Sheets From Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-stopped-printing-fixed-now/"><u>HP LaserJet Stopped Printing - Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-disconnected-swift-fix/"><u>Printer Disconnected: Swift Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-connection-of-print-device/"><u>Successful Connection of Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-connectivity-restored/"><u>[PRINT] Connectivity Restored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventative-measures-against-spooler-shutdowns-win/"><u>Preventative Measures Against Spooler Shutdowns (Win)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-discovering-the-best-practices-for-a-bigger-roi-with-fb-videos/"><u>[New] Discovering the Best Practices for a Bigger ROI with FB Videos</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-best-5-multitasking-visual-and-audio-producers/"><u>2024 Approved  Best 5 Multitasking Visual & Audio Producers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-infusing-life-into-ppt-with-professional-voiceovers/"><u>[New] 2024 Approved  Infusing Life Into PPT with Professional Voiceovers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-djd-snaps-adding-tracks-to-enhance-videos/"><u>In 2024, DJ'd Snaps  Adding Tracks to Enhance Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-listen-to-podcasts-on-your-iphone/"><u>[New] How to Listen to Podcasts on Your iPhone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-efficiently-incorporate-youtube-playlists-for-engaging-pages/"><u>[Updated] In 2024, Efficiently Incorporate YouTube Playlists for Engaging Pages</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-top-15-best-free-mp4-video-rotators-windows-mac-android-iphone-and-online-for-2024/"><u>Updated Top 15 Best Free MP4 Video Rotators Windows, Mac， Android, iPhone & Online for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-infinix-smart-8-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-10-most-popular-free-gaming-platforms-for-pc-and-android-for-2024/"><u>Updated 10 Most Popular Free Gaming Platforms for PC and Android for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-oppo-f23-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Oppo F23 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-live-gaming-recording-battle-pick-your-preference-obs-or-shadowplay-for-2024/"><u>[Updated] Live Gaming Recording Battle  Pick Your Preference, OBS or ShadowPlay for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/quintessential-fps-experiences-ranked-by-fun-factor-for-2024/"><u>Quintessential FPS Experiences Ranked by Fun Factor for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-maximizing-audio-capture-essential-techniques-for-facetime-for-2024/"><u>[New] Maximizing Audio Capture  Essential Techniques for FaceTime for 2024</u></a></li>
</ul></div>
