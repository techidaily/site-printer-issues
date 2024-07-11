---
title: Preventing Constant Interruptions From Spooler Service in Win10/7
date: 2024-07-10T17:07:10.797Z
updated: 2024-07-11T17:07:10.797Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventing Constant Interruptions From Spooler Service in Win10/7
excerpt: This Article Describes Preventing Constant Interruptions From Spooler Service in Win10/7
keywords: Windows 10 Spooler Service Issues,Stop Spooler Service Interruptions in Windows,Resolve Win10/7 Spooler Disruption,Preventing Spooler Service Crashes in Win10,Fix Constant Interruptions From Spooler in Windows 10/7,How to Stop Spooler Service Failures on Windows 7,Troubleshoot Spooler Service Problems in Windows Operating Systems
thumbnail: https://thmb.techidaily.com/992704407ab581931890c09cce338091c04f10f6ec09034fcef1854347c08c6c.jpg
---

## Preventing Constant Interruptions From Spooler Service in Win10/7

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
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-no-more-windows-7/"><u>Epson Printer Offline No More, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-intermittent-printer-spooler-halt-in-win-117/"><u>Resolving Intermittent Printer Spooler Halt in Win 11/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/intruder-in-network-print-spotlighted/"><u>Intruder in Network Print Spotlighted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-linked-in-seconds/"><u>Printer Linked in Seconds</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-found-inkjet-not-printing-epson/"><u>Fix Found: Inkjet Not Printing [Epson]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immaculate-documents-from-hp-printer-post-correction/"><u>Immaculate Documents From HP Printer Post-Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-connect-canon-printer-online/"><u>Effortlessly Connect Canon Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-out-error-0x00000709-for-printer-settings/"><u>Zeroing Out Error 0X00000709 for Printer Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-canon-device-that-wont-react/"><u>Reviving a Canon Device That Won't React</u></a></li>
<li><a href="https://printer-issues.techidaily.com/foreign-system-flagged-for-misused-printer/"><u>Foreign System Flagged for Misused Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-printer-connection-swiftly/"><u>Restore Printer Connection Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-7-devices-not-recognizing-post-sleep-usb-printers/"><u>[Fix] Windows 7 Devices Not Recognizing Post Sleep USB Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-post-update-fix/"><u>Printer Error Post-Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-due-to-current-domain-services-outage/"><u>Print Issue Due to Current Domain Services Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-brother-printer-print-operation-in-windows-oses/"><u>Streamlining Brother Printer Print Operation in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-domain-down-resulting-in-printer-failure/"><u>AD Domain Down - Resulting In Printer Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-officejet-paper-jams-step-by-step-solution/"><u>Win11 OfficeJet Paper Jams: Step-by-Step Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-non-printing-issues-five-tactics-to-get-your-canon-running-in-windows-11/"><u>Troubleshoot Non-Printing Issues: Five Tactics to Get Your Canon Running in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-v305-aio-printer-driver-update-in-windows-7/"><u>Dell V305 AIO Printer Driver Update in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-hp-printers-error-code-oxc4eb827f/"><u>Eliminating HP Printer's Error Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-brother-printer-not-printing-on-windows-1110/"><u>How to Fix Brother Printer Not Printing on Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-installation-of-multi-function-printer/"><u>Successful Installation of Multi-Function Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-install-a-new-canon-printer-step-by-step/"><u>How To Install a New Canon Printer (Step-by-Step)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-driver-not-located-by-win/"><u>Printer Error: Driver Not Located by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-stuck-printer-operations/"><u>Accelerate Stuck Printer Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-print-process-uncover-these-simple-steps-for-non-printing-canon-on-windows-11/"><u>Streamline Print Process: Uncover These Simple Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-configuration-error/"><u>Gear Up Glitch: Printer Configuration Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connecting-laptops-with-hp-printers-top-3-improvement-tips/"><u>Connecting Laptops with HP Printers - Top 3 Improvement Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-not-working-on-windows-11-windows-11-printer-issues/"><u>[FIXED] Printer Not Working on Windows 11? Windows 11 Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/farewell-to-printer-frustration-win-10s-solution-found/"><u>Farewell to Printer Frustration: Win 10'S Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-endless-white-paper-output/"><u>Epson Photo Printer: Endless White Paper Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-printer-performance-tips/"><u>Swift Printer Performance Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-communications-unavailable/"><u>Print Issue: Communications Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-uncooperative-printer-status-on-winntme-os/"><u>Fixing Uncooperative Printer Status on WinNT/Me OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-from-lurker-to-leader-the-roadmap-to-higher-fb-page-rankings/"><u>[New] From Lurker to Leader  The Roadmap to Higher FB Page Rankings</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-exclude-automatic-recommended-podcasts-in-spotify-feed/"><u>[Updated] Exclude Automatic Recommended Podcasts in Spotify Feed</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-new-windows-11-hacks-for-efficiency-experts/"><u>[New] In 2024, New Windows 11 Hacks for Efficiency Experts</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-honor-90-gt-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Honor 90 GT Safely | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/unlocking-the-secrets-to-overwatch-video-capture-for-2024/"><u>Unlocking the Secrets to Overwatch Video Capture for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tackling-photo-app-errors-in-windows-11/"><u>[Updated] Tackling Photo App Errors in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-ultimate-trick-to-share-igtv-in-stories/"><u>[Updated] The Ultimate Trick to Share IGTV in Stories</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-amplifying-video-clarity-on-youtube/"><u>2024 Approved  Amplifying Video Clarity on YouTube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-10-hidden-functions-to-enhance-your-canva-artistry/"><u>2024 Approved  Top 10 Hidden Functions to Enhance Your Canva Artistry</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-leaders-in-likeability-the-best-app-list-on-androidiphone/"><u>[New] 2024 Approved  Leaders in Likeability  The Best App List on Android/iPhone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-tecno-spark-10-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Tecno Spark 10 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-transforming-hidden-content-fb-video-strategies/"><u>[Updated] In 2024, Transforming Hidden Content  FB Video Strategies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-xiaomi-mix-fold-3-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Xiaomi Mix Fold 3 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-mavericks-video-editors-handbook-a-step-by-step-guide-for-2024/"><u>New Mavericks Video Editors Handbook A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-6-essential-tools-for-creating-engaging-movie-introduction-videos-for-2024/"><u>Updated 6 Essential Tools for Creating Engaging Movie Introduction Videos for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-create-stunning-animations-top-ios-and-android-stop-motion-apps/"><u>New Create Stunning Animations Top iOS and Android Stop Motion Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-proven-choices-selecting-the-top-6-costless-cloud-based-sound-editors-for-2024/"><u>Updated Proven Choices Selecting the Top 6 Costless Cloud-Based Sound Editors for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/from-social-networks-to-personal-messages-twitchs-journey-through-whatsapp-for-2024/"><u>From Social Networks to Personal Messages  Twitch's Journey Through WhatsApp for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-step-by-step-protocol-for-unearthing-hidden-gems-in-discord-servers/"><u>[New] Step-by-Step Protocol for Unearthing Hidden Gems in Discord Servers</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-infinix-zero-30-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Infinix Zero 30 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/yogic-alchemy-transform-your-body-mind-and-spirit/"><u>Yogic Alchemy - Transform Your Body, Mind & Spirit</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-brightness-to-twitch-video-playback/"><u>Restoring Brightness to Twitch Video Playback</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevating-your-videos-status-on-youtube-for-2024/"><u>[New] Elevating Your Video's Status on YouTube for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-best-mac-video-capturing-software-post-bandicam-revolution/"><u>[Updated] In 2024, Best Mac Video Capturing Software  Post-Bandicam Revolution</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-itel-a60s-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Itel A60s</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-tecno-spark-10c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-recommended-steadicams-for-drone-videography/"><u>[Updated] Expert-Recommended Steadicams for Drone Videography</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/soundscapes-for-vimeo-a-compreayers-manual-for-2024/"><u>Soundscapes for Vimeo  A Compreayer's Manual for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-best-apps-for-recording-and-editing-reaction-videos-on-the-go/"><u>Updated The Best Apps for Recording and Editing Reaction Videos on the Go</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigating-iphones-most-popular-watermarking-software-solutions-for-2024/"><u>Navigating iPhone's Most Popular Watermarking Software Solutions for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-clear-path-a-step-by-step-approach-to-buying-an-exceptional-4k-monitor/"><u>The Clear Path  A Step-By-Step Approach to Buying an Exceptional 4K Monitor</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-how-to-use-inshot-for-laptoppc-and-alternatives-video-editor/"><u>[Updated] In 2024, How to Use Inshot for Laptop/PC and Alternatives Video Editor</u></a></li>
</ul></div>
