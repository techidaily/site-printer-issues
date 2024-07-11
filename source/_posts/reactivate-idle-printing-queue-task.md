---
title: Reactivate Idle Printing Queue Task
date: 2024-07-10T17:43:02.976Z
updated: 2024-07-11T17:43:02.976Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Reactivate Idle Printing Queue Task
excerpt: This Article Describes Reactivate Idle Printing Queue Task
keywords: Reactivate IDLE Printer Queue,Idle Printing Queue Management,Resume Idle Print Jobs,Restart Printer Queue Task,Printing Queue Idle Issue Resolution,Enable Idle Printer Tasks,Revive Non-Active Printer Queue
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Reactivate Idle Printing Queue Task

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
<li><a href="https://printer-issues.techidaily.com/accelerate-clearing-print-job-queue/"><u>Accelerate Clearing Print Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guiding-through-printer-malfunction-fixes/"><u>Guiding Through Printer Malfunction Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unforeseen-setup-snag-found/"><u>Printer's Unforeseen Setup Snag Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-fedex-printer-connectivity-troubles/"><u>Rectifying FedEx Printer Connectivity Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-remedy-for-queued-printer-issue/"><u>Swift Remedy for Queued Printer Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574127184-printers-wont-print-all-pages-2024-fix/"><u>Printers Won’t Print All Pages [2024 Fix]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-operation-windows-compatible-driver-for-officejet-pro-8600/"><u>Efficient Operation: Windows Compatible Driver for Officejet Pro 8600</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-enable-brother-9330cdw-driver/"><u>Guide to Enable Brother 9330CDW Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-disruptive-print-spooler-failures-on-pcs/"><u>Preventing Disruptive Print Spooler Failures on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-missing-hp-support-in-windows-1110/"><u>[Print] Missing HP Support in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-enabling-online-scanner-in-win11/"><u>Re-Enabling Online Scanner in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/not-all-colors-printing-as-expected/"><u>Not All Colors Printing as Expected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-snag-your-printer-is-confused/"><u>Setup Snag: Your Printer Is Confused</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-all-pages-now-available/"><u>Perfect Print: All Pages Now Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-paper-shortage-2024-printer-update/"><u>Ending Paper Shortage: 2024 Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/colors-missing-in-document-output/"><u>Colors Missing in Document Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connecting-canon-printer-to-win7-successful/"><u>Connecting Canon Printer to Win7 Successful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-issue-mp620-driver-not-detected/"><u>[Windows Issue] MP620 Driver Not Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/transform-printing-experience-hp-officejets-newest-software-update/"><u>Transform Printing Experience: HP Officejet's Newest Software Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-printer-from-jamming-in-windows-11/"><u>Stop Your Printer From Jamming in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alleviating-hp-printer-error-code-oxc4eb827f/"><u>Alleviating HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-non-printing-issues-five-tactics-to-get-your-canon-running-in-windows-11/"><u>Troubleshoot Non-Printing Issues: Five Tactics to Get Your Canon Running in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/spooler-error-preventing-successful-prints/"><u>Spooler Error Preventing Successful Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/bilingual-bliss-embrace-germanys-idioms-in-25-words/"><u>Bilingual Bliss: Embrace Germany's Idioms in 25 Words</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-dance-revolution-tiktok-routines-on-a-mac-platform-for-2024/"><u>[New] Dance Revolution  TikTok Routines on a Mac Platform for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-macos-11-big-sur-essential-guide-for-upgrades/"><u>2024 Approved  MacOS 11 Big Sur  Essential Guide for Upgrades</u></a></li>
<li><a href="https://audio-editing.techidaily.com/enhancing-listening-experience-steps-for-standardizing-audio-amplitude-in-vlc-for-2024/"><u>Enhancing Listening Experience Steps for Standardizing Audio Amplitude in VLC for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-multi-snapping-made-simple-in-snapchat-video-edits-for-2024/"><u>[New] Multi-Snapping Made Simple in Snapchat Video Edits for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-nokia-c210-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Nokia C210 in Minutes | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nsider-guide-decoding-youtube-live-image-codes-for-2024/"><u>[New] Insider Guide  Decoding YouTube Live Image Codes for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-elite-nintendo-switch-fighters-showdown-max-156-for-2024/"><u>[New] Elite Nintendo Switch Fighters Showdown (Max 156) for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-freescape-extraction-revisited-a-look-at-the-latest-update/"><u>[New] Freescape Extraction Revisited  A Look at the Latest Update</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-navigate-and-network-adding-desktopmobile-friends/"><u>[Updated] Navigate & Network  Adding Desktop/Mobile Friends</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-samsung-galaxy-a54-5g-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Samsung Galaxy A54 5G</u></a></li>
</ul></div>
