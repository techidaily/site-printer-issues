---
title: How to Fix Print Spooler Keeps Stopping on Windows 10 & 7
date: 2024-06-28T06:50:36.337Z
updated: 2024-06-29T06:50:36.337Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Fix Print Spooler Keeps Stopping on Windows 10 & 7
excerpt: This Article Describes How to Fix Print Spooler Keeps Stopping on Windows 10 & 7
keywords: Fix Print Spooler Error,Solve Windows 7/10 Print Issues,Stop Print Spooler Failures,Troubleshoot Windows 7/10 Print Service,Resolve Spooler Problem on Windows 10,Fix Spooler Errors in Windows 7/10,Preventing Print Service Crashes on Windows 7/10
thumbnail: https://thmb.techidaily.com/de4f0312e209bc69406fe77be7db4ffab9fd4723c69e6ec9a49854fd1e940559.jpg
---

## How to Fix Print Spooler Keeps Stopping on Windows 10 & 7

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
<li><a href="https://printer-issues.techidaily.com/boost-your-output-v305-aio-driver-enhancement-in-win7/"><u>Boost Your Output: V305 AIO Driver Enhancement in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-guide-to-mfc-9330cdw-setup/"><u>Simple Guide to MFC-9330CDW Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-wireless-printer-setup-tutorial/"><u>HP Wireless Printer Setup Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-problem-hp-printer-driver-unavailable-in-winxo/"><u>[Windows Problem] HP Printer Driver Unavailable in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-scanner-link-to-computer-post-windows-update/"><u>Restore Scanner Link to Computer Post-Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574001783-technical-mishap-printer-setup-misstep/"><u>Technical Mishap: Printer Setup Misstep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-clearing-print-job-queue/"><u>Accelerate Clearing Print Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-cannot-retrieve-printer-drivers/"><u>Windows Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-failed-printer-defaults-error-code-0x00000709-overcome/"><u>Resetting Failed Printer Defaults: Error Code 0X00000709 Overcome</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/enhance-your-videos-a-step-by-step-guide-to-3d-effects-on-windows/"><u>Enhance Your Videos A Step-by-Step Guide to 3D Effects on Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-journey-to-freedom-with-free-movie-player-os-x-and-windows/"><u>2024 Approved  Journey to Freedom with FREE MOVIE PLAYER (OS X & Windows)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/cket-your-youtube-traffic-with-effective-outros/"><u>Skyrocket Your YouTube Traffic with Effective Outros</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-ease-of-skipping-through-tiktok-media/"><u>[Updated] In 2024, The Ease of Skipping Through TikTok Media</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-oppo-find-x7-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Oppo Find X7 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mobile-marketing-mastery-easy-steps-to-create-your-own-youtube-channel-for-2024/"><u>Mobile Marketing Mastery  Easy Steps to Create Your Own YouTube Channel for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-gopros-top-5-subaquatic-filter-choices/"><u>[New] In 2024, GoPro's Top 5 Subaquatic Filter Choices</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-az-screen-recorder-review-series-for-2024/"><u>[Updated] AZ Screen Recorder Review Series for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-list-10-best-free-online-video-looping-software/"><u>In 2024, The Ultimate List 10 Best Free Online Video Looping Software</u></a></li>
</ul></div>
