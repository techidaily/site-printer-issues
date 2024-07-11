---
title: Deactivate Stalled Print Job Queue Fastly
date: 2024-07-10T17:25:04.878Z
updated: 2024-07-11T17:25:04.878Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Deactivate Stalled Print Job Queue Fastly
excerpt: This Article Describes Deactivate Stalled Print Job Queue Fastly
keywords: Stalled Print Job Queue,Fastly Deactivation,Print Job Queue Management,Fast Print Job Resolution,Queue Clearance Techniques,Interrupt Print Job Queue,Optimize Print Processes with Fastly
thumbnail: https://thmb.techidaily.com/18c9dd2cba19f0ecf97513cafd5088c9e4acab9c65510cdf2678db2edca6954d.jpg
---

## Deactivate Stalled Print Job Queue Fastly

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
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/convenient-canon-printer-wireless-integration/"><u>Convenient Canon Printer Wireless Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-and-connecting-printer-error-resolved/"><u>Installing and Connecting Printer Error Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-printers-availability-with-these-tips/"><u>Regain Printer's Availability with These Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-secrets-of-pcl-xl-repairs/"><u>Unraveling the Secrets of PCL XL Repairs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/synchronize-printer-settings-across-multiple-devices-win10-style/"><u>Synchronize Printer Settings Across Multiple Devices, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-print-job-stuck-in-queue-quickly/"><u>Fix ‘Print Job Stuck in Queue’ Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fix-new-os-upgrade-mishap/"><u>Printer Fix: New OS Upgrade Mishap</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-hp-printer-on-win1110/"><u>Unable to Connect HP Printer on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problem-hp-printer-driver-issues-across-windows-versions/"><u>[Network Problem] HP Printer Driver Issues Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-fix-for-offline-hp-desktop/"><u>Successful Fix for Offline HP Desktop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-an-idle-brothers-printer-networkly/"><u>How to Reactivate an Idle Brothers Printer Networkly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-unprinted-pages-on-hp-printer-now/"><u>No More Unprinted Pages on HP Printer Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-printer-stands-silent-no-more/"><u>Post-Update, Printer Stands Silent No More</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win10-printer-setup-guide-hp-connection-fixes/"><u>Win10 Printer Setup Guide - HP Connection Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-windows-11-8-7-and-mf4770n-for-efficiency/"><u>Harmonizing Windows 11, 8, 7 & MF4770n for Efficiency</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fast-and-simple-printer-back-online-now/"><u>Fast & Simple: Printer Back Online Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-hiccup-discovered/"><u>Unexpected Print Hiccup Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-errors/"><u>Troubleshooting HP Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivation-of-online-scan-achieved-on-win11/"><u>Reactivation of Online Scan Achieved on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-inaccessible-printer-connection/"><u>Mended Inaccessible Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/procedure-connecting-hp-officejet-to-windows-device/"><u>Procedure: Connecting HP Officejet to Windows Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-issue-canon-pixma-mp620-and-win10-not-linked/"><u>[Compatibility Issue] Canon Pixma MP620 & WIN10 Not Linked</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-outputs-ceased-on-epson-model/"><u>Halted Outputs Ceased on Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstating-scan-functionality-in-windows-11/"><u>Reinstating Scan Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-scanner-on-windows-11/"><u>Fixing Non-Operational Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/activating-scanner-on-latest-win11-release/"><u>Activating Scanner on Latest Win11 Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-interruptions-on-win7win10/"><u>Avoiding Constant Printer Service Interruptions on Win7/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-failure-alert-domain-service-down/"><u>Print Failure Alert: Domain Service Down</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-boosting-online-presence-top-30-freefire-hashtags-and-tag-strategies/"><u>2024 Approved  Boosting Online Presence  Top 30 FreeFire Hashtags and Tag Strategies</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-free-and-high-quality-voice-alteration-demystified-a-step-by-step-video-voice-editors-handbook-using-filmora/"><u>Updated 2024 Approved Free and High-Quality Voice Alteration Demystified A Step-by-Step Video Voice Editors Handbook Using Filmora</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715860511469-leveraging-huaweis-inbuilt-screen-capture-tech-on-its-phones-for-2024/"><u>Leveraging Huawei's Inbuilt Screen Capture Tech on Its Phones. For 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-y17s-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-s18-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo S18</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gopros-best-underwater-enhancement-filters/"><u>2024 Approved  GoPro's Best Underwater Enhancement Filters</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-discover-chilling-acoustic-phenomena-for-2024/"><u>New Discover Chilling Acoustic Phenomena for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>How to Change/Add Location Filters on Snapchat For your Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/apeaksoft-2023-screens-recording-insights/"><u>Apeaksoft 2023 Screens Recording Insights</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-reclaiming-windows-photo-viewer-in-windows-10-methods-demystified/"><u>[Updated] Reclaiming Windows Photo Viewer in Windows 10 - Methods Demystified</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-minimum-view-count-for-youtube-success-stories/"><u>[Updated] The Minimum View Count for YouTube Success Stories</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-capture-your-screen-a-beginners-guide-to-recording-with-filmora-scrn/"><u>Updated 2024 Approved Capture Your Screen A Beginners Guide to Recording with Filmora Scrn</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/from-ordinary-to-extraordinary-transform-your-facebook-profile-with-these-tips-for-2024/"><u>From Ordinary to Extraordinary  Transform Your Facebook Profile with These Tips for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-from-voice-to-verse-a-novices-guide-to-creating-a-polished-podcast-masterpiece/"><u>In 2024, From Voice to Verse A Novices Guide to Creating a Polished Podcast Masterpiece</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-box-it-up-right-10-online-haunts-for-tailored-gift-boxes/"><u>2024 Approved  Box It Up Right  10 Online Haunts for Tailored Gift Boxes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unlimited-savvy-instagrams-infinite-save-tool-for-2024/"><u>Unlimited Savvy  Instagram's Infinite Save Tool for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-how-to-record-gameplay-on-xbox-one/"><u>In 2024, How to Record Gameplay on Xbox One</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/detailed-overview-of-the-wave-editor-key-functions-ratings-and-step-by-step-guides-for-2024/"><u>Detailed Overview of the Wave Editor Key Functions, Ratings, and Step-by-Step Guides for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-breaking-the-mold-revolutionary-methods-to-boost-your-fb-page-rank/"><u>[New] In 2024, Breaking the Mold  Revolutionary Methods to Boost Your FB Page Rank</u></a></li>
<li><a href="https://unlock-android.techidaily.com/5-solutions-for-infinix-zero-30-5g-unlock-without-password-by-drfone-android/"><u>5 Solutions For Infinix Zero 30 5G Unlock Without Password</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-image-all-screen-website-view-for-2024/"><u>[New] Image All-Screen Website View for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-audio-alteration-the-ultimate-guide/"><u>[New] Instagram's Audio Alteration  The Ultimate Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-diving-into-digital-delights-facebook-video-repository/"><u>[Updated] Diving Into Digital Delights  Facebook Video Repository</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-visual-magic-grading-through-hue-manipulation/"><u>[New] In 2024, Visual Magic  Grading Through Hue Manipulation</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-free-vimeo-tutorial-to-craft-engaging-videos/"><u>In 2024, Free Vimeo Tutorial to Craft Engaging Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/unlocking-old-tweets-with-twitter-archive-tools/"><u>Unlocking Old Tweets with Twitter Archive Tools</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mov-movies-on-moto-g-stylus-5g-2023-is-it-possible-by-aiseesoft-video-converter-play-mov-on-android/"><u>Play MOV movies on Moto G Stylus 5G (2023), is it possible?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/masterclass-in-glamour-beauty-tutorials-for-all-for-2024/"><u>Masterclass in Glamour  Beauty Tutorials for All for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
</ul></div>
