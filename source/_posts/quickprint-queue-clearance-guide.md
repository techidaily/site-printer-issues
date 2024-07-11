---
title: Quickprint Queue Clearance Guide
date: 2024-07-10T17:03:17.234Z
updated: 2024-07-11T17:03:17.234Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quickprint Queue Clearance Guide
excerpt: This Article Describes Quickprint Queue Clearance Guide
keywords: Quick Print Services,Queue Management Strategies,Fast Printer Clearance Tips,Effective Print Operations,Reducing Wait Times at Print Stations,Streamlining Printer Queue Management,Enhancing Office Efficiency with Quickprint Solutions
thumbnail: https://thmb.techidaily.com/ce2b50426ded5a960fb87586d9bc144c1e1a55defefae42789a30b646b9173fc.jpeg
---

## Quickprint Queue Clearance Guide

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
<li><a href="https://printer-issues.techidaily.com/solved-no-print-after-win7-device-suspend/"><u>[Solved] No Print After Win7 Device Suspend</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combating-printers-error-x97-in-epson/"><u>Combating Printer's Error X97 in Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-windows-printer-setup-successfully-fixed/"><u>Error 0X00000709: Windows Printer Setup Successfully Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/supercharge-dells-v305-inkjets-with-new-windows-driver/"><u>Supercharge Dell's V305 Inkjets with New Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-release-from-print-lineup/"><u>Speedy Release From Print Lineup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-service-recovered-on-windows-7-desktop/"><u>Print Service Recovered on Windows 7 Desktop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-release-of-stuck-prints/"><u>Rapid Release of Stuck Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlock-hidden-printer-features-in-win10-systems/"><u>Unlock Hidden Printer Features in WIN10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tips-for-swift-printers/"><u>Quick Tips for Swift Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-resolve-print-spooler-shutdown-woes-win-10-11-and-7/"><u>Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-hp-deskjet-d1360-printer-drivers-wont-install-in-windows-7-8-8110/"><u>[Resolved] HP Deskjet D1360 Printer Drivers Won’t Install in Windows 7, 8, 8.1,10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-drivers-conflict-on-hp-printer-model-67wdn/"><u>Fixed Drivers' Conflict on HP Printer Model 67Wdn</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-ink-dry-up-a-printers-cry-for-help/"><u>Overcoming Ink Dry-Up: A Printer's Cry for Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-spooling-failure-in-windows-10/"><u>Printer Spooling Failure in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quicken-your-print-jobs-easily/"><u>Quicken Your Print Jobs Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stay-current-with-the-latest-driver-release-for-hp-4630/"><u>Stay Current with the Latest Driver Release for HP 4630</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-installing-model-8720-printer-on-your-computer/"><u>Tutorial: Installing Model 8720 Printer on Your Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-printer-woes-with-windows-10-update-fix/"><u>Triumph Over Printer Woes with Windows 10 Update Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/laptop-meets-printing-unlocking-potential-with-3-fixes-for-hp/"><u>Laptop Meets Printing: Unlocking Potential with 3 Fixes for HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-siblings-printer-remains-unreachable/"><u>Fixing: Sibling's Printer Remains Unreachable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-to-hp-inkjet-non-operational-on-win11/"><u>Solution to HP Inkjet Non-Operational on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-the-gap-reactivate-and-recover-from-printer-disconnect/"><u>Bridge the Gap: Reactivate and Recover From Printer Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330cdw-fan-bro-free-drive-setup/"><u>MFC-9330CDW Fan Bro: Free Drive Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-communications-unavailable/"><u>Print Issue: Communications Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-of-missing-pages-with-new-tech-update/"><u>End of Missing Pages with New Tech Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-hp-printer-driver-is-unavailable-on-windows-1110/"><u>[Solved] HP Printer Driver Is Unavailable on Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unjamming-print-heads-a-practical-approach/"><u>Unjamming Print Heads: A Practical Approach</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-xp-vs-mp620-printer-compatibility-questions/"><u>Windows XP vs MP620 Printer Compatibility Questions?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-wireless-printer-with-hp-color-life-series/"><u>How To: Set Up a Wireless Printer with HP Color Life Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-needed-mp620-printer-not-detected-in-windows-os/"><u>[Solution Needed] MP620 Printer Not Detected in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-remove-print-spooler-service/"><u>How To Remove Print Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-forget-a-connected-printer-in-win-1011/"><u>Strategies to Forget a Connected Printer in Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-error-driver-not-located-by-win/"><u>Printer Error: Driver Not Located by Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-compatible-driver-release/"><u>Officejet Pro 8600 Windows Compatible Driver Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-constant-spooler-crashes-a-guide-for-windows-users/"><u>Preventing Constant Spooler Crashes: A Guide for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-printer-error-after-windows-11-update/"><u>Repaired: Printer Error After Windows 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-glitch-detected/"><u>Unexpected Print Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-installation-stalled-on-pc/"><u>Printer Installation Stalled on PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-cutting-edge-watermarking-tips-to-ensure-photo-security-on-instagram/"><u>[New] Cutting-Edge Watermarking  Tips to Ensure Photo Security on Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-auto-tracking-cameras/"><u>[New] Best Auto Tracking Cameras</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713949114752-discover-the-best-video-frame-rate-converters-for-smooth-playback-including-online-and-offline-options-learn-how-to-convert-frame-rates-for-free-and-elevate/"><u>Discover the Best Video Frame Rate Converters for Smooth Playback, Including Online and Offline Options. Learn How to Convert Frame Rates for Free and Elevate Your Video Quality with These Top 8 Tools for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unfolding-the-story-of-tiktoks-famous-figures-worldwide/"><u>[Updated] Unfolding the Story of TikTok's Famous Figures Worldwide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-mastering-aspect-ratio-in-final-cut-pro-essential-skills-for-video-editors/"><u>2024 Approved Mastering Aspect Ratio in Final Cut Pro Essential Skills for Video Editors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-8-3d-gold-text-effect-websites/"><u>2024 Approved  Best 8 3D Gold Text Effect Websites</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-unleashing-creativity-using-voice-changer-plus-for-iphone-speech-alteration/"><u>New Unleashing Creativity Using Voice Changer Plus for iPhone Speech Alteration</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-understanding-and-resolving-the-issue-of-missing-shorts-thumbnails/"><u>2024 Approved  Understanding & Resolving the Issue of Missing Shorts Thumbnails</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-maximize-your-cam-flagship-gear-with-ease/"><u>In 2024, Maximize Your Cam Flagship Gear with Ease</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-updated-user-manual-for-navigating-facebook/"><u>In 2024, The Updated User Manual for Navigating Facebook</u></a></li>
<li><a href="https://audio-editing.techidaily.com/8-favorite-high-quality-audio-recorders-for-online-sharing/"><u>8 Favorite High-Quality Audio Recorders for Online Sharing</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-streamlining-sound-integration-a-fast-fix-manual-for-premiere-pro/"><u>New 2024 Approved Streamlining Sound Integration A Fast Fix Manual for Premiere Pro</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-get-your-game-on-top-10plus-sites-to-download-games-for-free-for-2024/"><u>New Get Your Game On Top 10+ Sites to Download Games for Free for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-screen-capture-mastery-windows-edition-free-3-methods/"><u>[New] In 2024, Screen Capture Mastery  Windows Edition (Free, 3 Methods)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-utilizing-smartphones-for-effective-home-based-filming/"><u>[New] Utilizing Smartphones for Effective Home-Based Filming</u></a></li>
<li><a href="https://extra-information.techidaily.com/key-principles-to-write-captivating-vlog-dialogues/"><u>Key Principles to Write Captivating Vlog Dialogues</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-honor-x9a-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Honor X9a Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-earning-through-youtube-navigating-revenue-without-ads/"><u>[Updated] Earning Through YouTube  Navigating Revenue Without Ads</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-navigating-the-art-of-live-stream-archiving-for-tv-series/"><u>[Updated] Navigating the Art of Live Stream Archiving for TV Series</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-optimizing-speed-on-vimeo-content/"><u>[Updated] Optimizing Speed on Vimeo Content</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/exploring-options-a-treasure-hunt-for-your-tiktok-symbol/"><u>Exploring Options  A Treasure Hunt for Your TikTok Symbol</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-bystander-to-leader-in-the-world-of-insta-essential-tips-and-examples/"><u>[Updated] From Bystander to Leader in the World of Insta  Essential Tips & Examples</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-essential-tips-for-youtube-audio-library-you-wont-miss-for-2024/"><u>New Essential Tips for YouTube Audio Library You Wont Miss for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-y78plus-t1-edition-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-get-noticed-20-stunning-adobe-premiere-intro-templates-free-to-download-for-2024/"><u>New Get Noticed 20 Stunning Adobe Premiere Intro Templates Free to Download for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-honor-magic5-ultimate-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Honor Magic5 Ultimate to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-videos-from-iphone-11-pro-max-without-backup-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Videos from iPhone 11 Pro Max Without Backup? | Stellar</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-tailor-your-tweets-exceptional-video-to-twitch-tools/"><u>2024 Approved  Tailor Your Tweets  Exceptional Video to Twitch Tools</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-a-comprehensive-look-at-youtube-shorts-template-design/"><u>[New] 2024 Approved  A Comprehensive Look at YouTube Shorts Template Design</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-net-adapter-fb-stories-saver-app/"><u>[New] 2024 Approved  Net Adapter  FB Stories Saver App</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
</ul></div>
