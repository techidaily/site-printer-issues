---
title: Erase Print Task Queue Pause
date: 2024-07-29T00:29:09.152Z
updated: 2024-07-30T00:29:09.152Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Erase Print Task Queue Pause
excerpt: This Article Describes Erase Print Task Queue Pause
keywords: Erase Print Tasks,Cancel Printer Jobs,Halt Printing Queue,Pause Document Printing,Resume Print Queue,Stop Printing Process,Undo Recent Prints,Search Volume,Competitiveness,Relevance
thumbnail: https://thmb.techidaily.com/086d7c930c164ea9d01018f76fb536ddc6879aa44f658266ac4dd473faff469b.jpg
---

## Erase Print Task Queue Pause

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-best-practices-for-secure-transfer-of-phones-camera-roll-content-to-snapchat/"><u>[New] 2024 Approved  Best Practices for Secure Transfer of Phone's Camera Roll Content to Snapchat</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-diving-into-benqs-bl2711u-a-professional-4k-monitor-analysis/"><u>[New] In 2024, Diving Into BenQ’s BL2711U - A Professional 4K Monitor Analysis</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-screencapture-pro-laptop-tips-and-tricks/"><u>[New] In 2024, ScreenCapture Pro  Laptop Tips & Tricks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-lowering-obs-video-bandwidth/"><u>[New] Lowering OBS Video Bandwidth</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-perfect-your-images-with-polarr-a-complete-photography-resource/"><u>[New] Perfect Your Images with Polarr  A Complete Photography Resource</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-deskjet-d1360-printer-drivers-wont-install-in-windows-7-8-8110/"><u>[Resolved] HP Deskjet D1360 Printer Drivers Won’t Install in Windows 7, 8, 8.1,10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-issue-unable-to-locate-hp-print-drivers-on-win11/"><u>[System Issue] - Unable to Locate HP Print Drivers on Win11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-enhance-ipad-recording-simpler-approaches-revealed/"><u>[Updated] 2024 Approved  Enhance iPad Recording  Simpler Approaches Revealed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-explore-and-review-every-application-az-screenshotters-way/"><u>[Updated] 2024 Approved  Explore & Review Every Application - AZ Screenshotter's Way</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-laughter-logic-lab/"><u>[Updated] 2024 Approved  Laughter Logic Lab</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitters-wild-ride-the-hottest-tweets-unveiled/"><u>[Updated] 2024 Approved  Twitter's Wild Ride  The Hottest Tweets Unveiled</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-instant-stars-youtube-videos-with-rapid-popularity/"><u>[Updated] In 2024, Instant Stars  Youtube Videos with Rapid Popularity</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-peak-panzoid-structures-for-beginners/"><u>[Updated] Peak Panzoid Structures for Beginners</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-360-vision-showdown-samsung-and-lg-camera-face-off/"><u>2024 Approved  360 Vision Showdown  Samsung & LG Camera Face Off</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-achieve-perfect-youtube-broadcasts-with-superior-webcams/"><u>2024 Approved  Achieve Perfect YouTube Broadcasts with Superior Webcams</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-tactics-for-smoothly-importing-movies-to-vimeo-from-wmm/"><u>2024 Approved  Tactics for Smoothly Importing Movies to Vimeo From WMM</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-comprehensive-blueprint-for-capturing-whatsapp-calls/"><u>2024 Approved  The Comprehensive Blueprint for Capturing WhatsApp Calls</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-samsung-galaxy-a14-4g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Samsung Galaxy A14 4G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/added-printer-with-successful-operation/"><u>Added Printer with Successful Operation</u></a></li>
<li><a href="https://games-able.techidaily.com/ally-x-overcomes-key-handheld-challenge/"><u>Ally X Overcomes Key Handheld Challenge</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/apex-fb-platforms-topping-the-10-list/"><u>Apex FB Platforms  Topping the 10 List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-offline-troubles-with-a-neighborhood-printer/"><u>Avoiding Offline Troubles with a Neighborhood Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-problem-resolved/"><u>B200: Problem Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-errors-try-these-fixes-on-windows-1011/"><u>Brother Printer Errors? Try These Fixes on Windows 10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-samsung-galaxy-a05s-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Samsung Galaxy A05s to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-misaligned-images-from-w11-printers/"><u>Correct Misaligned Images From W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-printer-error-messages/"><u>Corrected Printer Error Messages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-v305-aio-printer-driver-update-in-windows-7/"><u>Dell V305 AIO Printer Driver Update in Windows 7</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/direct-entry-into-your-channel-simplifying-the-follow-button-creation-for-2024/"><u>Direct Entry Into Your Channel  Simplifying the Follow Button Creation for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-the-mystery-of-non-printing-machines/"><u>Dismantling the Mystery of Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-mf4770n-performance-in-windows-108/"><u>Enhancing MF4770n Performance in WIndows 10/8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-white-paper-trap-how-to-prevent-it/"><u>Epson's White Paper Trap: How to Prevent It?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expedite-your-experience-quick-iphone-time-lapse-for-2024/"><u>Expedite Your Experience  Quick iPhone Time-Lapse for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printer-driver-issues-on-windows-11/"><u>Fix Printer Driver Issues on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-issue-with-installing-printer/"><u>Fixed Issue with Installing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-offline-error/"><u>Fixing: Printer Offline Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-reactivate-dormant-hp-printers/"><u>Guidelines to Reactivate Dormant HP Printers</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-vivo-y27-4g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo Y27 4G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-honor-play-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-sony-xperia-1-v-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Sony Xperia 1 V</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-xiaomi-redmi-13c-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Xiaomi Redmi 13C</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-tecno-camon-20-premier-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Tecno Camon 20 Premier 5G Phone that is Locked?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-unlocking-video-treasures-securely-capturing-igtv-videos-on-windows-and-macos/"><u>In 2024, Unlocking Video Treasures  Securely Capturing IGTV Videos on Windows & MacOS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-canon-printer-step-by-step/"><u>Installing Canon Printer - Step-by-Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-printer-disconnection/"><u>Instantly Resolve Printer Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-network-printer-service-in-standby-mode/"><u>Local Network Printer Service in Standby Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/networking-issues-fixed-win7-printer-online/"><u>Networking Issues Fixed: Win7 Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-roll-out-latest-windows-7-dell-updates/"><u>Optimize Printing: Roll-Out Latest Windows 7 Dell Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printing-blockade-oxc4eb827f/"><u>Overcoming HP Printing Blockade: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paperjam-prevention-tips/"><u>PaperJam Prevention Tips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/premier-mc-village-residential-plans-for-2024/"><u>Premier MC Village Residential Plans for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/premium-audio-packs-for-visual-storytelling/"><u>Premium Audio Packs for Visual Storytelling</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recognition-failure-hp-driver-missing-in-win1011/"><u>Printer Recognition Failure: HP Driver Missing in WIN10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-refusing-to-use-all-colors/"><u>Printer Refusing to Use All Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-service-disabled-trouble-in-windows/"><u>Printer Service Disabled: Trouble in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-slow-printers/"><u>Quick Remedies for Slow Printers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-xiaomi-redmi-note-13-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Xiaomi Redmi Note 13 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-printers-purpose-beyond-empty-pages/"><u>Reviving a Printer's Purpose Beyond Empty Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scan-functionality-reinstated-in-win11/"><u>Scan Functionality: Reinstated in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-and-update-hp-officejet-4630-driver-edition/"><u>Secure & Update: HP Officejet 4630 Driver Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-restore-printer-functionality/"><u>Steps to Restore Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-and-rectify-non-responsive-printer-on-nt/"><u>Troubleshoot and Rectify Non-Responsive Printer on NT</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-locate-canon-pixma-mp620-drivers-on-win10/"><u>Unable to Locate Canon Pixma MP620 Drivers on WIN10</u></a></li>
</ul></div>
