---
title: Efficiently End Print Job Wait
date: 2024-07-10T17:12:06.203Z
updated: 2024-07-11T17:12:06.203Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Efficiently End Print Job Wait
excerpt: This Article Describes Efficiently End Print Job Wait
keywords: Print Job Cancellation,Quick Print Termination,Immediate Print Stop,Print Workflow Interruption,Optimize Print Job Ending,Print Management Strategies,Latency Reduction in Printing
thumbnail: https://thmb.techidaily.com/750c1d86ce393517a7e8e0f28b8261fcac89b61944729e317e412d6180bd4eb2.jpg
---

## Efficiently End Print Job Wait

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
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-hp-printer-status/"><u>How to Reactivate HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-printer-printing-blank-pages/"><u>[SOLVED] Epson Printer Printing Blank Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-print-issue-winerror-0x00000709-remedied/"><u>Triumph Over Print Issue: WinError 0X00000709 Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-searches-for-non-existent-printer-driver/"><u>Windows Searches for Non-Existent Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-add-hp-officejet-pro-8720-to-your-pc-step-by-step/"><u>How to Add HP OfficeJet Pro 8720 to Your PC [Step by Step]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-enhance-windows-11-8-7-integration/"><u>MF4770n Drivers - Enhance Windows 11, 8, 7 Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/proactive-measures-immediate-resolution-of-pcl-xl-problems/"><u>Proactive Measures: Immediate Resolution of PCL XL Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/default-printer-dilemma-windows-error-0x00000709-squashed/"><u>Default Printer Dilemma: Windows Error (0X00000709) Squashed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/officejet-pro-8600-windows-driver-and-utilities-set/"><u>Officejet Pro 8600 Windows Driver & Utilities Set</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-obstacle-with-epson/"><u>Overcome Printing Obstacle with Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-your-windows-11-printer-problems/"><u>Solve Your Windows 11 Printer Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574032401-trouble-printing-on-windows-11-lets-fix-it/"><u>Trouble Printing on Windows 11? Let's Fix It!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-hq-blank-page-conundrum-resolved/"><u>Epson HQ Blank Page Conundrum Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-single-printer-page-solution/"><u>Print Every Single Printer Page [Solution]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-usb-printers-unresponsive-in-win7-hibernate/"><u>[Fixed] USB Printers Unresponsive in Win7 Hibernate</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-hp-printer-connectivity-issues/"><u>Resolving HP Printer Connectivity Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-canon-printer-step-by-step/"><u>Installing Canon Printer - Step-by-Step</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573890689-canon-printer-woes-here-are-your-five-easy-fixes-in-windows-11/"><u>Canon Printer Woes? Here Are Your Five Easy Fixes in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-and-painless-connecting-canon-to-wi-fi-network/"><u>Quick and Painless: Connecting Canon to Wi-Fi Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domain-disabled-resulting-in-print-errors/"><u>Domain Disabled: Resulting in Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win2k-printer-response-error-resolution-guide/"><u>Win2K Printer Response: Error Resolution Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/intruder-in-network-print-spotlighted/"><u>Intruder in Network Print Spotlighted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-driven-print-screws/"><u>Unblocking Driven Print Screws</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zeroing-in-on-the-cause-of-hp-printers-white-sheets/"><u>Zeroing In on the Cause of HP Printer’s White Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setup-no-complications-found/"><u>Print Setup: No Complications Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-dell-inkjet-errors-immediately/"><u>Fixing Dell Inkjet Errors Immediately</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnecting-brothers-print-to-end-offline-status-woes/"><u>Reconnecting Brothers Print to End Offline Status Woes</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/compile-of-high-quality-sound-spectrum-templates-to-elevate-video-production-2023-update/"><u>Compile of High-Quality Sound Spectrum Templates to Elevate Video Production - 2023 Update</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-securely-sharing-video-on-youtube-with-settings/"><u>2024 Approved  Securely Sharing Video on YouTube with Settings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-maximizing-income-sourav-joshis-youtube-journey/"><u>[New] Maximizing Income  Sourav Joshi's YouTube Journey</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-from-novice-to-pro-magix-video-pro-x-journey/"><u>[New] 2024 Approved  From Novice to Pro  Magix Video Pro X Journey</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-from-novice-to-pro-an-extensive-guide-on-using-zd-softs-recording-features/"><u>[New] In 2024, From Novice to Pro  An Extensive Guide on Using ZD Soft’s Recording Features</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-enjoy-the-full-range-of-sharing-on-messenger-for-2024/"><u>[New] How to Enjoy the Full Range of Sharing on Messenger for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-no-limit-record-media-software/"><u>[Updated] 2024 Approved  No-Limit Record Media Software</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/unlocking-potential-top-10-tiktok-data-tools/"><u>Unlocking Potential  Top 10 TikTok Data Tools</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-mind-mavens-top-10-educational-youtube-hubs/"><u>In 2024, Mind Mavens  Top 10 Educational YouTube Hubs</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-breaking-the-videography-code-download-and-preserve-media-on-fb/"><u>[Updated] Breaking the Videography Code  Download and Preserve Media on FB</u></a></li>
<li><a href="https://some-tips.techidaily.com/utilizing-free-clip-art-for-graphic-designs-for-2024/"><u>Utilizing Free Clip Art for Graphic Designs for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-blur-faces-or-backgrounds-in-videos-best-apps-for-ios-and-android-for-2024/"><u>Updated Blur Faces or Backgrounds in Videos Best Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-activate-windows-xp-movie-creation-toolkit/"><u>[New] Activate Windows XP Movie Creation Toolkit</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-reno-9a-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo Reno 9A Device</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-exclusive-no-watermark-downloads-from-tiktok/"><u>[New] Exclusive  No Watermark Downloads From TikTok</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-disrupting-tradition-the-emerging-fb-ad-practices/"><u>[Updated] 2024 Approved  Disrupting Tradition  The Emerging FB Ad Practices</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-mastering-the-skill-how-to-securely-record-on-whatsapp-for-2024/"><u>[New] Mastering the Skill  How to Securely Record on WhatsApp for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stand-out-design-and-customize-professional-logos-via-free-templates/"><u>In 2024, Stand Out  Design and Customize Professional Logos via Free Templates</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-ultimate-videopad-review-pros-cons-and-alternatives/"><u>2024 Approved The Ultimate Videopad Review Pros, Cons, and Alternatives</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-get-your-final-cut-pro-90-days-free-trial-here-for-2024/"><u>Updated Get Your Final Cut Pro 90 Days FREE Trial Here for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-windows-enthusiasts-guide-to-premium-free-audio-editing-applications/"><u>New 2024 Approved Windows Enthusiasts Guide to Premium Free Audio Editing Applications</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-m1-pro-and-m1-max-a-comparative-insight-into-apples-latest-chips/"><u>In 2024, M1 Pro and M1 Max - A Comparative Insight Into Apple's Latest Chips</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-ace-2v-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Ace 2V Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comprehensive-insights-streamlined-iphone-podcast-downloads/"><u>2024 Approved  Comprehensive Insights  Streamlined iPhone Podcast Downloads</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-13-pro-max-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
</ul></div>
