---
title: How to Prevent Print Service Interruptions on W7/W10/W11
date: 2024-06-28T06:56:29.810Z
updated: 2024-06-29T06:56:29.810Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Prevent Print Service Interruptions on W7/W10/W11
excerpt: This Article Describes How to Prevent Print Service Interruptions on W7/W10/W11
keywords: Microsoft Windows Printing Troubleshooting,Preventing Print Service Disruptions W7/W8/W10/W11,Office Printer Problems on Windows 7/8/10/11,How to Fix Print Errors in W7, W8, W10, W11,Print Services Interruptions on Windows 7/8/10/11,Troubleshoot W7/W10/Win11 Print Service Failures,Preventing Printer Crashes on Windows 7/8/10/Win11
thumbnail: https://thmb.techidaily.com/c367633b9f9ef727c06fd08d3dd4d78a496570d920b7ae31f5d249d448106c6d.jpg
---

## How to Prevent Print Service Interruptions on W7/W10/W11

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
<li><a href="https://printer-issues.techidaily.com/windows-problems-no-access-to-hp-printer-drivers/"><u>Windows Problems: No Access to HP Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-paper-jamming-concern/"><u>Mended Paper Jamming Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-missing-driver-in-windows-os/"><u>HP Printer Setup: Missing Driver in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-canon-pixma-mp620-unseen-in-win11/"><u>[Driver Difficulty] Canon Pixma MP620 Unseen in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-workflow-swiftly/"><u>Optimize Printing Workflow Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-tangle-printer-reconfigured-incorrectly/"><u>Technical Tangle: Printer Reconfigured Incorrectly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/manual-setting-up-hp-officejet-on-desktop-system/"><u>Manual: Setting up HP Officejet on Desktop System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-win-10-printer-disruptions-success-story/"><u>The End of Win 10 Printer Disruptions - Success Story</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-cerseis-calls-top-15-sites-for-hearing-heroes-tts-files/"><u>[Updated] In 2024, Cersei's Calls  Top 15 Sites for Hearing Heroes' TTS Files</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-visualloger-12-professional-for-2024/"><u>[Updated] VisualLoger 12 Professional for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-making-memorable-impressions-with-fb-slideshow-features/"><u>In 2024, Making Memorable Impressions with FB Slideshow Features</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-infinix-smart-8-pro-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-if-you-do-not-know-how-to-quicktime-trim-video-clips-you-are-in-the-right-place-we-have-provided-information-that-will-help-you-trim-videos-with-thi/"><u>Updated If You Do Not Know How to QuickTime Trim Video Clips, You Are in the Right Place. We Have Provided Information that Will Help You Trim Videos with This Application and Make Them Engaging for Viewers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-banishing-curved-visuals-correcting-gopros-fish-eye/"><u>[Updated] Banishing Curved Visuals  Correcting GoPro's Fish Eye</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-guide-to-gamers-screen-recordings-with-win10-for-2024/"><u>[Updated] The Ultimate Guide to Gamers' Screen Recordings with Win10 for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-convert-instagram-videos-to-mp3-a-step-by-step-guide/"><u>2024 Approved Convert Instagram Videos to MP3 A Step-by-Step Guide</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-10-popular-cartoon-characters-that-should-top-your-list/"><u>New 10 Popular Cartoon Characters That Should Top Your List</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-refreshing-mistake-on-tiktok-what-happens-for-2024/"><u>[New] Refreshing Mistake on TikTok – What Happens for 2024</u></a></li>
</ul></div>
