---
title: Speedy Release From Print Lineup
date: 2024-08-27T02:19:32.068Z
updated: 2024-08-28T02:19:32.068Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speedy Release From Print Lineup
excerpt: This Article Describes Speedy Release From Print Lineup
keywords: Speedy Printer Release,Rapid Print Production,Quick Print Lineup Turnaround,High-Speed Printer Manufacturer,Faster Print Lineup Options,Speedy Printer Lineup Models,Quick Print Press Release Schedule
thumbnail: https://thmb.techidaily.com/06768f0764e3fd16593ec6ab66fe93ff9404677c09f36129dabffcc95362a115.jpg
---

## Speedy Release From Print Lineup

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

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/024-approved-optimizing-youtube-auditory-experience-for-viewers/"><u>[New] 2024 Approved  Optimizing YouTube Auditory Experience for Viewers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elite-recording-devices-for-livestream-producers-for-2024/"><u>[New] Elite Recording Devices for Livestream Producers for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-masterful-motivational-webcast-maker/"><u>[New] Masterful Motivational Webcast Maker</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-viral-video-quarterly-watch/"><u>[New] Viral Video Quarterly Watch</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-10-easy-youtube-video-ideas-everyone-can-make-it/"><u>[Updated] 10 Easy YouTube Video Ideas Everyone Can Make It</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-elevate-your-streaming-experience-six-insightful-quizzes-for-fandom-enthusiasts/"><u>[Updated] 2024 Approved  Elevate Your Streaming Experience  Six Insightful Quizzes for Fandom Enthusiasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-thrifty-pc-recording-utilities/"><u>[Updated] 2024 Approved  Thrifty PC Recording Utilities</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-digital-stream-capturers-2023-edition/"><u>[Updated] In 2024, Digital Stream Capturers, 2023 Edition</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-your-complete-guide-to-starting-a-zoom-conversation-on-an-android-device/"><u>[Updated] In 2024, Your Complete Guide to Starting a Zoom Conversation on an Android Device</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unboxing-mastery-the-soundtrack-selection-guidebook/"><u>[Updated] Unboxing Mastery  The Soundtrack Selection Guidebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-tips-how-to-reinstall-a-lost-print-job/"><u>[Windows Tips] How to Reinstall a Lost Print Job</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-ideal-pixel-gatherings-unique-ringtone-repository/"><u>2024 Approved  Ideal Pixel Gatherings  Unique Ringtone Repository</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-instagrams-silent-frames-no-more-a-sound-fix/"><u>2024 Approved  Instagram's Silent Frames No More – A Sound Fix</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-prime-recommendations-downloading-video-intros-and-templates/"><u>2024 Approved  Prime Recommendations  Downloading Video Intros & Templates</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-visionary-backdrop-transformers-photorealm-innovation/"><u>2024 Approved  Visionary Backdrop Transformers  PhotoRealm Innovation</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-vivo-y27-5g-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Vivo Y27 5G FRP</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-distortion-in-far-cry-6-game-graphics/"><u>Addressing Distortion in Far Cry 6 Game Graphics</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/apples-leap-forward-an-in-depth-look-at-the-m1-chip-in-the-latest-macbook-air-13-model-reviewed/"><u>Apple's Leap Forward: An In-Depth Look at the M1 Chip in the Latest MacBook Air 13” Model Reviewed</u></a></li>
<li><a href="https://win-solutions.techidaily.com/boosting-download-velocity-a-comprehensive-guide-for-improving-origin-speed/"><u>Boosting Download Velocity: A Comprehensive Guide for Improving Origin Speed</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/breaking-down-vimeo-streaming-giants-secrets-revealed-for-2024/"><u>Breaking Down Vimeo  Streaming Giant's Secrets Revealed for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bring-to-life-enable-your-silent-canon-print-spooler/"><u>Bring To Life: Enable Your Silent Canon Print Spooler</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/build-diy-virtual-reality-google-cardboard-hack/"><u>Build DIY Virtual Reality  Google Cardboard Hack</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-nokia-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Nokia?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/can-you-and-a-friend-listen-to-the-same-song-on-spotify-in-real-time/"><u>Can You And A Friend Listen To The Same Song On Spotify In Real Time?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-repeated-print-job-errors-in-windows-operating-systems/"><u>Combat Repeated Print Job Errors in Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-to-downloading-the-updated-driver-for-your-hp-officejet-pro-8610-on-various-windows-versions/"><u>Complete Guide to Downloading the Updated Driver for Your HP Officejet Pro 8610 on Various Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-connectivity-windows-10-way/"><u>Enhance Printer Connectivity, Windows 10 Way</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-windows-printer-setup-successfully-fixed/"><u>Error 0X00000709: Windows Printer Setup Successfully Fixed</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/exploring-the-world-of-computing-with-toms-gadget-guide/"><u>Exploring the World of Computing with Tom's Gadget Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-error-due-to-active-directory-halt/"><u>Fixed: Printer Error Due to Active Directory Halt</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-link-issues-fastly/"><u>Fixing Printer Link Issues Fastly</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-realme-narzo-n53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/get-the-scoop-on-playstation-5-slim-current-costs-future-launch-dates-and-in-depth-hardware-specs-revealed/"><u>Get the Scoop on PlayStation 5 Slim: Current Costs, Future Launch Dates & In-Depth Hardware Specs Revealed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/guide-sharing-melodies-in-facebook-narratives-for-2024/"><u>Guide  Sharing Melodies in Facebook Narratives for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/high-performance-drivers-hp-officejet-pro-8600-for-windows-pcs/"><u>High-Performance Drivers: HP Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/managing-paper-tray-sensor-problems/"><u>Managing Paper Tray Sensor Problems</u></a></li>
<li><a href="https://fox-helps.techidaily.com/master-money-with-periscope-a-newcomers-manual-for-2024/"><u>Master Money with Periscope  A Newcomer's Manual for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-guided-instructions-your-ultimate-guide-to-hp-printer-installation/"><u>Precision-Guided Instructions: Your Ultimate Guide to HP Printer Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-misdemeanor-by-unknown-system/"><u>Printing Misdemeanor by Unknown System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconciled-printer-not-responding/"><u>Reconciled: Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-head-alignment-issues-in-w11/"><u>Resolve Print Head Alignment Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-samsung-galaxy-s23-fe-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-samsung-print-woes/"><u>Solving Samsung Print Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-recover-an-offline-print-device-from-network/"><u>Steps to Recover an Offline Print Device From Network</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streamers-financial-health-check-in-youtubers-for-2024/"><u>Streamer's Financial Health Check in YouTubers for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-jolt-to-halted-print-queues/"><u>Swift Jolt to Halted Print Queues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-resolving-non-responsive-hp-scanners/"><u>Techniques for Resolving Non-Responsive HP Scanners</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-no-response/"><u>Troubleshooting HP Printer No Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-icon-in-win-810-systems/"><u>Unexpectedly No Printer Icon in Win 8/10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
</ul></div>
