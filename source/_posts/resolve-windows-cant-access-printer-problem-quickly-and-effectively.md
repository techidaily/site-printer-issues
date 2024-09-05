---
title: Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
date: 2024-09-04T06:17:47.432Z
updated: 2024-09-05T06:17:47.432Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
excerpt: This Article Describes Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
thumbnail: https://thmb.techidaily.com/e4e90e7c9acadc523d8e4202425b18a9d8056d3f1cd618361a73d2cd13f94e4f.jpg
---

## Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively

When you are trying to add a network shared printer, if you receive message “Windows cannot connect to the printer.”(commonly occur to Windows 7), you must be very frustrated. But don’t worry. You can use solutions in this post to fix the problem. Each solution has been reported to be useful. So try all of them until you have the problem fixed. 

 The error would appear with a specific error code like 0x0000007e. The most common error codes are as follows:

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59226592e8079.jpg) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x0000007e_ 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592265c744f96.png) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x00000002_ 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59226608a5031.jpg) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x0000007a_ 

[**Solution 1: Restart Print Spooler Service**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 2: Create a New Local Port**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 3: Delete Printer Drivers**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 4: Copy “mscms.dll” Manually**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 5: Delete a Subkey**](https://tools.techidaily.com/drivereasy/download/) 

##   **Solution 1: Restart Print Spooler Service** 

Follow steps below to stop Print Spooler service then start it again.

 1\. Press**Win+R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 2\. Type **services.msc** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592282c0cbfe5.png) 

 3\. In the**Name** list, locate and double-click on service **Print Spooler** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592282f40baaf.jpg) 

 3\. Under Service status, click**Stop** button. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228346254fb.png) 

 4\. Click**Start** button to start the service again.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922837fce75a.png) 

 5\. Click**OK** button.

 After that, add the printer again and see if the problem persists.

 ##  Solution 2: Create a New Local Port

Follow these steps:

 1\. Open[Control Panel](https://tools.techidaily.com/drivereasy/download/) .

 2\. View by Large icons, click**Devices and Printers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592284396a5e3.jpg) 

 3\. Click**Add a printer** at the top of the window.**Note:** To continue, you need to login to the computer as an administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592284c312e63.jpg) 

 4\. Select**Add a network, wireless or Bluetooth printer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592285527f2ca.jpg) 

 5\. Select**Create a new port** , change the “Type of port” to**Local Port** then click**Next** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922878323a31.jpg) 

 6.**Enter a port name** in the box. The port name is the printer’s address. The address format is **\\\\IP address or the Computer Name\\Printer’s Name** (refer to the following screen). Then click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228a6291554.png) 

 7\. Select the**printer model** from the directory and click**Next** button. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228e9593ce0.jpg) 

8\. Follow the rest on-screen instructions to finish adding the printer.

 ##   **Solution 3: Delete Printer Drivers** 

 The problem can be caused by printer drivers. So you can try to remove the drivers and install them again.

Follow steps below:

 1\. Press**Win+R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 2\. Type **printmanagement.msc** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228fef1fe19.png) 

 3\. In the left pane, click**All Drivers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59229062a2cbc.jpg) 

 4\. In the right pane, right-click on the printer driver and click**Delete** on the pop-up menu. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592290cca70ff.jpg) 

 If you see more than one printer driver names, repeat steps above to remove them one by one.

5\. Add the printer again. 

 If the problem persists, you may want to install the driver manually. You can download and install the driver from the printer manufacturer’s website. 

 If you have difficulty downloading the driver manually, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to help you. Driver Easy can scan your computer to detect all problem drivers then provide you with new drivers instantly. **[Download its Free version to have a try](https://tools.techidaily.com/drivereasy/download/)**  . If you find it helpful, you can consider upgrading to the Pro version. The Pro version allows you to update all drivers with just one-click.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592292ec90631.png) 

 ##  Solution 4: Copy “mscms.dll” Manually

 1\. Open**C:\\Windows\\system32** and find the file “**mscms.dll** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592294768b3e2.jpg) 

2\. Copy the file to the following path:

 **C:\\windows\\system32\\spool\\drivers\\x64\\3\\ if you are using 64-bit windows**   
 **C:\\windows\\system32\\spool\\drivers\\w32x86\\3\\ if you are using 32-bit windows** 

 If you have no idea which version of Windows you are using, see[How to Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) .

