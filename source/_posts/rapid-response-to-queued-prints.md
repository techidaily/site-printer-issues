---
title: Rapid Response to Queued Prints
date: 2024-08-08T01:08:09.470Z
updated: 2024-08-09T01:08:09.470Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Response to Queued Prints
excerpt: This Article Describes Rapid Response to Queued Prints
keywords: Quick Print Service,Speedy Print Delivery,Urgent Print Jobs Handling,Rapid Printer Queue Management,Expedited Print Processing,High-Speed Printer Services,Fast Print Order Turnaround
thumbnail: https://thmb.techidaily.com/08bfc68ca7424de532f1e4f97e0746486dfe84c1304de3ac8c4843a110a218e6.jpg
---

## Rapid Response to Queued Prints

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-moonlit-mastery-tips-for-perfecting-nighttime-photos/"><u>[New] 2024 Approved  Moonlit Mastery  Tips for Perfecting Nighttime Photos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-print-service-non-functioning-windows/"><u>[TROUBLESHOOT] Print Service Non-Functioning Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-proven-techniques-for-obs-broadcasting-on-fb/"><u>[Updated] 2024 Approved  Proven Techniques for OBS Broadcasting on FB</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-step-by-step-for-turning-insta-videos-into-mp3s/"><u>[Updated] 2024 Approved  Step-by-Step for Turning Insta Videos Into MP3s</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-converting-twitter-video-lyrics-to-custom-gif-animations-for-2024/"><u>[Updated] Converting Twitter Video Lyrics to Custom GIF Animations for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-enhancing-video-content-top-formats-on-youtube/"><u>[Updated] In 2024, Enhancing Video Content  Top Formats on YouTube</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-intro-to-photo-editing-mastering-lunapic-basics/"><u>[Updated] Intro to Photo Editing  Mastering LunaPic Basics</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-audiovisual-excellence-top-5-premium-slow-motion-gear/"><u>2024 Approved  Audiovisual Excellence  Top 5 Premium Slow-Motion Gear</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-insights-on-how-youtube-handles-uploaded-videos/"><u>2024 Approved  Insights on How YouTube Handles Uploaded Videos</u></a></li>
<li><a href="https://article-posts.techidaily.com/7-key-elements-for-perfect-instagram-unpackings-for-2024/"><u>7 Key Elements for Perfect Instagram Unpackings for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-tale-of-triumph-over-theoretical-paper-trails/"><u>A Tale of Triumph Over Theoretical Paper Trails</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-boundaries-questions-that-challenge-chatgpt/"><u>AI Boundaries: Questions That Challenge ChatGPT</u></a></li>
<li><a href="https://video-capture.techidaily.com/alter-macs-screen-capture-store-path-for-2024/"><u>Alter Mac's Screen Capture Store Path for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-fixing-missing-or-not-found-coredll-errors-effortlessly/"><u>Comprehensive Guide: Fixing Missing or Not Found Core.Dll Errors Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-no-print-restoring-functionality-of-brother-printer-winoses/"><u>Conquer No-Print: Restoring Functionality of Brother Printer, WinOSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-enhance-printer-speed/"><u>Effortlessly Enhance Printer Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expedite-jammed-print-queue/"><u>Expedite Jammed Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-for-post-update-printer-failure/"><u>Fix for Post-Update Printer Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hiccup-printer-config-issue/"><u>Hardware Hiccup: Printer Config Issue</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-you-cast-your-apple-iphone-15-pro-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>How Can You Cast Your Apple iPhone 15 Pro to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-game-lag-issues-on-dying-light-action-survival-platformer/"><u>How to Overcome Game Lag Issues on Dying Light Action Survival Platformer</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-x-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone X?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-basketball-enthusiasts-guide-to-online-viewing/"><u>In 2024, Basketball Enthusiast's Guide to Online Viewing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-samsung-galaxy-m14-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Samsung Galaxy M14 5G</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-high-quality-audio-drivers-compatible-with-windows-7/"><u>Install High-Quality Audio Drivers Compatible with Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-disconnected-printers/"><u>Methods to Reactivate Disconnected Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-colored-output-not-rendered/"><u>Printer's Colored Output Not Rendered</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-15-plus-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-scanner-activation-on-windows-10-system/"><u>Resetting Scanner Activation on Windows 10 System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-laser-print-quality-concerns/"><u>Resolving Laser Print Quality Concerns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/service-not-active-local-printer-spooler/"><u>Service Not Active: Local Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silencing-the-silent-printouts-in-your-device/"><u>Silencing the Silent Printouts in Your Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-installing-hp-envy-504-printers/"><u>Step-by-Step Guide to Installing HP Envy 504 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-incorporating-hp-printer-in-pc-network/"><u>Step-by-Step: Incorporating HP Printer in PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-non-responding-printer-unit/"><u>Tackled Non-Responding Printer Unit</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-back-on-brothers-printer-in-remote-spotlight/"><u>Turn Back on Brothers Printer in Remote Spotlight</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-hiccup-discovered/"><u>Unexpected Print Hiccup Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-restored-scan-operation/"><u>Windows 11: Restored Scan Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wizard-disconnecting-all-printers/"><u>Windows Wizard: Disconnecting All Printers</u></a></li>
</ul></div>
