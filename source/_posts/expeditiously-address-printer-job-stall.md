---
title: Expeditiously Address Printer Job Stall
date: 2024-08-27T02:18:00.891Z
updated: 2024-08-28T02:18:00.891Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expeditiously Address Printer Job Stall
excerpt: This Article Describes Expeditiously Address Printer Job Stall
keywords: Printer Job Stall,Fixing Printer Issues,Printer Troubleshooting Guide,Quick Fix Printer Halt,Printer Error Resolution,Overcoming Printer Job Freeze,Improving Print Output Speed
thumbnail: https://thmb.techidaily.com/1b6976dc536a482a8440b6155a5c6ffdb602672c280e778006363b18d82c63d3.jpg
---

## Expeditiously Address Printer Job Stall

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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/installation-pixma-mp620-not-found-in-windows-11-driver-list/"><u>[Installation] Pixma MP620 Not Found in Windows 11 Driver List</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-unlocking-youtubes-potential-establishing-an-effective-upload-cadence/"><u>[New] 2024 Approved  Unlocking YouTube's Potential  Establishing an Effective Upload Cadence</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/astering-youtube-channel-descriptions-for-2024/"><u>[New] Mastering YouTube Channel Descriptions for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-maximize-your-webcam-hp-and-chromebook-strategies-for-2024/"><u>[New] Maximize Your Webcam  HP & Chromebook Strategies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-optimal-quick-image-reader-for-pcs-for-2024/"><u>[Updated] Optimal Quick Image Reader for PCs for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-revealing-the-identity-of-viewers-on-youtube/"><u>[Updated] Revealing the Identity of Viewers on YouTube</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-ultimate-guide-to-non-udemy-online-education-sites/"><u>2024 Approved  Ultimate Guide to Non-Udemy Online Education Sites</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-iphone-15-plus-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase iPhone 15 Plus When Its Locked Within Seconds</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/asrock-revolutionizes-gaming-rigs-with-their-brand-new-ryzen-9000-motherboards/"><u>ASRock Revolutionizes Gaming Rigs with Their Brand New Ryzen 9000 Motherboards</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-problem-resolved/"><u>B200: Problem Resolved</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-productivity-in-vs-code-by-incorporating-chatgpt-a-guide-to-10-key-strategies/"><u>Boost Productivity in VS Code by Incorporating ChatGPT - A Guide to 10 Key Strategies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-errors-try-these-fixes-on-windows-1011/"><u>Brother Printer Errors? Try These Fixes on Windows 10/11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bulk-crafting-stunning-visuals-integrate-canva-with-chatgpt-for-quick-creation/"><u>Bulk Crafting Stunning Visuals: Integrate Canva with ChatGPT for Quick Creation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-output-issue-on-printer/"><u>Color Output Issue on Printer</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-infinix-hot-40i-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Infinix Hot 40i</u></a></li>
<li><a href="https://printer-issues.techidaily.com/confused-settings-your-printer-misconfigured/"><u>Confused Settings: Your Printer Misconfigured</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-the-mystery-of-non-printing-machines/"><u>Dismantling the Mystery of Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-page-gaps-the-2024-printer-fix/"><u>End Page Gaps: The 2024 Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-efficiency-update-hp-officejet-firmware/"><u>Enhance Printing Efficiency: Update HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-fault-no-0x97-resolved/"><u>Epson Fault No: 0X97 - Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-xerox-halt-error-codes/"><u>Fix: Xerox Halt - Error Codes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-issue-with-installing-printer/"><u>Fixed Issue with Installing Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-pcs-error-b200/"><u>Fixed PC's Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-communication-error/"><u>Fixed Printer Communication Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fully-functional-page-to-page-printer-printing/"><u>Fully Functional, Page-to-Page Printer Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-every-page-printer-release/"><u>Get Every Page Printer Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-merging-hp-printer-with-home-computing-device/"><u>Guide: Merging HP Printer with Home Computing Device</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-infinix-smart-8-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Infinix Smart 8 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-poco-c65-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Poco C65 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-essential-techniques-for-saving-facebook-messenger-calls/"><u>In 2024, Essential Techniques for Saving Facebook Messenger Calls</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-and-connecting-printer-error-resolved/"><u>Installing and Connecting Printer Error Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-printer-disconnection/"><u>Instantly Resolve Printer Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-your-canon-printer-print-effortlessly-on-pc/"><u>Make Your Canon Printer Print Effortlessly on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-cdw-driver-installation-guide/"><u>MFC-9330 CDW Driver Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-hiccup-unexpected-printer-connection/"><u>Network Hiccup: Unexpected Printer Connection</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-shrink-your-videos-10-best-free-online-compression-tools-for-2024/"><u>New Shrink Your Videos 10 Best Free Online Compression Tools for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/offline-domains-leading-to-print-failures/"><u>Offline Domains Leading to Print Failures</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printing-blockade-oxc4eb827f/"><u>Overcoming HP Printing Blockade: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-constant-interruptions-from-spooler-service-in-win107/"><u>Preventing Constant Interruptions From Spooler Service in Win10/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-disconnected-swift-fix/"><u>Printer Disconnected: Swift Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-recovery-steps/"><u>Printer Recovery Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-to-brother-wireless-mfc-9330c/"><u>Quick Guide to Brother Wireless MFC-9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-slow-printers/"><u>Quick Remedies for Slow Printers</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-galaxy-a34-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Galaxy A34 5G</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-error-on-hp-printer-oxc4eb827f/"><u>Resolving Error on HP Printer: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-the-printer-setup-error-for-hp-deskjet-d1360-on-windows-systems/"><u>Resolving the Printer Setup Error for HP Deskjet D1360 on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-and-update-hp-officejet-4630-driver-edition/"><u>Secure & Update: HP Officejet 4630 Driver Edition</u></a></li>
<li><a href="https://extra-support.techidaily.com/smart-naming-solutions-leading-10-ai-name-generators-for-2024/"><u>Smart Naming Solutions  Leading 10 AI Name Generators for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-remove-hardware-printers/"><u>Step-By-Step Guide to Remove Hardware Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-hp-inkjets-download-and-upgrade-tips/"><u>Streamline Your HP Inkjets - Download and Upgrade Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-adding-hp-printer-to-computer-network/"><u>Tutorial: Adding HP Printer to Computer Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/understanding-and-solving-epson-printing-anomalies/"><u>Understanding and Solving Epson Printing Anomalies</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-secrets-of-pcl-xl-repairs/"><u>Unraveling the Secrets of PCL XL Repairs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-to-top-tier-mf4770n-drivers-for-windows-11w8w7/"><u>Upgrade to Top-Tier MF4770n Drivers for Windows 11/W8/W7</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-11-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-quick-fix-for-scanner-errors/"><u>Windows 11: Quick Fix for Scanner Errors</u></a></li>
</ul></div>
