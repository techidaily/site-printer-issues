---
title: Swiftly Solve Stuck Printer Job Queue
date: 2024-09-04T06:12:59.872Z
updated: 2024-09-05T06:12:59.872Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swiftly Solve Stuck Printer Job Queue
excerpt: This Article Describes Swiftly Solve Stuck Printer Job Queue
keywords: Printer Job Error,Stuck Printer Job Queue Fix,Print Spooler Troubleshooting,Printer Queue Management,Cease Print Job Errors,Printer Spooler Service Restart,Resolve Printer Queue Delays
thumbnail: https://thmb.techidaily.com/1e11de4cf4f80ef092048741d4366db23f2bbee1459c9f567932a80d4f33ce93.jpg
---

## Swiftly Solve Stuck Printer Job Queue

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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/connectivity-issue-cannot-add-printer-drivers-to-multiple-windows/"><u>[Connectivity Issue] Cannot Add Printer Drivers to Multiple Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-inactive-print-spooler-in-windows-os/"><u>[FIX] Inactive Print Spooler in Windows OS</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-precision-and-vividness-with-the-benq-sw320-4k-monitor/"><u>[New] In 2024, Precision & Vividness with the BenQ SW320 4K Monitor</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-unveiling-the-best-zero-price-videochat-services-for-2024/"><u>[New] Unveiling the Best Zero-Price Videochat Services for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-print-service-non-functioning-windows/"><u>[TROUBLESHOOT] Print Service Non-Functioning Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-creative-filmmaking-on-a-budget-using-smartphones-as-webcams/"><u>[Updated] In 2024, Creative Filmmaking on a Budget  Using Smartphones as Webcams</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-tips-for-achieving-crystal-clear-1080p-on-fb/"><u>[Updated] In 2024, Tips for Achieving Crystal Clear 1080P on FB</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-photo-display-tools-for-iphone-series-upgrades/"><u>2024 Approved  Best Photo Display Tools For iPhone Series Upgrades</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-richer-imagery-enhancing-video-with-device-based-filters/"><u>2024 Approved  Richer Imagery  Enhancing Video with Device-Based Filters</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-operational-efficiency-with-mf4770n-on-w11w8w7-windows/"><u>Boost Operational Efficiency with MF4770n on W11/W8/W7 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printer-speed-with-simple-fixes/"><u>Boost Printer Speed with Simple Fixes</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/conquer-uneven-ground-a-detailed-evaluation-of-the-top-race-rc-rock-crawler-performance/"><u>Conquer Uneven Ground: A Detailed Evaluation of the Top Race RC Rock Crawler Performance</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-install-fresh-pl23-grove-to-ethernet-converter-drivers-for-windows-devices/"><u>Easy Install: Fresh PL23 Grove to Ethernet Converter Drivers for Windows Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-your-brother-printer-to-print-on-windows-1011-successfully/"><u>Enable Your Brother Printer to Print on Windows 10/11 Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-multifunction-device-shows-unwanted-emptiness/"><u>Epson Multifunction Device Shows Unwanted Emptiness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-for-post-update-printer-failure/"><u>Fix for Post-Update Printer Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-intermittent-print-service-disruptions-in-win-oss/"><u>Fixing Intermittent Print Service Disruptions in Win OSs</u></a></li>
<li><a href="https://android-frp.techidaily.com/from-jet-propulsion-to-supersonic-flight-witnessing-the-phenomenon-of-cannon-air-bursts/"><u>From Jet Propulsion to Supersonic Flight – Witnessing the Phenomenon of Cannon-Air Bursts</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-smart-8-pro-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-enable-brother-9330cdw-driver/"><u>Guide to Enable Brother 9330CDW Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-restoring-communication-with-printer/"><u>Guide to Restoring Communication with Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-setup-brothers-mfc-9330cdw-fan/"><u>Guide to Setup Brother's MFC-9330CDW Fan</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harmonizing-your-windows-photos-how-to-incorporate-audio-visual-features-for-2024/"><u>Harmonizing Your Windows Photos  How to Incorporate Audio-Visual Features for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-lava-yuva-3-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Lava Yuva 3 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/o-download-part-of-youtube-video-in-2024/"><u>How to Download Part of YouTube Video, In 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-tackle-windows-11-printer-malfunctions/"><u>How to Tackle Windows 11 Printer Malfunctions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-remove-iphone-15-plus-sim-lock-by-drfone-ios/"><u>In 2024, How to Remove iPhone 15 Plus SIM Lock?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-art-of-crafting-perfect-boomerangs-in-snap/"><u>In 2024, The Art of Crafting Perfect Boomerangs in Snap</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-importance-of-accurate-slug-line-writing-in-screenplays/"><u>In 2024, The Importance of Accurate Slug Line Writing in Screenplays</u></a></li>
<li><a href="https://win-answers.techidaily.com/lenovo-ideapad-3-15-inch-i7-gtx-1660-ti-in-depth-analysis-of-an-affordable-powerhouse-for-gamers/"><u>Lenovo IdeaPad 3 15-Inch (I7, GTX 1660 Ti) - In-Depth Analysis of an Affordable Powerhouse for Gamers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-maze-getting-brothers-printer-back-on-line/"><u>Navigating the Maze: Getting Brother's Printer Back on Line</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-printer-vanishes-whats-the-remedy/"><u>Network Printer Vanishes, What's the Remedy?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-epson-paper-jam/"><u>Overcome Epson Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-constant-spooler-crashes-a-guide-for-windows-users/"><u>Preventing Constant Spooler Crashes: A Guide for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unexpected-configuration-blunder/"><u>Printer's Unexpected Configuration Blunder</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-solution-for-printer-not-plugged-in/"><u>Rapid Solution for Printer Not Plugged In</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-link-to-computer-post-update/"><u>Reactivating Scanner Link to Computer Post-Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstated-default-printer-post-error-0x00000709-fix/"><u>Reinstated Default Printer Post-Error 0X00000709 Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-no-9008e/"><u>Resolved: Printer Error No. 9008E</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-the-frequent-failure-of-print-spooler-service/"><u>Resolving the Frequent Failure of Print Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-brother-printers-print-a-win1011-guide-to-fixing-issues/"><u>Revive Your Brother Printer's Print: A Win10/11 Guide to Fixing Issues</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899840863-samsungs-next-smartphone-projected-price-points-release-date-and-leaked-tech-info-for-galaxy-s25/"><u>Samsung's Next Smartphone: Projected Price Points, Release Date & Leaked Tech Info for Galaxy S25!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/service-not-active-local-printer-spooler/"><u>Service Not Active: Local Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-snag-your-printer-is-confused/"><u>Setup Snag: Your Printer Is Confused</u></a></li>
<li><a href="https://printer-issues.techidaily.com/silencing-the-silent-printouts-in-your-device/"><u>Silencing the Silent Printouts in Your Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-operations-new-printing-toolkit-for-windows-7-dell/"><u>Smooth Operations: New Printing Toolkit for Windows 7 Dell</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-installing-hp-envy-504-printers/"><u>Step-by-Step Guide to Installing HP Envy 504 Printers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-guide-to-writing-captivating-docu-scripts-for-2024/"><u>Step-By-Step Guide to Writing Captivating Docu-Scripts for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-assembly-combining-hp-printer-model-with-computer/"><u>Technical Assembly: Combining HP Printer Model with Computer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-comparative-benefits-of-digital-versus-traditional-libraries-in-contemporary-society/"><u>The Comparative Benefits of Digital Versus Traditional Libraries in Contemporary Society</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-novices-guide-to-photo-perfection-in-snapseed-for-2024/"><u>The Novice's Guide to Photo Perfection in Snapseed for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/transform-your-photographs-with-googles-smart-editing-features-using-artificnial-intelligence/"><u>Transform Your Photographs with Google's Smart Editing Features Using Artificnial Intelligence</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-euro-truck-simulator-2-computer-system-errors-a-step-by-step-guide/"><u>Troubleshooting Euro Truck Simulator 2 Computer System Errors - A Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/troubleshooting-guide-fixing-non-loading-web-pages-in-chrome/"><u>Troubleshooting Guide: Fixing Non-Loading Web Pages in Chrome</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-jammed-printers/"><u>Unlocking Jammed Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-secret-of-fully-formatted-paper-trails/"><u>Unlocking the Secret of Fully Formatted Paper Trails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-mystery-printer-works-after-win-10-patch/"><u>Unraveling the Mystery: Printer Works After Win 10 Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unrecognized-print-activity-sheds-light/"><u>Unrecognized Print Activity Sheds Light</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-guide-to-pc-intro-makers-online-vs-offline-for-2024/"><u>Updated The Ultimate Guide to PC Intro Makers Online vs Offline for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-nubia-red-magic-8s-pro-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Nubia Red Magic 8S Pro Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-system-cannot-retrieve-printer-drivers/"><u>Win System: Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-restored-scan-operation/"><u>Windows 11: Restored Scan Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-scanner-no-longer-offline/"><u>Windows 11: Scanner No Longer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-update-the-silent-printer/"><u>Windows Update: The Silent Printer</u></a></li>
</ul></div>
