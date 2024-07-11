---
title: Rapid Unjamming of Print Workqueue
date: 2024-07-10T17:48:54.827Z
updated: 2024-07-11T17:48:54.827Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Unjamming of Print Workqueue
excerpt: This Article Describes Rapid Unjamming of Print Workqueue
keywords: Rapid Workqueue Solutions,Fast-Tracking Print Processes,Workqueue Management,Efficient Printwork Queue Optimization,Unjamming Printer Workqueue Techniques,Streamlining Print Operations,Printer Workqueue Performance Improvement
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Rapid Unjamming of Print Workqueue

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
<li><a href="https://printer-issues.techidaily.com/scanner-reactivation-achieved-in-windows-11/"><u>Scanner Reactivation Achieved in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573877149-effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dead-paper-output-in-hp-printers/"><u>Fixing Dead Paper Output in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-software-conflicts-in-printing-hardware/"><u>Resolving Software Conflicts in Printing Hardware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-snag-another-systems-footprint-found/"><u>Printer Snag: Another System's Footprint Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-deadprint-a-step-by-step-guide/"><u>Reviving a Deadprint: A Step-by-Step Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printing-setup-for-hp-and-laptops-immediate-solutions/"><u>Seamless Printing Setup for HP & Laptops - Immediate Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-now-functioning/"><u>HP Printer Offline, Now Functioning</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-epson-workflow-flow/"><u>Restored Epson Workflow Flow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-crippled-printer-driver-unavailable-in-win/"><u>[SYSTEM CRIPPLED] Printer Driver Unavailable in Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-eliminating-pcl-xl-issues/"><u>Step-by-Step: Eliminating PCL XL Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-fedex-printer-connectivity-troubles/"><u>Rectifying FedEx Printer Connectivity Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-unfreeze-an-offline-brother-printer-online/"><u>How To Unfreeze an Offline Brother Printer Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-software-for-hp-officejet-4630-installation/"><u>Latest Software for HP Officejet 4630 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-document-output-on-windowshp/"><u>Streamlining Document Output on Windows/HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-paper-queue-freeze-on-windows-oses-10-11-and-7/"><u>Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hiccup-printer-config-issue/"><u>Hardware Hiccup: Printer Config Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-unresolved-printer-queue-issue/"><u>Speed Up Unresolved Printer Queue Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-document-saving-functionality-in-windows-11/"><u>Enhance Document Saving Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-canon-printer-fixes-for-windows-users/"><u>Effortless Canon Printer Fixes for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-non-responding-printer-unit/"><u>Tackled Non-Responding Printer Unit</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-for-reviving-offline-printers/"><u>Steps for Reviving Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-offline-printer-back-online/"><u>Win7 Offline Printer Back Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cured-printer-not-printing-on-epson-solved/"><u>Cured: Printer Not Printing on Epson [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-integration-update-mf4770n-drivers-on-w11w8w7-os/"><u>Smooth Integration: Update MF4770n Drivers on W11/W8/W7 OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-perfecting-the-art-of-borders-in-instagram-photos/"><u>[Updated] In 2024, Perfecting the Art of Borders in Instagram Photos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-video-editing-mastery-online-tutorials-for-beginners-and-pros/"><u>In 2024, Video Editing Mastery Online Tutorials for Beginners and Pros</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-15-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock iPhone 15 Without Passcode Easily</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/which-mp3-converter-reigns-supreme-on-mac-for-2024/"><u>Which MP3 Converter Reigns Supreme on Mac for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gopro-hero5-pro-vs-gopro-hero4-platinum-for-2024/"><u>GoPro Hero5 Pro Vs GoPro Hero4 Platinum for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ideal-tools-leading-mac-video-recording-programs/"><u>In 2024, Ideal Tools  Leading Mac Video Recording Programs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-8-valuable-image-ratio-changer-online/"><u>New 8 Valuable Image Ratio Changer Online</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-facebook-live-the-world-in-minutes/"><u>[New] 2024 Approved  Facebook Live  The World in Minutes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-online-no-cost-fb-sound-archive/"><u>[New] 2024 Approved  Online, No Cost FB Sound Archive</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-meizu-21-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Meizu 21</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/voice-adaptation-solutions-picks-for-video-makers/"><u>Voice Adaptation Solutions  Picks for Video Makers</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-fcp-audio-editing-made-easy-a-tutorial-for-creators-for-2024/"><u>Updated FCP Audio Editing Made Easy A Tutorial for Creators for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-step-by-step-process-for-high-quality-thumbnails-for-2024/"><u>[Updated] Step-by-Step Process for High-Quality Thumbnails for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/quick-guide-downloading-tiktok-for-mac-users-for-2024/"><u>Quick Guide  Downloading TikTok for Mac Users for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-copyright-free-audio-treasury-for-gamers-online/"><u>In 2024, Copyright-Free Audio Treasury for Gamers Online</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unleash-your-creativity-a-beginners-guide-to-mac-movie-maker-software/"><u>Unleash Your Creativity A Beginners Guide to Mac Movie Maker Software</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-hottest-youtube-music-playback-responses-23/"><u>[New] Hottest YouTube Music Playback Responses '23</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-vocaltune-hub-deciphering-the-technology-praise-from-users-and-what-else-you-should-explore/"><u>New 2024 Approved VocalTune Hub Deciphering the Technology, Praise From Users, and What Else You Should Explore</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unleash-creativity-with-these-8-mirrorless-cams-for-video-for-2024/"><u>Unleash Creativity with These 8 Mirrorless Cams For Video for 2024</u></a></li>
</ul></div>
