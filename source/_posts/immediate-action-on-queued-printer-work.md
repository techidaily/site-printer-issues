---
title: Immediate Action on Queued Printer Work
date: 2024-07-29T00:31:34.736Z
updated: 2024-07-30T00:31:34.736Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Immediate Action on Queued Printer Work
excerpt: This Article Describes Immediate Action on Queued Printer Work
keywords: Immediate Print Job Cancellation,Printer Queue Management Tips,Fixing Stuck Printer Workflows,Quick Solution for Queued Print Jobs,Resolve Printer Queue Delays,Immediate Action,Prevent Long Queue Print Jobs
thumbnail: https://thmb.techidaily.com/b5e9ddde4e68e5c468b12c2fce264f22eb978dc955e335250b1f4d060c7be8f8.jpg
---

## Immediate Action on Queued Printer Work

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-becoming-a-master-of-instagram-auditory-aesthetics/"><u>[New] In 2024, Becoming a Master of Instagram Auditory Aesthetics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-from-script-to-screen-animating-stories-using-wmm/"><u>[New] In 2024, From Script to Screen  Animating Stories Using WMM</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-conversion-handbook-srt-to-various-formats/"><u>[New] Ultimate Conversion Handbook  SRT to Various Formats</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-hp-printer-driver-is-unavailable-on-windows-1110/"><u>[Solved] HP Printer Driver Is Unavailable on Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-canon-mp620-unsupported-in-win11/"><u>[Troubleshooting] Canon MP620 Unsupported in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-alert-canon-printer-not-detected-in-win10/"><u>[Update Alert] Canon Printer Not Detected in WIN10</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-transform-your-memories-into-engaging-facebook-slides/"><u>[Updated] 2024 Approved  Transform Your Memories Into Engaging Facebook Slides</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-are-apples-new-processors-revolutionizing-editing-tech/"><u>2024 Approved  Are Apple's New Processors Revolutionizing Editing Tech?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-operability-win11w8w7-via-mf4770n-update/"><u>Boosting Operability: Win11/W8/W7 via MF4770n Update</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/brand-visibility-boosted-by-instagram-photowatermarking-for-2024/"><u>Brand Visibility Boosted by Instagram Photowatermarking for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-pinnacle-clarity-to-your-w11-desktop-wallpaper/"><u>Bringing Pinnacle Clarity to Your W11 Desktop Wallpaper</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-get-my-canon-printer-on-board/"><u>Can't Get My Canon Printer on Board</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-searching-for-driver-on-win11/"><u>Canon Pixma MP620: Searching for Driver on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cdw-duo-fan-guide-for-brother-9330c/"><u>CDW Duo Fan Guide for Brother 9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combat-brother-printer-not-printing-quagmire-reinstating-functionality-on-windows/"><u>Combat Brother Printer Not Printing Quagmire, Reinstating Functionality on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-printer-on-windows-instantly/"><u>Disabling Printer on Windows Instantly</u></a></li>
<li><a href="https://fox-helps.techidaily.com/elevate-your-drone-videos-with-the-best-editing-programs-for-2024/"><u>Elevate Your Drone Videos with the Best Editing Programs for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-photo-printer-over-printing-white-paper/"><u>Epson Photo Printer: Over-Printing White Paper</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-print-resuming/"><u>Epson's Print Resuming</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-tips-for-fixing-windows-11-printer/"><u>Essential Tips for Fixing Windows 11 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-brother-printer-print-malfunction-with-simple-steps/"><u>Fix Brother Printer Print Malfunction with Simple Steps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-disconnected-print-service/"><u>Fixing Disconnected Print Service</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-xiaomi-redmi-note-13-pro-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Xiaomi Redmi Note 13 Pro 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-motorola-moto-g84-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Motorola Moto G84 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-achieves-zero-blank-page-mishaps/"><u>HP Printer Achieves Zero Blank Page Mishaps</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-xiaomi-redmi-note-13-pro-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Xiaomi Redmi Note 13 Pro 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-sony-xperia-5-v-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Sony Xperia 5 V with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inaccessible-domains-causing-print-errors/"><u>Inaccessible Domains Causing Print Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-printer-setup-with-canon-guided-examples/"><u>Instant Printer Setup with Canon - Guided Examples</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-integration-boost-system-software-updates-windows/"><u>MF4770n Integration Boost: System Software Updates Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-blank-pages-on-epson/"><u>No More Blank Pages on Epson</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-flickering-on-hp-laptops/"><u>Overcoming Flickering on HP Laptops</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-ink-dry-up-a-printers-cry-for-help/"><u>Overcoming Ink Dry-Up: A Printer's Cry for Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-printing-hurdles-on-windows-11/"><u>Overcoming Printing Hurdles on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-active-directory-service-unavailable/"><u>PPrintError: Active Directory Service Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-halted-win10-doesnt-recognize-mp620-driver/"><u>Printer Setup Halted: WIN10 Doesn't Recognize MP620 Driver</u></a></li>
<li><a href="https://extra-information.techidaily.com/prioritize-savings-with-the-best-6-affordable-camera-brands/"><u>Prioritize Savings with the Best 6 Affordable Camera Brands</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-connection-remedy/"><u>Quick Printer Connection Remedy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-print-services-for-your-canon-device/"><u>Reclaiming Print Services for Your Canon Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-and-resume-a-step-by-step-guide-for-printers/"><u>Reconnect and Resume: A Step-by-Step Guide for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-clear-document-reception-from-hp-printer/"><u>Restoring Clear Document Reception From HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-deadprint-a-step-by-step-guide/"><u>Reviving a Deadprint: A Step-by-Step Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-clearance-of-stalled-print-queue/"><u>Speedy Clearance of Stalled Print Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamline-your-screen-time-step-by-step-towards-a-well-curated-playlist-for-2024/"><u>Streamline Your Screen Time  Step-by-Step Towards a Well-Curated Playlist for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-story-unshackling-printer-from-update-chains/"><u>Success Story: Unshackling Printer From Update Chains</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-printer-performance-tips/"><u>Swift Printer Performance Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/syncing-up-hp-printer-with-pc-settings/"><u>Syncing Up HP Printer with PC Settings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tailored-treasure-troves-the-ultimate-list-of-online-box-sellers-for-2024/"><u>Tailored Treasure Troves  The Ultimate List of Online Box Sellers for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-to-unblock-print-spoolers/"><u>Tips to Unblock Print Spoolers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-ad-service-interrupted/"><u>Unable To Print: AD Service Interrupted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574150252-unexpected-printer-error-alert/"><u>Unexpected Printer Error Alert!</u></a></li>
</ul></div>
