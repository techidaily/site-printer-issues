---
title: Rapid Fixation of Stuck Print Workqueue
date: 2024-07-29T00:27:57.289Z
updated: 2024-07-30T00:27:57.289Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Fixation of Stuck Print Workqueue
excerpt: This Article Describes Rapid Fixation of Stuck Print Workqueue
keywords: Rapid Workflow Solutions,Stuck Print Queue Remediation,Print Workflow Optimization,Quick Stuck Print Queue Resolution,Effective Print Queue Management,Workflow Bottleneck Solutions in Printing,Streamlining Stuck Print Processes
thumbnail: https://thmb.techidaily.com/443fa3d21137649dff0319f1c3c3070702e32a7b2f673e094959a8fdb4cdbd5b.jpg
---

## Rapid Fixation of Stuck Print Workqueue

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
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-make-fortnite-thumbnail-for-free-and-easy/"><u>[New] 2024 Approved  How to Make Fortnite Thumbnail for Free and Easy</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expertly-lit-the-17-must-haves-for-youtubers/"><u>[Updated] Expertly Lit  The 17 Must-Haves for Youtubers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1716069145478-updated-in-2024-silent-blades-and-righteous-honor-your-next-game-adventure-awaits/"><u>[Updated] In 2024, Silent Blades & Righteous Honor  Your Next Game Adventure Awaits!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-picsart-guide-discreetly-mask-faces/"><u>[Updated] Picsart Guide  Discreetly Mask Faces</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-online-destinations-for-sparkling-and-metallic-letters/"><u>2024 Approved  Best Online Destinations for Sparkling and Metallic Letters</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bringing-your-disconnected-hp-printer-online-in-w8/"><u>Bringing Your Disconnected HP Printer Online in W8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-fan-setup-instructions/"><u>Brother CDW Duo Fan Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-wireless-mfc-9330cdw-instructions/"><u>Brother Wireless MFC-9330CDW Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnosing-ink-and-paper-feed-issues-in-hp/"><u>Diagnosing Ink and Paper Feed Issues in HP</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-video-game-top-tips-for-perfect-live-thumbnails/"><u>Elevate Your Video Game  Top Tips for Perfect Live Thumbnails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-repeated-print-job-failures-guide-for-windows-107-users/"><u>End Repeated Print Job Failures: Guide for Windows 10/7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-your-printing-experience-with-canon-windows-10-tips/"><u>Enhance Your Printing Experience with Canon, Windows 10 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printer-driver-issues-on-windows-10/"><u>Fix Printer Driver Issues on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-printer-service-spooler-issues/"><u>Fixing Non-Operational Printer Service (Spooler) Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-online-offline-print-status-anomaly/"><u>Fixing Online-Offline Print Status Anomaly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hack-your-way-through-pcl-xl-troubles/"><u>Hack Your Way Through PCL XL Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-prevent-print-service-interruptions-on-w7w10w11/"><u>How to Prevent Print Service Interruptions on W7/W10/W11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-boosting-video-reach-on-youtube-an-in-depth-guide-to-seo-techniques/"><u>In 2024, Boosting Video Reach on YouTube  An In-Depth Guide to SEO Techniques</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-depth-review-is-aurora-revolutionary-in-2024/"><u>In-Depth Review  Is Aurora Revolutionary, In 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-paper-jamming-concern/"><u>Mended Paper Jamming Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/monochrome-output-despite-color-settings/"><u>Monochrome Output Despite Color Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-the-setup-of-hp-envy-printers/"><u>Navigating the Setup of HP Envy Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-like-a-pro-3-upgrades-to-link-your-printer-and-laptop-seamlessly/"><u>Print Like a Pro: 3 Upgrades to Link Your Printer & Laptop Seamlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-issue-not-showing-up-in-win-810/"><u>Printer Issue: Not Showing Up in Win 8/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-link-functional-print-device/"><u>Quick Link: Functional Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversed-printing-mishaps-hp-printer-now-solid-and-sure/"><u>Reversed Printing Mishaps: HP Printer Now Solid and Sure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revived-networked-printer-access/"><u>Revived Networked Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-mf4770n-functions-on-w11w8w7-os/"><u>Streamlining MF4770n Functions on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-solutions-to-printer-delays/"><u>Swift Solutions to Printer Delays</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-oneplus-11r-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When OnePlus 11R Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>