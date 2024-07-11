---
title: Stopping Intermittent Spooler Crashes in Win10/7 Devices
date: 2024-07-10T17:09:23.389Z
updated: 2024-07-11T17:09:23.389Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stopping Intermittent Spooler Crashes in Win10/7 Devices
excerpt: This Article Describes Stopping Intermittent Spooler Crashes in Win10/7 Devices
keywords: Intermittent Spooler Crash Fix,Stop SPOOLER in Windows 10/7,Spooler Crashes Resolution,Windows 10/7 Spooler Troubleshooting,Spooler Crash Prevention in Win 10/7,Intermittent Spooler Errors Windows Fix,Spooler Stability in Win10 Devices
thumbnail: https://thmb.techidaily.com/ee5c0d7e477d155cf7c4d7a41bb4baf523bd4dd370c1eec84bd95b2e762714db.png
---

## Stopping Intermittent Spooler Crashes in Win10/7 Devices

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
<li><a href="https://printer-issues.techidaily.com/fixed-error-0x00000709-on-printer-selection-in-windows/"><u>Fixed Error 0X00000709 on Printer Selection in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/supercharge-dells-v305-inkjets-with-new-windows-driver/"><u>Supercharge Dell's V305 Inkjets with New Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-107-solved/"><u>HP Printer Offline Status on Windows 10/7 [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-usage-fluctuation-raises-eyebrows/"><u>Printer Usage Fluctuation Raises Eyebrows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-print-processes-revealed/"><u>Brisk Print Processes Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-scannerprinter-blank-page-mystery-solved/"><u>Epson Scanner/Printer Blank Page Mystery Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-re-enable-scanned-device-connection/"><u>Windows 10: Re-Enable Scanned Device Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-canon-error-b200/"><u>Eradicated Canon Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-error-unable-to-install-mp620-drivers-in-win10/"><u>[System Error] Unable to Install MP620 Drivers in WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-and-propel-printers-fast/"><u>Unblock and Propel Printers Fast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-fixes-for-non-starting-print-spooler-on-pcs/"><u>Essential Fixes for Non-Starting Print Spooler on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-inkjet-malfunction/"><u>Correcting Inkjet Malfunction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-connectivity-crunch-windows-7-usb-printer-dormancy/"><u>[Resolved] Connectivity Crunch: Windows 7 USB Printer Dormancy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-enhance-printer-speed/"><u>Effortlessly Enhance Printer Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-driver-not-located-by-win/"><u>Printer Error: Driver Not Located by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win2k-printer-response-error-resolution-guide/"><u>Win2K Printer Response: Error Resolution Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cease-print-slowdown-in-winxp-solution-found/"><u>Cease Print Slowdown in WinXP - Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-printer-support-package-windows-based/"><u>Officejet Pro 8600 Printer Support Package, Windows-Based</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-removal-of-external-printers/"><u>Effortless Removal of External Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-from-sleep-troubleshooting-usb-printer-not-working/"><u>Wake From Sleep: Troubleshooting USB Printer Not Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-hiccup-discovered/"><u>Unexpected Print Hiccup Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-your-canon-printer-an-illustrated-tutorial/"><u>Installing Your Canon Printer - An Illustrated Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systematic-mf4770n-software-enhancement-windows-wise/"><u>Systematic MF4770n Software Enhancement Windows-Wise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplify-installation-with-our-proven-windows-hp-printer-methodology/"><u>Simplify Installation with Our Proven Windows-Hp Printer Methodology</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ended-canons-code-b200-misstep/"><u>Ended Canon's Code B200 Misstep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-error/"><u>Mended Printer Network Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-disabled-scan-in-win11/"><u>Reviving Disabled Scan in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapidly-reconnecting-to-your-printer/"><u>Rapidly Reconnecting to Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-windows-710-to-online-hp-printer/"><u>Reconnect Windows 7/10 to Online HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypass-blank-pages-reactivating-your-canon-print-spooler/"><u>Bypass Blank Pages: Reactivating Your Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-print-sessions-fixing-driver-issues-on-win10/"><u>Secure Print Sessions: Fixing Driver Issues on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-scanner-issue-on-windows-11/"><u>Resolving Scanner Issue on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-windows-7-printer-unresponsive/"><u>Resolved: Windows 7 Printer Unresponsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-paper-jams-in-copiers/"><u>Preventing Paper Jams in Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-canon-printer-seamless-wireless-hookup/"><u>Stepwise Canon Printer: Seamless Wireless Hookup</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-achieving-zen-in-meetings-how-to-disable-background-speech/"><u>In 2024, Achieving Zen in Meetings  How to Disable Background Speech</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unveiling-mastery-the-ultimate-animoji-guide-for-iphone-x/"><u>[Updated] Unveiling Mastery  The Ultimate Animoji Guide for iPhone X</u></a></li>
<li><a href="https://fox-blue.techidaily.com/strategies-to-extend-gopro-battery-hours-for-2024/"><u>Strategies to Extend GoPro Battery Hours for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/auralalley-navigating-the-vr-path-of-language-learning/"><u>AuralAlley: Navigating the VR Path of Language Learning</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-device-issue-on-windows-os/"><u>Troubleshooting Missing Device Issue on Windows OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-step-by-step-building-a-viral-instagram-film-empire/"><u>[New] In 2024, Step-by-Step  Building a Viral Instagram Film Empire</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-ace-screen-recorders-list-for-the-winning-setup/"><u>In 2024, The Ace Screen Recorders List - For the Winning Setup</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-the-elite-comprehensive-oculus-review-guide/"><u>[New] Unveiling the Elite  Comprehensive Oculus Review Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-meizu-21-to-mac-drfone-by-drfone-android/"><u>How to Mirror Meizu 21 to Mac? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-key-strategies-for-adding-timestamps-in-youtube-content/"><u>2024 Approved  Key Strategies for Adding Timestamps in YouTube Content</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-easy-methods-to-unlock-icloud-locked-apple-iphone-se-2020ipadipod-by-drfone-ios/"><u>3 Easy Methods to Unlock iCloud Locked Apple iPhone SE (2020)/iPad/iPod</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-az-recorder-expert-series-app-deep-dives/"><u>[Updated] 2024 Approved  AZ Recorder Expert Series  App Deep Dives</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-easy-to-follow-guide-recording-non-root-android-sounds-for-2024/"><u>[New] Easy-to-Follow Guide  Recording Non-Root Android Sounds for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-make-your-gif-on-whatsapp-in-simple-ways/"><u>How to Make Your GIF on WhatsApp in Simple Ways</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-global-audiences-local-stories-crafting-engaging-instagramcaptions-for-2024/"><u>[Updated] Global Audiences, Local Stories - Crafting Engaging #InstagramCaptions for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-listenguide-examination/"><u>[Updated] In 2024, ListenGuide Examination</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-samsung-galaxy-a23-5g-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Samsung Galaxy A23 5G?</u></a></li>
<li><a href="https://article-helps.techidaily.com/2023s-top-rated-vr-game-engines-exposed-for-2024/"><u>2023'S Top-Rated VR Game Engines Exposed for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-poco-c50-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Poco C50 FRP Bypass</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-essential-asmr-creators-to-follow/"><u>2024 Approved  Essential ASMR Creators to Follow</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/game-masters-top-ten-female-gaming-influencers/"><u>Game Masters  Top Ten Female Gaming Influencers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-windows-8-movie-maker-like-a-pro/"><u>In 2024, Navigating Windows 8 Movie Maker Like a Pro</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-avoiding-pitfalls-in-submitting-to-apple/"><u>2024 Approved  Avoiding Pitfalls in Submitting to Apple</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-samsung-galaxy-xcover-7-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Samsung Galaxy XCover 7 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-transform-your-ig-story-with-melodic-elements-without/"><u>[Updated] 2024 Approved  Transform Your IG Story with Melodic Elements (Without)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-become-a-snapboom-expert-in-minutes-for-2024/"><u>[New] Become a SnapBoom Expert in Minutes for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/resolving-frame-rate-puzzle-which-fps-brings-sharper-videos/"><u>Resolving Frame Rate Puzzle  Which FPS Brings Sharper Videos</u></a></li>
</ul></div>
