---
title: Preventing Continuous Spooler Failures on W10/W11/W7
date: 2024-07-10T17:13:00.115Z
updated: 2024-07-11T17:13:00.115Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventing Continuous Spooler Failures on W10/W11/W7
excerpt: This Article Describes Preventing Continuous Spooler Failures on W10/W11/W7
keywords: Continuous Spooler Troubleshooting,Windows 10/11/7 Spooler Fixes,Spooler Failure Solutions for W10/W11/W7,Prevent Spooler Crashes in W10/W11/W7,Windows 7/8/10 Spooler Stability,Spooler Failure Fixes for W7/8/10,Optimize Spooler Performance in Windows 10/11/7
thumbnail: https://thmb.techidaily.com/0b50962ffa3e17ae709bef162c3f8ff4d960cae116eaf3e790989364bc8da0ce.jpg
---

## Preventing Continuous Spooler Failures on W10/W11/W7

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
<li><a href="https://printer-issues.techidaily.com/easy-setup-brothers-mfc-9330cdw/"><u>Easy Setup: Brother's MFC-9330CDW</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-printer-in-error-state/"><u>How to Fix Printer in Error State</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-connectivity-interruptions/"><u>Addressed Connectivity Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-print-queue-disruption-in-multiple-oss/"><u>Preventing Print Queue Disruption in Multiple OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-cant-find-driver-on-windows-os/"><u>HP Printer Setup Error: Can't Find Driver on Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-connectivity-issue-sorted-out/"><u>HP Printer Connectivity Issue Sorted Out</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-driver-suite-for-windows-enhancement/"><u>HP Officejet Pro 8600 Driver Suite for Windows Enhancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cured-printer-not-printing-on-epson-solved/"><u>Cured: Printer Not Printing on Epson [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-my-printer-skips-colors/"><u>Why My Printer Skips Colors?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-4630-driver-download-and-update/"><u>HP Officejet 4630 Driver Download & Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-life-into-your-dying-windows-11-printer/"><u>Breathe Life Into Your Dying Windows 11 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-epsons-error-x97/"><u>Fixing Epson's Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-inkjet-connectivity-for-windows-vistaxp-users/"><u>Restore Inkjet Connectivity for Windows Vista/XP Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-print-experience-with-win-hp-printer-guide/"><u>Streamline Your Print Experience with Win HP Printer Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-printer-disconnection/"><u>Instantly Resolve Printer Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quicken-your-print-jobs-easily/"><u>Quicken Your Print Jobs Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-issue-with-installing-printer/"><u>Fixed Issue with Installing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-wastelanded-printer-on-windows-11/"><u>Stop Your Wastelanded Printer on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-searching-for-driver-on-win11/"><u>Canon Pixma MP620: Searching for Driver on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-code-0x00000709-to-fix-default-printer-setup/"><u>Cracking Code 0X00000709 to Fix Default Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-hp-printer-setup-wizards-in-windows/"><u>Navigating Through HP Printer Setup Wizards in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-document-transfer-with-printer-driver-fixes-on-win10/"><u>Enhance Document Transfer with Printer Driver Fixes on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-w10w7-hp-printer-no-connect/"><u>Resolving W10/W7 HP Printer No-Connect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplifying-pcl-xl-error-correction/"><u>Simplifying PCL XL Error Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574142393-cant-remove-printer-on-windows-solved/"><u>Can’t Remove Printer on Windows [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-inkjet-non-operational-state/"><u>Fixed Inkjet Non-Operational State</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-essential-recorder-tools-the-8-best-lists/"><u>[Updated] In 2024, Essential Recorder Tools  The 8 Best Lists</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-resolving-partial-muting-in-facebook-video-chats-updated-guide/"><u>[New] In 2024, Resolving Partial Muting in Facebook Video Chats (Updated Guide)</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-huawei-p60-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-pictureperfectionist-expert-guide-to-ig-size-settings/"><u>[Updated] In 2024, PicturePerfectionist  Expert Guide to IG Size Settings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-beginners-guide-to-iphone-screen-capture/"><u>[Updated] In 2024, Beginner's Guide to iPhone Screen Capture</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-oppo-a78-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Oppo A78 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-civi-3withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi Civi 3with/without a PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Honor Magic V2 | Dr.fone</u></a></li>
</ul></div>
