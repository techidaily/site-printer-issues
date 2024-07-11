---
title: Swift Jolt to Halted Print Queues
date: 2024-07-10T17:11:21.104Z
updated: 2024-07-11T17:11:21.104Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swift Jolt to Halted Print Queues
excerpt: This Article Describes Swift Jolt to Halted Print Queues
keywords: Halted Print Queue Fix,Stop Stalled Printers Quickly,Print System Disruption Solutions,Immediate Print Queue Resolution,Printer Queue Jolt Troubleshooting,Print Service Interruption Management,Expediting Halted Print Jobs
thumbnail: https://thmb.techidaily.com/70a221261e83ff3179ef93192d51afbff1f7257579ffa960f9e7a085032e4b04.png
---

## Swift Jolt to Halted Print Queues

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
2. In the Command Prompt window, enter the following commands separately:

net stop spooler

del %systemroot%\System32\spool\printers\* /Q **/F /S**

net start spooler

This will clear all of your print jobs stuck in a queue.

#### Option 3: Create a Bat file for permanent use

 If you don’t want to go through all the trouble again, there’s a permanent fix for you to do this. Create your own batch file and you just need to open it every time you want to clear the print queue. Here is how to do it:

1. Open Notepad or Notepad++ (but not a word processor like Microsoft Word.)
2. Enter the following lines:  
 **net stop spooler**  
 **del %systemroot%\\System32\\spool\\printers\* /Q /F /S**  
 **net start spooler**  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

### Fix 2: Reinstall the printer driver

 If your print jobs still get stuck in a queue, the main cause is a wrong or outdated printer driver. So you should update your printer driver to see if it fixes your problem.

 There are two ways to update your printer driver: manually or automatically.

#### Option 1: Install the printer driver manually

 Printer manufacturers such as HP, Canon, Brother, Dell, and Epson keep releasing new printer drivers to fix bugs and improve performance. To get them, you can go to your printer manufacturer’s website (always in the Support or Download section) and download the latest driver and install it manually.

