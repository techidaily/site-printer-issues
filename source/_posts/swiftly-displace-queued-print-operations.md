---
title: Swiftly Displace Queued Print Operations
date: 2024-06-28T07:21:55.497Z
updated: 2024-06-29T07:21:55.497Z
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
<li><a href="https://printer-issues.techidaily.com/printer-woes-in-windows-11-help-needed/"><u>Printer Woes in Windows 11 - Help Needed!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-struggles-cannot-find-mp620-printer-drivers/"><u>Windows 10 Struggles: Cannot Find MP620 Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-107-solved/"><u>HP Printer Offline Status on Windows 10/7 [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-printer-no-show-on-windows-me-edition/"><u>Addressing Printer No-Show on Windows ME Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-address-sibling-printer-unresponsiveness/"><u>Strategies to Address Sibling Printer Unresponsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7810-networking-guide-for-inkjet-hp-issues/"><u>Win7/8/10 Networking Guide for Inkjet HP Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-problem-discovered/"><u>Unexpected Print Problem Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-hp-xp-paper-issue/"><u>Troubleshooting Offline HP XP Paper Issue</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovating-photography-the-art-of-crafting-effective-gopro-time-lapse-for-2024/"><u>Innovating Photography  The Art of Crafting Effective GoPro Time-Lapse for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/is-it-possible-to-use-miracast-with-apple-iphone-xs-drfone-by-drfone-ios/"><u>Is it Possible to Use Miracast with Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-nokia-c300-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Nokia C300 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-vibrant-soundtrack-selection-for-anniversary-party-recording/"><u>Updated In 2024, Vibrant Soundtrack Selection for Anniversary Party Recording</u></a></li>
<li><a href="https://fox-helps.techidaily.com/which-pro-stream-software-reigns-supreme-vmix-vs-wirecast/"><u>Which Pro-Stream Software Reigns Supreme? VMix Vs. Wirecast</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-essence-of-video-editing-filmoras-ten-wonders/"><u>2024 Approved  The Essence of Video Editing  Filmora's Ten Wonders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sound-excellence-on-a-shoestring-superior-asmr-mics-affordably/"><u>In 2024, Sound Excellence on a Shoestring - Superior ASMR Mics Affordably</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sophisticated-screen-capture-3-top-tier-techniques-for-zoom-conversion/"><u>In 2024, Sophisticated Screen Capture  3 Top-Tier Techniques for Zoom Conversion</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-vivo-s18e-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Vivo S18e | Dr.fone</u></a></li>
</ul></div>