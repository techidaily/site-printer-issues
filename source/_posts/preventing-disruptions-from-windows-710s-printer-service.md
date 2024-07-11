---
title: Preventing Disruptions From Windows 7/10'S Printer Service
date: 2024-07-10T17:31:32.745Z
updated: 2024-07-11T17:31:32.745Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventing Disruptions From Windows 7/10'S Printer Service
excerpt: This Article Describes Preventing Disruptions From Windows 7/10'S Printer Service
keywords: Windows 7 Printer Issues,Windows 10 Printer Service Troubleshooting,Printer Connectivity Errors in Windows 7/10,Troubleshoot Windows 7 Printer Service Disruptions,Printer Errors in Windows 10 OS,Prevent Printer Service Downtimes on Windows 7/10,Windows 7/10 Printer Service Maintenance Tips
thumbnail: https://thmb.techidaily.com/f0eb15dbd4d3bc9550ae7ac5d466cfd7136ebba5996edeb6f057c08fddaa5f37.jpg
---

## Preventing Disruptions From Windows 7/10'S Printer Service

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
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-print-experience-with-win-hp-printer-guide/"><u>Streamline Your Print Experience with Win HP Printer Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-status-fluctuation-on-windows-7/"><u>Resolved Printer Status Fluctuation on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-cups-printer-connectivity-in-win7/"><u>Fixing CUPS Printer Connectivity in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-setup-with-win32-officejet-pro-8600-drivers/"><u>Seamless Setup with Win32 Officejet Pro 8600 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-restoring-default-windows-printer-0x00000709/"><u>Error Resolution: Restoring Default Windows Printer (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-hp-printer-offline-in-win7-home/"><u>Fixed HP Printer Offline in Win7 Home</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-access-to-hp-printer-driver-on-win1110/"><u>No Access to HP Printer Driver on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-brother-printer-no-output/"><u>Reviving Brother Printer No Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-overcoming-silent-hp-network-printers/"><u>Guide to Overcoming Silent HP Network Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-streamline-of-hindered-printer-jobs/"><u>Quick Streamline of Hindered Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/set-up-your-mfc-9330cdw-brother-fan/"><u>Set Up Your MFC-9330CDW Brother Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-textless-printouts-on-my-epson-scannerprinter/"><u>Trouble with Textless Printouts on My Epson Scanner/Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-dead-printers-on-windows-11-os/"><u>Revive Dead Printers on Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-printer-status-bring-back-your-brothers-printer/"><u>Reclaiming Printer Status: Bring Back Your Brother's Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-error-unforeseen-setup-glitch-detected/"><u>Print Error: Unforeseen Setup Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/all-pages-printer-output-ready/"><u>All Pages Printer Output Ready</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-black-screen-issue-on-hp-printer/"><u>Tackling Black Screen Issue on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-air-glide-instructions-quickly/"><u>Brother CDW Air-Glide Instructions Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-text-only-paper-the-epson-printer-glitch/"><u>No Text, Only Paper: The Epson Printer Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-woes-here-are-your-five-easy-fixes-in-windows-11/"><u>Canon Printer Woes? Here Are Your Five Easy Fixes in Windows 11!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-connect-canon-printer-online/"><u>Effortlessly Connect Canon Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-faulty-connectivity-in-printers/"><u>Diagnosing Faulty Connectivity in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-bars-in-hp-printers-output/"><u>Eliminating Ghost Bars in HP Printer's Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-re-enable-scanned-device-connection/"><u>Windows 10: Re-Enable Scanned Device Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-print-problem-after-win-11-update/"><u>Resolved Print Problem After Win 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-service-from-frequently-stopping/"><u>Stop Windows Print Service From Frequently Stopping</u></a></li>
<li><a href="https://printer-issues.techidaily.com/five-tips-to-reignite-the-print-on-your-canon-printer-in-windows-11-os/"><u>Five Tips to Reignite the Print on Your Canon Printer in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-link-to-computer-post-update/"><u>Reactivating Scanner Link to Computer Post-Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mysterious-printer-misfit-found/"><u>Mysterious Printer Misfit Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-pages-be-gone-hp-printer-now-fully-functional/"><u>Blank Pages Be Gone: HP Printer Now Fully Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-steps-for-stubborn-printer/"><u>Troubleshooting Steps for Stubborn Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-seamless-transition-update-mf4770n-on-w11win8w7/"><u>Achieve Seamless Transition: Update MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-disconnected-scanner-issue-in-windows-10/"><u>Resolving Disconnected Scanner Issue in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivate-idle-printing-queue-task/"><u>Reactivate Idle Printing Queue Task</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-audio-experience-for-switch/"><u>Superior Audio Experience for Switch</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-joining-the-digital-conversation-zooming-effortlessly-with-android/"><u>2024 Approved  Joining the Digital Conversation  Zooming Effortlessly with Android</u></a></li>
<li><a href="https://extra-skills.techidaily.com/secrets-for-hiring-top-notch-video-professionals-for-2024/"><u>Secrets for Hiring Top-Notch Video Professionals for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-expertly-crafted-video-making-software-iphone-android-for-2024/"><u>[New] Expertly Crafted Video-Making Software (iPhone, Android) for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-from-strategy-to-success-how-to-launch-top-tier-tiktok-campaigns/"><u>[Updated] From Strategy to Success  How to Launch Top-Tier TikTok Campaigns</u></a></li>
<li><a href="https://extra-hints.techidaily.com/5-pioneering-portals-to-streamline-your-text-effects-search-for-2024/"><u>5 Pioneering Portals to Streamline Your Text Effects Search for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-elevate-your-online-presence-editing-expertise-for-haul-vlogs/"><u>In 2024, Elevate Your Online Presence  Editing Expertise for Haul Vlogs</u></a></li>
<li><a href="https://extra-information.techidaily.com/battle-of-the-titans-gopro-hero4-black-versus-drift-ghost-s/"><u>Battle of the Titans  GoPro Hero4 Black Versus Drift Ghost-S</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-selling-vr-games-on-oculus-devices-for-2024/"><u>Best-Selling VR Games on Oculus Devices for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-edit-and-elevate-instagrams-ultimate-toolkit/"><u>[New] Edit & Elevate  Instagram's Ultimate Toolkit</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-your-ultimate-mobile-development-ally-selecting-the-best-15-android-virtualization-tools/"><u>[Updated] In 2024, Your Ultimate Mobile Development Ally  Selecting the Best 15 Android Virtualization Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-laptop-the-ultimate-guide-to-free-movie-decoders/"><u>[Updated] Laptop  The Ultimate Guide to Free Movie Decoders</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-ultimate-guide-to-forming-your-instagram-company-identity/"><u>In 2024, The Ultimate Guide to Forming Your Instagram Company Identity</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-broadcast-your-curated-playlist-with-ease/"><u>[New] 2024 Approved  Broadcast Your Curated Playlist with Ease</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-inshot-music-syncing-step-by-step-instructions-for-2024/"><u>[New] InShot Music Syncing  Step-by-Step Instructions for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-evaluating-visual-dynamics-the-power-of-luminances-hdr/"><u>2024 Approved  Evaluating Visual Dynamics  The Power of Luminance's HDR</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-best-video-enhancement-apps-for-tiktok-mastery-on-w-indospc/"><u>[New] 2024 Approved  Best Video Enhancement Apps for TikTok Mastery on W Indos/PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-turning-hobby-into-habit-making-money-with-vlogs/"><u>In 2024, Turning Hobby Into Habit  Making Money with Vlogs</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-exploring-beyond-manycam-enhanced-alternatives-in-2024/"><u>[Updated] Exploring Beyond ManyCam  Enhanced Alternatives, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-from-one-world-to-another-connecting-instagram-and-facebook/"><u>[Updated] 2024 Approved  From One World to Another  Connecting Instagram & Facebook</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-how-to-convert-your-vocal-sessions-into-pristine-mp3-files-the-best-5-recorders-reviewed/"><u>New How to Convert Your Vocal Sessions Into Pristine MP3 Files The Best 5 Recorders Reviewed</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/the-ultimate-list-10-best-free-green-screen-apps-for-mobile-phones-for-2024/"><u>The Ultimate List 10 Best Free Green Screen Apps for Mobile Phones for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-expert-approved-hand-drawing-whiteboard-animation-tools/"><u>New In 2024, Expert-Approved Hand Drawing Whiteboard Animation Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-vidmas-advantages-in-digital-video-recording-unpacked/"><u>[Updated] 2024 Approved  Vidma’s Advantages in Digital Video Recording Unpacked</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-motorola-moto-g-stylus-5g-2023-frp-bypass-by-drfone-android/"><u>About Motorola Moto G Stylus 5G (2023) FRP Bypass</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cutting-the-cord-on-costs-select-best-free-yt-title-makers/"><u>[New] In 2024, Cutting the Cord on Costs - Select Best-Free YT Title Makers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-high-quality-audio-extraction-proven-methods-for-video-to-mp3-conversion/"><u>Updated 2024 Approved High-Quality Audio Extraction Proven Methods for Video to MP3 Conversion</u></a></li>
</ul></div>
