---
title: Speedy Clearance of Stalled Print Queue
date: 2024-07-10T17:39:29.426Z
updated: 2024-07-11T17:39:29.426Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speedy Clearance of Stalled Print Queue
excerpt: This Article Describes Speedy Clearance of Stalled Print Queue
keywords: Fast Print Job Resumption,Quick Resolution for Printer Queues,Remediation of Halted Printing Processes,Efficient Handling of Print Queue Issues,Speedy Restoration of Print Service,Immediate Fix for Stalled Print Operations,Rapid Clearance of Printer Queue Backups
thumbnail: https://thmb.techidaily.com/8443124490dd4d26d174966fed147fd5721a9572389508714a7b16fe1b9aa1b0.jpg
---

## Speedy Clearance of Stalled Print Queue

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
<li><a href="https://printer-issues.techidaily.com/unlock-hidden-printer-features-in-win10-systems/"><u>Unlock Hidden Printer Features in WIN10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-mf4770n-support-software-windows-xp-7/"><u>Installing MF4770n Support Software Windows XP-7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turbocharge-printer-operations/"><u>Turbocharge Printer Operations</u></a></li>
<li><a href="https://printer-issues.techidaily.com/handling-printers-gone-dark/"><u>Handling Printers Gone Dark</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstating-scan-functionality-in-windows-11/"><u>Reinstating Scan Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/supercharge-dells-v305-inkjets-with-new-windows-driver/"><u>Supercharge Dell's V305 Inkjets with New Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/getting-back-online-actions-for-print-errors/"><u>Getting Back Online: Actions for Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/celebrating-clear-documentation-with-every-page/"><u>Celebrating Clear Documentation with Every Page</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-connectivity-gaps-for-windows-10-printing-issues/"><u>Bridge Connectivity Gaps for Windows 10 Printing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-hp-printer-fault-0xoxc4eb827f/"><u>Addressing HP Printer Fault: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-solved-error-avoided/"><u>Printer Puzzle Solved: Error Avoided</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-solution-for-printer-not-plugged-in/"><u>Rapid Solution for Printer Not Plugged In</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-printers-availability-with-these-tips/"><u>Regain Printer's Availability with These Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instruction-adding-officejet-pro-8720-to-computer-setup/"><u>Instruction: Adding OfficeJet Pro 8720 to Computer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-inactive-print-devices/"><u>Solutions for Inactive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquering-printer-malfunction-after-win-10-fixes/"><u>Conquering Printer Malfunction After Win 10 Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-printer-successfully-confirmed/"><u>Installing Printer Successfully Confirmed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-removal-guide-for-external-devices/"><u>Win Removal Guide for External Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-issue/"><u>Mended Printer Network Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paperless-challenges-ended-with-windows-upgrade/"><u>Paperless Challenges Ended with Window's Upgrade</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574058416-5-easy-ways-to-fix-canon-printer-wont-print-in-windows-10/"><u>5 Easy Ways to Fix Canon Printer Won’t Print in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-b200/"><u>Error Resolution: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-re-enable-scanned-device-connection/"><u>Windows 10: Re-Enable Scanned Device Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-blank-page-error-in-your-homes-epson-printer/"><u>Fix Blank Page Error in Your Home's Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-disruptive-print-spooler-failures-on-pcs/"><u>Preventing Disruptive Print Spooler Failures on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-sleephibernate-glitch-with-usb-printers-w7/"><u>[Resolved] Sleep/Hibernate Glitch with USB Printers, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-network-printer/"><u>Successfully Installed Network Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-service-restored-in-win7/"><u>Print Service Restored in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-solutions-for-brother-printer-print-problems-in-windows-1011/"><u>Quick Solutions for Brother Printer Print Problems in Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-wireless-printer-with-hp-color-life-series/"><u>How To: Set Up a Wireless Printer with HP Color Life Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-code-0x00000709-to-fix-default-printer-setup/"><u>Cracking Code 0X00000709 to Fix Default Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-my-printer-skips-colors/"><u>Why My Printer Skips Colors?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-standby-mode-glitch/"><u>Corrected Standby Mode Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-setup-software-package-hp-officejet-pro-8600-for-pcs/"><u>Quick Setup Software Package: HP OfficeJet Pro 8600 for PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-tech-tips-for-muted-movements-removing-audio-from-your-iphone-media/"><u>New Tech Tips for Muted Movements Removing Audio From Your iPhone Media</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-auditory-aids-the-ultimate-list-of-premium-discord-music-bots-to-try/"><u>Top Auditory Aids  The Ultimate List of Premium Discord Music Bots to Try</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/comprehensive-manual-mastering-mobizen-recorders/"><u>Comprehensive Manual  Mastering Mobizen Recorders</u></a></li>
<li><a href="https://extra-support.techidaily.com/shimmer-shots-the-art-of-setting-the-scene-with-light-for-2024/"><u>Shimmer Shots  The Art of Setting the Scene with Light for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-expert-tips-for-cutting-and-splicing-360-degree-footage-in-adobe-premiere/"><u>2024 Approved  Expert Tips for Cutting and Splicing 360-Degree Footage in Adobe Premiere</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-victory-tackling-video-tribulations-head-on/"><u>[New] 2024 Approved  Instagram Victory  Tackling Video Tribulations Head-On</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/journey-through-linguistic-landscapes-discovering-squid-game/"><u>Journey Through Linguistic Landscapes: Discovering Squid Game</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-m14-4g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy M14 4G</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-samsung-galaxy-a14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-honor-100-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Honor 100 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-smartphone-stories-to-youtube-success-a-step-by-step-mobile-guide-for-2024/"><u>From Smartphone Stories to YouTube Success  A Step-by-Step Mobile Guide for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1714257873365-updated-gopro-quik-vs-the-competition-a-review-and-alternative-options-for-pc-for-2024/"><u>Updated GoPro Quik Vs. The Competition A Review and Alternative Options for PC for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-making-a-lasting-impact-with-office-meetings-via-snap-camera-for-2024/"><u>[New] Making a Lasting Impact with Office Meetings via Snap Camera for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-captured-discourse-inspection/"><u>2024 Approved  Captured Discourse Inspection</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-content-for-success-how-to-start-your-own-youtube-chanel-for-2024/"><u>Crafting Content for Success  How to Start Your Own YouTube Chanel for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-poco-x6-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Poco X6 FRP Locks</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-comprehensive-guide-to-crafting-an-authentic-online-persona-on-facebook/"><u>[Updated] In 2024, The Comprehensive Guide to Crafting an Authentic Online Persona on Facebook</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-best-background-music-remover-to-help-you-remove-background-music-for-2024/"><u>Updated Best Background Music Remover to Help You Remove Background Music for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebooks-viewing-wave-the-hottest-videos-this-year/"><u>[Updated] Facebook’s Viewing Wave  The Hottest Videos This Year</u></a></li>
</ul></div>
