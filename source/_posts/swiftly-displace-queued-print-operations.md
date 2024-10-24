---
title: Swiftly Displace Queued Print Operations
date: 2024-10-16T20:54:18.129Z
updated: 2024-10-24T04:29:47.368Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
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
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-superior-8-filter-trios-for-broadcast-excellence-for-2024/"><u>[New] Superior 8 Filter Trios for Broadcast Excellence for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-revolutionizing-cinematography-with-advanced-3d-luts/"><u>[Updated] Revolutionizing Cinematography with Advanced 3D LUTs</u></a></li>
<li><a href="https://win-dash.techidaily.com/best-multiplatform-open-source-software-for-cd-tearing-on-pcs-macs-and-linux-systems/"><u>Best Multiplatform Open Source Software for CD Tearing on PCs, Macs, and Linux Systems</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/through-strategies-for-youtube-short-problem-solving-for-2024/"><u>Breakthrough Strategies for YouTube Short Problem-Solving for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanner-activation-after-updating-win10/"><u>Enable Scanner Activation After Updating Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-easy-wi-fi-connectivity-for-canon/"><u>Enabling Easy Wi-Fi Connectivity for Canon</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-make-an-informed-deceration-top-five-tips-when-buying-your-next-smartwatch/"><u>How to Make an Informed Deceration: Top Five Tips When Buying Your Next Smartwatch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-resumption-of-prints/"><u>Immediate Resumption of Prints</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-quick-steps-to-change-weather-location-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Quick Steps to Change Weather Location on Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/making-a-lasting-impression-with-profile-clips-for-2024/"><u>Making a Lasting Impression with Profile Clips for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-pcl-xl-errors-with-ease/"><u>Navigating Through PCL XL Errors with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-recovery-from-common-pcl-xl-failures/"><u>Rapid Recovery From Common PCL XL Failures</u></a></li>
<li><a href="https://some-guidance.techidaily.com/retoucher-votre-image-avec-des-apps-visage-libres-tops-choix-payants-et-gratuits/"><u>Retoucher Votre Image Avec Des Apps Visage Libres - Tops Choix Payants Et Gratuits</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/schlusselinformationen-fur-die-anschaffung-des-winx-dvd-video-programms-kauf-faq/"><u>Schlüsselinformationen Für Die Anschaffung Des WinX DVD Video-Programms - Kauf FAQ</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-guide-adding-hp-printer-officejet-pro-to-pc-network/"><u>Setup Guide: Adding HP Printer (Officejet Pro) to PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solidify-printing-integrity-fixing-issues-on-win10/"><u>Solidify Printing Integrity, Fixing Issues on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/transform-printing-experience-hp-officejets-newest-software-update/"><u>Transform Printing Experience: HP Officejet's Newest Software Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-loss-of-printers-internet-connection/"><u>Troubleshooting: Loss of Printer's Internet Connection</u></a></li>
</ul></div>

