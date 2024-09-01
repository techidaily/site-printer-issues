---
title: Quickprint Queue Clearance Guide
date: 2024-08-31T04:39:56.948Z
updated: 2024-09-01T04:39:56.948Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quickprint Queue Clearance Guide
excerpt: This Article Describes Quickprint Queue Clearance Guide
keywords: Quick Print Services,Queue Management Strategies,Fast Printer Clearance Tips,Effective Print Operations,Reducing Wait Times at Print Stations,Streamlining Printer Queue Management,Enhancing Office Efficiency with Quickprint Solutions
thumbnail: https://thmb.techidaily.com/ce2b50426ded5a960fb87586d9bc144c1e1a55defefae42789a30b646b9173fc.jpeg
---

## Quickprint Queue Clearance Guide

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
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-tech-tips-snagging-your-fb-status-video/"><u>[New] 2024 Approved  Tech Tips  Snagging Your FB Status Video</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-best-way-to-perform-obs-streaming/"><u>[New] Best Way to Perform OBS Streaming</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-next-gen-gameplay-logging-alternatives-to-fbx-for-2024/"><u>[New] Next-Gen Gameplay Logging Alternatives to FBX for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-quick-snapback-to-loss-prevention-for-2024/"><u>[New] Quick Snapback to Loss Prevention for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-rhythmripper-software-overview-and-testing-for-2024/"><u>[New] RhythmRipper Software Overview & Testing for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-compatibility-unable-to-connect-to-hp-print-service-on-windows/"><u>[OS Compatibility] - Unable to Connect to HP Print Service on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-resounding-beats-audio-studio-mac/"><u>[Updated] 2024 Approved  Resounding Beats  Audio Studio Mac</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024s-top-camera-lineup-for-professional-use/"><u>[Updated] 2024’S Top Camera Lineup for Professional Use</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-guide-to-efficient-telegram-web-use/"><u>[Updated] Step-By-Step Guide to Efficient Telegram Web Use</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-inspirational-cinema-collection-10-movie-gems/"><u>2024 Approved  Inspirational Cinema Collection  10 Movie Gems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-interactive-content-platform-audit-and-rating/"><u>2024 Approved  Interactive Content Platform Audit & Rating</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-utilizing-zoom-services-directly-from-your-inbox-gmail-edition/"><u>2024 Approved  Utilizing Zoom Services Directly From Your Inbox - Gmail Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-y28-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-from-your-apple-iphone-15-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID From Your Apple iPhone 15</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-tale-of-triumph-over-theoretical-paper-trails/"><u>A Tale of Triumph Over Theoretical Paper Trails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-no-print-restoring-functionality-of-brother-printer-winoses/"><u>Conquer No-Print: Restoring Functionality of Brother Printer, WinOSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-installation-of-upgraded-printer-drivers/"><u>Correct Installation of Upgraded Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-enhance-printer-speed/"><u>Effortlessly Enhance Printer Speed</u></a></li>
<li><a href="https://win-dash.techidaily.com/elevate-your-app-management-top-3-methods-for-running-software-as-an-administrator-on-windows-11-and-10-platforms/"><u>Elevate Your App Management: Top 3 Methods for Running Software as an Administrator on Windows 11 & 10 Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-devices-exhibiting-continuous-sheet-outputs/"><u>Epson Devices Exhibiting Continuous Sheet Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-error-continuous-sheet-replacement/"><u>Epson Printer Error: Continuous Sheet Replacement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-print-misstep-code-oxc4eb827f/"><u>Fixing HP Print Misstep: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-worklift-printer-setup-and-use/"><u>HP WorkLift Printer Setup and Use</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-poco-c55-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Poco C55 Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastery-in-motion-an-in-depth-look-at-polarrs-toolset/"><u>Mastery in Motion  An In-Depth Look at Polarr’s Toolset</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-disconnected-printers/"><u>Methods to Reactivate Disconnected Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-printer-device-windows-710-troubleshooting-steps/"><u>Missing Printer Device? Windows 7/10 Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-non-printing-issues-brother-printer-windows-edition/"><u>Navigating Non-Printing Issues: Brother Printer, Windows Edition</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-distort-degrade-and-disrupt-the-best-free-online-glitch-tools/"><u>New Distort, Degrade, and Disrupt The Best Free Online Glitch Tools</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inkless-printer-issues/"><u>Overcoming Inkless Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-nozzle-necessity-neglected/"><u>Post-Update, Nozzle Necessity Neglected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-unlisted-solutions-for-windows-xp-11/"><u>Printer Unlisted: Solutions for Windows XP-11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/procedure-connecting-hp-officejet-to-windows-device/"><u>Procedure: Connecting HP Officejet to Windows Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-printer-lacking-paper-delivery/"><u>Resolved: HP Printer Lacking Paper Delivery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-non-authentic-printer-use-case/"><u>Resolved: Non-Authentic Printer Use Case</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-laser-print-quality-concerns/"><u>Resolving Laser Print Quality Concerns</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/secrets-to-storing-and-viewing-digital-television-shows-for-2024/"><u>Secrets to Storing and Viewing Digital Television Shows for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/six-major-deterrents-preventing-windows-11-upgrade/"><u>Six Major Deterrents Preventing Windows 11 Upgrade</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speeding-up-prints-simplest-fixes/"><u>Speeding Up Prints: Simplest Fixes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/step-by-step-sharing-your-content-on-facebook-for-2024/"><u>Step-by-Step  Sharing Your Content on Facebook for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-non-responding-printer-unit/"><u>Tackled Non-Responding Printer Unit</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-huawei-p60-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-win-10-printer-disruptions-success-story/"><u>The End of Win 10 Printer Disruptions - Success Story</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-plating-palette-techniques-for-food-cinematography-for-2024/"><u>The Plating Palette  Techniques for Food Cinematography for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-guide-flawlessly-handle-pcl-xl-mistakes/"><u>Troubleshooting Guide: Flawlessly Handle PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-back-on-brothers-printer-in-remote-spotlight/"><u>Turn Back on Brothers Printer in Remote Spotlight</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wizard-disconnecting-all-printers/"><u>Windows Wizard: Disconnecting All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-epson-error-code-x97/"><u>Zeroing In on Epson Error Code X97</u></a></li>
</ul></div>
