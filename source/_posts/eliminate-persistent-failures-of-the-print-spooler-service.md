---
title: Eliminate Persistent Failures of the Print Spooler Service
date: 2024-06-28T06:55:31.000Z
updated: 2024-06-29T06:55:31.000Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Eliminate Persistent Failures of the Print Spooler Service
excerpt: This Article Describes Eliminate Persistent Failures of the Print Spooler Service
keywords: Print Spooler Service Failure,Stop Printer Print Queue Error,Spooler Service Troubleshooting,Print Spooler Recovery Steps,Preventing Print Spooler Crashes,Print Server Management Tips,Spooler Service Update Guidelines
thumbnail: https://thmb.techidaily.com/a84f233e2df716933c1def7036ee5f60e5a298fe75b79753bbc6bfd2f6d9a6e5.jpg
---

## Eliminate Persistent Failures of the Print Spooler Service

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
<li><a href="https://printer-issues.techidaily.com/make-your-canon-printer-print-effortlessly-on-pc/"><u>Make Your Canon Printer Print Effortlessly on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-mfc-9330-cdw-up-and-running/"><u>Get Your MFC-9330 CDW Up and Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-printers-purpose-beyond-empty-pages/"><u>Reviving a Printer's Purpose Beyond Empty Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-fixer-regain-lost-network-print-visibility/"><u>[Print Issue Fixer] Regain Lost Network Print Visibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-inkjet-aio-updater-for-win7/"><u>Dell Inkjet AIO Updater for Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-jammed-printers/"><u>Unlocking Jammed Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-b200/"><u>Error Resolution: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-ad-domain-offline/"><u>PPrintError - AD Domain Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-apple-iphone-xs-max-by-drfone-ios/"><u>Different Methods To Unlock Your Apple iPhone XS Max</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-removing-noise-from-music-using-adobe-audition-reviewing-all-possibilities-for-2024/"><u>New Removing Noise From Music Using Adobe Audition Reviewing All Possibilities for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-mastering-a-new-identity-the-complete-tiktok-username-transformation/"><u>[Updated] In 2024, Mastering a New Identity  The Complete TikTok Username Transformation</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-social-media-image-mastery-a-guide-to-perfect-aspect-ratios-and-dimensions/"><u>New 2024 Approved Social Media Image Mastery A Guide to Perfect Aspect Ratios and Dimensions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/chortlechamber-personalize-everyday-humor-online-for-2024/"><u>ChortleChamber  Personalize Everyday Humor Online for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-poco-f5-pro-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Poco F5 Pro 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-audio-amplification-for-powerpoint-presentations/"><u>In 2024, Audio Amplification for PowerPoint Presentations</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unveiling-the-full-potential-of-powerdirector-24/"><u>2024 Approved  Unveiling the Full Potential of PowerDirector '24</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-conquering-the-crash-solutions-for-windows-10-photos-issues/"><u>[New] Conquering the Crash  Solutions for Windows 10 Photos Issues</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unlock-the-hidden-potential-of-windows-11-with-these-tips/"><u>[New] Unlock the Hidden Potential of Windows 11 with These Tips</u></a></li>
</ul></div>
