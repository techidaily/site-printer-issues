---
title: Fix 'Print Job Stuck in Queue' Quickly
date: 2024-08-22T09:43:47.979Z
updated: 2024-08-23T09:43:47.979Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fix 'Print Job Stuck in Queue' Quickly
excerpt: This Article Describes Fix 'Print Job Stuck in Queue' Quickly
keywords: Resolve Printer Queue Error,Quick Fix for Print Job Delay,Print Job Stuck Solution,Fix Printer Queue Blockage,Unblock Print Job Instantly,Quickprint Troubleshooting Tips,Efficient Printer Queue Management,Print Job Stuck,Queue Issue Resolution,Print Queue Troubleshooting,Fix Print Job Hangup,Printing Queue Stall Fix,Quickly Resolve Print Job Queue,Cancel Stuck Print Job
thumbnail: https://thmb.techidaily.com/750c1d86ce393517a7e8e0f28b8261fcac89b61944729e317e412d6180bd4eb2.jpg
---

## Fix 'Print Job Stuck in Queue' Quickly

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
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
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
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-a-filmmakers-essentials-the-quintessential-5-camera-strategies/"><u>[New] A Filmmaker's Essentials  The Quintessential 5 Camera Strategies</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevating-your-channels-identity-with-titles-for-2024/"><u>[New] Elevating Your Channel's Identity with Titles for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/avigating-to-the-shadows-of-youtube-videos/"><u>[New] Navigating to the Shadows of YouTube Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-ultimate-list-of-exciting-pc-clickers-you-cant-miss-for-2024/"><u>[New] The Ultimate List of Exciting PC Clickers You Can't Miss for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-engaging-effectively-in-online-google-meet-talks-for-2024/"><u>[Updated] Engaging Effectively in Online Google Meet Talks for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-instantly-post-videos-on-twitter-using-phones-skipping-retweets/"><u>[Updated] In 2024, Instantly Post Videos on Twitter Using Phones, Skipping Retweets</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-nokia-c300-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Nokia C300 FRP</u></a></li>
<li><a href="https://extra-resources.techidaily.com/above-the-clouds-unveiled-best-online-portals-for-hd-skies-for-2024/"><u>Above the Clouds Unveiled  Best Online Portals for HD Skies for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-disabled-printer-problem-detected/"><u>Active Directory Disabled - Printer Problem Detected</u></a></li>
<li><a href="https://win-able.techidaily.com/alienware-command-center-malfunction-heres-how-to-restore-its-functionality/"><u>Alienware Command Center Malfunction? Here's How to Restore Its Functionality</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/asetek-stops-issuing-sales-forecasts-due-to-major-client-order-cancellations/"><u>Asetek Stops Issuing Sales Forecasts Due to Major Client Order Cancellations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/deactivate-stalled-print-job-queue-fastly/"><u>Deactivate Stalled Print Job Queue Fastly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-steps-to-tackle-pcl-xl-setbacks/"><u>Effortless Steps to Tackle PCL XL Setbacks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-velocity-now/"><u>Enhance Printer Velocity Now!</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/tial-steps-for-seamless-youtube-video-loops-for-2024/"><u>Essential Steps for Seamless YouTube Video Loops for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/finding-sound-in-silence-3-cost-free-methods-to-music-enrich-your-videos/"><u>Finding Sound in Silence  3 Cost-Free Methods to Music-Enrich Your Videos</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/flying-high-with-the-blade-blh4100-a-thrilling-rtf-rc-chopper-review/"><u>Flying High with the Blade BLH4100 - A Thrilling RTF RC Chopper Review</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-page-failure-resolved/"><u>HP Printer: Page Failure Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-windows-11-printer-work-again/"><u>Make Windows 11 Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigate-and-rectify-brother-printer-not-print-issue-on-windows-10/"><u>Navigate and Rectify Brother Printer Not Print Issue on Windows 10</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-converting-audio-to-text/"><u>New In 2024, Converting Audio to Text</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-issues-in-print-device-installation/"><u>No Issues in Print Device Installation</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimizing-your-experience-with-fixes-for-mass-effect-series-audio-interruptions/"><u>Optimizing Your Experience with Fixes for Mass Effect Series Audio Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overhauling-hp-printers-error-code-oxc4eb827f/"><u>Overhauling HP Printer's Error: Code OXC4EB827F</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-troubles-try-these-5-simple-ways-to-help-your-canon-print-on-windows-11/"><u>Print Troubles? Try These 5 Simple Ways to Help Your Canon Print on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-errors-resolving-them-in-windows-11/"><u>Printer Errors: Resolving Them in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-showing-up-a-guide-for-windows-users/"><u>Printer Not Showing Up: A Guide for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-brother-printer-issues-in-win1110/"><u>Quick Tips for Brother Printer Issues in Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-cups-errors-streamline-win10-printer-services/"><u>Rectify CUPS Errors: Streamline WIN10 Printer Services</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-printer-driver-glitches-on-win10-pc/"><u>Repair Printer Driver Glitches on WIN10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-sync-with-print-devices/"><u>Restoring Sync with Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-reports-with-paper-less-prints/"><u>Revolutionizing Reports with Paper-Less Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/saving-photo-printouts-from-failures/"><u>Saving Photo Printouts From Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-print-service-non-responsive/"><u>Solved: Print Service Non-Responsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-restore-your-canons-connectivity/"><u>Step-by-Step Guide to Restore Your Canon's Connectivity</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-updating-your-canon-mx49er-driver-for-pcs/"><u>Step-by-Step Guide: Updating Your Canon MX49er Driver for PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-wasted-time-fixing-windows-78s-non-operational-spooler/"><u>Stop Wasted Time: Fixing Windows 7/8'S Non-Operational Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-your-canon-printers-online-access/"><u>Streamlining Your Canon Printer's Online Access</u></a></li>
<li><a href="https://extra-resources.techidaily.com/streamlining-zoom-features-on-your-chromebook/"><u>Streamlining Zoom Features on Your Chromebook</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-epsons-puzzling-error-x97/"><u>Tackling Epson's Puzzling Error X97</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-xiaomi-redmi-note-12-proplus-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Xiaomi Redmi Note 12 Pro+ 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-installing-model-8720-printer-on-your-computer/"><u>Tutorial: Installing Model 8720 Printer on Your Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-printer-service-on-windows-10-11-7/"><u>Unblocking Printer Service on Windows 10, 11, 7</u></a></li>
<li><a href="https://screen-recording.techidaily.com/win10s-best-screen-capture-and-recording-options-for-2024/"><u>Win10's Best Screen Capture and Recording Options for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-print-problem-devices-unresponsive-post-sleep/"><u>Win7 Print Problem: Devices Unresponsive Post-Sleep</u></a></li>
</ul></div>
