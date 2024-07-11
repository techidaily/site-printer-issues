---
title: Fixing Erratic Printer Spooler Behavior (Win 11 & Older)
date: 2024-07-10T17:46:10.294Z
updated: 2024-07-11T17:46:10.294Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fixing Erratic Printer Spooler Behavior (Win 11 & Older)
excerpt: This Article Describes Fixing Erratic Printer Spooler Behavior (Win 11 & Older)
keywords: Fixing Erratic Printer Spooler Behavior,Spooler Error Troubleshooting (Windows 11 & Older),Printer Driver Issues in Windows 11 & XP,Troubleshoot Printing Errors on Windows,Resolving Windows Printer Problems,Spooled Document Synchronization Fix (Win 11 and Previous Versions),Print Spooler Error Recovery Solutions (Windows 10/8/7/Vista/XP)
thumbnail: https://thmb.techidaily.com/4c1fc861d688eb17793358701272fcb990bfc951646524d04a51586ab07132c7.jpg
---

## Fixing Erratic Printer Spooler Behavior (Win 11 & Older)

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
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-os-struggles-hp-driver-not-available/"><u>Windows OS Struggles: HP Driver Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-10/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/demystifying-error-x97-on-epson-printers/"><u>Demystifying Error X97 on Epson Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-integrating-printer-model-8720-in-pc/"><u>How-To: Integrating Printer Model 8720 in PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-blank-page-woes-printer-remedy-discovered/"><u>The End of Blank Page Woes: Printer Remedy Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-print-service-non-functioning-windows/"><u>[TROUBLESHOOT] Print Service Non-Functioning Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-on-epson-dispelled/"><u>Error Code 0X97 on Epson Dispelled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-connected-successfully/"><u>Resolved: PRINTER Connected Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1187/"><u>Canon MF4770n Driver Update in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printing-speed-instantly/"><u>Boost Printing Speed Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-shown-solutions-for-network-print-issues/"><u>Printer Not Shown: Solutions for Network Print Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-woes-here-are-your-five-easy-fixes-in-windows-11/"><u>Canon Printer Woes? Here Are Your Five Easy Fixes in Windows 11!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-your-printer-has-experienced-an-unexpected-configuration-problem/"><u>[SOLVED] Your Printer Has Experienced an Unexpected Configuration Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-printed-properly-post-hp-printer-glitch-resolution/"><u>Paper Printed Properly Post-HP Printer Glitch Resolution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-out-hp-printers-error-code-oxc4eb827f/"><u>Clearing Out HP Printer's Error Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-mf4770n-functionality-in-windows-ecosystems/"><u>Optimize MF4770n Functionality in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-service-restored-in-win7/"><u>Print Service Restored in Win7</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-dive-into-immersion-youtubes-best-vr-content/"><u>[New] 2024 Approved  Dive Into Immersion  YouTube's Best VR Content</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/secure-your-sound-3-safe-methods-of-audio-from-youtube-for-2024/"><u>Secure Your Sound  3 Safe Methods of Audio From YouTube for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-mastering-whatsapp-call-recording-techniques/"><u>[Updated] In 2024, Mastering WhatsApp Call Recording Techniques</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-trim-and-edit-videos-on-your-computer-top-10-software/"><u>New Trim and Edit Videos on Your Computer Top 10 Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simple-setup-winning-the-art-of-fishy-voice-transformation/"><u>In 2024, Simple Setup  Winning the Art of Fishy Voice Transformation</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-capture-and-save-with-ease-top-5-pc-snipers-reviewed-for-2024/"><u>[New] Capture & Save with Ease  Top 5 PC Snipers Reviewed for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-motorola-moto-g34-5g-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Motorola Moto G34 5G Devices</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-maximize-your-home-studio-webcam-recorder-essentials/"><u>[Updated] In 2024, Maximize Your Home Studio - WebCam Recorder Essentials</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-motion-blur-photo-with-gimp-step-by-step-guide/"><u>New 2024 Approved Motion Blur Photo With GIMP Step-By-Step Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-6-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone 6 when Phone is Broken?</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-breakthrough-methodology-introducing-chapters-in-your-youtube-videos/"><u>[New] Breakthrough Methodology  Introducing Chapters in Your YouTube Videos</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-cease-discord-activity-on-all-screens/"><u>[New] In 2024, Cease Discord Activity on All Screens</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-enhance-visibility-on-tiktok-a-list-of-powerful-username-concepts-for-2024/"><u>[Updated] Enhance Visibility on TikTok - A List of Powerful Username Concepts for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-creating-your-own-path-on-youtube-a-course-guide/"><u>[New] Creating Your Own Path on YouTube  A Course Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-blissful-onboarding-guide-for-new-users/"><u>2024 Approved  Blissful Onboarding Guide for New Users</u></a></li>
</ul></div>
