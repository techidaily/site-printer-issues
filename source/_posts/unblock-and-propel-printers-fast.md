---
title: Unblock and Propel Printers Fast
date: 2024-08-31T04:36:02.177Z
updated: 2024-09-01T04:36:02.177Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unblock and Propel Printers Fast
excerpt: This Article Describes Unblock and Propel Printers Fast
keywords: Printer Performance Optimization,Printhead Cleaning Tips,Speeding Up Printers,Unblock Cartridge Issue Solutions,Quick Printer Maintenance Tricks,High-Speed Printer Technology,Efficient Printer Setup Techniques
thumbnail: https://thmb.techidaily.com/f495fdc30704bb5311bdcea6bec28c308373dbaff21b69f564e50f099e806a16.jpg
---

## Unblock and Propel Printers Fast

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
<li><a href="https://printer-issues.techidaily.com/fixed-turtle-beach-recon-70-mic-not-working/"><u>[FIXED] Turtle Beach Recon 70 Mic Not Working</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-skyhigh-snapshot-top-5-time-lapse-videos/"><u>[Updated] In 2024, Skyhigh Snapshot - Top 5 Time-Lapse Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-instantly-personalize-your-phones-from-tiktok-sounds-to-ringtones/"><u>[Updated] Instantly Personalize Your Phones  From TikTok Sounds to Ringtones</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-snapseed-101-basic-editing-techniques-unveiled/"><u>[Updated] Snapseed 101  Basic Editing Techniques Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-unavailable-print-error-noted/"><u>Active Directory Unavailable, Print Error Noted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-printer-isolation-brothers-network-recovery-plan/"><u>Avoiding Printer Isolation: Brother's Network Recovery Plan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-watch-dogs-legion-experience-solutions-for-higher-fps-and-less-latency/"><u>Boost Your Watch Dogs: Legion Experience – Solutions for Higher FPS and Less Latency</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-mf4770n-integration-with-win-1087/"><u>Boosting MF4770n Integration with Win 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-the-gap-reactivate-and-recover-from-printer-disconnect/"><u>Bridge the Gap: Reactivate and Recover From Printer Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-non-printing-on-canon-uncover-5-easy-methods-for-windows-11-enthusiasts/"><u>Conquer Non-Printing on Canon - Uncover 5 Easy Methods for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-windows-11-printer-connection-fails/"><u>Correct Windows 11 Printer Connection Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-pcl-xl-hurdles-quickly-and-smoothly/"><u>Decoding PCL XL Hurdles Quickly and Smoothly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/defeating-the-bugs-how-to-handle-and-fix-fortnites-ls-0013-problem/"><u>Defeating the Bugs: How to Handle and Fix Fortnite's LS-0013 Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disconnect-printer-reconnect-windows-easily/"><u>Disconnect Printer, Reconnect Windows Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-data-cleansing-with-the-stellar-eraser-the-ultimate-mac-and-mobile-solution/"><u>Effortless Data Cleansing with the Stellar Eraser: The Ultimate Mac and Mobile Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-elimination-windows-printer-setback-0x00000709/"><u>Error Elimination: Windows Printer Setback (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-system-interrupt-controller-driver-issue-solved/"><u>Fix System Interrupt Controller Driver Issue [Solved]</u></a></li>
<li><a href="https://driver-download.techidaily.com/fix-your-bluetooth-issues-with-mpows-updated-drivers-for-windows-10-8-and-7-download-now/"><u>Fix Your Bluetooth Issues with MPOW's Updated Drivers for Windows 10, 8, and 7 - Download Now</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-honor-100-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-delete-inactive-printers-in-windows-easy-way/"><u>How To Delete Inactive Printers in Windows Easy Way</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-stop-assassins-creed-valhalla-from-frequently-crashing-on-your-computer/"><u>How to Stop Assassin's Creed: Valhalla From Frequently Crashing on Your Computer</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-infinix-zero-30-5g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Infinix Zero 30 5G Easily?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-8-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone 8</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastery-of-video-dimensions-achieving-balanced-facebook-posts-for-2024/"><u>Mastery of Video Dimensions  Achieving Balanced Facebook Posts for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimized-installation-process-hp-officejet-pro-8600-windows-driver/"><u>Optimized Installation Process: HP OfficeJet Pro 8600 Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-printer-disconnection-challenges/"><u>Overcoming Printer Disconnection Challenges</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-sound-from-laptop-audio-internal-speakers-step-by-step-tips/"><u>Reviving Sound From Laptop Audio Internal Speakers – Step-by-Step Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printing-setup-for-hp-and-laptops-immediate-solutions/"><u>Seamless Printing Setup for HP & Laptops - Immediate Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-repairs-for-common-winwordexe-application-glitches-a-step-by-step-guide/"><u>Simple Repairs for Common WINWORD.EXE Application Glitches - A Step-by-Step Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-iphones-cellular-data-issues-top-10-quick-fixes/"><u>Solving iPhone's Cellular Data Issues: Top 10 Quick Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-audio-issues-configuring-new-speakers-on-windows-10/"><u>Troubleshooting Audio Issues: Configuring New Speakers on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-guide-resolving-discord-streaming-disruptions/"><u>Troubleshooting Guide: Resolving Discord Streaming Disruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unused-printer-new-machine-alert/"><u>Unused Printer: New Machine Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-rev-fixes-resurrected-non-printing-printer/"><u>Win11 Rev Fixes: Resurrected Non-Printing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-offline-printer-back-online/"><u>Win7 Offline Printer Back Online</u></a></li>
</ul></div>
