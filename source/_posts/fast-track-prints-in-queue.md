---
title: Fast-Track Prints in Queue
date: 2024-09-09T01:24:03.002Z
updated: 2024-09-10T01:24:03.002Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fast-Track Prints in Queue
excerpt: This Article Describes Fast-Track Prints in Queue
keywords: Fast Track Printing Services,Quick Print Queue Management,Fast-Track Print Order Processing,Rapid Prints Queue Priority Service,High-Speed Print Services for Busy Businesses,Speedy Queue Management Printing,Express Prints with Priority Queue System
thumbnail: https://thmb.techidaily.com/13464bbf7702e727674e34228111122f1f619fb5b014ebf3cf5f5ddd4c2dec0d.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fast-Track Prints in Queue

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/driver-missing-canon-pixma-mp620-printer-not-finding-win10/"><u>[Driver Missing] Canon Pixma MP620 Printer Not Finding WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problems-windows-xp-10-printer-vanishes/"><u>[Network Problems] Windows XP-10, Printer Vanishes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-21-innovative-solutions-for-free-recording-of-online-meetings/"><u>[New] 2024 Approved  21 Innovative Solutions for Free Recording of Online Meetings</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-night-of-the-living-dead-games-an-epic-selection/"><u>[New] 2024 Approved  Night of the Living Dead Games  An Epic Selection</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-global-perspective-your-favorite-travel-youtubers/"><u>[New] A Global Perspective  Your Favorite Travel Youtubers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-seamless-blend-inserting-music-into-fb-video-posts/"><u>[New] In 2024, Seamless Blend  Inserting Music Into FB Video Posts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-transforming-fb-videos-into-mp3-files/"><u>[New] In 2024, Transforming Fb Videos Into MP3 Files</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-pioneering-techniques-to-transform-your-obs-studio-projects/"><u>[Updated] 2024 Approved  Pioneering Techniques to Transform Your OBS Studio Projects</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-live-recording-mastery-with-innovative-webcams-explored-for-2024/"><u>[Updated] Live Recording Mastery with Innovative WebCams Explored for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-prime-facebook-extra-tools-secure-file-grabber-firefox-version-for-2024/"><u>[Updated] Prime Facebook Extra Tools  Secure File Grabber, Firefox Version for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-strategies-for-stumbling-upon-covert-youtube-videos/"><u>[Updated] Strategies for Stumbling Upon Covert YouTube Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-enhancing-immersion-prepping-for-oculus/"><u>2024 Approved  Enhancing Immersion  Prepping for Oculus</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-vidmore-screen-recorder-how-to-use-it/"><u>2024 Approved  Vidmore Screen Recorder - How to Use It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-common-canon-printer-woes-in-windows-10-settings/"><u>Address Common Canon Printer Woes in Windows 10 Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/auditory-accents-integrating-tracks-into-video-on-modern-windows/"><u>Auditory Accents  Integrating Tracks Into Video on Modern Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-windows-10s-canon-printer-operation-success-rate/"><u>Boost Windows 10'S Canon Printer Operation Success Rate</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combating-printers-error-x97-in-epson/"><u>Combating Printer's Error X97 in Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-incessant-print-service-pauses-in-win-systems/"><u>End Incessant Print Service Pauses in Win Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-paper-shortage-2024-printer-update/"><u>Ending Paper Shortage: 2024 Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-document-saving-functionality-in-windows-11/"><u>Enhance Document Saving Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensuring-smooth-performance-mf4770n-in-win11win8w7/"><u>Ensuring Smooth Performance: MF4770n in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-repair-success/"><u>Epson Printer Repair Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-on-epson-dispelled/"><u>Error Code 0X97 on Epson Dispelled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-b200/"><u>Error Resolution: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guiding-through-printer-malfunction-fixes/"><u>Guiding Through Printer Malfunction Fixes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-vivo-y200e-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Vivo Y200e 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-oppo-reno-10-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Oppo Reno 10 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-on-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number On iPhone 13 Pro Max</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inability-to-print-in-full-colors/"><u>Inability to Print in Full Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-drivers-enhance-windows-11-8-7-integration/"><u>MF4770n Drivers - Enhance Windows 11, 8, 7 Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-canons-print-to-wi-fi-journey/"><u>Navigating Canon's Print to Wi-Fi Journey</u></a></li>
<li><a href="https://printer-issues.techidaily.com/never-again-the-end-of-blank-printouts/"><u>Never Again: The End of Blank Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-error-code-oxc4eb827f/"><u>Overcoming HP Printer Error Code: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-paper-queue-freeze-on-windows-oses-10-11-and-7/"><u>Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restarting-network-drivers-fixes-hp-printer/"><u>Restarting Network Drivers Fixes HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-sibling-print-device-from-online-standby-mode/"><u>Reviving Sibling Print Device From Online Standby Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionize-your-printing-3-futuristic-solutions-to-connect-hp-and-laptop/"><u>Revolutionize Your Printing: 3 Futuristic Solutions to Connect HP & Laptop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-fix-hp-printer-network-errors/"><u>Steps to Fix HP Printer Network Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-reconnect-offline-brother-printer/"><u>Steps to Reconnect Offline Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-and-fix-spooler-error-in-win-7-printers/"><u>Stop and Fix Spooler Error in Win 7 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-trouble-incorrect-printer-configuration/"><u>Tech Trouble: Incorrect Printer Configuration</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-infinix-zero-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/the-essential-guide-to-emoji-memoji-animoji-and-bitmoji/"><u>The Essential Guide to Emoji, Memoji, Animoji, and Bitmoji</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-hidden-printer-error-messages/"><u>Unveiling Hidden Printer Error Messages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/what-to-do-when-your-printer-is-offline/"><u>What To Do When Your Printer Is Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-nightmares-solutions-here/"><u>Windows 11 Printer Nightmares? Solutions Here</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-3x-print-hiccup-quick-fixes-needed/"><u>Windows 3.x Print Hiccup - Quick Fixes Needed</u></a></li>
</ul></div>
