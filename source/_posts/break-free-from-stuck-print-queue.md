---
title: Break Free From Stuck Print Queue
date: 2024-08-27T02:17:44.418Z
updated: 2024-08-28T02:17:44.418Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Break Free From Stuck Print Queue
excerpt: This Article Describes Break Free From Stuck Print Queue
keywords: Clear Stuck Print Queue,Fix Printer Printing Issues,Stop Printer Error Message,Resolve Print Spooler Problems,End Stuck Print Job Issue,Unfreeze or Release Print Queue,Prevent Long-Running Print Jobs
thumbnail: https://thmb.techidaily.com/4e1e135a4b0338f686903eb0c608ba2a349e6fad2f1ea5329a35a6ad22caba43.png
---

## Break Free From Stuck Print Queue

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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/driver-issue-windows-11-not-supporting-canon-mp620/"><u>[Driver Issue] Windows 11 Not Supporting Canon MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-search-failed-unable-to-locate-hp-winxo/"><u>[Driver Search Failed] - Unable to Locate HP WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/drivers-canon-mp620-not-found-on-11th-edition-windows/"><u>[Drivers] Canon MP620 Not Found on 11Th Edition Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-usb-printers-unresponsive-in-win7-hibernate/"><u>[Fixed] USB Printers Unresponsive in Win7 Hibernate</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-best-free-screen-recorder-programs-with-no-trial-period/"><u>[New] 2024 Approved  Best Free Screen Recorder Programs with No Trial Period</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-livestream-audiovideo-creators-hub/"><u>[New] 2024 Approved  LiveStream Audio/Video Creators Hub</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-winning-at-desktop-tiktok-strategies-and-techniques/"><u>[New] 2024 Approved  Winning at Desktop TikTok  Strategies and Techniques</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastery-manual-downloading-hd-videos-on-todays-digital-landscapes/"><u>[New] In 2024, Mastery Manual  Downloading HD Videos on Today's Digital Landscapes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-efficient-techniques-for-secure-and-effective-lecture-capturing-using-imac/"><u>[Updated] 2024 Approved  Efficient Techniques for Secure and Effective Lecture Capturing Using iMac</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-archive-your-antics-a-practical-guide-to-capturing-and-storing-gif-images-from-twitter-for-2024/"><u>[Updated] Archive Your Antics  A Practical Guide to Capturing and Storing GIF Images From Twitter for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-infinite-artistic-possibilities-with-top-10-apps/"><u>[Updated] Explore Infinite Artistic Possibilities with Top 10 Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-lava-blaze-2-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Lava Blaze 2 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-proven-steps-building-quality-time-lapses-on-galaxy-devices/"><u>2024 Approved  Proven Steps  Building Quality Time-Lapses on Galaxy Devices</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-quick-windows-surfing-guide-unveiled/"><u>2024 Approved  Quick Windows Surfing Guide Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ad-ds-service-down-unable-to-print/"><u>AD DS Service Down: Unable To Print</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/best-5-for-high-speed-video-capture-tech/"><u>Best 5 for High-Speed Video Capture Tech</u></a></li>
<li><a href="https://facebook.techidaily.com/beyond-first-impressions-deciphering-the-fb-intrigue/"><u>Beyond First Impressions: Deciphering The FB Intrigue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/black-and-white-only-mode-engaged-by-printer/"><u>Black & White Only Mode Engaged by Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-fan-setup-instructions/"><u>Brother CDW Duo Fan Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cannot-find-hp-printer-drivers-on-win1110/"><u>Cannot Find HP Printer Drivers on Win11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-found-windows-10-and-pixma-mp620-disconnect/"><u>Driver Not Found: Windows 10 and Pixma MP620 Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-hp-officejet-4630-latest-software-releases/"><u>Elevate HP Officejet 4630: Latest Software Releases</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-persistent-failures-of-the-print-spooler-service/"><u>Eliminate Persistent Failures of the Print Spooler Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-wi-fi-directly-for-canon-printers/"><u>Enabling Wi-Fi Directly for Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-repeated-print-job-failures-guide-for-windows-107-users/"><u>End Repeated Print Job Failures: Guide for Windows 10/7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-w11-printer-response-times/"><u>Enhance W11 Printer Response Times</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-your-printing-experience-with-canon-windows-10-tips/"><u>Enhance Your Printing Experience with Canon, Windows 10 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/explore-10-youtube-creators-accelerating-their-popularity/"><u>Explore 10 YouTube Creators Accelerating Their Popularity</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-offline-workflow-blockage/"><u>Fixed Offline Workflow Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanned-device-connection-issue-on-win10/"><u>Fixing Scanned Device Connection Issue on Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-brother-printer-back-to-life-fixing-non-print-on-windows/"><u>Get Your Brother Printer Back to Life: Fixing Non-Print on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-slow-printing-easily-and-quickly/"><u>How to Fix Slow Printing [Easily & Quickly]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-action-on-queued-printer-work/"><u>Immediate Action on Queued Printer Work</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-budget-friendly-microphones-for-online-broadcasters/"><u>In 2024, Budget-Friendly Microphones for Online Broadcasters</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-leveraging-tiktok-videos-for-twitter-audiences/"><u>In 2024, Leveraging TikTok Videos for Twitter Audiences</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-seamless-integration-of-skype-meetings-into-zoom-platform/"><u>In 2024, Seamless Integration of Skype Meetings Into Zoom Platform</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-whats-going-wrong-sideways-videos-on-instagram/"><u>In 2024, What's Going Wrong  Sideways Videos on Instagram</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-v30-profrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo V30 ProFRP Lock</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/jokejumper-generate-share-worthy-images-quickly-for-2024/"><u>JokeJumper  Generate Share-Worthy Images Quickly for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/monochrome-output-despite-color-settings/"><u>Monochrome Output Despite Color Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-problems-in-adding-printer/"><u>No Problems in Adding Printer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/number-1-in-the-elite-8-virtual-composite-maker/"><u>Number 1 in the Elite 8 Virtual Composite Maker</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-predicament-overcome-printer-setup-fix-for-windows-0x00000709/"><u>Paper Predicament Overcome: Printer Setup Fix for Windows (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setup-no-complications-found/"><u>Print Setup: No Complications Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-woes-ended-new-windows-solved-issue/"><u>Printer Woes Ended: New Windows Solved Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-woes-in-windows-11-help-needed/"><u>Printer Woes in Windows 11 - Help Needed!</u></a></li>
<li><a href="https://fox-access.techidaily.com/quality-control-best-free-lut-selections-and-links-reviewed/"><u>Quality Control  Best Free LUT Selections & Links Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-classics-playing-oldschool-games-with-dosbox-x/"><u>Reviving Classics: Playing Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-canon-printer-with-ease-on-wi-fi/"><u>Setting Up Canon Printer with Ease on Wi-Fi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-connection-solutions-joining-your-laptop-and-hp-printer/"><u>Streamlined Connection Solutions: Joining Your Laptop and HP Printer</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-complete-guide-to-360-video-submission-on-fb-for-2024/"><u>The Complete Guide to 360 Video Submission on FB for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-for-restarting-non-functional-hp-photo-units/"><u>Tips for Restarting Non-Functional HP Photo Units</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-unlinkage-from-youtube-shorts-complete-guide-for-2024/"><u>Total Unlinkage From YouTube Shorts  Complete Guide for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-colored-images/"><u>Unable to Print Colored Images</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocked-scanner-operation-in-windows-11-os/"><u>Unblocked Scanner Operation in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-glitch-detected/"><u>Unexpected Print Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unforeseen-print-malfunction-noted/"><u>Unforeseen Print Malfunction Noted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-troubleshooting-guide/"><u>Windows 11 Printer Troubleshooting Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-scanner-now-functional/"><u>Windows 11: Scanner Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-the-cause-of-hp-printers-white-sheets/"><u>Zeroing In on the Cause of HP Printer’s White Sheets</u></a></li>
</ul></div>
