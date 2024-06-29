---
title: Stop Printer'evolving Spooler Error (WX, W10 & W11)
date: 2024-06-28T06:51:41.364Z
updated: 2024-06-29T06:51:41.364Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop Printer'evolving Spooler Error (WX, W10 & W11)
excerpt: This Article Describes Stop Printer'evolving Spooler Error (WX, W10 & W11)
keywords: Windows Spooler Error,Printer Spooler Troubleshooting,Spooler Error Fixes,Printer Spooler W10/W11,Spooler Error X/W10,Printer Error X/W10/11,Printer Spooler X/W10 Troubleshooting,Written By,Printer Spooler X/W10/11
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## Stop Printer'evolving Spooler Error (WX, W10 & W11)

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
<li><a href="https://printer-issues.techidaily.com/fixing-siblings-printer-remains-unreachable/"><u>Fixing: Sibling's Printer Remains Unreachable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-device-interaction-with-mf4770n-upgrade-in-windows-1187/"><u>Streamline Device Interaction with MF4770n Upgrade in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-connectivity-crunch-windows-7-usb-printer-dormancy/"><u>[Resolved] Connectivity Crunch: Windows 7 USB Printer Dormancy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compact-bundle-optimized-hp-officejet-pro-8600-drivers-win32/"><u>Compact Bundle: Optimized HP Officejet Pro 8600 Drivers, Win32</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-inkjet-and-laser-issues-win10-style/"><u>Fix Inkjet & Laser Issues, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-document-output-on-windowshp/"><u>Streamlining Document Output on Windows/HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-access-a-guide-for-offline-printers/"><u>Regaining Access: A Guide for Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-printer-woes-with-windows-10-update-fix/"><u>Triumph Over Printer Woes with Windows 10 Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-vivo-y36i-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Vivo Y36i Through Google Earth?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-make-highlights-on-instagram-for-2024/"><u>How to Make Highlights on Instagram for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-internal-screen-recording-huawei-mate-1020-and-p-series-devices-p20-p10/"><u>[Updated] 2024 Approved  Internal Screen Recording  Huawei Mate 10/20 & P Series Devices (P20, P10)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-elevate-your-hashtag-game-on-instagram-a-comprehensive-guide-for-2024/"><u>[New] Elevate Your Hashtag Game on Instagram  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/text-to-mp3-encoding-across-all-major-mobile-and-desktop-os/"><u>Text to MP3 Encoding Across All Major Mobile and Desktop OS</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-14-plus-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From Apple iPhone 14 Plus</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/top-5-udemy-subtitle-translation-tools-for-seamless-auto-translations/"><u>Top 5 Udemy Subtitle Translation Tools for Seamless Auto Translations</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-best-in-class-text-tracking-and-animation-software-2023/"><u>New 2024 Approved Best in Class Text Tracking and Animation Software 2023</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-vivo-v27-pro-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Vivo V27 Pro? Try These Fixes</u></a></li>
</ul></div>
