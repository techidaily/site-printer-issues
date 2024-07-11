---
title: Instant Resolution for Caught-In Printer Jobs
date: 2024-07-10T16:57:22.524Z
updated: 2024-07-11T16:57:22.524Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instant Resolution for Caught-In Printer Jobs
excerpt: This Article Describes Instant Resolution for Caught-In Printer Jobs
keywords: Instant Printer Job Resolution,Quick Fix Caught-In Print Jobs,Emergency Solution for Stuck Prints,Rapid Recovery From Printing Jams,Immediate Remedy for Printer Errors,Efficient Repair of Paper Jams,Preventive Measures for Caught-In Prints
thumbnail: https://thmb.techidaily.com/8010c35385b1d4db309ae5aab39ce0f7ad55b6a2892c96756f155f1fe1fe9c5e.jpg
---

## Instant Resolution for Caught-In Printer Jobs

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
<li><a href="https://printer-issues.techidaily.com/guide-to-restoring-communication-with-printer/"><u>Guide to Restoring Communication with Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tailored-updates-mf4770n-for-windows-oses/"><u>Tailored Updates: MF4770n for WIndows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-paper-jams-and-misprints-on-windows-10/"><u>Resolve Paper Jams & Misprints on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-driver-compatibility-with-multiple-windows-oses/"><u>HP Deskjet D1360 Driver Compatibility with Multiple Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-11-printing-glitches/"><u>Troubleshoot Windows 11 Printing Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unstick-print-job-immediately/"><u>Unstick Print Job Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-fix-printer-not-responding-anymore/"><u>Win11 Fix: Printer Not Responding Anymore</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-and-update-hp-officejet-4630-driver-edition/"><u>Secure & Update: HP Officejet 4630 Driver Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enrich-printer-capabilities-dell-software-update-for-windows-7/"><u>Enrich Printer Capabilities: Dell Software Update for Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-hp-printer-not-responding/"><u>How to Fix HP Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-pages-galore-affected-by-epson-printer/"><u>White Pages Galore: Affected by Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unrecognized-print-activity-sheds-light/"><u>Unrecognized Print Activity Sheds Light</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-are-missing/"><u>Printer OS Error: Drivers Are MISSING</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplifying-pcl-xl-error-correction/"><u>Simplifying PCL XL Error Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-epson-printer-paper-jam/"><u>Resolved: Epson Printer Paper Jam</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-non-responsive-printer-issues-on-nt-os/"><u>Solving Non-Responsive Printer Issues on NT OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-error-code-0x97/"><u>[Solved] Epson Error Code 0X97</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-samsung-galaxy-s23-fe-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Vivo Y36i? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-vivo-g2-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Vivo G2.</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-uniting-visuals-the-art-of-video-sequence-composition/"><u>[New] In 2024, Uniting Visuals  The Art of Video Sequence Composition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harnessing-digital-artistry-top-6-nft-makers-reviewed/"><u>2024 Approved  Harnessing Digital Artistry - Top 6 NFT Makers Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/vlog-glow-achieving-professional-video-setup/"><u>Vlog Glow  Achieving Professional Video Setup</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-crafting-perfect-youtube-introend-videos-at-no-cost/"><u>[Updated] In 2024, Crafting Perfect YouTube Intro/End Videos at No Cost</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-deep-dive-into-effective-animoji-utilization-on-iphone-x/"><u>[Updated] A Deep Dive Into Effective Animoji Utilization on iPhone X</u></a></li>
<li><a href="https://driver-install.techidaily.com/keeping-hyperx-headsets-up-to-date-with-new-driver-implementations/"><u>Keeping HyperX Headsets Up To Date with New Driver Implementations</u></a></li>
<li><a href="https://fox-helps.techidaily.com/premium-video-quality-top-cameras-of-the-year-2024/"><u>Premium Video Quality  Top Cameras of the Year 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapchat-recordings-techniques-for-your-phone/"><u>[Updated] 2024 Approved  Snapchat Recordings  Techniques for Your Phone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-top-10plus-platforms-for-remote-church-experience/"><u>Discover Top 10+ Platforms for Remote Church Experience</u></a></li>
</ul></div>
