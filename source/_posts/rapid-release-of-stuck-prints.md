---
title: Rapid Release of Stuck Prints
date: 2024-08-31T04:36:47.151Z
updated: 2024-09-01T04:36:47.151Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Release of Stuck Prints
excerpt: This Article Describes Rapid Release of Stuck Prints
keywords: Stuck Prints Removal,Quick Unsticking Methods,Gummed Prints Solution,Print Release Techniques,Sticky Backing Board Removal,Non-Destructive Stick Print Release,How to Unstick Prints
thumbnail: https://thmb.techidaily.com/80de444cb408ef81f4728e2850b723591d8016d7f4cd61445fe263111407c51f.jpg
---

## Rapid Release of Stuck Prints

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
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-detected-unable-to-connect-pixma-mp620-to-win10/"><u>[Driver Not Detected] Unable to Connect Pixma MP620 to WIN10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-wintvrecorder-effortless-free-live-tv-saving-software/"><u>[New] In 2024, WinTVRecorder  Effortless, FREE Live TV Saving Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-drones-for-superior-gopro-camera-integration/"><u>[New] Leading Drones for Superior GoPro Camera Integration</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-understanding-sns-hdr-pros-role-in-hdr-editing-for-2024/"><u>[New] Understanding SNS HDR Pro's Role in HDR Editing for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-harnessing-power-a-complete-ez-grabber-manual/"><u>[Updated] 2024 Approved  Harnessing Power  A Complete EZ Grabber Manual</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-video-partition-prowess-ultimate-recorder-ranking-for-2024/"><u>[Updated] Video Partition Prowess  Ultimate Recorder Ranking for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-jumpstart-your-career-with-a-killer-youtube-gaming-channel/"><u>2024 Approved  Jumpstart Your Career with a Killer YouTube Gaming Channel</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-unveiling-the-secrets-of-video-captioning-in-vimeo/"><u>2024 Approved  Unveiling the Secrets of Video Captioning in Vimeo</u></a></li>
<li><a href="https://buynow-info.techidaily.com/2024s-most-effective-alternatives-to-microsoft-office-find-your-perfect-fit/"><u>2024'S Most Effective Alternatives to Microsoft Office – Find Your Perfect Fit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-met-not-satisfied-tagging-on-win11/"><u>Bypass Met Not Satisfied Tagging on Win11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/celebrating-18-years-digiartys-exclusive-limited-time-event/"><u>Celebrating 18 Years - Digiarty's Exclusive Limited-Time Event</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compreeed-software-bundle-officejet-pro-8600-windows-integration/"><u>Compreeed Software Bundle: OfficeJet Pro 8600, Windows Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-print-issues-with-comprehensive-windows-hp-guide/"><u>Conquer Print Issues with Comprehensive Windows HP Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/default-printer-dilemma-windows-error-0x00000709-squashed/"><u>Default Printer Dilemma: Windows Error (0X00000709) Squashed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-end-print-job-wait/"><u>Efficiently End Print Job Wait</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-of-missing-pages-with-new-tech-update/"><u>End of Missing Pages with New Tech Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-white-sheet-saga-with-hp-printer-fix/"><u>Ending White Sheet Saga with HP Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-office-efficiency-3-fixes-for-printer-and-laptop-synergy/"><u>Enhancing Office Efficiency: 3 Fixes for Printer & Laptop Synergy</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-latest-focusrite-scarlett-18i20-audio-interface-drivers-for-windows/"><u>Free Download: Latest Focusrite Scarlett 18I20 Audio Interface Drivers for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hit-compliant-update-addressed-previous-missing-tap-response/"><u>HIT-Compliant Update: Addressed Previous Missing Tap Response</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-effortlessly-formulating-cohesive-skype-chats-across-windowsmac-platforms/"><u>In 2024, Effortlessly Formulating Cohesive Skype Chats Across Windows/Mac Platforms</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-honor-x50-gt-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Honor X50 GT Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Realme C55 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/installing-hp-envy-5530-on-latest-windows-version/"><u>Installing HP Envy 5530 on Latest Windows Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-art-of-configuring-your-hp-printer-on-pcs/"><u>Mastering the Art of Configuring Your HP Printer on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/method-to-forget-your-printer-in-windows/"><u>Method to Forget Your Printer in Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-make-amazing-videos-on-your-mac-top-rated-video-editing-tools/"><u>New Make Amazing Videos on Your Mac Top-Rated Video Editing Tools</u></a></li>
<li><a href="https://printer-issues.techidaily.com/operation-print-device-added-without-issues/"><u>Operation: Print Device Added without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-print-performance-dells-latest-aio-upgrades-in-win7/"><u>Optimize Print Performance: Dell's Latest AIO Upgrades in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-spooler-crashing-strategies-for-win-users/"><u>Overcoming Spooler Crashing: Strategies for Win Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/parting-pleasantries-free-and-paid-outro-snippets/"><u>Parting Pleasantries  Free & Paid Outro Snippets</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-capturer-snappy-windows-snap/"><u>Professional Capturer  Snappy Windows Snap</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-troubleshooting-for-non-printing-canon-printers/"><u>Quick Troubleshooting for Non-Printing Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-prints-install-latest-v305-driver-in-win7/"><u>Revitalize Your Prints: Install Latest V305 Driver in Win7</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/social-laughter-downloaded-iphoneandroid-tutorial-for-gifs-for-2024/"><u>Social Laughter Downloaded  IPhone/Android Tutorial for GIFS for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-print-experience-with-win-hp-printer-guide/"><u>Streamline Your Print Experience with Win HP Printer Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/superior-viewing-experience-essentials-of-4k-downloading/"><u>Superior Viewing Experience  Essentials of 4K Downloading</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-noisy-or-disruptive-printers/"><u>Tackling Noisy or Disruptive Printers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-6-simple-minecraft-house-ideas-for-2024/"><u>Top 6 Simple Minecraft House Ideas for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7810-networking-guide-for-inkjet-hp-issues/"><u>Win7/8/10 Networking Guide for Inkjet HP Issues</u></a></li>
</ul></div>
