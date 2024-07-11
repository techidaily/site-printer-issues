---
title: "End Repeated Print Job Failures: Guide for Windows 10/7 Users"
date: 2024-07-10T16:51:43.109Z
updated: 2024-07-11T16:51:43.109Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes End Repeated Print Job Failures: Guide for Windows 10/7 Users"
excerpt: "This Article Describes End Repeated Print Job Failures: Guide for Windows 10/7 Users"
keywords: Windows 10 Print Troubleshooting,Preventing Printer Errors (Windows 7/10),Print Job Repeats Fix,Windows 10 Print Settings Optimization,Effective Printer Maintenance Guide (Windows),Resolve Repeated Print Failures in Windows,Windows Printer Settings (Troubleshooting)
thumbnail: https://thmb.techidaily.com/1fae0ad394ab82a99f86e121c7a2e9769c50867e0c2a328f8756769b7a14fb25.jpg
---

## End Repeated Print Job Failures: Guide for Windows 10/7 Users

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
<li><a href="https://printer-issues.techidaily.com/optimize-functionality-upgrading-mf4770n-on-w11w8w7-os/"><u>Optimize Functionality: Upgrading MF4770n on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-an-idle-brothers-printer-networkly/"><u>How to Reactivate an Idle Brothers Printer Networkly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combating-printers-error-x97-in-epson/"><u>Combating Printer's Error X97 in Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-cant-print-spooler-disabled/"><u>[ISSUE] Can't Print - Spooler Disabled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-reviving-dormant-hp-flexscribe-machines/"><u>Guide to Reviving Dormant HP FlexScribe Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-nightmares-solutions-here/"><u>Windows 11 Printer Nightmares? Solutions Here</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-bars-in-hp-printers-output/"><u>Eliminating Ghost Bars in HP Printer's Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-unresponsive-need-a-lifeline/"><u>Canon Printer: Unresponsive, Need A Lifeline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/maximize-mf4770n-in-windows-1087-systems/"><u>Maximize MF4770n in WIndows 10/8/7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printers-from-windows-system/"><u>Eradicating Printers From Windows System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-wasted-time-fixing-windows-78s-non-operational-spooler/"><u>Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domains-offline-causing-printer-errors/"><u>Domains Offline - Causing Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-non-responsive-printer-in-windows-11/"><u>Resolve Non-Responsive Printer in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplified-process-of-configuring-and-connecting-a-canon-printer/"><u>Simplified Process of Configuring & Connecting a Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-top-5-methods-to-resolve-canon-printer-print-issue-in-windows-11/"><u>Quick Fixes: Top 5 Methods to Resolve Canon Printer Print Issue in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-windows-10-printer-setup-woes/"><u>Tackle Windows 10 Printer Setup Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-print-functionality-after-win-11-update/"><u>Restored Print Functionality After Win 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-your-silent-canon-printer-now/"><u>Reconnect Your Silent Canon Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-restoration-of-active-print-queue/"><u>Quick Restoration of Active Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-rejoined-print-device/"><u>Instantly Rejoined Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problems-windows-xp-10-printer-vanishes/"><u>[Network Problems] Windows XP-10, Printer Vanishes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-speed-and-accuracy-on-windows-11/"><u>Fix Printing Speed and Accuracy on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-drivers-not-found-error-on-w11-systems/"><u>Fix Drivers Not Found Error on W11 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-my-printer-skips-colors/"><u>Why My Printer Skips Colors?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-the-epson-fix/"><u>Error Code 0X97: The Epson Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-printer-problem-5-quick-steps-to-enable-print-on-canon-and-windows-11-combo/"><u>Resolve Printer Problem: 5 Quick Steps to Enable Print on Canon & Windows 11 Combo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-due-to-current-domain-services-outage/"><u>Print Issue Due to Current Domain Services Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-your-hp-laserjet-remote-connection/"><u>Setting Up Your HP LaserJet Remote Connection</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-launching-success-on-youtube-tutorial-with-two-strategies/"><u>2024 Approved  Launching Success on YouTube  Tutorial with Two Strategies</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-audio-anomalies-top-disruptive-apps-on-the-go/"><u>[New] Audio Anomalies  Top Disruptive Apps on the Go</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-iphone-13-pro-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-honor-100-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-realme-11-pro-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Realme 11 Pro Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-tecno-spark-10-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Tecno Spark 10 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/cross-platform-playmates-top-15-friendly-games-to-share/"><u>Cross-Platform Playmates: Top 15 Friendly Games to Share</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-metaverse-versus-multimetase-analyzing-their-core-disparities/"><u>2024 Approved  Metaverse Versus MultiMetase  Analyzing Their Core Disparities</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cultivating-the-culture-of-creativity-within-youtube-shorts-for-2024/"><u>Cultivating the Culture of Creativity Within YouTube Shorts for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-uniting-your-feeds-posting-videos-from-twitter-on-snapchat/"><u>[Updated] 2024 Approved  Uniting Your Feeds  Posting Videos From Twitter on Snapchat</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/from-snapshots-to-delights-viral-eats-you-need-in-your-life/"><u>From Snapshots to Delights  Viral Eats You Need in Your Life</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-samsung-galaxy-xcover-6-pro-tactical-edition-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Samsung Galaxy XCover 6 Pro Tactical Edition FRP Bypass</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-samsung-galaxy-f34-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Samsung Galaxy F34 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamlining-your-remote-podcast-production-workflow/"><u>[Updated] Streamlining Your Remote Podcast Production Workflow</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-upgrade-your-content-presentation-with-top-tier-templates/"><u>In 2024, Upgrade Your Content Presentation with Top-Tier Templates</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-uncover-the-best-practices-for-video-seo-on-facebook/"><u>[New] Uncover the Best Practices for Video SEO on Facebook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-luts-unveiled-transforming-the-lands-market/"><u>2024 Approved  LUTs Unveiled  Transforming the Lands Market</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-co-marketing-brands-and-youtubes-dynamic-duo/"><u>[Updated] In 2024, Co-Marketing  Brands and YouTube's Dynamic Duo</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-masterclass-for-srt-editing-in-macos/"><u>2024 Approved  Masterclass for SRT Editing in macOS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-10-athletic-free-front-rows-for-relaxing/"><u>[Updated] 10 Athletic-Free Front Rows for Relaxing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-8-best-mirrorless-cameras-vloggers-should-know/"><u>[Updated] 2024 Approved  8 Best Mirrorless Cameras Vloggers Should Know</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-draw-cartoons-step-by-step-with-this-guide/"><u>How to Draw Cartoons Step by Step with This Guide</u></a></li>
</ul></div>
