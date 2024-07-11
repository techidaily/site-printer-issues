---
title: Immediate Action on Queued Printer Work
date: 2024-07-10T16:52:09.132Z
updated: 2024-07-11T16:52:09.132Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Action on Queued Printer Work
excerpt: This Article Describes Immediate Action on Queued Printer Work
keywords: Immediate Print Job Cancellation,Printer Queue Management Tips,Fixing Stuck Printer Workflows,Quick Solution for Queued Print Jobs,Resolve Printer Queue Delays,Immediate Action,Prevent Long Queue Print Jobs
thumbnail: https://thmb.techidaily.com/b5e9ddde4e68e5c468b12c2fce264f22eb978dc955e335250b1f4d060c7be8f8.jpg
---

## Immediate Action on Queued Printer Work

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
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-unable-to-locate-hp-winxo/"><u>[Driver Search Failed] - Unable to Locate HP WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-address-sibling-printer-unresponsiveness/"><u>Strategies to Address Sibling Printer Unresponsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win10-printer-setup-guide-hp-connection-fixes/"><u>Win10 Printer Setup Guide - HP Connection Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-halting-repeated-print-job-errors-windows/"><u>Quick Guide: Halting Repeated Print Job Errors (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-installing-hp-envy-504-printers/"><u>Step-by-Step Guide to Installing HP Envy 504 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-blank-page-problem-solved/"><u>HP Printer Blank Page Problem Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tutorial-setting-up-your-canon-printing-device/"><u>Quick Tutorial: Setting Up Your Canon Printing Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cdw-duo-fan-guide-for-brother-9330c/"><u>CDW Duo Fan Guide for Brother 9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-hp-photosmart-205n-printer-functions/"><u>Repaired HP Photosmart 205N Printer Functions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-successfully/"><u>Printer Setup Completed Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-blank-page-woes-printer-remedy-discovered/"><u>The End of Blank Page Woes: Printer Remedy Discovered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-not-responding-post-wake-from-sleep-w7/"><u>Printers Not Responding Post Wake From Sleep, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-b200/"><u>Error Resolution: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-compatibility-unable-to-connect-to-hp-print-service-on-windows/"><u>[OS Compatibility] - Unable to Connect to HP Print Service on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-now-functioning/"><u>HP Printer Offline, Now Functioning</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-epson-printer-to-normalcy/"><u>Restored Epson Printer to Normalcy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-guide-to-smoothly-linking-canon-printers/"><u>A Guide to Smoothly Linking Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-inkjet-printer/"><u>Successfully Installed Inkjet Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ended-canons-code-b200-misstep/"><u>Ended Canon's Code B200 Misstep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocked-scanner-operation-in-windows-11-os/"><u>Unblocked Scanner Operation in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-canon-printer-setup-instructions/"><u>Easy Canon Printer Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-detected-unable-to-connect-pixma-mp620-to-win10/"><u>[Driver Not Detected] Unable to Connect Pixma MP620 to WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-11-printing-glitches/"><u>Troubleshoot Windows 11 Printing Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-restored-communication-link/"><u>[PRINT] Restored Communication Link</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivation-of-online-scan-achieved-on-win11/"><u>Reactivation of Online Scan Achieved on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-ultimate-guide-to-installing-and-configuring-hp-printers/"><u>The Ultimate Guide to Installing and Configuring HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-print-queue-issue-on-win7-pc/"><u>Fixed Print Queue Issue on Win7 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-online-status-of-windowshp-multi-function/"><u>Reactivating Online Status of Windows/HP Multi-Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-wireless-mfc-9330cdw-instructions/"><u>Brother Wireless MFC-9330CDW Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-efficiency-quickly/"><u>Enhance Printer Efficiency Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-reconnecting-overcoming-offline-print-spooler/"><u>Guide to Reconnecting: Overcoming Offline Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-laser-print-troubleshooting/"><u>Tackling Laser Print Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-disconnected-scanner-issue-in-windows-10/"><u>Resolving Disconnected Scanner Issue in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-page-gaps-the-2024-printer-fix/"><u>End Page Gaps: The 2024 Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-printer-driver-setup-for-hp-deskjet-d1360-on-pcs/"><u>Trouble with Printer Driver Setup for HP Deskjet D1360 on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-your-v305-printing-fresh-with-windows-updates/"><u>Keep Your V305 Printing Fresh with WIndows Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-woes-here-are-your-five-easy-fixes-in-windows-11/"><u>Canon Printer Woes? Here Are Your Five Easy Fixes in Windows 11!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-error-after-wake-from-sleep-in-windows-7/"><u>[Resolved] Printer Error After Wake From Sleep in Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-connection-between-printer-and-wifi/"><u>Re-Establishing Connection Between Printer & WiFi</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastery-in-making-the-perfect-match-of-drones-and-propellers/"><u>In 2024, Mastery in Making the Perfect Match of Drones and Propellers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-stream-like-a-pro-top-5-cams-revolutionizing-live-broadcasts-on-twitch/"><u>[New] Stream Like a Pro  Top 5 Cams Revolutionizing Live Broadcasts on Twitch</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-exploring-the-ultimate-selection-of-gratis-vst-enhancers-updated/"><u>New Exploring the Ultimate Selection of Gratis VST Enhancers, Updated</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-ten-webm-to-mp3-converters-for-2024/"><u>New Top Ten WebM to MP3 Converters for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-motorola-defy-2-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Motorola Defy 2 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-lenovo-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Lenovo? Try These Fixes</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/carryminati-unmasked-the-monetary-milestones-for-2024/"><u>CarryMinati Unmasked  The Monetary Milestones for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transforming-augmented-reality-with-downloaded-free-luts-for-development/"><u>[New] Transforming Augmented Reality with Downloaded, Free LUTs for Development</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-vlc-key-mac-functions-explained/"><u>[New] Mastering VLC  Key Mac Functions Explained</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-safe-methods-to-fast-forward-in-spotify-files/"><u>[New] Safe Methods to Fast-Forward in Spotify Files</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Infinix Smart 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-a-beginners-guide-to-ios-screen-recording-for-2024/"><u>[Updated] A Beginner's Guide to iOS Screen Recording for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-make-creative-animation-videos/"><u>In 2024, Make Creative Animation Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagrams-mirage-identifying-false-friends-at-no-price/"><u>2024 Approved  Instagram's Mirage  Identifying False Friends at No Price</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-slow-down-time-a-beginners-guide-to-making-slow-motion-videos-on-kapwing/"><u>Updated In 2024, Slow Down Time A Beginners Guide to Making Slow-Motion Videos on Kapwing</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-best-of-the-best-top-10-online-waveform-generators-for-audio-enthusiasts/"><u>New The Best of the Best Top 10 Online Waveform Generators for Audio Enthusiasts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-realme-11x-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Realme 11X 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/content-creation-on-facebook-aspect-ratio-choice-for-2024/"><u>Content Creation on Facebook  Aspect Ratio Choice for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-cyberlink-vs-alternatives-the-ultimate-recording-showdown/"><u>[Updated] In 2024, Cyberlink Vs. Alternatives  The Ultimate Recording Showdown</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-video-posting-pathway-for-twitter-and-tumblr-users/"><u>[New] Video Posting Pathway for Twitter & Tumblr Users</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/become-a-bilingual-in-minutes-enjoy-unbelievable-discounts/"><u>Become a Bilingual in Minutes: Enjoy Unbelievable Discounts!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-oppo-find-x6-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Oppo Find X6 Phone? Unlock It Now</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-universal-strategies-for-screen-capturing-on-diverse-devices/"><u>[Updated] In 2024, Universal Strategies for Screen Capturing on Diverse Devices</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-11-audio-capture-devices-for-live-broadcasts-for-2024/"><u>[Updated] Top 11 Audio Capture Devices for Live Broadcasts for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-beginners-to-pros-choosing-webcams-for-youtube-live/"><u>In 2024, From Beginners to Pros  Choosing Webcams for YouTube Live</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo Y27 4G? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-poco-m6-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-crafting-compelling-compositions-with-magix-fruity-loops/"><u>2024 Approved  Crafting Compelling Compositions with Magix Fruity Loops</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-inside-camstudios-updated-screen-recorder-techniques-for-2024/"><u>[New] Inside CamStudio's Updated Screen Recorder Techniques for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Detect and Remove Spyware on Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/inside-the-top-10-virtual-reality-smartphone-gaming/"><u>Inside the Top 10 Virtual Reality Smartphone Gaming</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/sending-streaming-content-linking-fb-vids-and-whatsapp-messages/"><u>Sending Streaming Content  Linking FB Vids & WhatsApp Messages</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-cross-network-laughter-whos-tops-today/"><u>In 2024, Cross-Network Laughter  Who's Tops Today?</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-infinix-hot-30-5g-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Infinix Hot 30 5G and Browser | Dr.fone</u></a></li>
</ul></div>
