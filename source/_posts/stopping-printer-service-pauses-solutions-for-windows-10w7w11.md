---
title: "Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11"
date: 2024-07-10T17:41:22.254Z
updated: 2024-07-11T17:41:22.254Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11"
excerpt: "This Article Describes Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11"
keywords: Stopping Printer Service Pauses,Fixing Printer Halt in Windows 10,Resolving Printer Stops on Windows W7,Preventing Print Queue Errors,How to Stop Printer Faults and Interruptions,Solutions for Unresponsive Printer Service in Windows,Troubleshooting Printer Delays & Pauses in Windows OS
thumbnail: https://thmb.techidaily.com/aa55be7c2a41a4441a2d4709614981b2cbcf720fe14a850d289619ed36f925a3.png
---

## Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11

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
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-are-missing/"><u>Printer OS Error: Drivers Are MISSING</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-found-windows-10-and-pixma-mp620-disconnect/"><u>Driver Not Found: Windows 10 and Pixma MP620 Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocked-scanner-operation-in-windows-11-os/"><u>Unblocked Scanner Operation in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-canon-wi-fi-connection-process/"><u>Mastering the Canon-Wi-Fi Connection Process</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-driver-not-compatible-with-multiple-windows-systems-for-hp-d1360/"><u>Print Device Driver Not Compatible with Multiple Windows Systems for HP D1360</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-issue-hp-printer-not-recognized-by-os/"><u>Hardware Issue: HP Printer Not Recognized by OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-non-operation-on-windows-7-post-sleep/"><u>USB Printer Non-Operation on Windows 7 Post Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-paper-refilling-for-hp-officejet-pro-m574dw/"><u>Wireless Paper Refilling for HP Officejet Pro M574dw</u></a></li>
<li><a href="https://printer-issues.techidaily.com/help-needed-printers-unplanned-shift/"><u>Help Needed: Printer's Unplanned Shift</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugging-and-removing-a-secondary-printer-from-os/"><u>Unplugging and Removing a Secondary Printer From OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setup-no-complications-found/"><u>Print Setup: No Complications Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-intermittent-print-job-failures-windows/"><u>Steps to Stop Intermittent Print Job Failures (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-os-struggles-hp-driver-not-available/"><u>Windows OS Struggles: HP Driver Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574161603-successfully-installed-printer/"><u>Successfully Installed Printer.</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-cannot-retrieve-printer-drivers/"><u>Windows Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-mfc-9330cdw-wireless-effortlessly/"><u>Install MFC-9330CDW Wireless Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-reports-with-paper-less-prints/"><u>Revolutionizing Reports with Paper-Less Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-recover-an-offline-print-device-from-network/"><u>Steps to Recover an Offline Print Device From Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-wont-print-all-pages-2024-fix/"><u>Printers Won't Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/celebrating-clear-documentation-with-every-page/"><u>Celebrating Clear Documentation with Every Page</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-paperjam-error-by-deleting-printer/"><u>Eliminate PaperJam Error by Deleting Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-drive-efficiency-mf4770n-and-windows-systems/"><u>Boosting Drive Efficiency: MF4770n & Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printer-speed-with-simple-fixes/"><u>Boost Printer Speed with Simple Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-cant-print-spooler-disabled/"><u>[ISSUE] Can't Print - Spooler Disabled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-epson-printer-error-codes-on-w11/"><u>Troubleshoot Epson Printer Error Codes on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-windows-11-8-7-and-mf4770n-for-efficiency/"><u>Harmonizing Windows 11, 8, 7 & MF4770n for Efficiency</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-offline-causes-inability-to-print/"><u>AD DS Offline Causes Inability To Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-dilemma-windows-11-ignoring-pixma-mp620/"><u>[Driver Dilemma] Windows 11 Ignoring Pixma MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-firmware-for-mf4770n-on-windows-systems/"><u>Latest Firmware for MF4770n on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-document-transfer-with-printer-driver-fixes-on-win10/"><u>Enhance Document Transfer with Printer Driver Fixes on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-non-printing-issues-five-tactics-to-get-your-canon-running-in-windows-11/"><u>Troubleshoot Non-Printing Issues: Five Tactics to Get Your Canon Running in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-crippled-printer-driver-unavailable-in-win/"><u>[SYSTEM CRIPPLED] Printer Driver Unavailable in Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-epson-printer-printing-anomalies/"><u>Repaired: Epson Printer Printing Anomalies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-epson-inkjet-skips-printing-texts/"><u>Resolved: Epson Inkjet Skips Printing Texts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-comparing-dailymovements-and-youtubes-income-models-for-2024/"><u>[New] Comparing DailyMovement's and Youtube's Income Models for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-featured-top-ranked-emulators-for-3ds-on-pc/"><u>[New] 2024 Approved  Featured Top-Ranked Emulators for 3DS on PC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-affordable-choices-best-laptops-for-gamers-on-a-dime/"><u>[Updated] In 2024, Affordable Choices  Best Laptops for Gamers on a Dime</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-apple-iphone-13-pro-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From Apple iPhone 13 Pro without Password?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/cut-trim-and-edit-the-best-pc-video-software/"><u>Cut, Trim, and Edit The Best PC Video Software</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-fcpx-hacks-and-workarounds-expert-advice-for-smooth-editing-for-2024/"><u>New FCPX Hacks and Workarounds Expert Advice for Smooth Editing for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-disconnect-remove-spotify-from-your-facebook-profile/"><u>How To Disconnect: Remove Spotify From Your Facebook Profile</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-aspect-ratio-mastery-a-step-by-step-tiktok-guide/"><u>Updated In 2024, Aspect Ratio Mastery A Step-by-Step TikTok Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-avs-video-editor-review-update-whats-new/"><u>2024 Approved AVS Video Editor Review Update Whats New ?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713949236856-do-you-know-how-to-zoom-on-facebook-livestream-videos-through-this-article-you-will-find-multiple-ways-and-detailed-steps-to-zoom-in-on-the-facebook-livestr/"><u>Do You Know How to Zoom on Facebook Livestream Videos? Through This Article, You Will Find Multiple Ways and Detailed Steps to Zoom in on the Facebook Livestream Videos for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-15-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 15? Heres the Best Fixes</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-essence-of-time-stretching-detailed-review-of-slomo-2e1924/"><u>[Updated] The Essence of Time Stretching  Detailed Review of SloMo, 2E1924</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-y100a-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovations-in-motion-capture-for-enhanced-ux/"><u>[New] Innovations in Motion Capture for Enhanced UX</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-versatile-intro-editing-app-for-your-device-repertoire/"><u>[New] Versatile Intro Editing App for Your Device Repertoire</u></a></li>
<li><a href="https://extra-hints.techidaily.com/extensive-review-gopro-hero4-silver/"><u>Extensive Review  GoPro HERO4 Silver</u></a></li>
</ul></div>
