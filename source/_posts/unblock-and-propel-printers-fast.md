---
title: Unblock and Propel Printers Fast
date: 2024-07-10T17:11:31.334Z
updated: 2024-07-11T17:11:31.334Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unblock and Propel Printers Fast
excerpt: This Article Describes Unblock and Propel Printers Fast
keywords: Printer Performance Optimization,Printhead Cleaning Tips,Speeding Up Printers,Unblock Cartridge Issue Solutions,Quick Printer Maintenance Tricks,High-Speed Printer Technology,Efficient Printer Setup Techniques
thumbnail: https://thmb.techidaily.com/f495fdc30704bb5311bdcea6bec28c308373dbaff21b69f564e50f099e806a16.jpg
---

## Unblock and Propel Printers Fast

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
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-canon-pixma-mp620-and-windows-11-clash/"><u>[Compatibility] Canon Pixma MP620 and Windows 11 Clash</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cease-print-slowdown-in-winxp-solution-found/"><u>Cease Print Slowdown in WinXP - Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-it-running-smoothly-update-dells-inkjet-aio-on-windows-7/"><u>Keep It Running Smoothly: Update Dell's Inkjet AIO on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnostic-unable-to-start-local-spooler-service/"><u>[DIAGNOSTIC] Unable to Start Local Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/erase-print-task-queue-pause/"><u>Erase Print Task Queue Pause</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fixing-silent-hp-toner-units/"><u>Guide to Fixing Silent HP Toner Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bring-to-life-enable-your-silent-canon-print-spooler/"><u>Bring To Life: Enable Your Silent Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-overcome-unresponsive-hp-devices/"><u>Strategies to Overcome Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-detected-windows-print-error/"><u>Driver Not Detected: Windows Print Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-error-code-b200/"><u>Mended Error Code: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-paper-size-error-on-hp-deskjet-3070/"><u>Fixed Paper Size Error on HP DeskJet 3070</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-lack-of-full-color-capacity/"><u>Printer's Lack of Full Color Capacity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-your-non-printing-canon-into-a-reliable-device-with-tips/"><u>Turn Your Non-Printing Canon Into a Reliable Device with Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-network-print-problems/"><u>Resolving Network Print Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-react-when-your-printer-disconnects/"><u>How to React When Your Printer Disconnects</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-issue-printer-drivers-failing-on-w7-10-need-solution/"><u>[Technical Issue] Printer Drivers Failing on W7-10, Need Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-inactive-scanner-on-windows-11/"><u>Overcoming Inactive Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-prints-install-latest-v305-driver-in-win7/"><u>Revitalize Your Prints: Install Latest V305 Driver in Win7</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-why-no-video-suggestions-pop-up-in-your-social-media-world/"><u>[Updated] 2024 Approved  Why No Video Suggestions Pop Up in Your Social Media World?</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-create-stunning-intros-10-website-recommendations/"><u>New In 2024, Create Stunning Intros 10 Website Recommendations</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/maximizing-impact-livestreaming-360-degree-video-magic-on-youtube-for-2024/"><u>Maximizing Impact  Livestreaming 360-Degree Video Magic on YouTube for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-beats-and-boundaries-breaking-barriers-in-music-videos/"><u>In 2024, Beats & Boundaries  Breaking Barriers in Music Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-elegant-architecture-top-6-sleek-mc-houses/"><u>[Updated] In 2024, Elegant Architecture  Top 6 Sleek MC Houses</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/soaring-visions-with-dji-mavic-pro-insight/"><u>Soaring Visions with DJI Mavic Pro Insight</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-minimal-effort-maximum-recovery-for-deleted-posts/"><u>[Updated] Minimal Effort, Maximum Recovery for Deleted Posts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-topeightunleashed-cutting-edge-4k-blu-ray-systems/"><u>[New] TopEightUnleashed  Cutting-Edge 4K Blu-Ray Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-google-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after Google has been deleted</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-how-to-remove-the-endless-loop-from-animated-gif-for-2024/"><u>New How To Remove The Endless Loop From Animated GIF for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-15-pro-max-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Pro Max Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-from-sketches-to-high-end-graphics-best-software-reviewed/"><u>[New] From Sketches to High-End Graphics  Best Software Reviewed</u></a></li>
</ul></div>
