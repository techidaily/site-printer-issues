---
title: Accelerate Release for Queued Printer Work
date: 2024-08-27T02:17:43.285Z
updated: 2024-08-28T02:17:43.285Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Release for Queued Printer Work
excerpt: This Article Describes Accelerate Release for Queued Printer Work
keywords: Accelerated Print Release,Queued Printer Workflow Optimization,Reduce Printer Job Queue Time,Improve Printer Efficiency,Fast-Tracking Printer Operations,Enhanced Printer Process Speedup,Streamline Printer Tasks and Release
thumbnail: https://thmb.techidaily.com/95e300018e980291f8509be45c3e360fa38c440741dbce7d87b862e7e88474bb.jpg
---

## Accelerate Release for Queued Printer Work

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
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-effortless-group-video-chat-with-androids-facetime/"><u>[New] Effortless Group Video Chat with Android's Facetime</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-real-life-quantum-mechanics-on-the-silver-screen/"><u>[New] Real-Life Quantum Mechanics on the Silver Screen</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-screen-saver-saviors-how-to-download-and-save-your-favorite-tweets/"><u>[New] Screen Saver Saviors  How to Download and Save Your Favorite Tweets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-turn-your-shorts-into-cash-effective-monetization-techniques/"><u>[New] Turn Your Shorts Into Cash  Effective Monetization Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-not-connected-quickly-and-easily/"><u>[Solved] Printer Not Connected | Quickly & Easily</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-highest-quality-mp4-adapter-for-fb-integration/"><u>[Updated] 2024 Approved  Highest Quality MP4 Adapter for FB Integration</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-capture-cumulative-chronicles/"><u>[Updated] Capture Cumulative Chronicles</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-windows-10-preparing-your-pc-for-the-upgrade/"><u>[Updated] From Windows 10  Preparing Your PC for the Upgrade</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-igniting-virality-with-captivating-fb-giveaway-campaigns/"><u>[Updated] Igniting Virality with Captivating FB Giveaway Campaigns</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-earning-as-a-video-game-geek/"><u>[Updated] In 2024, Earning as a Video Game Geek</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revolutionary-techniques-for-chronological-categorization-of-photographs/"><u>[Updated] Revolutionary Techniques for Chronological Categorization of Photographs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-securing-and-archiving-snapchat-content-on-phone/"><u>[Updated] Securing and Archiving Snapchat Content on Phone</u></a></li>
<li><a href="https://games-able.techidaily.com/a-passionate-pursuit-uncovering-stunning-indie-titles/"><u>A Passionate Pursuit: Uncovering Stunning Indie Titles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-rectified/"><u>Code B200 Rectified</u></a></li>
<li><a href="https://blog-min.techidaily.com/comparing-tablets-pros-and-cons-of-the-latest-nexus-7-versus-nexus-10/"><u>Comparing Tablets: Pros and Cons of the Latest Nexus 7 Versus Nexus 10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/construct-share-worthy-graphics-on-giphy/"><u>Construct Share-Worthy Graphics on Giphy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-interactions-mf4770n-update-in-win11win87-os/"><u>Enhance Device Interactions: MF4770n Update in Win11/Win8/7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-confounding-error-0x97-explained/"><u>Epson's Confounding Error 0X97 Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-print-spooler-keeps-stopping-on-windows-11-and-7/"><u>How to Fix Print Spooler Keeps Stopping on Windows 11 & 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-mend-printer-queue-errors-on-windows-pcs/"><u>How to Mend Printer Queue Errors on Windows PCs</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-oppo-a1x-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-smoothly-incorporate-snap-camera-into-your-meet-calls-for-2024/"><u>How to Smoothly Incorporate Snap Camera Into Your Meet Calls for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-realme-gt-neo-5-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-stopped-printing-fixed-now/"><u>HP LaserJet Stopped Printing - Fixed Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-wireless-printer-setup-tutorial/"><u>HP Wireless Printer Setup Tutorial</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-elevate-visibility-comprehensive-guide-to-video-marketing-titles/"><u>In 2024, Elevate Visibility  Comprehensive Guide to Video Marketing Titles</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-honor-play-7t-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-mf4770n-for-optimal-performance-on-win11-8-7-systems/"><u>Integrate MF4770n for Optimal Performance on Win11, 8, 7 Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-samsung-galaxy-z-flip-5-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Samsung Galaxy Z Flip 5 Phone? Unlock It Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-brother-printer-printing-obstructions-in-windows/"><u>Overcoming Brother Printer Printing Obstructions in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inkjet-breakdowns-quickly/"><u>Overcoming Inkjet Breakdowns Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hardware-added-without-issues/"><u>Printer Hardware Added Without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-fixes-five-steps-to-ensure-your-canon-works-in-windows-11/"><u>Quick Printer Fixes: Five Steps to Ensure Your Canon Works in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-duplicate-documents-in-w11-printer-spool/"><u>Resolve Duplicate Documents in W11 Printer Spool</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-pc-scanning-disabled-in-windows-11/"><u>Resolved: PC Scanning Disabled in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-software-conflicts-in-printing-hardware/"><u>Resolving Software Conflicts in Printing Hardware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resume-printing-with-online-canon-printer-tips/"><u>Resume Printing with Online Canon Printer Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-print-functionality-top-5-tips-and-tricks-for-a-working-canon-printer-in-windows-11/"><u>Revive Print Functionality: Top 5 Tips & Tricks for a Working Canon Printer in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-offline-hp-multi-function-device/"><u>Reviving Offline HP Multi-Function Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-paper-jamming-in-w11-laser-printers/"><u>Solve Paper Jamming in W11 Laser Printers</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-solution-overcoming-steamvrs-error/"><u>Step-by-Step Solution: Overcoming SteamVR's Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-network-printer/"><u>Successfully Installed Network Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/top-five-solutions-to-resolve-your-canon-printer-not-printing-issue-in-windows-11/"><u>Top Five Solutions to Resolve Your Canon Printer Not Printing Issue in Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-unleash-fcpxs-full-potential-a-guide-to-managing-storage-and-freeing-up-space/"><u>Updated In 2024, Unleash FCPXs Full Potential A Guide to Managing Storage and Freeing Up Space</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/vanquish-sims-blackout-trouble/"><u>Vanquish Sims' Blackout Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/victory-fixing-print-issues-in-windows-10/"><u>Victory: Fixing Print Issues in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-hp-printer-connectivity-fixed/"><u>Win HP Printer Connectivity Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winerror-0x00000709-default-printer-restored/"><u>WinError 0X00000709: Default Printer Restored</u></a></li>
</ul></div>
