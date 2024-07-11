---
title: Essential Guide to Stopping Repeated Spooler Halt in Windows
date: 2024-07-10T17:36:30.836Z
updated: 2024-07-11T17:36:30.836Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Essential Guide to Stopping Repeated Spooler Halt in Windows
excerpt: This Article Describes Essential Guide to Stopping Repeated Spooler Halt in Windows
keywords: Windows 10 SPOOLER STOPPING REPEATS,How to Stop Spooler Errors on Windows,Solutions for Repeated Spooler Hangs (Windows),Preventing Spooler Halt in Windows OS,Fixing Repeated Spooler Errors (Windows),Stop Spooler Errors on Windows 10,Troubleshooting Repeated Spooler Halt in Windows
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Essential Guide to Stopping Repeated Spooler Halt in Windows

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
<li><a href="https://printer-issues.techidaily.com/dispelling-hp-printers-fatal-mistake-0xoxc4eb827f/"><u>Dispelling HP Printer's Fatal Mistake 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-restarting-brother-printer-for-windows/"><u>Troubleshooting: Restarting Brother Printer for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-10/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ceased-epson-standby-error/"><u>Ceased Epson Standby Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-on-offline-hp-desktop-printer-in-wx-2003/"><u>Turn On Offline HP Desktop Printer in WX 2003</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-service-down-unable-to-print/"><u>AD DS Service Down: Unable To Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-error-0x97-resolution-found/"><u>Epson Error 0X97: Resolution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-air-glide-instructions-quickly/"><u>Brother CDW Air-Glide Instructions Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-driver-suite-for-windows-enhancement/"><u>HP Officejet Pro 8600 Driver Suite for Windows Enhancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recognition-failure-hp-driver-missing-in-win1011/"><u>Printer Recognition Failure: HP Driver Missing in WIN10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-delete-inactive-printers-in-windows-easy-way/"><u>How To Delete Inactive Printers in Windows Easy Way</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winerror-zeroed-out-restoring-printer-setup-0x00000709/"><u>WinError Zeroed Out - Restoring Printer Setup (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-printer-back-in-action-on-windows-11/"><u>Get Your Printer Back in Action on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquering-the-blank-page-battlefield-for-printers/"><u>Conquering the Blank Page Battlefield for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/getting-your-w7s-offline-hp-print-running/"><u>Getting Your W7's Offline HP Print Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-not-working-solve-it-in-win1011/"><u>Brother Printer Not Working? Solve It in Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-hp-printers-error-code-oxc4eb827f/"><u>Eliminating HP Printer's Error Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fixed-after-new-windows-version-patch/"><u>Printer Fixed After New Windows Version Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/what-to-do-when-your-printer-is-offline/"><u>What To Do When Your Printer Is Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-wireless-setup-step-by-step/"><u>Brother CDW Wireless Setup: Step by Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-canon-printer-with-ease-on-wi-fi/"><u>Setting Up Canon Printer with Ease on Wi-Fi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-windows-117-hp-printer-errors/"><u>Overcoming Windows 11/7 HP Printer Errors</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-expert-strategies-to-master-the-instagram-query-tag/"><u>2024 Approved  Expert Strategies to Master the Instagram Query Tag</u></a></li>
<li><a href="https://fox-helps.techidaily.com/improving-professional-collaboration-with-strategic-office-planning-for-2024/"><u>Improving Professional Collaboration with Strategic Office Planning for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-effortless-media-transition-from-mp3-to-youtube-video-posting/"><u>[Updated] In 2024, Effortless Media Transition  From MP3 to YouTube Video Posting</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 To Others devices? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-the-art-of-flawless-conversion-video-to-mp3-without-losing-a-beat/"><u>Updated 2024 Approved The Art of Flawless Conversion Video to MP3 without Losing a Beat</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-quick-tutorial-inverting-video-playback-in-vlc-media-player/"><u>[Updated] 2024 Approved  Quick Tutorial  Inverting Video Playback in VLC Media Player</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-craftsmanship-in-action-macs-5-elite-snipping-applications/"><u>[Updated] In 2024, Craftsmanship in Action  Mac's 5 Elite Snipping Applications</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-expert-picks-optimal-vr-for-drone-pilots/"><u>[New] 2024 Approved  Expert Picks  Optimal VR for Drone Pilots</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-oppo-reno-11-5g-device-sim-by-drfone-android/"><u>Easily Unlock Your Oppo Reno 11 5G Device SIM</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-techniques-for-gh-video-logging/"><u>[New] Techniques for GH Video Logging</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-latest-screens-recording-revelation-by-apeaksoft-2023/"><u>In 2024, The Latest Screens Recording Revelation by Apeaksoft, 2023</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/1714208521440-new-in-2024-why-final-cut-pro-beats-final-cut-express/"><u>New In 2024, Why Final Cut Pro Beats Final Cut Express</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-precision-and-flexibility-exploring-the-best-10-mac-recording-tools/"><u>[New] In 2024, Precision and Flexibility  Exploring the Best 10 Mac Recording Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-lava-yuva-2-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Lava Yuva 2 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-block-someone-on-instagram-for-2024/"><u>How to Block Someone on Instagram for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-free-and-easy-mov-video-rotation-solutions/"><u>New In 2024, Free and Easy MOV Video Rotation Solutions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-future-fusion-unlocking-mac-with-smartwatches/"><u>[New] Future Fusion  Unlocking Mac With Smartwatches</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-synchronizing-realism-advanced-green-screen-applications-for-viewers/"><u>In 2024, Synchronizing Realism  Advanced Green Screen Applications for Viewers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-future-of-communication-voice-altering-software-shaping-google-meet-interactions-2024-edition/"><u>New The Future of Communication Voice Altering Software Shaping Google Meet Interactions, 2024 Edition</u></a></li>
</ul></div>
