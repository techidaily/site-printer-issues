---
title: Quick Fix to Printer Job Backlog
date: 2024-07-10T17:01:30.662Z
updated: 2024-07-11T17:01:30.662Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Fix to Printer Job Backlog
excerpt: This Article Describes Quick Fix to Printer Job Backlog
keywords: Printer Job Backlog,Print Queue Management,Faster Printer Processing,Printer Performance Optimization,Print Backlog Solutions,Reduce Print Job Delays,Printer Backlog Reduction Tips
thumbnail: https://thmb.techidaily.com/16a9b35c6bd9fc401c0908fd1a1024fa5ae9f4d4fbf37f1eb35abe3fab424ae1.jpg
---

## Quick Fix to Printer Job Backlog

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
<li><a href="https://printer-issues.techidaily.com/color-printing-malfunction-detected/"><u>Color Printing Malfunction Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-page-missing-issue-with-printers/"><u>Resolve Page Missing Issue with Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574032401-trouble-printing-on-windows-11-lets-fix-it/"><u>Trouble Printing on Windows 11? Let's Fix It!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-epson-ink-problem-now-prints/"><u>Corrected Epson Ink Problem, Now Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-efficiency-quickly/"><u>Enhance Printer Efficiency Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-cups-errors-streamline-win10-printer-services/"><u>Rectify CUPS Errors: Streamline WIN10 Printer Services</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-unresponsive-hp-devices/"><u>Troubleshooting Unresponsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-errors-detected-during-printer-setup/"><u>No Errors Detected During Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-solution-for-printer-not-plugged-in/"><u>Rapid Solution for Printer Not Plugged In</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-0x00000709-on-printer-selection-in-windows/"><u>Fixed Error 0X00000709 on Printer Selection in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-correction-implemented/"><u>B200 Correction Implemented</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-resolution-achieved/"><u>Code B200 Resolution Achieved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-epson-printer-to-normalcy/"><u>Restored Epson Printer to Normalcy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-offline-solved/"><u>Epson Printer Offline [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/banishing-the-whiteout-from-our-print-sources/"><u>Banishing the Whiteout From Our Print Sources</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-empty-pages-a-printers-success-story/"><u>Eliminating Empty Pages: A Printer's Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/beginners-guide-to-setting-up-a-canon-printer-with-images/"><u>Beginner's Guide to Setting up a Canon Printer (with Images)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-performance-upgrade-dell-inkjet-aio-on-windows-7/"><u>Drive Performance: Upgrade Dell Inkjet AIO on WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-queue-error-messages-on-windows-11/"><u>Fix Printing Queue Error Messages on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-print-processes-revealed/"><u>Brisk Print Processes Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-installation-issue-for-laser-printer/"><u>Fixed Installation Issue for Laser Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-faulty-connectivity-in-printers/"><u>Diagnosing Faulty Connectivity in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/erase-print-task-queue-pause/"><u>Erase Print Task Queue Pause</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-maze-getting-brothers-printer-back-on-line/"><u>Navigating the Maze: Getting Brother's Printer Back on Line</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-obstacle-with-epson/"><u>Overcome Printing Obstacle with Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstating-scan-functionality-in-windows-11/"><u>Reinstating Scan Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-and-performance-boost-officejet-pro-8600-windows-version/"><u>Compatibility & Performance Boost: Officejet Pro 8600, Windows Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-hp-printer-error-code-oxc4eb827f/"><u>Purging HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unexpected-configuration-blunder/"><u>Printer's Unexpected Configuration Blunder</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-13-mini-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 13 mini without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-unleash-your-inner-toon-16-fantastic-cartoonizer-apps/"><u>Updated In 2024, Unleash Your Inner Toon 16 Fantastic Cartoonizer Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-a-network-locked-realme-v30-phone-by-drfone-android/"><u>How to Unlock a Network Locked Realme V30 Phone?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-top-3-audio-amplifiers-boost-your-videos-and-streams-to-perfection/"><u>Updated 2024 Approved Top 3 Audio Amplifiers Boost Your Videos and Streams to Perfection</u></a></li>
<li><a href="https://article-helps.techidaily.com/10-best-practices-for-boosting-srt-on-pc-and-macos/"><u>10 Best Practices for Boosting SRT on PC & macOS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-metaverse-vs-multiverse-whats-the-difference/"><u>[New] Metaverse vs Multiverse  What's the Difference?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-capture-your-vision-leading-tablet-art-tools/"><u>[Updated] Capture Your Vision  Leading Tablet Art Tools</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-elevate-your-sound-experience-subscribe-to-20-youtube-sounds/"><u>In 2024, Elevate Your Sound Experience  Subscribe to 20 YouTube Sounds</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/top-10-websites-to-download-free-sound-clips-for-videos/"><u>Top 10 Websites to Download Free Sound Clips for Videos</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-enjoy-your-content-youtube-shorts-are-shown-again/"><u>[New] Enjoy Your Content – YouTube Shorts Are Shown Again</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-frugal-cloud-cradle-for-copious-file-collection/"><u>In 2024, Frugal Cloud Cradle for Copious File Collection</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-how-to-keep-your-videos-quiet-and-clear/"><u>2024 Approved  How to Keep Your Videos Quiet and Clear</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oppo-find-x7mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Oppo Find X7Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-discovering-where-to-get-realistic-smashing-glass-audio-cues-for-2024/"><u>Updated Discovering Where to Get Realistic Smashing Glass Audio Cues for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/photoshops-powerful-tool-image-curving-techniques-for-2024/"><u>Photoshop's Powerful Tool  Image Curving Techniques for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-enhance-your-presence-best-free-tools-for-intriguing-openings/"><u>[Updated] 2024 Approved  Enhance Your Presence  Best Free Tools for Intriguing Openings</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-create-youtube-intro-animation-like-a-pro/"><u>New 2024 Approved How to Create YouTube Intro Animation Like a Pro</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-make-unforgettable-moments-top-video-collage-apps-for-ios/"><u>2024 Approved Make Unforgettable Moments Top Video Collage Apps for iOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-taking-views-viral-the-ultimate-guide-for-youtube-success/"><u>In 2024, Taking Views Viral  The Ultimate Guide for YouTube Success</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-oppo-reno-11-pro-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-strategies-for-discovering-personal-style-identity-for-2024/"><u>[Updated] Strategies for Discovering Personal Style Identity for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-streamlining-sound-quality-the-best-three-approaches-for-podcast-to-mp3-transition/"><u>In 2024, Streamlining Sound Quality The Best Three Approaches for Podcast to MP3 Transition</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-mastering-zooms-filters-for-clear-premium-calls/"><u>[New] In 2024, Mastering Zoom's Filters for Clear, Premium Calls</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-essential-tips-for-smooth-screen-sharing-on-skype-while-working-from-home/"><u>2024 Approved  Essential Tips for Smooth Screen Sharing on Skype While Working From Home</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-radiant-hue-tuner-program/"><u>[Updated] Radiant Hue Tuner Program</u></a></li>
</ul></div>
