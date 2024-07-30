---
title: Accelerate Queued Print Processes
date: 2024-07-29T00:31:11.824Z
updated: 2024-07-30T00:31:11.824Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Queued Print Processes
excerpt: This Article Describes Accelerate Queued Print Processes
keywords: Accelerate Printing Speed,Improve Print Workflow Efficiency,Queue Management for Printers,Reduce Queued Printing Times,Optimize Print Job Scheduling,Enhance Printer Process Speed,Streamline Printing Workflows
thumbnail: https://thmb.techidaily.com/2453bc5c0249af0de921ee166f14d8e128b375913b07ba9cca730be764e6c410.jpg
---

## Accelerate Queued Print Processes

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
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

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/alert-windows-10-print-queue-offline/"><u>[ALERT] Windows 10: Print Queue Offline</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-streamlining-short-film-previews-for-channels/"><u>[New] 2024 Approved  Streamlining Short Film Previews for Channels</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-kinemaster-made-memes/"><u>[New] The Art of KineMaster-Made Memes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-integrating-pre-recorded-content-into-facebook-live-shows/"><u>[Updated] Integrating Pre-Recorded Content Into Facebook Live Shows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-swift-playback-on-instagram-videos-mobiledesktop/"><u>[Updated] Swift Playback on Instagram Videos (Mobile/Desktop)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-adding-videos-to-written-work-a-budget-friendly-way/"><u>2024 Approved  Adding Videos to Written Work  A Budget-Friendly Way</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-pro-mic-tech-review-best-9-online-recorders-uncovered/"><u>2024 Approved  Pro Mic Tech Review  Best 9 Online Recorders Uncovered</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-itel-p40-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Itel P40 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-page-queue-in-hp-printer-errors/"><u>Clearing Page Queue in HP Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-solve-offline-canon-printer-issues/"><u>Connectivity Woes? Solve Offline Canon Printer Issues</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/elevate-your-content-11-steps-to-amplify-fb-video-performance-for-2024/"><u>Elevate Your Content  11 Steps to Amplify FB Video Performance for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-the-non-print-on-canon-here-are-your-top-5-fixes-for-windows-11-users/"><u>Eliminate the Non-Print on Canon - Here Are Your Top 5 Fixes for Windows 11 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-epson-misprint-mistake/"><u>Ending Epson Misprint Mistake</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-error-b200/"><u>Eradicated Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-x97-on-epson-unraveled-solution/"><u>Error X97 on Epson - Unraveled Solution</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-cascading-error-messages-with-printers/"><u>Fixing Cascading Error Messages with Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-xiaomi-13t-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-uninstall-a-print-driver-in-windows/"><u>How to Uninstall a Print Driver in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-reno-9a-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo Reno 9A to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-installation-woes-on-windows-11/"><u>MP620 Printer Installation Woes on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-epson-paper-jam-signals/"><u>Navigating Through Epson Paper Jam Signals</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-trends-in-technology-3-solutions-connecting-laptops-and-hp-printers/"><u>New Trends in Technology - 3 Solutions Connecting Laptops & HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/perfect-print-job-across-all-printers/"><u>Perfect Print Job Across All Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574021414-print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-crisis-averted-zeroing-out-error-0x00000709/"><u>Printer Setup Crisis Averted - Zeroing Out Error (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-unwillingness-for-full-color-printing/"><u>Printer's Unwillingness for Full-Color Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-resumed-in-hp-all-in-one-after-network-fix/"><u>Printing Resumed in HP All-in-One After Network Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-your-silent-canon-printer-now/"><u>Reconnect Your Silent Canon Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-mf4770n-compatibility-in-win1187/"><u>Revitalize Your MF4770n Compatibility in Win11/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-address-sibling-printer-unresponsiveness/"><u>Strategies to Address Sibling Printer Unresponsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-non-printing-your-guide-to-fixing-brother-printer-on-windows/"><u>Streamline Non-Printing: Your Guide to Fixing Brother Printer on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-sony-xperia-1-v-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Sony Xperia 1 V FRP Bypass</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblock-and-propel-printers-fast/"><u>Unblock and Propel Printers Fast</u></a></li>
<li><a href="https://techidaily.com/unlock-locked-iphone-15-plus-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>Unlock locked iPhone 15 Plus without Passcode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-pages-galore-affected-by-epson-printer/"><u>White Pages Galore: Affected by Epson Printer</u></a></li>
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-samsung-galaxy-s23plus-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Samsung Galaxy S23+? Fixed | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-compatibility-boost-with-mf4770n-update/"><u>Windows Compatibility Boost with MF4770n Update</u></a></li>
</ul></div>
