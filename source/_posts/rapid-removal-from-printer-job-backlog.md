---
title: Rapid Removal From Printer Job Backlog
date: 2024-07-10T16:50:24.399Z
updated: 2024-07-11T16:50:24.399Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Removal From Printer Job Backlog
excerpt: This Article Describes Rapid Removal From Printer Job Backlog
keywords: Rapid Printer Job Clearing,Fast Removal of Printer Backlog,Quick Elimination of Print Jobs Queue,Efficient Printer Job Management,Reduce Printer Job Accumulation,Printer Backlog Resolution,Unclogging Printer Print Job Backlog
thumbnail: https://thmb.techidaily.com/3b5dbab902dc8db71b72fe778c491655a451dd9fd6fc0286da7f19ebe4c291dd.jpg
---

## Rapid Removal From Printer Job Backlog

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
<li><a href="https://printer-issues.techidaily.com/from-silence-to-service-restoring-online-status-in-printer/"><u>From Silence to Service: Restoring Online Status in Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-sheetless-anxiety-to-confident-printing/"><u>From Sheetless Anxiety to Confident Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-canon-printer-is-playing-hard-to-respond/"><u>My Canon Printer Is Playing Hard To Respond</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-hp-print-misstep-code-oxc4eb827f/"><u>Fixing HP Print Misstep: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcame-hp-printers-spooler-error/"><u>Overcame HP Printer's Spooler Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-assembly-combining-hp-printer-model-with-computer/"><u>Technical Assembly: Combining HP Printer Model with Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-tips-how-to-reinstall-a-lost-print-job/"><u>[Windows Tips] How to Reinstall a Lost Print Job</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-blank-pages-challenge/"><u>Overcoming HP Printer Blank Pages Challenge</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-inkjet-and-laser-issues-win10-style/"><u>Fix Inkjet & Laser Issues, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-epson-paper-jam/"><u>Overcome Epson Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-perfection-achieved-say-goodbye-to-ghosts/"><u>Print Perfection Achieved: Say Goodbye to Ghosts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-code-b200/"><u>Fixed: Error Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-scanner-on-latest-win10-os/"><u>Reactivating Scanner on Latest Win10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-on-windows-hp-devices/"><u>Unblocking Offline Status on Windows HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-disappearing-printers-in-windows-810/"><u>How to Fix Disappearing Printers in WIndows 8/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unexpected-configuration-blunder/"><u>Printer's Unexpected Configuration Blunder</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-repeated-printer-errors-in-windows-107-environments/"><u>Curing Repeated Printer Errors in Windows 10/7 Environments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-mute-how-to-engage/"><u>Canon Printer Mute - How to Engage?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-up-call-faulty-usb-printers-in-windows-7-mode/"><u>Wake Up Call: Faulty USB Printers in Windows 7 Mode</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-ios-slideshow-software-from-x-to-ios13/"><u>[Updated] Best iOS Slideshow Software From X to IOS13</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-figma-erase-background-elements-seamlessly/"><u>[New] Navigating Figma  Erase Background Elements Seamlessly</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-starting-point-for-film-designers/"><u>[Updated] 2024 Approved  The Starting Point for Film Designers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prime-video-capture-leaders-revealed/"><u>[New] Prime Video Capture Leaders Revealed</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/amplify-video-impact-leading-trackers-for-youtube-ranks/"><u>Amplify Video Impact  Leading Trackers for YouTube Ranks</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-latest-evolution-2023s-samsung-bd-j5900-review/"><u>2024 Approved  The Latest Evolution  2023'S Samsung BD-J5900 Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-media-conversion-from-xml-to-srt-efficiently/"><u>[Updated] Mastering Media Conversion  From XML to SRT Efficiently</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-decoding-instagrams-reels-and-stories-differences-for-2024/"><u>[New] Decoding Instagram's Reels and Stories Differences for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-from-iphone-se-2022-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives From iPhone SE (2022)</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-superior-streams-with-av1-activate-on-youtube/"><u>2024 Approved  Superior Streams with AV1  Activate on YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-iptv-recording-on-various-platforms-for-2024/"><u>[Updated] IPTV Recording on Various Platforms for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-formulating-fascinating-film-moments/"><u>[New] Formulating Fascinating Film Moments</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-guide-to-converting-soundcloud-to-mp3-for-2024/"><u>New The Ultimate Guide to Converting Soundcloud to MP3 for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-unleash-creativity-angled-rotation-mastery-for-youtube-vids/"><u>[Updated] Unleash Creativity  Angled Rotation Mastery for YouTube Vids</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-az-screenshot-mastery-full-app-review/"><u>2024 Approved  AZ Screenshot Mastery - Full App Review</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-navigating-instagrams-voice-customization-features/"><u>In 2024, Navigating Instagram's Voice Customization Features</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovative-methods-for-creating-luts/"><u>[Updated] Innovative Methods for Creating LUTs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-beyond-fcpx-10-video-editing-software-solutions-worth-exploring/"><u>Updated In 2024, Beyond FCPX 10 Video Editing Software Solutions Worth Exploring</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-seek-out-humorous-auditory-laughers/"><u>2024 Approved Seek Out Humorous Auditory Laughers</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-of-the-web-free-video-editors-for-online-use/"><u>New Best of the Web Free Video Editors for Online Use</u></a></li>
</ul></div>
