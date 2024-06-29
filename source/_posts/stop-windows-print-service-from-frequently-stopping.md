---
title: Stop Windows Print Service From Frequently Stopping
date: 2024-06-28T07:08:29.302Z
updated: 2024-06-29T07:08:29.302Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop Windows Print Service From Frequently Stopping
excerpt: This Article Describes Stop Windows Print Service From Frequently Stopping
keywords: Windows Print Spooler Troubleshooting,Stop Printer Service Restarts,Fix Print Spooler Errors,Windows Print Service Stability Improvement,Prevent Windows Printer Hangs,Enhance Print Service Performance in Windows,Windows Printer Spooling Issues Fix Guide
thumbnail: https://thmb.techidaily.com/6110f59d84b8b2836afe3cb9128ab55b4983bac7c041837cad5f3c0f9163df97.jpg
---

## Stop Windows Print Service From Frequently Stopping

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
<li><a href="https://printer-issues.techidaily.com/cannot-load-printer-driver-not-detected-by-win/"><u>Cannot Load Printer: Driver Not Detected by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-canon-printer-to-wifi-easily/"><u>How to Connect Canon Printer to Wifi Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fix-all-paper-print-job-achievement/"><u>New Fix: All-Paper Print Job Achievement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversed-printing-mishaps-hp-printer-now-solid-and-sure/"><u>Reversed Printing Mishaps: HP Printer Now Solid and Sure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-compatible-driver-release/"><u>Officejet Pro 8600 Windows Compatible Driver Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-cant-find-driver-on-windows-os/"><u>HP Printer Setup Error: Can't Find Driver on Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failure-cannot-locate-mp620-driver-on-windows-10/"><u>[Driver Search Failure] Cannot Locate MP620 Driver on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-inactive-hp-printing-units/"><u>Reviving Inactive HP Printing Units</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-looking-forward-to-making-up-your-career-in-video-editing-land-in-here-to-learn-about-the-credibility-of-some-popular-video-editing-courses-for-2024/"><u>New Looking Forward to Making up Your Career in Video Editing? Land in Here to Learn About the Credibility of some Popular Video Editing Courses for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-14-pro-max-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 14 Pro Max To Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-step-by-step-strategies-to-make-your-video-stand-out-with-effective-end-screens/"><u>2024 Approved  Step-by-Step Strategies to Make Your Video Stand Out with Effective End Screens</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-boosting-brand-visibility-essential-insta-highlight-upgrades/"><u>[New] In 2024, Boosting Brand Visibility  Essential Insta Highlight Upgrades</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-shoot-past-tiktok-the-top-5-social-network-alternatives/"><u>In 2024, Shoot Past TikTok  The Top 5 Social Network Alternatives</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oppo-a18-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Oppo A18 Without Password | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-optimized-approach-to-delete-unwanted-youtube-posts/"><u>[Updated] Optimized Approach to Delete Unwanted YouTube Posts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/unlocking-real-time-voice-manipulation-top-6-application-choices-for-2024/"><u>Unlocking Real-Time Voice Manipulation Top 6 Application Choices for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-a-comprehensive-look-at-editing-and-uploading-virtual-reality-videos-to-youtube/"><u>In 2024, A Comprehensive Look at Editing and Uploading Virtual Reality Videos to YouTube</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-vivo-x-flip-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Vivo X Flip</u></a></li>
</ul></div>
