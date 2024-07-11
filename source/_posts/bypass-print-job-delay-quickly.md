---
title: Bypass Print Job Delay Quickly
date: 2024-07-10T16:56:50.519Z
updated: 2024-07-11T16:56:50.519Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Bypass Print Job Delay Quickly
excerpt: This Article Describes Bypass Print Job Delay Quickly
keywords: Print Job Bypass,Quick Print Delay Fix,Speed Up Printer Jobs,Avoid Print Queue Delays,Prevent Printer Job Hangups,Rapid Print Processing Solutions,Eliminate Printer Job Wait Time
thumbnail: https://thmb.techidaily.com/843a2530bd30cf31b24741cc2e56b474bee5d065dd6fb56cbf786d1e09002e10.jpg
---

## Bypass Print Job Delay Quickly

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
<li><a href="https://printer-issues.techidaily.com/unblocking-printer-service-on-windows-10-11-7/"><u>Unblocking Printer Service on Windows 10, 11, 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-air-glide-cdw-duo-instructions/"><u>Brother Air Glide CDW Duo Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-year-new-ways-to-integrate-your-laptop-and-printer-effortlessly/"><u>New Year, New Ways to Integrate Your Laptop & Printer Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-swift-printers/"><u>Quick Tips for Swift Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-windows-9598-print-jobs-that-wont-respond/"><u>Revive Windows 95/98 Print Jobs That Won't Respond</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-snag-your-printer-is-confused/"><u>Setup Snag: Your Printer Is Confused</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elegant-setup-procedure-for-high-performance-hp-printers-in-windows/"><u>Elegant Setup Procedure for High-Performance HP Printers in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-simple-steps-to-make-your-canon-printer-work-again/"><u>5 Simple Steps to Make Your Canon Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-non-responsive-hp-printers/"><u>Resolving Non-Responsive HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-confounding-error-0x97-explained/"><u>Epson's Confounding Error 0X97 Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-corrective-action-complete/"><u>B200 Corrective Action Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-unresponsive-xp-printer-jobs-without-delay/"><u>Fix Unresponsive XP Printer Jobs Without Delay</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-searching-for-driver-on-win11/"><u>Canon Pixma MP620: Searching for Driver on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-wont-detect-canon-mp620-printer-what-now/"><u>Windows 11 Won't Detect Canon MP620 Printer, What Now?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-usage-fluctuation-raises-eyebrows/"><u>Printer Usage Fluctuation Raises Eyebrows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-print-driver-missing-in-windows-1110/"><u>HP Print Driver Missing in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-inkjet-and-laser-issues-win10-style/"><u>Fix Inkjet & Laser Issues, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574168670-how-to-fix-a-printer-that-wont-print/"><u>How to Fix a Printer That Won’t Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recognition-failure-hp-driver-missing-in-win1011/"><u>Printer Recognition Failure: HP Driver Missing in WIN10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-paper-trail-issue-error-0x00000709-solution-found/"><u>Windows Paper Trail Issue - Error 0X00000709 Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-brother-wireless-9330cdw-fan/"><u>Install Brother Wireless 9330CDW Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-print-experience-with-win-hp-printer-guide/"><u>Streamline Your Print Experience with Win HP Printer Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-mishap-printer-setup-misstep/"><u>Technical Mishap: Printer Setup Misstep!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-restore-your-canons-connectivity/"><u>Step-by-Step Guide to Restore Your Canon's Connectivity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-online-offline-print-status-anomaly/"><u>Fixing Online-Offline Print Status Anomaly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerate-stuck-printer-operations/"><u>Accelerate Stuck Printer Operations</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/live-obs-video-on-instagram-for-2024/"><u>Live OBS Video on Instagram for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-mastering-the-nuances-of-high-resolution-vr-recordings/"><u>2024 Approved  Mastering the Nuances of High-Resolution VR Recordings</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-understanding-tiktoks-profile-picture-language-pfp-for-2024/"><u>[New] Understanding TikTok's Profile Picture Language (PFP) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-storytellers-edge-integrating-youtube-vids-with-ig/"><u>[Updated] 2024 Approved  The Storyteller's Edge  Integrating YouTube Vids with IG</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-samsung-galaxy-s23-ultra-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Samsung Galaxy S23 Ultra Location | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-tips-for-constructing-inspirational-day-to-day-visual-narratives/"><u>In 2024, Tips for Constructing Inspirational Day-to-Day Visual Narratives</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-finding-the-perfect-pair-matching-mics-with-every-type-of-youtubers-style/"><u>In 2024, Finding the Perfect Pair  Matching Mics with Every Type of YouTuber's Style</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-essential-guide-to-mac-screen-recording-with-shortcuts/"><u>2024 Approved  The Essential Guide to Mac Screen Recording with Shortcuts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-se-2020-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone SE (2020) Space | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/conquer-online-video-platforms-zooming-into-youtube-and-fb-lives/"><u>Conquer Online Video Platforms  Zooming Into YouTube & FB Lives</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-erase-iphone-6-plus-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Erase iPhone 6 Plus When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-optimal-obs-configurations-on-budget-computers/"><u>In 2024, Optimal OBS Configurations on Budget Computers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unveiling-youtubes-most-innovative-ad-designers/"><u>2024 Approved  Unveiling YouTube’s Most Innovative Ad Designers</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-15-top-newsroom-ambiance-tracks-compilation/"><u>New 15 Top Newsroom Ambiance Tracks Compilation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-from-words-to-memos-iphone-sound-guide/"><u>[New] From Words to Memos  IPhone Sound Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/capture-igtv-media-step-by-step-guide-for-pc-and-mac-devices-for-2024/"><u>Capture IGTV Media  Step-by-Step Guide for PC & Mac Devices for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-the-best-webcam-recorders-for-windows-11/"><u>[Updated] 2024 Approved  The Best Webcam Recorders for Windows 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-unveiling-the-secrets-to-supervised-simultaneous-streams/"><u>[New] 2024 Approved  Unveiling the Secrets to Supervised Simultaneous Streams</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-mastering-slack-and-filmora-efficient-meeting-planning-and-recording-guide/"><u>2024 Approved  Mastering Slack & Filmora  Efficient Meeting Planning & Recording Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-what-is-mukbang-and-how-to-make-mukbang-videos/"><u>2024 Approved  What Is Mukbang and How to Make Mukbang Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-meizu-21-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-ultimate-movie-watchlists-for-efficient-screen-time/"><u>[Updated] In 2024, Ultimate Movie Watchlists for Efficient Screen Time</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/apeaks-leap-forward-in-screen-capture-review-and-results-for-2024/"><u>Apeak’s Leap Forward in Screen Capture – Review and Results for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Nokia C02 | Dr.fone</u></a></li>
</ul></div>
