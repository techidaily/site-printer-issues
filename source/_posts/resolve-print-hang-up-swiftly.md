---
title: Resolve Print Hang-Up Swiftly
date: 2024-08-15T03:16:41.801Z
updated: 2024-08-16T03:16:41.801Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve Print Hang-Up Swiftly
excerpt: This Article Describes Resolve Print Hang-Up Swiftly
keywords: Quick Printer Troubleshooting,Fixing Print Errors Fast,Resolve Print Issues Rapidly,Immediate Solutions For Print Problems,Speedy Fixes for Hanging Prints,Efficient Print Fault Remedies,Swift Resolution of Print Hang-Ups
thumbnail: https://thmb.techidaily.com/3631238ca7c06e0c64e4d00a9d13c9e8220b196fb6f2fa2e2f0075e18f87eaf2.jpg
---

## Resolve Print Hang-Up Swiftly

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
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-lab.techidaily.com/n-2024-crafting-an-impactful-online-presence-with-perfect-yt-dimensions/"><u>[New] In 2024, Crafting an Impactful Online Presence with Perfect YT Dimensions</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-art-of-revisiting-historical-facebook-posts-mobilelaptop/"><u>[New] In 2024, The Art of Revisiting Historical Facebook Posts (Mobile/Laptop)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-three-ways-to-make-your-instagram-videos-pop-with-captions/"><u>[New] Three Ways to Make Your Instagram Videos Pop with Captions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-comprehensive-guide-to-embedding-youtube-playlists-online/"><u>[Updated] 2024 Approved  Comprehensive Guide to Embedding YouTube Playlists Online</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-everlasting-deactivation-tactics-against-youtubes-sneaky-snack/"><u>[Updated] 2024 Approved  Everlasting Deactivation Tactics Against YouTube's Sneaky Snack</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-innovative-techniques-to-enhance-your-obs-broadcasts-android/"><u>[Updated] 2024 Approved  Innovative Techniques to Enhance Your OBS Broadcasts (Android)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-iconic-scripts-that-reshaped-cinemas-landscape/"><u>2024 Approved  Iconic Scripts That Reshaped Cinema's Landscape</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-pinnacle-of-picture-quality-best-players-24/"><u>2024 Approved  The Pinnacle of Picture Quality  Best Players '24</u></a></li>
<li><a href="https://printer-issues.techidaily.com/all-page-printer-issues-resolved/"><u>All-Page Printer Issues Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-standby-mode-glitch/"><u>Corrected Standby Mode Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/duplicate-device-printing-discovered-and-tackled/"><u>Duplicate Device Printing Discovered & Tackled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-velocity-now/"><u>Enhance Printer Velocity Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-a-printer-that-wont-print/"><u>How to Fix a Printer That Won't Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-install-a-new-canon-printer-step-by-step/"><u>How To Install a New Canon Printer (Step-by-Step)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-react-when-your-printer-disconnects/"><u>How to React When Your Printer Disconnects</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-xiaomi-mix-fold-3-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Xiaomi Mix Fold 3 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-honor-v-purse-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Honor V Purse via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-15-pro-max-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 15 Pro Max When You Forget the Passcode?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-6s-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 6s 3 Ways To Unlock</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-windows-11-printer-work-again/"><u>Make Windows 11 Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/maximize-mf4770n-in-windows-1087-systems/"><u>Maximize MF4770n in WIndows 10/8/7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigate-and-rectify-brother-printer-not-print-issue-on-windows-10/"><u>Navigate and Rectify Brother Printer Not Print Issue on Windows 10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/next-gen-cuts-select-best-6-video-editing-apps-for-mac-big-sur-for-2024/"><u>Next-Gen Cuts  Select Best 6 Video Editing Apps for Mac Big Sur for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcoming-the-challenge-of-microsoft-word-file-accessibility-problems/"><u>Overcoming the Challenge of Microsoft Word File Accessibility Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overhauling-hp-printers-error-code-oxc4eb827f/"><u>Overhauling HP Printer's Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-showing-up-a-guide-for-windows-users/"><u>Printer Not Showing Up: A Guide for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-due-to-domain-service-outage/"><u>Printer Problem Due to Domain Service Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-printer-driver-glitches-on-win10-pc/"><u>Repair Printer Driver Glitches on WIN10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-error-in-epsons-print-function/"><u>Repaired: Error in Epson's Print Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-reports-with-paper-less-prints/"><u>Revolutionizing Reports with Paper-Less Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/saving-photo-printouts-from-failures/"><u>Saving Photo Printouts From Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-unlink-external-hardware-from-windows-os/"><u>Steps to Unlink External Hardware From Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-and-tricks-connecting-your-canon-instantly/"><u>Tips & Tricks: Connecting Your Canon Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-printer-service-on-windows-10-11-7/"><u>Unblocking Printer Service on Windows 10, 11, 7</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-2024-approved-the-most-efficient-tools-to-convert-text-to-mp3-with-the-best-natural-voices/"><u>Updated 2024 Approved The Most Efficient Tools to Convert Text to MP3 With the Best Natural Voices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-get-started-with-mp4-video-editing-a-friendly-tutorial-for-mac-and-windows-beginners/"><u>Updated Get Started with MP4 Video Editing A Friendly Tutorial for Mac and Windows Beginners</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-print-problem-devices-unresponsive-post-sleep/"><u>Win7 Print Problem: Devices Unresponsive Post-Sleep</u></a></li>
</ul></div>
