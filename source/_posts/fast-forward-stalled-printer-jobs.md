---
title: Fast-Forward Stalled Printer Jobs
date: 2024-08-22T09:39:58.407Z
updated: 2024-08-23T09:39:58.407Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fast-Forward Stalled Printer Jobs
excerpt: This Article Describes Fast-Forward Stalled Printer Jobs
keywords: Printer Job Stall,Fast-Forward Printer Error,Print Spooler Stalling,Printer Queue Management,Resolve Print Job Failure,Print Spooler Service Errors,Optimize Print Job Performance
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## Fast-Forward Stalled Printer Jobs

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
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
<li><a href="https://video-capture.techidaily.com/updated-effortlessly-integrating-obs-into-your-mac-step-by-step-guide-for-2024/"><u>[Updated] Effortlessly Integrating OBS Into Your Mac  Step by Step Guide for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-essential-ipad-recording-tools-3-edition-for-2024/"><u>[Updated] Essential iPad Recording Tools  #3 Edition for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-unveiling-the-prospects-of-splitcam-for-videographers/"><u>[Updated] In 2024, Unveiling the Prospects of SplitCam for Videographers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigating-the-world-of-gopro-streaming-and-social-media-networks-for-2024/"><u>[Updated] Navigating the World of Gopro Streaming and Social Media Networks for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024-3-fixes-to-connect-hp-printer-to-laptop/"><u>2024 | 3 Fixes to Connect HP Printer to Laptop</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-guidelines-for-effective-video-integration-in-teaching/"><u>2024 Approved  Guidelines for Effective Video Integration in Teaching</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-make-your-favorite-tiktok-sound-a-phones-custom-ringtone/"><u>2024 Approved  Make Your Favorite TikTok Sound a Phone's Custom Ringtone</u></a></li>
<li><a href="https://extra-information.techidaily.com/action-ammo-face-off-prodigy-cameras-compared-black-vs-session/"><u>Action Ammo Face-Off  Prodigy Cameras Compared – Black vs Session</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ease-into-plc-error-resolution/"><u>Ease Into PLC Error Resolution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://extra-hints.techidaily.com/immersion-in-metaverse-leading-hmds-reviewed/"><u>Immersion in Metaverse  Leading HMDs Reviewed</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-a15-4g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy A15 4G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-vivo-x100-pro-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Vivo X100 Pro Android SIM Unlock APK</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-the-capacity-for-storing-videos-on-large-scale-drives-64128gb/"><u>In 2024, Understanding the Capacity for Storing Videos on Large-Scale Drives (64/128GB)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/innovative-virtual-bike-trails-unveiled/"><u>Innovative Virtual Bike Trails Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-tips-mfc-9330cdw-driver/"><u>Installation Tips: MFC-9330CDW Driver</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-a-detailed-review-and-alternatives-of-vocaloid6-voice-generator-for-2024/"><u>New A Detailed Review & Alternatives of VOCALOID6 Voice Generator for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-horizons-in-workspace-tech-converging-hp-and-laptops-flawlessly/"><u>New Horizons in Workspace Tech - Converging HP and Laptops Flawlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-unprinted-pages-on-hp-printer-now/"><u>No More Unprinted Pages on HP Printer Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-failure-in-hp-model-xyz/"><u>Overcome Printing Failure in HP Model XYZ</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-puzzle-resolved-error-0x00000709/"><u>Printer Setup Puzzle: Resolved Error 0X00000709</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-oppo-a58-4g-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Oppo A58 4G Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnecting-brothers-print-to-end-offline-status-woes/"><u>Reconnecting Brothers Print to End Offline Status Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-respondent-printer-on-windows-3x-edition/"><u>Revive Non-Respondent Printer on Windows 3.x Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-printer-solutions-unveiled/"><u>Speedy Printer Solutions Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stopping-printer-service-pauses-solutions-for-windows-10w7w11/"><u>Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-driven-print-screws/"><u>Unblocking Driven Print Screws</u></a></li>
<li><a href="https://extra-information.techidaily.com/unforgettable-stop-motion-films-the-top-15-list/"><u>Unforgettable Stop-Motion Films - The Top 15 List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-hp-paper-jam-resolved/"><u>Win11 HP Paper Jam Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-inactivity-post-sleep-fix-guide/"><u>Win7 Printer Inactivity Post-Sleep: Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-issues-quick-solutions-needed/"><u>Windows 11 Printer Issues - Quick Solutions Needed</u></a></li>
</ul></div>
