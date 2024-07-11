---
title: Swiftly Solve Stuck Printer Job Queue
date: 2024-07-10T17:02:03.736Z
updated: 2024-07-11T17:02:03.736Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swiftly Solve Stuck Printer Job Queue
excerpt: This Article Describes Swiftly Solve Stuck Printer Job Queue
keywords: Printer Job Error,Stuck Printer Job Queue Fix,Print Spooler Troubleshooting,Printer Queue Management,Cease Print Job Errors,Printer Spooler Service Restart,Resolve Printer Queue Delays
thumbnail: https://thmb.techidaily.com/1e11de4cf4f80ef092048741d4366db23f2bbee1459c9f567932a80d4f33ce93.jpg
---

## Swiftly Solve Stuck Printer Job Queue

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
<li><a href="https://printer-issues.techidaily.com/windows-7-usb-printer-not-printing-after-sleep/"><u>Windows 7: USB Printer Not Printing After Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-wont-print-all-pages-2024-fix/"><u>Printers Won't Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-operability-win11w8w7-via-mf4770n-update/"><u>Boosting Operability: Win11/W8/W7 via MF4770n Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/complete-pages-printed-by-printers-now/"><u>Complete Pages Printed by Printers Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simple-steps-for-attaching-hp-wireless-door-mounted-printers/"><u>Simple Steps for Attaching HP Wireless Door Mounted Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-device-functions-with-mf4770n-on-w11win8w7/"><u>Streamline Device Functions with MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-canon-print-failure-on-windows-10-effectively/"><u>Solve Canon Print Failure on Windows 10 Effectively</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-printer-printing-blank-pages/"><u>[SOLVED] Epson Printer Printing Blank Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-paper-jam-hp-print-fix-on-os-x/"><u>Overcoming Paper Jam: HP Print Fix on OS X</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restore-scanner-link-to-computer-in-windows-10/"><u>Restore Scanner Link to Computer in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-snag-your-printer-is-confused/"><u>Setup Snag: Your Printer Is Confused</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1187/"><u>Canon MF4770n Driver Update in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-and-configure-hp-wireless-printer/"><u>How to Connect & Configure HP Wireless Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-laser-print-nozzle-blockage/"><u>Quick Fix: Laser Print Nozzle Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-ultimate-guide-to-installing-and-configuring-hp-printers/"><u>The Ultimate Guide to Installing and Configuring HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-find-hp-printer-drivers-on-win1110/"><u>Cannot Find HP Printer Drivers on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-seamless-transition-update-mf4770n-on-w11win8w7/"><u>Achieve Seamless Transition: Update MF4770n on W11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-online-on-windows-7-after-troubleshooting/"><u>Printer Online on Windows 7 After Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-error-now-corrected/"><u>B200 Error: Now Corrected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/not-all-colors-printing-as-expected/"><u>Not All Colors Printing as Expected</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unleash-your-creativity-best-free-video-fx-apps-for-ios-and-android-for-2024/"><u>New Unleash Your Creativity Best Free Video FX Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-embarking-on-style-and-niche-discovery-journey-for-2024/"><u>[New] Embarking on Style & Niche Discovery Journey for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-unbrand-your-videos-removing-filmora-watermark-made-easy/"><u>New In 2024, Unbrand Your Videos Removing Filmora Watermark Made Easy</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-zoom-and-google-meet-visual-clarity-your-step-by-step-guide-to-cleaner-participation/"><u>[New] 2024 Approved  Zoom & Google Meet Visual Clarity  Your Step-by-Step Guide to Cleaner Participation</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-best-discord-font-generators-onlineiphoneandroid/"><u>[Updated] 2024 Approved  Best Discord Font Generators [Online/iPhone/Android]</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/cross-platform-movie-recording-pc-mac-and-mobile/"><u>Cross-Platform Movie Recording  PC, Mac & Mobile</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-honor-90-lite-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Honor 90 Lite to Roku | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/nlocking-your-potential-multiplatform-studio-use-for-profit/"><u>[New] Unlocking Your Potential  Multiplatform Studio Use for Profit</u></a></li>
<li><a href="https://fox-access.techidaily.com/unveiling-the-process-of-sharing-srt-text-in-social-digital-spaces/"><u>Unveiling the Process of Sharing SRT Text in Social Digital Spaces</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-6s-plus-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 6s Plus Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/macs-ultimate-visual-recorder-for-2024/"><u>Mac's Ultimate Visual Recorder for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-prime-voice-changers-essentials-for-video-makers/"><u>[Updated] Prime Voice Changers  Essentials for Video Makers</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-make-a-bokeh-effect/"><u>How to Make a Bokeh Effect</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-streamlining-instagram-story-captioning-techniques/"><u>[Updated] In 2024, Streamlining Instagram Story Captioning Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-complete-guide-to-motion-without-touch-sensors/"><u>The Complete Guide to Motion Without Touch Sensors</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-tiktok-video-safeguarding-on-smartphones-uncovered-for-2024/"><u>[Updated] TikTok Video Safeguarding on Smartphones Uncovered for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-crop-trim-and-perfect-mastering-video-editing-with-avidemux/"><u>2024 Approved Crop, Trim, and Perfect Mastering Video Editing with Avidemux</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlocking-team-efficiency-the-best-language-learning-apps/"><u>Unlocking Team Efficiency: The Best Language Learning Apps</u></a></li>
</ul></div>
