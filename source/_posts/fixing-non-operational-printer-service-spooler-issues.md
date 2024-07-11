---
title: Fixing Non-Operational Printer Service (Spooler) Issues
date: 2024-07-10T16:51:55.108Z
updated: 2024-07-11T16:51:55.108Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fixing Non-Operational Printer Service (Spooler) Issues
excerpt: This Article Describes Fixing Non-Operational Printer Service (Spooler) Issues
keywords: Printer Spooler Troubleshooting,Causes of Printer Hang-Up,Solving Spooler Errors on Windows Devices,Print Queue Management Fixes,Spooler Service Repair Guide,Optimizing Printer Performance (Spooler),Preventing Print Spooler Failures
thumbnail: https://thmb.techidaily.com/9878ff62b08356ff78ffb4d4ce5fd0c27ab1ffdc4dd530f388b0fa3845feed6f.jpg
---

## Fixing Non-Operational Printer Service (Spooler) Issues

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
<li><a href="https://printer-issues.techidaily.com/printer-unresponsive-solutions-needed/"><u>Printer Unresponsive: Solutions Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-error-code-following-device-suspend-w7/"><u>[Solved] Printer Error Code Following Device Suspend, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-overcome-unresponsive-hp-devices/"><u>Strategies to Overcome Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compreeed-software-bundle-officejet-pro-8600-windows-integration/"><u>Compreeed Software Bundle: OfficeJet Pro 8600, Windows Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-w11-printer-software-problems/"><u>Resolve W11 Printer Software Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-brother-printer-print-operation-in-windows-oses/"><u>Streamlining Brother Printer Print Operation in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-brother-printer-issues-in-win1110/"><u>Quick Tips for Brother Printer Issues in Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-online-functionality-regained/"><u>Epson Online Functionality Regained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-network-printer-how-to-find-it-on-your-os/"><u>Hidden Network Printer: How to Find It on Your OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-noise-level-fluctuation-in-hp-officejet-pro-x100/"><u>Repaired Noise Level Fluctuation in HP Officejet Pro X100</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-wireless-setup-guide-for-brother-fans/"><u>MFC-9330 Wireless Setup Guide for Brother Fans</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-printer-hp-deskjet-d1360-struggles-on-various-windows-platforms/"><u>[Installing Printer]: HP Deskjet D1360 Struggles on Various Windows Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-canon-printer-a-visual-walkthrough/"><u>How to Set Up a Canon Printer: A Visual Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-unresolved-printer-queue-issue/"><u>Speed Up Unresolved Printer Queue Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-and-connecting-your-canon-printer/"><u>Efficiently Setting Up and Connecting Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-mf4770n-support-software-windows-xp-7/"><u>Installing MF4770n Support Software Windows XP-7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-fix-for-blank-sheets-in-hp-printers-cycle/"><u>Successful Fix for Blank Sheets in HP Printer's Cycle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-compatibility-boosting-mf4770n-performance-in-win11win8w7/"><u>Enhance Compatibility: Boosting MF4770n Performance in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-hp-printer-drivers-on-windows-1011/"><u>Finding HP Printer Drivers on Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-installing-hp-photosmart-printer/"><u>Step-by-Step: Installing HP PhotoSmart Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fix-all-paper-print-job-achievement/"><u>New Fix: All-Paper Print Job Achievement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-misaligned-images-from-w11-printers/"><u>Correct Misaligned Images From W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-efficiency-update-hp-officejet-firmware/"><u>Enhance Printing Efficiency: Update HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-hp-inkjet-on-windows-11-offline/"><u>Unblocking HP Inkjet on Windows 11 Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fully-functional-page-to-page-printer-printing/"><u>Fully Functional, Page-to-Page Printer Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-connectivity-interruptions/"><u>Addressed Connectivity Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-missing-hp-print-drivers-unfound/"><u>Windows Missing: HP Print Drivers Unfound</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-responsive-printer-halted-what-to-do/"><u>Non-Responsive Printer Halted, What to Do?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unavailable-domain-services-prevents-printer-access/"><u>Unavailable Domain Services Prevents Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-hp-printer-not-responding/"><u>How to Fix HP Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-scanner-link-to-computer-post-windows-update/"><u>Restore Scanner Link to Computer Post-Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1087/"><u>Canon MF4770n Driver Update in Windows 10/8/7</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-hobbyist-to-host-mac-sports-channel-creation/"><u>[New] 2024 Approved  From Hobbyist to Host  Mac Sports Channel Creation</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-stellar-background-choices-for-effective-video-conferencing/"><u>[New] 2024 Approved  Stellar Background Choices for Effective Video Conferencing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/craft-professional-episodes-a-comprehensive-guide-to-editing-in-garageband/"><u>Craft Professional Episodes  A Comprehensive Guide to Editing in GarageBand</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-transformative-color-workflow-with-cg-central-luts-for-2024/"><u>[New] Transformative Color Workflow with CG Central LUTs for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unleashing-potential-career-exploration-in-design-for-2024/"><u>[Updated] Unleashing Potential  Career Exploration in Design for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-professionals-choice-ranking-the-top-9-microphone-apps/"><u>[New] 2024 Approved  Professional's Choice  Ranking the Top 9 Microphone Apps</u></a></li>
<li><a href="https://fox-http.techidaily.com/innovation-in-display-tech-top-10-of-4k-displays/"><u>Innovation in Display Tech  #Top 10 of 4K Displays</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selecting-your-next-travel-cinema-device-for-2024/"><u>Selecting Your Next Travel Cinema Device for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-xiaomi-redmi-13c-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Xiaomi Redmi 13C 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-melodicmeasurement-reaction-to-tunes/"><u>2024 Approved  MelodicMeasurement  Reaction to Tunes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-lenovo-thinkphone-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Lenovo ThinkPhone? Try These Fixes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-frame-rates-speed-and-wondershare-filmora/"><u>2024 Approved Frame Rates, Speed, and Wondershare Filmora</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-a79-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo A79 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-iphone-14-pro-max-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On iPhone 14 Pro Max? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://extra-information.techidaily.com/become-a-color-connoisseur-in-digital-photography-for-2024/"><u>Become a Color Connoisseur in Digital Photography for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-winning-strategies-the-best-5-methods-for-game-recording-in-windows-11/"><u>[Updated] Winning Strategies  The Best 5 Methods for Game Recording in Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/er-the-10-best-makeup-experts-on-youtube-you-cant-ignore/"><u>Uncover the 10 Best Makeup Experts on YouTube You Can't Ignore</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-10-premier-igtv-horizontal-video-editors-for-2024/"><u>[New] 10 Premier IGTV Horizontal Video Editors for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/8-innovative-activities-for-enhancing-artistry-and-creativity/"><u>8 Innovative Activities for Enhancing Artistry and Creativity</u></a></li>
<li><a href="https://extra-tips.techidaily.com/acid-pro-overview-plus-best-software-match-ups-for-2024/"><u>ACID Pro Overview + Best Software Match-Ups for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-best-7-practical-cost-free-ways-to-improve-your-digital-vocal-effects/"><u>Updated 2024 Approved Best 7 Practical, Cost-Free Ways to Improve Your Digital Vocal Effects</u></a></li>
<li><a href="https://facebook.techidaily.com/demystifying-profile-naming-and-username-systems/"><u>Demystifying Profile Naming and Username Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-visual-splendor-of-blade-cameras-in-full-hd/"><u>2024 Approved  The Visual Splendor of Blade Cameras in Full HD</u></a></li>
</ul></div>
