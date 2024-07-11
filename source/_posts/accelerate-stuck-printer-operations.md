---
title: Accelerate Stuck Printer Operations
date: 2024-07-10T17:28:40.419Z
updated: 2024-07-11T17:28:40.419Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Stuck Printer Operations
excerpt: This Article Describes Accelerate Stuck Printer Operations
keywords: Accelerating Printer Issues,Resolve Stuck Print Head,Fix Jammed Toner Cartridge,Speeding Up Slow Printers,Overcoming Printer Freezes,Improving Print Speed,Troubleshooting HP Printer Problems
thumbnail: https://thmb.techidaily.com/2a9cc8bf4d555df620abafcb570dcc2752e8e2040a84b647ff438519a4be3866.jpg
---

## Accelerate Stuck Printer Operations

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
<li><a href="https://printer-issues.techidaily.com/advanced-techniques-to-setup-hp-print-devices-in-win10-os/"><u>Advanced Techniques to Setup HP Print Devices in Win10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quicken-your-print-jobs-easily/"><u>Quicken Your Print Jobs Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-offline-printer-back-online/"><u>Win7 Offline Printer Back Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-missing-pages-issue-with-new-printer-update/"><u>End Missing Pages Issue with New Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-windows-710-to-online-hp-printer/"><u>Reconnect Windows 7/10 to Online HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/saving-photo-printouts-from-failures/"><u>Saving Photo Printouts From Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-malfunction-mystery/"><u>Unraveling Printer Malfunction Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-for-windows-print-system/"><u>Driver Search Failed for Windows Print System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-linked-in-seconds/"><u>Printer Linked in Seconds</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-not-acknowledging-calls/"><u>Canon Printer Not Acknowledging Calls</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-problems-in-adding-printer/"><u>No Problems in Adding Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fixing-silent-hp-toner-units/"><u>Guide to Fixing Silent HP Toner Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-efficiency-install-dell-printer-driver-update-in-win7/"><u>Boost Efficiency: Install Dell Printer Driver Update in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-networked-printer-issues/"><u>Navigating Through Networked Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/colors-not-filling-in-prints/"><u>Colors Not Filling In Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-paper-jams-in-copiers/"><u>Preventing Paper Jams in Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-white-paper-trap-how-to-prevent-it/"><u>Epson's White Paper Trap: How to Prevent It?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-communication-not-available-issue/"><u>[Solved] Printer Communication Not Available Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-wi-fi-directly-for-canon-printers/"><u>Enabling Wi-Fi Directly for Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fresh-output-updated-driver-v305-and-windows-windows-7/"><u>Fresh Output, Updated Driver: V305 and Windows WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-print-issues-with-comprehensive-windows-hp-guide/"><u>Conquer Print Issues with Comprehensive Windows HP Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-top-5-methods-to-resolve-canon-printer-print-issue-in-windows-11/"><u>Quick Fixes: Top 5 Methods to Resolve Canon Printer Print Issue in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/default-printer-dilemma-windows-error-0x00000709-squashed/"><u>Default Printer Dilemma: Windows Error (0X00000709) Squashed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-your-non-printing-brother-printer-in-win1011/"><u>Reviving Your Non-Printing Brother Printer in Win10/11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-top-5-twitch-broadcasting-techniques/"><u>[New] 2024 Approved  Top 5 Twitch Broadcasting Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-often-should-you-upload-videos-to-youtube-to-get-more-views/"><u>[Updated] How Often Should You Upload Videos to YouTube to Get More Views</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-realme-12plus-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Realme 12+ 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-video-editor-battle-is-inshot-reigning-supreme/"><u>In 2024, Top Video Editor Battle  Is InShot Reigning Supreme?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-seamless-storytelling-top-10-premiere-pro-transition-effects-for-2024/"><u>New Seamless Storytelling Top 10 Premiere Pro Transition Effects for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-android-and-ios-guide-capturing-google-meet-sessions/"><u>[Updated] In 2024, Android & iOS Guide  Capturing Google Meet Sessions</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-blueprints-of-bliss-building-a-virtual-mc-village-home/"><u>[Updated] Blueprints of Bliss  Building a Virtual MC Village Home</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-simplified-strategies-for-novice-level-nft-crafting/"><u>[New] Simplified Strategies for Novice-Level NFT Crafting</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-elevate-your-social-presence-proven-methods-for-fb-fan-expansion-for-2024/"><u>[New] Elevate Your Social Presence  Proven Methods for FB Fan Expansion for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-from-basic-to-bespoke-personalizing-your-tiktok-profile/"><u>[New] 2024 Approved  From Basic to Bespoke  Personalizing Your TikTok Profile</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-vivo-y27s-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Vivo Y27s to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/understanding-tiktoks-profile-picture-language-pfp-for-2024/"><u>Understanding TikTok's Profile Picture Language (PFP) for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-pro-level-tips-for-expert-vimeo-recording-for-2024/"><u>[New] Pro-Level Tips for Expert Vimeo Recording for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-12-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server On iPhone 12</u></a></li>
<li><a href="https://extra-resources.techidaily.com/innovative-shooting-modes-smart-hdr-3-and-4-explained-simply/"><u>Innovative Shooting Modes  Smart HDR 3 & 4 Explained Simply</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-cutting-edge-editing-40-final-cut-pro-x-keyboard-shortcuts-you-need/"><u>New 2024 Approved Cutting-Edge Editing 40 Final Cut Pro X Keyboard Shortcuts You Need</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-14-pro-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 14 Pro iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-live-with-clarity-secrets-for-high-quality-fb-recordings/"><u>[New] In 2024, Live with Clarity  Secrets for High-Quality FB Recordings</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/insight-into-tseries-earnings-and-profitability-through-youtube-channels/"><u>Insight Into TSeries' Earnings and Profitability Through YouTube Channels</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/audio-tranquility-in-action-fading-and-pulsating-sounds-made-easy-in-adobe-after-effects-for-2024/"><u>Audio Tranquility in Action Fading and Pulsating Sounds Made Easy in Adobe After Effects for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-step-by-step-guide-to-snapchats-captivating-boomers-for-2024/"><u>[New] Step-By-Step Guide to Snapchat's Captivating Boomers for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-engaging-instagram-reels-step-by-step/"><u>[New] Crafting Engaging Instagram Reels Step-by-Step</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unlocked-skies-cheapest-drones-that-dont-break-the-bank/"><u>[New] Unlocked Skies  Cheapest Drones that Don't Break the Bank</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-shadow-copy-procedures/"><u>Addressing Failed Shadow Copy Procedures</u></a></li>
<li><a href="https://some-tips.techidaily.com/tutorial-turning-on-hdr-for-windows-11-users-for-2024/"><u>Tutorial  Turning on HDR for Windows 11 Users for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-a59-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Oppo A59 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
</ul></div>
