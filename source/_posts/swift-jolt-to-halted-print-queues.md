---
title: Swift Jolt to Halted Print Queues
date: 2024-08-31T04:35:56.398Z
updated: 2024-09-01T04:35:56.398Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swift Jolt to Halted Print Queues
excerpt: This Article Describes Swift Jolt to Halted Print Queues
keywords: Halted Print Queue Fix,Stop Stalled Printers Quickly,Print System Disruption Solutions,Immediate Print Queue Resolution,Printer Queue Jolt Troubleshooting,Print Service Interruption Management,Expediting Halted Print Jobs
thumbnail: https://thmb.techidaily.com/70a221261e83ff3179ef93192d51afbff1f7257579ffa960f9e7a085032e4b04.png
---

## Swift Jolt to Halted Print Queues

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
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
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
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-sharexs-standards-met-by-others/"><u>[New] 2024 Approved  ShareX's Standards Met by Others</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-exclusive-review-of-showmore-authoritative-screen-capture-software/"><u>[New] Exclusive Review of ShowMore’ Authoritative Screen Capture Software</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-your-guide-to-facebook-video-angle-selection/"><u>[Updated] Your Guide to Facebook Video Angle Selection</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-secrets-to-exceptional-tiktok-videos/"><u>2024 Approved  Expert Secrets to Exceptional TikTok Videos</u></a></li>
<li><a href="https://driver-install.techidaily.com/accelerate-updating-logitech-mouse-for-win11-enthusiasts/"><u>Accelerate Updating Logitech Mouse for Win11 Enthusiasts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/amazon-alexa-versus-google-assistant-determining-the-best-personal-digital-assistant-for-you/"><u>Amazon Alexa versus Google Assistant - Determining the Best Personal Digital Assistant for You</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-life-into-your-dying-windows-11-printer/"><u>Breathe Life Into Your Dying Windows 11 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-air-glide-instructions/"><u>Brother CDW Duo Air Glide Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-the-code-printer-error-x97/"><u>Cracking the Code: Printer Error X97</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-mp3s-from-instagram-the-easy-methodology-for-2024/"><u>Crafting Mp3s From Instagram  The Easy Methodology for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-for-windows-print-system/"><u>Driver Search Failed for Windows Print System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-xerox-paper-jam-issues/"><u>Eliminating Xerox Paper Jam Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanned-device-functionality-in-windows-10/"><u>Enable Scanned Device Functionality in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-print-job-responsiveness-on-xp-edition/"><u>Enhance Print Job Responsiveness on XP Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-millennium-xps-sluggish-printer-response/"><u>Fix Windows Millennium XP's Sluggish Printer Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-successful-driver-installation-for-hp-d1360/"><u>Hardware Setup: Successful Driver Installation for HP D1360?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-driver-not-detected-by-os/"><u>HP Printer Setup Error: Driver Not Detected by OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/identified-interloper-on-network-printer/"><u>Identified Interloper on Network Printer</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-vlc-key-mac-functions-explained/"><u>In 2024, Mastering VLC  Key Mac Functions Explained</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfect-pixels-a-guide-to-the-11-best-edits-for-color-balance/"><u>In 2024, Perfect Pixels  A Guide to the 11 Best Edits for Color Balance</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-hp-printer-seamlessly-in-windows-environment/"><u>Integrate HP Printer Seamlessly in Windows Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-jam-no-more-epson-printer-fixed/"><u>Paper Jam No More: Epson Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-printer-setup-guide/"><u>Rapid Printer Setup Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-access-sister-brother-printer-offline-fix-guide/"><u>Regain Access: Sister-Brother Printer Offline Fix Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-12-pro-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplify-removal-of-wiredwireless-printers/"><u>Simplify Removal of Wired/Wireless Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-win10-printer-functionality/"><u>Streamline WIN10 Printer Functionality</u></a></li>
<li><a href="https://extra-information.techidaily.com/streamlining-windows-photos-experience-with-added-filtersmusic/"><u>Streamlining Windows Photos Experience with Added Filters/Music</u></a></li>
</ul></div>
