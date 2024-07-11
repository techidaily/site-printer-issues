---
title: "Troubleshooting Windows XP/11: Non-Stopping Print Service"
date: 2024-07-10T17:02:09.849Z
updated: 2024-07-11T17:02:09.849Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Troubleshooting Windows XP/11: Non-Stopping Print Service"
excerpt: "This Article Describes Troubleshooting Windows XP/11: Non-Stopping Print Service"
keywords: Windows XP Print Service Troubleshooting,Windows 11 Non-Stopping Print Service Fixes,Resolve Windows XP/11 Print Errors,Uninterrupted Print Service for Windows XP,Stop Non-Stopping Print Service on Windows 11,Windows XP/11 Print Issues Guide,Print Service Error Handling for Windows XP/11
thumbnail: https://thmb.techidaily.com/d558a627b87b79877888fadd197a60bce9f9f188240e22025a6fa593d0f053ec.jpg
---

## Troubleshooting Windows XP/11: Non-Stopping Print Service

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
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-11/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-dell-printer-offline-error-on-windows-7/"><u>Resolved Dell Printer Offline Error on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-network-printer/"><u>Successfully Installed Network Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-your-printing-experience-with-canon-windows-10-tips/"><u>Enhance Your Printing Experience with Canon, Windows 10 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/gone-are-the-days-of-missing-printer-pages/"><u>Gone Are The Days of Missing Printer Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-intermittent-printer-spooler-halt-in-win-117/"><u>Resolving Intermittent Printer Spooler Halt in Win 11/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disconnecting-all-print-devices-at-once-on-pc/"><u>Disconnecting All Print Devices at Once on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-pcs-no-printer-icon-heres-what-to-do/"><u>Windows PCs, No Printer Icon? Here's What to Do</u></a></li>
<li><a href="https://printer-issues.techidaily.com/top-five-solutions-to-resolve-your-canon-printer-not-printing-issue-in-windows-11/"><u>Top Five Solutions to Resolve Your Canon Printer Not Printing Issue in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expediting-clogged-print-order/"><u>Expediting Clogged Print Order</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-manual-hp-smartoffice-800-series/"><u>Installation Manual: HP SmartOffice 800 Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-inkjet-fix-successful/"><u>Win7 Inkjet Fix Successful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-canon-printer-a-visual-walkthrough/"><u>How to Set Up a Canon Printer: A Visual Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-no-connection-detected/"><u>Resolved: PRINTER No Connection Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantaneous-fix-guide-unwinding-pcl-xl-errors/"><u>Instantaneous Fix Guide: Unwinding PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-your-canon-printer-an-illustrated-tutorial/"><u>Installing Your Canon Printer - An Illustrated Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-snafu-printer-configuration-gone-awry/"><u>Technical Snafu: Printer Configuration Gone Awry</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printer-output-5-effective-steps-for-non-printing-canon-on-windows-11/"><u>Reignite Printer Output: 5 Effective Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-cannot-set-default-printer-on-windows-solved/"><u>Error 0X00000709 Cannot Set Default Printer on Windows [Solved]</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-unveiling-top-5-mac-snippet-applications/"><u>In 2024, Unveiling Top 5 Mac Snippet Applications</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-samsung-galaxy-m34-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, The Best iSpoofer Alternative to Try On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-stepwise-approach-to-mastering-vimeo-recording/"><u>[New] Stepwise Approach to Mastering Vimeo Recording</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-effortlessly-run-apps-and-videos-together-in-chrome/"><u>In 2024, How to Effortlessly Run Apps & Videos Together In Chrome</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mp4s-melodic-mysteries-solved-nine-easy-to-implement-audio-extraction-methods-for-the-new-decade/"><u>MP4s Melodic Mysteries Solved Nine Easy-to-Implement Audio Extraction Methods for the New Decade</u></a></li>
<li><a href="https://extra-information.techidaily.com/joining-the-zoom-community-with-ease-on-an-android-device/"><u>Joining the Zoom Community with Ease on an Android Device</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-pioneering-poetic-presentations-in-motion-graphics/"><u>2024 Approved Pioneering Poetic Presentations in Motion Graphics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-tecno-camon-20-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Tecno Camon 20 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-unleash-high-definition-content-with-youtubes-av1-feature/"><u>[Updated] 2024 Approved  Unleash High-Definition Content with YouTube’s AV1 Feature</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-2024-approved-best-10-free-and-best-text-to-speech-generators/"><u>New 2024 Approved Best 10 Free and Best Text-to-Speech Generators</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-crafting-a-winning-live-broadcast-essentials-and-strategies/"><u>In 2024, Crafting a Winning Live Broadcast  Essentials and Strategies</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Nokia G42 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-master-your-youtube-settings-stop-auto-play-videos/"><u>[Updated] Master Your YouTube Settings - Stop Auto-Play Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-laying-down-an-elegant-tiktok-credits-panel/"><u>[New] Laying Down an Elegant TikTok Credits Panel</u></a></li>
</ul></div>