* HP:[HP software and Driver Downloads](https://support.hp.com/us-en/drivers)
* Canon:[Canon Drivers & Downloads](https://www.usa.canon.com/internet/portal/us/home/support/drivers-downloads)
* Brother:[Brother Driver Downloads](https://www.brother-usa.com/brother-support/driver-downloads)
* Dell:[Dell Drivers & Downloads](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fsupport%2Fhome%2Fus%2Fen%2F04%3Fapp%3Ddrivers)
* Epson:[Epson Products & Drivers](https://global.epson.com/products%5Fand%5Fdrivers/)

![](https://images.drivereasy.com/wp-content/uploads/2020/01/kisspng-pixel-illustration-printer-5a983b8a6f6aa4.5830009615199261544564.png)

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
5. Try printing again. Your printer should be working properly now.

---

 Hopefully, your printer can work like a charm now. However, if none of the fixes above solved your printer stuck in a queue, please check the USB or Wireless connection to make sure that your printer is communicating well with your computer or mobile phone.

Feel free to drop us a comment if you have any questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [printer](https://tools.techidaily.com/drivereasy/download/)
* [printer driver](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://printer-issues.techidaily.com/full-colors-unavailable-on-printout/"><u>Full Colors Unavailable on Printout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-printer-back-in-action-on-windows-11/"><u>Get Your Printer Back in Action on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-xp-non-responsive-printer-issue-resolved/"><u>Windows XP: Non-Responsive Printer Issue Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-print-sentry-refuses-responses/"><u>My Print Sentry Refuses Responses</u></a></li>
<li><a href="https://printer-issues.techidaily.com/high-performance-drivers-hp-officejet-pro-8600-for-windows-pcs/"><u>High-Performance Drivers: HP Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-not-printing-solved/"><u>HP Printer Not Printing [SOLVED]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-uncooperative-printer-status-on-winntme-os/"><u>Fixing Uncooperative Printer Status on WinNT/Me OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcame-hp-printers-spooler-error/"><u>Overcame HP Printer's Spooler Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-driver-not-located-by-win/"><u>Printer Error: Driver Not Located by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/directions-assembling-hp-print-with-your-pc/"><u>Directions: Assembling HP Print with Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-due-to-domain-service-outage/"><u>Printer Problem Due to Domain Service Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-noisy-or-disruptive-printers/"><u>Tackling Noisy or Disruptive Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-link-your-laptop-and-hp-printer-with-these-fixes/"><u>Effortlessly Link Your Laptop and HP Printer with These Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-restoration-completed-for-win11/"><u>Scanner Restoration Completed for Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-text-only-paper-the-epson-printer-glitch/"><u>No Text, Only Paper: The Epson Printer Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/duplicate-device-printing-discovered-and-tackled/"><u>Duplicate Device Printing Discovered & Tackled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-networked-printer-issues/"><u>Navigating Through Networked Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-print-job-stuck-in-queue-quickly/"><u>Fix ‘Print Job Stuck in Queue’ Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-driver-compatibility-with-multiple-windows-oses/"><u>HP Deskjet D1360 Driver Compatibility with Multiple Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/professional-setup-guide-win32-officejet-pro-8600-driver-installation/"><u>Professional Setup Guide: Win32 Officejet Pro 8600 Driver Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-color-in-black-and-white-outputs/"><u>No Color in Black and White Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-job-across-all-printers/"><u>Perfect Print Job Across All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-device-management-officejet-pro-8600-drivers-pc-friendly/"><u>Streamlined Device Management: Officejet Pro 8600 Drivers, PC-Friendly</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-samsung-galaxy-a05s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/8-best-daw-for-hip-hop-music-production-for-2024/"><u>8 Best DAW for Hip-Hop Music Production for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/flawless-top-timelapse-capturer/"><u>Flawless Top Timelapse Capturer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-how-to-engage-your-audience-in-live-discord-streams-easily-for-2024/"><u>[New] How to Engage Your Audience in Live Discord Streams Easily for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/instantize-dynamic-images-in-photoshop/"><u>Instantize Dynamic Images in Photoshop</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-video-editing-on-a-mac-here-are-10-fantastic-vegas-pro-alternatives-for-2024/"><u>New Video Editing on a Mac? Here Are 10 Fantastic Vegas Pro Alternatives for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Samsung Galaxy A25 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-find-n3-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Oppo Find N3</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-motorola-edge-2023-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Motorola Edge 2023 Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-infinix-hot-40-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Infinix Hot 40 to Roku | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-finding-the-most-skilled-film-capturers/"><u>[New] Finding the Most Skilled Film Capturers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-acquiring-safe-gratis-vlc-media-player-on-macos-systems/"><u>[Updated] In 2024, Acquiring Safe, Gratis VLC Media Player on macOS Systems</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-dissecting-splitcams-superiority-as-a-recorder/"><u>[New] 2024 Approved  Dissecting SplitCam’s Superiority as a Recorder</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-transformative-pfps-that-define-your-tiktok-identity-for-2024/"><u>[New] Transformative PFPs that Define Your TikTok Identity for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/smooth-installation-of-lenovo-g580-drivers/"><u>Smooth Installation of Lenovo G580 Drivers</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-how-to-dominate-the-viral-video-edit-scene-on-tiktok-for-2024/"><u>[New] How to Dominate the Viral Video Edit Scene on TikTok for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-professional-font-creation-solutions-for-discord-enthusiasts-for-2024/"><u>[Updated] Professional Font Creation Solutions for Discord Enthusiasts for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-itel-a60s-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Itel A60s to New Android? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-animate-for-free-top-12-options-for-windows-and-mac-users-for-2024/"><u>New Animate for Free Top 12 Options for Windows and Mac Users for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-essential-audacity-manual-for-mac-audio-capture-for-2024/"><u>[New] The Essential Audacity Manual for Mac Audio Capture for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-to-webm-the-10-best-youtube-to-webm-converters/"><u>[Updated] YouTube to WebM  The 10 Best YouTube to WebM Converters</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-elevate-your-videos-best-3d-animation-and-video-software/"><u>2024 Approved Elevate Your Videos Best 3D Animation and Video Software</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-silencing-the-singers-10-high-quality-audio-programs-to-minimize-vocal-interference-in-studio-setups/"><u>New 2024 Approved Silencing the Singers 10 High-Quality Audio Programs to Minimize Vocal Interference in Studio Setups</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-motorola-moto-g24-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Motorola Moto G24 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-enhance-video-subtitles-with-these-essential-online-resources-and-apps-for-2024/"><u>[Updated] Enhance Video Subtitles with These Essential Online Resources & Apps for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-androids-gaming-revolution-experience-the-power-of-kinemaster-app/"><u>In 2024, Android's Gaming Revolution  Experience the Power of KineMaster App</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-the-perfect-thumbnail-top-9-budget-friendly-tools/"><u>Craft the Perfect Thumbnail  Top 9 Budget-Friendly Tools</u></a></li>
</ul></div>
