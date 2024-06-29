---
title: Troubleshooting Non-Starting Spooler on Your PC (Windows)
date: 2024-06-28T06:58:41.039Z
updated: 2024-06-29T06:58:41.039Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Troubleshooting Non-Starting Spooler on Your PC (Windows)
excerpt: This Article Describes Troubleshooting Non-Starting Spooler on Your PC (Windows)
keywords: Windows Spooler Troubleshooting Guide,Fix Non-Starting Spooler (Windows),How to Troubleshoot Windows Services,Fixing Spooler Service Failure (Windows),Windows Spooler Errors Resolution,Reasons for Non-Starting Windows Spooler,Troubleshoot Spooler Service (Windows)
thumbnail: https://thmb.techidaily.com/db339cfb71ad17e704275f446976657b74bdf593b2c3464a856c74dd3bbe549b.jpg
---

## Troubleshooting Non-Starting Spooler on Your PC (Windows)

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
<li><a href="https://printer-issues.techidaily.com/resume-printing-with-online-canon-printer-tips/"><u>Resume Printing with Online Canon Printer Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-journey-successfully-installing-a-hp-printer-on-windows/"><u>Stepwise Journey: Successfully Installing a HP Printer on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-crosscheck-print-failures/"><u>Clearing Crosscheck Print Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-component-pixma-mp620-driver-on-windows-10/"><u>[Missing Component] Pixma MP620 Driver on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-error-correction/"><u>Mastering Printer Error Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unpacking-pcl-xl-breakdowns-effortlessly/"><u>Unpacking PCL XL Breakdowns Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-malfunction-mystery/"><u>Unraveling Printer Malfunction Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-quickly-link-canon-devices-on-wi-fi/"><u>How to Quickly Link Canon Devices on Wi-Fi</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-steps-to-add-subtitles-in-canva/"><u>Updated 2024 Approved Steps to Add Subtitles in Canva</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-twitter-to-mp3-how-to-convert-videos-on-social-media/"><u>[New] Twitter to MP3  How to Convert Videos on Social Media</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-choreographed-audio-selecting-superior-soundtracks-for-montage-masterpieces/"><u>In 2024, Choreographed Audio Selecting Superior Soundtracks for Montage Masterpieces</u></a></li>
<li><a href="https://extra-information.techidaily.com/efficient-techniques-for-editing-account-numbers-on-tiktok/"><u>Efficient Techniques for Editing Account Numbers on TikTok</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-investigating-spotlighted-comments-online/"><u>[New] Investigating Spotlighted Comments Online</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-seamless-gif-converters-online-5-rated-highly-for-2024/"><u>[New] Seamless GIF Converters Online, 5 Rated Highly for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-interactive-guide-twitter-and-facebook-synergy/"><u>2024 Approved  Interactive Guide  Twitter & Facebook Synergy</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-value-panoramic-recording-equipment-for-savvy-shoppers/"><u>In 2024, Top Value Panoramic Recording Equipment for Savvy Shoppers</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-comprehensive-guide-to-vocaroo-audio-capture-practices-and-substitutes/"><u>Updated In 2024, Comprehensive Guide to Vocaroo Audio Capture Practices and Substitutes</u></a></li>
</ul></div>
