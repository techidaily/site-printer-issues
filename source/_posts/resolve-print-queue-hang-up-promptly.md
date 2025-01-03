---
title: Resolve Print Queue Hang-Up Promptly
date: 2024-12-30T00:10:29.555Z
updated: 2025-01-02T20:30:11.495Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve Print Queue Hang-Up Promptly
excerpt: This Article Describes Resolve Print Queue Hang-Up Promptly
keywords: Print Queue Resolution,Immediate Print Queue Fixes,Print Spooler Troubleshooting,Printer Queue Error Resolution,Print System Stability Improvement,Fast Printer Queue Clearance,Prevent Print Queue Crashes
thumbnail: https://thmb.techidaily.com/9ce1efb4d78691d1fda3d25f6e0de4e7036d8fbbf749d1e5f5caf96b519e32e1.png
---

## Resolve Print Queue Hang-Up Promptly

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://printer-issues.techidaily.com/driver-dilemma-windows-11-ignoring-pixma-mp620/"><u>[Driver Dilemma] Windows 11 Ignoring Pixma MP620</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-top-4-sites-for-free-skype-tones/"><u>[Updated] Top 4 Sites for Free Skype Tones</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-all-apple-watches-compatible-with-watchos-11-and-those-excluded-from-update/"><u>Comprehensive Guide: All Apple Watches Compatible with WatchOS 11 and Those Excluded From Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-excessive-network-usage-understanding-and-fixing-svchostexe-netsvcs/"><u>Dealing with Excessive Network Usage – Understanding & Fixing svchost.exe (NETSVCS)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/download-and-convert-dailymotion-videos-for-free-online-for-2024/"><u>Download and Convert Dailymotion Videos for Free Online for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574135496-enhance-printer-velocity-now/"><u>Enhance Printer Velocity Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-inkjet-non-operational-state/"><u>Fixed Inkjet Non-Operational State</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hassle-free-connections-3-innovative-ways-to-link-laptop-plus-hp/"><u>Hassle-Free Connections: 3 Innovative Ways to Link Laptop + HP</u></a></li>
<li><a href="https://fox-helps.techidaily.com/highlighting-heroics-at-the-x-olympics-2022/"><u>Highlighting Heroics at the X-Olympics 2022</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-take-photos-while-recording-videos-on-iphone/"><u>How to Take Photos While Recording Videos on iPhone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-wave-goodbye-to-costs-with-our-50-free-banners-offer/"><u>In 2024, Wave Goodbye to Costs with Our 50 Free Banners Offer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/intuitive-firmware-update-process-for-hp-printers-especially-4630/"><u>Intuitive Firmware Update Process for HP Printers, Especially 4630</u></a></li>
<li><a href="https://discover-help.techidaily.com/managing-windows-firewall-settings-through-control-panel-essential-tips-by-yl-software-experts/"><u>Managing Windows Firewall Settings Through Control Panel: Essential Tips by YL Software Experts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-guide-for-non-printing-machines/"><u>Repair Guide for Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-canon-device-that-wont-react/"><u>Reviving a Canon Device That Won't React</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smoothly-reactivated-scanner-on-windows-11/"><u>Smoothly Reactivated Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-added-new-printer/"><u>Successfully Added New Printer</u></a></li>
<li><a href="https://discover-community.techidaily.com/top-12-applicazioni-piu-efficienti-per-condividere-lo-schermo-movavi/"><u>Top 12 Applicazioni Più Efficienti Per Condividere Lo Schermo - Movavi</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722985730828-top-tips-for-preventing-elex-ii-game-crashes-on-pc-solved/"><u>Top Tips for Preventing Elex II Game Crashes on PC – Solved!</u></a></li>
</ul></div>

