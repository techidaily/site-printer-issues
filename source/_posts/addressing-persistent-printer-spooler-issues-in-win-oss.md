---
title: Addressing Persistent Printer Spooler Issues in Win OSs
date: 2024-07-10T17:30:39.287Z
updated: 2024-07-11T17:30:39.287Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Addressing Persistent Printer Spooler Issues in Win OSs
excerpt: This Article Describes Addressing Persistent Printer Spooler Issues in Win OSs
keywords: Printer Spooler Error,Windows Print Service Fix,Spooler Troubleshooting Guide,Print Spooler Reset in Win OSs,Persistent Print Issues Windows,Spooler Services Repair Win OSs,Print Queue Anomalies Fix
thumbnail: https://thmb.techidaily.com/e7b4c7d026fb9a820758c805a32df2a4b6a1efba9319850eda25937764e730c5.jpg
---

## Addressing Persistent Printer Spooler Issues in Win OSs

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
<li><a href="https://printer-issues.techidaily.com/connection-guide-integrating-hp-printer-with-pc-network/"><u>Connection Guide: Integrating HP Printer with PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-drivers-and-utilities-officejet-pro-8600-for-pc-users/"><u>Unified Drivers & Utilities: OfficeJet Pro 8600 for PC Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivation-of-online-scan-achieved-on-win11/"><u>Reactivation of Online Scan Achieved on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-active-directory-offline/"><u>Unable To Print: Active Directory Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-code-xf34/"><u>Troubleshooting HP Printer Code #XF34</u></a></li>
<li><a href="https://printer-issues.techidaily.com/directions-assembling-hp-print-with-your-pc/"><u>Directions: Assembling HP Print with Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-established-printer-connections/"><u>Success: Established Printer Connections</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-performance-officejet-pro-8600-driver-for-windows/"><u>Enhanced Performance: Officejet Pro 8600 Driver for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-solve-offline-canon-printer-issues/"><u>Connectivity Woes? Solve Offline Canon Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-added-new-printer/"><u>Successfully Added New Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-hp-printer-seamlessly-in-windows-environment/"><u>Integrate HP Printer Seamlessly in Windows Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-mysterious-setup-error/"><u>Printer Puzzle: Mysterious Setup Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-efficiency-quickly/"><u>Enhance Printer Efficiency Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-it-running-smoothly-update-dells-inkjet-aio-on-windows-7/"><u>Keep It Running Smoothly: Update Dell's Inkjet AIO on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-fixing-epson-error-x97/"><u>Understanding & Fixing Epson Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unlisted-solutions-for-windows-xp-11/"><u>Printer Unlisted: Solutions for Windows XP-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-oxc4eb827f-error-on-hp-devices/"><u>Addressing OXC4EB827F Error on HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resume-printing-with-online-canon-printer-tips/"><u>Resume Printing with Online Canon Printer Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-installation-of-canon-print-devices/"><u>Mastering the Installation of Canon Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recommendations-for-reactivating-hp-print-headless-systems/"><u>Recommendations for Reactivating HP Print Headless Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-printing-after-update-woes-ended/"><u>Smooth Printing After Update Woes Ended</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-error-xf09-on-epson-devices/"><u>Addressing Error #XF09 on Epson Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-print-no-hassle-method/"><u>Reconnect Print: No Hassle Method</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-networked-hp-printer-on-w7/"><u>Restoring Networked HP Printer on W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-disruptions-from-windows-710s-printer-service/"><u>Preventing Disruptions From Windows 7/10'S Printer Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-installing-hp-photosmart-printer/"><u>Step-by-Step: Installing HP PhotoSmart Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-cant-get-hp-d1360-to-work-windows-versions-involved/"><u>[Hardware Setup] Can't Get HP D1360 to Work: Windows Versions Involved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-silent-canon-printer/"><u>Reviving a Silent Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-connection-remedy/"><u>Quick Printer Connection Remedy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-dormant-windows-3x-print-jobs-instantly/"><u>Reviving Dormant Windows 3.x Print Jobs Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-scan-back-to-operational-state/"><u>Windows Scan: Back to Operational State</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanner-activation-after-updating-win10/"><u>Enable Scanner Activation After Updating Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-hp-printer-error-code-oxc4eb827f/"><u>Purging HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revamp-printer-functions-install-new-hp-inkjets-software/"><u>Revamp Printer Functions: Install New HP Inkjets Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printing-revolution-install-new-inkjet-drivers-and-updates/"><u>HP Printing Revolution: Install New Inkjet Drivers and Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-printing-resumes-after-upgraded-system-changes/"><u>Smooth Printing Resumes After Upgraded System Changes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-domain-down-resulting-in-printer-failure/"><u>AD Domain Down - Resulting In Printer Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-usb-printers-ignoring-command-in-windows-7-mode/"><u>[Fix] USB Printers Ignoring Command in Windows 7 Mode</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-ultimate-font-customization-tools-for-discord-devices/"><u>2024 Approved  Ultimate Font Customization Tools for Discord Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/echoing-emotions-infusing-music-into-instareel-content/"><u>Echoing Emotions  Infusing Music Into InstaReel Content</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tips-for-seamless-crossfading-in-audacity/"><u>In 2024, Tips for Seamless Crossfading in Audacity</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-most-attractive-gaming-peripherals-for-under-100/"><u>[New] In 2024, The Most Attractive Gaming Peripherals for Under $100</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-realme-12plus-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Realme 12+ 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-motorcycle-video-magic-best-cam-hats-of-2023-selection/"><u>In 2024, Motorcycle Video Magic  Best Cam Hats of 2023 Selection</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/organize-soundtracks-on-youtube-the-playlist-guide/"><u>Organize Soundtracks on Youtube  The Playlist Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-remarkable-judgment-and-substitutes-advice/"><u>2024 Approved  Remarkable Judgment & Substitutes Advice</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-mac-display-recorder-tips-and-tricks/"><u>[Updated] 2024 Approved  Mac Display Recorder Tips & Tricks</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-premium-convert-mp4-to-facebook-media/"><u>[New] 2024 Approved  Premium Convert  MP4 to Facebook Media</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-infinix-smart-8-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Infinix Smart 8 to iPad | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-12-pro-max-learn-all-4-methods-drfone-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone 12 Pro Max? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-redefining-schooling-with-virtual-reality/"><u>In 2024, Redefining Schooling with Virtual Reality</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-connect-with-community-spots-a-dynamic-guide-for-local-explorers-on-the-move/"><u>2024 Approved  Connect with Community Spots  A Dynamic Guide for Local Explorers on the Move</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-best-bites-outside-the-box-new-film-favorites/"><u>[New] In 2024, Best Bites Outside the Box  New Film Favorites</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-htc-u23-unlock-without-password-by-drfone-android/"><u>5 Solutions For HTC U23 Unlock Without Password</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-realme-12plus-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Realme 12+ 5G</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-6s-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone 6s without Apple Account</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-boosting-brand-with-tiktok-promotion-a-growth-blueprint/"><u>[New] In 2024, Boosting Brand with TikTok Promotion  A Growth Blueprint</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-a-found-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How To Unlock A Found Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://fox-links.techidaily.com/unveiling-the-powerhouses-of-vr-engine-technology/"><u>Unveiling the Powerhouses of VR Engine Technology</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-oppo-reno-9a-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Oppo Reno 9A</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-channel-conversion-secrets-yt-vs-igtv-for-2024/"><u>[New] Channel Conversion Secrets  YT Vs IGTV for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-perfect-timing-adjust-video-speed-in-snapchat-easily/"><u>[New] In 2024, Perfect Timing  Adjust Video Speed in Snapchat Easily</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-smartphone-and-tablet-companion-best-gba-simulators/"><u>[New] 2024 Approved  Smartphone & Tablet Companion  Best GBA Simulators</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-procuring-growls-and-whispers-audio-packages/"><u>Updated In 2024, Procuring Growls and Whispers Audio Packages</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-oppo-a58-4g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Oppo A58 4G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-how-to-uncover-hidden-facebook-vids-updated-guide-for-2024/"><u>[New] How to Uncover Hidden Facebook Vids (Updated Guide) for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-the-most-advanced-real-time-speech-modification-tools/"><u>2024 Approved The Most Advanced Real-Time Speech Modification Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-polishing-profile-vids-tips-and-tricks/"><u>[New] In 2024, Polishing Profile Vids  Tips and Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-discovering-expert-seed-selection-for-valheimers/"><u>[New] 2024 Approved  Discovering Expert Seed Selection for Valheimers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-palette-perfection-in-11-step-by-step-lessons/"><u>[Updated] Palette Perfection in 11 Step-by-Step Lessons</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-5-cloud-saviors-mastering-2024s-space-savers/"><u>[Updated] Top 5 Cloud Saviors  Mastering 2024'S Space Savers</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-gross-income-estimates-for-youtube-star-pewdopeep/"><u>2024 Approved  Gross Income Estimates for YouTube Star PewDoPeep</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-blades-and-boards-olympians-on-ice/"><u>2024 Approved  Blades & Boards  Olympians on Ice</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-apple-iphone-15-plus-location-on-skout-drfone-by-drfone-virtual-ios/"><u>How to Change Apple iPhone 15 Plus Location on Skout | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-gionee-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Gionee FRP</u></a></li>
</ul></div>
