---
title: Speedy Release From Print Lineup
date: 2024-07-10T17:15:02.513Z
updated: 2024-07-11T17:15:02.513Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speedy Release From Print Lineup
excerpt: This Article Describes Speedy Release From Print Lineup
keywords: Speedy Printer Release,Rapid Print Production,Quick Print Lineup Turnaround,High-Speed Printer Manufacturer,Faster Print Lineup Options,Speedy Printer Lineup Models,Quick Print Press Release Schedule
thumbnail: https://thmb.techidaily.com/06768f0764e3fd16593ec6ab66fe93ff9404677c09f36129dabffcc95362a115.jpg
---

## Speedy Release From Print Lineup

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
<li><a href="https://printer-issues.techidaily.com/printer-optimization-made-simple/"><u>Printer Optimization Made Simple</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-brother-printer-not-printing-on-windows-1110/"><u>How to Fix Brother Printer Not Printing on Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steering-clear-obstacles-onboard-brother-printer-again/"><u>Steering Clear Obstacles: Onboard Brother Printer Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-non-responsive-hp-devices/"><u>Methods to Reactivate Non-Responsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mp620-printer-driver-unavailable-on-windows-10/"><u>Canon MP620 Printer Driver Unavailable on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-from-sleep-troubleshooting-usb-printer-not-working/"><u>Wake From Sleep: Troubleshooting USB Printer Not Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-print-problem-devices-unresponsive-post-sleep/"><u>Win7 Print Problem: Devices Unresponsive Post-Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-repeated-print-job-failures-guide-for-windows-107-users/"><u>End Repeated Print Job Failures: Guide for Windows 10/7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expeditiously-address-printer-job-stall/"><u>Expeditiously Address Printer Job Stall</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-unresponsive-printers/"><u>Repairing Unresponsive Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-sync-with-print-devices/"><u>Restoring Sync with Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-network-communication-issue/"><u>Repaired Network Communication Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-leads-to-non-printer-functionality/"><u>Win 11 Update Leads to Non-Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fix-scanner-disconnection-in-windows-10/"><u>Guide to Fix Scanner Disconnection in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mysterious-print-job-by-secondary-computer/"><u>Mysterious Print Job by Secondary Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-printer-manager-for-windows-systems/"><u>HP Officejet Pro 8600 Printer Manager for Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-driver-download-for-windows/"><u>HP Officejet Pro 8600 Driver Download for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canons-non-print-dilemma-with-these-quick-fixes-in-windows-11/"><u>Overcome Canon's Non-Print Dilemma with These Quick Fixes in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seeking-solutions-for-print-device-driver-failure-in-windows-os/"><u>Seeking Solutions for Print Device Driver Failure in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-troubles-try-these-5-simple-ways-to-help-your-canon-print-on-windows-11/"><u>Print Troubles? Try These 5 Simple Ways to Help Your Canon Print on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-job-queue-freeze/"><u>Overcome Print Job Queue Freeze</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574106588-fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-mf4770n-functions-on-w11w8w7-os/"><u>Streamlining MF4770n Functions on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hijacked-multiple-sessions-spotted/"><u>Printer Hijacked? Multiple Sessions Spotted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-printer-printing-blank-pages/"><u>[SOLVED] Epson Printer Printing Blank Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-intermittent-print-job-failures-windows/"><u>Steps to Stop Intermittent Print Job Failures (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-cannot-retrieve-printer-drivers/"><u>Windows Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/comprehensive-support-pack-officejet-pro-8600-windows-edition/"><u>Comprehensive Support Pack: Officejet Pro 8600, Windows Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-operational-usb-printers-in-sleep-mode-w7/"><u>Troubleshooting Non-Operational USB Printers in Sleep Mode, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-hp-inkjets-download-and-upgrade-tips/"><u>Streamline Your HP Inkjets - Download and Upgrade Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-steps-for-windows-11/"><u>Printer Not Responding: Steps for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-solution-to-pcl-xl-problems/"><u>Effortless Solution to PCL XL Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-disappearing-printers-in-windows-810/"><u>How to Fix Disappearing Printers in WIndows 8/10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/real-time-media-streamers-app-overview-for-2024/"><u>Real-Time Media Streamer's App Overview for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-pro-tips-to-perfectly-capture-your-mac-with-ease-and-speed/"><u>2024 Approved  Pro Tips to Perfectly Capture Your Mac with Ease and Speed</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-se-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/boost-engagement-stream-live-from-twitch-embed-on-fb/"><u>Boost Engagement  Stream Live From Twitch, Embed on FB</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-pcmaclaptop-easy-obs-setup-for-fb-livestreaming/"><u>2024 Approved  PC/Mac/Laptop  Easy OBS Setup for FB Livestreaming</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-trace-the-tonal-embodiment-of-an-ancient-bell-for-2024/"><u>Updated Trace the Tonal Embodiment of an Ancient Bell for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-maximizing-your-youtube-potential-with-content-partnerships/"><u>[New] Maximizing Your YouTube Potential with Content Partnerships</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-termination-immersive-reality/"><u>In 2024, Ideal Termination  Immersive Reality</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-fcp-a-guide-to-obtaining-copy-without-cost/"><u>[Updated] Unlocking FCP  A Guide to Obtaining Copy Without Cost</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-se-2020-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone SE (2020) Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-influential-tiktok-treasures-your-top-30-amazon-list/"><u>[Updated] In 2024, Influential TikTok Treasures – Your Top 30 Amazon List</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-motorola-razr-40-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Motorola Razr 40 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/be-heard-in-discord-understanding-tts-functions/"><u>Be Heard in Discord  Understanding TTS Functions</u></a></li>
</ul></div>
