---
title: Expediting Clogged Print Order
date: 2024-08-15T03:16:17.806Z
updated: 2024-08-16T03:16:17.806Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expediting Clogged Print Order
excerpt: This Article Describes Expediting Clogged Print Order
keywords: Expedited Print Orders,Fast Track Print Processing,Urgent Printer Order Support,Resolving Print Job Delays,Speedy Order Fulfillment for Printing Services,Clogged Printer Issue Resolution,Accelerated Print Order Handling
thumbnail: https://thmb.techidaily.com/9009e7502f48b6a7260ab49e34d5c0ede3d2f18aac9b63fbba531138fcdb2ca3.jpg
---

## Expediting Clogged Print Order

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/compatibility-issue-canon-pixma-mp620-and-win10-not-linked/"><u>[Compatibility Issue] Canon Pixma MP620 & WIN10 Not Linked</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-fix-windows-810-printer-missing-issue/"><u>[Network Fix] Windows 8/10 Printer Missing Issue</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-compreeved-list-of-premium-androidiphone-slow-motion-video-tools/"><u>[New] Compreeved List of Premium Android/iPhone Slow Motion Video Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-effective-measures-to-block-pesky-video-ads-online/"><u>[New] Effective Measures to Block Pesky Video Ads Online</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-enhancing-iphone-image-clarity-and-focus/"><u>[New] Enhancing iPhone Image Clarity and Focus</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-essential-tips-for-picking-leading-free-srt-translation-tools/"><u>[New] Essential Tips for Picking Leading Free SRT Translation Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-essential-tips-for-effective-instagram-video-conversations/"><u>[New] In 2024, Essential Tips for Effective Instagram Video Conversations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-iphone-ringtones-a-guide-to-personalized-sound-choices/"><u>[New] IPhone Ringtones  A Guide to Personalized Sound Choices</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-mastering-multitasking-firefox-picture-in-picture-explained/"><u>[New] Mastering Multitasking  Firefox Picture-in-Picture Explained</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-optimal-android-apps-for-clear-screen-recordings-for-2024/"><u>[New] Optimal Android Apps for Clear Screen Recordings for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-step-by-step-method-for-personalizing-your-discord-avatar-for-2024/"><u>[New] Step-By-Step Method for Personalizing Your Discord Avatar for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-your-printer-has-experienced-an-unexpected-configuration-problem/"><u>[SOLVED] Your Printer Has Experienced an Unexpected Configuration Problem</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-innovate-your-farming-journey-with-these-stardews-top-7-mods/"><u>[Updated] Innovate Your Farming Journey with These Stardew's Top 7 Mods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-resolving-skewed-online-video-quality/"><u>[Updated] Resolving Skewed Online Video Quality</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-calendar-integration-for-efficient-google-meets/"><u>2024 Approved  Calendar Integration for Efficient Google Meets</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/7-critical-blunders-to-steer-clear-of-with-generative-ai-technologies/"><u>7 Critical Blunders to Steer Clear of with Generative AI Technologies</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-realme-gt-3-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Realme GT 3</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-visual-process-guide-on-setting-up-your-canon-printer/"><u>A Visual Process Guide on Setting up Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/accelerated-release-of-print-queued-tasks/"><u>Accelerated Release of Print Queued Tasks</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/accessing-audio-at-no-cost-the-ultimate-list-of-8-mp3-seekers-android-for-2024/"><u>Accessing Audio at No Cost  The Ultimate List of 8 MP3 Seekers (Android) for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/apple-iphone-11-pro-max-icloud-activation-lock-bypass-by-drfone-ios/"><u>Apple iPhone 11 Pro Max iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ceased-non-printer-error-on-hp-laserjet-pro-m637/"><u>Ceased Non-Printer Error on HP LaserJet Pro M637</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquering-printer-malfunction-after-win-10-fixes/"><u>Conquering Printer Malfunction After Win 10 Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-route-reconnecting-print-devices/"><u>Easy Route: Reconnecting Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-print-troubleshoot-0x97/"><u>Epson Print Troubleshoot: 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-canon-error-b200/"><u>Eradicated Canon Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-eradicated-printer-for-epson-works/"><u>Error Eradicated: Printer for Epson Works</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-to-resolve-when-and-why-you-cant-find-msvcr8cdll/"><u>Expert Tips to Resolve When and Why You Can't Find MSVCR8C.dll</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-wireless-printing-issue-with-hp-envy-5680v5/"><u>Fixed Wireless Printing Issue with HP Envy 5680V5</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-overcoming-silent-hp-network-printers/"><u>Guide to Overcoming Silent HP Network Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-revive-unresponsive-canon-printer/"><u>How to Revive Unresponsive Canon Printer?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-and-install-a-canon-printer-with-photos/"><u>How to Set Up and Install a Canon Printer with Photos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-stop-life360-from-tracking-you-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/improve-print-quality-fixing-win10-drivers/"><u>Improve Print Quality: Fixing WIN10 Drivers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pro-anglers-choice-the-top-5-cameras-for-fishing/"><u>In 2024, Pro Angler's Choice  The Top 5 Cameras For Fishing</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, The Best iSpoofer Alternative to Try On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/innovative-strategies-for-revamping-your-video-covers-on-fb-for-2024/"><u>Innovative Strategies for Revamping Your Video Covers on FB for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-software-for-hp-officejet-4630-installation/"><u>Latest Software for HP Officejet 4630 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-art-of-fixing-printer-problems-after-win-10/"><u>Mastering the Art of Fixing Printer Problems After Win 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-not-responding/"><u>Mended Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-responsive-printer-halted-what-to-do/"><u>Non-Responsive Printer Halted, What to Do?</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcome-cod-black-ops-cold-war-not-starting-on-pc-effective-fixes-revealed/"><u>Overcome Cod: Black Ops Cold War Not Starting on PC – Effective Fixes Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-paper-jams-in-copiers/"><u>Preventing Paper Jams in Copiers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-drive-issue-cant-connect-on-pc/"><u>Printer Drive Issue: Can't Connect on PC</u></a></li>
<li><a href="https://driver-install.techidaily.com/professional-steinberg-drivers-bundle/"><u>Professional Steinberg Drivers Bundle</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/quick-tips-to-produce-quality-thumbnails-fast-for-2024/"><u>Quick Tips to Produce Quality Thumbnails Fast for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnected-print-spooler-in-win7/"><u>Reconnected Print Spooler in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-scanner-link-to-pc-post-update-in-windows-10/"><u>Regaining Scanner Link to PC Post-Update in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-frequent-spooler-halt-issues-on-pcs-running-windows/"><u>Resolving Frequent Spooler Halt Issues on PCs Running Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-intermittent-printer-spooler-halt-in-win-117/"><u>Resolving Intermittent Printer Spooler Halt in Win 11/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversing-printer-freezes/"><u>Reversing Printer Freezes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-windows-9598-print-jobs-that-wont-respond/"><u>Revive Windows 95/98 Print Jobs That Won't Respond</u></a></li>
<li><a href="https://printer-issues.techidaily.com/second-pc-same-printer-issue-resolved/"><u>Second PC, Same Printer Issue? Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-error-epson-fault-code/"><u>Solving Error: Epson Fault Code</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speed-up-unresolved-printer-queue-issue/"><u>Speed Up Unresolved Printer Queue Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-repair-for-xerox-error-alert-0x1/"><u>Swift Repair for Xerox Error Alert 0X1</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tailoring-snaps-the-science-behind-compelling-advertising/"><u>Tailoring Snaps  The Science Behind Compelling Advertising</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-xiaomi-redmi-k70e-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Xiaomi Redmi K70E</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-fails-to-respond-post-suspend-win7/"><u>USB Printer Fails to Respond Post Suspend, Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-fails-to-recognize-pixma-mp620-printer-driver/"><u>Windows 10 Fails to Recognize Pixma MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winnt2000-reactivate-sluggish-printer-response/"><u>WinNT/2000: Reactivate Sluggish Printer Response</u></a></li>
</ul></div>
