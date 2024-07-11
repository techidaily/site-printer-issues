---
title: Unhinder Printers at a Gallop
date: 2024-07-10T17:39:45.987Z
updated: 2024-07-11T17:39:45.987Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unhinder Printers at a Gallop
excerpt: This Article Describes Unhinder Printers at a Gallop
keywords: "Identify Key Concepts in the Title,Expand These Keywords Into Related Terms and Long-Tail Phrases:,Analyze Potential Keyword Competition,Unhindered Printers,High-Speed Printers,Streamlined Printing Process,Optimal Printer Performance,Galloping Efficiency,Printer Acceleration Technology,Fast-Paced Printing Solutions"
thumbnail: https://thmb.techidaily.com/46bc9e67353768ac792e1534a64f3c2875130c736cfcb08614e4c3a629de687e.jpg
---

## Unhinder Printers at a Gallop

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
<li><a href="https://printer-issues.techidaily.com/reestablish-printer-with-ease-and-speed/"><u>Reestablish Printer with Ease & Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-to-disable-networked-printers-in-windows/"><u>Techniques to Disable Networked Printers in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-root-cause-of-frequent-printer-service-halt-win/"><u>Finding the Root Cause of Frequent Printer Service Halt (Win)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantaneous-fix-guide-unwinding-pcl-xl-errors/"><u>Instantaneous Fix Guide: Unwinding PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/refining-drive-functionality-mf4770n-windows-update/"><u>Refining Drive Functionality: MF4770n Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-code-b200/"><u>Fixed: Error Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-offline-issue-with-ease-in-this-guide/"><u>Troubleshoot Offline Issue with Ease in This Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-printer-back-in-action-on-windows-11/"><u>Get Your Printer Back in Action on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-steps-to-unlock-printer-output-easy-fixes-for-canon-on-windows-11/"><u>Simple Steps to Unlock Printer Output: Easy Fixes for Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/interpreting-codes-for-inkjet-problems/"><u>Interpreting Codes for Inkjet Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smart-strategies-for-effective-windows-based-hp-printer-setups/"><u>Smart Strategies for Effective Windows-Based HP Printer Setups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-in-pages-a-success-story-for-printers/"><u>Precision in Pages: A Success Story for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-117-fix-for-non-responsive-printer-spooler/"><u>Win 11/7 Fix for Non-Responsive Printer Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-laserjet-errors-the-cure-for-windows-xp7/"><u>HP Laserjet Errors: The Cure for Windows XP/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-joining-officejet-8720-to-home-computers/"><u>Guide: Joining OfficeJet 8720 to Home Computers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-tutorial-setting-up-an-hp-photosmart-x529i/"><u>Connectivity Tutorial: Setting Up an HP PhotoSmart X529i</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-simple-fixes-for-the-future-of-printing-with-laptops-all-in-one-guide/"><u>3 Simple Fixes for the Future of Printing with Laptops - All In One Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unforeseen-setup-snag-found/"><u>Printer's Unforeseen Setup Snag Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-setup-for-a-brand-new-canon-printer/"><u>Effortless Setup for a Brand-New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-simple-steps-to-make-your-canon-printer-work-again/"><u>5 Simple Steps to Make Your Canon Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-suddenly-offline-printers/"><u>Quick Fixes for Suddenly Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-offline-issue-on-windows-7/"><u>[Fixed] Printer Offline Issue on Windows 7</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-10-leading-video-conferencing-software-for-phonespcs/"><u>[New] 10 Leading Video Conferencing Software for Phones/PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-top-ranked-gaming-recorder-tools/"><u>2024 Approved  Top-Ranked Gaming Recorder Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-videotwitter-audible-direct-download/"><u>[Updated] In 2024, VideoTwitter Audible  Direct Download</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-tecno-spark-10-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-video-credits-expertise-top-6-maker-guide-for-2024/"><u>[New] Free Video Credits Expertise - Top 6 Maker Guide for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-meringue-movie-magic-step-by-step-guide-to-ice-cream-capture-for-2024/"><u>[New] Meringue Movie Magic  Step-by-Step Guide to Ice Cream Capture for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-secrets-revealed-saving-video-chats-from-facebook-messenger/"><u>[Updated] Secrets Revealed  Saving Video Chats From Facebook Messenger</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-a-glance-at-your-world-freeze-and-save-windows/"><u>In 2024, A Glance at Your World  Freeze and Save Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-s18-pro-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after S18 Pro has been deleted</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-best-free-vob-video-editing-software-for-beginners/"><u>New 2024 Approved Best Free VOB Video Editing Software for Beginners</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-echoes-of-chuckles-parody-playlists-for-2024/"><u>[Updated] Echoes of Chuckles  Parody Playlists for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-masterclass-banishing-green-on-your-mac-for-youtube-success/"><u>[Updated] Masterclass  Banishing Green on Your Mac for YouTube Success</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719577505926-one-moment-a-day-gain-mastery-over-urdu/"><u>One Moment a Day, Gain Mastery Over Urdu!</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-10-comprehensible-and-cost-free-subtitle-downloader-sites/"><u>[New] 2024 Approved  10 Comprehensible & Cost-Free Subtitle Downloader Sites</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-capture-attention-yt-imagery-and-its-dimension-magic/"><u>In 2024, Capture Attention  YT Imagery and Its Dimension Magic</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-crafting-the-perfect-harmony-fusing-lyrics-and-images-with-lyric-video-maker/"><u>[New] In 2024, Crafting the Perfect Harmony  Fusing Lyrics & Images with Lyric Video Maker</u></a></li>
</ul></div>
