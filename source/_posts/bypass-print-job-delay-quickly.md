---
title: Bypass Print Job Delay Quickly
date: 2024-09-04T06:14:16.498Z
updated: 2024-09-05T06:14:16.498Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Bypass Print Job Delay Quickly
excerpt: This Article Describes Bypass Print Job Delay Quickly
keywords: Print Job Bypass,Quick Print Delay Fix,Speed Up Printer Jobs,Avoid Print Queue Delays,Prevent Printer Job Hangups,Rapid Print Processing Solutions,Eliminate Printer Job Wait Time
thumbnail: https://thmb.techidaily.com/843a2530bd30cf31b24741cc2e56b474bee5d065dd6fb56cbf786d1e09002e10.jpg
---

## Bypass Print Job Delay Quickly

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
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-insiders-guide-to-on-screen-text-in-youtube-media/"><u>[New] 2024 Approved  The Insider's Guide to On-Screen Text in YouTube Media</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-advanced-8-visual-boosts-for-online-broadcasts/"><u>[New] Advanced 8 Visual Boosts for Online Broadcasts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-essential-guide-software-free-techniques-for-vimeo-downloads/"><u>[New] In 2024, Essential Guide  Software-Free Techniques for Vimeo Downloads</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flawless-free-download-of-youtube-video-covers-no-hurdles/"><u>[New] In 2024, Flawless Free Download of YouTube Video Covers - No Hurdles</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/os-and-android-youtube-autoplay-tricks/"><u>[New] IOS & Android  YouTube AutoPlay Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-fixer-regain-lost-network-print-visibility/"><u>[Print Issue Fixer] Regain Lost Network Print Visibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-local-print-spooler-service-not-running-on-windows/"><u>[SOLVED] Local Print Spooler Service Not Running on Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-expert-tips-on-choosing-top-9-webcam-enhancement-tools-for-2024/"><u>[Updated] Expert Tips on Choosing Top 9 Webcam Enhancement Tools for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-one-step-guide-to-simultaneous-cam-plus-screen-recording/"><u>[Updated] One Step Guide to Simultaneous Cam + Screen Recording</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>10 Best Fake GPS Location Spoofers for Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-the-art-creating-high-quality-gopro-vlogs/"><u>2024 Approved  Mastering The Art  Creating High-Quality Gopro Vlogs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574061275-b200-bug-fixed-ready-to-go/"><u>B200 Bug Fixed, Ready to Go</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-page-dilemma-hp-printer-now-printing-correctly/"><u>Blank Page Dilemma: HP Printer Now Printing Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-gap-fast-printer-connection/"><u>Bridging Gap: Fast Printer Connection</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-a58-4g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Oppo A58 4G</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573877149-effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-disconnect-resolved/"><u>Epson Disconnect Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-code-0x97-uncovered-and-resolved/"><u>Epson Fault Code 0X97 Uncovered & Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-fixes-for-non-starting-print-spooler-on-pcs/"><u>Essential Fixes for Non-Starting Print Spooler on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-in-effect-for-b200/"><u>Fix In Effect for B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-disappearing-printers-in-windows-810/"><u>How to Fix Disappearing Printers in WIndows 8/10</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-poco-f5-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Poco F5 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-your-hp-4630-at-the-forefront-with-timely-driver-upgrades/"><u>Keep Your HP 4630 at the Forefront with Timely Driver Upgrades</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-deletion-of-printers-on-pc/"><u>Mastering the Deletion of Printers on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-enhanced-support-for-windows-versions-108/"><u>MF4770n Enhanced Support for WIndows Versions 10/8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-a-silent-printer-in-office/"><u>Navigating a Silent Printer in Office</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-epsons-error-0x97-maze/"><u>Navigating Epson's Error 0X97 Maze</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/navigating-your-path-as-a-first-time-youtuber-sidestep-these-8-common-mistakes/"><u>Navigating Your Path as a First-Time YouTuber  Sidestep These 8 Common Mistakes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-from-zero-to-hero-master-lip-syncing-with-these-5-amazing-apps-for-2024/"><u>New From Zero to Hero Master Lip Syncing with These 5 Amazing Apps for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-text-only-paper-the-epson-printer-glitch/"><u>No Text, Only Paper: The Epson Printer Glitch</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcome-audio-hurdles-in-google-meet-with-these-windows-11-and-10-solutions/"><u>Overcome Audio Hurdles in Google Meet with These Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-print-server-disconnect/"><u>Overcoming Print Server Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-trail-points-to-unidentified-user/"><u>Paper Trail Points to Unidentified User</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-error-on-windows-fixed/"><u>Printer Not Responding Error on Windows Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-shown-solutions-for-network-print-issues/"><u>Printer Not Shown: Solutions for Network Print Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstating-print-spooler-services-correctly/"><u>Reinstating Print Spooler Services Correctly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/scripting-success-with-chatgpt-the-story-of-my-podcast-journey/"><u>Scripting Success with ChatGPT: The Story of My Podcast Journey</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printer-function-release/"><u>Seamless Printer Function Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-officejets-no-print-malaise/"><u>Solving OfficeJet's No Print Malaise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-resolve-print-spooler-shutdown-woes-win-10-11-and-7/"><u>Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-and-resolve-printer-spooling-trouble/"><u>Steps to Stop and Resolve Printer Spooling Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-black-screen-issue-on-hp-printer/"><u>Tackling Black Screen Issue on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-to-revive-non-printing-hp-all-in-ones/"><u>Tips to Revive Non-Printing HP All-In-Ones</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-epson-printer-error-codes-on-w11/"><u>Troubleshoot Epson Printer Error Codes on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-cartridge-replacement-failures/"><u>Troubleshooting Cartridge Replacement Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-produce-full-color-prints/"><u>Unable to Produce Full-Color Prints</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-tecno-pova-6-pro-5g-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Tecno Pova 6 Pro 5G Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-itel-a60-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Itel A60? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-fix-printer-not-responding-anymore/"><u>Win11 Fix: Printer Not Responding Anymore</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-usb-printer-reset-problems-post-sleep-cycle/"><u>Win7 USB Printer Reset: Problems Post-Sleep Cycle</u></a></li>
</ul></div>
