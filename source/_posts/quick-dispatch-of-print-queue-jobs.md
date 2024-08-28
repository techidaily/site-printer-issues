---
title: Quick Dispatch of Print Queue Jobs
date: 2024-08-27T02:16:18.941Z
updated: 2024-08-28T02:16:18.941Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Dispatch of Print Queue Jobs
excerpt: This Article Describes Quick Dispatch of Print Queue Jobs
keywords: Quick Print Job Dispatch,Fast Print Queue Processing,Efficient Print Service,Rapid Print Job Execution,Reduced Print Job Wait Times,Speedy Printer Queue Management,High-Speed Print Job Handling
thumbnail: https://thmb.techidaily.com/d1baf3dfbbd327d9cbcf98353df44476f218395c1d3282d729e920baf2edbea8.jpg
---

## Quick Dispatch of Print Queue Jobs

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
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
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
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/driver-issue-windows-11-not-supporting-canon-mp620/"><u>[Driver Issue] Windows 11 Not Supporting Canon MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-unable-to-locate-hp-winxo/"><u>[Driver Search Failed] - Unable to Locate HP WINXO</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-use-hashtags-on-instagram/"><u>[Updated] 2024 Approved  How to Use Hashtags on Instagram</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-unlocking-sierra-comprehensive-icloud-drives/"><u>[Updated] 2024 Approved  Unlocking Sierra  Comprehensive iCloud Drives</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-backtracking-visuals-proficient-strategies-for-insta-image-source-for-2024/"><u>[Updated] Backtracking Visuals  Proficient Strategies for Insta Image Source for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-decoding-game-archiving-mastering-roblox-footage-on-apple-systems-for-2024/"><u>[Updated] Decoding Game Archiving  Mastering Roblox Footage on Apple Systems for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-expert-tips-for-fixing-non-displaying-shorts-thumbnails-for-2024/"><u>[Updated] Expert Tips for Fixing Non-Displaying Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-optimize-visual-design-top-10-must-have-type-plugins-for-ae/"><u>[Updated] In 2024, Optimize Visual Design  Top 10 Must-Have Type Plugins for AE</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-top-8-cost-free-android-video-recording-software/"><u>[Updated] In 2024, Top 8 Cost-Free Android Video Recording Software</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-iphones-secret-to-time-extended-videography-for-2024/"><u>[Updated] IPhone's Secret to Time-Extended Videography for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-a-guide-to-blurring-and-eliminating-photo-borders/"><u>2024 Approved  A Guide to Blurring and Eliminating Photo Borders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-networked-video-streaming-with-vlc/"><u>2024 Approved  Navigating Networked Video Streaming with VLC</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-pro-hdr-image-creation-with-photoshop-secrets/"><u>2024 Approved  Pro HDR Image Creation with Photoshop Secrets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-fan-setup-instructions/"><u>Brother CDW Duo Fan Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-wireless-mfc-9330cdw-instructions/"><u>Brother Wireless MFC-9330CDW Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-ink-and-paper-feed-issues-in-hp/"><u>Diagnosing Ink and Paper Feed Issues in HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-hp-officejet-4630-latest-software-releases/"><u>Elevate HP Officejet 4630: Latest Software Releases</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-repeated-print-job-failures-guide-for-windows-107-users/"><u>End Repeated Print Job Failures: Guide for Windows 10/7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-w11-printer-response-times/"><u>Enhance W11 Printer Response Times</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-your-printing-experience-with-canon-windows-10-tips/"><u>Enhance Your Printing Experience with Canon, Windows 10 Tips</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>Fake the Location to Get Around the MLB Blackouts on Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-offline-workflow-blockage/"><u>Fixed Offline Workflow Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-printer-service-spooler-issues/"><u>Fixing Non-Operational Printer Service (Spooler) Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-online-offline-print-status-anomaly/"><u>Fixing Online-Offline Print Status Anomaly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hack-your-way-through-pcl-xl-troubles/"><u>Hack Your Way Through PCL XL Troubles</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-data-retrieval-tool-restore-lost-data-from-honor-x7b-by-fonelab-android-recover-data/"><u>Honor Data Retrieval tool – restore lost data from Honor X7b</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-slow-printing-easily-and-quickly/"><u>How to Fix Slow Printing [Easily & Quickly]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-action-on-queued-printer-work/"><u>Immediate Action on Queued Printer Work</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-enhance-visibility-on-instagram-the-art-of-animated-texts-in-stories/"><u>In 2024, Enhance Visibility on Instagram  The Art of Animated Texts in Stories</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-nokia-g22-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Nokia G22?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/infiltrating-early-adopter-groups-a-guide-to-starfield-trials/"><u>Infiltrating Early Adopter Groups: A Guide to Starfield Trials</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-paper-jamming-concern/"><u>Mended Paper Jamming Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/monochrome-output-despite-color-settings/"><u>Monochrome Output Despite Color Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-setup-of-hp-envy-printers/"><u>Navigating the Setup of HP Envy Printers</u></a></li>
<li><a href="https://games-able.techidaily.com/preempting-compatibility-issues-in-your-next-computer-buy/"><u>Preempting Compatibility Issues in Your Next Computer Buy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-issue-not-showing-up-in-win-810/"><u>Printer Issue: Not Showing Up in Win 8/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-link-functional-print-device/"><u>Quick Link: Functional Print Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/resident-evil-village-troubleshooting-steps-for-seamless-pc-gaming-experience/"><u>Resident Evil Village - Troubleshooting Steps for Seamless PC Gaming Experience</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversed-printing-mishaps-hp-printer-now-solid-and-sure/"><u>Reversed Printing Mishaps: HP Printer Now Solid and Sure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-networked-printer-access/"><u>Revived Networked Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-mf4770n-functions-on-w11w8w7-os/"><u>Streamlining MF4770n Functions on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-solutions-to-printer-delays/"><u>Swift Solutions to Printer Delays</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-comprehensive-roadmap-to-effective-reddit-sharing-for-2024/"><u>The Comprehensive Roadmap to Effective Reddit Sharing for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-for-restarting-non-functional-hp-photo-units/"><u>Tips for Restarting Non-Functional HP Photo Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-troubleshooting-guide/"><u>Windows 11 Printer Troubleshooting Guide</u></a></li>
</ul></div>
