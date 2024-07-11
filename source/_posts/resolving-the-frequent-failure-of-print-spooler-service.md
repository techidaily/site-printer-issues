---
title: Resolving the Frequent Failure of Print Spooler Service
date: 2024-07-10T17:24:04.944Z
updated: 2024-07-11T17:24:04.944Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolving the Frequent Failure of Print Spooler Service
excerpt: This Article Describes Resolving the Frequent Failure of Print Spooler Service
keywords: Fixing Windows Print Spooler Crashes,Troubleshoot Printer Spooler Service Failures,Windows Print Spooler Service Fixes,Restart Windows Print Spooler Service,Prevent Print Spooler Service Errors,Fix Printer Spooler Service on Windows,Recommended Solutions for Print Spooler Failures
thumbnail: https://thmb.techidaily.com/e3e57dc288a15eebc6a087ce47534d889b154128f1cec9b763b947b83648c7c9.jpg
---

## Resolving the Frequent Failure of Print Spooler Service

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
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-enhance-windows-11-8-7-integration/"><u>MF4770n Drivers - Enhance Windows 11, 8, 7 Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-connectivity-between-laptops-and-hp-discover-the-best-fixes/"><u>Instant Connectivity Between Laptops & HP - Discover the Best Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unknown-computer-known-printer-case-closed/"><u>Unknown Computer, Known Printer - Case Closed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fixed-version-printing-whole-documents/"><u>New Fixed Version: Printing Whole Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disconnecting-all-print-devices-at-once-on-pc/"><u>Disconnecting All Print Devices at Once on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/limited-color-range-in-output-documents/"><u>Limited Color Range in Output Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-and-secure-printer-communication-in-win10/"><u>Upgrade and Secure Printer Communication in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-installation-guide-for-windows/"><u>HP Printer Installation Guide for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-struggles-cannot-find-mp620-printer-drivers/"><u>Windows 10 Struggles: Cannot Find MP620 Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-device-management-officejet-pro-8600-drivers-pc-friendly/"><u>Streamlined Device Management: Officejet Pro 8600 Drivers, PC-Friendly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-transition-new-driver-for-your-hp-4630/"><u>Seamless Transition: New Driver for Your HP 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-end-print-job-wait/"><u>Efficiently End Print Job Wait</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-error-now-corrected/"><u>B200 Error: Now Corrected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-scanner-on-windows-11-os/"><u>Reviving Scanner on Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-optimization-made-simple/"><u>Printer Optimization Made Simple</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reestablish-links-essential-steps-to-solve-printer-woes/"><u>Reestablish Links: Essential Steps to Solve Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-mf4770n-with-w11-w8-w7-ecosystems/"><u>Harmonizing MF4770n with W11, W8, W7 Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-blank-page-woes-printer-remedy-discovered/"><u>The End of Blank Page Woes: Printer Remedy Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-and-performance-boost-officejet-pro-8600-windows-version/"><u>Compatibility & Performance Boost: Officejet Pro 8600, Windows Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-unprinted-printer/"><u>Troubleshooting: Unprinted Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-releases-dell-v305-driver-and-utility-supports-win7/"><u>New Releases: Dell V305 Driver & Utility Supports Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-installation-inkjet-printer-error-fixed/"><u>Post Installation, Inkjet Printer Error Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-page-gaps-the-2024-printer-fix/"><u>End Page Gaps: The 2024 Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-functionality-in-dormant-hp-multi-function-devices/"><u>Restoring Functionality in Dormant HP Multi-Function Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-imprinter-malfunctions-in-windows-11/"><u>Address Imprinter Malfunctions in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-get-your-brother-printer-back-up-and-running-on-windows/"><u>How to Get Your Brother Printer Back Up & Running on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-printer-no-start-error/"><u>Addressed Printer No Start Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-scanner-troubleshooting-win10/"><u>Reconnect Scanner: Troubleshooting Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-lexmark-printer-glitches/"><u>Addressing Lexmark Printer Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-scanner-link-to-computer-in-win10/"><u>Re-Establishing Scanner Link to Computer in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-epson-inkjet-skips-printing-texts/"><u>Resolved: Epson Inkjet Skips Printing Texts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mysterious-print-job-by-secondary-computer/"><u>Mysterious Print Job by Secondary Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-sleephibernate-glitch-with-usb-printers-w7/"><u>[Resolved] Sleep/Hibernate Glitch with USB Printers, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-offline-causes-inability-to-print/"><u>AD DS Offline Causes Inability To Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-vectors-alternatives-to-the-classic-acid-pro/"><u>2024 Approved  Top Vectors Alternatives to the Classic ACID Pro</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-integrating-gopro-adventures-with-popular-social-media-channels/"><u>In 2024, Integrating GoPro Adventures with Popular Social Media Channels</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-highest-quality-action-capturing-methods/"><u>[New] In 2024, Highest Quality Action Capturing Methods</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-discord-speaking-tts-basics-guide-for-2024/"><u>Mastering Discord Speaking  TTS Basics Guide for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-professional-tips-to-perfect-igtv-thumbnails/"><u>In 2024, Professional Tips to Perfect IGTV Thumbnails</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-2022-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE (2022) To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-boost-visual-speakers-output-enhance-movie-and-video-audibility/"><u>Updated In 2024, Boost Visual Speakers Output Enhance Movie and Video Audibility</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-direct-controls-full-guide-to-powerdirector-2024/"><u>Mastering Direct Controls  Full Guide to PowerDirector 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-professional-pcmac-screen-recorders/"><u>[Updated] Professional PC/Mac Screen Recorders</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-on-your-iphone-12-pro-max-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled On your iPhone 12 Pro Max? How to Fix</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-smart-planners-guide-to-virtual-meeting-success/"><u>[New] The Smart Planner's Guide to Virtual Meeting Success</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-avoid-download-hassle-top-5-online-converters-for-gif-to-video/"><u>[Updated] Avoid Download Hassle  Top 5 Online Converters for GIF to Video</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-prime-20-anime-openers-soundscape/"><u>In 2024, Prime 20 Anime Openers' Soundscape</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-tiktok-content-creation-navigating-copyright-rules/"><u>[Updated] 2024 Approved  TikTok Content Creation  Navigating Copyright Rules</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-how-to-add-subtitles-to-igtv-videos/"><u>[Updated] How to Add Subtitles to IGTV Videos?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-cutting-edge-avi-video-editors-top-16-picks-for-trimming-and-cutting-cross-platform/"><u>New Cutting-Edge AVI Video Editors Top 16 Picks for Trimming and Cutting Cross-Platform</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-influence-made-possible-today/"><u>[New] 2024 Approved  Instagram Influence Made Possible Today</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-tips-for-sharing-twitter-videos-on-instagram/"><u>[New] In 2024, Tips for Sharing Twitter Videos on Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-picture-capture-unpacker-for-2024/"><u>[Updated] Picture Capture Unpacker for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-realme-10t-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Realme 10T 5G Without PUK Codes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-seamless-tweet-integration-on-facebook-platform/"><u>[New] In 2024, Seamless Tweet Integration on Facebook Platform</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-redmi-13c-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-10-youtube-video-to-mp3-converter-withwithout-editor/"><u>Top 10 YouTube Video to Mp3 Converter With/Without Editor</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-xiaomi-13t-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Xiaomi 13T Phone that is Locked?</u></a></li>
<li><a href="https://extra-support.techidaily.com/refining-photos-the-step-by-step-guide-to-clean-edges-on-photopea-for-2024/"><u>Refining Photos  The Step-by-Step Guide to Clean Edges on Photopea for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-cutting-edge-strategies-for-iptv-capture-success/"><u>2024 Approved  Cutting-Edge Strategies for IPTV Capture Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-download-youtube-thumbnail-in-3-waysonlinewinmac/"><u>[Updated] 2024 Approved  How to Download Youtube Thumbnail in 3 Ways[Online/Win/Mac]</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-elevate-your-online-statement-with-tiktok-customization/"><u>[Updated] In 2024, Elevate Your Online Statement with TikTok Customization</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-apex-video-and-tune-constructor-studio-quality-pc-edition/"><u>[New] Apex Video & Tune Constructor  Studio-Quality PC Edition</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-learn-how-video-montages-were-used-over-film-history-with-examples-and-the-types-of-videos-for-shorter-montages-plus-learn-about-the-best-software-f/"><u>Updated Learn How Video Montages Were Used over Film History with Examples and the Types of Videos for Shorter Montages. Plus, Learn About the Best Software for It</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-navigating-youtube-gaming-live-stream-basics/"><u>[New] Navigating YouTube Gaming  Live Stream Basics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-from-capture-to-share-the-art-of-live-360-broadcasting-on-fb/"><u>[New] From Capture to Share  The Art of Live 360 Broadcasting on FB</u></a></li>
</ul></div>
