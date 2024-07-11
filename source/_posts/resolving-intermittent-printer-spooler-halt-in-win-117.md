---
title: Resolving Intermittent Printer Spooler Halt in Win 11/7
date: 2024-07-10T17:03:27.960Z
updated: 2024-07-11T17:03:27.960Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolving Intermittent Printer Spooler Halt in Win 11/7
excerpt: This Article Describes Resolving Intermittent Printer Spooler Halt in Win 11/7
keywords: Win 11 Printer Spooler Issue,Intermittent Printing Error Fix,Win 7 Printer Spooler Solution,Resolve Print Queue Halt,Troubleshooting Spooler Problems,Printer Driver Update Tips,Automatic Print Spooler Repair (Win 11/7)
thumbnail: https://thmb.techidaily.com/3d0b2d16ee1d6e6a1474c3b5739a00253bf279f4294e6c37548bb9b82e10821e.jpg
---

## Resolving Intermittent Printer Spooler Halt in Win 11/7

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
<li><a href="https://printer-issues.techidaily.com/printer-fault-ad-services-out-of-service/"><u>Printer Fault: AD Services Out of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-that-can-handle-full-document-sizes/"><u>Printers That Can Handle Full Document Sizes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-fault-resolutions/"><u>Mastering Printer Fault Resolutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-speed-and-accuracy-on-windows-11/"><u>Fix Printing Speed and Accuracy on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-print-service-not-starting-correctly/"><u>[WARNING] Print Service Not Starting Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-resumption-of-prints/"><u>Immediate Resumption of Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/foreign-system-flagged-for-misused-printer/"><u>Foreign System Flagged for Misused Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-spooler-failures-on-windows-7-10-and-11/"><u>Overcoming Spooler Failures on Windows 7, 10 & 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-intermittent-printing-on-hp-deskjet-305dn/"><u>Fixed Intermittent Printing on HP DeskJet 305Dn</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-post-upgrade-success-story/"><u>Printer Problem Post Upgrade: Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-searching-for-missing-windows-driver/"><u>MP620 Printer: Searching for Missing Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-assembly-combining-hp-printer-model-with-computer/"><u>Technical Assembly: Combining HP Printer Model with Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-driver-update-win32-officejet-pro-8600-utility-bundle/"><u>Streamlined Driver Update: Win32 Officejet Pro 8600 Utility Bundle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-issue-unable-to-get-hp-d1360-up-and-running-in-windows-8-10/"><u>[Installation Issue] Unable to Get HP D1360 Up and Running in Windows 8-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplify-print-setup-wi-fi-connection-for-canon/"><u>Simplify Print Setup: Wi-Fi Connection for Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-inaccessible-for-windows-print/"><u>Driver Inaccessible for Windows Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-removal-from-printer-job-backlog/"><u>Rapid Removal From Printer Job Backlog</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt98-restore-efficient-printer-responsiveness/"><u>WinNT/98: Restore Efficient Printer Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-restoration-of-active-print-queue/"><u>Quick Restoration of Active Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-uncooperative-printer-status-on-winntme-os/"><u>Fixing Uncooperative Printer Status on WinNT/Me OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-connect-protocol-printer-online/"><u>Quick Connect Protocol: Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-access-to-hp-printer-driver-on-win1110/"><u>No Access to HP Printer Driver on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-error-code-oxc4eb827f/"><u>Overcoming HP Printer Error Code: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-fixes-five-steps-to-ensure-your-canon-works-in-windows-11/"><u>Quick Printer Fixes: Five Steps to Ensure Your Canon Works in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-unleashing-creativity-how-to-start-live-on-tiktok-via-computer/"><u>[New] Unleashing Creativity  How to Start Live on TikTok Via Computer</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-uncomplicated-video-snip-for-win10-users/"><u>[Updated] In 2024, Uncomplicated Video Snip for Win10 Users</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-looking-for-the-different-ar-video-effects-to-include-in-your-film-check-out-this-article-for-the-best-10-augmented-reality-effects-and-the-fun-ar-e/"><u>In 2024, Looking for the Different Ar Video Effects to Include in Your Film? Check Out This Article for the Best 10 Augmented Reality Effects and the Fun Ar Effects in Filmora</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-12-pro-max-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-top-20-creative-snapchat-lens-ideas-for-unique-shots/"><u>In 2024, Top 20 Creative Snapchat Lens Ideas for Unique Shots</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-discover-the-best-musically-focused-bots-on-discord-platforms/"><u>[Updated] 2024 Approved  Discover the Best Musically-Focused Bots on Discord Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-glitch-video-editing-software-for-windows-and-mac-users/"><u>New In 2024, Top Glitch Video Editing Software for Windows and Mac Users</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-ultimate-guide-to-free-avi-video-rotators-top-5-for-2024/"><u>New The Ultimate Guide to Free AVI Video Rotators Top 5 for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-unlocking-iphone-x-ease-mending-face-id-problems/"><u>[Updated] Unlocking iPhone X Ease  Mending Face ID Problems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-itel-p40plus-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Itel P40+ Lock Screen Password?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-infinix-note-30-vip-by-fonelab-android-recover-music/"><u>How to recover old music from your Infinix Note 30 VIP</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-the-ultimate-guide-for-emoji-laden-discord-statements/"><u>[New] 2024 Approved  The Ultimate Guide for Emoji-Laden Discord Statements</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensible-guide-for-novices-crafting-professional-tiktok-edits/"><u>[Updated] Comprehensible Guide for Novices  Crafting Professional TikTok Edits</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-lenovos-functional-touch-screens/"><u>Restoring Lenovo's Functional Touch Screens</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-elite-10-sound-recording-essentials-on-spotify-platform/"><u>[New] 2024 Approved  Elite 10 Sound Recording Essentials on Spotify Platform</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-chromebooks-premium-free-video-capture-extensions/"><u>[New] 2024 Approved  Chromebook's Premium Free Video Capture Extensions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-advanced-techniques-for-proximity-viewing-in-roblox/"><u>In 2024, Advanced Techniques for Proximity Viewing in Roblox</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expertly-manipulating-colors-in-video-edits/"><u>[Updated] Expertly Manipulating Colors in Video Edits</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-optimal-pc-mac-screen-recording-software/"><u>2024 Approved  Optimal PC-Mac Screen Recording Software</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-top-10-best-offline-ios-games-you-should-try/"><u>[Updated] In 2024, Top 10 Best Offline iOS Games You Should Try</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oppo-a1x-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A1x 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-money-trail-exploring-mr-beasts-path/"><u>In 2024, The Money Trail  Exploring Mr. Beast's Path</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-quiet-quality-of-comfort-asmr-expert-choices/"><u>2024 Approved  The Quiet Quality of Comfort  ASMR Expert Choices</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-simplified-audio-voice-customization-methods-description-standards-and-variants/"><u>New In 2024, Simplified Audio Voice Customization Methods Description, Standards, and Variants</u></a></li>
</ul></div>
