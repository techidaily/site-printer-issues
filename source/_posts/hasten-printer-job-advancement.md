---
title: Hasten Printer Job Advancement
date: 2024-08-08T01:10:27.139Z
updated: 2024-08-09T01:10:27.139Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Hasten Printer Job Advancement
excerpt: This Article Describes Hasten Printer Job Advancement
keywords: Accelerate Inkjet Printing Processes,Advance Printer Technology Speed,Increase Print Job Efficiency,Optimize Printer Operation Speed,Fast-Track Print Technology Development,Enhance Printer Speed & Performance,Improve Print Job Turnaround Time
thumbnail: https://thmb.techidaily.com/dbfa6019d8b3f211a2d4346989a8be20fa1fb2520363f53adb487ff9f78fd127.jpg
---

## Hasten Printer Job Advancement

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
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
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-mastering-your-slide-show-webcam-screen-capture-methods/"><u>[Updated] 2024 Approved  Mastering Your Slide Show  Webcam Screen Capture Methods</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-discover-the-ultimate-affordable-tool-to-transform-your-valorant-gameplay-for-2024/"><u>[Updated] Discover the Ultimate, Affordable Tool to Transform Your Valorant Gameplay for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-accelerated-attention-on-instagram-the-like-video-method/"><u>[Updated] In 2024, Accelerated Attention on Instagram - The Like-Video Method</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfecting-the-synergy-of-visuals-and-voiceovers-in-videos/"><u>[Updated] Perfecting the Synergy of Visuals and Voiceovers in Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/15-pioneering-youtube-tutorials-for-flawless-product-reviews-for-2024/"><u>15 Pioneering YouTube Tutorials for Flawless Product Reviews for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-nokia-g42-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Nokia G42 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-epsons-error-x97/"><u>Addressing Epson's Error X97</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-vega-64-driver-update-steps-to-fix-compatibility-on-windows-devices-solved/"><u>AMD Vega 64 Driver Update: Steps to Fix Compatibility on Windows Devices [SOLVED]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-dormant-printers/"><u>Dealing with Dormant Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/defeating-paper-jams-fixing-spooler-issues-win-1011/"><u>Defeating Paper Jams: Fixing Spooler Issues (Win 10/11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantle-disconnection-get-your-printer-printing-again/"><u>Dismantle Disconnection: Get Your Printer Printing Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-manage-hp-officejet-4630-updates/"><u>Efficiently Manage HP Officejet 4630 Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Xiaomi Civi 3 Disney 100th Anniversary Edition? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-print-sentry-refuses-responses/"><u>My Print Sentry Refuses Responses</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-methods-quickly-connect-hp-to-laptops/"><u>New Methods: Quickly Connect HP to Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-brother-printer-print-failures-on-windows-systems/"><u>Overcome Brother Printer Print Failures on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-service-restored-in-win7/"><u>Print Service Restored in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-steps-to-setup-canon-printer-in-pictures/"><u>Quick Steps to Setup - Canon Printer in Pictures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rejuvenate-your-mf4770n-experience-for-win11-8-7/"><u>Rejuvenate Your MF4770n Experience for Win11, 8, 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-inkjet-driver-errors-on-w11/"><u>Solve Inkjet Driver Errors on W11</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/spooler-error-printer-not-initializing-in-windows/"><u>Spooler Error: Printer Not Initializing in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-canon-printer-wi-fi-installation/"><u>Step-by-Step Canon Printer Wi-Fi Installation</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-fun-girl-games-for-kids-for-2024/"><u>Top Fun Girl Games for Kids for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-hidden-cause-of-blank-printouts/"><u>Unveiling the Hidden Cause of Blank Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win32-officejet-pro-8600-printer-installation-file/"><u>Win32 Officejet Pro 8600 Printer Installation File</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-xp-non-responsive-printer-issue-resolved/"><u>Windows XP: Non-Responsive Printer Issue Resolved</u></a></li>
</ul></div>
