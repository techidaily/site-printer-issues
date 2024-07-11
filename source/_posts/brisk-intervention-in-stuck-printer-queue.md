---
title: Brisk Intervention in Stuck Printer Queue
date: 2024-07-10T17:17:23.734Z
updated: 2024-07-11T17:17:23.734Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Brisk Intervention in Stuck Printer Queue
excerpt: This Article Describes Brisk Intervention in Stuck Printer Queue
keywords: Brisk Intervention,Resolving Stuck Print Queue,Printer Queue Management,Quick Fix for Printer Errors,Preventing Printer Jamming,Manual Printer Queue Clearance,Troubleshooting Printer Queue Issues
thumbnail: https://thmb.techidaily.com/f7564240f8faa92ac0e388d789a175a79bd1b95533429025b3702f8272211ea0.jpg
---

## Brisk Intervention in Stuck Printer Queue

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
<li><a href="https://printer-issues.techidaily.com/steps-to-resolve-print-spooler-shutdown-woes-win-10-11-and-7/"><u>Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-difficulty-unable-to-locate-hp-driver-on-winxo/"><u>[Driver Difficulty] - Unable to Locate HP Driver on WinXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-purge-network-print-settings-on-win-1011/"><u>Guide to Purge Network Print Settings on Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-failure-not-recognizing-canon-model/"><u>Printer Failure: Not Recognizing Canon Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-no-printer-device-on-your-os/"><u>Unexpectedly No Printer Device on Your OS?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-3d-imaging-printer-easily/"><u>Integrating HP 3D Imaging Printer Easily</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-cannot-set-default-printer-on-windows-solved/"><u>Error 0X00000709 Cannot Set Default Printer on Windows [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-repair-for-xerox-error-alert-0x1/"><u>Swift Repair for Xerox Error Alert 0X1</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-printer-setup-with-canon-guided-examples/"><u>Instant Printer Setup with Canon - Guided Examples</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-printer-malfunction-code-0x97/"><u>Mending Printer Malfunction: Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-queue-error-messages-on-windows-11/"><u>Fix Printing Queue Error Messages on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-down-print-operation-fails/"><u>Active Directory Down - Print Operation Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/nozzle-clog-in-hp-printer-cleared-successfully/"><u>Nozzle Clog in HP Printer Cleared Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-memory-overuse-by-w11-printers/"><u>Address Memory Overuse by W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-missing-hp-print-drivers-unfound/"><u>Windows Missing: HP Print Drivers Unfound</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-interactions-mf4770n-update-in-win11win87-os/"><u>Enhance Device Interactions: MF4770n Update in Win11/Win8/7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-tutorial-setting-up-an-hp-photosmart-x529i/"><u>Connectivity Tutorial: Setting Up an HP PhotoSmart X529i</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-obstacle-with-epson/"><u>Overcome Printing Obstacle with Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-searching-for-missing-windows-driver/"><u>MP620 Printer: Searching for Missing Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-printer-disconnected-from-network/"><u>Troubleshooting: Printer Disconnected From Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-issue/"><u>Mended Printer Network Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnose-and-cure-win10-print-spooler-hiccups/"><u>Diagnose & Cure WIN10 Print Spooler Hiccups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-pcl-xl-complications-swiftly/"><u>Navigating PCL XL Complications Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-printer/"><u>Successfully Installed Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-pixma-mp620-not-found-in-windows-11-driver-list/"><u>[Installation] Pixma MP620 Not Found in Windows 11 Driver List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-releasing-a-stuck-printer-from-windows/"><u>Quick Guide: Releasing A Stuck Printer From Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-internet-connectivity-for-brother-printer/"><u>Reclaiming Internet Connectivity for Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-hp-printer-firmware-update/"><u>Step-by-Step Guide to HP Printer Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-cant-get-hp-d1360-to-work-windows-versions-involved/"><u>[Hardware Setup] Can't Get HP D1360 to Work: Windows Versions Involved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330cdw-fan-bro-free-drive-setup/"><u>MFC-9330CDW Fan Bro: Free Drive Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-error-on-hp-printer-0xoxc4eb827f/"><u>Eliminating Error on HP Printer: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-hp-printer-offline-in-win7-home/"><u>Fixed HP Printer Offline in Win7 Home</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-journey-from-void-papers-to-valuable-outputs/"><u>The Journey From Void Papers to Valuable Outputs</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-11-pro-max-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 11 Pro Max iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-breaking-down-augmented-realitys-mysteries/"><u>[Updated] Breaking Down Augmented Reality's Mysteries</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-vidmas-technology-in-screen-capturing-spotlighted-for-2024/"><u>[New] Vidma’s Technology in Screen Capturing Spotlighted for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-minecraft-community-image-bank-access/"><u>[Updated] Minecraft Community Image Bank Access</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-channel-buying-made-simple-a-beginners-toolkit/"><u>2024 Approved  Channel Buying Made Simple  A Beginner’s Toolkit</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-crafting-your-perfect-youtube-playlists-a-step-by-step-guide/"><u>2024 Approved  Crafting Your Perfect YouTube Playlists  A Step-by-Step Guide</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-pokegoplusplus-still-work-on-apple-iphone-12-miniipad-drfone-by-drfone-virtual-ios/"><u>Does PokeGo++ still work on Apple iPhone 12 mini/iPad? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-transforming-your-tiktok-presence-with-exceptional-photos-for-2024/"><u>[Updated] Transforming Your TikTok Presence with Exceptional Photos for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unleashing-the-power-of-cross-platform-video-playback-software/"><u>Unleashing the Power of Cross-Platform Video Playback Software</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-local-labor-costs-the-availability-and-rates-of-skilled-electricians-in-the-area-can-affect-labor-costs-significantly/"><u>[Updated] __Local Labor Costs__  The Availability and Rates of Skilled Electricians in the Area Can Affect Labor Costs Significantly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-ultimate-guide-to-selecting-best-windows-screen-capture-tools/"><u>[Updated] Ultimate Guide to Selecting Best Windows Screen Capture Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-xiaomi-redmi-k70-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Xiaomi Redmi K70 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-enhance-cinematic-vision-using-ae-luts-effectively-for-2024/"><u>[Updated] Enhance Cinematic Vision  Using AE LUTs Effectively for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-stream-movies-from-your-device-to-chromecast-windows-mac-android-and-ios-tutorial-for-2024/"><u>Updated Stream Movies From Your Device to Chromecast Windows, Mac, Android, and iOS Tutorial for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-how-to-play-youtube-in-background-on-iphone-and-android/"><u>[New] How to Play YouTube in Background on iPhone and Android</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-channel-your-content-earning-through-evaluative-endeavors-online/"><u>[Updated] 2024 Approved  Channel Your Content  Earning Through Evaluative Endeavors Online</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-locate-your-youtube-fanbase-for-2024/"><u>[New] How to Locate Your YouTube Fanbase for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-bringing-your-vision-to-life-top-7-animation-drawing-software-tools/"><u>Updated In 2024, Bringing Your Vision to Life Top 7 Animation Drawing Software Tools</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-free-video-storage-10-reliable-hosts-for-personal-and-commercial-videos/"><u>2024 Approved Free Video Storage 10 Reliable Hosts for Personal and Commercial Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-exclusive-access-to-premium-playlists-on-mobile-devices/"><u>[Updated] In 2024, Exclusive Access to Premium Playlists on Mobile Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/introducing-efficient-speech-to-text-utilization-in-powerpoint-for-2024/"><u>Introducing Efficient Speech-to-Text Utilization in PowerPoint for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-obs-and-streamlabs-mac-integration/"><u>[Updated] Mastering OBS & Streamlabs Mac Integration</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-six-easy-steps-to-enhance-your-videos-with-music-without-expense/"><u>Updated 2024 Approved Six Easy Steps to Enhance Your Videos with Music Without Expense</u></a></li>
</ul></div>
