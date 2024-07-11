---
title: How to Fix Print Spooler Keeps Stopping on Windows 11 & 7
date: 2024-07-10T16:49:52.095Z
updated: 2024-07-11T16:49:52.095Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Fix Print Spooler Keeps Stopping on Windows 11 & 7
excerpt: This Article Describes How to Fix Print Spooler Keeps Stopping on Windows 11 & 7
keywords: Resolve Print Spooler Issues,Windows 11 Print Spooler Fix Guide,Stop Windows 7 Print Service Failure,Print Spooler Troubleshooting Steps,Fix Print Service Errors in Windows 11 and 7,Preventing Print Spooler Crashes on Windows 10, 11 & 7,Print Service Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/98cce883f8c6d6df0bb852da7eb40767e5514e4304dfa4fcbf005c1298bed966.jpg
---

## How to Fix Print Spooler Keeps Stopping on Windows 11 & 7

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
<li><a href="https://printer-issues.techidaily.com/instantaneous-fix-guide-unwinding-pcl-xl-errors/"><u>Instantaneous Fix Guide: Unwinding PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/identified-non-printer-owners-computer-mischief/"><u>Identified Non-Printer Owner's Computer Mischief</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-from-sleep-troubleshooting-usb-printer-not-working/"><u>Wake From Sleep: Troubleshooting USB Printer Not Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/full-colors-unavailable-on-printout/"><u>Full Colors Unavailable on Printout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unjamming-print-heads-a-practical-approach/"><u>Unjamming Print Heads: A Practical Approach</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrading-to-flawless-mf4770n-operation-in-windows-1187/"><u>Upgrading to Flawless MF4770n Operation in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rescue-mission-for-my-non-reactive-printer/"><u>Rescue Mission for My Non-Reactive Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-colored-images/"><u>Unable to Print Colored Images</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-response-from-my-canon-printout-machine/"><u>No Response From My Canon Printout Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-tackle-windows-11-printer-malfunctions/"><u>How to Tackle Windows 11 Printer Malfunctions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-print-misstep-code-oxc4eb827f/"><u>Fixing HP Print Misstep: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-users-guide-to-hp-printer-installation/"><u>Windows User's Guide to HP Printer Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-windows-117-hp-printer-errors/"><u>Overcoming Windows 11/7 HP Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024s-guide-to-perfectly-pairing-hp-printer-with-laptops/"><u>2024'S Guide to Perfectly Pairing HP Printer with Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-stopped-working-after-windows-10-update/"><u>SOLVED: Printer Stopped Working After Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-status-fluctuation-on-windows-7/"><u>Resolved Printer Status Fluctuation on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-not-printing-solved/"><u>HP Printer Not Printing [SOLVED]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-support-tip-reveal-hidden-printer-on-your-pc/"><u>[Tech Support Tip] Reveal Hidden Printer on Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/maintaining-optimal-printer-performance/"><u>Maintaining Optimal Printer Performance</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-lags-in-printing/"><u>Immediate Fixes for Lags in Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-compatibility-unable-to-connect-to-hp-print-service-on-windows/"><u>[OS Compatibility] - Unable to Connect to HP Print Service on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/image-guide-to-install-and-connect-canon-printers/"><u>Image Guide to Install and Connect Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-hp-printer-error-0xoxc4eb827f/"><u>Tackling HP Printer Error 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-easy-wi-fi-connectivity-for-canon/"><u>Enabling Easy Wi-Fi Connectivity for Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypassing-fault-error-eco-error-xf1/"><u>Bypassing Fault: Error #Eco-Error XF1</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-solve-brother-printer-offline-problem/"><u>How to Solve Brother Printer Offline Problem</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unlimited-tiktok-videos-no-watermarks-free-downloads-for-2024/"><u>[New] Unlimited TikTok Videos  No Watermarks, Free Downloads for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-best-of-the-best-top-5-video-editing-apps-for-iphone-this-year/"><u>Updated Best of the Best Top 5 Video Editing Apps for iPhone This Year</u></a></li>
<li><a href="https://extra-tips.techidaily.com/leading-brands-car-compatible-viewing-devices/"><u>Leading Brands' Car-Compatible Viewing Devices</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-hot-40-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Hot 40 Phone FRP Lock</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-windows-phone-apps-for-your-cinematic-journey/"><u>Best Windows Phone Apps for Your Cinematic Journey</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-honor-x9b-device-sim-by-drfone-android/"><u>Easily Unlock Your Honor X9b Device SIM</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-infinix-hot-40i-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Infinix Hot 40i Phones with/without a PC</u></a></li>
<li><a href="https://facebook.techidaily.com/reactivating-trumps-virtual-social-hub/"><u>Reactivating Trump's Virtual Social Hub</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-transform-your-memories-best-online-photo-and-video-collage-apps/"><u>Updated 2024 Approved Transform Your Memories Best Online Photo and Video Collage Apps</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/behind-the-scenes-guide-to-elusive-instagram-tools-for-2024/"><u>Behind-the-Scenes Guide to Elusive Instagram Tools for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-the-pros-guide-to-iphone-voice-memos-and-more/"><u>[Updated] 2024 Approved  The Pro's Guide to iPhone Voice Memos and More</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-cutting-edge-game-recording-for-league-of-legends-lol-players/"><u>In 2024, Cutting-Edge Game Recording for League of Legends LoL Players</u></a></li>
<li><a href="https://some-guidance.techidaily.com/uniting-zooms-power-with-facebook-live-streaming-for-2024/"><u>Uniting Zoom's Power with Facebook LIVE Streaming for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-unlock-chromes-full-potential-with-pip-across-devices-for-2024/"><u>[New] Unlock Chrome's Full Potential with PIP Across Devices for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-8-stunning-movie-creator-for-mac/"><u>New In 2024, 8 Stunning Movie Creator for Mac</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-mastering-the-art-of-iphones-detailed-photography/"><u>[Updated] 2024 Approved  Mastering the Art of iPhone's Detailed Photography</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-top-12-solutions-to-decipher-and-display-hidden-video-posts-on-fb/"><u>[New] Top 12 Solutions to Decipher and Display Hidden Video Posts on FB</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/device-unlock-xiaomi-redmi-note-12r-by-drfone-android-unlock-android-unlock/"><u>Device unlock  Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-select-20-humorous-incarceration-posts-to-infuse-positivity-into-facebook-feeds/"><u>In 2024, Select 20 Humorous Incarceration Posts to Infuse Positivity Into Facebook Feeds</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-best-music-player-software-for-android-for-2024/"><u>[New] Best Music Player Software for Android for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transforming-pixels-to-audible-artistry/"><u>In 2024, Transforming Pixels to Audible Artistry</u></a></li>
<li><a href="https://fox-helps.techidaily.com/leveraging-android-for-immersive-virtual-and-360-videos/"><u>Leveraging Android for Immersive Virtual and 360 Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-advanced-tips-for-zooms-video-filters/"><u>[New] 2024 Approved  Advanced Tips for Zoom's Video Filters</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-dynamic-viewership-statistics-platforms/"><u>[New] 2024 Approved  Dynamic Viewership Statistics Platforms</u></a></li>
</ul></div>
