---
title: How to Stop and Repair Spooler on Windows Versions 7-11
date: 2024-07-10T17:29:17.232Z
updated: 2024-07-11T17:29:17.232Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Stop and Repair Spooler on Windows Versions 7-11
excerpt: This Article Describes How to Stop and Repair Spooler on Windows Versions 7-11
keywords: Stop Spooler,Spooler Repair,Windows 7 Spooler Stop,Windows 10 Spooler Repair,Windows Versions Stop Spooler,Windows 8 Spooler Fix,Windows Server Spooler Stop
thumbnail: https://thmb.techidaily.com/c39d96a0392062878f0d55bc9ae4650b6150e40d84fd4972f36d7344db4ba87f.jpg
---

## How to Stop and Repair Spooler on Windows Versions 7-11

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
<li><a href="https://printer-issues.techidaily.com/cannot-find-hp-printer-drivers-on-win1110/"><u>Cannot Find HP Printer Drivers on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secrets-of-efficiently-setting-up-hp-on-pcs/"><u>Unveiling the Secrets of Efficiently Setting Up HP on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mp620-printer-driver-search-on-win10-unsuccessful/"><u>Canon MP620 Printer Driver Search on WIN10 Unsuccessful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-hp-d1360-drivers-success-on-windows-versions/"><u>Installing HP D1360 Drivers: Success on Windows Versions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-pixma-mp620-drivers-missing-windows-10/"><u>[Update Required] Pixma MP620 Drivers Missing Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-page-failure-resolved/"><u>HP Printer: Page Failure Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-compatible-driver-release/"><u>Officejet Pro 8600 Windows Compatible Driver Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-laser-print-nozzle-blockage/"><u>Quick Fix: Laser Print Nozzle Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypass-print-job-delay-quickly/"><u>Bypass Print Job Delay Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-epson-printing-now-continues/"><u>Halted Epson Printing, Now Continues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-print-job-responsiveness-on-xp-edition/"><u>Enhance Print Job Responsiveness on XP Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fixed-version-printing-whole-documents/"><u>New Fixed Version: Printing Whole Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-your-non-printing-canon-into-a-reliable-device-with-tips/"><u>Turn Your Non-Printing Canon Into a Reliable Device with Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-devices-exhibiting-continuous-sheet-outputs/"><u>Epson Devices Exhibiting Continuous Sheet Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-installing-hp-photosmart-printer/"><u>Step-by-Step: Installing HP PhotoSmart Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winerror-zeroed-out-restoring-printer-setup-0x00000709/"><u>WinError Zeroed Out - Restoring Printer Setup (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-colored-images/"><u>Unable to Print Colored Images</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unstick-print-job-immediately/"><u>Unstick Print Job Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-glitch-resolution-0x97/"><u>Epson Glitch Resolution: 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-shared-printer-usage-concern/"><u>Resolved: Shared Printer Usage Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-print-spooler-keeps-stopping-on-windows-11-and-7/"><u>How to Fix Print Spooler Keeps Stopping on Windows 11 & 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-shenanigans-unauthorized-printer-access/"><u>System Shenanigans: Unauthorized Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2-steps-to-set-up-canon-printer-with-pictures/"><u>2 Steps to Set up Canon Printer (With Pictures)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/supreme-session-naming-service/"><u>Supreme Session Naming Service</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-iphone-13-pro-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your iPhone 13 Pro in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-vivo-y55s-5g-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/prime-picks-excellent-mac-based-video-snatchers/"><u>Prime Picks  Excellent Mac-Based Video Snatchers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-disabling-background-chatter-in-tiktok-videos-three-streamlined-techniques-for-2024/"><u>New Disabling Background Chatter in TikTok Videos Three Streamlined Techniques for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-review-vlcs-capability-to-record-screens/"><u>[New] Review  VLC's Capability to Record Screens</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-ideal-tools-for-secure-vimeo-downloads/"><u>[Updated] 2024 Approved  Ideal Tools for Secure Vimeo Downloads</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-innovative-sound-solutions-for-videographers-streamlining-effect-implementation/"><u>In 2024, Innovative Sound Solutions for Videographers Streamlining Effect Implementation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-4k-visionary-review-blades-spectrum-expansion/"><u>2024 Approved  4K Visionary Review  Blade's Spectrum Expansion</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-video-brand-enhancement-embedding-logoswatermarks-for-youtube-shows/"><u>In 2024, Video Brand Enhancement  Embedding Logos/Watermarks for YouTube Shows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-acquiring-high-clarity-imagery-without-limitations/"><u>[New] Acquiring High-Clarity Imagery without Limitations</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-essential-steps-for-clearance-prior-to-tiktok-uploads/"><u>[New] The Essential Steps for Clearance Prior to TikTok Uploads</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-loop-videos-on-iphone-for-2024/"><u>How to Loop Videos on iPhone for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-channel-boost-achieve-youtube-affiliate-milestone-with-10k-vistas-for-2024/"><u>[Updated] Channel Boost  Achieve YouTube Affiliate Milestone with 10K Vistas for 2024</u></a></li>
</ul></div>
