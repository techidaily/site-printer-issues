---
title: Erase Print Task Queue Pause
date: 2024-07-10T16:46:11.421Z
updated: 2024-07-11T16:46:11.421Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Erase Print Task Queue Pause
excerpt: This Article Describes Erase Print Task Queue Pause
keywords: Erase Print Tasks,Cancel Printer Jobs,Halt Printing Queue,Pause Document Printing,Resume Print Queue,Stop Printing Process,Undo Recent Prints,Search Volume,Competitiveness,Relevance
thumbnail: https://thmb.techidaily.com/086d7c930c164ea9d01018f76fb536ddc6879aa44f658266ac4dd473faff469b.jpg
---

## Erase Print Task Queue Pause

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
<li><a href="https://printer-issues.techidaily.com/hp-printers-white-sheets-cured-with-new-solution/"><u>HP Printer’s White Sheets Cured with New Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-ink-and-paper-feed-issues-in-hp/"><u>Diagnosing Ink and Paper Feed Issues in HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-restore-printer-functionality/"><u>Steps to Restore Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-print-error-on-hp-deskjet-4120x-resolved/"><u>No-Print Error on HP DeskJet 4120X Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fix-scanner-disconnection-in-windows-10/"><u>Guide to Fix Scanner Disconnection in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-stopped-working-after-windows-11-update/"><u>SOLVED: Printer Stopped Working After Windows 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstate-scanner-connection-on-windows-10-machine/"><u>Reinstate Scanner Connection on Windows 10 Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-deletion-of-printers-on-pc/"><u>Mastering the Deletion of Printers on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-recurring-spooler-errors-on-wx-w10-w11/"><u>Combat Recurring Spooler Errors on WX, W10, W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/journeys-end-successfully-setting-up-hp-printer-in-win-os/"><u>Journey's End: Successfully Setting Up HP Printer in Win OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/second-pc-same-printer-issue-resolved/"><u>Second PC, Same Printer Issue? Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-error-now-working/"><u>Epson Printer Error, Now Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-remedies-for-common-pcl-xl-issues/"><u>Efficient Remedies for Common PCL XL Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/networking-issues-fixed-win7-printer-online/"><u>Networking Issues Fixed: Win7 Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-ink-cartridge-errors-in-printers/"><u>Decoding Ink Cartridge Errors in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-fix-for-blank-sheets-in-hp-printers-cycle/"><u>Successful Fix for Blank Sheets in HP Printer's Cycle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-millennium-xps-sluggish-printer-response/"><u>Fix Windows Millennium XP's Sluggish Printer Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypass-print-job-delay-quickly/"><u>Bypass Print Job Delay Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1187/"><u>Canon MF4770n Driver Update in Windows 11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-printing-resumes-after-upgraded-system-changes/"><u>Smooth Printing Resumes After Upgraded System Changes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-error-oxc4eb827f/"><u>Troubleshooting HP Printer Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-your-canon-printer-disconnects/"><u>Troubleshooting: Your Canon Printer Disconnects</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugged-reset-to-bring-canon-printer-back-online/"><u>Unplugged? Reset to Bring Canon Printer Back Online</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oppo-a1-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Oppo A1 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-iphone-15-plus-stuck-at-attempting-data-recovery-loop-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix iPhone 15 Plus Stuck at attempting data recovery Loop | Stellar</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/resize-crop-and-convert-top-online-image-ratio-tools-for-2024/"><u>Resize, Crop, and Convert Top Online Image Ratio Tools for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-a-step-by-step-journey-mac-and-pcs-path-to-tiktok-videos/"><u>[New] A Step-by-Step Journey  Mac & PC's Path to TikTok Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-podcast-broadcast-simplifier/"><u>In 2024, Ultimate Podcast Broadcast Simplifier</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/thriving-onscreen-financial-growth-in-the-youtube-arena/"><u>Thriving Onscreen  Financial Growth in the YouTube Arena</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-elevating-listener-experience-through-powerful-podcast-covers-the-latest-design-dos-and-donts/"><u>New In 2024, Elevating Listener Experience Through Powerful Podcast Covers (The Latest Design Dos and Donts)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-bring-back-faded-watch-icon-artwork/"><u>2024 Approved  Bring Back Faded Watch Icon Artwork</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-smart-7-hd-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-poco-c55-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Poco C55 Phone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-visual-cohesion-through-simple-fading-techniques/"><u>[Updated] 2024 Approved  Visual Cohesion Through Simple Fading Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-poco-c50-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Poco C50 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-optimize-your-presence-mastering-snapchat-business-use/"><u>[Updated] In 2024, Optimize Your Presence  Mastering Snapchat Business Use</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/insta-chat-101-an-introduction-to-online-video-talks/"><u>Insta Chat 101  An Introduction to Online Video Talks</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
</ul></div>
