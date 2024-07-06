---
title: Steps to Stop and Resolve Printer Spooling Trouble
date: 2024-06-28T07:06:36.434Z
updated: 2024-06-29T07:06:36.434Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Steps to Stop and Resolve Printer Spooling Trouble
excerpt: This Article Describes Steps to Stop and Resolve Printer Spooling Trouble
keywords: Resolving Printer Spooler Issues,Printer Spooler Troubleshooting Guide,Stop Printer Spooling Errors,Prevent Printer Spooler Failures,How to Fix Spooler Problems on Printer,Printer Spooling Solution Steps,Troubleshoot Printer Spooler Malfunctions
thumbnail: https://thmb.techidaily.com/46df1e48b2f44db2d880f0d7735cdada8076c6dcb75637faff2a09a30c684309.jpg
---

## Steps to Stop and Resolve Printer Spooling Trouble

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
<li><a href="https://printer-issues.techidaily.com/tutorial-adding-hp-printer-to-computer-network/"><u>Tutorial: Adding HP Printer to Computer Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/process-for-adding-connecting-8720-printer-model-to-pc/"><u>Process for Adding: Connecting 8720 Printer Model to PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-shenanigans-unauthorized-printer-access/"><u>System Shenanigans: Unauthorized Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speeding-up-prints-simplest-fixes/"><u>Speeding Up Prints: Simplest Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-link-to-your-printer/"><u>Effortless Link to Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-troubles-try-these-5-simple-ways-to-help-your-canon-print-on-windows-11/"><u>Print Troubles? Try These 5 Simple Ways to Help Your Canon Print on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printing-with-simple-tips-for-canon-windows/"><u>Reignite Printing with Simple Tips for Canon, Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-gifify-your-twit-making-vids-free-and-flashy/"><u>2024 Approved  Gifify Your Twit  Making Vids Free & Flashy</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-video-channels-face-off-the-monetization-tale-of-two-titles/"><u>2024 Approved  Video Channels Face-Off  The Monetization Tale of Two Titles</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-whatsapp-status-editor-apps-our-top-picks/"><u>New In 2024, WhatsApp Status Editor Apps Our Top Picks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-chromebooks-ultimate-sniping-software-our-5-favorites/"><u>[New] In 2024, Chromebook's Ultimate Sniping Software  Our 5 Favorites</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitter-video-frame-changer/"><u>[Updated] 2024 Approved  Twitter Video Frame Changer</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-teenyscreenmugger-evaluation-insights-for-2024/"><u>[Updated] TeenyScreenMugger Evaluation Insights for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/list-of-pokemon-go-joysticks-on-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-fifa-scoreboard-tactics-in-infographics/"><u>Top FIFA Scoreboard Tactics in Infographics</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-hidden-narrators-of-fb-nuggets/"><u>[Updated] 2024 Approved  Hidden Narrators of FB Nuggets</u></a></li>
</ul></div>
