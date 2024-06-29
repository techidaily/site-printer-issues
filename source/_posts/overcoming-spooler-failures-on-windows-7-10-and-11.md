---
title: Overcoming Spooler Failures on Windows 7, 10 & 11
date: 2024-06-28T07:22:33.691Z
updated: 2024-06-29T07:22:33.691Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Overcoming Spooler Failures on Windows 7, 10 & 11
excerpt: This Article Describes Overcoming Spooler Failures on Windows 7, 10 & 11
keywords: Spooler Failure Solution,Windows 7 Spooler Troubleshooting,Spooler Errors on Windows 10,Overcoming Print Service Manager Issues,Spooler Troubleshooting Guide for Windows,Troubleshoot Spooler Failure in Windows,Preventing Print Service Manager Errors
thumbnail: https://thmb.techidaily.com/79f38eb573cc99e5f54bf7180a8b2f400aa646add73d8ccbbc068b9cd2192911.jpg
---

## Overcoming Spooler Failures on Windows 7, 10 & 11

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
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/complete-printing-solution-unveiled/"><u>Complete Printing Solution Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-inkjet-driver-errors-on-w11/"><u>Solve Inkjet Driver Errors on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-recognized-missing-hp-drivers-on-win1011/"><u>Printer Not Recognized: Missing HP Drivers on Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-scanner-on-windows-11/"><u>Fixing Non-Operational Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prevent-windows-10-printer-malfunctions-and-fails/"><u>Prevent Windows 10 Printer Malfunctions and Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574106588-fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-the-erratic-behavior-of-print-spooler-windows/"><u>Troubleshooting the Erratic Behavior of Print Spooler (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-what-to-look-for-in-audio-editor-software-for-mac-os-x/"><u>New 2024 Approved What to Look for in Audio Editor Software for Mac OS X</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-the-craft-of-epic-gopro-time-lapse-video/"><u>Mastering the Craft of Epic GoPro Time Lapse Video</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-recording-skype-best-practices-for-pcs-and-macs/"><u>In 2024, Recording Skype  Best Practices for PCs & Macs</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-smoothen-your-mobile-videos-with-these-top-rated-free-android-apps/"><u>Updated 2024 Approved Smoothen Your Mobile Videos with These Top-Rated Free Android Apps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-enhance-your-channels-image-adding-watermarks-and-logos-to-video-posts-for-2024/"><u>[Updated] Enhance Your Channel's Image  Adding Watermarks & Logos to Video Posts for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-grading-for-emotion-altering-footage-to-evoke-feelings/"><u>In 2024, Grading for Emotion  Altering Footage to Evoke Feelings</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-from-iphone-8-plus-by-drfone-ios/"><u>Unlock Apple ID without Phone Number From iPhone 8 Plus</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-scouring-youtubes-notable-responses/"><u>In 2024, Scouring YouTube's Notable Responses</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-free-dvd-player-for-windows-10-our-top-10-picks/"><u>Updated 2024 Approved Free DVD Player for Windows 10 Our Top 10 Picks</u></a></li>
</ul></div>
