---
title: Instant Realignment for Trapped Print Jobs
date: 2024-07-10T16:48:28.930Z
updated: 2024-07-11T16:48:28.930Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instant Realignment for Trapped Print Jobs
excerpt: This Article Describes Instant Realignment for Trapped Print Jobs
keywords: Instant Print Job Relief,Resolve Stuck Print Jobs,Trapped Print Workflow Solutions,Quick Alignment for Printer Jams,Faster Print Processing Services,Efficient Print Job Reallocation,On-The-Spot Fixes for Delayed Prints
thumbnail: https://thmb.techidaily.com/759e3775dd226670ae28d5af19c1defd92ebed9270d940f9ca545069c585fcb0.jpg
---

## Instant Realignment for Trapped Print Jobs

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
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curb-intermittent-printer-halt-a-win-guide/"><u>Curb Intermittent Printer Halt: A Win Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dell-inkjet-errors-immediately/"><u>Fixing Dell Inkjet Errors Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-blackout-blank-sheets-every-time/"><u>Epson Printer Blackout: Blank Sheets Every Time</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-back-life-to-dead-printer/"><u>Bringing Back Life to Dead Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-scanner-connection-on-newly-installed-windows-10/"><u>Enabling Scanner Connection on Newly Installed Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-predicament-overcome-printer-setup-fix-for-windows-0x00000709/"><u>Paper Predicament Overcome: Printer Setup Fix for Windows (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-service-disabled-trouble-in-windows/"><u>Printer Service Disabled: Trouble in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unavailable-domain-services-printer-malfunction/"><u>Unavailable Domain Services, Printer Malfunction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-hurdle-installation-of-hp-d1360-printer-drivers/"><u>Compatibility Hurdle: Installation of HP D1360 Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnostic-unable-to-start-local-spooler-service/"><u>[DIAGNOSTIC] Unable to Start Local Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printing-speed-instantly/"><u>Boost Printing Speed Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-online-status-for-your-printer/"><u>Reclaiming Online Status for Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-driver-inaccessible-windows-1011-trouble/"><u>HP Driver Inaccessible - Windows 10/11 Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-steps-for-brothers-printer-resuming-normalcy-online/"><u>Easy Steps for Brother's Printer Resuming Normalcy Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/maximize-mf4770n-in-windows-1087-systems/"><u>Maximize MF4770n in WIndows 10/8/7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-integrating-hp-officejet-pro-8720-into-pc/"><u>Guide: Integrating HP Officejet Pro 8720 Into PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-inaccessible-printer-connection/"><u>Mended Inaccessible Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-post-windows-update-printer-workflow/"><u>Revived Post Windows Update Printer Workflow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-mute-how-to-engage/"><u>Canon Printer Mute - How to Engage?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-printer-software-solution-officejet-pro-8600-for-windows-pcs/"><u>Unified Printer Software Solution: Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-and-configure-hp-wireless-printer/"><u>How to Connect & Configure HP Wireless Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-pcs-error-b200/"><u>Fixed PC's Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-offline-causes-inability-to-print/"><u>AD DS Offline Causes Inability To Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-required-pixma-mp620-drivers-missing-windows-10/"><u>[Update Required] Pixma MP620 Drivers Missing Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-users-print-request-on-printer-noticed/"><u>Hidden User's Print Request on Printer Noticed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-brother-mfc-9330cdw-quickly/"><u>Install Brother MFC-9330CDW Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-printer-solutions-unveiled/"><u>Speedy Printer Solutions Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-unresponsive-on-pc/"><u>Print Spooler Service Unresponsive on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-restore-printer-functionality/"><u>Steps to Restore Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-9330cdw-fan-and-software-guide/"><u>Brother 9330CDW Fan & Software Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-puzzle-solved-error-avoided/"><u>Printer Puzzle Solved: Error Avoided</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fast-track-prints-in-queue/"><u>Fast-Track Prints in Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-queue-fails-to-operate-on-desktop/"><u>Printer Queue Fails to Operate on Desktop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-navigate-canons-wireless-print-setup/"><u>Effortlessly Navigate Canon's Wireless Print Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-tech-incorporating-hp-printer-into-pc-workflow/"><u>Stepwise Tech: Incorporating HP Printer Into PC Workflow</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-transformative-zooms-for-snapchat-photos-and-videos/"><u>[Updated] In 2024, Transformative Zooms for Snapchat Photos & Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-upgrading-your-spotify-library-to-youtube-music-access/"><u>[Updated] Upgrading Your Spotify Library to YouTube Music Access</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-your-picture-at-a-glance-quick-steps-for-saving-social-media-pics/"><u>[New] Your Picture at a Glance  Quick Steps for Saving Social Media Pics</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-the-essential-guide-to-using-voicemod-effectively-on-desktop-and-mobile/"><u>[Updated] In 2024, The Essential Guide to Using VoiceMod Effectively on Desktop & Mobile</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-prime-video-strategies-selecting-perfect-format-for-youtube/"><u>2024 Approved  Prime Video Strategies – Selecting Perfect Format for YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-thumbnail-blueprint-for-successful-videos/"><u>[Updated] The Ultimate Thumbnail Blueprint for Successful Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-basic-blueprint-for-seamless-speech-alteration-in-your-windows-sphere/"><u>In 2024, The Basic Blueprint for Seamless Speech Alteration in Your Windows Sphere</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-5-best-vr-video-converters-how-to-convert-regular-videos-to-vr/"><u>New Top 5 Best VR Video Converters How to Convert Regular Videos to VR</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-channel-catalysts-affiliates-aiding-budgeted-buzzers/"><u>2024 Approved  Channel Catalysts  Affiliates Aiding Budgeted Buzzers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-infinix-hot-30i-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Infinix Hot 30i.</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquer-oversized-drafts-learn-to-edit-and-organize-tiktok-content-for-2024/"><u>Conquer Oversized Drafts  Learn to Edit and Organize TikTok Content for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-unique-video-identity-designing-personalized-thumbnails/"><u>2024 Approved  Unique Video Identity  Designing Personalized Thumbnails</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-guide-to-annotate-windows-photos-video-content/"><u>[New] Step-by-Step Guide to Annotate Windows Photos Video Content</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/infusing-vibrancy-into-stories-a-guide-to-choosing-the-right-emojis/"><u>Infusing Vibrancy Into Stories  A Guide to Choosing the Right Emojis</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-quick-start-guide-utilizing-aiseesoft-for-effortless-screen-recordings/"><u>In 2024, Quick Start Guide  Utilizing Aiseesoft for Effortless Screen Recordings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-social-media-savant-writes-on-mastering-brand-promotion-for-2024/"><u>The Social Media Savant' Writes on Mastering Brand Promotion for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-nubia-red-magic-8s-pro-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Nubia Red Magic 8S Pro Phone When You Forget the Password</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-loop-like-a-boss-quick-and-easy-techniques-for-youtube-watchers/"><u>[New] 2024 Approved  Loop Like a Boss  Quick and Easy Techniques for YouTube Watchers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-s17-pro-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Vivo S17 Pro PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-structuring-inspirational-lifestyle-content-for-audiences/"><u>[Updated] 2024 Approved  Structuring Inspirational Lifestyle Content for Audiences</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-do-you-want-to-know-how-to-add-a-vhs-effect-premiere-look-you-can-easily-apply-the-vhs-effect-to-your-videos-using-adobe-premiere-pro/"><u>2024 Approved Do You Want to Know How to Add a VHS Effect Premiere Look? You Can Easily Apply the VHS Effect to Your Videos Using Adobe Premiere Pro</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-realme-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Realme Phone When You Forget the Password</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-perfect-your-profile-easy-guide-for-instagram-videos-from-desktop/"><u>[Updated] In 2024, Perfect Your Profile  Easy Guide for Instagram Videos From Desktop</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-join-the-favorite-fun-top-10-tiktok-trials/"><u>[Updated] In 2024, Join the Favorite Fun  Top 10 TikTok Trials</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adjusting-spotify-settings-stop-automated-podcast-suggestions/"><u>Adjusting Spotify Settings  Stop Automated Podcast Suggestions</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-motorola-moto-g84-5g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Motorola Moto G84 5G IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-calendar-on-iphone-15-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover lost Calendar on iPhone 15 | Stellar</u></a></li>
<li><a href="https://screen-capture.techidaily.com/efficient-entry-powerpoint-recordings-for-2024/"><u>Efficient Entry  PowerPoint Recordings for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/"><u>Kickstart Your Telegram Promotion Journey  Tips for Newbies</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-0x80072f30/"><u>Troubleshooting Microsoft Store: Error Code 0X80072F30</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/new-years-aspirations-method-to-success/"><u>New Year's Aspirations: Method to Success</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-simultaneous-screen-and-camera-capture-guide/"><u>2024 Approved  Simultaneous Screen & Camera Capture Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-xiaomi-redmi-12-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Xiaomi Redmi 12 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
</ul></div>
