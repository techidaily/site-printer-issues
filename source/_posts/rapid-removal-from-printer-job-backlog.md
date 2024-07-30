---
title: Rapid Removal From Printer Job Backlog
date: 2024-07-29T00:30:52.333Z
updated: 2024-07-30T00:30:52.333Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Removal From Printer Job Backlog
excerpt: This Article Describes Rapid Removal From Printer Job Backlog
keywords: Rapid Printer Job Clearing,Fast Removal of Printer Backlog,Quick Elimination of Print Jobs Queue,Efficient Printer Job Management,Reduce Printer Job Accumulation,Printer Backlog Resolution,Unclogging Printer Print Job Backlog
thumbnail: https://thmb.techidaily.com/3b5dbab902dc8db71b72fe778c491655a451dd9fd6fc0286da7f19ebe4c291dd.jpg
---

## Rapid Removal From Printer Job Backlog

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-the-ultimate-checklist-tracking-igtv-analytics-for-2024/"><u>[New] The Ultimate Checklist  Tracking IGTV Analytics for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-2023-facebook-short-videos-and-everything-about-them/"><u>[Updated] 2024 Approved  2023 | Facebook Short Videos and Everything About Them</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-from-obscurity-to-star-in-3-simple-steps-for-2024/"><u>[Updated] From Obscurity to Star in 3 Simple Steps for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-macs-top-screen-recorders-face-off-bandicam-vs-camtasia/"><u>[Updated] Mac's Top Screen Recorders Face-Off  Bandicam vs Camtasia</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-issue-mp620-driver-not-detected/"><u>[Windows Issue] MP620 Driver Not Detected</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-elevating-your-macro-videos-a-comprehensive-checklist/"><u>2024 Approved  Elevating Your Macro Videos  A Comprehensive Checklist</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-simple-steps-to-make-your-canon-printer-work-again/"><u>5 Simple Steps to Make Your Canon Printer Work Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-hp-printer-fault-0xoxc4eb827f/"><u>Addressing HP Printer Fault: 0XOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/advanced-techniques-to-setup-hp-print-devices-in-win10-os/"><u>Advanced Techniques to Setup HP Print Devices in Win10 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-printing-speed-instantly/"><u>Boost Printing Speed Instantly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-your-output-v305-aio-driver-enhancement-in-win7/"><u>Boost Your Output: V305 AIO Driver Enhancement in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-drive-efficiency-mf4770n-and-windows-systems/"><u>Boosting Drive Efficiency: MF4770n & Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-faulty-connectivity-in-printers/"><u>Diagnosing Faulty Connectivity in Printers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-c210-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from C210</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-of-the-line-for-non-printed-pages/"><u>End of the Line for Non-Printed Pages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-eliminated/"><u>Error B200 Eliminated</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-siblings-printer-remains-unreachable/"><u>Fixing: Sibling's Printer Remains Unreachable</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-y100i-power-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Y100i Power 5G</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-canon-printer-a-visual-walkthrough/"><u>How to Set Up a Canon Printer: A Visual Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-4630-driver-download-and-update/"><u>HP Officejet 4630 Driver Download & Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-officejet-pro-8600-printer-manager-for-windows-systems/"><u>HP Officejet Pro 8600 Printer Manager for Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-it-running-smoothly-update-dells-inkjet-aio-on-windows-7/"><u>Keep It Running Smoothly: Update Dell's Inkjet AIO on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-fixed-version-printing-whole-documents/"><u>New Fixed Version: Printing Whole Documents</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-printer-added-operation-without-issues/"><u>New Printer Added: Operation Without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-non-printing-in-canon-printers-windows-edition/"><u>Overcome Non-Printing in Canon Printers, Windows Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-spooler-failure/"><u>Overcome Print Spooler Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-installation-inkjet-printer-error-fixed/"><u>Post Installation, Inkjet Printer Error Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-compatibility-windows-11-and-canons-mp620/"><u>Printer Compatibility: Windows 11 and Canon's MP620</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-unnecessary-printers-in-os/"><u>Purging Unnecessary Printers in OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-linking-your-canon-to-wi-fi/"><u>Quick Guide: Linking Your Canon to Wi-Fi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-turn-on-your-disconnected-canon-printer/"><u>Quick Guide: Turn On Your Disconnected Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tip-uninstalling-default-print-devices/"><u>Quick Tip: Uninstalling Default Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-link-between-sibling-and-online-printer/"><u>Restoring Link Between Sibling and Online Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-windows-11-printer-suddenly-stopped-working/"><u>Revive Your Windows 11 Printer Suddenly Stopped Working</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-brother-printer-print-operation-in-windows-oses/"><u>Streamlining Brother Printer Print Operation in Windows OSes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-reducing-shakiness-on-your-gopro-movie/"><u>The Ultimate Guide to Reducing Shakiness on Your GoPro Movie</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-guide-your-canon-printer-wont-print/"><u>Troubleshooting Guide: Your Canon Printer Won't Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-your-non-printing-canon-into-a-reliable-device-with-tips/"><u>Turn Your Non-Printing Canon Into a Reliable Device with Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlocking-ig-potential-strategies-for-accumulating-1000plus-likesmonth-for-2024/"><u>Unlocking IG Potential  Strategies for Accumulating 1,000+ Likes/Month for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-leads-to-non-printer-functionality/"><u>Win 11 Update Leads to Non-Printer Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-troubleshoot-non-functional-printer/"><u>Windows 11: Troubleshoot Non-Functional Printer</u></a></li>
</ul></div>
