---
title: Accelerate Clearing Print Job Queue
date: 2024-08-22T09:40:47.511Z
updated: 2024-08-23T09:40:47.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Clearing Print Job Queue
excerpt: This Article Describes Accelerate Clearing Print Job Queue
keywords: Accelerated Print Job Processing,Print Job Queue Optimization,High-Speed Print Job Management,Rapid Printing Solutions,Print Queue Acceleration Techniques,Efficient Print Job Prioritization,Streamline Print Management
thumbnail: https://thmb.techidaily.com/4e313b1018e0c2499cbd20182728d1887cb747f9b7e2192f6f1e12c2015f85ae.jpg
---

## Accelerate Clearing Print Job Queue

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
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/driver-search-failure-cannot-locate-mp620-driver-on-windows-10/"><u>[Driver Search Failure] Cannot Locate MP620 Driver on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-missing-printer-driver-in-win/"><u>[ISSUE] Missing Printer Driver in Win</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-harmony-in-transit-relocating-your-loved-songs/"><u>[New] 2024 Approved  Harmony in Transit  Relocating Your Loved Songs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-instagram-edge-vertical-footage-editing-techniques-on-final-cut-x/"><u>[New] 2024 Approved  The Instagram Edge  Vertical Footage Editing Techniques on Final Cut X</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-your-content-with-these-top-keyword-discovery-tools-for-2024/"><u>[New] Elevate Your Content with These Top Keyword Discovery Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-from-front-to-back-and-back-again-the-insta-rotation-ritual-for-success/"><u>[New] In 2024, From Front to Back, and Back Again  The Insta Rotation Ritual for Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-11/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-leaders-designing-ultra-realistic-virtual-worlds/"><u>[Updated] 2024 Approved  Leaders Designing Ultra-Realistic Virtual Worlds</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-streamline-and-stand-out-twitters-video-directive/"><u>[Updated] 2024 Approved  Streamline and Stand Out  Twitter's Video Directive</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-generating-a-signature-tiktok-keyphrase/"><u>[Updated] Generating a Signature TikTok Keyphrase</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-first-time-furnishings-minimalist-house-plans-in-mc/"><u>[Updated] In 2024, First-Time Furnishings  Minimalist House Plans in MC</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-mastering-motion-control-top-camera-gadgets/"><u>[Updated] Mastering Motion Control - Top Camera Gadgets</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-step-by-step-inserting-chapters-in-vimeo-videos-for-2024/"><u>[Updated] Step-by-Step  Inserting Chapters in Vimeo Videos for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024-update-printers-prints-every-page/"><u>2024 Update: Printers Prints Every Page</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bypass-the-hurdles-correcting-error-code-10-on-your-steam-game-disks/"><u>Bypass the Hurdles: Correcting Error Code 10 on Your Steam Game Disks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connection-guide-integrating-hp-printer-with-pc-network/"><u>Connection Guide: Integrating HP Printer with PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-when-print-devices-go-offline/"><u>Connectivity Woes: When Print Devices Go Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrective-measures-in-place-for-hp-printers-blanks/"><u>Corrective Measures in Place for HP Printer's Blanks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://tech-revival.techidaily.com/demystifying-the-technology-behind-gpt-4all-insights-into-its-design-and-operation/"><u>Demystifying the Technology Behind GPT- 4All: Insights Into Its Design and Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-0x97-unravelled-and-solved/"><u>Epson 0X97 - Unravelled & Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-hp-printer-error-oxc4eb827f/"><u>Eradicating HP Printer Error OXC4EB827F</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/grasping-the-essentials-of-english-grammar-a-focus-on-contractions/"><u>Grasping the Essentials of English Grammar: A Focus on Contractions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-honor-play-40c-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Honor Play 40C Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-x-keeps-asking-for-outlook-password-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone X Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructions-installing-hp-officejet-on-pc-interface/"><u>Instructions: Installing HP Officejet on PC Interface</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/linux-on-chrome-os-a-step-by-step-installation-guide-updated-2023/"><u>Linux on Chrome OS A Step-by-Step Installation Guide (Updated 2023)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-canon-wi-fi-connection-process/"><u>Mastering the Canon-Wi-Fi Connection Process</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-that-can-handle-full-document-sizes/"><u>Printers That Can Handle Full Document Sizes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-print-no-hassle-method/"><u>Reconnect Print: No Hassle Method</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-print-job-failures-on-windows-11/"><u>Rectify Print Job Failures on Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/remove-device-supervision-from-your-apple-iphone-se-by-drfone-ios/"><u>Remove Device Supervision From your Apple iPhone SE</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-offline-print-slot/"><u>Repaired Offline Print Slot</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-install-errors/"><u>Resolved Printer Install Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-link-your-hp-officejet-pro-wirelessly/"><u>Tutorial: Link Your HP Officejet Pro Wirelessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-and-mp620-printer-wheres-the-compatibility/"><u>Win11 & MP620 Printer: Where's the Compatibility?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-out-error-0x97-in-epson-units/"><u>Zeroing Out Error 0X97 in Epson Units</u></a></li>
</ul></div>