3\. Try to connect to the printer again.

 ##  Solution 5: Delete a Subkey

 Modifying registry keys incorrectly may cause serious system problems. So before you get started, it is recommended that you[back up the registry key](https://tools.techidaily.com/drivereasy/download/) so you can restore it in case any problems occurs.

 1\. Stop **Print Spooler** service. (refer steps in Solution 1 to stop the service)

 2\. Press**Win + R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 3\. Type **regedit** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922973c415cc.png) 

 4\. Expand   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows NT\\CurrentVersion\\Print\\Providers\\Client Side Rendering Print Provider** . Right-click on **Client Side Rendering Print Provider** and select**Delete.** 

5\. Start the Print Spooler service.

6\. Reboot your computer and try to add the printer again.

 Hope the solutions here will help you fix the printer not connecting issue.

* [printers](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-radiant-reels-elevate-your-visuals-with-3-insta-tactics/"><u>[New] 2024 Approved  Radiant Reels  Elevate Your Visuals with 3 Insta Tactics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-clearer-anonymity-discreet-faces-deletion/"><u>[New] Clearer Anonymity  Discreet Faces Deletion</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-cost-efficient-guide-to-skype-calls-in-mp3/"><u>[New] In 2024, The Cost-Efficient Guide to Skype Calls in MP3</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-ustream-evaluation-find-alternates/"><u>[New] Ustream Evaluation, Find Alternates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-driver-is-unavailable-on-windows/"><u>[SOLVED] Printer Driver Is Unavailable on Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-pro-editors-insight-restore-true-colors-to-faded-iphone-hdr-in-adobe-premiere-for-2024/"><u>[Updated] [Pro Editor's Insight] Restore True Colors to Faded iPhone HDR in Adobe Premiere for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-best-6-modern-homes-for-minecraft-enthusiasts/"><u>[Updated] 2024 Approved  Best 6 Modern Homes for Minecraft Enthusiasts</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-srt-to-subconvert-the-ultimate-guide/"><u>[Updated] 2024 Approved  SRT to SUBCONVERT  The Ultimate Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-your-world-transformed-youtubes-immersive-vr-collection/"><u>[Updated] 2024 Approved  Your World Transformed  Youtube's Immersive VR Collection</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-crafting-impressive-videos-with-the-best-methods-for-obs-studio/"><u>[Updated] Crafting Impressive Videos with the Best Methods for OBS Studio</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-hideous-heroes-black-vs-gleaming-guardians-silver-for-2024/"><u>[Updated] Hideous Heroes (Black) VS Gleaming Guardians (Silver) for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ios-gamers-top-5-ps2-emulators-unveiled-for-2024/"><u>[Updated] IOS Gamers' Top 5 PS2 Emulators Unveiled for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-streamline-video-editing-in-windows-10-photos-using-story-remix/"><u>[Updated] Streamline Video Editing in Windows 10 Photos Using Story Remix</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-the-best-mobile-tools-to-pull-videos-from-youtube/"><u>[Updated] Unveiling the Best Mobile Tools to Pull Videos From YouTube</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-nokia-c110-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Nokia C110 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-11/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 11</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-10-digital-landscape-replacers-for-videos/"><u>Best 10 Digital Landscape Replacers for Videos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-repeated-printer-errors-in-windows-107-environments/"><u>Curing Repeated Printer Errors in Windows 10/7 Environments</u></a></li>
<li><a href="https://tech-haven.techidaily.com/does-chatgpt-improve-through-interactions-with-users/"><u>Does ChatGPT Improve Through Interactions With Users?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-updates-for-hp-officejet-pro-8720-on-windows-complete-guide/"><u>Download and Install Updates for HP OfficeJet Pro 8720 on Windows: Complete Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-setup-for-a-brand-new-canon-printer/"><u>Effortless Setup for a Brand-New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanner-activation-after-updating-win10/"><u>Enable Scanner Activation After Updating Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-easy-wi-fi-connectivity-for-canon/"><u>Enabling Easy Wi-Fi Connectivity for Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/erase-print-task-queue-pause/"><u>Erase Print Task Queue Pause</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-risks-utilizing-chatgpt-for-crafting-cyber-threats/"><u>Exploring the Risks: Utilizing ChatGPT for Crafting Cyber Threats</u></a></li>
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-configuration-error/"><u>Gear Up Glitch: Printer Configuration Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-reconfigured-wrongly/"><u>Gear-Up Glitch: Printer Reconfigured Wrongly?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-maintain-your-powertoys-setup-during-system-upgrade/"><u>Guide to Maintain Your PowerToys Setup During System Upgrade</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-the-issue-when-football-manager-2023-stays-at-loading-game-screen/"><u>How to Fix the Issue When Football Manager 2023 Stays at 'Loading Game' Screen</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-resumption-of-prints/"><u>Immediate Resumption of Prints</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-the-iphone-14-plus-icloud-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing the iPhone 14 Plus iCloud Lock</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-s24plus-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy S24+ to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-screenstream-worldwide-live-including-exclusive-locals/"><u>In 2024, ScreenStream  Worldwide Live, Including Exclusive Locals</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-without-hurdles-for-printer/"><u>Installation Without Hurdles for Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructive-blueprint-attaching-hp-printer-8720-to-windows-system/"><u>Instructive Blueprint: Attaching HP Printer 8720 to Windows System</u></a></li>
<li><a href="https://tech-hub.techidaily.com/learning-healthy-recipes-can-ai-assistants-like-chatgpt-help/"><u>Learning Healthy Recipes: Can AI Assistants Like ChatGPT Help?</u></a></li>
<li><a href="https://extra-information.techidaily.com/master-the-art-of-freezing-out-the-backdrop-in-your-design/"><u>Master the Art of Freezing Out the Backdrop in Your Design</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-error/"><u>Mended Printer Network Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-pcl-xl-errors-with-ease/"><u>Navigating Through PCL XL Errors with Ease</u></a></li>
<li><a href="https://app-tips.techidaily.com/play-ogg-format-files-at-no-cost-best-cross-platform-ogg-players-for-windows-and-macos/"><u>Play OGG Format Files at No Cost: Best Cross-Platform OGG Players for Windows & macOS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prevent-windows-10-printer-malfunctions-and-fails/"><u>Prevent Windows 10 Printer Malfunctions and Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connected-problems-resolved-quickly/"><u>Printer Connected, Problems Resolved Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-successfully/"><u>Printer Setup Completed Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-hp-printer-error-code-oxc4eb827f/"><u>Purging HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-recovery-from-common-pcl-xl-failures/"><u>Rapid Recovery From Common PCL XL Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapidly-reconnecting-to-your-printer/"><u>Rapidly Reconnecting to Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-printer-error-after-windows-11-update/"><u>Repaired: Printer Error After Windows 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restarting-non-functional-usb-devices-post-sleep-windows-7/"><u>Restarting Non-Functional USB Devices Post Sleep, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-connected-status-for-offline-hp-laserjet/"><u>Restore Connected Status for Offline HP Laserjet</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-guide-adding-hp-printer-officejet-pro-to-pc-network/"><u>Setup Guide: Adding HP Printer (Officejet Pro) to PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smoothed-out-printer-connection-hurdles/"><u>Smoothed Out Printer Connection Hurdles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solidify-printing-integrity-fixing-issues-on-win10/"><u>Solidify Printing Integrity, Fixing Issues on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-connectivity-disconnection/"><u>Solved Connectivity Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-hp-printer-oxc4eb827f-fatality-problem/"><u>Solving HP Printer OXC4EB827F Fatality Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-functionality-with-mf4770n-driver-upgrade-for-windows-11w8w7/"><u>Streamline Functionality with MF4770n Driver Upgrade for Windows 11/W8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-journey-from-void-papers-to-valuable-outputs/"><u>The Journey From Void Papers to Valuable Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/transform-printing-experience-hp-officejets-newest-software-update/"><u>Transform Printing Experience: HP Officejet's Newest Software Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-textless-printouts-on-my-epson-scannerprinter/"><u>Trouble with Textless Printouts on My Epson Scanner/Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-brother-printer-on-your-network/"><u>Troubleshooting Offline Brother Printer on Your Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-loss-of-printers-internet-connection/"><u>Troubleshooting: Loss of Printer's Internet Connection</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-s17-pro-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Vivo S17 Pro Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secret-behind-empty-printouts/"><u>Unveiling the Secret Behind Empty Printouts</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-mp4-made-easy-10-best-webm-to-mp4-conversion-tools/"><u>Updated 2024 Approved MP4 Made Easy 10 Best WebM to MP4 Conversion Tools</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-speed-up-your-storytelling-time-lapse-video-editing-in-final-cut-pro-for-2024/"><u>Updated Speed Up Your Storytelling Time Lapse Video Editing in Final Cut Pro for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/warriors-epic-valhallas-endgame/"><u>Warriors' Epic  Valhalla's Endgame</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->