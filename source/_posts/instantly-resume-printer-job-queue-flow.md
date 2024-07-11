---
title: Instantly Resume Printer Job Queue Flow
date: 2024-07-10T17:46:30.733Z
updated: 2024-07-11T17:46:30.733Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantly Resume Printer Job Queue Flow
excerpt: This Article Describes Instantly Resume Printer Job Queue Flow
keywords: Printer Job Management,Instant Printer Queue Recovery,Print Job Queue Optimization,Resume Printer Workflow Automation,Continuous Print Job Processing,Print Spooler Management,Printer Queue Error Resolution
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Instantly Resume Printer Job Queue Flow

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
<li><a href="https://printer-issues.techidaily.com/dealing-with-dormant-printers/"><u>Dealing with Dormant Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-starting-spooler-on-your-pc-windows/"><u>Troubleshooting Non-Starting Spooler on Your PC (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-streamline-of-hindered-printer-jobs/"><u>Quick Streamline of Hindered Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recommendations-for-reactivating-inactive-hp-paper-feeders/"><u>Recommendations for Reactivating Inactive HP Paper Feeders</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-solve-stuck-printer-job-queue/"><u>Swiftly Solve Stuck Printer Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-releasing-a-stuck-printer-from-windows/"><u>Quick Guide: Releasing A Stuck Printer From Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-woes-after-suspend-on-windows-7-systems/"><u>Printer Woes After Suspend on Windows 7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-guide-to-smoothly-linking-canon-printers/"><u>A Guide to Smoothly Linking Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-scan-to-computer-is-no-longer-activated-on-windows-11/"><u>Solved: Scan to Computer Is No Longer Activated on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canon-printer-not-responding/"><u>[FIXED] Canon Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-install-errors/"><u>Resolved Printer Install Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-engage-withprinter-online-troubleshooting-steps/"><u>Re-Engage Withprinter: Online Troubleshooting Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrate-mf4770n-for-optimal-performance-on-win11-8-7-systems/"><u>Integrate MF4770n for Optimal Performance on Win11, 8, 7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/master-brother-printer-print-issues-a-win1011-fix-guide/"><u>Master Brother Printer Print Issues: A Win10/11 Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-ad-domain-offline/"><u>PPrintError - AD Domain Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicate-printer-errors-on-windows-10-pc/"><u>Eradicate Printer Errors on Windows 10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quickly-rectify-non-printing-problem-top-5-techniques-to-aid-canon-print-on-window-11/"><u>Quickly Rectify Non-Printing Problem: Top 5 Techniques to Aid Canon Print on Window 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-restore-printer-functionality/"><u>Steps to Restore Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-unprinted-printer/"><u>Troubleshooting: Unprinted Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-installing-hp-photosmart-printer/"><u>Step-by-Step: Installing HP PhotoSmart Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-prints-new-dell-v305-windows-enhancements/"><u>Streamline Prints: New Dell V305 WIndows Enhancements</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hasten-printer-job-advancement/"><u>Hasten Printer Job Advancement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-interactions-mf4770n-update-in-win11win87-os/"><u>Enhance Device Interactions: MF4770n Update in Win11/Win8/7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-recurring-spooler-errors-on-wx-w10-w11/"><u>Combat Recurring Spooler Errors on WX, W10, W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-frustration-to-functionality-blank-page-cured/"><u>From Frustration to Functionality: Blank Page Cured</u></a></li>
<li><a href="https://printer-issues.techidaily.com/improve-print-quality-fixing-win10-drivers/"><u>Improve Print Quality: Fixing WIN10 Drivers</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-5-most-user-friendly-online-tone-creators/"><u>Updated In 2024, The 5 Most User-Friendly Online Tone Creators</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-lenovo-thinkphone-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Lenovo ThinkPhone ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-14-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 14 Pro Max without iTunes? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/visiovista-android-and-ios-instagram-tile-artisan/"><u>VisioVista  Android & iOS Instagram Tile Artisan</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-hp-laptop-tips-for-perfect-screen-recordings/"><u>[New] 2024 Approved  HP Laptop Tips for Perfect Screen Recordings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-perfectly-pairing-photos-step-by-step-guide/"><u>[New] 2024 Approved  Perfectly Pairing Photos - Step-by-Step Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-here-is-how-you-can-do-it-effectively-either-with-built-in-tools-provided-by-tiktok-or-with-additional-pieces-of-reverser-tools-to-reverse/"><u>New 2024 Approved Here Is How You Can Do It Effectively, Either with Built-In Tools Provided by TikTok or with Additional Pieces of Reverser Tools to Reverse a TikTok Video</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ultimate-compilation-of-ios-compatible-ps2-games-for-2024/"><u>[New] Ultimate Compilation of iOS-Compatible PS2 Games for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-mastering-iphone-audio-recordings-a-detailed-tutorial/"><u>New 2024 Approved Mastering iPhone Audio Recordings A Detailed Tutorial</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-crowded-online-spaces-offering-no-cost-guitar-song-lines-and-artwork/"><u>Updated Crowded Online Spaces Offering No-Cost Guitar Song Lines and Artwork</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-honor-magic-6-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Honor Magic 6 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/digital-imaging-secrets-focusing-with-targeted-blurs/"><u>Digital Imaging Secrets  Focusing with Targeted Blurs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-unlock-the-secret-sauce-of-making-money-with-vimeo-ads/"><u>In 2024, Unlock the Secret Sauce of Making Money with Vimeo Ads</u></a></li>
</ul></div>
