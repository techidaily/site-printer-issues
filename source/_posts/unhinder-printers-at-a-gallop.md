---
title: Unhinder Printers at a Gallop
date: 2024-12-08T18:59:49.355Z
updated: 2024-12-10T03:17:54.004Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  

![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  

![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
2. In the Command Prompt window, enter the following commands separately:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-knowledge.techidaily.com/new-free-mindset-tunes-no-copyrights/"><u>[New] Free Mindset Tunes - No Copyrights</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-mastering-remote-conferences-with-5-elite-recorders/"><u>[Updated] In 2024, Mastering Remote Conferences with 5 Elite Recorders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-getting-started-with-digital-image-detailing/"><u>2024 Approved Getting Started with Digital Image Detailing</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/1726026660530-2/"><u>初心者向け動画同時再生テクニック: 2つの画面で一緒に見る方法</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/easy-steps-to-customize-handbrake-configuration-for-apple-ipad-compatible-video-and-dvd-content/"><u>Easy Steps to Customize Handbrake Configuration for Apple iPad-Compatible Video and DVD Content</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-eradicated-printer-for-epson-works/"><u>Error Eradicated: Printer for Epson Works</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/al-banishment-of-youtubes-quick-clips/"><u>Eternal Banishment of YouTube's Quick Clips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/improve-print-quality-fixing-win10-drivers/"><u>Improve Print Quality: Fixing WIN10 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-software-for-hp-officejet-4630-installation/"><u>Latest Software for HP Officejet 4630 Installation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/performance-showdown-how-kingstons-c38-ddr5-7200-camm2-stacks-up-against-conventional-dimm-memory-modules-a-benchmark-study/"><u>Performance Showdown: How Kingston's C38 DDR5-7200 CAMM2 Stacks Up Against Conventional DIMM Memory Modules - A Benchmark Study</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-scanner-link-to-pc-post-update-in-windows-10/"><u>Regaining Scanner Link to PC Post-Update in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversing-printer-freezes/"><u>Reversing Printer Freezes</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solving-windows-11-bsod-caused-by-netwtw04sys-steps-and-tips/"><u>Solving Windows 11 BSOD Caused by Netwtw04.sys: Steps and Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-unresolved-printer-queue-issue/"><u>Speed Up Unresolved Printer Queue Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-repair-for-xerox-error-alert-0x1/"><u>Swift Repair for Xerox Error Alert 0X1</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-xiaomi-redmi-13c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt2000-reactivate-sluggish-printer-response/"><u>WinNT/2000: Reactivate Sluggish Printer Response</u></a></li>
</ul></div>

