---
title: Combat Repeated Print Job Errors in Windows Operating Systems
date: 2024-06-28T07:04:12.505Z
updated: 2024-06-29T07:04:12.505Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Combat Repeated Print Job Errors in Windows Operating Systems
excerpt: This Article Describes Combat Repeated Print Job Errors in Windows Operating Systems
keywords: Fixing Printer Errors in Windows,Resolving Repeated Print Failures in Windows,Troubleshooting Print Job Interruptions in Windows,Stop Recurring Print Issues on Windows Operating Systems,Solutions for Persistent Print Problems in Windows OS,Overcoming Continuous Printer Errors in Windows 10/8/7,Preventing Repeated Print Job Failures in Microsoft Windows
thumbnail: https://thmb.techidaily.com/b715f9d9400fe89c8b9a306e0f9ed90d4ce3c93f7f901de6da9a82347225a712.jpg
---

## Combat Repeated Print Job Errors in Windows Operating Systems

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
<li><a href="https://printer-issues.techidaily.com/canon-printer-connection-made-easy-images-included/"><u>Canon Printer Connection Made Easy (Images Included)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-wasted-time-fixing-windows-78s-non-operational-spooler/"><u>Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-windows-11-printer-work-again/"><u>Make Windows 11 Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-relief-for-queued-print-tasks/"><u>Immediate Relief for Queued Print Tasks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systematic-mf4770n-software-enhancement-windows-wise/"><u>Systematic MF4770n Software Enhancement Windows-Wise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-epsons-error-x97/"><u>Addressing Epson's Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-error-code-b200/"><u>Mended Error Code: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-non-printing-in-canon-printers-windows-edition/"><u>Overcome Non-Printing in Canon Printers, Windows Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-streamlining-social-media-facebook-video-auto-play/"><u>[New] In 2024, Streamlining Social Media  Facebook Video Auto-Play</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-top-10-free-stock-footage-websites-you-should-know/"><u>[New] In 2024, Top 10 Free Stock Footage Websites You Should Know</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-create-amazing-slow-motion-videos-8-affordable-slow-motion-cameras/"><u>Updated Create Amazing Slow-Motion Videos 8 Affordable Slow-Motion Cameras</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-podcast-style-unboxing/"><u>2024 Approved  The Ultimate Guide to Podcast-Style Unboxing</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/create-amazing-slow-motion-videos-8-affordable-slow-motion-cameras/"><u>Create Amazing Slow-Motion Videos 8 Affordable Slow-Motion Cameras</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-eliminate-blur-in-zoom-calls-actionable-strategies/"><u>[Updated] 2024 Approved  Eliminate Blur in Zoom Calls – Actionable Strategies</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/onetization-contest-dailymovement-vs-youtubes-earnings-battleground/"><u>The Monetization Contest  DailyMovement vs Youtube's Earnings Battleground</u></a></li>
<li><a href="https://extra-tips.techidaily.com/quality-control-meets-creativity-exploring-top-18-cam-tools/"><u>Quality Control Meets Creativity  Exploring Top 18 Cam Tools</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nokia-c12-plus-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nokia C12 Plus to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-find-cricket-sound-effect/"><u>New In 2024, Find Cricket Sound Effect</u></a></li>
</ul></div>