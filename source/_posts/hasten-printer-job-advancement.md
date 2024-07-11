---
title: Hasten Printer Job Advancement
date: 2024-07-10T17:42:22.103Z
updated: 2024-07-11T17:42:22.103Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Hasten Printer Job Advancement
excerpt: This Article Describes Hasten Printer Job Advancement
keywords: Accelerate Inkjet Printing Processes,Advance Printer Technology Speed,Increase Print Job Efficiency,Optimize Printer Operation Speed,Fast-Track Print Technology Development,Enhance Printer Speed & Performance,Improve Print Job Turnaround Time
thumbnail: https://thmb.techidaily.com/dbfa6019d8b3f211a2d4346989a8be20fa1fb2520363f53adb487ff9f78fd127.jpg
---

## Hasten Printer Job Advancement

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
<li><a href="https://printer-issues.techidaily.com/setup-guide-adding-hp-printer-officejet-pro-to-pc-network/"><u>Setup Guide: Adding HP Printer (Officejet Pro) to PC Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-paper-mishap-error-code-0x00000709-solved/"><u>Windows Paper Mishap - Error Code 0X00000709 Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/demystifying-paper-jam-symptoms-in-printers/"><u>Demystifying Paper Jam Symptoms in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-brother-printer-not-printing-quagmire-reinstating-functionality-on-windows/"><u>Combat Brother Printer Not Printing Quagmire, Reinstating Functionality on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlock-hidden-printer-features-in-win10-systems/"><u>Unlock Hidden Printer Features in WIN10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-fix-scanner-disconnection-in-windows-10/"><u>Guide to Fix Scanner Disconnection in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inaccessible-domains-causing-print-errors/"><u>Inaccessible Domains Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-issue-code-b200/"><u>Resolved Issue Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reach-new-horizons-in-printer-functionality-4630-driver-upgrade-guide/"><u>Reach New Horizons in Printer Functionality: 4630 Driver Upgrade Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-instructions-connecting-your-new-canon-print-device/"><u>Stepwise Instructions: Connecting Your New Canon Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-installation-wizard-officejet-pro-8600-windows-printer-suite/"><u>Seamless Installation Wizard: Officejet Pro 8600 Windows Printer Suite</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstate-scanner-connection-on-windows-10-machine/"><u>Reinstate Scanner Connection on Windows 10 Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/complete-printing-solution-unveiled/"><u>Complete Printing Solution Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicate-brother-printers-no-print-dilemma-on-windows/"><u>Eradicate Brother Printer's No-Print Dilemma on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-efficient-data-flow-for-printers/"><u>Restoring Efficient Data Flow for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-with-textless-printouts-on-my-epson-scannerprinter/"><u>Trouble with Textless Printouts on My Epson Scanner/Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-horizons-in-workspace-tech-converging-hp-and-laptops-flawlessly/"><u>New Horizons in Workspace Tech - Converging HP and Laptops Flawlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printer-latency-issues/"><u>Eradicating Printer Latency Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-compatibility-windows-11-and-canons-mp620/"><u>Printer Compatibility: Windows 11 and Canon's MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-fixes-for-epson-error-0x97/"><u>Mastering Fixes for Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-11-printer-glitches-swiftly/"><u>Fix Windows 11 Printer Glitches Swiftly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-diving-deep-the-intricacies-of-the-mukbang-phenomenon-for-2024/"><u>[New] Diving Deep  The Intricacies of the Mukbang Phenomenon for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-elevate-video-popularity-12-key-strategies-unveiled/"><u>[New] 2024 Approved  Elevate Video Popularity  12 Key Strategies Unveiled</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamline-image-editing-ditching-backgrounds-in-affinity-photo/"><u>2024 Approved  Streamline Image Editing  Ditching Backgrounds in Affinity Photo</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-future-of-3d-color-grading-tools/"><u>[Updated] The Future of 3D Color Grading Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-12-mini-with-a-mask-on-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 mini with a Mask On</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streamlining-full-hd-watching-of-twit-videos/"><u>In 2024, Streamlining Full HD Watching of Twit Videos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/zero-to-hero-in-youtube-traffic-for-2024/"><u>From Zero to Hero in YouTube Traffic for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-safe-exit-procedures-for-departing-discord-servers-for-2024/"><u>[New] Safe Exit  Procedures for Departing Discord Servers for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-apps-for-perfectly-altered-videos-on-ios-and-desktop/"><u>[Updated] Premium Apps for Perfectly Altered Videos on iOS & Desktop</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-10-best-video-editing-apps-for-kids-free-and-paid-for-2024/"><u>New 10 Best Video Editing Apps for Kids FREE & PAID for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-mastering-the-zoom-meeting-experience-tips-for-fluid-online-discussion/"><u>[New] 2024 Approved  Mastering the Zoom Meeting Experience  Tips for Fluid Online Discussion</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-apple-iphone-6-plus-lock-screen-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From Apple iPhone 6 Plus Lock Screen</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-13-pro-max-without-swiping-up-6-ways-by-drfone-ios/"><u>How To Unlock Apple iPhone 13 Pro Max Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-free-yet-effective-10-security-camera-software-options/"><u>New 2024 Approved Free Yet Effective 10 Security Camera Software Options</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-perfecting-podcast-production-an-ultimate-tutorial-for-high-quality-zoom-recordings/"><u>[New] 2024 Approved  Perfecting Podcast Production  An Ultimate Tutorial for High-Quality Zoom Recordings</u></a></li>
</ul></div>
