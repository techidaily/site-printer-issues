---
title: Immediate Fixes for Non-Responsive Printer Service (Windows)
date: 2024-06-28T07:13:24.472Z
updated: 2024-06-29T07:13:24.472Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Fixes for Non-Responsive Printer Service (Windows)
excerpt: This Article Describes Immediate Fixes for Non-Responsive Printer Service (Windows)
keywords: Non-Responsive Printer Troubleshooting,Windows Non-Responsive Printer Fixes,Resolve Windows Printer Hangup,Fix Non-Responsive Print Service in Windows,Windows Printer Connection Issues,Immediate Remedies for Windows Print Errors,Unresponsive Printer Service Diagnostics (Windows)
thumbnail: https://thmb.techidaily.com/2efc75770914ae3db1b269aa438526aea2b37f029f972da8e465d2fb4ae63f10.jpg
---

## Immediate Fixes for Non-Responsive Printer Service (Windows)

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
<li><a href="https://printer-issues.techidaily.com/solving-officejets-no-print-malaise/"><u>Solving OfficeJet's No Print Malaise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-mended-hp-printer-no-output/"><u>Successfully Mended HP Printer No Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-action-on-queued-print-processes/"><u>Immediate Action on Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-inkjet-connectivity-for-windows-vistaxp-users/"><u>Restore Inkjet Connectivity for Windows Vista/XP Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-error-unable-to-locate-printer-drivers/"><u>[WIN ERROR] Unable to Locate Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-failure-not-recognizing-canon-model/"><u>Printer Failure: Not Recognizing Canon Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-usb-printer-reset-problems-post-sleep-cycle/"><u>Win7 USB Printer Reset: Problems Post-Sleep Cycle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-wireless-printer-with-hp-color-life-series/"><u>How To: Set Up a Wireless Printer with HP Color Life Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-hp-printer-setup-manual/"><u>Win HP Printer Setup Manual</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-printers-purpose-beyond-empty-pages/"><u>Reviving a Printer's Purpose Beyond Empty Pages</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-infinix-zero-5g-2023-turbo-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Infinix Zero 5G 2023 Turbo Pattern Lock Screen</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/turning-youtube-sounds-into-text-an-in-depth-no-cost-course/"><u>Turning YouTube Sounds Into Text  An In-Depth, No-Cost Course</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-animations-how-to-craft-engaging-professional-looking-gifs/"><u>In 2024, YouTube Animations  How To Craft Engaging, Professional-Looking GIFs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/premium-designers-stellar-instagram-hlv-page-builders-for-2024/"><u>Premium Designers  Stellar Instagram HLV Page Builders for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-unboxing-splice-a-detailed-examination-of-the-video-editing-app-for-2024/"><u>Updated Unboxing Splice A Detailed Examination of the Video Editing App for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-sharing-tweets-via-vids-on-whatsapp-now/"><u>[New] 2024 Approved  Sharing Tweets via Vids on WhatsApp Now</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-mastering-auditory-narratives-the-ultimate-list-of-where-to-find-premium-podcast-sound-effects/"><u>2024 Approved Mastering Auditory Narratives The Ultimate List of Where to Find Premium Podcast Sound Effects</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-oppo-find-n3-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Oppo Find N3? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-unlocking-virtual-meetings-googles-facetime-tutorial/"><u>In 2024, Unlocking Virtual Meetings  Google's Facetime Tutorial</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Samsung Galaxy S24? | Dr.fone</u></a></li>
</ul></div>
