---
title: Quick Fix to Printer Job Backlog
date: 2024-08-31T04:41:02.208Z
updated: 2024-09-01T04:41:02.208Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Fix to Printer Job Backlog
excerpt: This Article Describes Quick Fix to Printer Job Backlog
keywords: Printer Job Backlog,Print Queue Management,Faster Printer Processing,Printer Performance Optimization,Print Backlog Solutions,Reduce Print Job Delays,Printer Backlog Reduction Tips
thumbnail: https://thmb.techidaily.com/16a9b35c6bd9fc401c0908fd1a1024fa5ae9f4d4fbf37f1eb35abe3fab424ae1.jpg
---

## Quick Fix to Printer Job Backlog

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/issue-missing-printer-driver-in-win/"><u>[ISSUE] Missing Printer Driver in Win</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-zoom-meetings-on-windows-10/"><u>[New] Navigating Zoom Meetings on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-11/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-ultimate-top-quality-hd-screen-capture-tools/"><u>[Updated] 2024 Approved  Ultimate Top-Quality HD Screen Capture Tools</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-unlocking-respectful-dialogue-a-strategy-guide-to-reporting-misconduct-in-online-communities/"><u>[Updated] 2024 Approved  Unlocking Respectful Dialogue  A Strategy Guide to Reporting Misconduct in Online Communities</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-ultimate-selection-of-8-instagram-schedulers-for-phones/"><u>[Updated] In 2024, The Ultimate Selection of 8 Instagram Schedulers for Phones</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-iphone-photography-fundamentals-the-essential-10-arrangement-rules/"><u>[Updated] IPhone Photography Fundamentals  The Essential 10 Arrangement Rules</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-dive-into-retro-gaming-the-5-highest-rated-android-ps2-emulators/"><u>2024 Approved  Dive Into Retro Gaming  The 5 Highest-Rated Android PS2 Emulators</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-luminary-megascape-ultimate-4k-integrated-hubs/"><u>2024 Approved  Luminary MegaScape  Ultimate 4K Integrated Hubs</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-master-the-art-of-sharing-gaming-moments-xboxfb-livestream/"><u>2024 Approved  Master the Art of Sharing Gaming Moments  Xbox/FB Livestream</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024-update-printers-prints-every-page/"><u>2024 Update: Printers Prints Every Page</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beware-5-common-tricks-using-chatgpt-you-should-avoid/"><u>Beware: 5 Common Tricks Using ChatGPT You Should Avoid</u></a></li>
<li><a href="https://win-able.techidaily.com/chrome-high-cpu-usage-problem-addressed-optimal-fixes-and-solutions/"><u>Chrome High CPU Usage Problem Addressed – Optimal Fixes and Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-printing-malfunction-detected/"><u>Color Printing Malfunction Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connection-guide-integrating-hp-printer-with-pc-network/"><u>Connection Guide: Integrating HP Printer with PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-when-print-devices-go-offline/"><u>Connectivity Woes: When Print Devices Go Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-printer-configuration-errors-in-w11/"><u>Correct Printer Configuration Errors in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrective-measures-in-place-for-hp-printers-blanks/"><u>Corrective Measures in Place for HP Printer's Blanks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-hp-printer-on-windows-107/"><u>Enabling HP Printer on Windows 10/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-updated-epson-l3150-driver-software-for-your-pc-compatible-with-multiple-windows-versions/"><u>Get Updated Epson L3150 Driver Software for Your PC | Compatible with Multiple Windows Versions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructions-installing-hp-officejet-on-pc-interface/"><u>Instructions: Installing HP Officejet on PC Interface</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-canon-wi-fi-connection-process/"><u>Mastering the Canon-Wi-Fi Connection Process</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-htc-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from HTC .</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-error-unforeseen-setup-glitch-detected/"><u>Print Error: Unforeseen Setup Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-print-no-hassle-method/"><u>Reconnect Print: No Hassle Method</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-print-job-failures-on-windows-11/"><u>Rectify Print Job Failures on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-install-errors/"><u>Resolved Printer Install Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-dead-printers-on-windows-11-os/"><u>Revive Dead Printers on Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-fast-track-setting-up-and-enjoying-ifunny-memes-for-2024/"><u>The Fast Track  Setting Up & Enjoying iFunny Memes for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-and-mp620-printer-wheres-the-compatibility/"><u>Win11 & MP620 Printer: Where's the Compatibility?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-out-error-0x97-in-epson-units/"><u>Zeroing Out Error 0X97 in Epson Units</u></a></li>
</ul></div>
