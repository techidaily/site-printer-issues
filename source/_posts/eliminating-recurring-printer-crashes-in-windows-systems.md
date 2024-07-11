---
title: Eliminating Recurring Printer Crashes in Windows Systems
date: 2024-07-10T16:42:29.534Z
updated: 2024-07-11T16:42:29.534Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Eliminating Recurring Printer Crashes in Windows Systems
excerpt: This Article Describes Eliminating Recurring Printer Crashes in Windows Systems
keywords: Printer Troubleshooting Guide,Prevent Printer Errors Windows 10/8/7,Windows System Print Driver Fixes,Stable Printer Setup Windows Operating Systems,Avoid Recurring Printer Malfunctions in OS,Effective Print Spooler Fixes Windows Crashes,Enhance Printer Performance in Windows Systems
thumbnail: https://thmb.techidaily.com/ecfcd073ace7d18c0661d93194869f4c69c9a93b7f7e0b0c3bf6cf212d7d6071.jpg
---

## Eliminating Recurring Printer Crashes in Windows Systems

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
<li><a href="https://printer-issues.techidaily.com/turn-your-non-printing-canon-into-a-reliable-device-with-tips/"><u>Turn Your Non-Printing Canon Into a Reliable Device with Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-pcs-scanner-connection-on-win10/"><u>Reactivating PC's Scanner Connection on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-with-hp-print-on-w7-resolved/"><u>Connectivity Woes with HP Print on W7 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canon-printer-puzzles-in-windows-11-here-are-five-easy-solutions/"><u>Overcome Canon Printer Puzzles in Windows 11 - Here Are Five Easy Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/spooler-error-preventing-successful-prints/"><u>Spooler Error Preventing Successful Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-gaps-connecting-canon-to-wireless-networks/"><u>Bridging Gaps: Connecting Canon to Wireless Networks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printer-function-release/"><u>Seamless Printer Function Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-searches-for-non-existent-printer-driver/"><u>Windows Searches for Non-Existent Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/offline-printer-status-solved-win7-hp-troubleshooting-guide/"><u>Offline Printer Status Solved: Win7 HP Troubleshooting Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-lost-pages-thanks-to-new-fixes/"><u>No More Lost Pages, Thanks to New Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-offline-workflow-blockage/"><u>Fixed Offline Workflow Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smoothed-out-printer-connection-hurdles/"><u>Smoothed Out Printer Connection Hurdles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-blank-output-hp-printers-success-story/"><u>Banishing Blank Output: HP Printer's Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-default-problem-error-0x00000709-fixed/"><u>Unraveling Printer Default Problem - Error 0X00000709 Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-network-printer/"><u>Successfully Installed Network Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-inactive-print-devices/"><u>Solutions for Inactive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-operation-revamping-mf4770n-on-w11-w8-w7-platforms/"><u>Seamless Operation: Revamping MF4770n on W11, W8, W7 Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overhauling-hp-printers-error-code-oxc4eb827f/"><u>Overhauling HP Printer's Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-online-status-of-windowshp-multi-function/"><u>Reactivating Online Status of Windows/HP Multi-Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-d1360-print-driver-installation-across-windows-systems/"><u>Troubleshooting HP D1360 Print Driver Installation Across Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-paperless-print-error-rectified/"><u>Post-Upgrade, Paperless Print Error Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-issue-canon-pixma-mp620-and-win10-not-linked/"><u>[Compatibility Issue] Canon Pixma MP620 & WIN10 Not Linked</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-constant-interruptions-from-spooler-service-in-win107/"><u>Preventing Constant Interruptions From Spooler Service in Win10/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-samsung-print-woes/"><u>Solving Samsung Print Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-code-b200/"><u>Fixed: Error Code B200</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-launch-free-dvd-playback-capabilities-on-windowsmac-laptops/"><u>[Updated] Launch Free DVD Playback Capabilities on Windows/Mac Laptops</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-top-rated-video-voice-over-software-for-pc-review-and-download/"><u>New In 2024, Top-Rated Video Voice Over Software for PC - Review and Download</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2023s-leading-cameras-for-samsung-gear-360-successors-for-2024/"><u>2023'S Leading Cameras for Samsung Gear 360 Successors for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-unleashing-creativity-with-vn-video-editor-on-pc-a-review-for-2024/"><u>New Unleashing Creativity with VN Video Editor on PC A Review for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-screenmaster-mastering-window-recordings-on-spring/"><u>[Updated] ScreenMaster  Mastering Window Recordings on Spring</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-seamless-video-capture-and-save-with-top-apps-list/"><u>[Updated] Seamless Video Capture & Save with Top Apps List</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-infinix-smart-7-hd-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Infinix Smart 7 HD Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/cutting-edge-online-no-cost-converters-for-tiktok-to-mp3s-for-2024/"><u>Cutting-Edge Online, No Cost Converters for TikTok to MP3s for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/decoding-uavs-the-science-behind-airborne-machines/"><u>Decoding UAVs  The Science Behind Airborne Machines</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-facebooks-viral-videos-the-top-8-counting-up-to-2023/"><u>[New] In 2024, Facebook's Viral Videos  The Top 8 Counting Up to 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-audio-excellence-premium-recording-mics-ranked/"><u>In 2024, Audio Excellence  Premium Recording Mics Ranked</u></a></li>
</ul></div>
