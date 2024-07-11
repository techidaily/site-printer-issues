---
title: "Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler"
date: 2024-07-10T17:26:20.475Z
updated: 2024-07-11T17:26:20.475Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler"
excerpt: "This Article Describes Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler"
keywords: Fixing Non-Operational Spooler,Windows 7 Spooler Fix,Windows 8 Spooler Troubleshooting,Stop Spooler Time Wasting,Windows Spooler Error Fix,Optimize Spooler Performance in Windows,Spooler Service Repair Guide
thumbnail: https://thmb.techidaily.com/a333bfbef34affdca1048ed2699696db5230242a15d7fcb3455927615d5179aa.JPG
---

## Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler

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
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-glitch-detected/"><u>Unexpected Print Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-on-laptops-with-improved-hp-printer-links/"><u>Optimize Printing on Laptops with Improved HP Printer Links</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-offline-canon-printer-immediately/"><u>Revive Offline Canon Printer Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-brothers-air-glide-driver/"><u>Install Brother's Air-Glide Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-activation-restored-for-windows-10-users/"><u>Scanner Activation Restored for Windows 10 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-up-call-faulty-usb-printers-in-windows-7-mode/"><u>Wake Up Call: Faulty USB Printers in Windows 7 Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-setup-for-air-glide/"><u>Brother MFC-9330CDW Setup for Air Glide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-compatible-with-online-scanner-again/"><u>Win11 Compatible with Online Scanner Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-post-update-printer-glitches/"><u>Overcoming Post-Update Printer Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connect-printer-with-a-click-no-delay/"><u>Connect Printer with a Click, No Delay</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-epson-printer-paper-jam/"><u>Resolved: Epson Printer Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-setup-with-win32-officejet-pro-8600-drivers/"><u>Seamless Setup with Win32 Officejet Pro 8600 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-epson-paper-jam/"><u>Overcome Epson Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-on-latest-win10-os/"><u>Reactivating Scanner on Latest Win10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-the-printer-after-updating-woes/"><u>Triumph over the Printer After Updating Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-d1360-overcoming-driver-installation-obstacles-in-multiple-os-environments/"><u>HP D1360: Overcoming Driver Installation Obstacles in Multiple OS Environments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-brother-printer-not-printing-quagmire-reinstating-functionality-on-windows/"><u>Combat Brother Printer Not Printing Quagmire, Reinstating Functionality on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-connectivity-between-laptops-and-hp-discover-the-best-fixes/"><u>Instant Connectivity Between Laptops & HP - Discover the Best Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-mf4770n-integration-on-windows-platforms/"><u>Elevate MF4770n Integration on Windows Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-online-after-repair/"><u>Win7 Printer Online After Repair</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-hp-printer-not-responding/"><u>How to Fix HP Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-hp-printer-error-oxc4eb827f/"><u>Eradicating HP Printer Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-simple-steps-to-make-your-canon-printer-work-again/"><u>5 Simple Steps to Make Your Canon Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-enhance-windows-11-8-7-integration/"><u>MF4770n Drivers - Enhance Windows 11, 8, 7 Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-link-issues-fastly/"><u>Fixing Printer Link Issues Fastly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-efficiency-update-hp-officejet-firmware/"><u>Enhance Printing Efficiency: Update HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-maintenance-causing-print-errors/"><u>AD DS Maintenance Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-get-my-canon-printer-on-board/"><u>Can't Get My Canon Printer on Board</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alert-local-print-queue-not-running/"><u>[ALERT] Local Print Queue Not Running</u></a></li>
<li><a href="https://vp-tips.techidaily.com/expert-tips-on-amassing-stock-art-resources-for-2024/"><u>Expert Tips on Amassing Stock Art Resources for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/icloud-separation-how-to-disconnect-iphone-6-and-ipad-by-drfone-ios/"><u>iCloud Separation How To Disconnect iPhone 6 and iPad</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-elevating-social-influence-top-techniques-for-facebook-seo-excellence/"><u>[New] 2024 Approved  Elevating Social Influence  Top Techniques for Facebook SEO Excellence</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unveiling-effective-strategies-for-fb-in-stream-ad-setup/"><u>[New] Unveiling Effective Strategies for FB In-Stream Ad Setup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/family-fantasy-films-this-summers-best-10-classics/"><u>Family Fantasy Films  This Summer's Best 10 Classics</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-realme-c55-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Realme C55 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://some-skills.techidaily.com/jokejuggernaut-top-humor-tool-for-2024/"><u>JokeJuggernaut - Top Humor Tool for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-12-prominent-nokia-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Nokia Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/pixelpatchwork-android-and-ios-instagram-collage/"><u>PixelPatchwork  Android & iOS Instagram Collage</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-motorola-razr-40-ultra-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Motorola Razr 40 Ultra Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pro-techniques-for-exceptional-iphone-hdr-results/"><u>Pro Techniques for Exceptional iPhone HDR Results</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-insiders-guide-to-fixing-popular-youtube-short-problems/"><u>2024 Approved  The Insider's Guide to Fixing Popular YouTube Short Problems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/detailed-guide-to-googles-voice-to-text-service-features-and-usage/"><u>Detailed Guide to Google's Voice-to-Text Service Features and Usage</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/all-about-creating-compelling-twitresponses-for-2024/"><u>All About Creating Compelling TwitResponses for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlock-your-youtube-personality-top-6-creator-categories/"><u>Unlock Your YouTube Personality  Top 6 Creator Categories</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-optimizing-your-youtube-video-preservation/"><u>In 2024, Optimizing Your YouTube Video Preservation</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unlocking-the-secrets-to-altering-your-networks-showcase-picture/"><u>Unlocking the Secrets to Altering Your Network's Showcase Picture</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-art-of-crafting-persuasive-video-covers-for-social-media-platforms/"><u>[Updated] The Art of Crafting Persuasive Video Covers for Social Media Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/virtual-reality-revolution-which-headset-leads-the-charge/"><u>Virtual Reality Revolution  Which Headset Leads the Charge?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-focused-frame-capture-leading-cams-for-slow-movement-recording/"><u>In 2024, Focused Frame Capture  Leading Cams for Slow Movement Recording</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-messages-from-apple-iphone-12-pro-max-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Messages from Apple iPhone 12 Pro Max to iPhone Including iPhone 15 | Dr.fone</u></a></li>
</ul></div>
