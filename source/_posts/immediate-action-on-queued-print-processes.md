---
title: Immediate Action on Queued Print Processes
date: 2024-08-22T09:41:03.563Z
updated: 2024-08-23T09:41:03.563Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Action on Queued Print Processes
excerpt: This Article Describes Immediate Action on Queued Print Processes
keywords: Queue Reduction,Print Queue Management,Printer Processing Time,Fast Print Resolution,Print Queue Optimization,Rapid Print Processing,Print Queue Cancellation
thumbnail: https://thmb.techidaily.com/2e7cadf9e7c8396ddc846863b7d8b8551ba6b8c7abac3eec6dd5274d2d66a517.jpg
---

## Immediate Action on Queued Print Processes

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
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-from-novice-to-pro-creating-impressive-fb-covers/"><u>[New] 2024 Approved  From Novice to Pro  Creating Impressive FB Covers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/rafting-engaging-gamers-banners-using-pre-made-themes-for-2024/"><u>[New] Crafting Engaging Gamers' Banners  Using Pre-Made Themes for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-depth-analysis-of-fb-chat-recording-techniques-for-2024/"><u>[New] In-Depth Analysis of FB Chat Recording Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-time-reversal-tactics-unique-youtube-video-experiences/"><u>[New] Time-Reversal Tactics  Unique YouTube Video Experiences</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlock-the-potential-of-your-phone-individual-ringtone-creation-on-android/"><u>[New] Unlock the Potential of Your Phone  Individual Ringtone Creation on Android</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-compatibility-unable-to-connect-to-hp-print-service-on-windows/"><u>[OS Compatibility] - Unable to Connect to HP Print Service on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-brighten-up-your-gaming-setup-eliminate-black-screens-with-obs-for-2024/"><u>[Updated] Brighten Up Your Gaming Setup  Eliminate Black Screens with OBS for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-ultimate-10-plugin-power-duo-for-final-cut-pro/"><u>[Updated] In 2024, The Ultimate 10 Plugin Power Duo for Final Cut Pro</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-the-entrepreneurial-roadmap-for-starting-an-online-product-critique-site/"><u>2024 Approved  The Entrepreneurial Roadmap for Starting an Online Product Critique Site</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-poco-m6-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-tale-of-triumph-over-theoretical-paper-trails/"><u>A Tale of Triumph Over Theoretical Paper Trails</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adopting-powerpoints-advanced-speech-to-text-functionality-for-dynamic-slide-shows/"><u>Adopting PowerPoint’s Advanced Speech-to-Text Functionality for Dynamic Slide Shows</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nces-on-the-rise-gauge/"><u>Audiences on the Rise Gauge</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-no-print-restoring-functionality-of-brother-printer-winoses/"><u>Conquer No-Print: Restoring Functionality of Brother Printer, WinOSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-installation-of-upgraded-printer-drivers/"><u>Correct Installation of Upgraded Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-enhance-printer-speed/"><u>Effortlessly Enhance Printer Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://facebook.techidaily.com/engage-friends-utilizing-facebook-portal-tv-for-video-calls/"><u>Engage Friends: Utilizing Facebook Portal TV for Video Calls</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-devices-exhibiting-continuous-sheet-outputs/"><u>Epson Devices Exhibiting Continuous Sheet Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-error-continuous-sheet-replacement/"><u>Epson Printer Error: Continuous Sheet Replacement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expedite-jammed-print-queue/"><u>Expedite Jammed Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-print-misstep-code-oxc4eb827f/"><u>Fixing HP Print Misstep: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hiccup-printer-config-issue/"><u>Hardware Hiccup: Printer Config Issue</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-oppo-find-n3-flip-is-unlocked-by-drfone-android/"><u>How To Check if Your Oppo Find N3 Flip Is Unlocked</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-galaxy-a15-4g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Galaxy A15 4G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-vivo-v29e-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Vivo V29e?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-worklift-printer-setup-and-use/"><u>HP WorkLift Printer Setup and Use</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-10-best-youtube-keyword-tools-to-get-more-views/"><u>In 2024, 10 Best YouTube Keyword Tools to Get More Views</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-realme-c67-4g-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Realme C67 4G</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-effective-screen-recording-with-a-focus-on-usability/"><u>In 2024, Effective Screen Recording with a Focus on Usability</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-samsung-galaxy-a25-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Samsung Galaxy A25 5G Devices | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-modern-electronics-by-toms-tech-experts/"><u>In-Depth Analysis of Modern Electronics by Tom's Tech Experts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-disconnected-printers/"><u>Methods to Reactivate Disconnected Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-printer-device-windows-710-troubleshooting-steps/"><u>Missing Printer Device? Windows 7/10 Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-non-printing-issues-brother-printer-windows-edition/"><u>Navigating Non-Printing Issues: Brother Printer, Windows Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inkless-printer-issues/"><u>Overcoming Inkless Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-nozzle-necessity-neglected/"><u>Post-Update, Nozzle Necessity Neglected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unlisted-solutions-for-windows-xp-11/"><u>Printer Unlisted: Solutions for Windows XP-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-colored-output-not-rendered/"><u>Printer's Colored Output Not Rendered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/procedure-connecting-hp-officejet-to-windows-device/"><u>Procedure: Connecting HP Officejet to Windows Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-laser-print-quality-concerns/"><u>Resolving Laser Print Quality Concerns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speeding-up-prints-simplest-fixes/"><u>Speeding Up Prints: Simplest Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/streamlining-your-process-tools-and-tricks-for-smooth-broadcasting/"><u>Streamlining Your Process  Tools and Tricks for Smooth Broadcasting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-non-responding-printer-unit/"><u>Tackled Non-Responding Printer Unit</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-win-10-printer-disruptions-success-story/"><u>The End of Win 10 Printer Disruptions - Success Story</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-samsung-galaxy-s23-fe-by-drfone-android/"><u>Three Ways to Sim Unlock Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-guide-flawlessly-handle-pcl-xl-mistakes/"><u>Troubleshooting Guide: Flawlessly Handle PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-back-on-brothers-printer-in-remote-spotlight/"><u>Turn Back on Brothers Printer in Remote Spotlight</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-hiccup-discovered/"><u>Unexpected Print Hiccup Discovered</u></a></li>
<li><a href="https://driver-install.techidaily.com/unifying-usbasp-driver-functionality-in-old-and-new-windows/"><u>Unifying USBasp Driver Functionality in Old & New Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wizard-disconnecting-all-printers/"><u>Windows Wizard: Disconnecting All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-epson-error-code-x97/"><u>Zeroing In on Epson Error Code X97</u></a></li>
</ul></div>
