---
title: Resolving Frequent Spooler Halt Issues on PCs Running Windows
date: 2024-07-10T17:05:29.832Z
updated: 2024-07-11T17:05:29.832Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolving Frequent Spooler Halt Issues on PCs Running Windows
excerpt: This Article Describes Resolving Frequent Spooler Halt Issues on PCs Running Windows
keywords: Spooler Halt Issues,PC Frequent Halt,Windows System Halt,Fixing Halt Problems,Resolving Spooler Errors,Troubleshoot Spooler Failure,Stop Spooler Crashes in Windows
thumbnail: https://thmb.techidaily.com/30c3f68025cf60445ca0af9503de0d05421151fac72dff09f39b3449e1fcd630.jpg
---

## Resolving Frequent Spooler Halt Issues on PCs Running Windows

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
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-the-cause-of-hp-printers-white-sheets/"><u>Zeroing In on the Cause of HP Printer’s White Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-4630-driver-download-and-update/"><u>HP Officejet 4630 Driver Download & Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-methods-quickly-connect-hp-to-laptops/"><u>New Methods: Quickly Connect HP to Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-operational-efficiency-with-mf4770n-on-w11w8w7-windows/"><u>Boost Operational Efficiency with MF4770n on W11/W8/W7 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-crisis-averted-zeroing-out-error-0x00000709/"><u>Printer Setup Crisis Averted - Zeroing Out Error (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574163521-windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-non-operation-on-windows-7-post-sleep/"><u>USB Printer Non-Operation on Windows 7 Post Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-seamless-transition-update-mf4770n-on-w11win8w7/"><u>Achieve Seamless Transition: Update MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-setting-up-hp-projetronics-with-pc/"><u>Guide: Setting up HP Projetronics with PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-successful-driver-installation-for-hp-d1360/"><u>Hardware Setup: Successful Driver Installation for HP D1360?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-post-upgrade-success-story/"><u>Printer Problem Post Upgrade: Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-inkjet-now-functioning-correctly/"><u>Epson Inkjet, Now Functioning Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-in-effect-for-b200/"><u>Fix In Effect for B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/proactive-measures-immediate-resolution-of-pcl-xl-problems/"><u>Proactive Measures: Immediate Resolution of PCL XL Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-print-drivers-troubleshooting-across-windows-versions/"><u>HP Deskjet D1360 Print Drivers: Troubleshooting Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-and-tricks-connecting-your-canon-instantly/"><u>Tips & Tricks: Connecting Your Canon Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ultimate-tips-for-canon-print-setup/"><u>Ultimate Tips for Canon Print Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-malfunction-mystery/"><u>Unraveling Printer Malfunction Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-repair-hp-networking-issue-ended/"><u>Successful Repair: HP Networking Issue Ended</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-scannerprinter-blank-page-mystery-solved/"><u>Epson Scanner/Printer Blank Page Mystery Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-107-solved/"><u>HP Printer Offline Status on Windows 10/7 [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-issue-printer-drivers-failing-on-w7-10-need-solution/"><u>[Technical Issue] Printer Drivers Failing on W7-10, Need Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-issues-in-print-device-installation/"><u>No Issues in Print Device Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-driver-download-for-windows/"><u>HP Officejet Pro 8600 Driver Download for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-struggle-hp-deskjet-d1360-not-installing-on-w7-10/"><u>[Setup Struggle] HP Deskjet D1360 Not Installing on W7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-spits-out-unprinted-sheets/"><u>Resolved: Printer Spits Out Unprinted Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-error-only-blank-sheets-from-epson/"><u>Printer Setup Error: Only Blank Sheets From Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-default-problem-error-0x00000709-fixed/"><u>Unraveling Printer Default Problem - Error 0X00000709 Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stopping-printer-service-pauses-solutions-for-windows-10w7w11/"><u>Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574049626-fix-print-job-stuck-in-queue-quickly/"><u>Fix 'Print Job Stuck in Queue' Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/service-not-active-local-printer-spooler/"><u>Service Not Active: Local Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printers-odd-behavior-unnecessary-paper-usage/"><u>Epson Printer's Odd Behavior: Unnecessary Paper Usage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-unresponsive-on-pc/"><u>Print Spooler Service Unresponsive on PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-lava-yuva-3-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Lava Yuva 3 and Browser | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-secrets-of-filmo/"><u>In 2024, Secrets of Filmo</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-on-apple-iphone-7-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock On Apple iPhone 7 You Should Try Out</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-screen-streaming-showdown-face-off-between-obs-and-shadowtoolkit/"><u>[New] Screen Streaming Showdown  Face Off Between OBS & ShadowToolKit</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-youtube-mastery-comprehensive-editing-for-lifelong-learners/"><u>2024 Approved  YouTube Mastery  Comprehensive Editing for Lifelong Learners</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-dissecting-youtube-chatter/"><u>[New] 2024 Approved  Dissecting YouTube Chatter</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/efficiency-in-advertising-post-facebook-algorithm-overhaul/"><u>Efficiency in Advertising Post-Facebook Algorithm Overhaul</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-mastering-effective-social-media-video-promos/"><u>[Updated] In 2024, Mastering Effective Social Media Video Promos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professionals-picks-best-10-no-price-cross-platform-photo-editing-software/"><u>In 2024, Professionals' Picks  Best 10 No-Price, Cross-Platform Photo Editing Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-screenshotsweeperpro-next-gen-bg-removal-tool/"><u>[New] ScreenshotSweeperPro  Next-Gen BG Removal Tool</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/mkvtoolnix-mac-streamline-your-video-editing-workflow-for-2024/"><u>MKVtoolnix Mac Streamline Your Video Editing Workflow for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/essential-tips-record-powerpoint-live-with-webcam/"><u>Essential Tips  Record PowerPoint Live with Webcam</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-integrating-external-websites-into-instagrams-ecosystem/"><u>[Updated] 2024 Approved  Integrating External Websites Into Instagram's Ecosystem</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-se-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone SE</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Realme Narzo N53? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/tailor-made-melodies-your-roadmap-for-playlists-for-2024/"><u>Tailor-Made Melodies  Your Roadmap for Playlists for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-monetizing-success-a-strategic-approach/"><u>[New] Monetizing Success  A Strategic Approach</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-encyclopedia-of-hands-on-detection/"><u>[New] The Encyclopedia of Hands-On Detection</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-art-of-instagram-video-filming/"><u>Unveiling the Art of Instagram Video Filming</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-enhance-creativity-top-50plus-inspirational-tiktok-quotes/"><u>In 2024, Enhance Creativity  Top 50+ Inspirational TikTok Quotes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-best-practices-8-steps-for-digital-sound-preservation/"><u>[New] 2024 Approved  Best Practices  8 Steps for Digital Sound Preservation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-cutting-edge-video-meeting-techniques-on-slack-plus-filmora/"><u>[Updated] In 2024, Cutting-Edge Video Meeting Techniques on Slack + Filmora</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-dissecting-the-narrative-in-youtube-dialogues/"><u>[New] Dissecting the Narrative in YouTube Dialogues</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-from-stills-to-movies-a-pixiz-tutorial-for-photo-animators/"><u>In 2024, From Stills to Movies  A Pixiz Tutorial for Photo Animators</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-edition-the-definitive-strategy-for-youtube-monetization/"><u>[New] 2024 Edition  The Definitive Strategy for YouTube Monetization</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cost-breakdown-for-youtube-ads-for-2024/"><u>Cost Breakdown for YouTube Ads for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-6-virtual-venues-propelling-professional-connections/"><u>2024 Approved  Leading 6 Virtual Venues Propelling Professional Connections</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Sony Xperia 5 V | Dr.fone</u></a></li>
</ul></div>
