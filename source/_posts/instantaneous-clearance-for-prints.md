---
title: Instantaneous Clearance for Prints
date: 2024-09-30T11:06:16.310Z
updated: 2024-10-01T06:48:30.060Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantaneous Clearance for Prints
excerpt: This Article Describes Instantaneous Clearance for Prints
keywords: Instant Print Clearance,Rapid Print Approval Process,Immediate Print Authorization,Quick Clearance Prints,Express Print Release,Same-Day Print Clearance,Fast-Track Printing Approval
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Instantaneous Clearance for Prints

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-prime-selection-of-simple-effective-gamers-edit-tools-for-2024/"><u>[New] Prime Selection of Simple, Effective Gamers' Edit Tools for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-pixma-mp620-drivers-missing-windows-10/"><u>[Update Required] Pixma MP620 Drivers Missing Windows 10</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-expand-your-online-realm-harnessing-youtube-insights-powerfully/"><u>[Updated] 2024 Approved Expand Your Online Realm Harnessing YouTube Insights Powerfully</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-insta-perfection-the-leading-ten-grid-creation-software-listed/"><u>2024 Approved Insta-Perfection The Leading Ten Grid Creation Software Listed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-secure-your-animated-gifs-with-these-winning-recording-software-on-pc/"><u>2024 Approved Secure Your Animated GIFs with These Winning Recording Software on PC</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-softening-mix-tracks-incrementally-in-fl/"><u>2024 Approved Softening Mix Tracks Incrementally in FL</u></a></li>
<li><a href="https://facebook.techidaily.com/a-step-by-step-approach-hd-media-mastery-in-fb-mobile/"><u>A Step-by-Step Approach: HD Media Mastery in Fb Mobile</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-printer-output-immediately/"><u>Accelerate Printer Output Immediately</u></a></li>
<li><a href="https://some-techniques.techidaily.com/boost-your-traffic-with-our-cutting-edge-cookiebot-technology/"><u>Boost Your Traffic with Our Cutting-Edge Cookiebot Technology</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://buynow-info.techidaily.com/budget-friendly-wifi-expansion-evaluating-the-performance-of-the-tp-link-re200-ac750/"><u>Budget-Friendly WiFi Expansion: Evaluating the Performance of the TP-Link RE200 AC750</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-no-more-windows-7/"><u>Epson Printer Offline No More, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printer-driver-issues-on-windows-10/"><u>Fix Printer Driver Issues on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-printer-service-spooler-issues/"><u>Fixing Non-Operational Printer Service (Spooler) Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-asus-rog-phone-8-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Asus ROG Phone 8 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-prevent-print-service-interruptions-on-w7w10w11/"><u>How to Prevent Print Service Interruptions on W7/W10/W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-pcl-xl-complications-swiftly/"><u>Navigating PCL XL Complications Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-like-a-pro-3-upgrades-to-link-your-printer-and-laptop-seamlessly/"><u>Print Like a Pro: 3 Upgrades to Link Your Printer & Laptop Seamlessly</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protecting-your-privacy-can-personalized-ai-models-like-chatgpt-pose-risks/"><u>Protecting Your Privacy: Can Personalized AI Models Like ChatGPT Pose Risks?</u></a></li>
</ul></div>

