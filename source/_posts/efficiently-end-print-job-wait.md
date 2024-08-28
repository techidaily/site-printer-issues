---
title: Efficiently End Print Job Wait
date: 2024-08-27T02:19:59.909Z
updated: 2024-08-28T02:19:59.909Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Efficiently End Print Job Wait
excerpt: This Article Describes Efficiently End Print Job Wait
keywords: Print Job Cancellation,Quick Print Termination,Immediate Print Stop,Print Workflow Interruption,Optimize Print Job Ending,Print Management Strategies,Latency Reduction in Printing
thumbnail: https://thmb.techidaily.com/750c1d86ce393517a7e8e0f28b8261fcac89b61944729e317e412d6180bd4eb2.jpg
---

## Efficiently End Print Job Wait

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
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-start-broadcasting-now-instagram-live-guide/"><u>[New] 2024 Approved  Start Broadcasting Now  Instagram Live Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-examining-the-gaps-in-todays-vr-narratives/"><u>[Updated] Examining the Gaps in Today's VR Narratives</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-game-changer-how-to-optimize-your-fb-giveaway-posts/"><u>2024 Approved  The Game-Changer  How to Optimize Your FB Giveaway Posts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-bug-fixed-ready-to-go/"><u>B200 Bug Fixed, Ready to Go!</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/blending-beats-fusion-studios-guide-to-cohesive-sound/"><u>Blending Beats  Fusion Studio's Guide to Cohesive Sound</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-guide-on-unlocking-iphone-se-with-a-broken-screen-drfone-by-drfone-ios/"><u>Complete Guide on Unlocking iPhone SE with a Broken Screen? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-with-hp-print-on-w7-resolved/"><u>Connectivity Woes with HP Print on W7 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dispelling-hp-printers-fatal-mistake-0xoxc4eb827f/"><u>Dispelling HP Printer's Fatal Mistake 0xOXC4EB827F</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dive-deep-into-single-platform-livestreaming-with-onestream/"><u>Dive Deep Into Single-Platform Livestreaming with OneStream</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-print-problem-decoded-error-x97/"><u>Epson's Print Problem Decoded: Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574106588-fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-issue-hp-printer-not-recognized-by-os/"><u>Hardware Issue: HP Printer Not Recognized by OS</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/how-to-edit-videos-with-quicktime-on-mac-step-by-step-guide-for-2024/"><u>How to Edit Videos with QuickTime on Mac Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-nokia-c12-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-unfreeze-an-offline-brother-printer-online/"><u>How To Unfreeze an Offline Brother Printer Online</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-glamour-a-guide-to-video-color-balance/"><u>In 2024, YouTube Glamour  A Guide to Video Color Balance</u></a></li>
<li><a href="https://win-solutions.techidaily.com/master-the-sequel-boosting-frame-rate-and-smoothness-in-dragons-dogma-2-gaming-sessions/"><u>Master the Sequel: Boosting Frame Rate & Smoothness in Dragon's Dogma 2 Gaming Sessions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-canon-printer-wont-respond-what-now/"><u>My Canon Printer Won't Respond, What Now?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimizing-mf4770n-driver-for-w11-w8-w7/"><u>Optimizing MF4770n Driver for W11, W8, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canon-printer-puzzles-in-windows-11-here-are-five-easy-solutions/"><u>Overcome Canon Printer Puzzles in Windows 11 - Here Are Five Easy Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-vivo-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Vivo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-spooler-stopped-on-pc-help-needed/"><u>Printer Spooler Stopped on PC, Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-powerhouse-latest-updates-for-dell-printer-windows-7/"><u>Printing Powerhouse: Latest Updates for Dell Printer WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-scanner-link-to-computer-in-win10/"><u>Re-Establishing Scanner Link to Computer in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivate-and-resume-fixing-your-disconnected-printer/"><u>Reactivate and Resume: Fixing Your Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-stuck-print-head/"><u>Remedying Stuck Print Head</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-network-failure/"><u>Resolved Printer Network Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-activation-a-win10-fix-guide/"><u>Scanner Activation: A Win10 Fix Guide</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-wont-play-on-civi-3-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on Civi 3</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-spooler-from-freaking-out/"><u>Stop Windows Print Spooler From Freaking Out</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-impact-on-commerce-leveraging-chatgpt-and-whispers-powerful-apis/"><u>The Impact on Commerce: Leveraging ChatGPT and Whisper's Powerful APIs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-unraveling-the-latest-in-computer-gadgets-and-performance/"><u>Tom's Tech Insights: Unraveling the Latest in Computer Gadgets and Performance</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-10-printer-software/"><u>Troubleshoot Windows 10 Printer Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-11-printing-glitches/"><u>Troubleshoot Windows 11 Printing Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-full-potential-of-hp-printers-in-windows/"><u>Unlocking the Full Potential of HP Printers in Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-video-editing-on-a-shoestring-16-free-and-intuitive-movie-makers/"><u>Updated In 2024, Video Editing on a Shoestring 16 Free and Intuitive Movie Makers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808096145-usb-selective-suspend-everything-you-need-to-know-about-it/"><u>USB Selective Suspend - Everything You Need to Know About It!</u></a></li>
</ul></div>
