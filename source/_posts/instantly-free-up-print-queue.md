---
title: Instantly Free Up Print Queue
date: 2024-09-04T06:14:36.975Z
updated: 2024-09-05T06:14:36.975Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantly Free Up Print Queue
excerpt: This Article Describes Instantly Free Up Print Queue
keywords: Print Job Cancellation,Printer Queue Management,Free Up Print Queue Instantly,Cancel Printer Jobs on Windows,How to Clear Print Queue Fast,Printer Spooler Troubleshooting,Print System Error Free Up
thumbnail: https://thmb.techidaily.com/450ec1b84e72a24dc748a4aee1ff3d014e9229d42ab5bd65b8cf7e7b256ed53c.jpg
---

## Instantly Free Up Print Queue

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
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/hardware-setup-cant-get-hp-d1360-to-work-windows-versions-involved/"><u>[Hardware Setup] Can't Get HP D1360 to Work: Windows Versions Involved</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-insert-youtube-links-for-an-engaging-ppt-experience/"><u>[New] 2024 Approved  How to Insert YouTube Links for an Engaging PPT Experience</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-immerse-in-visual-creation-best-3d-model-and-rendering-tools-reviewed/"><u>[New] 2024 Approved  Immerse in Visual Creation  Best 3D Model & Rendering Tools Reviewed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-exclusive-insights-elevating-your-mobizen-screencast-game-for-2024/"><u>[New] Exclusive Insights  Elevating Your Mobizen Screencast Game for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systemissue-printer-spooler-not-functioning-in-windows/"><u>[SYSTEM_ISSUE] Printer Spooler Not Functioning in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-expert-routines-for-flawless-webinar-replays/"><u>[Updated] 2024 Approved  Expert Routines for Flawless Webinar Replays</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-achieve-peak-meeting-performance-a-detailed-zoom-guide-for-2024/"><u>[Updated] Achieve Peak Meeting Performance  A Detailed Zoom Guide for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-designing-the-ideal-youtube-playlist-for-you/"><u>[Updated] Designing the Ideal YouTube Playlist for You</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-your-first-footsteps-in-the-fiscal-world-of-filming/"><u>[Updated] In 2024, Your First Footsteps in the Fiscal World of Filming</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-joyous-film-grabber-assessment/"><u>[Updated] Joyous Film Grabber Assessment</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-premier-choice-the-best-10-recorders-for-tech-talks/"><u>[Updated] Premier Choice  The Best 10 Recorders for Tech Talks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-speak-and-save-voice-memo-on-iphone-2024/"><u>[Updated] Speak & Save - Voice Memo on iPhone 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/winx-mediatrans-iphoneipadipodand-windows-1nx/"><u>『公式』WinX MediaTrans: スムーズなiPhoneからiPad、iPodへのデータ移行&管理 - Windows (1nX)で簡単に操作可能</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-advanced-screen-recording-methods-on-dell-laptops/"><u>2024 Approved  Advanced Screen Recording Methods on Dell Laptops</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-advanced-techniques-in-developing-compelling-customer-success-narratives/"><u>2024 Approved  Advanced Techniques in Developing Compelling Customer Success Narratives</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-examining-the-unseen-history-of-your-social-media-activity/"><u>2024 Approved  Examining the Unseen History of Your Social Media Activity</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-photo-distortions-adobe-photoshop-techniques/"><u>2024 Approved  Mastering Photo Distortions  Adobe Photoshop Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-professional-youtubers-guide-studio-vs-next-generation-beta/"><u>2024 Approved  Professional YouTuber's Guide  Studio Vs. Next Generation Beta</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-guide-to-understanding-electric-motorcycle-systems/"><u>A Comprehensive Guide to Understanding Electric Motorcycle Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-persistent-printer-spooler-issues-in-win-oss/"><u>Addressing Persistent Printer Spooler Issues in Win OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alleviating-hp-printer-error-code-oxc4eb827f/"><u>Alleviating HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-the-spell-of-paper-misfeeding/"><u>Breaking the Spell of Paper Misfeeding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canons-mp620-printer-not-recognized-by-win11/"><u>Canon's MP620 Printer Not Recognized by Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capture-the-airwaves-a-beginners-internet-radio-guide-for-2024/"><u>Capture the Airwaves  A Beginner's Internet Radio Guide for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-common-color-distortion-glitches/"><u>Correcting Common Color Distortion Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-dell-inkjet-driver-upgrade-for-windows-7/"><u>Enhance Printing: Dell Inkjet Driver Upgrade for Windows 7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/excel-file-recovery-recover-corrupt-excel-2007-files-easily-by-stellar-guide/"><u>Excel File Recovery – Recover Corrupt Excel 2007 Files Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-print-job-stuck-in-queue-quickly/"><u>Fix ‘Print Job Stuck in Queue’ Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-shows-error-message-epson/"><u>Fixed: Printer Shows Error Message [Epson]</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/guide-mastering-the-art-of-snapping-screenshots-with-windows/"><u>Guide: Mastering the Art of Snapping Screenshots with Windows ✨🖥️</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-epson-printing-now-continues/"><u>Halted Epson Printing, Now Continues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printers-white-sheets-cured-with-new-solution/"><u>HP Printer’s White Sheets Cured with New Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-win10-printer-performance-and-speed/"><u>Optimize WIN10 Printer Performance and Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-job-queue-freeze/"><u>Overcome Print Job Queue Freeze</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hooked-up-instantly-and-easily/"><u>Printer Hooked Up Instantly & Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-offline-not-responding-errors/"><u>Printer Offline, Not Responding Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quicken-your-print-jobs-easily/"><u>Quicken Your Print Jobs Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-non-print-in-canon-on-windows-with-ease/"><u>Resolve Non-Print in Canon on Windows with Ease</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-printer-disconnection-problem-on-network/"><u>Solutions for Printer Disconnection Problem on Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-solutions-to-overcome-pcl-xl-errors/"><u>Speedy Solutions to Overcome PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-print-process-uncover-these-simple-steps-for-non-printing-canon-on-windows-11/"><u>Streamline Print Process: Uncover These Simple Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-powershell-security-controls/"><u>The Ultimate Guide to PowerShell Security Controls</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-connecting-hp-printer-to-windows-pc/"><u>Tutorial: Connecting HP Printer to Windows PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-fixing-epson-error-x97/"><u>Understanding & Fixing Epson Error X97</u></a></li>
</ul></div>
