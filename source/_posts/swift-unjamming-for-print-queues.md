---
title: Swift Unjamming for Print Queues
date: 2024-07-10T17:20:57.247Z
updated: 2024-07-11T17:20:57.247Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swift Unjamming for Print Queues
excerpt: This Article Describes Swift Unjamming for Print Queues
keywords: PrintQueue Optimization,Faster Print Processes,Print Queue Management Tools,Unblock Printers Quickly,Reduce Print Job Delays,Efficient Printer Queue Solutions,Print System Performance Enhancement
thumbnail: https://thmb.techidaily.com/d9697a004ae2bbc53020d06bba853be86eb98852ff5592973ceaa096b1863e66.jpg
---

## Swift Unjamming for Print Queues

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
<li><a href="https://printer-issues.techidaily.com/fixing-siblings-printer-remains-unreachable/"><u>Fixing: Sibling's Printer Remains Unreachable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-the-root-cause-of-frequent-printer-service-halt-win/"><u>Finding the Root Cause of Frequent Printer Service Halt (Win)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-hibernate-usb-print-issues-on-windows-7-devices/"><u>Post-Hibernate USB Print Issues on Windows 7 Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-output-missing-color-details/"><u>Print Output: Missing Color Details</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-outputs-ceased-on-epson-model/"><u>Halted Outputs Ceased on Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-non-responsive-printer-service-windows/"><u>Immediate Fixes for Non-Responsive Printer Service (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printing-revolution-install-new-inkjet-drivers-and-updates/"><u>HP Printing Revolution: Install New Inkjet Drivers and Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-unblocked-scan-functionality/"><u>Windows 11: Unblocked Scan Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-disconnected-print-service/"><u>Fixing Disconnected Print Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-printer-problem-resolved-and-happy-again/"><u>Post-Update Printer Problem: Resolved and Happy Again!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-steps-to-unlock-printer-output-easy-fixes-for-canon-on-windows-11/"><u>Simple Steps to Unlock Printer Output: Easy Fixes for Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-spits-out-unprinted-sheets/"><u>Resolved: Printer Spits Out Unprinted Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-unable-to-locate-hp-driver-on-winxo/"><u>[Driver Difficulty] - Unable to Locate HP Driver on WinXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-no-longer-exists/"><u>Error B200 No Longer Exists</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-locate-missing-print-server-device/"><u>How to Locate Missing Print Server Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-mf4770n-for-optimal-performance-on-win11-8-7-systems/"><u>Integrate MF4770n for Optimal Performance on Win11, 8, 7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/discover-hidden-printer-devices-in-windows-710/"><u>Discover Hidden Printer Devices in WIndows 7/10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-7-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status From Your iPhone 7</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-how-to-turn-off-suggested-posts-on-instagram-in-2024/"><u>[New] How to Turn Off Suggested Posts on Instagram, In 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discovering-best-steadicams-for-enhanced-dslr-shooting-experience/"><u>Discovering Best Steadicams for Enhanced DSLR Shooting Experience</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-how-to-free-rotate-and-merge-videos-on-android/"><u>[Updated] In 2024, How to Free Rotate and Merge Videos on Android</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-revolutionize-your-streaming-game-with-these-5-pro-tips/"><u>[New] In 2024, Revolutionize Your Streaming Game with These 5 Pro Tips</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-securely-download-your-youtube-playlist-at-any-time/"><u>In 2024, Securely Download Your YouTube Playlist at Any Time</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-4-detailed-steps-to-flip-a-clip-in-final-cut-pro/"><u>New 2024 Approved 4 Detailed Steps to Flip a Clip in Final Cut Pro</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expertly-lit-the-17-must-haves-for-youtubers-for-2024/"><u>[Updated] Expertly Lit  The 17 Must-Haves for Youtubers for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-stop-ipadiphone-from-freezing-during-fb-playback/"><u>[Updated] In 2024, Stop iPad/iPhone From Freezing During FB Playback</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/comprehensive-apowersoft-recording-workshop-with-4-creative-replacements/"><u>Comprehensive Apowersoft Recording Workshop with 4 Creative Replacements</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comparing-gopros-max-and-hero-11-for-the-best-video-quality-for-2024/"><u>Comparing GoPro's Max and Hero 11 for the Best Video Quality for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-lens-wisdom-advanced-insights-into-capturing-and-editing-art/"><u>In 2024, Lens Wisdom  Advanced Insights Into Capturing & Editing Art</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unraveling-the-pioneers-behind-famed-discord-expressions-for-2024/"><u>[Updated] Unraveling the Pioneers Behind Famed Discord Expressions for 2024</u></a></li>
</ul></div>
