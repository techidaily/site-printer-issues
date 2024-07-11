---
title: Combat Recurring Spooler Errors on WX, W10, W11
date: 2024-07-10T16:47:52.952Z
updated: 2024-07-11T16:47:52.952Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Combat Recurring Spooler Errors on WX, W10, W11
excerpt: This Article Describes Combat Recurring Spooler Errors on WX, W10, W11
keywords: Spooler Errors,Solve Spooler Errors WX, W10, W11,Recurring Spooler Errors Fix,WX, W10, W11 Spooler Troubleshooting,Spooler Errors Windows 10/11,Prevent Spooler Crashes WX, W10, W11,Spooler Error Log Analysis Windows 10/W11/WX
thumbnail: https://thmb.techidaily.com/98b85ce6d797323413c6bf7e018c1d8e6594fdbbf15afde0abd2d98dfde1d7e0.jpg
---

## Combat Recurring Spooler Errors on WX, W10, W11

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
<li><a href="https://printer-issues.techidaily.com/scanner-activation-restored-for-windows-10-users/"><u>Scanner Activation Restored for Windows 10 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-repeated-print-job-errors-in-windows-operating-systems/"><u>Combat Repeated Print Job Errors in Windows Operating Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-printer-disconnection-problem-on-network/"><u>Solutions for Printer Disconnection Problem on Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-printer-woes-with-windows-10-update-fix/"><u>Triumph Over Printer Woes with Windows 10 Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-woes-ended-new-windows-solved-issue/"><u>Printer Woes Ended: New Windows Solved Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-enabling-online-scanner-in-win11/"><u>Re-Enabling Online Scanner in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-paper-size-error-on-hp-deskjet-3070/"><u>Fixed Paper Size Error on HP DeskJet 3070</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unravel-offline-mystery-with-easy-fixes-for-your-canon-printer/"><u>Unravel Offline Mystery with Easy Fixes for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-brother-printer-print-operation-in-windows-oses/"><u>Streamlining Brother Printer Print Operation in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/visual-installation-guide-for-a-new-canon-printer/"><u>Visual Installation Guide for a New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-unresponsive-seek-help-fast/"><u>Canon Printer: Unresponsive, Seek Help Fast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-access-to-hp-printer-driver-on-win1110/"><u>No Access to HP Printer Driver on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-office-printer-breakdowns/"><u>Overcoming Office Printer Breakdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-after-wake-from-sleep-in-windows-7/"><u>[Resolved] Printer Error After Wake From Sleep in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-to-color-requests/"><u>Printer Not Responding to Color Requests</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-duplex-mismatches-on-windows-11/"><u>Address Duplex Mismatches on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-center-finding-hidden-network-devices-in-win-10/"><u>[Solution Center] Finding Hidden Network Devices in Win 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-remedies-for-common-pcl-xl-issues/"><u>Efficient Remedies for Common PCL XL Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-hp-printer-driver-not-in-windows-os/"><u>Hardware Setup: HP Printer Driver Not in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-epson-paperless-operation-issue/"><u>Troubleshooting Epson Paperless Operation Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canons-code-b200-fixed-now/"><u>Canon's Code B200 Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574150252-unexpected-printer-error-alert/"><u>Unexpected Printer Error Alert!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-silent-hp-printers/"><u>Quick Fixes for Silent HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/black-and-white-only-mode-engaged-by-printer/"><u>Black & White Only Mode Engaged by Printer</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-avs-video-editor-a-comprehensive-review/"><u>In 2024, AVS Video Editor A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://driver-install.techidaily.com/unleash-potential-lenovos-simple-upgrade-path/"><u>Unleash Potential: Lenovo's Simple Upgrade Path</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-how-to-record-whatsapp-call/"><u>In 2024, How to Record WhatsApp Call</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-maximizing-sound-the-best-online-tools-for-amplifying-video-volumes/"><u>Updated Maximizing Sound The Best Online Tools for Amplifying Video Volumes</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-6-networks-maximizing-biz-potential/"><u>In 2024, Premium 6 Networks Maximizing Biz Potential</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-the-art-of-seamless-editing-mastering-the-filmora-experience/"><u>[New] 2024 Approved  The Art of Seamless Editing  Mastering the Filmora Experience</u></a></li>
<li><a href="https://fox-helps.techidaily.com/sony-s6700-updated-summary-unpacked/"><u>Sony S6700 Updated Summary Unpacked</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-from-iphone-15-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out From iPhone 15 How to Bypass?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-acclaimed-constructors-top-notch-instagram-hlv-artisans/"><u>[Updated] 2024 Approved  Acclaimed Constructors  Top-Notch Instagram HLV Artisans</u></a></li>
</ul></div>
