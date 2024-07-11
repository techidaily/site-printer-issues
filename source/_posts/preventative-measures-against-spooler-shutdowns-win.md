---
title: Preventative Measures Against Spooler Shutdowns (Win)
date: 2024-07-10T17:16:40.670Z
updated: 2024-07-11T17:16:40.670Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Preventative Measures Against Spooler Shutdowns (Win)
excerpt: This Article Describes Preventative Measures Against Spooler Shutdowns (Win)
keywords: Preventative Measures Against Spooler Shutdowns,Windows System Preventive Tips,Avoiding Spooler Crashes on Windows,Tips for Stable Windows Print Service,How to Prevent Windows Printer Errors,Spooler Error Mitigation Techniques (Windows),Preventing Spooler Issues in Windows OS
thumbnail: https://thmb.techidaily.com/f61e0cf06b5f94c52331e7280bfea34d0fc7a11feee31daa0334519a989e1892.jpg
---

## Preventative Measures Against Spooler Shutdowns (Win)

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
<li><a href="https://printer-issues.techidaily.com/easy-install-mfc-9330cdw-driver-download/"><u>Easy Install: MFC-9330CDW Driver Download</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setup-no-complications-found/"><u>Print Setup: No Complications Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-mp620-not-recognized-by-windows/"><u>[Update Required] MP620 Not Recognized by Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-scanner-issue-on-windows-11/"><u>Resolving Scanner Issue on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-error-now-working/"><u>Epson Printer Error, Now Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-established-printer-connections/"><u>Success: Established Printer Connections</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-canons-print-to-wi-fi-journey/"><u>Navigating Canon's Print to Wi-Fi Journey</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-offline-issue-on-windows-7/"><u>[Fixed] Printer Offline Issue on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-unblocked-scan-functionality/"><u>Windows 11: Unblocked Scan Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-printer-woes-with-windows-10-update-fix/"><u>Triumph Over Printer Woes with Windows 10 Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/foreign-processors-print-job-revealed/"><u>Foreign Processor's Print Job Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-no-9008e/"><u>Resolved: Printer Error No. 9008E</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574049626-fix-print-job-stuck-in-queue-quickly/"><u>Fix 'Print Job Stuck in Queue' Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1087/"><u>Canon MF4770n Driver Update in Windows 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recommendations-for-reactivating-hp-print-headless-systems/"><u>Recommendations for Reactivating HP Print Headless Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-ink-and-paper-feed-issues-in-hp/"><u>Diagnosing Ink and Paper Feed Issues in HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tailored-updates-mf4770n-for-windows-oses/"><u>Tailored Updates: MF4770n for WIndows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-usb-printers-ignoring-command-in-windows-7-mode/"><u>[Fix] USB Printers Ignoring Command in Windows 7 Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-output-v305-aio-driver-enhancement-in-win7/"><u>Boost Your Output: V305 AIO Driver Enhancement in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-correction-b200/"><u>Canon Correction: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-manage-hp-officejet-4630-updates/"><u>Efficiently Manage HP Officejet 4630 Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/syncing-up-hp-printer-with-pc-settings/"><u>Syncing Up HP Printer with PC Settings</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-poco-x5-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Poco X5 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/superior-lineup-elite-webcam-mounts/"><u>Superior Lineup  Elite Webcam Mounts</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-vivo-y100-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Vivo Y100 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/live-chat-with-woocommerce-leading-into-the-live-selling-world/"><u>Live Chat With WooCommerce Leading Into the Live Selling World</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-y200-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-asus-rog-phone-8-pro-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-end-credits-maker-the-1-video-closers-guide/"><u>[New] In 2024, Free End Credits Maker - The #1 Video Closers Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premier-podcasts-on-googles-platform/"><u>[New] Premier Podcasts on Google's Platform</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-iphone-15-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On iPhone 15 If Youve Tried Everything</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-frugal-filmmakers-guide-to-affordable-camera-gear/"><u>The Frugal Filmmaker's Guide to Affordable Camera Gear</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-ultimate-voice-transformation-handbook-for-gamers-for-2024/"><u>The Ultimate Voice Transformation Handbook for Gamers for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-guide-on-google-podcast-upload/"><u>Ultimate Guide on Google Podcast Upload</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steady-your-screen-fix-flicker-in-windows-7/"><u>Steady Your Screen: Fix Flicker in Windows 7</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-iphoneandroid-screen-capture-for-google-meet-participants/"><u>2024 Approved  IPhone/Android Screen Capture for Google Meet Participants</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-essence-of-the-apple-m1-a-technological-marvel/"><u>In 2024, The Essence of the Apple M1  A Technological Marvel</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-integrated-video-workflows-on-ios/"><u>[Updated] Integrated Video Workflows on iOS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-glow-up-guide-for-the-social-savvy-top-three-highlighters-on-instagram/"><u>[New] Glow-Up Guide for the Social Savvy  Top Three Highlighters on Instagram</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/how-to-fade-inout-audio-with-keyframes-in-filmora-for-mac-for-2024/"><u>How to Fade In/Out Audio with Keyframes in Filmora for Mac for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-infinix-hot-40-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Infinix Hot 40 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-optimal-speech-devices-web-based-for-2024/"><u>[New] Optimal Speech Devices, Web-Based for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-navigating-webcam-features-on-apples-macbook/"><u>[New] In 2024, Navigating Webcam Features on Apple's MacBook</u></a></li>
</ul></div>
