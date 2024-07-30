---
title: Bypass Printer Job Queue Delay Instantly
date: 2024-07-29T00:28:19.733Z
updated: 2024-07-30T00:28:19.733Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Bypass Printer Job Queue Delay Instantly
excerpt: This Article Describes Bypass Printer Job Queue Delay Instantly
keywords: Instant Print Queue Bypass,Printer Job Speed Up,Avoid Printer Wait Time,Fast Print Processing,Printer Queue Optimization,Real-Time Printer Job Management,Eliminate Print Job Latency
thumbnail: https://thmb.techidaily.com/850c193e7db5e5c0dafad83a501e0d012a7f8ab4be61e59f0459fea3e866d702.png
---

## Bypass Printer Job Queue Delay Instantly

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/driver-search-problem-windows-10-cant-find-mp620-printer-driver/"><u>[Driver Search] Problem: Windows 10 Can't Find MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canon-printer-not-responding/"><u>[FIXED] Canon Printer Not Responding</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-expert-picks-top-9-video-chat-and-conference-apps-iosandroid/"><u>[New] 2024 Approved  Expert Picks  Top 9 Video Chat & Conference Apps iOS/Android</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-streaming-success-monetization-unlocked-with-500-subscribers/"><u>[New] Streaming Success  Monetization Unlocked with 500 Subscribers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unmatched-smartphone-camera-apps-on-ios-and-android-devices/"><u>[New] Unmatched Smartphone Camera Apps on iOS & Android Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-alert-unable-to-locate-on-windows-10/"><u>[Printer Driver Alert]: Unable to Locate on Windows 10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-experts-choice-extracting-youtube-video-intros-online-for-2024/"><u>[Updated] Expert's Choice  Extracting Youtube Video Intros Online for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-alternative-solutions-to-game-bar-recording/"><u>[Updated] In 2024, Alternative Solutions to Game Bar Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-quick-click-quality-4-simple-steps-to-take-a-chromebook-screenshot/"><u>[Updated] Quick Click Quality  4 Simple Steps to Take a Chromebook Screenshot</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-resolve-deceptive-user-appearance-within-chat-environments/"><u>[Updated] Resolve Deceptive User Appearance Within Chat Environments</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-richer-screen-content-filter-integration-on-devices/"><u>[Updated] Richer Screen Content  Filter Integration on Devices</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2023-comprehensive-grip-on-visualcutter-software-review-for-2024/"><u>2023 Comprehensive Grip on VisualCutter Software Review for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-10-top-inspirational-movies-for-personal-power-boosts/"><u>2024 Approved  10 Top Inspirational Movies for Personal Power Boosts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-craft-stunning-designs-learn-to-cleanse-images-background-in-canva/"><u>2024 Approved  Craft Stunning Designs  Learn to Cleanse Images' Background in Canva</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-honor-90-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Honor 90 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/another-computer-is-using-the-printer-solved/"><u>Another Computer Is Using the Printer [Solved]</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/avoiding-unwanted-shaking-in-dynamic-gopro-footage-for-2024/"><u>Avoiding Unwanted Shaking in Dynamic GoPro Footage for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-load-printer-driver-not-detected-by-win/"><u>Cannot Load Printer: Driver Not Detected by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-driver-missing-please-help/"><u>Canon Pixma MP620: Driver Missing, Please Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-wireless-connectivity-issues-for-w11-printers/"><u>Correct Wireless Connectivity Issues for W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easily-set-up-brothers-9330w-fan/"><u>Easily Set Up Brother's 9330W Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/excessive-blank-sheets-on-new-epson-multifunction-product/"><u>Excessive Blank Sheets on New Epson Multifunction Product</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-guide-to-prime-livestream-sites-for-2024/"><u>Exclusive Guide to Prime Livestream Sites for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-right-hp-d1360-print-drivers-in-windows-ecosystems/"><u>Finding the Right HP D1360 Print Drivers in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574049626-fix-print-job-stuck-in-queue-quickly/"><u>Fix 'Print Job Stuck in Queue' Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixation-on-pcl-xl-a-handy-manual/"><u>Fixation on PCL XL: A Handy Manual</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-no-more-blank-documents/"><u>Fixed [Epson]: No More Blank Documents</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-realme-c51-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Realme C51 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-magic-v2-phone-without-google-account-by-drfone-android/"><u>How to Unlock Honor Magic V2 Phone without Google Account?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-scan-and-print-unit-fixed-no-more-delays/"><u>HP Scan & Print Unit Fixed - No More Delays</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-oneplus-ace-2v-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace OnePlus Ace 2V Location | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-disconnected-print-issue/"><u>Instantly Resolve Disconnected Print Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/intruder-alert-unexpected-printer-activity/"><u>Intruder Alert: Unexpected Printer Activity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-fault-resolutions/"><u>Mastering Printer Fault Resolutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-quick-fixes-for-pcl-xl-errors/"><u>Mastering Quick Fixes for PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-updates-for-streamlined-windows-functionality/"><u>MF4770n Updates for Streamlined Windows Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-errors-in-connecting-printer-to-pc/"><u>No Errors in Connecting Printer to PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/not-all-colors-printing-as-expected/"><u>Not All Colors Printing as Expected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-post-update-printer-glitches/"><u>Overcoming Post-Update Printer Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574064539-post-update-printer-problem-resolved-and-happy-again/"><u>Post-Update Printer Problem: Resolved and Happy Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-silence-speaks-louder-than-no-response/"><u>Printer's Silence Speaks Louder Than No Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-now-consistently-full-page-output/"><u>Printers Now Consistently Full-Page Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-dispatch-of-print-queue-jobs/"><u>Quick Dispatch of Print Queue Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-internet-connectivity-for-brother-printer/"><u>Reclaiming Internet Connectivity for Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printing-with-simple-tips-for-canon-windows/"><u>Reignite Printing with Simple Tips for Canon, Windows</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-gt-10-pro-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of GT 10 Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-failed-printer-defaults-error-code-0x00000709-overcome/"><u>Resetting Failed Printer Defaults: Error Code 0X00000709 Overcome</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-hp-printer-connectivity-issues/"><u>Resolving HP Printer Connectivity Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-inactive-hp-printing-units/"><u>Reviving Inactive HP Printing Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a15-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A15 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-system-flaw-b200/"><u>Solved: System Flaw B200</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/streamlined-subtitling-processes-for-instagrams-dynamic-media-for-2024/"><u>Streamlined Subtitling Processes for Instagram's Dynamic Media for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-the-road-for-printer-errors-with-windows-update/"><u>The End of the Road for Printer Errors with Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unjamming-print-heads-a-practical-approach/"><u>Unjamming Print Heads: A Practical Approach</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugging-and-removing-a-secondary-printer-from-os/"><u>Unplugging and Removing a Secondary Printer From OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-removal-guide-for-external-devices/"><u>Win Removal Guide for External Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win10-printer-setup-guide-hp-connection-fixes/"><u>Win10 Printer Setup Guide - HP Connection Fixes</u></a></li>
</ul></div>
