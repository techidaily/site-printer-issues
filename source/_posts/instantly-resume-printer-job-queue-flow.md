---
title: Instantly Resume Printer Job Queue Flow
date: 2024-09-09T01:23:58.482Z
updated: 2024-09-10T01:23:58.482Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantly Resume Printer Job Queue Flow
excerpt: This Article Describes Instantly Resume Printer Job Queue Flow
keywords: Printer Job Management,Instant Printer Queue Recovery,Print Job Queue Optimization,Resume Printer Workflow Automation,Continuous Print Job Processing,Print Spooler Management,Printer Queue Error Resolution
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Instantly Resume Printer Job Queue Flow

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-unable-to-locate-hp-driver-on-winxo/"><u>[Driver Difficulty] - Unable to Locate HP Driver on WinXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-canon-pixma-mp620-unseen-in-win11/"><u>[Driver Difficulty] Canon Pixma MP620 Unseen in Win11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-capture-igtv-media-step-by-step-guide-for-pc-and-mac-devices/"><u>[New] 2024 Approved  Capture IGTV Media  Step-by-Step Guide for PC & Mac Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-3-tactics-to-enhance-your-instagram-films-look/"><u>[New] 3 Tactics to Enhance Your Instagram Film's Look</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/levated-viewership-status-symbolized-by-buttons/"><u>[New] Elevated Viewership Status Symbolized by Buttons</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-unlock-fb-seo-potential-with-keyword-rich-strategies/"><u>[New] In 2024, Unlock FB SEO Potential with Keyword-Rich Strategies</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-creator-to-critic-evaluating-video-value-across-platforms/"><u>[Updated] From Creator to Critic  Evaluating Video Value Across Platforms</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-the-ultimate-guide-for-emoji-laden-discord-statements/"><u>[Updated] In 2024, The Ultimate Guide for Emoji-Laden Discord Statements</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-print-service-not-starting-correctly/"><u>[WARNING] Print Service Not Starting Correctly</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-premier-movie-options-beyond-the-top-selections-for-2024/"><u>2023'S Premier Movie Options  Beyond The Top Selections for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-master-your-media-comprehensive-guide-to-instagram-converters-windowsmac/"><u>2024 Approved  Master Your Media  Comprehensive Guide to Instagram Converters (Windows/Mac)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/a-beginners-approach-to-nvidia-screen-capture-for-2024/"><u>A Beginner's Approach to NVIDIA Screen Capture for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addsvc-not-responding-printer-error-reported/"><u>ADDSVC Not Responding: Printer Error Reported</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574003773-canon-printer-is-offline-heres-how-to-fix-it/"><u>Canon Printer Is Offline? Here's How to Fix It!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compact-bundle-optimized-hp-officejet-pro-8600-drivers-win32/"><u>Compact Bundle: Optimized HP Officejet Pro 8600 Drivers, Win32</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicate-printer-errors-on-windows-10-pc/"><u>Eradicate Printer Errors on Windows 10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-the-epson-fix/"><u>Error Code 0X97: The Epson Fix</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fading-sound-tracks-with-logic-pro-for-2024/"><u>Fading Sound Tracks with Logic Pro for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-windows-11-support-for-mp620-printer/"><u>Finding Windows 11 Support for MP620 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-windows-11-8-7-and-mf4770n-for-efficiency/"><u>Harmonizing Windows 11, 8, 7 & MF4770n for Efficiency</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-blending-photos-into-a-kaleidoscopic-visual-symphony/"><u>In 2024, Blending Photos Into a Kaleidoscopic Visual Symphony</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s24-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S24 Bootloader Easily</u></a></li>
<li><a href="https://extra-information.techidaily.com/incremental-movie-moment/"><u>Incremental Movie Moment</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mac-stellar-file-eraser-ultimate-solution-with-pre-planned-deletion-features/"><u>Mac Stellar File Eraser: Ultimate Solution with Pre-Planned Deletion Features</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-installation-of-canon-print-devices/"><u>Mastering the Installation of Canon Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-printer-support-package-windows-based/"><u>Officejet Pro 8600 Printer Support Package, Windows-Based</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canons-non-print-dilemma-with-these-quick-fixes-in-windows-11/"><u>Overcome Canon's Non-Print Dilemma with These Quick Fixes in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-ink-cartridge-disasters/"><u>Preventing Ink Cartridge Disasters</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-dilemma-ends-after-new-windows-installation/"><u>Print Dilemma Ends After New Windows Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-are-missing/"><u>Printer OS Error: Drivers Are MISSING</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-mysterious-setup-error/"><u>Printer Puzzle: Mysterious Setup Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-dell-printer-offline-error-on-windows-7/"><u>Resolved Dell Printer Offline Error on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-status-fluctuation-on-windows-7/"><u>Resolved Printer Status Fluctuation on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-stalled-printer-tasks/"><u>Speed Up Stalled Printer Tasks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-established-printer-connections/"><u>Success: Established Printer Connections</u></a></li>
<li><a href="https://printer-issues.techidaily.com/synchronize-printer-settings-across-multiple-devices-win10-style/"><u>Synchronize Printer Settings Across Multiple Devices, Win10 Style</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-vivo-t2-pro-5g-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Vivo T2 Pro 5G Device</u></a></li>
<li><a href="https://extra-tips.techidaily.com/twitch-time-travel-retrieve-lost-broadcast-moments/"><u>Twitch Time-Travel  Retrieve Lost Broadcast Moments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/v305-dell-printer-driver-fix-for-windows-7/"><u>V305 Dell Printer Driver Fix for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-hp-printer-setup-manual/"><u>Win HP Printer Setup Manual</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-7-printer-repaired/"><u>Windows 7 Printer Repaired</u></a></li>
</ul></div>
