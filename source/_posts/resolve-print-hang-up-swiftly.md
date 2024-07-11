---
title: Resolve Print Hang-Up Swiftly
date: 2024-07-10T17:31:49.018Z
updated: 2024-07-11T17:31:49.018Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve Print Hang-Up Swiftly
excerpt: This Article Describes Resolve Print Hang-Up Swiftly
keywords: Quick Printer Troubleshooting,Fixing Print Errors Fast,Resolve Print Issues Rapidly,Immediate Solutions For Print Problems,Speedy Fixes for Hanging Prints,Efficient Print Fault Remedies,Swift Resolution of Print Hang-Ups
thumbnail: https://thmb.techidaily.com/3631238ca7c06e0c64e4d00a9d13c9e8220b196fb6f2fa2e2f0075e18f87eaf2.jpg
---

## Resolve Print Hang-Up Swiftly

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
<li><a href="https://printer-issues.techidaily.com/solutions-for-non-functional-printers/"><u>Solutions for Non-Functional Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-windows-11-support-for-mp620-printer/"><u>Finding Windows 11 Support for MP620 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-print-queue-on-windows-10/"><u>Unblock Print Queue on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-to-brother-wireless-mfc-9330c/"><u>Quick Guide to Brother Wireless MFC-9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fault-ad-services-out-of-service/"><u>Printer Fault: AD Services Out of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-10-printer-software/"><u>Troubleshoot Windows 10 Printer Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/healed-printer-communication-link/"><u>Healed Printer Communication Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-deletion-of-printers-on-pc/"><u>Mastering the Deletion of Printers on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/getting-back-online-actions-for-print-errors/"><u>Getting Back Online: Actions for Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-activity-multiple-users-detected/"><u>Printer Activity: Multiple Users Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructive-blueprint-attaching-hp-printer-8720-to-windows-system/"><u>Instructive Blueprint: Attaching HP Printer 8720 to Windows System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-printer-connectivity-issue-win7/"><u>Fixing Printer Connectivity Issue: Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inkless-printer-issues/"><u>Overcoming Inkless Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-error-canon-print-misfires/"><u>Remedying Error: Canon Print Misfires</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-overcoming-post-upgrade-prints/"><u>Successfully Overcoming Post-Upgrade Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-hidden-cause-of-blank-printouts/"><u>Unveiling the Hidden Cause of Blank Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-recurring-printer-errors-in-win10win7/"><u>Troubleshooting Recurring Printer Errors in Win10/Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-epson-inkjet-skips-printing-texts/"><u>Resolved: Epson Inkjet Skips Printing Texts</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-audiophiles-pathway-selecting-video-audio/"><u>[New] Audiophile's Pathway  Selecting Video Audio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-soundtrack-synergy-inshot-edition/"><u>[Updated] Soundtrack Synergy  InShot Edition</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-ultimate-guide-10-best-video-players-with-slow-motion-for-2024/"><u>The Ultimate Guide 10 Best Video Players with Slow Motion for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/conquer-windows-screenshots-5-recommended-recorders-for-2024/"><u>Conquer Windows Screenshots  #5 Recommended Recorders for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-gamify-success-15-best-capture-software-for-pc-and-mac/"><u>[New] In 2024, Gamify Success  #15 Best Capture Software for PC and Mac</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-hilarity-host-the-10-funniest-twitter-challenges/"><u>2024 Approved  Hilarity Host  The 10 Funniest Twitter Challenges</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-overcoming-blurry-facebook-video-views-on-devices/"><u>[New] 2024 Approved  Overcoming Blurry Facebook Video Views on Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-photos-from-galaxy-s23-tactical-edition-by-fonelab-android-recover-photos/"><u>Possible solutions to restore deleted photos from Galaxy S23 Tactical Edition.</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-5-elite-voice-recorders-for-apple-devices-unveiled/"><u>[Updated] 5 Elite Voice Recorders for Apple Devices Unveiled</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-workplace-dialogue-dominance-unraveling-slacks-edge-over-discord/"><u>[New] 2024 Approved  Workplace Dialogue Dominance  Unraveling Slack's Edge Over Discord</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-lively-letters-on-screen-bounce-with-ease-and-style/"><u>[Updated] In 2024, Lively Letters on Screen  Bounce with Ease and Style</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-google-pixel-7a-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Google Pixel 7a</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streaming-success-starts-here-8-tips-for-beginners/"><u>2024 Approved  Streaming Success Starts Here - 8 Tips for Beginners</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/share-your-pcmac-experience-with-free-recording-tools/"><u>Share Your PC/Mac Experience with Free Recording Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-poco-m6-pro-4g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Poco M6 Pro 4G Location by Number | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-s-top-rated-video-editing-software-for-avchd-files/"><u>In 2024, S Top-Rated Video Editing Software for AVCHD Files</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-inside-look-a-catalog-of-tracking-methods/"><u>[New] 2024 Approved  Inside Look  A Catalog of Tracking Methods</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/social-media-success-strategies-for-effective-facebook-reel-creation-for-2024/"><u>Social Media Success  Strategies for Effective Facebook Reel Creation for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-io-scanner-insiders-handbook-for-2024/"><u>[New] The Ultimate IO Scanner Insider's Handbook for 2024</u></a></li>
</ul></div>
