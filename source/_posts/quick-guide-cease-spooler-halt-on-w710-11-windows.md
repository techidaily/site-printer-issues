---
title: "Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
date: 2024-07-10T17:33:21.076Z
updated: 2024-07-11T17:33:21.076Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
excerpt: "This Article Describes Quick Guide: Cease Spooler Halt on W7/10, 11 Windows"
keywords: Windows Cleanup Guide,Cease Spooler Fix for Windows 7/10/11,Windows Spooler Halt Tutorial,Speed Up Windows 7/10/11,Windows Performance Boost Guide,Resolve Windows 7/10/11 Bloatware Issue,Optimize System Resources Windows 7/10/11
thumbnail: https://thmb.techidaily.com/31170fc82b47adef76e35b1dbe5e6312865cece8cca3cd844fe92c1c213c87ec.jpg
---

## Quick Guide: Cease Spooler Halt on W7/10, 11 Windows

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
<li><a href="https://printer-issues.techidaily.com/effortlessly-establish-canon-printer-link/"><u>Effortlessly Establish Canon Printer Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mend-winxp-print-issues-non-responsive-error-solved/"><u>Mend WinXP Print Issues: Non-Responsive Error Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-textless-printouts-on-my-epson-scannerprinter/"><u>Trouble with Textless Printouts on My Epson Scanner/Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-to-brother-wireless-mfc-9330c/"><u>Quick Guide to Brother Wireless MFC-9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-device-on-your-os/"><u>Unexpectedly No Printer Device on Your OS?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplifying-canon-printer-wireless-connection/"><u>Simplifying Canon Printer Wireless Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-connection-solutions-joining-your-laptop-and-hp-printer/"><u>Streamlined Connection Solutions: Joining Your Laptop and HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/supercharge-dells-v305-inkjets-with-new-windows-driver/"><u>Supercharge Dell's V305 Inkjets with New Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-endless-white-paper-output/"><u>Epson Photo Printer: Endless White Paper Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-and-secure-printer-communication-in-win10/"><u>Upgrade and Secure Printer Communication in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-print-queue-disruption-in-multiple-oss/"><u>Preventing Print Queue Disruption in Multiple OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-response-from-networked-printer/"><u>Resolving No Response From Networked Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-prints-on-monitors/"><u>Eliminating Ghost Prints on Monitors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hooked-up-instantly-and-easily/"><u>Printer Hooked Up Instantly & Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-journey-from-void-papers-to-valuable-outputs/"><u>The Journey From Void Papers to Valuable Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-usb-drive-software-upgrade-for-windows/"><u>MF4770n USB Drive Software Upgrade for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-issue-cannot-add-printer-drivers-to-multiple-windows/"><u>[Connectivity Issue] Cannot Add Printer Drivers to Multiple Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-and-propel-printers-fast/"><u>Unblock and Propel Printers Fast</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnecting-brothers-print-to-end-offline-status-woes/"><u>Reconnecting Brothers Print to End Offline Status Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-in-picture-getting-your-canon-printer-ready/"><u>Step-In-Picture: Getting Your Canon Printer Ready</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-tale-of-triumph-over-theoretical-paper-trails/"><u>A Tale of Triumph Over Theoretical Paper Trails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-not-printing-conquer-this-issue-with-our-top-5-solutions-for-windows-11/"><u>Canon Printer Not Printing? Conquer This Issue with Our Top 5 Solutions for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canons-code-b200-fixed-now/"><u>Canon's Code B200 Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-setup-for-officejet-pro-m110-series-a-complete-walkthrough/"><u>Wireless Setup for Officejet Pro M110 Series: A Complete Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rejuvenate-your-mf4770n-experience-for-win11-8-7/"><u>Rejuvenate Your MF4770n Experience for Win11, 8, 7</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-and-windows-10-unite-for-smooth-driver-load-resolution/"><u>AMD and Windows 10 Unite for Smooth Driver Load Resolution</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-the-best-of-both-worlds-free-and-paid-video-editors-for-windows-11/"><u>Updated In 2024, The Best of Both Worlds Free and Paid Video Editors for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-mask-dimming-functionality-in-system-preferences/"><u>Tactics to Mask Dimming Functionality in System Preferences</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-mastering-mobile-screen-recording-in-snapchat/"><u>[New] 2024 Approved  Mastering Mobile  Screen Recording in Snapchat</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-artisans-guide-to-tiktok-captions-top-5-craftsmanship-strategies/"><u>2024 Approved  The Artisan's Guide to TikTok Captions  Top 5 Craftsmanship Strategies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlock-the-power-of-your-youtube-brand-for-growth-in-subs/"><u>2024 Approved  Unlock the Power of Your YouTube Brand for Growth in Subs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unveiling-the-foremost-android-alternatives-for-playstation-2-emulation-for-2024/"><u>[Updated] Unveiling The Foremost Android Alternatives for PlayStation 2 Emulation for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/effortless-capture-of-webcast-radios-your-practical-guide/"><u>Effortless Capture of Webcast Radios  Your Practical Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-artists-guide-to-best-free-3d-psds/"><u>In 2024, Innovative Artists' Guide to Best Free 3D PSDs</u></a></li>
</ul></div>
