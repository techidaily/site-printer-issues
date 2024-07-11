---
title: Quick Streamline of Hindered Printer Jobs
date: 2024-07-10T16:55:50.713Z
updated: 2024-07-11T16:55:50.713Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Streamline of Hindered Printer Jobs
excerpt: This Article Describes Quick Streamline of Hindered Printer Jobs
keywords: Quick Printer Job Optimization,Streamlining Print Jobs,Enhancing Print Workflow Efficiency,Hindered Printing Solutions,Speed up Stalled Print Tasks,Improve Printing Process Performance,Faster Handling of Jammed Prints
thumbnail: https://thmb.techidaily.com/baabb0210a0e9d1dfef8f1a18fa201bad1a8f950b33fad191c1a3f8c1897f172.jpg
---

## Quick Streamline of Hindered Printer Jobs

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
<li><a href="https://printer-issues.techidaily.com/steering-clear-obstacles-onboard-brother-printer-again/"><u>Steering Clear Obstacles: Onboard Brother Printer Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unforeseen-print-malfunction-noted/"><u>Unforeseen Print Malfunction Noted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-connecting-hp-printer-to-windows-pc/"><u>Tutorial: Connecting HP Printer to Windows PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-get-my-canon-printer-on-board/"><u>Can't Get My Canon Printer on Board</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-inkjet-printer-unresponsive/"><u>Post Upgrade, Inkjet Printer Unresponsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-unresponsive-on-pc/"><u>Print Spooler Service Unresponsive on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-print-speed-and-quality-download-hp-officejet-firmware/"><u>Boost Print Speed & Quality - Download HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-printer-operation-post-windows-10-update/"><u>Unblocking Printer Operation Post-Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-mf4770n-functions-on-w11w8w7-os/"><u>Streamlining MF4770n Functions on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantaneous-fix-guide-unwinding-pcl-xl-errors/"><u>Instantaneous Fix Guide: Unwinding PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugged-reset-to-bring-canon-printer-back-online/"><u>Unplugged? Reset to Bring Canon Printer Back Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-guide-to-smoothly-linking-canon-printers/"><u>A Guide to Smoothly Linking Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paperless-challenges-ended-with-windows-upgrade/"><u>Paperless Challenges Ended with Window's Upgrade</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-for-resolving-brother-printer-online-issues/"><u>Guidelines for Resolving Brother Printer Online Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-network-printer-not-showing-up-in-windows-1110/"><u>[Fixed] Network Printer Not Showing up in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driving-performance-mf4770n-on-windows-oss/"><u>Driving Performance: MF4770n on Windows OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-brother-printers-print-a-win1011-guide-to-fixing-issues/"><u>Revive Your Brother Printer's Print: A Win10/11 Guide to Fixing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-all-in-one-printers-connectivity-armored-up/"><u>HP All-in-One Printer's Connectivity Armored Up</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-connectivity-restored/"><u>[PRINT] Connectivity Restored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-disruptions-on-win7win10/"><u>Avoiding Constant Printer Service Disruptions on Win7/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-solving-epson-printing-anomalies/"><u>Understanding and Solving Epson Printing Anomalies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-mf4770n-integration-on-windows-platforms/"><u>Elevate MF4770n Integration on Windows Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-canon-device-that-wont-react/"><u>Reviving a Canon Device That Won't React</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-interactions-mf4770n-update-in-win11win87-os/"><u>Enhance Device Interactions: MF4770n Update in Win11/Win8/7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimized-installation-process-hp-officejet-pro-8600-windows-driver/"><u>Optimized Installation Process: HP OfficeJet Pro 8600 Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-hp-printer-drivers-on-windows-1011/"><u>Finding HP Printer Drivers on Windows 10/11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-nokia-c12-plus-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Nokia C12 Plus</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-next-gen-options-to-record-high-quality-gaming-footage/"><u>[New] 2024 Approved  Next Gen Options to Record High-Quality Gaming Footage</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-6-nft-makers-for-artists-to-unleash-imagination/"><u>Top 6 NFT Makers for Artists to Unleash Imagination</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-realme-12-pro-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Realme 12 Pro 5G Devices | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-mastering-video-conferencing-combining-the-power-of-zoom-and-skype-for-2024/"><u>[Updated] Mastering Video Conferencing  Combining the Power of ZOOM & SKYPE for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-poco-x5-pro-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-zooming-into-perfection-a-compreenasional-tutorial-on-audio-recording/"><u>2024 Approved  Zooming Into Perfection  A Compreenasional Tutorial on Audio Recording</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-xbox-gameplay-perfect-screen-recording-guide/"><u>2024 Approved  Xbox Gameplay  Perfect Screen Recording Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-f5-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Poco F5 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-collage-artistry-with-precision/"><u>2024 Approved  Mastering Collage Artistry with Precision</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-speed-removing-ssgnatures-immediately-for-2024/"><u>Mastering Speed  Removing Ssgnatures Immediately for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/elevate-gameplay-memories-overwatchs-recording-hacks/"><u>Elevate Gameplay Memories - Overwatch's Recording Hacks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unraveling-popularity-myths-the-real-truth-about-instagram-reels-for-2024/"><u>Unraveling Popularity Myths  The Real Truth About Instagram Reels for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-realme-c67-4g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Realme C67 4G Fingerprint Lock</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-best-voice-changers-for-whatsapp-free-included-for-2024/"><u>Updated Best Voice Changers for WhatsApp Free Included for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-dissecting-screen-capture-tools-an-in-depth-look-at-apeaksoft/"><u>[Updated] 2024 Approved  Dissecting Screen Capture Tools  An In-Depth Look at Apeaksoft</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-12-youtube-game-openers-a-comparative-guide-no-expense/"><u>[New] 2024 Approved  Best 12 YouTube Game Openers  A Comparative Guide (No Expense)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-itel-p40plus-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Itel P40+ PC | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-top-10-mouse-recorders/"><u>[New] 2024 Approved  Top 10 Mouse Recorders</u></a></li>
</ul></div>
