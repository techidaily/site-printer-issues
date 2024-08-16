---
title: Fix ‘Print Job Stuck in Queue’ Quickly
date: 2024-08-15T03:16:19.891Z
updated: 2024-08-16T03:16:19.891Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fix ‘Print Job Stuck in Queue’ Quickly
excerpt: This Article Describes Fix ‘Print Job Stuck in Queue’ Quickly
keywords: Quick Print Job Fix,Resolve Stuck Printer Queue,Stop Printing Errors Immediately,Print Queue Troubleshooting Steps,Prevent Print Job Delays,Printer Queue Management Tips,Expeditious Printer Issue Resolution
thumbnail: https://thmb.techidaily.com/3cd047344d86e8920c72e515095d66dfd7e255dbcb41fa2030513ad2ed26d835.jpg
---

## Fix ‘Print Job Stuck in Queue’ Quickly

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
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-seamless-playback-tips-and-tricks-for-infinite-youtube-views/"><u>[New] 2024 Approved  Seamless Playback  Tips & Tricks for Infinite Youtube Views</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-ken-burns-method-in-camtasia-9-explained-simply/"><u>[New] 2024 Approved  The Ken Burns Method in Camtasia 9 Explained Simply</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-flipping-the-script-on-instagrams-video-content-for-2024/"><u>[New] Flipping the Script on Instagram's Video Content for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-efficient-techniques-for-accessing-and-saving-vimeo-videos/"><u>[New] In 2024, Efficient Techniques for Accessing and Saving Vimeo Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-revolutionize-your-posts-best-igtv-edits-unveiled/"><u>[New] In 2024, Revolutionize Your Posts  Best IGTV Edits Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-deskjet-d1360-printer-drivers-wont-install-in-windows-7-8-8110/"><u>[Resolved] HP Deskjet D1360 Printer Drivers Won’t Install in Windows 7, 8, 8.1,10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-examining-the-potential-of-4-second-subscriptions/"><u>[Updated] 2024 Approved  Examining the Potential of 4-Second Subscriptions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-amalgamate-ppts-for-video-creation/"><u>[Updated] Amalgamate PPTs for Video Creation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-new-horizons-a-tech-upgrade-blueprint/"><u>[Updated] Navigating New Horizons  A Tech Upgrade Blueprint</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlock-the-power-of-persuasion-perfecting-your-shorts-visual-hook/"><u>2024 Approved  Unlock the Power of Persuasion  Perfecting Your Shorts' Visual Hook</u></a></li>
<li><a href="https://extra-information.techidaily.com/auditory-aesthetics-for-slides-infusing-your-ppt-with-tunes-for-2024/"><u>Auditory Aesthetics for Slides  Infusing Your PPT with Tunes for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-problem-resolved/"><u>B200: Problem Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-errors-try-these-fixes-on-windows-1011/"><u>Brother Printer Errors? Try These Fixes on Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/confused-settings-your-printer-misconfigured/"><u>Confused Settings: Your Printer Misconfigured</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dell-v305-aio-printer-driver-update-in-windows-7/"><u>Dell V305 AIO Printer Driver Update in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-the-mystery-of-non-printing-machines/"><u>Dismantling the Mystery of Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-page-gaps-the-2024-printer-fix/"><u>End Page Gaps: The 2024 Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-issue-with-installing-printer/"><u>Fixed Issue with Installing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-communication-error/"><u>Fixed Printer Communication Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fully-functional-page-to-page-printer-printing/"><u>Fully Functional, Page-to-Page Printer Printing</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-erase-iphone-13-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase iPhone 13 Data Permanently | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-distort-pic-using-different-tools/"><u>In 2024, How to Distort Pic Using Different Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-synth-symphony-selecting-superior-dj-templates-for-download/"><u>In 2024, Synth Symphony  Selecting Superior DJ Templates for Download</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-depth-analysis-of-the-renovated-ratchet-and-clank-epic/"><u>In-Depth Analysis of the Renovated Ratchet & Clank Epic</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-canon-printer-step-by-step/"><u>Installing Canon Printer - Step-by-Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-printer-disconnection/"><u>Instantly Resolve Printer Disconnection</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175723043-ips-screen-and-customizable-rgb-lighting-featured-on-budget-friendly-valkyrie-al125-cpu-air-cooler-for-less-than-20-bucks/"><u>IPS Screen & Customizable RGB Lighting Featured on Budget-Friendly Valkyrie AL125 CPU Air Cooler for Less than 20 Bucks!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/networking-issues-fixed-win7-printer-online/"><u>Networking Issues Fixed: Win7 Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printing-blockade-oxc4eb827f/"><u>Overcoming HP Printing Blockade: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-refusing-to-use-all-colors/"><u>Printer Refusing to Use All Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-slow-printers/"><u>Quick Remedies for Slow Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-the-printer-setup-error-for-hp-deskjet-d1360-on-windows-systems/"><u>Resolving the Printer Setup Error for HP Deskjet D1360 on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-and-update-hp-officejet-4630-driver-edition/"><u>Secure & Update: HP Officejet 4630 Driver Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/sleight-of-the-brain-navigating-top-room-riddles-for-2024/"><u>Sleight of the Brain  Navigating Top Room Riddles for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-hp-inkjets-download-and-upgrade-tips/"><u>Streamline Your HP Inkjets - Download and Upgrade Tips</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-vivo-v30-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/transform-your-videos-a-beginners-guide-to-editing-with-windows-movie-maker-for-2024/"><u>Transform Your Videos A Beginners Guide to Editing with Windows Movie Maker for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-locate-canon-pixma-mp620-drivers-on-win10/"><u>Unable to Locate Canon Pixma MP620 Drivers on WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-solving-epson-printing-anomalies/"><u>Understanding and Solving Epson Printing Anomalies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-secrets-of-pcl-xl-repairs/"><u>Unraveling the Secrets of PCL XL Repairs</u></a></li>
</ul></div>
