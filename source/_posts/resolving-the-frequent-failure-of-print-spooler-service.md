---
title: Resolving the Frequent Failure of Print Spooler Service
date: 2024-06-28T07:10:51.594Z
updated: 2024-06-29T07:10:51.594Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolving the Frequent Failure of Print Spooler Service
excerpt: This Article Describes Resolving the Frequent Failure of Print Spooler Service
keywords: Fixing Windows Print Spooler Crashes,Troubleshoot Printer Spooler Service Failures,Windows Print Spooler Service Fixes,Restart Windows Print Spooler Service,Prevent Print Spooler Service Errors,Fix Printer Spooler Service on Windows,Recommended Solutions for Print Spooler Failures
thumbnail: https://thmb.techidaily.com/e3e57dc288a15eebc6a087ce47534d889b154128f1cec9b763b947b83648c7c9.jpg
---

## Resolving the Frequent Failure of Print Spooler Service

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
<li><a href="https://printer-issues.techidaily.com/successful-installation-of-multi-function-printer/"><u>Successful Installation of Multi-Function Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-alert-unable-to-locate-on-windows-10/"><u>[Printer Driver Alert]: Unable to Locate on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/victory-fixing-print-issues-in-windows-10/"><u>Victory: Fixing Print Issues in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-the-erratic-behavior-of-print-spooler-windows/"><u>Troubleshooting the Erratic Behavior of Print Spooler (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reengage-the-printing-pro-saving-brother-printer-from-isolation/"><u>Reengage the Printing Pro: Saving Brother Printer From Isolation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-restoring-communication-with-printer/"><u>Guide to Restoring Communication with Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-maze-getting-brothers-printer-back-on-line/"><u>Navigating the Maze: Getting Brother's Printer Back on Line</u></a></li>
<li><a href="https://discord-videos.techidaily.com/exclusive-communication-apps-post-discord/"><u>Exclusive Communication Apps Post-Discord</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-techniques-for-audience-friendly-audio-declines-in-imovie-projects/"><u>Updated In 2024, Techniques for Audience-Friendly Audio Declines in iMovie Projects</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-samsung-galaxy-s24-ultra-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Samsung Galaxy S24 Ultra Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-samsung-ubd-k8500-analysis/"><u>Updated Samsung UBD-K8500 Analysis</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-iphone-13-pro-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From iPhone 13 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/discover-cost-free-vfx-wonders-on-the-net/"><u>Discover Cost-Free VFX Wonders on the Net</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-enhancing-meet-visuals-applying-filters-effects-and-masks-for-2024/"><u>[New] Enhancing Meet Visuals  Applying Filters, Effects & Masks for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Xiaomi Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-standout-panzoid-design-kits/"><u>[New] 2024 Approved  Standout Panzoid Design Kits</u></a></li>
</ul></div>
