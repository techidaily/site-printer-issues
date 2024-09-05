---
title: Speed Up Stalled Printer Tasks
date: 2024-09-04T06:17:03.602Z
updated: 2024-09-05T06:17:03.602Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speed Up Stalled Printer Tasks
excerpt: This Article Describes Speed Up Stalled Printer Tasks
keywords: Printer Speed Optimization,Fixing Printer Lag Issues,Enhance Print Task Performance,Print Task Acceleration Tips,Resolve Printer Slowdowns,Improving Printer Workflow Efficiency,Printer Task Streamlining Techniques
thumbnail: https://thmb.techidaily.com/4e8500390862c71ba9fd3f45025661c15b6c8c5d9fdf1c818444f469b9c52d07.PNG
---

## Speed Up Stalled Printer Tasks

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
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-exploring-youtubes-regular-income-mechanism/"><u>[New] 2024 Approved  Exploring YouTube's Regular Income Mechanism</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-free-unique-audio-selections-for-video-conclusions/"><u>[New] 2024 Approved  Free, Unique Audio Selections for Video Conclusions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-essential-directories-unencumbered-visuals-galore/"><u>[New] In 2024, Essential Directories  Unencumbered Visuals Galore</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-the-drone-racers-companion-basics-to-aces-and-top-5-fpv-brands/"><u>[New] In 2024, The Drone Racer's Companion  Basics to Aces and Top 5 FPV Brands</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-speeding-up-your-instagram-video-watch-time/"><u>[New] Speeding Up Your Instagram Video Watch Time</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-smart-way-to-extract-specific-segments-from-youtube/"><u>[New] The Smart Way to Extract Specific Segments From YouTube</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-error-code-following-device-suspend-w7/"><u>[Solved] Printer Error Code Following Device Suspend, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-tip-revive-missing-windows-xp10-printer/"><u>[Tech Tip] Revive Missing Windows XP/10 Printer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-digging-into-the-heart-of-recordcast-technology/"><u>[Updated] 2024 Approved  Digging Into the Heart of RecordCast Technology</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-proven-recorders-ioss-leading-screenshot-tools/"><u>[Updated] 2024 Approved  Proven Recorders  IOS's Leading Screenshot Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-virtual-horizons-with-meaningful-metaverse-sentiments/"><u>[Updated] Exploring Virtual Horizons with Meaningful Metaverse Sentiments</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-performance-drones-sold-here/"><u>[Updated] High-Performance Drones Sold Here</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-how-to-maximize-your-youtube-shorts-earnings/"><u>[Updated] In 2024, How to Maximize Your YouTube Shorts Earnings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-tips-how-to-reinstall-a-lost-print-job/"><u>[Windows Tips] How to Reinstall a Lost Print Job</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bring-to-life-enable-your-silent-canon-print-spooler/"><u>Bring To Life: Enable Your Silent Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-repeated-print-job-errors-in-windows-operating-systems/"><u>Combat Repeated Print Job Errors in Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-install-epson-wf-7710-printer-drivers-for-your-windows-pc-windows-11-81-and-earlier-supported/"><u>Easy Install EPSON WF-7710 Printer Drivers for Your Windows PC (Windows 11, 8.1 & Earlier Supported)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-connectivity-windows-10-way/"><u>Enhance Printer Connectivity, Windows 10 Way</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-error-due-to-active-directory-halt/"><u>Fixed: Printer Error Due to Active Directory Halt</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-link-issues-fastly/"><u>Fixing Printer Link Issues Fastly</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/from-novice-to-proficient-russian-numeral-acquisition/"><u>From Novice to Proficient: Russian Numeral Acquisition</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/husqvarnas-high-flyers-the-2023-drone-review-series-for-2024/"><u>Husqvarna's High Flyers  The 2023 Drone Review Series for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-zte-nubia-flip-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from ZTE Nubia Flip 5G Phones with/without a PC</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-vivo-s18e-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-xiaomi-13-ultras-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Xiaomi 13 Ultras Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win-howtos.techidaily.com/insider-tips-conquering-the-complete-darkness-screens-on-startup-of-mhw/"><u>Insider Tips: Conquering the Complete Darkness Screens on Startup of MHW</u></a></li>
<li><a href="https://printer-issues.techidaily.com/managing-paper-tray-sensor-problems/"><u>Managing Paper Tray Sensor Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-workflow-swiftly/"><u>Optimize Printing Workflow Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-hooked-up-no-friction/"><u>Print Device Hooked Up, No Friction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-solved-for-epson-model/"><u>Print Issue Solved for Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-misdemeanor-by-unknown-system/"><u>Printing Misdemeanor by Unknown System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstate-scanner-connection-on-windows-10-machine/"><u>Reinstate Scanner Connection on Windows 10 Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-samsung-print-woes/"><u>Solving Samsung Print Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-recover-an-offline-print-device-from-network/"><u>Steps to Recover an Offline Print Device From Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-jolt-to-halted-print-queues/"><u>Swift Jolt to Halted Print Queues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-resolving-non-responsive-hp-scanners/"><u>Techniques for Resolving Non-Responsive HP Scanners</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transform-videos-affordable-high-quality-effs-for-2024/"><u>Transform Videos - Affordable, High-Quality Effs for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transformative-beauty-tutorials-for-everyone-for-2024/"><u>Transformative Beauty Tutorials for Everyone for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-no-response/"><u>Troubleshooting HP Printer No Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://os-tips.techidaily.com/ultimate-selection-of-iphone-case-innovations-and-designs-for-the-year-2023/"><u>Ultimate Selection of iPhone Case Innovations and Designs for the Year 2023</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-icon-in-win-810-systems/"><u>Unexpectedly No Printer Icon in Win 8/10 Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unleash-speed-edit-windows-11-photos-like-a-pro/"><u>Unleash Speed  Edit Windows 11 Photos Like a Pro</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/winxdvd-pro-advanced-dvd-copying-with-ai-powered-video-improvement-and-mobile-transfer-features/"><u>WinXDVD Pro: Advanced DVD Copying with AI-Powered Video Improvement & Mobile Transfer Features</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zero-in-on-the-problem-discover-these-5-ways-to-help-your-canon-printer-print/"><u>Zero in on the Problem: Discover These 5 Ways to Help Your Canon Printer Print</u></a></li>
</ul></div>
