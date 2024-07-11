---
title: Fast-Track Prints in Queue
date: 2024-07-10T17:36:32.860Z
updated: 2024-07-11T17:36:32.860Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fast-Track Prints in Queue
excerpt: This Article Describes Fast-Track Prints in Queue
keywords: Fast Track Printing Services,Quick Print Queue Management,Fast-Track Print Order Processing,Rapid Prints Queue Priority Service,High-Speed Print Services for Busy Businesses,Speedy Queue Management Printing,Express Prints with Priority Queue System
thumbnail: https://thmb.techidaily.com/13464bbf7702e727674e34228111122f1f619fb5b014ebf3cf5f5ddd4c2dec0d.jpg
---

## Fast-Track Prints in Queue

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
<li><a href="https://printer-issues.techidaily.com/accelerate-queued-print-processes/"><u>Accelerate Queued Print Processes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-printer-conflicts-in-windows/"><u>Clearing Up Printer Conflicts in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-no-more-blank-documents/"><u>Fixed [Epson]: No More Blank Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-drive-efficiency-mf4770n-and-windows-systems/"><u>Boosting Drive Efficiency: MF4770n & Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/activating-scanner-on-latest-win11-release/"><u>Activating Scanner on Latest Win11 Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-usb-printers-ignoring-command-in-windows-7-mode/"><u>[Fix] USB Printers Ignoring Command in Windows 7 Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mystery-machine-paper-trail-exposed/"><u>Mystery Machine Paper Trail Exposed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-connect-canon-printer-online/"><u>Effortlessly Connect Canon Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocked-scanner-operation-in-windows-11-os/"><u>Unblocked Scanner Operation in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-epson-printing-now-continues/"><u>Halted Epson Printing, Now Continues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hasten-reconnecting-print-queued-jobs/"><u>Hasten Reconnecting Print Queued Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-for-reviving-offline-printers/"><u>Steps for Reviving Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensuring-regular-maintenayer-print-function/"><u>Ensuring Regular Maintenayer Print Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-the-no-content-print-jobs-on-an-epson-device/"><u>Fixing the 'No Content' Print Jobs on an Epson Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-lack-of-full-color-capacity/"><u>Printer's Lack of Full Color Capacity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-resolving-pcl-xl-glitches/"><u>Quick Guide: Resolving PCL XL Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-tackle-windows-11-printer-malfunctions/"><u>How to Tackle Windows 11 Printer Malfunctions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unplugging-and-removing-a-secondary-printer-from-os/"><u>Unplugging and Removing a Secondary Printer From OS</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-the-videographers-guide-to-precision-facetime-recordings/"><u>In 2024, The Videographer's Guide to Precision Facetime Recordings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boost-your-drive-10-top-motivation-films/"><u>Boost Your Drive  10 Top Motivation Films</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-search-comments-on-youtube-quickly/"><u>[Updated] How to Search Comments on YouTube Quickly?</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-legality-of-recording-on-youtube-platform/"><u>[New] 2024 Approved  Legality of Recording on YouTube Platform?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-evaluating-max-360-and-hero-11-the-ultimate-gopro-video-battle/"><u>[Updated] Evaluating Max 360 & Hero 11  The Ultimate GoPro Video Battle</u></a></li>
<li><a href="https://extra-resources.techidaily.com/traverse-costs-watch-anywhere-gratis-video-player-pcmac/"><u>Traverse Costs, Watch Anywhere - Gratis VIDEO Player (PC/Mac)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-picperfect-pro-enhance-your-mobile-images-for-free/"><u>[Updated] PicPerfect Pro  Enhance Your Mobile Images for Free</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tackling-texts-and-gifs-an-experts-meme-making-manual-for-9gag/"><u>[New] Tackling Texts and Gifs  An Expert's Meme-Making Manual for 9GAG</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/investigating-storage-amounts-vids-on-64128gb-hardware-for-2024/"><u>Investigating Storage Amounts  Vids on 64/128GB Hardware for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-polishing-your-tiktok-content-a-guide-to-filters/"><u>[Updated] Polishing Your TikTok Content  A Guide to Filters</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-11-audio-capture-devices-for-live-broadcasts/"><u>[New] Top 11 Audio Capture Devices for Live Broadcasts</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-oneplus-ace-2-pro-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On OnePlus Ace 2 Pro? Fix Now | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-harnessing-the-power-of-film-in-educational-practice/"><u>[New] Harnessing the Power of Film in Educational Practice</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-top-10-screenshot-tools-of-2021-for-2024/"><u>The Top 10 Screenshot Tools of 2021 for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-shipping-secrets-to-surprises-unveiling-new-strategies/"><u>2024 Approved  From Shipping Secrets to Surprises  Unveiling New Strategies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-starting-out-key-equipment-and-software-for-vlogging/"><u>[Updated] Starting Out  Key Equipment & Software for Vlogging</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tips-and-tricks-to-avoid-photo-crashes-on-windows-11/"><u>Tips & Tricks to Avoid Photo Crashes on Windows 11</u></a></li>
</ul></div>
