---
title: Resolving Frequent Spooler Halt Issues on PCs Running Windows
date: 2024-06-28T07:02:04.272Z
updated: 2024-06-29T07:02:04.272Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolving Frequent Spooler Halt Issues on PCs Running Windows
excerpt: This Article Describes Resolving Frequent Spooler Halt Issues on PCs Running Windows
keywords: Spooler Halt Issues,PC Frequent Halt,Windows System Halt,Fixing Halt Problems,Resolving Spooler Errors,Troubleshoot Spooler Failure,Stop Spooler Crashes in Windows
thumbnail: https://thmb.techidaily.com/30c3f68025cf60445ca0af9503de0d05421151fac72dff09f39b3449e1fcd630.jpg
---

## Resolving Frequent Spooler Halt Issues on PCs Running Windows

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
<li><a href="https://printer-issues.techidaily.com/how-to-get-your-brother-printer-back-up-and-running-on-windows/"><u>How to Get Your Brother Printer Back Up & Running on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-non-print-in-canon-on-windows-with-ease/"><u>Resolve Non-Print in Canon on Windows with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-9330cdw-fan-and-software-guide/"><u>Brother 9330CDW Fan & Software Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-secrets-of-pcl-xl-repairs/"><u>Unraveling the Secrets of PCL XL Repairs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-operational-efficiency-with-mf4770n-on-w11w8w7-windows/"><u>Boost Operational Efficiency with MF4770n on W11/W8/W7 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-story-unshackling-printer-from-update-chains/"><u>Success Story: Unshackling Printer From Update Chains</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-guide-to-stopping-repeated-spooler-halt-in-windows/"><u>Essential Guide to Stopping Repeated Spooler Halt in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-unboxed-to-printed-the-complete-win-hp-printer-guidebook/"><u>From Unboxed to Printed: The Complete Win HP Printer Guidebook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-art-of-humor-in-video-tips-for-facebook-and-instagram-memes/"><u>2024 Approved  The Art of Humor in Video  Tips for Facebook and Instagram Memes</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-13-pro-max-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 13 Pro Max</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitch-and-prime-whos-watching-the-show-2023-edition-for-2024/"><u>[Updated] Twitch and Prime  Who’s Watching the Show? 2023 Edition for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-propel-your-youtube-journey-breakthroughs-at-the-500-subscriber-mark/"><u>2024 Approved  Propel Your YouTube Journey  Breakthroughs at the 500-Subscriber Mark</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/rethinking-streaming-new-platforms-challenge-obs/"><u>Rethinking Streaming  New Platforms Challenge OBS</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-superior-smartphones-that-dominate-in-video-recording/"><u>In 2024, Superior Smartphones That Dominate in Video Recording</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-video-storytelling-made-easy-best-ios-collage-apps/"><u>Updated 2024 Approved Video Storytelling Made Easy Best iOS Collage Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-10-virtual-reality-headgear-for-smartphones/"><u>Best 10 Virtual Reality Headgear for Smartphones</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/recording-webinars-on-a-budget-friendly-platform-for-2024/"><u>Recording Webinars on a Budget-Friendly Platform for 2024</u></a></li>
</ul></div>
