---
title: Swiftly Displace Queued Print Operations
date: 2024-09-04T06:17:50.224Z
updated: 2024-09-05T06:17:50.224Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swiftly Displace Queued Print Operations
excerpt: This Article Describes Swiftly Displace Queued Print Operations
keywords: Displace Queued Print Operations,Swiftly Execute Printer Jobs,Manage Print Processes,Accelerate Print Queue Management,Printer Job Scheduling Optimization,Efficient Print System Transition,Immediate Handling of Printer Tasks
thumbnail: https://thmb.techidaily.com/d08434487f817b4e37cfe7558cadbd43386d2a1219d74867c43320f3c0faf48e.jpg
---

## Swiftly Displace Queued Print Operations

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
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-amplifying-impact-youtube-visibility-techniques/"><u>[New] 2024 Approved  Amplifying Impact  YouTube Visibility Techniques</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-efficient-methods-for-recording-minecraft-sessions/"><u>[New] Efficient Methods for Recording Minecraft Sessions</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/asterful-seo-approaches-for-soaring-in-youtube-video-popularity-for-2024/"><u>[New] Masterful SEO Approaches for Soaring in YouTube Video Popularity for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unleashing-your-viewing-experience-screen-recording-solutions/"><u>[New] Unleashing Your Viewing Experience  Screen Recording Solutions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-follow-the-leaders-youtubes-elite-music-bands/"><u>[Updated] 2024 Approved  Follow the Leaders  YouTube's Elite Music Bands</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-illustrator-tutorial-bringing-text-to-life/"><u>[Updated] Illustrator Tutorial  Bringing Text to Life</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-release-for-queued-printer-work/"><u>Accelerate Release for Queued Printer Work</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/beating-the-market-top-file-managers/"><u>Beating the Market  Top File Managers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-infinix-note-30-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Infinix Note 30.</u></a></li>
<li><a href="https://printer-issues.techidaily.com/break-free-from-stuck-print-queue/"><u>Break Free From Stuck Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-life-into-your-printer-overcoming-offline-issues/"><u>Breathe Life Into Your Printer: Overcoming Offline Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-driver-windows-11-refuses-to-connect/"><u>Canon Pixma MP620 Driver: Windows 11 Refuses to Connect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-prints-failing-to-appear/"><u>Color Prints Failing to Appear</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connect-and-print-with-hp-deskjet-2630-remote/"><u>Connect & Print with HP DeskJet 2630 Remote</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Infinix Smart 7 HD? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-latest-updates-for-canoscan-lide-220-scanner-software/"><u>Download and Latest Updates for CanoScan LiDE 220 Scanner Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-white-refills-in-epson-printing-issue/"><u>Endless White Refills in Epson Printing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expeditiously-address-printer-job-stall/"><u>Expeditiously Address Printer Job Stall</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-unboxed-to-printed-the-complete-win-hp-printer-guidebook/"><u>From Unboxed to Printed: The Complete Win HP Printer Guidebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/getting-your-w7s-offline-hp-print-running/"><u>Getting Your W7's Offline HP Print Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-cure-printer-blank-screens/"><u>Guidelines to Cure Printer Blank Screens</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-oppo-a79-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-the-printer-not-printing-issue/"><u>How to Fix the Printer Not Printing Issue</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ideal-tech-gear-our-top-18-webcam-recording-innovations-reviewed/"><u>Ideal Tech Gear  Our Top 18 Webcam Recording Innovations Reviewed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/identified-non-owner-print-job-intervention/"><u>Identified Non-Owner Print Job Intervention</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gazegraphic-reviews-synopsis/"><u>In 2024, GazeGraphic Reviews Synopsis</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-seamless-edits-navigating-photoshops-eraser-function/"><u>In 2024, Seamless Edits  Navigating Photoshop’s Eraser Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instruction-adding-officejet-pro-8720-to-computer-setup/"><u>Instruction: Adding OfficeJet Pro 8720 to Computer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-3d-imaging-printer-easily/"><u>Integrating HP 3D Imaging Printer Easily</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/is-your-iphone-7-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>Is Your iPhone 7 in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/offline-printer-issue-resolved-in-win7/"><u>Offline Printer Issue Resolved in Win7</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/optimizing-your-project-b-roll-utilization-tips/"><u>Optimizing Your Project  B-Roll Utilization Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-printer-problem-resolved-and-happy-again/"><u>Post-Update Printer Problem: Resolved and Happy Again!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-service-recovered-on-windows-7-desktop/"><u>Print Service Recovered on Windows 7 Desktop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unresponsive-due-to-missing-os-driver/"><u>Printer Unresponsive Due to Missing OS Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-steps-to-revive-asus-camera/"><u>Quick Steps to Revive ASUS Camera</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-scanner-troubleshooting-win10/"><u>Reconnect Scanner: Troubleshooting Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-communication-breakdown-with-print-server/"><u>Resolved: Communication Breakdown with Print Server</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-offline-canon-printer-immediately/"><u>Revive Offline Canon Printer Immediately</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-blueprint-to-thriving-in-spotify-ads/"><u>The Ultimate Blueprint to Thriving in Spotify Ads</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-tecno-pop-7-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Tecno Pop 7 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-non-printing-issues-five-tactics-to-get-your-canon-running-in-windows-11/"><u>Troubleshoot Non-Printing Issues: Five Tactics to Get Your Canon Running in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooted-epson-printer-malfunction/"><u>Troubleshooted Epson Printer Malfunction</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-a-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>Updated 2024 Approved A Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-scanner-reactivated-without-fuss/"><u>Win11: Scanner Reactivated Without Fuss</u></a></li>
</ul></div>
