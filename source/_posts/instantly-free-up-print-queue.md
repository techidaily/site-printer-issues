---
title: Instantly Free Up Print Queue
date: 2024-07-10T16:57:24.517Z
updated: 2024-07-11T16:57:24.517Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantly Free Up Print Queue
excerpt: This Article Describes Instantly Free Up Print Queue
keywords: Print Job Cancellation,Printer Queue Management,Free Up Print Queue Instantly,Cancel Printer Jobs on Windows,How to Clear Print Queue Fast,Printer Spooler Troubleshooting,Print System Error Free Up
thumbnail: https://thmb.techidaily.com/450ec1b84e72a24dc748a4aee1ff3d014e9229d42ab5bd65b8cf7e7b256ed53c.jpg
---

## Instantly Free Up Print Queue

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
<li><a href="https://printer-issues.techidaily.com/the-end-of-the-road-for-printer-errors-with-windows-update/"><u>The End of the Road for Printer Errors with Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/full-colors-unavailable-on-printout/"><u>Full Colors Unavailable on Printout</u></a></li>
<li><a href="https://printer-issues.techidaily.com/realign-printer-settings-in-win10-environment/"><u>Realign Printer Settings in Win10 Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-hp-printer-error-0xoxc4eb827f/"><u>Tackling HP Printer Error 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drive-upgrade-streamline-mf4770n-in-windows/"><u>Drive Upgrade: Streamline MF4770n in WIndows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-instant-ink-into-your-networked-devices/"><u>Integrating HP Instant Ink Into Your Networked Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-scanner-windows-10-troubleshooting-tips/"><u>Reconnect Scanner: Windows 10 Troubleshooting Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-stop-and-resolve-printer-spooling-trouble/"><u>Steps to Stop and Resolve Printer Spooling Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instruction-setting-up-hp-printer-on-pc/"><u>Instruction: Setting Up HP Printer on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-blank-page-problem-solved/"><u>HP Printer Blank Page Problem Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7win10-stop-wasted-time-on-persistent-spooler-errors/"><u>Win7/Win10: Stop Wasted Time on Persistent Spooler Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-wireless-setup-step-by-step/"><u>Brother CDW Wireless Setup: Step by Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setup-pathway-attaching-hp-8720-to-computer-systems/"><u>Setup Pathway: Attaching HP 8720 to Computer Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-color-in-black-and-white-outputs/"><u>No Color in Black and White Outputs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-fixes-five-steps-to-ensure-your-canon-works-in-windows-11/"><u>Quick Printer Fixes: Five Steps to Ensure Your Canon Works in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-reviving-inactive-hp-copiers/"><u>Techniques for Reviving Inactive HP Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-disabled-scan-in-win11/"><u>Reviving Disabled Scan in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-inactive-print-devices/"><u>Solutions for Inactive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-functionality-with-mf4770n-driver-upgrade-for-windows-11w8w7/"><u>Streamline Functionality with MF4770n Driver Upgrade for Windows 11/W8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-are-my-documents-black-and-white/"><u>Why Are My Documents Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-navigate-canons-wireless-print-setup/"><u>Effortlessly Navigate Canon's Wireless Print Setup</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevate-your-youtube-presence-uncovering-the-6-key-strategies-to-boost-retention-rates/"><u>In 2024, Elevate Your YouTube Presence  Uncovering the 6 Key Strategies to Boost Retention Rates</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-oppo-a79-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Oppo A79 5G Devices | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/chuckle-crafting-tool-for-2024/"><u>Chuckle Crafting Tool for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-ultimate-guide-to-equalizing-auditory-output-in-vlc-software-for-2024/"><u>The Ultimate Guide to Equalizing Auditory Output in VLC Software for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-x8b-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Honor X8b Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-where-can-i-find-scary-sound-effect/"><u>Updated 2024 Approved Where Can I Find Scary Sound Effect?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-best-alternative-to-gopro-studio-to-work-with-gopro-footage/"><u>New 2024 Approved Best Alternative to GoPro Studio to Work with GoPro Footage</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-choosing-the-best-iphone-video-editor-filmorago-or-cameo/"><u>[New] In 2024, Choosing the Best iPhone Video Editor  FilmoRaGo or Cameo?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-free-makers-hub-for-top-tier-fb-visuals/"><u>[Updated] In 2024, Free Maker's Hub for Top-Tier FB Visuals</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-apple-iphone-14-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your Apple iPhone 14</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-driving-traffic-a-guide-to-successful-tiktok-campaigns/"><u>[New] In 2024, Driving Traffic  A Guide to Successful TikTok Campaigns</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-list-10-empowering-flicks-for-2024/"><u>The Ultimate List  10 Empowering Flicks for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-boosting-business-top-10-highlight-optimization-hacks/"><u>[New] In 2024, Boosting Business  Top 10 Highlight Optimization Hacks</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Meizu 21 | Dr.fone</u></a></li>
</ul></div>
