---
title: Swiftly Displace Queued Print Operations
date: 2024-07-10T17:47:18.094Z
updated: 2024-07-11T17:47:18.094Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swiftly Displace Queued Print Operations
excerpt: This Article Describes Swiftly Displace Queued Print Operations
keywords: Displace Queued Print Operations,Swiftly Execute Printer Jobs,Manage Print Processes,Accelerate Print Queue Management,Printer Job Scheduling Optimization,Efficient Print System Transition,Immediate Handling of Printer Tasks
thumbnail: https://thmb.techidaily.com/d08434487f817b4e37cfe7558cadbd43386d2a1219d74867c43320f3c0faf48e.jpg
---

## Swiftly Displace Queued Print Operations

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
<li><a href="https://printer-issues.techidaily.com/finding-the-right-hp-d1360-print-drivers-in-windows-ecosystems/"><u>Finding the Right HP D1360 Print Drivers in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-driver-upgrade-for-w11w8w7/"><u>MF4770n Driver Upgrade for W11/W8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/joining-process-attaching-hp-officejet-to-desktop-pcs/"><u>Joining Process: Attaching HP Officejet to Desktop PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-clearing-print-job-queue/"><u>Accelerate Clearing Print Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-the-whiteout-from-our-print-sources/"><u>Banishing the Whiteout From Our Print Sources</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bugfix-windows-printer-spooler-stuck/"><u>[BUGFIX] Windows Printer Spooler Stuck</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reengage-the-printing-pro-saving-brother-printer-from-isolation/"><u>Reengage the Printing Pro: Saving Brother Printer From Isolation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-toner-depletion-crisis/"><u>Curing Toner Depletion Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-print-job-stuck-in-queue-quickly/"><u>Fix ‘Print Job Stuck in Queue’ Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-printer-output-immediately/"><u>Accelerate Printer Output Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-epsons-enigma-code-0x97/"><u>Eradicating Epson's Enigma: Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-7-printer-status-now-functional/"><u>Windows 7 Printer Status: Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-add-hp-officejet-pro-8720-to-your-pc-step-by-step/"><u>How to Add HP OfficeJet Pro 8720 to Your PC [Step by Step]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winme-printer-no-response-how-to-remedy-it/"><u>WinME Printer No Response - How to Remedy It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resume-printing-with-online-canon-printer-tips/"><u>Resume Printing with Online Canon Printer Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-your-canon-printers-online-access/"><u>Streamlining Your Canon Printer's Online Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-icon-in-win-810-systems/"><u>Unexpectedly No Printer Icon in Win 8/10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-techniques-for-offline-printers/"><u>Troubleshooting Techniques for Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-issue-mp620-driver-not-detected/"><u>[Windows Issue] MP620 Driver Not Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-gaps-in-documents-with-new-fixes/"><u>No More Gaps in Documents with New Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/advanced-drives-mf4770n-software-upgrade-windows/"><u>Advanced Drives: MF4770n Software Upgrade Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-revive-unresponsive-canon-printer/"><u>How to Revive Unresponsive Canon Printer?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-the-printer-after-updating-woes/"><u>Triumph over the Printer After Updating Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-clogged-toner-cartridges/"><u>Addressing Clogged Toner Cartridges</u></a></li>
<li><a href="https://network-issues.techidaily.com/corrected-resolved-windows-no-amd-driver-found/"><u>[CORRECTED] Resolved Windows: No AMD Driver Found</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-11-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 11?</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sky-high-data-capacity-at-zero-cost-top-20-free-cloud-storages-to-explore/"><u>[New] Sky-High Data Capacity at Zero Cost  Top 20 Free Cloud Storages to Explore</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-oppo-k11x-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Oppo K11x without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-exclusive-access-to-top-15-android-virtualization-apps-mac-and-pc-for-2024/"><u>[New] Exclusive Access to Top 15 Android Virtualization Apps (Mac & PC) for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-snapchats-artistic-palette-the-anime-filter-experience/"><u>[Updated] In 2024, Snapchat’s Artistic Palette  The Anime Filter Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-essential-screen-recorder-guide-top-5-for-win-users/"><u>[Updated] Essential Screen Recorder Guide  Top 5 for Win Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-alliance-formula-youtube-partnerships-with-brands-for-2024/"><u>The Alliance Formula  YouTube Partnerships with Brands for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-path-to-prominence-secure-1000-ig-alliesmonth/"><u>[Updated] In 2024, The Path to Prominence  Secure 1,000 IG Allies/Month</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-nokia-c02-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-navigating-the-complexities-of-tiktok-elements-with-ease-for-2024/"><u>[New] Navigating the Complexities of TikTok Elements with Ease for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-clap-quest-unearthing-enthusiastic-reactions-for-2024/"><u>New Clap Quest Unearthing Enthusiastic Reactions for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-in-depth-guide-to-video-money-making-across-platforms/"><u>2024 Approved  In-Depth Guide to Video Money-Making Across Platforms</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-call-logs-from-c32-by-fonelab-android-recover-call-logs/"><u>How to retrieve erased call logs from C32?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-tecno-camon-30-pro-5g-by-drfone-android/"><u>How to Bypass FRP on Tecno Camon 30 Pro 5G?</u></a></li>
<li><a href="https://youtube-web.techidaily.com/izing-profits-from-short-youtube-videos/"><u>Maximizing Profits From Short YouTube Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-apex-capture-vs-lumen-hub/"><u>2024 Approved  Apex Capture VS Lumen Hub</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-from-twitter-videosyoutube-songs-to-scribbled-mp3-files/"><u>[Updated] Step-by-Step  From Twitter Videos/YouTube Songs to Scribbled MP3 Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-unveiling-the-top-5-windows-screen-capturing-utilities/"><u>[Updated] Unveiling The Top 5 Windows Screen Capturing Utilities</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-nokia-c02-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Nokia C02 Phones with Screen Locked and Not | Dr.fone</u></a></li>
</ul></div>
