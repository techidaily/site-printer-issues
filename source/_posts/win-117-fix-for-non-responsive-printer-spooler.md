---
title: Win 11/7 Fix for Non-Responsive Printer Spooler
date: 2024-06-28T07:17:25.146Z
updated: 2024-06-29T07:17:25.146Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Win 11/7 Fix for Non-Responsive Printer Spooler
excerpt: This Article Describes Win 11/7 Fix for Non-Responsive Printer Spooler
keywords: Win 11 Troubleshooting Guide,Printer Spooler Fix,Non-Responsive Printer Issues,Windows 11/7 Spooler Error,Fix Non-Responsive Printer,Resolve Windows 11/7 Printer Spooler Problems,How To Fix Non-Responsive Printer Spooler (Step by Step)
thumbnail: https://thmb.techidaily.com/d9427c61032284cb88ab156d6c103f9d31f7d2686f689f4e79141572fa04ae5d.jpg
---

## Win 11/7 Fix for Non-Responsive Printer Spooler

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
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-fixing-unable-to-add-hp-d1360-drivers-in-windows-oses/"><u>[Error Fixing] Unable to Add HP D1360 Drivers in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-wont-print-all-pages-2024-fix/"><u>Printers Won't Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversed-printing-mishaps-hp-printer-now-solid-and-sure/"><u>Reversed Printing Mishaps: HP Printer Now Solid and Sure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scan-activation-error-resolved-in-win11/"><u>Scan Activation Error Resolved in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-slow-printing-easily-and-quickly/"><u>How to Fix Slow Printing [Easily & Quickly]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-epson-workflow-flow/"><u>Restored Epson Workflow Flow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dont-let-offline-be-the-end-for-your-canon-printer/"><u>Don’t Let Offline Be the End for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-removal-of-external-printers/"><u>Effortless Removal of External Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-issue-mp620-driver-not-detected/"><u>[Windows Issue] MP620 Driver Not Detected</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-lore-of-roguelites-amidst-classic-rpgs/"><u>[Updated] The Lore of Roguelites Amidst Classic RPGs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-tier-designers-making-magic-in-discord-emojis/"><u>Top-Tier Designers  Making Magic in Discord Emojis</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-choosing-your-recording-champion-pick-obs-or-bandicam/"><u>In 2024, Choosing Your Recording Champion  Pick OBS or Bandicam?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-enhance-and-clean-up-youtube-footage-borderless-tutorial/"><u>[New] Enhance and Clean Up YouTube Footage  Borderless Tutorial</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-premium-sound-design-software-free-vs-paid-edition-focusing-on-linux-based-audio-editing-tools/"><u>Updated Premium Sound Design Software Free Vs. Paid Edition - Focusing on Linux-Based Audio Editing Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-leading-10-live-streaming-services/"><u>2024 Approved  Unveiling the Leading 10 Live-Streaming Services</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-datadeliverer-analyst-take/"><u>[Updated] DataDeliverer Analyst Take</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-poco-c51-drfone-by-drfone-android/"><u>How to Screen Mirroring Poco C51? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-windows-10-video-trimming-top-10-free-tools-you-need-to-know/"><u>In 2024, Windows 10 Video Trimming Top 10 Free Tools You Need to Know</u></a></li>
</ul></div>
