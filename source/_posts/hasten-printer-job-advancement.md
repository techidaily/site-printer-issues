---
title: Hasten Printer Job Advancement
date: 2024-12-02T18:31:28.652Z
updated: 2024-12-09T16:00:15.304Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Hasten Printer Job Advancement
excerpt: This Article Describes Hasten Printer Job Advancement
keywords: Accelerate Inkjet Printing Processes,Advance Printer Technology Speed,Increase Print Job Efficiency,Optimize Printer Operation Speed,Fast-Track Print Technology Development,Enhance Printer Speed & Performance,Improve Print Job Turnaround Time
thumbnail: https://thmb.techidaily.com/dbfa6019d8b3f211a2d4346989a8be20fa1fb2520363f53adb487ff9f78fd127.jpg
---

## Hasten Printer Job Advancement

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  

![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-maximum-videos-on-a-64gb-drive/"><u>[New] 2024 Approved Maximum Videos on a 64GB Drive</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-record-twitch-live-stream/"><u>[Updated] How to Record Twitch Live Stream</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-keeping-your-views-private-top-5-insta-tools/"><u>[Updated] In 2024, Keeping Your Views Private - Top 5 Insta Tools</u></a></li>
<li><a href="https://some-tips.techidaily.com/webmmkv-movavi/"><u>無料WebM到MKV同步變更 - 使用Movavi的簡易指南</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573835599-canon-pixma-mp620-driver-missing-please-help/"><u>Canon Pixma MP620: Driver Missing, Please Help!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-paper-jams-without-hassle/"><u>Clearing Paper Jams Without Hassle</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fixing-fish-eye-effects-in-hd-and-4k-videos-a-comprehensive-guide/"><u>Fixing Fish Eye Effects in HD and 4K Videos: A Comprehensive Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/ideal-termination-immersive-reality/"><u>Ideal Termination Immersive Reality</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-mac-techniques-for-instagram-short-form-videos/"><u>In 2024, Mac Techniques for Instagram Short-Form Videos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-of-printer-finalized/"><u>Installation of Printer Finalized</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212263441-lost-your-steam-game-files-learn-how-to-get-them-back-and-restore-access/"><u>Lost Your Steam Game Files? Learn How to Get Them Back and Restore Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-obstacles-in-adding-new-printer-to-network/"><u>No Obstacles in Adding New Printer to Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-queue-unavailable-on-local-pc/"><u>Print Queue Unavailable on Local PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-print-sessions-fixing-driver-issues-on-win10/"><u>Secure Print Sessions: Fixing Driver Issues on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-displace-queued-print-operations/"><u>Swiftly Displace Queued Print Operations</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-family-friendly-christian-films-for-downloading-and-enjoying-with-children/"><u>Top Family-Friendly Christian Films for Downloading & Enjoying With Children</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722980769121-troubleshooting-continuous-lag-in-warframe-solutions-found/"><u>Troubleshooting Continuous Lag in Warframe - Solutions Found!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-mf4770n-drivers-in-win1087-environment/"><u>Update MF4770n Drivers in Win10/8/7 Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-from-sleep-troubleshooting-usb-printer-not-working/"><u>Wake From Sleep: Troubleshooting USB Printer Not Working</u></a></li>
</ul></div>

