---
title: Instantaneous Clearance for Prints
date: 2024-07-10T17:36:47.131Z
updated: 2024-07-11T17:36:47.131Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Instantaneous Clearance for Prints
excerpt: This Article Describes Instantaneous Clearance for Prints
keywords: Instant Print Clearance,Rapid Print Approval Process,Immediate Print Authorization,Quick Clearance Prints,Express Print Release,Same-Day Print Clearance,Fast-Track Printing Approval
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Instantaneous Clearance for Prints

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
<li><a href="https://printer-issues.techidaily.com/rectify-print-job-failures-on-windows-11/"><u>Rectify Print Job Failures on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypass-printer-job-queue-delay-instantly/"><u>Bypass Printer Job Queue Delay Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-with-hp-print-on-w7-resolved/"><u>Connectivity Woes with HP Print on W7 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-wireless-printer-with-hp-color-life-series/"><u>How To: Set Up a Wireless Printer with HP Color Life Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-printer-configuration-errors-in-w11/"><u>Correct Printer Configuration Errors in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-eliminating-drivers-without-error/"><u>Techniques for Eliminating Drivers Without Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win107-troubleshooting-steps-to-address-spooler-failures/"><u>Win10/7 Troubleshooting Steps to Address Spooler Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-no-access-to-printer-drivers/"><u>Windows: No Access to Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-issue-eliminated/"><u>B200 Issue Eliminated</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-printer-malfunction-code-0x97/"><u>Mending Printer Malfunction: Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winning-strategies-for-installing-hp-printer-software/"><u>Winning Strategies for Installing HP Printer Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-anomaly-linked-to-unknown-pc/"><u>Printing Anomaly Linked to Unknown PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-error-unable-to-install-mp620-printer-driver/"><u>Windows Error: Unable to Install MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-device-hooked-up-no-friction/"><u>Print Device Hooked Up, No Friction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt-reactivate-sluggish-uncooperative-printer/"><u>WinNT: Reactivate Sluggish, Uncooperative Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-cannot-retrieve-printer-drivers/"><u>Windows Cannot Retrieve Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printing-speed-instantly/"><u>Boost Printing Speed Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-find-hp-printer-drivers-on-win1110/"><u>Cannot Find HP Printer Drivers on Win11/10</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-elevate-your-social-presence-proven-methods-for-fb-fan-expansion/"><u>[Updated] 2024 Approved  Elevate Your Social Presence  Proven Methods for FB Fan Expansion</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dive-into-dynamic-footage-the-review-of-polaroid-cubeplus/"><u>Dive Into Dynamic Footage  The Review of Polaroid Cube+</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-looking-for-a-way-to-edit-your-profile-picture-for-telegram-heres-an-easy-and-quick-guide-on-how-to-change-delete-and-hide-your-profile-picture-/"><u>New In 2024, Looking for a Way to Edit Your Profile Picture for Telegram? Heres an Easy and Quick Guide on How to Change, Delete and Hide Your Profile Picture with Simple Steps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/integrated-iptv-channel-distribution/"><u>Integrated IPTV Channel Distribution</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-effortless-integration-of-xbox-and-facebook-streams/"><u>[New] Effortless Integration of Xbox and Facebook Streams</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/harnessing-tiktoks-hottest-hashtags-for-visibility-for-2024/"><u>Harnessing TikTok's Hottest HashTags for Visibility for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-instant-insights-switching-up-your-facebook-profile-coverage-easily/"><u>2024 Approved  Instant Insights  Switching Up Your Facebook Profile Coverage Easily</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-fcpx-title-tutorial-from-basics-to-advanced-techniques/"><u>Updated FCPX Title Tutorial From Basics to Advanced Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-art-of-anime-adaptation-jujutsu-kaisens-tiktok-success/"><u>The Art of Anime Adaptation  Jujutsu Kaisen's TikTok Success</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leveraging-famebit-strategies-for-effective-youtube-sponsors-for-2024/"><u>Leveraging FameBit Strategies for Effective YouTube Sponsors for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-vivo-v29-pro-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Vivo V29 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-magic-5-lite-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor Magic 5 Lite Devices</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-gionee-f3-pro-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Gionee F3 Pro? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-best-practices-for-youtube-to-igtv-transformation/"><u>2024 Approved  Best Practices for YouTube to IGTV Transformation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-ultimate-tutorial-mastering-twitter-video-responses/"><u>In 2024, Ultimate Tutorial  Mastering Twitter Video Responses</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-galaxy-f34-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Samsung Galaxy F34 5G?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-12-pro-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 12 Pro Randomly Asking for Apple ID Password</u></a></li>
</ul></div>
