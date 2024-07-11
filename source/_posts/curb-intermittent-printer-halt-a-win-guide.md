---
title: "Curb Intermittent Printer Halt: A Win Guide"
date: 2024-07-10T16:47:56.899Z
updated: 2024-07-11T16:47:56.899Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Curb Intermittent Printer Halt: A Win Guide"
excerpt: "This Article Describes Curb Intermittent Printer Halt: A Win Guide"
keywords: Intermittent Printer Issues,How to Fix Print Halt Errors,Printer Troubleshooting Guide,Print Device Recovery Tips,Curbing Printer Errors Effectively,Best Practices for Print Management,Avoiding Printer Malfunctions
thumbnail: https://thmb.techidaily.com/e2b7342586f1532a636225d5506546a483f2a235bec60ba0d26a57d5b805db19.jpg
---

## Curb Intermittent Printer Halt: A Win Guide

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
<li><a href="https://printer-issues.techidaily.com/swift-printer-performance-tips/"><u>Swift Printer Performance Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-mended-hp-printer-no-output/"><u>Successfully Mended HP Printer No Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-right-hp-d1360-print-drivers-in-windows-ecosystems/"><u>Finding the Right HP D1360 Print Drivers in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-needed-mp620-printer-not-detected-in-windows-os/"><u>[Solution Needed] MP620 Printer Not Detected in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-canon-printer-fixes-for-windows-users/"><u>Effortless Canon Printer Fixes for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-windows-7-software-for-dell-inkjet-aios/"><u>Cutting Edge: Windows 7 Software for Dell Inkjet AIOs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-setup-for-officejet-pro-m110-series-a-complete-walkthrough/"><u>Wireless Setup for Officejet Pro M110 Series: A Complete Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-wastelanded-printer-on-windows-11/"><u>Stop Your Wastelanded Printer on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-error-unable-to-locate-printer-drivers/"><u>[WIN ERROR] Unable to Locate Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pixma-mp620-searching-for-driver-on-win11-repository/"><u>Pixma MP620: Searching for Driver on Win11 Repository</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-prints-failing-to-appear/"><u>Color Prints Failing to Appear</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-print-sentry-refuses-responses/"><u>My Print Sentry Refuses Responses</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-reactivate-dormant-hp-printers/"><u>Guidelines to Reactivate Dormant HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-established-printer-connections/"><u>Success: Established Printer Connections</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-print-troubleshoot-0x97/"><u>Epson Print Troubleshoot: 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/defeating-paper-jams-fixing-spooler-issues-win-1011/"><u>Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-printerevolving-spooler-error-wx-w10-and-w11/"><u>Stop Printer'evolving Spooler Error (WX, W10 & W11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unresponsive-due-to-missing-os-driver/"><u>Printer Unresponsive Due to Missing OS Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-get-an-offline-printer-running-on-vistaxp/"><u>How to Get an Offline Printer Running on Vista/XP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win107-troubleshooting-steps-to-address-spooler-failures/"><u>Win10/7 Troubleshooting Steps to Address Spooler Failures</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/bunny-up-your-video-editing-game-wondershare-filmora-easter-discount-for-2024/"><u>Bunny Up Your Video Editing Game Wondershare Filmora Easter Discount for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-creative-potential-with-top-tips-for-gopro-timelapses/"><u>[New] Unleash Creative Potential with Top Tips for GoPro Timelapses</u></a></li>
<li><a href="https://some-approaches.techidaily.com/strategies-to-skyrocket-like-counts-in-tiktok-unpack-videos-for-2024/"><u>Strategies to Skyrocket 'Like' Counts in TikTok Unpack Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-itel-p55-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Itel P55 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-closer-examination-of-googles-ar-stickers-and-competitors/"><u>A Closer Examination of Google's AR Stickers and Competitors</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-best-4k-monitors-for-mac-the-ultimate-list-for-2024/"><u>[New] Best 4K Monitors for Mac - The Ultimate List for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-6s-plus-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone 6s Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-role-of-free-exchange-in-discovery-for-2024/"><u>The Role of Free Exchange in Discovery for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-top-3-premier-audio-amplification-websites-for-mp3s/"><u>New In 2024, Top 3 Premier Audio Amplification Websites for MP3s</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-crafting-premium-soundtracks-with-zooms-record-feature/"><u>[Updated] 2024 Approved  Crafting Premium Soundtracks with Zoom's Record Feature</u></a></li>
<li><a href="https://youtube-help.techidaily.com/maximizing-impact-a-guide-to-customizing-game-banners-for-2024/"><u>Maximizing Impact  A Guide to Customizing Game Banners for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-video-player-face-off-vlc-against-mpc-for-2024/"><u>Free Video Player Face-Off  VLC Against MPC for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-33-chuckle-inducing-tiktok-joke-series/"><u>2024 Approved  33 Chuckle-Inducing TikTok Joke Series</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-rise-to-fame-on-instagram-top-9-strategies-revealed/"><u>2024 Approved  Rise to Fame on Instagram  Top 9 Strategies Revealed</u></a></li>
</ul></div>
