---
title: Reactivate Idle Printing Queue Task
date: 2024-09-24T18:28:35.447Z
updated: 2024-09-26T04:54:40.006Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Reactivate Idle Printing Queue Task
excerpt: This Article Describes Reactivate Idle Printing Queue Task
keywords: Reactivate IDLE Printer Queue,Idle Printing Queue Management,Resume Idle Print Jobs,Restart Printer Queue Task,Printing Queue Idle Issue Resolution,Enable Idle Printer Tasks,Revive Non-Active Printer Queue
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Reactivate Idle Printing Queue Task

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-video-quality-edge-mirrorless-versus-dslr-cameras/"><u>[New] Video Quality Edge Mirrorless Versus DSLR Cameras</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/1725288258213-2022dvd/"><u>2022最强大的DVD到数字化转换技术：终极指南</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-steps-to-crafting-powerful-end-of-episode-notes/"><u>2024 Approved Steps to Crafting Powerful End-of-Episode Notes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brisk-release-from-print-waitlist/"><u>Brisk Release From Print Waitlist</u></a></li>
<li><a href="https://article-files.techidaily.com/detailed-elucinasion-the-google-podcast-application-explained/"><u>Detailed Elucinasion The Google Podcast Application Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-scanner-activation-issue-after-installing-updates/"><u>Fix Scanner Activation Issue After Installing Updates</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-craftsmanship-in-marvellous-marvel-creation/"><u>In 2024, Craftsmanship in Marvellous Marvel Creation</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-lane-the-funniest-youtubers-for-a-good-time-for-2024/"><u>Laughing Lane The Funniest YouTubers for a Good Time for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/microvid-virtuoso/"><u>MicroVid Virtuoso</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-cease-spooler-halt-on-w710-11-windows/"><u>Quick Guide: Cease Spooler Halt on W7/10, 11 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-guide-setting-up-a-canon-printer/"><u>Quick Guide: Setting Up a Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-scanner-troubleshooting-guide-for-win10-users/"><u>Reconnect Scanner: Troubleshooting Guide for Win10 Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-narzo-60x-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Narzo 60x 5G</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-noise-level-fluctuation-in-hp-officejet-pro-x100/"><u>Repaired Noise Level Fluctuation in HP Officejet Pro X100</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-steps-for-stubborn-printer/"><u>Troubleshooting Steps for Stubborn Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-printer-disconnected-from-network/"><u>Troubleshooting: Printer Disconnected From Network</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/turning-off-the-speaking-feature-tips-for-managing-your-samsung-tvs-voice-control/"><u>Turning Off the Speaking Feature: Tips for Managing Your Samsung TV's Voice Control</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-problems-no-access-to-hp-printer-drivers/"><u>Windows Problems: No Access to HP Printer Drivers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtubes-role-in-todays-dynamic-educational-landscape-for-2024/"><u>YouTube's Role in Today's Dynamic Educational Landscape for 2024</u></a></li>
</ul></div>

