---
title: Resolve Print Queue Hang-Up Promptly
date: 2024-07-10T17:35:44.059Z
updated: 2024-07-11T17:35:44.059Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve Print Queue Hang-Up Promptly
excerpt: This Article Describes Resolve Print Queue Hang-Up Promptly
keywords: Print Queue Resolution,Immediate Print Queue Fixes,Print Spooler Troubleshooting,Printer Queue Error Resolution,Print System Stability Improvement,Fast Printer Queue Clearance,Prevent Print Queue Crashes
thumbnail: https://thmb.techidaily.com/9ce1efb4d78691d1fda3d25f6e0de4e7036d8fbbf749d1e5f5caf96b519e32e1.png
---

## Resolve Print Queue Hang-Up Promptly

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
<li><a href="https://printer-issues.techidaily.com/clearing-crosscheck-print-failures/"><u>Clearing Crosscheck Print Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-hp-printer-status/"><u>How to Reactivate HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-connect-unplugged-printer-fixed/"><u>Quick Connect: Unplugged Printer Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-printer-isolation-brothers-network-recovery-plan/"><u>Avoiding Printer Isolation: Brother's Network Recovery Plan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connected-problems-resolved-quickly/"><u>Printer Connected, Problems Resolved Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-get-your-brother-printer-back-up-and-running-on-windows/"><u>How to Get Your Brother Printer Back Up & Running on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-phantom-error-messages-on-printers/"><u>Repairing Phantom Error Messages on Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-every-page-printer-release/"><u>Get Every Page Printer Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-brother-printers-offline-hurdle/"><u>Overcoming Brother Printer's Offline Hurdle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-print-sentry-refuses-responses/"><u>My Print Sentry Refuses Responses</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-in-pages-a-success-story-for-printers/"><u>Precision in Pages: A Success Story for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-hp-color-laser-all-in-one-installation/"><u>Streamlining HP Color Laser All-In-One Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winprint-woes-successfully-fixing-error-0x00000709/"><u>WinPrint Woes: Successfully Fixing Error 0X00000709</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-error-on-windows-fixed/"><u>Printer Not Responding Error on Windows Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-busted-fixing-error-0x00000709-in-windows/"><u>Print Issue Busted: Fixing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-paper-jams-in-copiers/"><u>Preventing Paper Jams in Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-error-correction/"><u>Mastering Printer Error Correction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unstick-print-job-immediately/"><u>Unstick Print Job Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-problems-in-adding-printer/"><u>No Problems in Adding Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/duplicate-device-printing-discovered-and-tackled/"><u>Duplicate Device Printing Discovered & Tackled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-issue-canon-pixma-mp620-unsupported-by-win10/"><u>[Driver Issue] Canon Pixma MP620 Unsupported by WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-w11-color-calibration-problems/"><u>Solve W11 Color Calibration Problems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-adding-vibrancy-easy-youtube-subscribe-animations-with-filmora/"><u>[New] In 2024, Adding Vibrancy  Easy YouTube Subscribe Animations with Filmora</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-crucial-elements-when-choosing-an-audio-editor-for-apple-computers/"><u>Updated 2024 Approved Crucial Elements When Choosing an Audio Editor for Apple Computers</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-easy-methods-to-unlock-icloud-locked-iphone-12-pro-maxipadipod-by-drfone-ios/"><u>3 Easy Methods to Unlock iCloud Locked iPhone 12 Pro Max/iPad/iPod</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-innovative-ideas-for-snapad-success-in-business/"><u>[Updated] Innovative Ideas for SnapAd Success in Business</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/charting-the-evolution-of-windows-movie-maker/"><u>Charting the Evolution of Windows Movie Maker</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-streamlabs-versus-obs-a-compreran-analysis-for-broadcasters/"><u>[New] In 2024, Streamlabs Versus OBS  A Compreran Analysis for Broadcasters</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-imovie-alternatives-for-windows-1110-pcs-2023/"><u>In 2024, Best iMovie Alternatives for Windows 11/10 PCs 2023</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-key-approaches-to-enhance-vhs-photos-digitally/"><u>[Updated] Key Approaches to Enhance VHS Photos Digitally</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-oppo-a58-4g-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Oppo A58 4G.</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-split-trim-and-convert-avi-files-in-minutes-2023-edition/"><u>Updated In 2024, Split, Trim, and Convert AVI Files in Minutes 2023 Edition</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-why-does-fcpx-keep-crashing-find-out-and-fix-it/"><u>Updated Why Does FCPX Keep Crashing? Find Out and Fix It</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/tips-for-youtube-video-shooting-for-2024/"><u>Tips for YouTube Video Shooting for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-innovative-editing-methods-for-yt-videos-with-windows-movie-maker/"><u>2024 Approved  Innovative Editing Methods for YT Videos with Windows Movie Maker</u></a></li>
</ul></div>
