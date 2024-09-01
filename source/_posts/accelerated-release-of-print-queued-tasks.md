---
title: Accelerated Release of Print Queued Tasks
date: 2024-08-31T04:39:23.784Z
updated: 2024-09-01T04:39:23.784Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerated Release of Print Queued Tasks
excerpt: This Article Describes Accelerated Release of Print Queued Tasks
keywords: Print Job Scheduling,Rapid Print Processing,Print Queue Optimization,Accelerated Print Workflows,Print Task Release Enhancement,Enhanced Print Queue Management,Faster Printer Task Execution
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Accelerated Release of Print Queued Tasks

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
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
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
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
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
<li><a href="https://printer-issues.techidaily.com/alert-local-print-queue-not-running/"><u>[ALERT] Local Print Queue Not Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-usb-printers-ignoring-command-in-windows-7-mode/"><u>[Fix] USB Printers Ignoring Command in Windows 7 Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-guide-reconnect-missing-print-devices-windows-xp-7-10/"><u>[Network Guide] Reconnect Missing Print Devices Windows-XP-7-10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-analyzing-view-count-to-cash-out-on-youtube/"><u>[New] 2024 Approved  Analyzing View Count to Cash Out on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-top-5-affordable-gaming-mice-and-keyboards-99plus/"><u>[New] 2024 Approved  Top 5 Affordable Gaming Mice & Keyboards $99+</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-video-traffic-triumph-key-youtube-seo-tools/"><u>[New] 2024 Approved  Video Traffic Triumph - Key YouTube SEO Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-breathtaking-judgment-and-variant-proposals/"><u>[New] Breathtaking Judgment & Variant Proposals</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-top-10-stealthy-story-audiences/"><u>[New] In 2024, The Top 10 Stealthy Story Audiences</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-lights-play-our-picks-for-the-top-10-photographic-lenses/"><u>[New] Light's Play  Our Picks for The Top 10 Photographic Lenses</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-needed-unable-to-install-hp-d1360-drivers-in-windows-environments/"><u>[Update Needed] Unable to Install HP D1360 Drivers in Windows Environments</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-discover-best-android-picture-tools/"><u>[Updated] 2024 Approved  Discover Best Android Picture Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-delving-into-youtubes-complex-calculation-of-viewer-stats/"><u>[Updated] In 2024, Delving Into YouTube's Complex Calculation of Viewer Stats</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-tips-to-prevent-audio-loss-in-live-obs-recording-for-2024/"><u>[Updated] Tips to Prevent Audio Loss in Live OBS Recording for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-spooler-error-affects-print-output/"><u>[WARNING] Spooler Error Affects Print Output</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-least-expensive-skyvault-service-for-big-files/"><u>2024 Approved  The Least Expensive SkyVault Service for Big Files</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-installation-of-wi-fi-adapter-on-desktop-computers-tutorial-guide/"><u>Easy Installation of Wi-Fi Adapter on Desktop Computers - Tutorial Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-steps-for-brothers-printer-resuming-normalcy-online/"><u>Easy Steps for Brother's Printer Resuming Normalcy Online</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723862793164-epic-deal-alert-experience-immersive-gameplay-on-a-240-hz-159-acer-nitro-monitor/"><u>Epic Deal Alert: Experience Immersive Gameplay on a 240 Hz, $159 Acer Nitro Monitor!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-queue-error-messages-on-windows-11/"><u>Fix Printing Queue Error Messages on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-0x00000709-on-printer-selection-in-windows/"><u>Fixed Error 0X00000709 on Printer Selection in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-locate-missing-print-server-device/"><u>How to Locate Missing Print Server Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-upgrade-instructions/"><u>HP Printer Driver, Upgrade Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-failure-canon-pixma-mp620-driver-missing-in-win10/"><u>Installation Failure: Canon Pixma MP620 Driver Missing in WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-free-up-print-queue/"><u>Instantly Free Up Print Queue</u></a></li>
<li><a href="https://win11.techidaily.com/keep-top-spot-for-note-taking-on-win-1011-oses/"><u>Keep Top Spot for Note Taking on Win 10/11 OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-error-correction/"><u>Mastering Printer Error Correction</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/meta-quest-3-revealed-comprehensive-overview-of-specs-expected-release-date-and-price-points/"><u>Meta Quest 3 Revealed - Comprehensive Overview of Specs, Expected Release Date, and Price Points</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-non-responsive-hp-devices/"><u>Methods to Reactivate Non-Responsive HP Devices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-get-ready-to-play-top-10-best-free-game-download-sites-for-pc-and-android-devices-for-2024/"><u>New Get Ready to Play Top 10 Best Free Game Download Sites for PC and Android Devices for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/nozzle-clog-in-hp-printer-cleared-successfully/"><u>Nozzle Clog in HP Printer Cleared Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-post-update-fix/"><u>Printer Error Post-Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-recognized-missing-hp-drivers-on-win1011/"><u>Printer Not Recognized: Missing HP Drivers on Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-reboot-no-more-error-after-windows-10-patch/"><u>Printer Reboot, No More Error After Windows 10 Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubles-resolved-windows-11-guide/"><u>Printer Troubles Resolved: Windows 11 Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-windows-710-to-online-hp-printer/"><u>Reconnect Windows 7/10 to Online HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-win-11-printer-hiccup-after-update/"><u>Resolved Win 11 Printer Hiccup After Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-blank-page-output-from-hp/"><u>Resolving Blank Page Output From HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-connection-fix-canon-printer-offline/"><u>Restore Connection: Fix Canon Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-responsive-printer-in-windows-nt-environment/"><u>Revive Non-Responsive Printer in Windows NT Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-post-windows-update-printer-workflow/"><u>Revived Post Windows Update Printer Workflow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-your-windows-11-printer-problems/"><u>Solve Your Windows 11 Printer Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-non-responsive-printer-issues-on-nt-os/"><u>Solving Non-Responsive Printer Issues on NT OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-canon-printer-seamless-wireless-hookup/"><u>Stepwise Canon Printer: Seamless Wireless Hookup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-laser-print-troubleshooting/"><u>Tackling Laser Print Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574001783-technical-mishap-printer-setup-misstep/"><u>Technical Mishap: Printer Setup Misstep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-ultimate-guide-to-installing-and-configuring-hp-printers/"><u>The Ultimate Guide to Installing and Configuring HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-printer-driver-setup-for-hp-deskjet-d1360-on-pcs/"><u>Trouble with Printer Driver Setup for HP Deskjet D1360 on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wins-against-windows-10-print-glitches-after-upgrade/"><u>Wins Against Window's 10 Print Glitches After Upgrade</u></a></li>
</ul></div>
