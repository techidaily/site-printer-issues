---
title: Quick Restoration of Active Print Queue
date: 2024-07-10T16:46:41.809Z
updated: 2024-07-11T16:46:41.809Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Restoration of Active Print Queue
excerpt: This Article Describes Quick Restoration of Active Print Queue
keywords: Print Management Software,Restore Print Queue Faster,Print Job Optimization,Efficient Printing Processes,Automated Printer Queue Management,Print Workflow Automation,Reduce Print Queue Timeouts
thumbnail: https://thmb.techidaily.com/8b607e0e604394629b363ae69329923c5b752c9a4c4af741aef58011df0d7554.jpg
---

## Quick Restoration of Active Print Queue

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
<li><a href="https://printer-issues.techidaily.com/blank-page-problem-persists-on-new-epson-printer-model/"><u>Blank Page Problem Persists on New Epson Printer Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-persistent-failures-of-the-print-spooler-service/"><u>Eliminate Persistent Failures of the Print Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-setting-up-hp-laserjet-compact-connectivity/"><u>Guide to Setting Up HP LaserJet Compact Connectivity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-print-for-office-hp-devices/"><u>Enabling Duplex Print for Office HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-seamless-transition-update-mf4770n-on-w11win8w7/"><u>Achieve Seamless Transition: Update MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-hp-printer-issue-code-oxc4eb827f/"><u>Rectifying HP Printer Issue: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-link-your-laptop-and-hp-printer-with-these-fixes/"><u>Effortlessly Link Your Laptop and HP Printer with These Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-solve-brother-printer-offline-problem/"><u>How to Solve Brother Printer Offline Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-hp-printer-oxc4eb827f-fatality-problem/"><u>Solving HP Printer OXC4EB827F Fatality Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-a-siblings-printer-out-of-network-hibernation/"><u>Bringing a Sibling's Printer Out of Network Hibernation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-shared-network-device-conflict/"><u>Solved: Shared Network Device Conflict</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-paper-jamming-concern/"><u>Mended Paper Jamming Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-releases-dell-v305-driver-and-utility-supports-win7/"><u>New Releases: Dell V305 Driver & Utility Supports Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-color-rejection/"><u>Printer's Color Rejection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionize-your-printing-3-futuristic-solutions-to-connect-hp-and-laptop/"><u>Revolutionize Your Printing: 3 Futuristic Solutions to Connect HP & Laptop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/directions-assembling-hp-print-with-your-pc/"><u>Directions: Assembling HP Print with Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-incorporating-hp-printer-in-pc-network/"><u>Step-by-Step: Incorporating HP Printer in PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/issue-cant-print-spooler-disabled/"><u>[ISSUE] Can't Print - Spooler Disabled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-clear-print-head-conflict-on-win-1011/"><u>How To Clear Print Head Conflict on Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-mf4770n-compatibility-in-win1187/"><u>Revitalize Your MF4770n Compatibility in Win11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-missing-pages-issue-with-new-printer-update/"><u>End Missing Pages Issue with New Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-blank-page-problem-solved/"><u>HP Printer Blank Page Problem Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reprogram-inkjet-and-laser-drivers-for-win10-pcs/"><u>Reprogram Inkjet & Laser Drivers for Win10 PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-print-queue-problems-on-windows-11/"><u>Solve Print Queue Problems on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-instant-ink-into-your-networked-devices/"><u>Integrating HP Instant Ink Into Your Networked Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-canon-wi-fi-connection-process/"><u>Mastering the Canon-Wi-Fi Connection Process</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-printer-alert/"><u>Fixing: Offline PRINTER Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-offline-hp-printer-woes/"><u>Overcoming Offline HP Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-inaccessible-printer-connection/"><u>Mended Inaccessible Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-firmware-for-mf4770n-on-windows-systems/"><u>Latest Firmware for MF4770n on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-toner-trouble/"><u>Navigating Through Toner Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-no-0x97-resolved/"><u>Epson Fault No: 0X97 - Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restarting-non-functional-usb-devices-post-sleep-windows-7/"><u>Restarting Non-Functional USB Devices Post Sleep, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unknown-computer-known-printer-case-closed/"><u>Unknown Computer, Known Printer - Case Closed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-intermittent-print-job-failures-windows/"><u>Steps to Stop Intermittent Print Job Failures (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-pcl-xl-mistakes-with-ease/"><u>Tackling PCL XL Mistakes with Ease</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-leading-ways-streaming-and-recording-real-time-sport-events/"><u>[New] Leading Ways  Streaming and Recording Real-Time Sport Events</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-infinix-hot-40-pro-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Infinix Hot 40 Pro?</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-luts-unveiled-transforming-the-lands-market/"><u>2024 Approved  LUTs Unveiled  Transforming the Lands Market</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-pioneering-audio-visual-integration-generating-waveforms-and-introducing-dynamic-animations-with-premiere-pro/"><u>Updated 2024 Approved Pioneering Audio-Visual Integration Generating Waveforms & Introducing Dynamic Animations with Premiere Pro</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-how-to-edit-mp4-videosfiles-in-macwindows-2023-tutorial/"><u>New 2024 Approved How to Edit MP4 Videos/Files in Mac/Windows 2023 Tutorial</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-cartoon-conversion-blueprint-tips-and-tricks-for-2024/"><u>The Cartoon Conversion Blueprint Tips and Tricks for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-seamless-way-to-capture-your-favorite-pc-games-6-methods/"><u>[Updated] The Seamless Way to Capture Your Favorite PC Games (6 Methods)</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>The Most Useful Tips for Pokemon Go Ultra League On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-google-pixel-8-pro-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Google Pixel 8 Pro FRP</u></a></li>
<li><a href="https://win11.techidaily.com/struggling-with-game-installs-xbox-app-solutions/"><u>Struggling with Game Installs: Xbox App Solutions</u></a></li>
</ul></div>
