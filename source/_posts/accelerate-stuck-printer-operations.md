---
title: Accelerate Stuck Printer Operations
date: 2024-08-15T03:17:00.210Z
updated: 2024-08-16T03:17:00.210Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Stuck Printer Operations
excerpt: This Article Describes Accelerate Stuck Printer Operations
keywords: Accelerating Printer Issues,Resolve Stuck Print Head,Fix Jammed Toner Cartridge,Speeding Up Slow Printers,Overcoming Printer Freezes,Improving Print Speed,Troubleshooting HP Printer Problems
thumbnail: https://thmb.techidaily.com/2a9cc8bf4d555df620abafcb570dcc2752e8e2040a84b647ff438519a4be3866.jpg
---

## Accelerate Stuck Printer Operations

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
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
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

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-preserving-your-virtual-sessions-gotomeeting-tips/"><u>[New] 2024 Approved  Preserving Your Virtual Sessions  GoToMeeting Tips</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-experience-a-bundle-of-9-whole-film-christmas-treasures-for-free/"><u>[New] In 2024, Experience a Bundle of 9 Whole-Film Christmas Treasures for Free</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-vimeo-earnings-unlocked-strategies-for-content-creators-for-2024/"><u>[New] Vimeo Earnings Unlocked  Strategies for Content Creators for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-not-printing-in-color/"><u>[SOLVED] Printer Not Printing in Color</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-twitter-archive-mastery-a-guide-to-gif-download-success/"><u>[Updated] In 2024, Twitter Archive Mastery  A Guide to GIF Download Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-windows-narrators-legacy-keyboard-shortcuts/"><u>A Complete Guide to Windows Narrator's Legacy Keyboard Shortcuts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-life-into-your-dying-windows-11-printer/"><u>Breathe Life Into Your Dying Windows 11 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-air-glide-instructions/"><u>Brother CDW Duo Air Glide Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mp620-printer-driver-search-on-win10-unsuccessful/"><u>Canon MP620 Printer Driver Search on WIN10 Unsuccessful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-excellence-a-full-breakdown-of-sj-cam-s6-for-2024/"><u>Capturing Excellence  A Full Breakdown of SJ-CAM S6 for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-the-code-printer-error-x97/"><u>Cracking the Code: Printer Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://win-answers.techidaily.com/cyberpunk-2077-performance-issues-fixed-say-goodbye-to-lag-and-stuttering/"><u>Cyberpunk 2077 Performance Issues Fixed: Say Goodbye to Lag & Stuttering</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-for-windows-print-system/"><u>Driver Search Failed for Windows Print System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-xerox-paper-jam-issues/"><u>Eliminating Xerox Paper Jam Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanned-device-functionality-in-windows-10/"><u>Enable Scanned Device Functionality in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-print-job-responsiveness-on-xp-edition/"><u>Enhance Print Job Responsiveness on XP Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-millennium-xps-sluggish-printer-response/"><u>Fix Windows Millennium XP's Sluggish Printer Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/getting-started-cdw-duo-driver-installation/"><u>Getting Started: CDW Duo Driver Installation</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-iphone-6s-by-drfone-ios/"><u>Guide on How To Remove Apple ID From iPhone 6s</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-successful-driver-installation-for-hp-d1360/"><u>Hardware Setup: Successful Driver Installation for HP D1360?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-8-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-driver-not-detected-by-os/"><u>HP Printer Setup Error: Driver Not Detected by OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-gamers-guidebook-4-proven-strategies-for-gameplay-recordings/"><u>In 2024, Gamer's Guidebook  4 Proven Strategies for Gameplay Recordings</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-xiaomi-14-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Xiaomi 14 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-c55-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme C55 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-xiaomi-redmi-note-13-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Xiaomi Redmi Note 13 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-hp-printer-seamlessly-in-windows-environment/"><u>Integrate HP Printer Seamlessly in Windows Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-releases-dell-v305-driver-and-utility-supports-win7/"><u>New Releases: Dell V305 Driver & Utility Supports Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-jam-no-more-epson-printer-fixed/"><u>Paper Jam No More: Epson Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pixma-mp620-drivers-lost-on-win11-systems/"><u>Pixma MP620 Drivers Lost on Win11 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-printer-setup-guide/"><u>Rapid Printer Setup Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-access-sister-brother-printer-offline-fix-guide/"><u>Regain Access: Sister-Brother Printer Offline Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-scanner-link-to-computer-in-windows-10/"><u>Restore Scanner Link to Computer in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplify-removal-of-wiredwireless-printers/"><u>Simplify Removal of Wired/Wireless Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act</u></a></li>
</ul></div>
