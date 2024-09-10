---
title: "Unable To Print: AD Service Interrupted"
date: 2024-09-09T01:24:02.711Z
updated: 2024-09-10T01:24:02.711Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Unable To Print: AD Service Interrupted"
excerpt: "This Article Describes Unable To Print: AD Service Interrupted"
keywords: Unable To Print Errors,AD Service Interruption Troubleshooting,Printer Connectivity Issues,Common Problems With Active Directory,How to Fix Printing Services Disruption,Solutions For Print Server Downtime,Synchronization Issue with AD and Printing Devices
thumbnail: https://thmb.techidaily.com/4ba28a3dd24936be14c010b9b472cc28e6164f2ddc628c9763c3b8ea3ee12f42.png
---

## Unable To Print: AD Service Interrupted

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Close the Services window and check if you could print files successfully.  

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115934/19272" target="_top" id="2115934">
  <img src="//a.impactradius-go.com/display-ad/19272-2115934" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115934/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) Close the Registry Editor window and check to see if you could print files successfully.

* [printer](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-footage.techidaily.com/new-elevating-your-videos-visual-impact-youtubthumbnail-design-on-macos-for-2024/"><u>[New] Elevating Your Video's Visual Impact  YoutubThumbnail Design on macOS for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-real-time-recording-tech-that-never-delays-you-for-2024/"><u>[New] Real-Time Recording Tech That Never Delays You for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-user-friendly-steps-for-storing-google-voice-conversations-for-2024/"><u>[New] User-Friendly Steps for Storing Google Voice Conversations for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-chuckle-hour-on-tiktok-joke-and-riddle-roundup-for-laughter-lovers-for-2024/"><u>[Updated] Chuckle Hour on TikTok  Joke & Riddle Roundup for Laughter Lovers for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-from-playtime-to-peak-time-top-gaming-women-in-the-digital-space/"><u>[Updated] In 2024, From Playtime to Peak Time  Top Gaming Women in the Digital Space</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-unleash-potential-best-gaming-content-to-elevate-your-channel/"><u>[Updated] In 2024, Unleash Potential  Best Gaming Content to Elevate Your Channel</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-a-step-by-step-guide-to-stunning-image-artistry-mosaics/"><u>2024 Approved  A Step-By-Step Guide to Stunning Image Artistry Mosaics</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-insightful-cloud-costs-price-comparison-and-recommendations/"><u>2024 Approved  Insightful Cloud Costs  Price, Comparison & Recommendations</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-mp4-file-editing-removing-sound-tracks/"><u>2024 Approved MP4 File Editing Removing Sound Tracks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-bug-fixed-ready-to-go/"><u>B200 Bug Fixed, Ready to Go!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-with-hp-print-on-w7-resolved/"><u>Connectivity Woes with HP Print on W7 Resolved</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-leading-workout-management-applications-for-a-healthier-2024/"><u>Discover the Leading Workout Management Applications for a Healthier 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dispelling-hp-printers-fatal-mistake-0xoxc4eb827f/"><u>Dispelling HP Printer's Fatal Mistake 0xOXC4EB827F</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-canon-scanning-software-for-windows-computers-no-cost/"><u>Download Canon Scanning Software for Windows Computers - No Cost</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-wireless-connectivity-for-hp-print/"><u>Enabling Wireless Connectivity for HP Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epsons-print-problem-decoded-error-x97/"><u>Epson's Print Problem Decoded: Error X97</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/fixing-blank-sequences-during-obs-recording/"><u>Fixing Blank Sequences During OBS Recording</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574106588-fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-joining-officejet-8720-to-home-computers/"><u>Guide: Joining OfficeJet 8720 to Home Computers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-issue-hp-printer-not-recognized-by-os/"><u>Hardware Issue: HP Printer Not Recognized by OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-set-a-viral-song-as-your-phones-personal-melody-for-2024/"><u>How To Set a Viral Song as Your Phone's Personal Melody for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-unfreeze-an-offline-brother-printer-online/"><u>How To Unfreeze an Offline Brother Printer Online</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-gionee-f3-promirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Gionee F3 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-your-canon-printer-an-illustrated-tutorial/"><u>Installing Your Canon Printer - An Illustrated Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-canon-printer-wont-respond-what-now/"><u>My Canon Printer Won't Respond, What Now?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimizing-mf4770n-driver-for-w11-w8-w7/"><u>Optimizing MF4770n Driver for W11, W8, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canon-printer-puzzles-in-windows-11-here-are-five-easy-solutions/"><u>Overcome Canon Printer Puzzles in Windows 11 - Here Are Five Easy Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-to-color-requests/"><u>Printer Not Responding to Color Requests</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-spooler-stopped-on-pc-help-needed/"><u>Printer Spooler Stopped on PC, Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printing-powerhouse-latest-updates-for-dell-printer-windows-7/"><u>Printing Powerhouse: Latest Updates for Dell Printer WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-scanner-link-to-computer-in-win10/"><u>Re-Establishing Scanner Link to Computer in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivate-and-resume-fixing-your-disconnected-printer/"><u>Reactivate and Resume: Fixing Your Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-stuck-print-head/"><u>Remedying Stuck Print Head</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-network-failure/"><u>Resolved Printer Network Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-printer-link-to-spooler/"><u>Restored PRINTER Link to Spooler</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-activation-a-win10-fix-guide/"><u>Scanner Activation: A Win10 Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplify-print-setup-wi-fi-connection-for-canon/"><u>Simplify Print Setup: Wi-Fi Connection for Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-spooler-from-freaking-out/"><u>Stop Windows Print Spooler From Freaking Out</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-wastelanded-printer-on-windows-11/"><u>Stop Your Wastelanded Printer on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/strategies-to-forget-a-connected-printer-in-win-1011/"><u>Strategies to Forget a Connected Printer in Win 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swiftly-reunite-disconnected-printer/"><u>Swiftly Reunite Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-10-printer-software/"><u>Troubleshoot Windows 10 Printer Software</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-11-printing-glitches/"><u>Troubleshoot Windows 11 Printing Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-full-potential-of-hp-printers-in-windows/"><u>Unlocking the Full Potential of HP Printers in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-best-audio-waveform-generator/"><u>Updated In 2024, Best Audio Waveform Generator</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-error-unresponsive-on-win7-restart/"><u>USB Printer Error: Unresponsive on Win7 Restart</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-non-operation-on-windows-7-post-sleep/"><u>USB Printer Non-Operation on Windows 7 Post Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
</ul></div>
