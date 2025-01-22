---
title: Rapid Unjamming of Print Workqueue
date: 2025-01-20T18:50:16.440Z
updated: 2025-01-22T00:50:54.925Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Unjamming of Print Workqueue
excerpt: This Article Describes Rapid Unjamming of Print Workqueue
keywords: Rapid Workqueue Solutions,Fast-Tracking Print Processes,Workqueue Management,Efficient Printwork Queue Optimization,Unjamming Printer Workqueue Techniques,Streamlining Print Operations,Printer Workqueue Performance Improvement
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Rapid Unjamming of Print Workqueue

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://discord-videos.techidaily.com/new-the-essential-steps-to-thrive-in-discord-livestreaming-for-2024/"><u>[New] The Essential Steps to Thrive in Discord Livestreaming for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-delving-into-youtubes-digital-video-workshop-for-2024/"><u>[Updated] Delving Into YouTube's Digital Video Workshop for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-how-to-record-audio-from-youtube/"><u>[Updated] How to Record Audio From YouTube</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2-steps-to-set-up-canon-printer-with-pictures/"><u>2 Steps to Set up Canon Printer (With Pictures)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-barriers-reconnecting-brothers-networked-printer/"><u>Breaking Barriers: Reconnecting Brother's Networked Printer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-battery-issues-on-your-acer-device-when-it-wont-charge/"><u>Diagnosing Battery Issues on Your Acer Device – When It Won’t Charge</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/digital-dream-team-best-screen-capture-software-online/"><u>Digital Dream Team Best Screen Capture Software Online</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-zte-blade-a73-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-found-inkjet-not-printing-epson/"><u>Fix Found: Inkjet Not Printing [Epson]</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-stop-apple-music-from-automatically-playing/"><u>How to Stop Apple Music From Automatically Playing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-vivo-s18-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Vivo S18 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/interpreting-codes-for-inkjet-problems/"><u>Interpreting Codes for Inkjet Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-canon-printer-wi-fi-setup/"><u>Mastering Canon Printer Wi-Fi Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reestablish-links-essential-steps-to-solve-printer-woes/"><u>Reestablish Links: Essential Steps to Solve Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-network-disconnectivity-in-hp-printers/"><u>Solving Network Disconnectivity in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-tech-merging-8720-printer-into-pc-system/"><u>Step by Step Tech: Merging 8720 Printer Into PC System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/streamlined-method-to-track-down-your-voice-in-youtube-threads-for-2024/"><u>Streamlined Method to Track Down Your Voice in YouTube Threads for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-50-amazing-cyber-monday-offers-on-elite-cleaning-robots-score-discounts-on-roomba-and-roborock-models-gadgetzoo/"><u>Top 50 Amazing Cyber Monday Offers on Elite Cleaning Robots: Score Discounts on Roomba & Roborock Models | GadgetZoo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-d1360-print-driver-installation-across-windows-systems/"><u>Troubleshooting HP D1360 Print Driver Installation Across Windows Systems</u></a></li>
</ul></div>

