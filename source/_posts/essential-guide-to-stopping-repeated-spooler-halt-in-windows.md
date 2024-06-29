---
title: Essential Guide to Stopping Repeated Spooler Halt in Windows
date: 2024-06-28T07:16:46.001Z
updated: 2024-06-29T07:16:46.001Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Essential Guide to Stopping Repeated Spooler Halt in Windows
excerpt: This Article Describes Essential Guide to Stopping Repeated Spooler Halt in Windows
keywords: Windows 10 SPOOLER STOPPING REPEATS,How to Stop Spooler Errors on Windows,Solutions for Repeated Spooler Hangs (Windows),Preventing Spooler Halt in Windows OS,Fixing Repeated Spooler Errors (Windows),Stop Spooler Errors on Windows 10,Troubleshooting Repeated Spooler Halt in Windows
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Essential Guide to Stopping Repeated Spooler Halt in Windows

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
<li><a href="https://printer-issues.techidaily.com/quickly-rectify-non-printing-problem-top-5-techniques-to-aid-canon-print-on-window-11/"><u>Quickly Rectify Non-Printing Problem: Top 5 Techniques to Aid Canon Print on Window 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/process-for-adding-connecting-8720-printer-model-to-pc/"><u>Process for Adding: Connecting 8720 Printer Model to PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-action-on-queued-print-processes/"><u>Immediate Action on Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-in-upgraded-windows-10-version/"><u>Reactivating Scanner in Upgraded Windows 10 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/sleeper-mode-dilemma-usb-printers-not-awakening-in-w7/"><u>Sleeper Mode Dilemma: USB Printers Not Awakening in W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-performance-upgrade-dell-inkjet-aio-on-windows-7/"><u>Drive Performance: Upgrade Dell Inkjet AIO on WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-and-update-hp-officejet-4630-driver-edition/"><u>Secure & Update: HP Officejet 4630 Driver Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquering-the-blank-page-battlefield-for-printers/"><u>Conquering the Blank Page Battlefield for Printers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-youtube-shorts-a-beginners-guide/"><u>[New] YouTube Shorts  A Beginner's Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-narzo-60x-5g-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme Narzo 60x 5G Device</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harmonizing-hearts-interacting-with-a-diverse-subscriber-base/"><u>[New] Harmonizing Hearts  Interacting with a Diverse Subscriber Base</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-structuring-engaging-online-vignettes/"><u>2024 Approved  Structuring Engaging Online Vignettes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-aerial-excellence-with-mi-drone-a-high-quality-look/"><u>[Updated] Aerial Excellence with MI Drone - A High-Quality Look</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-transforming-challenges-into-triumphs-with-these-30-tips/"><u>[Updated] In 2024, Transforming Challenges Into Triumphs with These 30 Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/calculating-the-comfort-zone-for-podcast-duration/"><u>Calculating the Comfort Zone for Podcast Duration</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleashing-visual-potential-is-pickup-the-pinnacle-of-android-editing-tools-for-2024/"><u>Unleashing Visual Potential  Is PickUp the Pinnacle of Android Editing Tools for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-elevate-your-digital-presence-best-ways-to-utilize-zoom-changer/"><u>In 2024, Elevate Your Digital Presence  Best Ways to Utilize Zoom Changer</u></a></li>
</ul></div>
