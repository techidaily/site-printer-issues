---
title: Eliminate Constant Spooler Pauses Across Win Versions
date: 2024-07-10T17:42:03.783Z
updated: 2024-07-11T17:42:03.783Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Eliminate Constant Spooler Pauses Across Win Versions
excerpt: This Article Describes Eliminate Constant Spooler Pauses Across Win Versions
keywords: Eliminate SPOOLER Pauses,Constant Spooler Pause Reduction,Performance Optimization for Win SPOOLER Pauses,Troubleshoot Constant Spooler in Windows,Remedy Win SPOOLER Delays,Eliminate Spooler Latency in Windows Versions,Resolve SPOOLER Interruptions on Win Systems
thumbnail: https://thmb.techidaily.com/db587631bccc11018e71b0f197be1378b7d1dbbecd5a463368074dbdb88b8238.jpg
---

## Eliminate Constant Spooler Pauses Across Win Versions

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
<li><a href="https://printer-issues.techidaily.com/overcoming-epson-error-code-0x97/"><u>Overcoming Epson Error Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-load-printer-driver-not-detected-by-win/"><u>Cannot Load Printer: Driver Not Detected by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-print-server-disconnect/"><u>Overcoming Print Server Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-blank-pages-windows-11-printer-woes/"><u>Fix Blank Pages: Windows 11 Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-wireless-printing-issue-with-hp-envy-5680v5/"><u>Fixed Wireless Printing Issue with HP Envy 5680V5</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-a-siblings-printer-out-of-network-hibernation/"><u>Bringing a Sibling's Printer Out of Network Hibernation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-setup-for-officejet-pro-m110-series-a-complete-walkthrough/"><u>Wireless Setup for Officejet Pro M110 Series: A Complete Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-pcs-error-b200/"><u>Fixed PC's Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unforeseen-setup-snag-found/"><u>Printer's Unforeseen Setup Snag Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-searches-for-non-existent-printer-driver/"><u>Windows Searches for Non-Existent Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-hook-up-your-hp-officejet-pro-duo/"><u>Quick Guide: Hook Up Your HP Officejet Pro Duo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-drive-functionality-with-mf4770n-on-windows-oss/"><u>Enhanced Drive Functionality with MF4770n on WIndows OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-and-configure-hp-wireless-printer/"><u>How to Connect & Configure HP Wireless Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-network-printer-service-in-standby-mode/"><u>Local Network Printer Service in Standby Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-disabled-scan-in-win11/"><u>Reviving Disabled Scan in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-correction-implemented/"><u>B200 Correction Implemented</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-and-canons-mp620-a-driver-match/"><u>Windows 11 & Canon's MP620: A Driver Match?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-code-xf34/"><u>Troubleshooting HP Printer Code #XF34</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-canon-printer-with-ease-on-wi-fi/"><u>Setting Up Canon Printer with Ease on Wi-Fi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-epsons-puzzling-error-x97/"><u>Tackling Epson's Puzzling Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-obstacles-in-adding-new-printer-to-network/"><u>No Obstacles in Adding New Printer to Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-streamline-of-hindered-printer-jobs/"><u>Quick Streamline of Hindered Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-paper-size-error-on-hp-deskjet-3070/"><u>Fixed Paper Size Error on HP DeskJet 3070</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-secrets-of-pcl-xl-repairs/"><u>Unraveling the Secrets of PCL XL Repairs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-pcs-scanner-connection-on-win10/"><u>Reactivating PC's Scanner Connection on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-repairing-epson-printer-issues/"><u>Successfully Repairing Epson Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-gap-fast-printer-connection/"><u>Bridging Gap: Fast Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fixed-after-new-windows-version-patch/"><u>Printer Fixed After New Windows Version Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-solve-brother-printer-offline-problem/"><u>How to Solve Brother Printer Offline Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensure-reliability-update-printer-software-for-win7-users/"><u>Ensure Reliability: Update Printer Software for Win7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systemissue-printer-spooler-not-functioning-in-windows/"><u>[SYSTEM_ISSUE] Printer Spooler Not Functioning in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanner-disconnection-issue-in-windows-10/"><u>Fixing Scanner Disconnection Issue in Windows 10</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/top-rated-audio-editing-software-for-macos-identifying-the-ultimate-mp3-trimmer/"><u>Top-Rated Audio Editing Software for macOS Identifying the Ultimate MP3 Trimmer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-art-of-duality-mastering-image-turnover-on-social-media-giants/"><u>In 2024, The Art of Duality  Mastering Image Turnover on Social Media Giants</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-how-to-make-gif-stickers-for-whatsapp-100-the-simple-way/"><u>2024 Approved How to Make GIF Stickers for WhatsApp 100 The Simple Way</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-unlock-creative-closure-ideas-with-our-template-service/"><u>[Updated] Unlock Creative Closure Ideas with Our Template Service</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-infinix-note-30-5g-drfone-by-drfone-android/"><u>How to Screen Mirroring Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-chorus-to-clips-soundtracking-in-imovie/"><u>2024 Approved  Chorus to Clips  Soundtracking in iMovie</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-most-admired-iphone-based-podcast-platforms/"><u>[New] Most Admired iPhone-Based Podcast Platforms</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-free-easy-hd-download-of-fb-media-library/"><u>[Updated] In 2024, Free, Easy HD Download of FB Media Library</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/mastering-live-broadcasts-obs-tips-for-youtube-and-twitch/"><u>Mastering Live Broadcasts  OBS Tips for YouTube & Twitch</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-sifting-through-the-sands-of-youtube-conversations/"><u>[Updated] Sifting Through the Sands of YouTube Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-best-dark-moody-luts-during-editing/"><u>2024 Approved Best Dark Moody LUTs During Editing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/elevate-your-content-game-with-extended-instagram-videos-for-2024/"><u>Elevate Your Content Game with Extended Instagram Videos for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-amazon-prime-viewers-who-to-follow-on-twitter-now/"><u>In 2024, Amazon Prime Viewers - Who to Follow on Twitter, Now</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-ultimate-instagram-captioning-hack-for-reels-and-stories-for-2024/"><u>[New] The Ultimate Instagram Captioning Hack for Reels and Stories for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-proactive-preservation-ios-photos-to-your-snap-story/"><u>2024 Approved  Proactive Preservation  IOS Photos to Your Snap Story</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-5-pro-tips-to-perfectly-tag-videos-and-maximize-views/"><u>[Updated] 5 Pro Tips to Perfectly Tag Videos and Maximize Views</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-your-pc-snipping-guide-the-best-tools-to-try-first-for-2024/"><u>[New] Your PC Snipping Guide  The Best Tools to Try First for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-crafting-captivating-real-time-tweets-for-maximum-impact/"><u>In 2024, Crafting Captivating Real-Time Tweets for Maximum Impact</u></a></li>
</ul></div>
