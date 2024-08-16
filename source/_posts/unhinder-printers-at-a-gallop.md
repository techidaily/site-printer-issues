---
title: Unhinder Printers at a Gallop
date: 2024-08-15T03:13:08.403Z
updated: 2024-08-16T03:13:08.403Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unhinder Printers at a Gallop
excerpt: This Article Describes Unhinder Printers at a Gallop
keywords: "Identify Key Concepts in the Title,Expand These Keywords Into Related Terms and Long-Tail Phrases:,Analyze Potential Keyword Competition,Unhindered Printers,High-Speed Printers,Streamlined Printing Process,Optimal Printer Performance,Galloping Efficiency,Printer Acceleration Technology,Fast-Paced Printing Solutions"
thumbnail: https://thmb.techidaily.com/46bc9e67353768ac792e1534a64f3c2875130c736cfcb08614e4c3a629de687e.jpg
---

## Unhinder Printers at a Gallop

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
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
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
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/compatibility-canon-pixma-mp620-and-windows-11-clash/"><u>[Compatibility] Canon Pixma MP620 and Windows 11 Clash</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixation-local-network-printer-spooler-stuck/"><u>[FIXATION] Local Network Printer Spooler Stuck</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-androids-expert-choice-for-quick-vid-boosting/"><u>[New] Android's Expert Choice for Quick Vid Boosting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-mp620-not-recognized-by-windows/"><u>[Update Required] MP620 Not Recognized by Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-seamless-social-streams-link-instagram-and-facebook/"><u>[Updated] 2024 Approved  Seamless Social Streams  Link Instagram & Facebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/acancel-free-setup-for-wi-fi-connected-printers/"><u>Acancel-Free Setup for Wi-Fi Connected Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/beginners-guide-to-setting-up-a-canon-printer-with-images/"><u>Beginner's Guide to Setting up a Canon Printer (with Images)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ubscribers-wisely-watch-your-numbers-soar-in-2024/"><u>Buy Subscribers Wisely, Watch Your Numbers Soar, In 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-resolution-achieved/"><u>Code B200 Resolution Achieved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquering-the-blank-page-battlefield-for-printers/"><u>Conquering the Blank Page Battlefield for Printers</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-motorola-moto-g24-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Motorola Moto G24 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-xiaomi-redmi-a2plus-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Xiaomi Redmi A2+</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-endless-white-paper-output/"><u>Epson Photo Printer: Endless White Paper Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-mfc-9330-cdw-up-and-running/"><u>Get Your MFC-9330 CDW Up and Running</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-oneplus-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on OnePlus</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-107-solved/"><u>HP Printer Offline Status on Windows 10/7 [Solved]</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-smartest-ways-to-track-wedding-dates-ios-and-android-style/"><u>In 2024, Smartest Ways to Track Wedding Dates, iOS & Android Style</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-pdf-digestion-with-chatgpt-discover-these-4-techniques/"><u>Mastering PDF Digestion with ChatGPT: Discover These 4 Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-hp-printer-setup-wizards-in-windows/"><u>Navigating Through HP Printer Setup Wizards in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-white-pages-a-printers-triumph-story/"><u>No More White Pages: A Printer's Triumph Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/offline-printer-status-solved-win7-hp-troubleshooting-guide/"><u>Offline Printer Status Solved: Win7 HP Troubleshooting Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-stops-printing-post-win11-installation/"><u>Printer Stops Printing Post Win11 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-connect-protocol-printer-online/"><u>Quick Connect Protocol: Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-incompatible-printer-drivers-for-hp-d1360-in-windows/"><u>Resolving Incompatible Printer Drivers for HP D1360 in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-response-from-networked-printer/"><u>Resolving No Response From Networked Printer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-future-of-gaming-comprehensive-info-on-xboxs-upcoming-virtual-reality-set-up-price-and-specs-inside/"><u>The Future of Gaming: Comprehensive Info on Xbox's Upcoming Virtual Reality Set-Up – Price and Specs Inside!</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-zeoid-startups-revealed-in-panzoids-for-2024/"><u>Top Zeoid Startups Revealed in Panzoids for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-dell-aio-printer-software-in-windows-7/"><u>Upgrade: Dell AIO Printer Software in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/whiteout-printing-issue-plaguing-my-epson-model/"><u>Whiteout Printing Issue Plaguing My Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-my-printer-skips-colors/"><u>Why My Printer Skips Colors?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-117-fix-for-non-responsive-printer-spooler/"><u>Win 11/7 Fix for Non-Responsive Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt-reactivate-sluggish-uncooperative-printer/"><u>WinNT: Reactivate Sluggish, Uncooperative Printer</u></a></li>
</ul></div>
