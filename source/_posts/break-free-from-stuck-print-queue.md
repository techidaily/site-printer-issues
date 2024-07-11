---
title: Break Free From Stuck Print Queue
date: 2024-07-10T17:15:34.778Z
updated: 2024-07-11T17:15:34.778Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Break Free From Stuck Print Queue
excerpt: This Article Describes Break Free From Stuck Print Queue
keywords: Clear Stuck Print Queue,Fix Printer Printing Issues,Stop Printer Error Message,Resolve Print Spooler Problems,End Stuck Print Job Issue,Unfreeze or Release Print Queue,Prevent Long-Running Print Jobs
thumbnail: https://thmb.techidaily.com/4e1e135a4b0338f686903eb0c608ba2a349e6fad2f1ea5329a35a6ad22caba43.png
---

## Break Free From Stuck Print Queue

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
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-driver-missing-please-help/"><u>Canon Pixma MP620: Driver Missing, Please Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-ad-service-interrupted/"><u>Unable To Print: AD Service Interrupted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immaculate-documents-from-hp-printer-post-correction/"><u>Immaculate Documents From HP Printer Post-Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-printer-connectivity-issues-in-w11/"><u>Tackle Printer Connectivity Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-all-pages-now-available/"><u>Perfect Print: All Pages Now Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-back-to-normal-goodbye-ghost-bars/"><u>HP Printer Back to Normal: Goodbye, Ghost Bars</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-settled-printer-issues-post-upgrade/"><u>Issue Settled: Printer Issues Post Upgrade</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-inkjet-and-laser-issues-win10-style/"><u>Fix Inkjet & Laser Issues, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-blank-pages-fixing-brother-printer-not-printing-in-win/"><u>Stop Blank Pages: Fixing Brother Printer Not Printing in Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-toner-depletion-crisis/"><u>Curing Toner Depletion Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-workspace-setup-with-easy-fixes-for-print-laptop-linkage/"><u>Revolutionizing Workspace Setup with Easy Fixes for Print-Laptop Linkage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/whiteout-printing-issue-plaguing-my-epson-model/"><u>Whiteout Printing Issue Plaguing My Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-not-working-solve-it-in-win1011/"><u>Brother Printer Not Working? Solve It in Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/convenient-canon-printer-wireless-integration/"><u>Convenient Canon Printer Wireless Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-service-from-frequently-stopping/"><u>Stop Windows Print Service From Frequently Stopping</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-printing-speed-today/"><u>Streamline Printing Speed Today</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-canon-printer-step-by-step/"><u>Installing Canon Printer - Step-by-Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/never-again-the-end-of-blank-printouts/"><u>Never Again: The End of Blank Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-online-on-windows-7-after-troubleshooting/"><u>Printer Online on Windows 7 After Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-operations-new-printing-toolkit-for-windows-7-dell/"><u>Smooth Operations: New Printing Toolkit for Windows 7 Dell</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-displace-queued-print-operations/"><u>Swiftly Displace Queued Print Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-communications-unavailable/"><u>Print Issue: Communications Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-error-code-0x97/"><u>[Solved] Epson Error Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-mute-how-to-engage/"><u>Canon Printer Mute - How to Engage?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-canon-printer-seamless-wireless-hookup/"><u>Stepwise Canon Printer: Seamless Wireless Hookup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smoothly-reactivated-scanner-on-windows-11/"><u>Smoothly Reactivated Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-updates-for-sluggish-printers/"><u>Speedy Updates for Sluggish Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-sleephibernate-glitch-with-usb-printers-w7/"><u>[Resolved] Sleep/Hibernate Glitch with USB Printers, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-shenanigans-unauthorized-printer-access/"><u>System Shenanigans: Unauthorized Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-hook-up-your-hp-officejet-pro-duo/"><u>Quick Guide: Hook Up Your HP Officejet Pro Duo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unravel-offline-mystery-with-easy-fixes-for-your-canon-printer/"><u>Unravel Offline Mystery with Easy Fixes for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-fedex-printer-connectivity-troubles/"><u>Rectifying FedEx Printer Connectivity Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-silent-hp-printers/"><u>Quick Fixes for Silent HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-closer-inspect-of-the-stunning-dell-p2715q-monitors-capabilities/"><u>2024 Approved  A Closer Inspect of the Stunning Dell P2715Q Monitor's Capabilities</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-control-over-screen-dpi-in-windows-11-fix/"><u>Enhanced Control Over Screen DPI in Windows 11 Fix</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-itel-p55-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Itel P55 Quickly | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1716042027137-new-2024-approved-top-6-minecraft-house-ideas-for-beginners/"><u>[New] 2024 Approved  Top 6 Minecraft House Ideas [for Beginners]</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ering-the-future-of-online-filmmaking-with-sony-vegas-and-youtube/"><u>Pioneering the Future of Online Filmmaking with Sony Vegas and YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-advanced-screen-recording-suite-for-windows-and-macos/"><u>In 2024, Advanced Screen Recording Suite for Windows & macOS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-exploring-the-efficiency-of-modern-tunefab-recorders/"><u>[New] In 2024, Exploring the Efficiency of Modern Tunefab Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-error-unsigned-update-files-fix-guide/"><u>Windows Error: Unsigned Update Files; Fix Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-windows-video-editing-made-easy-a-step-by-step-guide/"><u>2024 Approved Windows Video Editing Made Easy A Step-by-Step Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-step-into-vlogging-fundamental-gear-and-applications/"><u>In 2024, Step Into Vlogging  Fundamental Gear and Applications</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-sound-sanitation-online-eliminating-unwanted-audio-disturbances-from-web-streams/"><u>In 2024, Sound Sanitation Online Eliminating Unwanted Audio Disturbances From Web Streams</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-live-setting-picks/"><u>Ultimate Live Setting Picks</u></a></li>
<li><a href="https://ai-voice.techidaily.com/top-6-mickey-mouse-voice-generators-providing-efficient-results/"><u>Top 6 Mickey Mouse Voice Generators Providing Efficient Results</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-itel-p55t-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Itel P55T</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-key-dimensions-youtube-titles-and-images-that-work/"><u>In 2024, Key Dimensions  YouTube Titles & Images That Work</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-transformation-mp4-plus-srt-success-for-2024/"><u>The Ultimate Transformation  MP4 + SRT Success for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-five-iphone-podcast-services-to-streaming/"><u>[New] Five iPhone Podcast Services to Streaming</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unmatched-streaming-excellence-top-1enas-comparative-analysis/"><u>[Updated] Unmatched Streaming Excellence  Top 1Enas Comparative Analysis</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-preserve-audio-perfection-how-to-convert-video-to-mp3/"><u>Updated In 2024, Preserve Audio Perfection How to Convert Video to MP3</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-poco-x5-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Poco X5 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/a-backward-glance-proven-strategies-for-pinpointing-picture-sources-on-instagram/"><u>A Backward Glance  Proven Strategies for Pinpointing Picture Sources on Instagram</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-capturing-time-on-pause-instagrams-slow-motion-secrets-for-2024/"><u>[Updated] Capturing Time on Pause  Instagram's Slow-Motion Secrets for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enjoy-endless-creativity-discover-the-best-in-cheap-online-video-downloading/"><u>[Updated] 2024 Approved  Enjoy Endless Creativity  Discover the Best in Cheap, Online Video Downloading</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-best-methods-to-record-high-quality-audio-in-mp3-format-top-5-recorder-choices-for-2024/"><u>The Best Methods to Record High-Quality Audio in MP3 Format – Top 5 Recorder Choices for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/screenflow-mastery-for-mac-users-a-critical-look-for-2024/"><u>ScreenFlow Mastery for Mac Users – A Critical Look for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-synchronized-screen-serenity-youtube-loops-on-television/"><u>[New] Synchronized Screen Serenity  YouTube Loops on Television</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-navigating-message-reactions-with-ease-discord/"><u>[New] 2024 Approved  Navigating Message Reactions with Ease (Discord)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-guide-to-effortless-telegram-web-use/"><u>2024 Approved  Step-by-Step Guide to Effortless Telegram Web Use</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-charting-the-course-for-youtube-music-uploads/"><u>[Updated] In 2024, Charting the Course for YouTube Music Uploads</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-from-everyday-use-to-extraordinary-virtual-adventures-smartphone-vr-conversion-guide/"><u>2024 Approved  From Everyday Use to Extraordinary Virtual Adventures  Smartphone-VR Conversion Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhance-social-media-presence-by-saving-webcam-videos-via-vlc-for-2024/"><u>Enhance Social Media Presence by Saving Webcam Videos via VLC for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-zero-to-hero-funimates-apk-unleashed-playbook/"><u>[New] From Zero to Hero  Funimate's APK Unleashed Playbook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-essential-screen-recording-software-list-for-vloggers/"><u>[New] 2024 Approved  Essential Screen Recording Software List for Vloggers</u></a></li>
</ul></div>
