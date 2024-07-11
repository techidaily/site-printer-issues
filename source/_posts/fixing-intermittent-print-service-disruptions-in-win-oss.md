---
title: Fixing Intermittent Print Service Disruptions in Win OSs
date: 2024-07-10T17:23:25.445Z
updated: 2024-07-11T17:23:25.445Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fixing Intermittent Print Service Disruptions in Win OSs
excerpt: This Article Describes Fixing Intermittent Print Service Disruptions in Win OSs
keywords: Windows Operating System Print Problems,Resolving Printer Interruptions on PCs,Troubleshooting Print Service Issues in Windows,Fixing WinOS Print Disconnections,Solutions for Recurring Print Errors in Windows,Addressing Print Service Outages on Windows Machines,Overcoming Printer Connectivity Problems in Win OSs
thumbnail: https://thmb.techidaily.com/4cc762a4b279881853cc89fa45ad5b311a699fba43bbccdd544fcfb9e3bcdf69.jpg
---

## Fixing Intermittent Print Service Disruptions in Win OSs

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
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-error-code-b200/"><u>Mended Error Code: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-canon-printer-working-again-find-5-fixes-for-the-non-prints-in-windows-11/"><u>Get Your Canon Printer Working Again! Find 5 Fixes for the Non-Prints in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-assembly-combining-hp-printer-model-with-computer/"><u>Technical Assembly: Combining HP Printer Model with Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-responsive-printer-halted-what-to-do/"><u>Non-Responsive Printer Halted, What to Do?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-inkjet-workflows-new-printer-software-update-for-windows-7/"><u>Streamline Inkjet Workflows: New Printer Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-wireless-printing-issue-with-hp-envy-5680v5/"><u>Fixed Wireless Printing Issue with HP Envy 5680V5</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-start-initiating-your-hp-printer-for-windows-users/"><u>Smooth Start: Initiating Your HP Printer for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-inkjet-aio-updater-for-win7/"><u>Dell Inkjet AIO Updater for Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-nightmares-solutions-here/"><u>Windows 11 Printer Nightmares? Solutions Here</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanned-device-connection-issue-on-win10/"><u>Fixing Scanned Device Connection Issue on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-sheet-woes-end-with-hp-printer-update-fixed/"><u>White Sheet Woes End with HP Printer Update Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-in-effect-for-b200/"><u>Fix In Effect for B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/interpreting-codes-for-inkjet-problems/"><u>Interpreting Codes for Inkjet Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alert-local-print-queue-not-running/"><u>[ALERT] Local Print Queue Not Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-straightforward-approach-to-pcl-xl-malfunctions/"><u>A Straightforward Approach to PCL XL Malfunctions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-mf4770n-integration-with-win-1087/"><u>Boosting MF4770n Integration with Win 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/spooler-error-printer-not-initializing-in-windows/"><u>Spooler Error: Printer Not Initializing in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-clearance-of-stalled-print-queue/"><u>Speedy Clearance of Stalled Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-missing-canon-pixma-mp620-printer-not-finding-win10/"><u>[Driver Missing] Canon Pixma MP620 Printer Not Finding WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/handling-printers-gone-dark/"><u>Handling Printers Gone Dark</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-link-between-printer-and-network/"><u>Re-Establishing Link Between Printer & Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-erratic-printer-spooler-behavior-win-11-and-older/"><u>Fixing Erratic Printer Spooler Behavior (Win 11 & Older)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compreeed-software-bundle-officejet-pro-8600-windows-integration/"><u>Compreeed Software Bundle: OfficeJet Pro 8600, Windows Integration</u></a></li>
<li><a href="https://extra-tips.techidaily.com/choosing-ultrawide-vs-uhd-4k-displays-a-comprehensive-guide/"><u>Choosing UltraWide vs UHD 4K Displays  A Comprehensive Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-oppo-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Oppo</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-to-use-itop-recorder-a-compelling-case-in-2024/"><u>[New] To Use ITop Recorder  A Compelling Case, In 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-apple-iphone-7-plus-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock Apple iPhone 7 Plus to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-clipcomposers-journey-thorough-review-of-androvid/"><u>[Updated] ClipComposer's Journey – Thorough Review of AndroVid</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-time-lapse-techniques-for-samsung-enthusiasts/"><u>[Updated] Unveiling Time Lapse Techniques for Samsung Enthusiasts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-ultimate-clarity-choosing-the-perfect-4k-screen/"><u>In 2024, Unlock Ultimate Clarity  Choosing the Perfect 4K Screen</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capturing-life-in-motion-ipad-timelapse-guide/"><u>[New] Capturing Life in Motion  IPad Timelapse Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/bypass-watermarks-on-iphone-download-tiktok-videos/"><u>Bypass Watermarks on iPhone  Download TikTok Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-combo-guide-zooming-into-facebook-streaming/"><u>2024 Approved  The Ultimate Combo Guide  Zooming Into Facebook Streaming</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-free-to-mp3-journey-top-10-online-converters/"><u>[New] Free-to-Mp3 Journey  Top 10 Online Converters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-choosing-the-right-screen-recorder-outside-of-xbox/"><u>[New] In 2024, Choosing the Right Screen Recorder, Outside of Xbox</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-x100-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on X100.</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-powerful-strategies-for-optimizing-gratuitous-timer-use/"><u>[Updated] 2024 Approved  Powerful Strategies for Optimizing Gratuitous Timer Use</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-laughing-liberally-with-our-meme-toolbox/"><u>[New] Laughing Liberally with Our Meme Toolbox</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-samsung-galaxy-m34-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Samsung Galaxy M34</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-oppo-f25-pro-5g-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Oppo F25 Pro 5G</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-best-at-memes-app-version/"><u>The Best at Memes (App Version)</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/simplified-pubg-voice-alteration-guide/"><u>Simplified PUBG Voice Alteration Guide</u></a></li>
</ul></div>
