---
title: Rapid Response to Queued Prints
date: 2024-10-06T21:46:01.441Z
updated: 2024-10-12T06:19:21.739Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Rapid Response to Queued Prints
excerpt: This Article Describes Rapid Response to Queued Prints
keywords: Quick Print Service,Speedy Print Delivery,Urgent Print Jobs Handling,Rapid Printer Queue Management,Expedited Print Processing,High-Speed Printer Services,Fast Print Order Turnaround
thumbnail: https://thmb.techidaily.com/08bfc68ca7424de532f1e4f97e0746486dfe84c1304de3ac8c4843a110a218e6.jpg
---

## Rapid Response to Queued Prints

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-creators-primer-to-understanding-major-content-providers/"><u>[New] In 2024, A Creator's Primer to Understanding Major Content Providers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-leveraging-the-power-of-visual-storytelling-in-fb-covers/"><u>[Updated] 2024 Approved Leveraging the Power of Visual Storytelling in FB Covers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tailored-timeline-management-best-twitter-unfollow-tools-ranked/"><u>[Updated] 2024 Approved Tailored Timeline Management Best Twitter Unfollow Tools Ranked</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-comparing-vsdc-to-best-screen-recording-software/"><u>[Updated] In 2024, Comparing VSDC to Best Screen Recording Software</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-secrets-of-crafting-captivating-instagram-videos/"><u>[Updated] In 2024, The Secrets of Crafting Captivating Instagram Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-excellent-video-and-picture-capture-for-iphones-and-androids-here/"><u>2024 Approved Excellent Video & Picture Capture for iPhones & Androids Here!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-connectivity-interruptions/"><u>Addressed Connectivity Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bypass-blank-pages-reactivating-your-canon-print-spooler/"><u>Bypass Blank Pages: Reactivating Your Canon Print Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-w11-scanner-output-issues/"><u>Fix W11 Scanner Output Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-office-efficiency-with-quick-fixes-for-printerpluslaptop-linkage/"><u>Harmonizing Office Efficiency with Quick Fixes for Printer+Laptop Linkage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-fixes-for-lags-in-printing/"><u>Immediate Fixes for Lags in Printing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-maximizing-impact-the-best-instagram-hashtag-list/"><u>In 2024, Maximizing Impact The Best Instagram Hashtag List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-mf4770n-support-software-windows-xp-7/"><u>Installing MF4770n Support Software Windows XP-7</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/navigating-instagrams-authenticity-rules-for-2024/"><u>Navigating Instagram’s Authenticity Rules for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rdr-reuniting-raid-arrays-drive-rescue/"><u>RDR: Reuniting RAID Arrays - Drive Rescue</u></a></li>
<li><a href="https://facebook.techidaily.com/swiftly-updating-personal-graphics-on-facebook-platform/"><u>Swiftly Updating Personal Graphics on Facebook Platform</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win711-hp-printer-network-recovery-tips/"><u>Win7/11 HP Printer Network Recovery Tips</u></a></li>
</ul></div>

