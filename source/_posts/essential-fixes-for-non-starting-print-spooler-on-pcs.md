---
title: Essential Fixes for Non-Starting Print Spooler on PCs
date: 2024-06-28T07:06:06.322Z
updated: 2024-06-29T07:06:06.322Z
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
<li><a href="https://printer-issues.techidaily.com/installation-of-printer-finalized/"><u>Installation of Printer Finalized</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cured-printer-not-printing-on-epson-solved/"><u>Cured: Printer Not Printing on Epson [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-repaired-connectivity-issue/"><u>[PRINT] Repaired Connectivity Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-slow-printing-easily-and-quickly/"><u>How to Fix Slow Printing [Easily & Quickly]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-print-service-non-responsive/"><u>Solved: Print Service Non-Responsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-locate-missing-print-server-device/"><u>How to Locate Missing Print Server Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-transition-new-driver-for-your-hp-4630/"><u>Seamless Transition: New Driver for Your HP 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-scan-back-to-operational-state/"><u>Windows Scan: Back to Operational State</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-fix-achieved/"><u>B200 Fix Achieved</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-guide-to-creating-viral-whatsapp-status-videos/"><u>Updated The Ultimate Guide to Creating Viral WhatsApp Status Videos</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-12-pro-without-losing-any-content-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 12 Pro without Losing Any Content? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prime-pick-best-vr-devices-of-the-year/"><u>In 2024, Prime Pick  Best VR Devices of the Year</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-harnessing-luts-for-enhanced-visual-effects-in-ar-experiences/"><u>[New] Harnessing LUTs for Enhanced Visual Effects in AR Experiences</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-fast-track-video-scaling-for-perfect-mac-display/"><u>2024 Approved  Fast-Track Video Scaling for Perfect Mac Display</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-top-picks-for-snapchats-best-edits-on-both-smartphone-platforms-for-2024/"><u>[New] Top Picks for Snapchat's Best Edits on Both Smartphone Platforms for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-mastering-clear-sound-techniques-for-eliminating-audio-distortion-in-videos/"><u>2024 Approved Mastering Clear Sound Techniques for Eliminating Audio Distortion in Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-journey-of-rhythms-choreographing-tiktok-on-macos/"><u>[Updated] In 2024, Journey of Rhythms  Choreographing TikTok on MacOS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-art-of-video-clarity-with-version-22-vce-for-2024/"><u>Mastering the Art of Video Clarity with Version 2.2 VCE for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-upload-ubiquity-from-twitter-to-snapchat-videos-for-2024/"><u>[New] Upload Ubiquity  From Twitter to Snapchat Videos for 2024</u></a></li>
</ul></div>