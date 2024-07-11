---
title: Immediate Fixes for Non-Responsive Printer Service (Windows)
date: 2024-07-10T17:29:27.992Z
updated: 2024-07-11T17:29:27.992Z
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
<li><a href="https://printer-issues.techidaily.com/purging-unnecessary-printers-in-os/"><u>Purging Unnecessary Printers in OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-integration-update-mf4770n-drivers-on-w11w8w7-os/"><u>Smooth Integration: Update MF4770n Drivers on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-intermittent-printing-on-hp-deskjet-305dn/"><u>Fixed Intermittent Printing on HP DeskJet 305Dn</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574110556-printing-woes-config-error-help-needed/"><u>Printing Woes: Config Error, Help Needed!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-brother-printer-print-failures-on-windows-systems/"><u>Overcome Brother Printer Print Failures on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-over-printing-white-paper/"><u>Epson Photo Printer: Over-Printing White Paper</u></a></li>
<li><a href="https://printer-issues.techidaily.com/foreign-processors-print-job-revealed/"><u>Foreign Processor's Print Job Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-printer-status-bring-back-your-brothers-printer/"><u>Reclaiming Printer Status: Bring Back Your Brother's Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-missing-driver-in-os/"><u>[PRINTER PROBLEM] Missing Driver in OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unlisted-solutions-for-windows-xp-11/"><u>Printer Unlisted: Solutions for Windows XP-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-out-of-service/"><u>Fixed Epson Out Of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-d1360-printer-drivers-not-working-on-windows-7-10/"><u>[Fix] D1360 Printer Drivers Not Working on Windows 7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-driver-not-detected-by-os/"><u>HP Printer Setup Error: Driver Not Detected by OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-overcoming-post-upgrade-prints/"><u>Successfully Overcoming Post-Upgrade Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-connect-unplugged-printer-fixed/"><u>Quick Connect: Unplugged Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-simple-fixes-for-the-future-of-printing-with-laptops-all-in-one-guide/"><u>3 Simple Fixes for the Future of Printing with Laptops - All In One Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-network-disconnectivity-in-hp-printers/"><u>Solving Network Disconnectivity in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-error-on-windows-fixed/"><u>Printer Not Responding Error on Windows Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-enhancement-mf4770n-software-upgrade-windows/"><u>System Enhancement: MF4770n Software Upgrade WIndows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/iconic-imagery-stories-a-peek-inside/"><u>Iconic Imagery Stories  A Peek Inside</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-spawn-a-shared-chuckle/"><u>[Updated] Spawn a Shared Chuckle</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevating-video-view-count-top-hashtag-trends-guide/"><u>2024 Approved  Elevating Video View Count  Top Hashtag Trends Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-notes-navigated-steps-for-sound-submissions-to-youtube/"><u>In 2024, Notes Navigated  Steps for Sound Submissions to YouTube</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-the-most-influential-quotes-list-to-make-your-tiktok-videos-shine/"><u>[Updated] 2024 Approved  The Most Influential Quotes List to Make Your TikTok Videos Shine</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-poco-c51-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Poco C51 Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-elite-collection-the-best-11-streamers-for-2024/"><u>[New] Elite Collection  The Best 11 Streamers for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-on-iphone-se-2020-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out On iPhone SE (2020) How to Bypass?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-navigating-to-horror-film-soundscape-pieces/"><u>Updated In 2024, Navigating to Horror Film Soundscape Pieces</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-discover-the-best-in-class-our-list-of-12-high-performing-flip-cameras/"><u>[New] 2024 Approved  Discover the Best in Class  Our List of 12 High-Performing Flip Cameras</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-compreenas-guide-to-choosing-ideal-lenses-for-filmmaking/"><u>A Compreenas Guide to Choosing Ideal Lenses for Filmmaking</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-advanced-techniques-for-screen-recorders-in-video-games/"><u>[New] 2024 Approved  Advanced Techniques for Screen Recorders in Video Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-amateur-vlogs-to-professional-gopro-cinematography-excellence/"><u>2024 Approved  From Amateur Vlogs to Professional GoPro Cinematography Excellence</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-tips-for-capturing-whatsapp-chat-calls-methods-and-techniques/"><u>In 2024, Tips for Capturing WhatsApp Chat Calls  Methods & Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-from-novice-to-pro-your-roadmap-to-crafting-engaging-fb-stories/"><u>[New] From Novice to Pro  Your Roadmap to Crafting Engaging FB Stories</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-how-to-record-hulu-on-all-platforms-winmacmobile/"><u>In 2024, How To Record Hulu On All Platforms - Win/Mac/Mobile</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-iphone-15-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on iPhone 15</u></a></li>
</ul></div>
