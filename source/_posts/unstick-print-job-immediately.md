---
title: Unstick Print Job Immediately
date: 2024-07-29T00:26:14.626Z
updated: 2024-07-30T00:26:14.626Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unstick Print Job Immediately
excerpt: This Article Describes Unstick Print Job Immediately
keywords: Immediate Printer Assistance,Stop Print Job Error,Unstick Printer Jam Remedies,Quick Print Job Recovery,Effective Printer Troubleshooting,Unblock Print Queue Immediately,Instant Print Job Resolution
thumbnail: https://thmb.techidaily.com/063adb3e91f9e707cd239c6a9a79b813aee233d9ca23dd7f8b09ffae8f586c57.jpg
---

## Unstick Print Job Immediately

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-rise-through-the-instagram-rankings-fast/"><u>[New] 2024 Approved  Rise Through the Instagram Rankings Fast</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-rapidly-rise-with-smart-instagram-reel-techniques-for-2024/"><u>[New] Rapidly Rise with Smart Instagram Reel Techniques for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-zd-soft-an-in-depth-guide-to-capture-record-and-edit-videos/"><u>[New] ZD Soft  An In-Depth Guide to Capture, Record & Edit Videos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-error-code-following-device-suspend-w7/"><u>[Solved] Printer Error Code Following Device Suspend, W7</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-elevate-your-videos-youtube-trailers-through-filmora/"><u>[Updated] Elevate Your Videos  YouTube Trailers Through Filmora</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-obs-and-shadowplay-which-streams-better/"><u>[Updated] In 2024, Obs and ShadowPlay - Which Streams Better?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-swift-video-transformation-with-top-8-apps/"><u>[Updated] Swift Video Transformation with Top 8 Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-path-to-your-first-tweet-signing-up-for-twitter-for-2024/"><u>[Updated] The Path to Your First Tweet  Signing Up for Twitter for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-tips-how-to-reinstall-a-lost-print-job/"><u>[Windows Tips] How to Reinstall a Lost Print Job</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expertise-in-mobile-lut-apps/"><u>2024 Approved  Expertise in Mobile LUT Apps</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-navigating-through-top-rated-livestreams-your-guide-to-watching-cricket/"><u>2024 Approved  Navigating Through Top-Rated Livestreams  Your Guide to Watching Cricket</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-postmycam-seeking-top-notch-alternatives/"><u>2024 Approved  PostMyCam  Seeking Top-Notch Alternatives</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bring-to-life-enable-your-silent-canon-print-spooler/"><u>Bring To Life: Enable Your Silent Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-repeated-print-job-errors-in-windows-operating-systems/"><u>Combat Repeated Print Job Errors in Windows Operating Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-connectivity-windows-10-way/"><u>Enhance Printer Connectivity, Windows 10 Way</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhance-your-videos-with-dynamic-camera-movements-camtasa-guide-for-2024/"><u>Enhance Your Videos with Dynamic Camera Movements - Camtasa Guide for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-windows-printer-setup-successfully-fixed/"><u>Error 0X00000709: Windows Printer Setup Successfully Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-error-due-to-active-directory-halt/"><u>Fixed: Printer Error Due to Active Directory Halt</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-link-issues-fastly/"><u>Fixing Printer Link Issues Fastly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/high-performance-drivers-hp-officejet-pro-8600-for-windows-pcs/"><u>High-Performance Drivers: HP Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-it-poco-x6-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Poco X6 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-vivo-y36i-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Vivo Y36i</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-avoiding-common-pitfalls-when-posting-on-instagram/"><u>In 2024, Avoiding Common Pitfalls When Posting on Instagram</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-cartoonize-your-memories-a-simple-guide-to-converting-videos/"><u>In 2024, Cartoonize Your Memories A Simple Guide to Converting Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-changing-up-the-sound-how-to-customize-your-iphone-tunes/"><u>In 2024, Changing Up the Sound  How to Customize Your iPhone Tunes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-pro-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 Pro with a Mask On</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-s18-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Vivo S18 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-stream-ready-steam-gameplay-filming-guide/"><u>In 2024, Stream-Ready  Steam Gameplay Filming Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-understanding-the-impact-of-circular-videography/"><u>In 2024, Understanding the Impact of Circular Videography</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-is-ipogo-not-working-on-realme-v30-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Realme V30? Fixed | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/managing-paper-tray-sensor-problems/"><u>Managing Paper Tray Sensor Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-workflow-swiftly/"><u>Optimize Printing Workflow Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-your-output-inkjet-aio-driver-update-in-windows-7/"><u>Perfect Your Output: Inkjet AIO Driver Update in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-guided-instructions-your-ultimate-guide-to-hp-printer-installation/"><u>Precision-Guided Instructions: Your Ultimate Guide to HP Printer Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-hooked-up-no-friction/"><u>Print Device Hooked Up, No Friction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-solved-for-epson-model/"><u>Print Issue Solved for Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-misdemeanor-by-unknown-system/"><u>Printing Misdemeanor by Unknown System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconciled-printer-not-responding/"><u>Reconciled: Printer Not Responding</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-70-lite-5g-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after 70 Lite 5G has been deleted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstate-scanner-connection-on-windows-10-machine/"><u>Reinstate Scanner Connection on Windows 10 Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-head-alignment-issues-in-w11/"><u>Resolve Print Head Alignment Issues in W11</u></a></li>
<li><a href="https://driver-install.techidaily.com/restore-win11-sound-reinstall-audio-software/"><u>Restore Win11 Sound: Reinstall Audio Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-samsung-print-woes/"><u>Solving Samsung Print Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-recover-an-offline-print-device-from-network/"><u>Steps to Recover an Offline Print Device From Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-jolt-to-halted-print-queues/"><u>Swift Jolt to Halted Print Queues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-resolving-non-responsive-hp-scanners/"><u>Techniques for Resolving Non-Responsive HP Scanners</u></a></li>
<li><a href="https://discord-videos.techidaily.com/the-complete-guide-for-incorporating-funny-and-engaging-gifs-into-your-discord-chats/"><u>The Complete Guide for Incorporating Funny & Engaging GIFs Into Your Discord Chats</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-quick-cure-for-common-pcl-xl-discrepancies/"><u>The Quick Cure for Common PCL XL Discrepancies</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-examination-of-samsung-photo-editor-features-for-2024/"><u>The Ultimate Examination of Samsung Photo Editor Features for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/three-fee-free-methods-for-mixing-audio-in-imovie-projects/"><u>Three Fee-Free Methods for Mixing Audio in iMovie Projects</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-redmi-k70-pro-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi Redmi K70 Pro Location | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-no-response/"><u>Troubleshooting HP Printer No Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ate-list-best-ios-friendly-free-video-editors/"><u>Ultimate List  Best iOS-Friendly, Free Video Editors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-icon-in-win-810-systems/"><u>Unexpectedly No Printer Icon in Win 8/10 Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unfazed-viewing-stop-monitor-flickering-troubles/"><u>Unfazed Viewing: Stop Monitor Flickering Troubles</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-hardware-drivers-in-windows-11-by-drivereasy-guide/"><u>Use Device Manager to reinstall hardware drivers in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/visual-gastronomy-a-chefs-guide-to-film-production/"><u>Visual Gastronomy  A Chef's Guide to Film Production</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zero-in-on-the-problem-discover-these-5-ways-to-help-your-canon-printer-print/"><u>Zero in on the Problem: Discover These 5 Ways to Help Your Canon Printer Print</u></a></li>
</ul></div>
