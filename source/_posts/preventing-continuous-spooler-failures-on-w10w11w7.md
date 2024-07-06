---
title: Preventing Continuous Spooler Failures on W10/W11/W7
date: 2024-06-28T07:05:37.166Z
updated: 2024-06-29T07:05:37.166Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventing Continuous Spooler Failures on W10/W11/W7
excerpt: This Article Describes Preventing Continuous Spooler Failures on W10/W11/W7
keywords: Continuous Spooler Troubleshooting,Windows 10/11/7 Spooler Fixes,Spooler Failure Solutions for W10/W11/W7,Prevent Spooler Crashes in W10/W11/W7,Windows 7/8/10 Spooler Stability,Spooler Failure Fixes for W7/8/10,Optimize Spooler Performance in Windows 10/11/7
thumbnail: https://thmb.techidaily.com/0b50962ffa3e17ae709bef162c3f8ff4d960cae116eaf3e790989364bc8da0ce.jpg
---

## Preventing Continuous Spooler Failures on W10/W11/W7

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
<li><a href="https://printer-issues.techidaily.com/scanner-activation-a-win10-fix-guide/"><u>Scanner Activation: A Win10 Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-spooler-error-affects-print-output/"><u>[WARNING] Spooler Error Affects Print Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-not-printing-conquer-this-issue-with-our-top-5-solutions-for-windows-11/"><u>Canon Printer Not Printing? Conquer This Issue with Our Top 5 Solutions for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-print-service-not-starting-correctly/"><u>[WARNING] Print Service Not Starting Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-stopped-working-after-windows-10-update/"><u>SOLVED: Printer Stopped Working After Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-constant-spooler-pauses-across-win-versions/"><u>Eliminate Constant Spooler Pauses Across Win Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-searches-but-not-finding-canon-mp620-printer-driver/"><u>Windows Searches but Not Finding: Canon MP620 Printer Driver</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-nokia-xr21-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Nokia XR21 to Another | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-converting-files-is-easy-with-the-right-tools-and-likewise-gif-to-jpg-conversion-is-choose-the-best-tool-and-get-the-expected-results-within-the-blink-o/"><u>New Converting Files Is Easy with the Right Tools, and Likewise, GIF to JPG Conversion Is. Choose the Best Tool and Get the Expected Results Within the Blink of an Eye</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-oppo-find-x6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/step-up-your-melody-game-with-these-top-20-youtube-music-sources/"><u>Step Up Your Melody Game with These Top 20 YouTube Music Sources</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-capturing-the-essence-of-facetime-on-facebook/"><u>In 2024, Capturing the Essence of FaceTime on Facebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleash-the-power-of-windows-11s-media-importer-tools-for-2024/"><u>Unleash the Power of Windows 11'S Media Importer Tools for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-vivo-v27-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Vivo V27 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-mastermind-mind-games-trivia-channel-hunt-for-24/"><u>[New] 2024 Approved  Mastermind Mind Games - Trivia Channel Hunt for '24</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-most-suitable-chromebook-friendly-audio-editing-software-for-modern-musicians-top-8-list-updated/"><u>Updated The Most Suitable Chromebook-Friendly Audio Editing Software for Modern Musicians (Top 8 List, Updated )</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-are-you-looking-to-remove-echo-in-premiere-pro-please-look-at-our-guide-for-advice-and-suggestions-on-getting-the-best-possible-outcomes-for-2024/"><u>New Are You Looking to Remove Echo in Premiere Pro? Please Look at Our Guide for Advice and Suggestions on Getting the Best Possible Outcomes for 2024</u></a></li>
</ul></div>
