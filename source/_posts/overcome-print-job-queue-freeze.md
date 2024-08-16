---
title: Overcome Print Job Queue Freeze
date: 2024-08-15T03:15:30.034Z
updated: 2024-08-16T03:15:30.034Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Overcome Print Job Queue Freeze
excerpt: This Article Describes Overcome Print Job Queue Freeze
keywords: Print Job Management,Prevent Print Queue Bottlenecks,Resolve Printer Queue Errors,Print Job Optimization Techniques,Overcoming Printer Queue Halt Issues,Synchronized Printing Processes,Advanced Print Queue Management
thumbnail: https://thmb.techidaily.com/fb4a67269b09db2a7f2f5849b8bae34d180258d63241c7d8da96fca41cce9da8.jpg
---

## Overcome Print Job Queue Freeze

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
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<li><a href="https://printer-issues.techidaily.com/fix-windows-7-devices-not-recognizing-post-sleep-usb-printers/"><u>[Fix] Windows 7 Devices Not Recognizing Post Sleep USB Printers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-effortless-solutions-for-instagram-video-archiving/"><u>[New] 2024 Approved  Effortless Solutions for Instagram Video Archiving</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-when-and-why-should-you-post-on-instagram/"><u>[New] In 2024, When and Why Should You Post on Instagram?</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-takes-2022-skating-spectaculars/"><u>[New] Top Takes - 2022 Skating Spectaculars</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-troubleshoot-unseen-network-printer-on-windows-pcs/"><u>[OS Troubleshoot] Unseen Network Printer on Windows PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-mastering-audio-prime-9-mic-recording-solutions/"><u>[Updated] 2024 Approved  Mastering Audio  Prime 9 Mic Recording Solutions</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-panoramic-lenses-vs-depth-filled-images/"><u>[Updated] 2024 Approved  Panoramic Lenses vs Depth-Filled Images</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-the-art-of-muting-background-sounds-in-skype/"><u>[Updated] 2024 Approved  The Art of Muting Background Sounds in Skype</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-copyright-compliance-and-photovideo-sharing/"><u>[Updated] Copyright Compliance & Photo/Video Sharing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-crafting-content-cultivating-capital-your-videography-voyage/"><u>[Updated] Crafting Content, Cultivating Capital  Your Videography Voyage</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-elevating-your-snaps-with-expert-guided-boomerangs-for-2024/"><u>[Updated] Elevating Your Snaps with Expert-Guided Boomerangs for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-strategies-for-profitable-youtube-videos-for-2024/"><u>[Updated] Essential Strategies for Profitable YouTube Videos for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-immersive-escapes-delving-into-jaunt-vr/"><u>[Updated] In 2024, Immersive Escapes  Delving Into Jaunt VR</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-asgardian-crusade-final-quest/"><u>[Updated] In 2024, The Asgardian Crusade  Final Quest</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-unleashing-shareability-secrets-of-trending-on-fb/"><u>[Updated] In 2024, Unleashing Shareability  Secrets of Trending on Fb</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-viral-video-quarterly-watch/"><u>2024 Approved  Viral Video Quarterly Watch</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-iphone-6-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase iPhone 6 When Its Locked Within Seconds</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-stuck-printer-operations/"><u>Accelerate Stuck Printer Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-error-xf09-on-epson-devices/"><u>Addressing Error #XF09 on Epson Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alleviated-printer-network-disconnect/"><u>Alleviated Printer Network Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-issue-eliminated/"><u>B200 Issue Eliminated</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-print-processes-revealed/"><u>Brisk Print Processes Revealed</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpts-limitations-exposed-3-excel-tasks-it-simply-cant-handle/"><u>ChatGPT's Limitations Exposed: 3 Excel Tasks It Simply Can't Handle</u></a></li>
<li><a href="https://article-posts.techidaily.com/clearer-visions-advanced-techniques-for-zooming-photos-and-videos/"><u>Clearer Visions  Advanced Techniques for Zooming Photos & Videos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-printer-conflicts-in-windows/"><u>Clearing Up Printer Conflicts in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/djis-edge-shifted-the-ultimate-mavic-air-vs-spark-showdown/"><u>DJI's Edge Shifted  The Ultimate Mavic Air Vs. Spark Showdown</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-vivo-y100-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Vivo Y100 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-operation-windows-compatible-driver-for-officejet-pro-8600/"><u>Efficient Operation: Windows Compatible Driver for Officejet Pro 8600</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-connect-canon-printer-online/"><u>Effortlessly Connect Canon Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-start-to-finish-complete-xvideostudioinsight-for-2024/"><u>From Start to Finish  Complete XVideoStudioInsight for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-video-to-audio-quickly-create-mp3-from-youtube-on-mac-for-2024/"><u>From Video to Audio  Quickly Create MP3 From YouTube on Mac for 2024</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-realme-narzo-60-pro-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Realme Narzo 60 Pro 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-clear-print-head-conflict-on-win-1011/"><u>How To Clear Print Head Conflict on Win 10/11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-from-iphone-12-pro-by-drfone-ios/"><u>How To Remove the Two Factor Authentication From iPhone 12 Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-stop-and-repair-spooler-on-windows-versions-7-11/"><u>How to Stop and Repair Spooler on Windows Versions 7-11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-90-pro-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Honor 90 Pro PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-non-responsive-printer-service-windows/"><u>Immediate Fixes for Non-Responsive Printer Service (Windows)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-htc-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your HTC Device SIM</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-from-apple-iphone-6s-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID from Apple iPhone 6s</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-f34-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy F34 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-picks-a-list-of-must-play-google-cardboard-vr-games/"><u>In 2024, Premium Picks  A List of Must-Play Google Cardboard VR Games</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-rejoined-print-device/"><u>Instantly Rejoined Print Device</u></a></li>
<li><a href="https://extra-skills.techidaily.com/integrating-cg-centrals-luts-into-vfx-production-flows-for-2024/"><u>Integrating CG Central's Luts Into VFX Production Flows for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-your-v305-printing-fresh-with-windows-updates/"><u>Keep Your V305 Printing Fresh with WIndows Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-canon-printer-is-playing-hard-to-respond/"><u>My Canon Printer Is Playing Hard To Respond</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unforeseen-setup-snag-found/"><u>Printer's Unforeseen Setup Snag Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-wont-print-all-pages-2024-fix/"><u>Printers Won't Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-silent-hp-printers/"><u>Quick Fixes for Silent HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-top-5-methods-to-resolve-canon-printer-print-issue-in-windows-11/"><u>Quick Fixes: Top 5 Methods to Resolve Canon Printer Print Issue in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-printer-driver-crashes-on-windows-11/"><u>Resolve Printer Driver Crashes on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seeking-solutions-for-print-device-driver-failure-in-windows-os/"><u>Seeking Solutions for Print Device Driver Failure in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-printing-after-update-woes-ended/"><u>Smooth Printing After Update Woes Ended</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-non-responsive-print-devices/"><u>Solutions for Non-Responsive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-blank-pages-fixing-brother-printer-not-printing-in-win/"><u>Stop Blank Pages: Fixing Brother Printer Not Printing in Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-printing-on-windows-11-lets-fix-it/"><u>Trouble Printing on Windows 11? Let's Fix It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-errors/"><u>Troubleshooting HP Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-unresponsive-hp-devices/"><u>Troubleshooting Unresponsive HP Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-microsoft-word-is-there-a-cost-free-alternative-available/"><u>Unlocking Microsoft Word: Is There a Cost-Free Alternative Available?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-malfunction-mystery/"><u>Unraveling Printer Malfunction Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/updating-drives-with-mf4770n-for-windows-1087/"><u>Updating Drives with MF4770n for Windows 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-10-upgrade-print-says-no/"><u>Win 10 Upgrade - Print Says No</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-earnings-per-thousand-views-explained-for-2024/"><u>YouTube Earnings Per Thousand Views Explained for 2024</u></a></li>
</ul></div>
