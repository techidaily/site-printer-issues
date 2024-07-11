---
title: Steps to Stop and Resolve Printer Spooling Trouble
date: 2024-07-10T17:15:06.556Z
updated: 2024-07-11T17:15:06.556Z
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
<li><a href="https://printer-issues.techidaily.com/fine-tune-your-prints-install-new-v305-driver-in-win7/"><u>Fine-Tune Your Prints: Install New V305 Driver in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scan-functionality-reinstated-in-win11/"><u>Scan Functionality: Reinstated in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tactics-for-uninstalling-windows-printers/"><u>Tactics for Uninstalling Windows Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printer-function-release/"><u>Seamless Printer Function Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-unable-to-locate-hp-winxo/"><u>[Driver Search Failed] - Unable to Locate HP WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-ad-domain-offline/"><u>PPrintError - AD Domain Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-oxc4eb827f-error-on-hp-devices/"><u>Addressing OXC4EB827F Error on HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnected-print-spooler-in-win7/"><u>Reconnected Print Spooler in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/improve-network-settings-for-w11-printers/"><u>Improve Network Settings for W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabled-hp-all-in-one-printer-active-now/"><u>Enabled: HP All-in-One Printer Active Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-printer-error-what-windows-users-can-do/"><u>Network Printer Error: What Windows Users Can Do</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-brother-printer-not-printing-issue-step-by-step-winoses/"><u>Tackling Brother Printer Not Printing Issue, Step by Step, WinOSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/identified-non-printer-owners-computer-mischief/"><u>Identified Non-Printer Owner's Computer Mischief</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-installation-hp-officejet-pro-8600-on-windows/"><u>Streamlined Installation: HP OfficeJet Pro 8600 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-refusing-to-use-all-colors/"><u>Printer Refusing to Use All Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/lighten-your-load-fast-prints-guide/"><u>Lighten Your Load: Fast Prints Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-solved-for-epson-model/"><u>Print Issue Solved for Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turbo-charge-your-print-operations/"><u>Turbo-Charge Your Print Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-spits-out-unprinted-sheets/"><u>Resolved: Printer Spits Out Unprinted Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-clear-print-head-conflict-on-win-1011/"><u>How To Clear Print Head Conflict on Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicate-brother-printers-no-print-dilemma-on-windows/"><u>Eradicate Brother Printer's No-Print Dilemma on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-operation-windows-compatible-driver-for-officejet-pro-8600/"><u>Efficient Operation: Windows Compatible Driver for Officejet Pro 8600</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-disabled-scan-in-win11/"><u>Reviving Disabled Scan in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-troubleshooting-get-your-canon-printer-printing-on-windows/"><u>Easy Troubleshooting: Get Your Canon Printer Printing on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-swift-printers/"><u>Quick Tips for Swift Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-solutions-to-printer-delays/"><u>Swift Solutions to Printer Delays</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-release-from-print-lineup/"><u>Speedy Release From Print Lineup</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-make-your-whatsapp-status-pop-with-these-top-video-makers/"><u>In 2024, Make Your WhatsApp Status Pop with These Top Video Makers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-revolutionize-video-files-with-instant-fb-to-mp4-and-hd-upgrade/"><u>[Updated] 2024 Approved  Revolutionize Video Files with Instant FB to MP4 & HD Upgrade</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-binge-worthy-battles-discovering-the-viral-tiktok-top-10/"><u>[New] Binge-Worthy Battles  Discovering the Viral TikTok Top 10</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-best-video-loopers-to-loop-videos-for-free-on-windows-and-mac/"><u>New Best Video Loopers to Loop Videos for Free on Windows and Mac</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/legalities-in-sharing-instagram-melodies-for-2024/"><u>Legalities in Sharing Instagram Melodies for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-infinix-hot-30-5g-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Infinix Hot 30 5G</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-essential-tips-for-using-tiktok-on-macwindows-systems/"><u>2024 Approved  Essential Tips for Using TikTok on Mac/Windows Systems</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-cutting-edge-tips-designing-immersive-educational-videos-for-online-learning/"><u>[New] 2024 Approved  Cutting-Edge Tips  Designing Immersive Educational Videos for Online Learning</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-safe-secure-and-stress-free-exclusive-list-of-free-video-call-apps-for-iphoneandroid/"><u>[Updated] In 2024, Safe, Secure & Stress-Free  Exclusive List of Free Video Call Apps for iPhone/Android</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-shielding-the-sound-comprehensive-guide-to-dismissing-wind-turbulence-in-recordings/"><u>2024 Approved Shielding the Sound Comprehensive Guide to Dismissing Wind Turbulence in Recordings</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-time-saving-approaches-to-turn-whatsapp-audios-into-mp3-format/"><u>New 2024 Approved Time-Saving Approaches to Turn WhatsApp Audios Into MP3 Format</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-latest-smartphones-and-their-fit-with-gear-vr-technology/"><u>2024 Approved  Latest Smartphones and Their Fit With Gear VR Technology</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-elevating-soundtracks-on-mobile-the-top-8-android-apps-redefining-music-production/"><u>In 2024, Elevating Soundtracks on Mobile The Top 8 Android Apps Redefining Music Production</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-cross-service-song-matching-sharing-your-musical-journey/"><u>[New] In 2024, Cross-Service Song Matching  Sharing Your Musical Journey</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-12-pro-max-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 Pro Max Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-discover-the-top-8-ios-audio-production-tools-for-your-ipad-and-iphone/"><u>Updated 2024 Approved Discover the Top 8 iOS Audio Production Tools for Your iPad & iPhone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-15-pro-max-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 15 Pro Max and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-rated-movie-making-apps-for-windows-10/"><u>New Top-Rated Movie Making Apps for Windows 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-visual-narrative-crafting-your-podcasts-brand-image/"><u>[Updated] The Visual Narrative  Crafting Your Podcast's Brand Image</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-itel-p55plus-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Itel P55+ Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-honor-x50-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Honor X50 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-cacophony-compendium-discovering-the-top-8-websites-to-access-an-array-of-superior-free-sound-effects/"><u>New The Cacophony Compendium Discovering the Top 8 Websites to Access an Array of Superior Free Sound Effects</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mastering-the-art-of-beat-isolation-in-music-production/"><u>Mastering the Art of Beat Isolation in Music Production</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/smartest-titles-at-your-fingertips-for-2024/"><u>Smartest Titles at Your Fingertips for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-vivo-v27e-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Vivo V27e</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/accelerate-your-channel-growth-affordable-subscribers-available/"><u>Accelerate Your Channel Growth - Affordable Subscribers Available</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-sustaining-system-stability-returning-to-el-capitan/"><u>2024 Approved  Sustaining System Stability  Returning to El Capitan</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-top-instagram-tagging-strategies-to-skyrocket-likes-and-followers-for-2024/"><u>[New] Top Instagram Tagging Strategies to Skyrocket Likes and Followers for 2024</u></a></li>
</ul></div>
