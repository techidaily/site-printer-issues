---
title: Expedite Jammed Print Queue
date: 2024-08-22T09:41:54.517Z
updated: 2024-08-23T09:41:54.517Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Expedite Jammed Print Queue
excerpt: This Article Describes Expedite Jammed Print Queue
keywords: Print Spooler Troubleshooting,Printer Queue Management,Jammed Printer Remedies,Improve Print Queue Speed,Printer Hardware Faults,Prevent Printing Errors,Optimize Printer Performance
thumbnail: https://thmb.techidaily.com/6e8a41ece450d9380c701774f844497938589115375c3e1f4cbaa1de7ab99a22.jpg
---

## Expedite Jammed Print Queue

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
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
<li><a href="https://screen-capture.techidaily.com/new-comparing-the-leading-no-cost-video-communication-apps-iosandroid-for-2024/"><u>[New] Comparing the Leading No-Cost Video Communication Apps (iOS/Android) for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-direct-download-and-mp3-creation-for-streaming-video-files/"><u>[Updated] 2024 Approved  Direct Download & MP3 Creation for Streaming Video Files</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-expert-strategies-for-vocal-identity-on-instagram-for-2024/"><u>[Updated] Expert Strategies for Vocal Identity on Instagram for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-elevate-your-iphone-photos-top-8-picks/"><u>2024 Approved  Elevate Your Iphone Photos  Top 8 Picks</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-precision-no-download-leading-websites-turning-gif-into-video/"><u>2024 Approved  Precision No-Download  Leading Websites Turning GIF Into Video</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-oxc4eb827f-error-on-hp-devices/"><u>Addressing OXC4EB827F Error on HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-setup-for-air-glide/"><u>Brother MFC-9330CDW Setup for Air Glide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-woes-issue-fixed/"><u>Epson Printer Woes, Issue Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-0x00000709-cannot-set-default-printer-on-windows-solved/"><u>Error 0X00000709 Cannot Set Default Printer on Windows [Solved]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/five-tips-to-reignite-the-print-on-your-canon-printer-in-windows-11-os/"><u>Five Tips to Reignite the Print on Your Canon Printer in Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-windows-11-printer-power-reset-issues/"><u>Fix Windows 11 Printer Power Reset Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/frostfangs-frequency-prime-online-locations-for-tts-files-for-2024/"><u>Frostfang's Frequency  Prime Online Locations for TTS Files for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-can-i-access-iphone-pictures-that-seem-missing-despite-being-erased-discover-8-solutions/"><u>How Can I Access iPhone Pictures That Seem Missing Despite Being Erased? Discover 8 Solutions</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-iphone-15-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your iPhone 15 without Security Questions?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Oppo A2? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-d1360-printer-setup-failure-in-multiple-windows-versions/"><u>HP D1360 Printer Setup Failure in Multiple Windows Versions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-oneplus-11r-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track OnePlus 11R without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/meme-ology-the-science-of-popularizing-video-laughs-on-social-platforms/"><u>Meme-Ology  The Science of Popularizing Video Laughs on Social Platforms</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-cutting-edge-free-vob-video-editors-a-detailed-comparison-for-2024/"><u>New Cutting-Edge Free VOB Video Editors A Detailed Comparison for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574154094-no-more-unprinted-pages-on-hp-printer-now/"><u>No More Unprinted Pages on HP Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-absence-mp620-on-windows-10-os/"><u>Printer Driver Absence: MP620 on Windows 10 OS</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/professional-production-pro-the-alluring-tascam-cd-200bt-unveiled-and-reviews/"><u>Professional Production Pro: The Alluring Tascam CD-200BT Unveiled and Reviews</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnected-disabled-printer-service/"><u>Reconnected Disabled PRINTER Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regaining-access-a-guide-for-offline-printers/"><u>Regaining Access: A Guide for Offline Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-hp-printers-error-code-oxc4eb827f/"><u>Repairing HP Printer's Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-inkjet-error-on-windows-7/"><u>Resolved Inkjet Error on Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-inkjet-puzzled-printing/"><u>Resolving Inkjet: Puzzled Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-print-issue-with-brother-printer-in-windows-oses/"><u>Resolving No-Print Issue with Brother Printer in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-functionality-in-dormant-hp-multi-function-devices/"><u>Restoring Functionality in Dormant HP Multi-Function Devices</u></a></li>
<li><a href="https://fox-helps.techidaily.com/step-by-step-implementing-effective-transitions-on-inshot-for-2024/"><u>Step-by-Step  Implementing Effective Transitions on Inshot for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-journey-successfully-installing-a-hp-printer-on-windows/"><u>Stepwise Journey: Successfully Installing a HP Printer on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-shenanigans-unauthorized-printer-access/"><u>System Shenanigans: Unauthorized Printer Access</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-itel-s23plus-frp-by-drfone-android/"><u>The Updated Method to Bypass Itel S23+ FRP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unify-mf4770n-with-windows-environment-in-win11win87/"><u>Unify MF4770n with Windows Environment in Win11/Win8/7</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/vs-video-edition-gopro-hero-or-polaroid-cube/"><u>Vs. Video Edition  GoPro Hero or Polaroid Cube?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win2k-printer-response-error-resolution-guide/"><u>Win2K Printer Response: Error Resolution Guide</u></a></li>
</ul></div>
