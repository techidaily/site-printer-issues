---
title: Speedy Clearance of Stalled Print Queue
date: 2024-08-15T03:13:00.336Z
updated: 2024-08-16T03:13:00.336Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speedy Clearance of Stalled Print Queue
excerpt: This Article Describes Speedy Clearance of Stalled Print Queue
keywords: Fast Print Job Resumption,Quick Resolution for Printer Queues,Remediation of Halted Printing Processes,Efficient Handling of Print Queue Issues,Speedy Restoration of Print Service,Immediate Fix for Stalled Print Operations,Rapid Clearance of Printer Queue Backups
thumbnail: https://thmb.techidaily.com/8443124490dd4d26d174966fed147fd5721a9572389508714a7b16fe1b9aa1b0.jpg
---

## Speedy Clearance of Stalled Print Queue

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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://printer-issues.techidaily.com/printer-setup-unable-to-locate-hp-driver-winxo/"><u>[Printer Setup] Unable to Locate HP Driver WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-unable-to-install-printeroperation-could-not-be-completed/"><u>[Solved] Unable to Install Printer.Operation Could Not Be Completed</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unleash-creativity-how-to-elegantly-add-descriptive-elements-in-photos-for-windows-and-macos/"><u>[Updated] Unleash Creativity  How to Elegantly Add Descriptive Elements in Photos for Windows & MacOS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-digital-decoder-masterful-online-tv-recording-methods/"><u>2024 Approved  Digital Decoder  Masterful Online TV Recording Methods</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-maintenance-causing-print-errors/"><u>AD DS Maintenance Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-printer-driver-bugs-in-win10/"><u>Address Printer Driver Bugs in Win10</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-asmr-microphones-with-amazing-performance-and-affordable-price-for-2024/"><u>Best ASMR Microphones with Amazing Performance and Affordable Price for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-the-gap-reactivate-offline-canon-printer/"><u>Bridge the Gap: Reactivate Offline Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-air-glide-instructions-quickly/"><u>Brother CDW Air-Glide Instructions Quickly</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-oppo-find-x6-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Oppo Find X6 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-code-0x00000709-to-fix-default-printer-setup/"><u>Cracking Code 0X00000709 to Fix Default Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-print-job-errors/"><u>Eliminating Ghost Print Job Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-solved/"><u>Epson Printer Offline [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-for-non-operational-post-upgrade-printer/"><u>Fix for Non-Operational Post-Upgrade Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-your-canon-printers-non-print-problem-with-these-top-five-tricks-in-windows-11/"><u>Fix Your Canon Printer's Non-Print Problem with These Top Five Tricks in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-windows-hp-print-link/"><u>Fixing Offline Windows-HP Print Link</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-6-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-of-the-tp-link-archer-c8e-sub-100-wireless-router-with-impressive-speed/"><u>In Depth Analysis of the TP-Link Archer C8e - Sub $100 Wireless Router with Impressive Speed!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/in-depth-installing-and-tweaking-your-hp-printer-on-windows/"><u>In-Depth: Installing and Tweaking Your HP Printer on Windows</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/master-youtube-monetization-tips-to-boost-income-via-shorts/"><u>Master YouTube Monetization  Tips to Boost Income via Shorts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-error-code-b200/"><u>Mended Error Code: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mysterious-print-job-by-secondary-computer/"><u>Mysterious Print Job by Secondary Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-responsive-usb-printers-in-win7-after-hibernate/"><u>Non Responsive USB Printers in Win7 After Hibernate</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-successful/"><u>Printer Setup: Successful</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/quick-retrieval-downloading-gifs-from-twitter-apps-for-2024/"><u>Quick Retrieval  Downloading GIFs From Twitter Apps for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reigniting-your-silent-printer/"><u>Reigniting Your Silent Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-windows-7-printer-unresponsive/"><u>Resolved: Windows 7 Printer Unresponsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-white-paper-output-on-hp-printer/"><u>Resolving White Paper Output on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-connected-status-to-siblings-print-device/"><u>Restoring Connected Status to Sibling's Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-scanner-activation-for-win10-users/"><u>Restoring Scanner Activation for Win10 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-scan-to-computer-is-no-longer-activated-on-windows-10/"><u>Solved: Scan to Computer Is No Longer Activated on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steering-clear-obstacles-onboard-brother-printer-again/"><u>Steering Clear Obstacles: Onboard Brother Printer Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-remedy-for-queued-printer-issue/"><u>Swift Remedy for Queued Printer Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-mishap-printer-setup-misstep/"><u>Technical Mishap: Printer Setup Misstep!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-iphone-photography-playbook-for-2024/"><u>The Ultimate iPhone Photography Playbook for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-guide-to-solving-lego-star-wars-the-skywalker-saga-pc-issues-2024-edition/"><u>Ultimate Guide to Solving LEGO Star Wars: The Skywalker Saga PC Issues - 2024 Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-inkjet-fix-successful/"><u>Win7 Inkjet Fix Successful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-printer-setup-for-efficient-home-office-with-hp/"><u>Wireless Printer Setup for Efficient Home Office with HP</u></a></li>
</ul></div>
