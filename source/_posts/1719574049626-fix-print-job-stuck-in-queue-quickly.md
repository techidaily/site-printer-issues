---
title: Fix 'Print Job Stuck in Queue' Quickly
date: 2024-07-10T17:19:18.755Z
updated: 2024-07-11T17:19:18.755Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fix 'Print Job Stuck in Queue' Quickly
excerpt: This Article Describes Fix 'Print Job Stuck in Queue' Quickly
keywords: Resolve Printer Queue Error,Quick Fix for Print Job Delay,Print Job Stuck Solution,Fix Printer Queue Blockage,Unblock Print Job Instantly,Quickprint Troubleshooting Tips,Efficient Printer Queue Management,Print Job Stuck,Queue Issue Resolution,Print Queue Troubleshooting,Fix Print Job Hangup,Printing Queue Stall Fix,Quickly Resolve Print Job Queue,Cancel Stuck Print Job
thumbnail: https://thmb.techidaily.com/750c1d86ce393517a7e8e0f28b8261fcac89b61944729e317e412d6180bd4eb2.jpg
---

## Fix 'Print Job Stuck in Queue' Quickly

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
<li><a href="https://printer-issues.techidaily.com/printerranker-setting-snafu-alert/"><u>Printer'ranker: Setting Snafu Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-no-9008e/"><u>Resolved: Printer Error No. 9008E</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-prints-new-dell-v305-windows-enhancements/"><u>Streamline Prints: New Dell V305 WIndows Enhancements</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-non-printing-on-canon-uncover-5-easy-methods-for-windows-11-enthusiasts/"><u>Conquer Non-Printing on Canon - Uncover 5 Easy Methods for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-usage-fluctuation-raises-eyebrows/"><u>Printer Usage Fluctuation Raises Eyebrows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printers-from-windows-system/"><u>Eradicating Printers From Windows System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/identified-non-printer-owners-computer-mischief/"><u>Identified Non-Printer Owner's Computer Mischief</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-lan-configuration-for-w11-printers/"><u>Resolve LAN Configuration for W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fast-track-prints-in-queue/"><u>Fast-Track Prints in Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-for-windows-print-system/"><u>Driver Search Failed for Windows Print System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inaccessible-domains-causing-print-errors/"><u>Inaccessible Domains Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-10-upgrade-print-says-no/"><u>Win 10 Upgrade - Print Says No</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-solutions-to-overcome-pcl-xl-errors/"><u>Speedy Solutions to Overcome PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-loss-of-printers-internet-connection/"><u>Troubleshooting: Loss of Printer's Internet Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-cannot-retrieve-printer-drivers/"><u>Windows Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-clearance-of-stalled-print-queue/"><u>Speedy Clearance of Stalled Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-and-connecting-printer-error-resolved/"><u>Installing and Connecting Printer Error Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-mf4770n-performance-in-windows-108/"><u>Enhancing MF4770n Performance in WIndows 10/8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-network-issue-resolved-in-win7-pro/"><u>Printer Network Issue Resolved in Win7 Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quickprint-queue-clearance-guide/"><u>Quickprint Queue Clearance Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-saturation-dropped-in-prints/"><u>Color Saturation Dropped in Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-canon-printers-print-function-with-these-5-windows-11-tricks/"><u>Revive Your Canon Printer's Print Function with These 5 Windows 11 Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-and-painless-connecting-canon-to-wi-fi-network/"><u>Quick and Painless: Connecting Canon to Wi-Fi Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-rectified/"><u>Code B200 Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-printers-purpose-beyond-empty-pages/"><u>Reviving a Printer's Purpose Beyond Empty Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-scanner-activation-on-windows-10-system/"><u>Resetting Scanner Activation on Windows 10 System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bring-to-life-enable-your-silent-canon-print-spooler/"><u>Bring To Life: Enable Your Silent Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-intermittent-printer-spooler-halt-in-win-117/"><u>Resolving Intermittent Printer Spooler Halt in Win 11/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-d1360-printer-drivers-not-working-on-windows-7-10/"><u>[Fix] D1360 Printer Drivers Not Working on Windows 7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-crisis-averted-zeroing-out-error-0x00000709/"><u>Printer Setup Crisis Averted - Zeroing Out Error (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574110556-printing-woes-config-error-help-needed/"><u>Printing Woes: Config Error, Help Needed!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-responsive-printer-in-windows-nt-environment/"><u>Revive Non-Responsive Printer in Windows NT Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-errors-windows-10-solutions/"><u>Overcome Print Errors: Windows 10 Solutions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-music-library-app-android-focused/"><u>[Updated] Iconic Music Library App, Android-Focused</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-the-secrets-of-successful-youtube-collaborations/"><u>2024 Approved  Unlocking the Secrets of Successful YouTube Collaborations</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-oppo-reno-10-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Oppo Reno 10 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-honor-magic-6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-3ds-love-selective-sensitive-android-gaming-solutions/"><u>[Updated] In 2024, 3DS Love  Selective, Sensitive Android Gaming Solutions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/cutting-edge-pfp-trends-enhancing-your-tiktok-impact/"><u>Cutting-Edge PFP Trends Enhancing Your TikTok Impact</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-leading-tips-seamless-youtube-to-mpeg-conversion-guide/"><u>[New] Leading Tips  Seamless YouTube-to-MPEG Conversion Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://techidaily.com/xiaomi-civi-3-disney-100th-anniversary-edition-video-recovery-recover-deleted-videos-from-xiaomi-civi-3-disney-100th-anniversary-edition-by-fonelab-android-recover-video/"><u>Xiaomi Civi 3 Disney 100th Anniversary Edition Video Recovery - Recover Deleted Videos from Xiaomi Civi 3 Disney 100th Anniversary Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-normal-screen-orientation-for-windows-10/"><u>Restore Normal Screen Orientation for Windows 10</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-control-over-your-spotify-default-podcast-recommendations/"><u>2024 Approved  Control Over Your Spotify Default Podcast Recommendations</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-oppo-find-x6-pro-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Oppo Find X6 Pro? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-audiovisual-fusion-incorporating-songs-in-ig-media/"><u>[New] 2024 Approved  Audiovisual Fusion  Incorporating Songs in IG Media</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-essential-tiktok-gamers-you-cant-miss/"><u>[Updated] In 2024, Essential TikTok Gamers You Can't Miss</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-step-by-step-guide-to-adding-descriptive-text-in-tiktok-videos/"><u>In 2024, Step-by-Step Guide to Adding Descriptive Text in TikTok Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-top-ogg-conversion-software-our-key-takeaways/"><u>2024 Approved Top OGG Conversion Software Our Key Takeaways</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-sweeping-visual-upgrades-with-instagrams-chroma-key-tooling/"><u>[New] Sweeping Visual Upgrades with Instagram’s Chroma Key Tooling</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-youtube-live-the-comprehensive-playbook/"><u>In 2024, Mastering YouTube Live  The Comprehensive Playbook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-blurring-backgrounds-a-visual-hideaway-guide/"><u>In 2024, Blurring Backgrounds  A Visual Hideaway Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/a-critical-look-at-the-leading-economically-friendly-lut-sources/"><u>A Critical Look at the Leading, Economically Friendly LUT Sources</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-methods-to-rectify-obs-fullscreen-crash-for-2024/"><u>[Updated] Methods to Rectify OBS Fullscreen Crash for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-how-to-clone-yourself-on-tiktok-a-simple-guide/"><u>[Updated] In 2024, How to Clone Yourself on TikTok - a Simple Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-unraveling-the-mysteries-of-instagrams-video-timeframe/"><u>[Updated] In 2024, Unraveling the Mysteries of Instagram's Video Timeframe</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-vr-movies-for-immersive-viewing-for-2024/"><u>Premier VR Movies for Immersive Viewing for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-5-speedy-shot-strategies-right-from-your-living-room/"><u>Ultimate 5 Speedy Shot Strategies Right From Your Living Room</u></a></li>
<li><a href="https://facebook.techidaily.com/beware-the-copycat-con-artists-on-facebook/"><u>Beware the Copycat Con Artists on Facebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fine-tuning-virtual-presence-in-ms-teams/"><u>[New] Fine-Tuning Virtual Presence in MS Teams</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-top-5-secure-methods-to-maximize-instagram-earnings/"><u>[Updated] Top 5 Secure Methods to Maximize Instagram Earnings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/ultimate-highlight-hits-ios-and-android-instagram-covers-apps-for-2024/"><u>Ultimate Highlight Hits  IOS & Android Instagram Covers Apps for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unveiling-the-top-ten-youtube-music-reaction-stars/"><u>In 2024, Unveiling the Top Ten YouTube Music Reaction Stars</u></a></li>
<li><a href="https://screen-recording.techidaily.com/x-sonic-recorder-desktop-format/"><u>X-Sonic Recorder  Desktop Format</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo Reno 11F 5G | Dr.fone</u></a></li>
</ul></div>
