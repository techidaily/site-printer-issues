---
title: Expedite Jammed Print Queue
date: 2024-07-10T17:23:17.309Z
updated: 2024-07-11T17:23:17.309Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expedite Jammed Print Queue
excerpt: This Article Describes Expedite Jammed Print Queue
keywords: Print Spooler Troubleshooting,Printer Queue Management,Jammed Printer Remedies,Improve Print Queue Speed,Printer Hardware Faults,Prevent Printing Errors,Optimize Printer Performance
thumbnail: https://thmb.techidaily.com/6e8a41ece450d9380c701774f844497938589115375c3e1f4cbaa1de7ab99a22.jpg
---

## Expedite Jammed Print Queue

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
<li><a href="https://printer-issues.techidaily.com/overcoming-brother-printers-offline-hurdle/"><u>Overcoming Brother Printer's Offline Hurdle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-bridge-your-printer-and-wifi-with-canon/"><u>Effortlessly Bridge Your Printer and Wifi with Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-canon-mp620-unsupported-in-win11/"><u>[Troubleshooting] Canon MP620 Unsupported in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-network-disconnectivity-in-hp-printers/"><u>Solving Network Disconnectivity in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-issue-mp620-unavailable-in-win10/"><u>Printer Driver Issue: MP620 Unavailable in WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-missing-pages-issue-with-new-printer-update/"><u>End Missing Pages Issue with New Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-slow-printers/"><u>Quick Remedies for Slow Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-issue-printer-drivers-failing-on-w7-10-need-solution/"><u>[Technical Issue] Printer Drivers Failing on W7-10, Need Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-like-a-pro-3-upgrades-to-link-your-printer-and-laptop-seamlessly/"><u>Print Like a Pro: 3 Upgrades to Link Your Printer & Laptop Seamlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt-reactivate-sluggish-uncooperative-printer/"><u>WinNT: Reactivate Sluggish, Uncooperative Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-solved/"><u>Epson Printer Offline [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-domain-service-not-available/"><u>Unable To Access: Domain Service Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stopping-intermittent-spooler-crashes-in-win107-devices/"><u>Stopping Intermittent Spooler Crashes in Win10/7 Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-colored-images/"><u>Unable to Print Colored Images</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugging-and-removing-a-secondary-printer-from-os/"><u>Unplugging and Removing a Secondary Printer From OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-internet-connectivity-for-brother-printer/"><u>Reclaiming Internet Connectivity for Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-offline-workflow-blockage/"><u>Fixed Offline Workflow Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574178084-printer-woes-in-windows-11-help-needed/"><u>Printer Woes in Windows 11 - Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cease-print-slowdown-in-winxp-solution-found/"><u>Cease Print Slowdown in WinXP - Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-shared-printer-usage-concern/"><u>Resolved: Shared Printer Usage Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-connectivity-gaps-for-windows-10-printing-issues/"><u>Bridge Connectivity Gaps for Windows 10 Printing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-software-for-hp-officejet-4630-installation/"><u>Latest Software for HP Officejet 4630 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-non-printing-usb-printers-on-win7-after-suspend/"><u>[Fix] Non-Printing USB Printers on Win7 After Suspend</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-office-efficiency-3-fixes-for-printer-and-laptop-synergy/"><u>Enhancing Office Efficiency: 3 Fixes for Printer & Laptop Synergy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-117-fix-for-non-responsive-printer-spooler/"><u>Win 11/7 Fix for Non-Responsive Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-center-finding-hidden-network-devices-in-win-10/"><u>[Solution Center] Finding Hidden Network Devices in Win 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-recurring-spooler-errors-on-wx-w10-w11/"><u>Combat Recurring Spooler Errors on WX, W10, W11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-favorite-frameworks-top-instagram-filters/"><u>2024 Approved  Favorite Frameworks  Top Instagram Filters</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-tecno-camon-20-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Tecno Camon 20</u></a></li>
<li><a href="https://vp-tips.techidaily.com/explore-innovative-ways-for-sound-capture-in-modern-windows-11-pcs/"><u>Explore Innovative Ways for Sound Capture in Modern Windows 11 PCs</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-your-expertise-in-minutes-essential-youtube-hacks-at-a-glance/"><u>Prove Your Expertise in Minutes  Essential YouTube Hacks at a Glance</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-diy-instagram-videos-simple-steps-to-success/"><u>[Updated] DIY Instagram Videos  Simple Steps to Success</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-motorola-g24-power-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Motorola G24 Power Black and White | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-in-depth-review-videovision-pro-suite-the-new-frontier/"><u>2024 Approved  In-Depth Review  VideoVision Pro Suite - The New Frontier</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-videotwit-grabber-capture-tweets-visuals-for-ios/"><u>[New] 2024 Approved  VideoTwit Grabber  Capture Tweets' Visuals for iOS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/jumpstart-your-cash-with-these-8-innovative-tiktok-methods/"><u>Jumpstart Your Cash with These 8 Innovative TikTok Methods</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-cut-trim-and-edit-top-10-free-video-software-for-windows-10/"><u>Updated In 2024, Cut, Trim, and Edit Top 10 Free Video Software for Windows 10</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-discover-the-best-online-lyric-video-makers-for-your-music/"><u>Updated In 2024, Discover the Best Online Lyric Video Makers for Your Music</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-vivo-t2x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-spark-10c-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Spark 10C using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-discovering-the-tech-behind-dji-phantom-3-professional/"><u>[New] 2024 Approved  Discovering the Tech Behind DJI Phantom 3 Professional</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-leading-audio-transformation-software-listings-for-2024/"><u>[New] Leading Audio Transformation Software Listings for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/archive-exploration-for-social-media-insight-for-2024/"><u>Archive Exploration for Social Media Insight for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-bridge-the-gap-instagram-meets-tiktok/"><u>2024 Approved  Bridge the Gap  Instagram Meets TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-simple-guide-youtube-to-mp3-on-mac/"><u>[Updated] In 2024, Simple Guide  YouTube to MP3 on Mac,</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-cost-breakdown-for-youtube-ads/"><u>2024 Approved  Cost Breakdown for YouTube Ads</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-economical-android-communication-tools-best-of-10-for-2024/"><u>[Updated] Economical Android Communication Tools, Best of 10 for 2024</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-top-10-talking-photo-online-tools-you-have-to-try/"><u>Updated Top 10 Talking Photo Online Tools You Have To Try</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-apex-window-based-podcast-enhancements-top-8-selections/"><u>[Updated] Apex Window-Based Podcast Enhancements  Top 8 Selections</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oppo-reno-11-pro-5gwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Oppo Reno 11 Pro 5Gwith/without a PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-desktop-capture-the-windows-user-guide/"><u>[Updated] Desktop Capture  The Windows User Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-script-to-splendor-animating-effects-unbound/"><u>[Updated] In 2024, From Script to Splendor  Animating Effects Unbound</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-scraps-to-stunning-a-photomontage-journey/"><u>From Scraps to Stunning  A Photomontage Journey</u></a></li>
<li><a href="https://youtube-web.techidaily.com/our-next-favorite-youtuber-might-be-just-a-test-away-six-categories-explored/"><u>[New] Your Next Favorite YouTuber Might Be Just a Test Away  Six Categories Explored</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-remote-management-from-iphone-6-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove remote management from iPhone 6?</u></a></li>
</ul></div>
