---
title: Quick Remedies for Recurring Printer Errors on Windows Systems
date: 2024-07-10T17:05:18.961Z
updated: 2024-07-11T17:05:18.961Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Remedies for Recurring Printer Errors on Windows Systems
excerpt: This Article Describes Quick Remedies for Recurring Printer Errors on Windows Systems
keywords: Quick Fixes (Related Concept),Printer Errors (Specific Problem),Recurring Issues (Problem Frequency),Windows Systems (Target Operating System),Solutions for Printing (Solution Aspect),Troubleshooting Printers (Method of Solving Problems),Fix Printer Problems (Action-Oriented Phrasing),Quick Fixes,Printer Errors,Recurring Issues,Windows Systems,Solutions for Printing,Troubleshooting Printers,Fix Printer Problems
thumbnail: https://thmb.techidaily.com/0d94a1daa7c27cd73a9d8298e21e0d777d1adaffd7b41de949895538a87e46dd.jpg
---

## Quick Remedies for Recurring Printer Errors on Windows Systems

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
<li><a href="https://printer-issues.techidaily.com/deactivate-stalled-print-job-queue-fastly/"><u>Deactivate Stalled Print Job Queue Fastly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-printer-isolation-brothers-network-recovery-plan/"><u>Avoiding Printer Isolation: Brother's Network Recovery Plan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-ink-cartridge-error/"><u>Tackled Ink Cartridge Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-windows-710-to-online-hp-printer/"><u>Reconnect Windows 7/10 to Online HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-offline-hp-printer-woes/"><u>Overcoming Offline HP Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-connectivity-interruptions/"><u>Addressed Connectivity Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drivers-canon-mp620-not-found-on-11th-edition-windows/"><u>[Drivers] Canon MP620 Not Found on 11Th Edition Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-access-to-domain-services-printer-not-responding/"><u>No Access To Domain Services, Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alleviated-printer-network-disconnect/"><u>Alleviated Printer Network Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-cartridge-replacement-failures/"><u>Troubleshooting Cartridge Replacement Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-siblings-printer-remains-unreachable/"><u>Fixing: Sibling's Printer Remains Unreachable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-unable-to-install-printeroperation-could-not-be-completed/"><u>[Solved] Unable to Install Printer.Operation Could Not Be Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573890689-canon-printer-woes-here-are-your-five-easy-fixes-in-windows-11/"><u>Canon Printer Woes? Here Are Your Five Easy Fixes in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-mend-printer-queue-errors-on-windows-pcs/"><u>How to Mend Printer Queue Errors on Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-velocity-now/"><u>Enhance Printer Velocity Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-pcl-xl-faults-instantly/"><u>Overcoming PCL XL Faults Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/search-unsuccessful-for-windows-printer-driver/"><u>Search Unsuccessful for Windows Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-11-printer-power-reset-issues/"><u>Fix Windows 11 Printer Power Reset Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024-update-printers-prints-every-page/"><u>2024 Update: Printers Prints Every Page</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-root-cause-of-frequent-printer-service-halt-win/"><u>Finding the Root Cause of Frequent Printer Service Halt (Win)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-functionality-upgrading-mf4770n-on-w11w8w7-os/"><u>Optimize Functionality: Upgrading MF4770n on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-all-in-one-printers-connectivity-armored-up/"><u>HP All-in-One Printer's Connectivity Armored Up</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-top-fixes-to-bridge-hp-printers-with-laptop-effortlessly/"><u>3 Top Fixes to Bridge HP Printers with Laptop Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/acancel-free-setup-for-wi-fi-connected-printers/"><u>Acancel-Free Setup for Wi-Fi Connected Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-pcl-xl-complications-swiftly/"><u>Navigating PCL XL Complications Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-without-hurdles-for-printer/"><u>Installation Without Hurdles for Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turbo-charge-your-print-operations/"><u>Turbo-Charge Your Print Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quicken-your-print-jobs-easily/"><u>Quicken Your Print Jobs Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/securely-link-disconnected-printer-quickly/"><u>Securely Link Disconnected Printer Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-non-responsive-printer-in-windows-11/"><u>Resolve Non-Responsive Printer in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-scanner-no-longer-offline/"><u>Windows 11: Scanner No Longer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-permissions-violation-by-hidden-system/"><u>Printer Permissions Violation by Hidden System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-win10-printer-functionality/"><u>Streamline WIN10 Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-paper-trail-issue-error-0x00000709-solution-found/"><u>Windows Paper Trail Issue - Error 0X00000709 Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-craft-professional-looking-video-invites-with-these-iphone-and-android-apps/"><u>New In 2024, Craft Professional-Looking Video Invites with These iPhone and Android Apps</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>Fake the Location to Get Around the MLB Blackouts on Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-mac-software-for-optimal-dvd-burning/"><u>[New] Navigating Mac Software for Optimal DVD Burning</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nokia-c210-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nokia C210</u></a></li>
<li><a href="https://article-posts.techidaily.com/why-does-my-photo-booth-video-keep-freezing-in-2024/"><u>Why Does My Photo Booth Video Keep Freezing, In 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/achieve-mastery-in-tracking-fbs-recently-seen-videos/"><u>Achieve Mastery in Tracking Fb’s Recently Seen Videos</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/create-cartoon-characters-from-your-photos-for-2024/"><u>Create Cartoon Characters From Your Photos for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-learn-how-to-make-your-csgo-montage-impressive/"><u>New In 2024, Learn How to Make Your CSGO Montage Impressive</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fine-tuning-fade-effects-in-music-software/"><u>2024 Approved  Fine-Tuning Fade Effects in Music Software</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-the-complete-beginners-guide-to-voice-recording-on-your-computer-with-audacity/"><u>Updated 2024 Approved The Complete Beginners Guide to Voice Recording on Your Computer with Audacity</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-se-2020-drfone-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-integrating-zoom-into-your-daily-schedule-for-2024/"><u>[New] Integrating Zoom Into Your Daily Schedule for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/gaming-on-a-budget-top-10-free-game-download-platforms-for-pc-and-android-for-2024/"><u>Gaming on a Budget Top 10 Free Game Download Platforms for PC and Android for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-android-games-funimate-pro-apk-deep-dive-for-2024/"><u>Unlock Android Games - Funimate Pro APK Deep Dive for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pro-tip-unveiling-the-best-10-free-image-vaults/"><u>[New] Pro Tip  Unveiling the Best 10 Free Image Vaults</u></a></li>
<li><a href="https://video-capture.techidaily.com/1716069811180-new-in-2024-capturing-screen-content-via-built-in-recorders-in-the-mate-and-p-series/"><u>[New] In 2024, Capturing Screen Content via Built-In Recorders in the Mate and P Series.</u></a></li>
</ul></div>
