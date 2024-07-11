---
title: Swift Remedy for Queued Printer Issue
date: 2024-07-10T17:28:23.545Z
updated: 2024-07-11T17:28:23.545Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Swift Remedy for Queued Printer Issue
excerpt: This Article Describes Swift Remedy for Queued Printer Issue
keywords: Quick Print Problem Fix,Printer Queue Resolution,Stop Printing Delays,Halt Printer Jams Quickly,Efficient Print Issue Troubleshooting,Printer Queue Management Tips,Swift Print Issue Resolution Methods
thumbnail: https://thmb.techidaily.com/4e0785a6bbb7f888bb5d221bb92cd0cb4855dc6ae8cb9e04372b123059b2f388.jpg
---

## Swift Remedy for Queued Printer Issue

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
<li><a href="https://printer-issues.techidaily.com/resolving-network-print-problems/"><u>Resolving Network Print Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-blank-page-syndrome-in-print-devices/"><u>Fixing Blank Page Syndrome in Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-issue-unable-to-locate-hp-print-drivers-on-win11/"><u>[System Issue] - Unable to Locate HP Print Drivers on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-persistent-printer-spooler-issues-in-win-oss/"><u>Addressing Persistent Printer Spooler Issues in Win OSs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-spits-out-unprinted-sheets/"><u>Resolved: Printer Spits Out Unprinted Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wireless-setup-for-officejet-pro-m110-series-a-complete-walkthrough/"><u>Wireless Setup for Officejet Pro M110 Series: A Complete Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-non-responsive-canon-printer/"><u>How to Fix Non-Responsive Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-uncooperative-printer-status-on-winntme-os/"><u>Fixing Uncooperative Printer Status on WinNT/Me OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-error-only-blank-sheets-from-epson/"><u>Printer Setup Error: Only Blank Sheets From Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cure-print-issues-with-windows-11-advice/"><u>Cure Print Issues with Windows 11 Advice</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-cartridge-replacement-failures/"><u>Troubleshooting Cartridge Replacement Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easily-set-up-brothers-9330w-fan/"><u>Easily Set Up Brother's 9330W Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alert-local-print-queue-not-running/"><u>[ALERT] Local Print Queue Not Running</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-fan-setup-instructions/"><u>Brother CDW Duo Fan Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-printer-successfully-confirmed/"><u>Installing Printer Successfully Confirmed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-printer-on-windows-xpvista7/"><u>Fixing Offline Printer on Windows XP/Vista/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-office-printer-breakdowns/"><u>Overcoming Office Printer Breakdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-sleep-printer-issues-in-windows-7-usb-devices/"><u>Post-Sleep Printer Issues in Windows 7 USB Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-solve-brother-printer-offline-problem/"><u>How to Solve Brother Printer Offline Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/advanced-drives-mf4770n-software-upgrade-windows/"><u>Advanced Drives: MF4770n Software Upgrade Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-canon-printer-step-by-step/"><u>Installing Canon Printer - Step-by-Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hardware-added-without-issues/"><u>Printer Hardware Added Without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-code-0x97-uncovered-and-resolved/"><u>Epson Fault Code 0X97 Uncovered & Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-inaccessible-printer-network/"><u>Troubleshooting: Inaccessible Printer Network</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tuneful-texts-musical-infusion-on-whatsapp-for-2024/"><u>Tuneful Texts  Musical Infusion on WhatsApp for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-creating-compelling-solo-videos-on-a-budget-for-2024/"><u>[New] Creating Compelling Solo Videos on a Budget for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-rewind-to-save-incorporating-80s-vhs-in-todays-cinematic-edits/"><u>[Updated] From Rewind to Save  Incorporating 80S VHS in Today's Cinematic Edits</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mastering-audio-editing-expert-techniques-for-voice-isolation-in-adobe-audition-for-2024/"><u>Mastering Audio Editing Expert Techniques for Voice Isolation in Adobe Audition for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gone-sticker-refining-vids-for-a-slick-tiktok-presence/"><u>[New] Gone Sticker  Refining Vids for a Slick TikTok Presence</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-ai-script-wondershare-virbo/"><u>New 2024 Approved AI Script | Wondershare Virbo</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-elevate-your-tiktok-presence-50plus-trending-tags/"><u>[New] In 2024, Elevate Your TikTok Presence  50+ Trending Tags</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-vivo-y28-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-blaze-curve-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Blaze Curve 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-navigating-google-meet-professionally-free-of-charge-for-2024/"><u>[New] Navigating Google Meet Professionally, Free of Charge for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-gif-speed-modifiers-top-picks-for-web-iphone-and-android/"><u>New In 2024, GIF Speed Modifiers Top Picks for Web, iPhone, and Android</u></a></li>
</ul></div>
