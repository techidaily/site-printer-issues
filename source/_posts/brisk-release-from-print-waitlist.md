---
title: Brisk Release From Print Waitlist
date: 2024-08-15T03:15:11.637Z
updated: 2024-08-16T03:15:11.637Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Brisk Release From Print Waitlist
excerpt: This Article Describes Brisk Release From Print Waitlist
keywords: Brisk Print Release,Print Waitlist Removal,Fast Printing Service,Printer Access Fast Track,Quick Booking and Printing,Expedited Printing Solutions,Express Publishing Services
thumbnail: https://thmb.techidaily.com/77d2b3ef679b5fcf16ae0f3446de13ba438b3d48f4673334fb3a900060d9f0bc.jpg
---

## Brisk Release From Print Waitlist

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
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
<li><a href="https://printer-issues.techidaily.com/alert-windows-10-print-queue-offline/"><u>[ALERT] Windows 10: Print Queue Offline</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-comprehensive-list-of-leading-no-cost-video-chat-apps-iosandroid/"><u>[New] Comprehensive List of Leading No-Cost Video Chat Apps (iOS/Android)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-cutting-edge-approaches-to-in-game-auditory-logging-for-2024/"><u>[New] Cutting-Edge Approaches to In-Game Auditory Logging for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-breakthrough-techniques-for-online-audio-archiving-and-editing/"><u>[Updated] In 2024, Breakthrough Techniques for Online Audio Archiving & Editing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-learn-the-solution-to-instagram-video-issues-for-2024/"><u>[Updated] Learn the Solution to Instagram Video Issues for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-hottest-youtube-music-playback-responses-23/"><u>2024 Approved  Hottest YouTube Music Playback Responses '23</u></a></li>
<li><a href="https://tech-haven.techidaily.com/7-smart-alternatives-to-chatgpt-apps-for-smartphones/"><u>7 Smart Alternatives to ChatGPT Apps for Smartphones</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574142393-cant-remove-printer-on-windows-solved/"><u>Can’t Remove Printer on Windows [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-page-queue-in-hp-printer-errors/"><u>Clearing Page Queue in HP Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-solve-offline-canon-printer-issues/"><u>Connectivity Woes? Solve Offline Canon Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-the-non-print-on-canon-here-are-your-top-5-fixes-for-windows-11-users/"><u>Eliminate the Non-Print on Canon - Here Are Your Top 5 Fixes for Windows 11 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-epson-misprint-mistake/"><u>Ending Epson Misprint Mistake</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-error-b200/"><u>Eradicated Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-windows-printer-setup-successfully-fixed/"><u>Error 0X00000709: Windows Printer Setup Successfully Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-cascading-error-messages-with-printers/"><u>Fixing Cascading Error Messages with Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/high-performance-drivers-hp-officejet-pro-8600-for-windows-pcs/"><u>High-Performance Drivers: HP Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/honor-magic-5-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Honor Magic 5 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-tecno-pova-5-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Tecno Pova 5 for Free? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-elevating-impact-refined-techniques-in-ppt-presentation-speaking/"><u>In 2024, Elevating Impact  Refined Techniques in PPT Presentation Speaking</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-asus-rog-phone-8-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Asus ROG Phone 8 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-video-editor-battle-is-inshot-reigning-supreme/"><u>In 2024, Top Video Editor Battle  Is InShot Reigning Supreme?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-magic-in-marketing-top-20-keyphrases/"><u>In 2024, Unlocking Magic in Marketing - Top 20 Keyphrases</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-installation-woes-on-windows-11/"><u>MP620 Printer Installation Woes on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-trends-in-technology-3-solutions-connecting-laptops-and-hp-printers/"><u>New Trends in Technology - 3 Solutions Connecting Laptops & HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-job-across-all-printers/"><u>Perfect Print Job Across All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-guided-instructions-your-ultimate-guide-to-hp-printer-installation/"><u>Precision-Guided Instructions: Your Ultimate Guide to HP Printer Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574021414-print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-crisis-averted-zeroing-out-error-0x00000709/"><u>Printer Setup Crisis Averted - Zeroing Out Error (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unwillingness-for-full-color-printing/"><u>Printer's Unwillingness for Full-Color Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconciled-printer-not-responding/"><u>Reconciled: Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-head-alignment-issues-in-w11/"><u>Resolve Print Head Alignment Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-mf4770n-compatibility-in-win1187/"><u>Revitalize Your MF4770n Compatibility in Win11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/social-media-savviness-mastering-4-techniques-to-record-facebook-lives/"><u>Social Media Savviness  Mastering 4 Techniques to Record Facebook Lives</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-in-picture-getting-your-canon-printer-ready/"><u>Step-In-Picture: Getting Your Canon Printer Ready</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-recover-an-offline-print-device-from-network/"><u>Steps to Recover an Offline Print Device From Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-address-sibling-printer-unresponsiveness/"><u>Strategies to Address Sibling Printer Unresponsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/transform-your-gaming-rig-xpg-hybrid-dual-fan-cooler-with-full-liquid-loop-system-handles-up-to-280w-cpus/"><u>Transform Your Gaming Rig: XPG Hybrid Dual-Fan Cooler with Full Liquid Loop System Handles Up to 280W CPUs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshoot-anthem-delays/"><u>Troubleshoot Anthem Delays</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-and-propel-printers-fast/"><u>Unblock and Propel Printers Fast</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-elevate-your-video-game-top-online-editors-for-chromebook/"><u>Updated Elevate Your Video Game Top Online Editors for Chromebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-pages-galore-affected-by-epson-printer/"><u>White Pages Galore: Affected by Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-compatibility-boost-with-mf4770n-update/"><u>Windows Compatibility Boost with MF4770n Update</u></a></li>
</ul></div>
