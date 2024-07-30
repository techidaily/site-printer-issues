---
title: Quick Fix for Languishing Printer Jobs
date: 2024-07-29T00:26:39.431Z
updated: 2024-07-30T00:26:39.431Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Fix for Languishing Printer Jobs
excerpt: This Article Describes Quick Fix for Languishing Printer Jobs
keywords: Printer Troubleshooting,Print Job Recovery Techniques,Efficient Printer Maintenance,Optimize Print Job Performance,Printer Error Fixes,Advanced Printer Settings Adjustment,Reliable Print Job Solutions
thumbnail: https://thmb.techidaily.com/fdc25fa9e7d76ca87920564362f13d91c2db273783ec5bcb39c2377739cf581a.jpg
---

## Quick Fix for Languishing Printer Jobs

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-component-pixma-mp620-driver-on-windows-10/"><u>[Missing Component] Pixma MP620 Driver on Windows 10</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/0-strategies-for-boosting-your-youtube-visibility/"><u>[New] 10 Strategies for Boosting Your YouTube Visibility</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-behind-the-scenes-iphone-video-loops-unveiled/"><u>[New] 2024 Approved  Behind the Scenes  IPhone Video Loops Unveiled</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-easy-methods-to-incorporate-subtitles-on-vimeo/"><u>[New] In 2024, Easy Methods to Incorporate Subtitles on Vimeo</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-engagement-integrating-youtube-music-into-videos/"><u>[New] Maximizing Engagement  Integrating YouTube Music Into Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-transforming-your-android-into-a-broadcast-hub/"><u>[New] Transforming Your Android Into a Broadcast Hub</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-crippled-printer-driver-unavailable-in-win/"><u>[SYSTEM CRIPPLED] Printer Driver Unavailable in Win</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-navigating-youtube-partnerships-successfully/"><u>[Updated] 2024 Approved  Navigating YouTube Partnerships Successfully</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-everything-you-need-to-succeed-with-youtube-short-videos-for-2024/"><u>[Updated] Everything You Need to Succeed with YouTube Short Videos for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-saving-game-moments-with-fbx-recorder/"><u>[Updated] In 2024, Saving Game Moments with FBX Recorder</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-tips-for-effective-tripod-usage-in-video-blogging/"><u>2024 Approved  Tips for Effective Tripod Usage in Video Blogging</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-top-5-screen-capture-utilities-for-windows-users/"><u>2024 Approved  Top 5 Screen Capture Utilities for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-top-ranked-fixes-for-integrated-hp-and-laptop-operation/"><u>3 Top-Ranked Fixes for Integrated HP and Laptop Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-print-speed-and-quality-download-hp-officejet-firmware/"><u>Boost Print Speed & Quality - Download HP Officejet Firmware</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/crafting-immersive-experiences-with-captions-on-stories-and-reels-for-2024/"><u>Crafting Immersive Experiences with Captions on Stories & Reels for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cutting-edge-image-editors-for-text-addition/"><u>Cutting-Edge Image Editors for Text Addition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-laser-printer-errors/"><u>Decoding Laser Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-remedies-for-common-pcl-xl-issues/"><u>Efficient Remedies for Common PCL XL Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-constant-spooler-pauses-across-win-versions/"><u>Eliminate Constant Spooler Pauses Across Win Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-efficiency-printer-software-update-for-dell-and-win7/"><u>Enhance Efficiency: Printer Software Update for Dell & Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-out-of-service/"><u>Fixed Epson Out Of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fix-scanner-disconnection-in-windows-10/"><u>Guide to Fix Scanner Disconnection in Windows 10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From Apple iPhone XS Max</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-inside-look-how-dell-p2715q-delivers-on-4k-quality/"><u>In 2024, Inside Look  How Dell P2715Q Delivers on 4K Quality</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-samsung-galaxy-z-fold-5-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ng-converter-youtube-dialogue-to-text/"><u>Leading Converter  YouTube Dialogue to Text</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-toner-trouble/"><u>Navigating Through Toner Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-communications-unavailable/"><u>Print Issue: Communications Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fixed-after-new-windows-version-patch/"><u>Printer Fixed After New Windows Version Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hijacked-multiple-sessions-spotted/"><u>Printer Hijacked? Multiple Sessions Spotted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-spooling-failure-in-windows-10/"><u>Printer Spooling Failure in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-usage-fluctuation-raises-eyebrows/"><u>Printer Usage Fluctuation Raises Eyebrows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-enabling-online-scanner-in-win11/"><u>Re-Enabling Online Scanner in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-engage-withprinter-online-troubleshooting-steps/"><u>Re-Engage Withprinter: Online Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/realign-printer-settings-in-win10-environment/"><u>Realign Printer Settings in Win10 Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recovering-windows-hp-printer-status/"><u>Recovering Windows HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-reactivation-achieved-in-windows-11/"><u>Scanner Reactivation Achieved in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-pathway-attaching-hp-8720-to-computer-systems/"><u>Setup Pathway: Attaching HP 8720 to Computer Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-guide-to-mfc-9330cdw-setup/"><u>Simple Guide to MFC-9330CDW Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-document-output-on-windowshp/"><u>Streamlining Document Output on Windows/HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tactics-for-uninstalling-windows-printers/"><u>Tactics for Uninstalling Windows Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-reviving-inactive-hp-copiers/"><u>Techniques for Reviving Inactive HP Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-complete-roadmap-to-activating-and-installing-your-win-hp-printer/"><u>The Complete Roadmap to Activating & Installing Your Win HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-blank-page-woes-printer-remedy-discovered/"><u>The End of Blank Page Woes: Printer Remedy Discovered</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-list-of-on-line-aid-sources-for-flawless-visual-text-for-2024/"><u>The Ultimate List of On-Line Aid Sources for Flawless Visual Text for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-operational-usb-printers-in-sleep-mode-w7/"><u>Troubleshooting Non-Operational USB Printers in Sleep Mode, W7</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-smart-7-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Smart 7 password or pattern lock</u></a></li>
</ul></div>
