---
title: Resolve Print Queue Hang-Up Promptly
date: 2024-08-15T03:14:54.697Z
updated: 2024-08-16T03:14:54.697Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve Print Queue Hang-Up Promptly
excerpt: This Article Describes Resolve Print Queue Hang-Up Promptly
keywords: Print Queue Resolution,Immediate Print Queue Fixes,Print Spooler Troubleshooting,Printer Queue Error Resolution,Print System Stability Improvement,Fast Printer Queue Clearance,Prevent Print Queue Crashes
thumbnail: https://thmb.techidaily.com/9ce1efb4d78691d1fda3d25f6e0de4e7036d8fbbf749d1e5f5caf96b519e32e1.png
---

## Resolve Print Queue Hang-Up Promptly

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-unable-to-locate-hp-driver-on-winxo/"><u>[Driver Difficulty] - Unable to Locate HP Driver on WinXO</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-stay-in-the-limelight-how-to-keep-youtube-cc-and-boost-views/"><u>[New] 2024 Approved  Stay in the Limelight  How to Keep YouTube CC and Boost Views</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-usb-printers-not-working-after-sleep-in-windows-7/"><u>[Solved] USB Printers Not Working After Sleep in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-pixma-mp620-drivers-missing-windows-10/"><u>[Update Required] Pixma MP620 Drivers Missing Windows 10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-apowersofts-role-in-screen-capture-analysis-and-comparisons/"><u>[Updated] 2024 Approved  Apowersoft's Role in Screen Capture  Analysis & Comparisons</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-teen-riches-skyrocket-with-viral-video-empire/"><u>[Updated] 2024 Approved  Teen Riches Skyrocket with Viral Video Empire</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-diy-audio-excellence-no-mic-necessary/"><u>[Updated] DIY Audio Excellence  No Mic Necessary</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-10-best-asmr-recorders-for-exceptional-audio-quality/"><u>[Updated] In 2024, 10 Best ASMR Recorders for Exceptional Audio Quality</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-instagram-videos-understanding-time-constraints-for-2024/"><u>[Updated] Mastering Instagram Videos  Understanding Time Constraints for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-srt-file-conversion-simplified-with-os-support/"><u>[Updated] SRT File Conversion Simplified with OS Support</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-of-the-best-smartphone-ready-vr-headset-roundup/"><u>2024 Approved  Best of the Best  Smartphone-Ready VR Headset Roundup</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-mastering-insta-photo-and-video-reposts/"><u>2024 Approved  Mastering Insta Photo & Video Reposts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-transforming-your-video-with-strategic-vimeo-end-screens/"><u>2024 Approved  Transforming Your Video with Strategic Vimeo End Screens</u></a></li>
<li><a href="https://buynow-info.techidaily.com/5-must-have-mice-to-upgrade-your-mac-workstation-a-curated-list/"><u>5 Must-Have Mice to Upgrade Your Mac Workstation : A Curated List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-printer-output-immediately/"><u>Accelerate Printer Output Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addsvc-not-responding-printer-error-reported/"><u>ADDSVC Not Responding: Printer Error Reported</u></a></li>
<li><a href="https://facebook.techidaily.com/balancing-your-fb-friends-list-unfollow-and-follow-dynamics-explained/"><u>Balancing Your FB Friends List: Unfollow & Follow Dynamics Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574003773-canon-printer-is-offline-heres-how-to-fix-it/"><u>Canon Printer Is Offline? Here's How to Fix It!</u></a></li>
<li><a href="https://facebook.techidaily.com/cross-platform-content-posting-instagram-reels-to-facebook/"><u>Cross-Platform Content: Posting Instagram Reels to Facebook</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/efficiently-implementing-youtube-end-screens-for-2024/"><u>Efficiently Implementing Youtube End Screens for 2024</u></a></li>
<li><a href="https://media-tips.techidaily.com/effortlessly-transform-videos-for-mobile-devices-android-smartphones-and-tablets/"><u>Effortlessly Transform Videos for Mobile Devices (Android Smartphones & Tablets)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-no-more-windows-7/"><u>Epson Printer Offline No More, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-the-epson-fix/"><u>Error Code 0X97: The Epson Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-windows-11-support-for-mp620-printer/"><u>Finding Windows 11 Support for MP620 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printer-driver-issues-on-windows-10/"><u>Fix Printer Driver Issues on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-printer-service-spooler-issues/"><u>Fixing Non-Operational Printer Service (Spooler) Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/glitch-overcome-visuals-preserved-and-stable/"><u>Glitch Overcome: Visuals Preserved and Stable</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-infinix-gt-10-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Infinix GT 10 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-prevent-print-service-interruptions-on-w7w10w11/"><u>How to Prevent Print Service Interruptions on W7/W10/W11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-infinix-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Infinix</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-iphone-12-imei-checker-by-drfone-ios/"><u>In 2024, Best Free iPhone 12 IMEI Checker</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-honor-magic-6-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Honor Magic 6 Face Lock?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-highest-quality-gag-editor/"><u>In 2024, Highest Quality Gag Editor</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a18-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A18 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-fixes-for-epson-error-0x97/"><u>Mastering Fixes for Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-installation-of-canon-print-devices/"><u>Mastering the Installation of Canon Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-paper-jamming-concern/"><u>Mended Paper Jamming Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-pcl-xl-complications-swiftly/"><u>Navigating PCL XL Complications Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-setup-of-hp-envy-printers/"><u>Navigating the Setup of HP Envy Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-printer-support-package-windows-based/"><u>Officejet Pro 8600 Printer Support Package, Windows-Based</u></a></li>
<li><a href="https://hardware-help.techidaily.com/official-logitech-gaming-steering-wheel-get-your-gt-driving-force-download-compatible-with-win7win10win11/"><u>Official Logitech Gaming Steering Wheel: Get Your GT Driving Force Download Compatible with Win7/Win10/Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-windows-rapid-photo-displayer-for-2024/"><u>Prime Window's Rapid Photo Displayer for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-dilemma-ends-after-new-windows-installation/"><u>Print Dilemma Ends After New Windows Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-like-a-pro-3-upgrades-to-link-your-printer-and-laptop-seamlessly/"><u>Print Like a Pro: 3 Upgrades to Link Your Printer & Laptop Seamlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-issue-not-showing-up-in-win-810/"><u>Printer Issue: Not Showing Up in Win 8/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-mysterious-setup-error/"><u>Printer Puzzle: Mysterious Setup Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-hook-up-your-hp-officejet-pro-duo/"><u>Quick Guide: Hook Up Your HP Officejet Pro Duo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-link-functional-print-device/"><u>Quick Link: Functional Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-efficient-data-flow-for-printers/"><u>Restoring Efficient Data Flow for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-networked-printer-access/"><u>Revived Networked Printer Access</u></a></li>
<li><a href="https://fox-blue.techidaily.com/shades-of-success-color-grading-fundamentals/"><u>Shades of Success  Color Grading Fundamentals</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-stalled-printer-tasks/"><u>Speed Up Stalled Printer Tasks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-solutions-to-printer-delays/"><u>Swift Solutions to Printer Delays</u></a></li>
<li><a href="https://printer-issues.techidaily.com/synchronize-printer-settings-across-multiple-devices-win10-style/"><u>Synchronize Printer Settings Across Multiple Devices, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turbocharge-printer-operations/"><u>Turbocharge Printer Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-hp-printer-setup-manual/"><u>Win HP Printer Setup Manual</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-7-printer-repaired/"><u>Windows 7 Printer Repaired</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/zte-nubia-flip-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>ZTE Nubia Flip 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
</ul></div>
