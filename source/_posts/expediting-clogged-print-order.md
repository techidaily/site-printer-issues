---
title: Expediting Clogged Print Order
date: 2024-07-10T17:31:01.615Z
updated: 2024-07-11T17:31:01.615Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expediting Clogged Print Order
excerpt: This Article Describes Expediting Clogged Print Order
keywords: Expedited Print Orders,Fast Track Print Processing,Urgent Printer Order Support,Resolving Print Job Delays,Speedy Order Fulfillment for Printing Services,Clogged Printer Issue Resolution,Accelerated Print Order Handling
thumbnail: https://thmb.techidaily.com/9009e7502f48b6a7260ab49e34d5c0ede3d2f18aac9b63fbba531138fcdb2ca3.jpg
---

## Expediting Clogged Print Order

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
<li><a href="https://printer-issues.techidaily.com/clearing-crosscheck-print-failures/"><u>Clearing Crosscheck Print Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-online-status-for-your-printer/"><u>Reclaiming Online Status for Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-for-mounting-your-canon-printer/"><u>Essential Steps for Mounting Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-inkjet-aio-updater-for-win7/"><u>Dell Inkjet AIO Updater for Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-failure-spooler-issue-on-workstation/"><u>[SYSTEM FAILURE] Spooler Issue on Workstation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reset-scanner-connection-status-on-pc-windows-10/"><u>Reset Scanner Connection Status on PC, Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-online-after-repair/"><u>Win7 Printer Online After Repair</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-unable-to-locate-hp-driver-on-winxo/"><u>[Driver Difficulty] - Unable to Locate HP Driver on WinXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-reactivity-in-canon-printer-mode/"><u>Non-Reactivity in Canon Printer Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-printer-software-solution-officejet-pro-8600-for-windows-pcs/"><u>Unified Printer Software Solution: Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-your-hp-laserjet-remote-connection/"><u>Setting Up Your HP LaserJet Remote Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-integrating-hp-officejet-pro-8720-into-pc/"><u>Guide: Integrating HP Officejet Pro 8720 Into PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-on-offline-hp-desktop-printer-in-wx-2003/"><u>Turn On Offline HP Desktop Printer in WX 2003</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ease-into-plc-error-resolution/"><u>Ease Into PLC Error Resolution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-due-to-domain-service-outage/"><u>Printer Problem Due to Domain Service Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-intervention-in-stuck-printer-queue/"><u>Brisk Intervention in Stuck Printer Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/manual-setting-up-hp-officejet-on-desktop-system/"><u>Manual: Setting up HP Officejet on Desktop System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-missing-unsuccessful-in-finding-pixma-mp620-on-win11/"><u>[Driver Missing] Unsuccessful in Finding Pixma MP620 on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/second-pc-same-printer-issue-resolved/"><u>Second PC, Same Printer Issue? Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-hp-printer-status/"><u>How to Reactivate HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-back-to-normal-goodbye-ghost-bars/"><u>HP Printer Back to Normal: Goodbye, Ghost Bars</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-error-code-oxc4eb827f-on-hp-printers/"><u>How to Fix Error Code OXC4EB827F on HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-guide-reconnect-missing-print-devices-windows-xp-7-10/"><u>[Network Guide] Reconnect Missing Print Devices Windows-XP-7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-11/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/slow-down-your-videos-a-step-by-step-guide-to-vlcs-slow-motion-feature/"><u>Slow Down Your Videos A Step-by-Step Guide to VLCs Slow Motion Feature</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-a-movie-in-minutes-a-quickstart-guide-for-2024/"><u>New Make a Movie in Minutes A Quickstart Guide for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-list-mac-video-editors-for-macos-big-sur-11-users-for-2024/"><u>Ultimate List  Mac Video Editors for macOS Big Sur 11 Users for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-master-your-images-top-15-instagram-downloader-apps-for-2024/"><u>[Updated] Master Your Images  Top 15 Instagram Downloader Apps for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagram-visual-mastery-crop-and-edit-videos-like-pros/"><u>Instagram Visual Mastery  Crop and Edit Videos Like Pros</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/essential-mp3-labeling-tools-the-five-must-have-online-editors-for-2024/"><u>Essential MP3 Labeling Tools The Five Must-Have Online Editors for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-showdown-of-projectors-and-tvs-in-a-4k-setting/"><u>The Ultimate Showdown of Projectors & TVs in a 4K Setting</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/vdx-quickcapture-evaluation-guide-comprehensive-review/"><u>VDX QuickCapture Evaluation Guide  Comprehensive Review</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-xiaomi-14-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Xiaomi 14 Device</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-ultimate-tutorial-mastering-twitter-video-responses/"><u>[Updated] 2024 Approved  Ultimate Tutorial  Mastering Twitter Video Responses</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-filmora-edits-explained-addressing-common-concerns-and-questions/"><u>[New] Filmora Edits Explained  Addressing Common Concerns and Questions</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-foremost-sound-amplifiers-for-smartphones-androidios-updated-list/"><u>The Foremost Sound Amplifiers for Smartphones (Android/iOS, Updated List)</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-poco-m6-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Poco M6 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-powerdirector-color-correction-bringing-harmony-to-your-video-edits/"><u>New PowerDirector Color Correction Bringing Harmony to Your Video Edits</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-from-footage-to-narrative-the-essential-guide-to-instagram-descriptive-texts/"><u>2024 Approved  From Footage to Narrative  The Essential Guide to Instagram Descriptive Texts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-ultimate-voice-memo-solution-comparing-vocaroo-and-its-competitors/"><u>Updated In 2024, The Ultimate Voice Memo Solution Comparing Vocaroo and Its Competitors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/saving-big-on-final-cut-pro-without-paying/"><u>Saving Big on Final Cut Pro without Paying</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-amass-1000-visionary-supporters-fast-track-style/"><u>[Updated] Amass 1,000 Visionary Supporters Fast-Track Style</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-inside-look-freewebcampro-software-overview/"><u>[New] In 2024, Inside Look  FreeWebcamPro Software Overview</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-photo-mosaics-unveiled-a-journey-to-brighter-spaces/"><u>[New] In 2024, Photo Mosaics Unveiled  A Journey to Brighter Spaces</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-crafting-perfect-lines-in-digital-imagery/"><u>In 2024, Crafting Perfect Lines in Digital Imagery</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-the-ultimate-list-of-free-video-dubbing-software-for-pc/"><u>In 2024, The Ultimate List of Free Video Dubbing Software for PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-guide-to-cost-effective-2024-cloud-services/"><u>[New] Ultimate Guide to Cost-Effective 2024 Cloud Services</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-new-worlds-an-in-depth-study-of-6-metaverse-models/"><u>In 2024, Navigating New Worlds  An In-Depth Study of 6 Metaverse Models</u></a></li>
<li><a href="https://discord-videos.techidaily.com/unveiling-the-secrets-of-discord-spoilers/"><u>Unveiling the Secrets of Discord Spoilers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-keeping-your-views-private-top-5-insta-tools/"><u>[New] 2024 Approved  Keeping Your Views Private - Top 5 Insta Tools</u></a></li>
</ul></div>
