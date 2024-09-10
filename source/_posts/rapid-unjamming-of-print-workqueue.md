---
title: Rapid Unjamming of Print Workqueue
date: 2024-09-09T01:23:57.767Z
updated: 2024-09-10T01:23:57.767Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Unjamming of Print Workqueue
excerpt: This Article Describes Rapid Unjamming of Print Workqueue
keywords: Rapid Workqueue Solutions,Fast-Tracking Print Processes,Workqueue Management,Efficient Printwork Queue Optimization,Unjamming Printer Workqueue Techniques,Streamlining Print Operations,Printer Workqueue Performance Improvement
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Rapid Unjamming of Print Workqueue

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.
<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/os-compatibility-unable-to-connect-to-hp-print-service-on-windows/"><u>[OS Compatibility] - Unable to Connect to HP Print Service on Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-sprinkle-life-into-your-videos-free-text-tricks/"><u>2024 Approved  Sprinkle Life Into Your Videos  Free Text Tricks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-transforming-movs-to-mp4mkv-on-pc/"><u>2024 Approved  Transforming MOVs to MP4/MKV on PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transforming-video-makeup-through-color-alignment/"><u>2024 Approved  Transforming Video Makeup Through Color Alignment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-clearing-print-job-queue/"><u>Accelerate Clearing Print Job Queue</u></a></li>
<li><a href="https://facebook.techidaily.com/avoiding-pitfalls-humorous-interactions-on-facebook/"><u>Avoiding Pitfalls: Humorous Interactions on Facebook</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-realme-v30-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Realme V30 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/charting-the-course-of-monetization-for-creator-economy-on-youtubeshorts/"><u>Charting the Course of Monetization for Creator Economy on YouTubeshorts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-installation-of-upgraded-printer-drivers/"><u>Correct Installation of Upgraded Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-devices-exhibiting-continuous-sheet-outputs/"><u>Epson Devices Exhibiting Continuous Sheet Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-error-continuous-sheet-replacement/"><u>Epson Printer Error: Continuous Sheet Replacement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-phantom-errors-in-epson-printer/"><u>Fixed Phantom Errors in Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-print-misstep-code-oxc4eb827f/"><u>Fixing HP Print Misstep: Code OXC4EB827F</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-add-fonts-to-after-effects-for-2024/"><u>How to Add Fonts to After Effects for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-get-an-offline-printer-running-on-vistaxp/"><u>How to Get an Offline Printer Running on Vista/XP</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-oppo-f25-pro-5g-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Oppo F25 Pro 5G Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-worklift-printer-setup-and-use/"><u>HP WorkLift Printer Setup and Use</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-action-on-queued-print-processes/"><u>Immediate Action on Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-plug-in-for-print-devices/"><u>Immediate Plug-In for Print Devices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-phantom-3-confrontation-illusionist-4-enters/"><u>In 2024, Phantom 3 Confrontation  Illusionist 4 Enters</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-printer-device-windows-710-troubleshooting-steps/"><u>Missing Printer Device? Windows 7/10 Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-non-printing-issues-brother-printer-windows-edition/"><u>Navigating Non-Printing Issues: Brother Printer, Windows Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inkless-printer-issues/"><u>Overcoming Inkless Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-nozzle-necessity-neglected/"><u>Post-Update, Nozzle Necessity Neglected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unlisted-solutions-for-windows-xp-11/"><u>Printer Unlisted: Solutions for Windows XP-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/procedure-connecting-hp-officejet-to-windows-device/"><u>Procedure: Connecting HP Officejet to Windows Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-non-authentic-printer-use-case/"><u>Resolved: Non-Authentic Printer Use Case</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speeding-up-prints-simplest-fixes/"><u>Speeding Up Prints: Simplest Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-to-fix-silent-hp-multi-fax-printers/"><u>Techniques to Fix Silent HP Multi-Fax Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-win-10-printer-disruptions-success-story/"><u>The End of Win 10 Printer Disruptions - Success Story</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-check-comparing-bandicams-performance-to-competitors/"><u>The Ultimate Check  Comparing Bandicam's Performance to Competitors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-guide-flawlessly-handle-pcl-xl-mistakes/"><u>Troubleshooting Guide: Flawlessly Handle PCL XL Mistakes</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-s18-pro-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo S18 Pro Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-epson-error-code-x97/"><u>Zeroing In on Epson Error Code X97</u></a></li>
</ul></div>
