---
title: "PPrintError: Active Directory Service Unavailable"
date: 2024-09-09T01:24:02.369Z
updated: 2024-09-10T01:24:02.369Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes PPrintError: Active Directory Service Unavailable"
excerpt: "This Article Describes PPrintError: Active Directory Service Unavailable"
keywords: PPrintError,Active Directory Service Unavailable,AD Services Offline,Print Server Error,Domain Controller Down,Unable to Connect to AD,Troubleshooting AD Downtime
thumbnail: https://thmb.techidaily.com/39b1aa90cbe15af25eeef086af2b40b5abbe4ea0e44addc2aa4ec5af37792daa.jpg
---

## PPrintError: Active Directory Service Unavailable

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-free-minecraft-youtube-banners-with-templates/"><u>[New] 2024 Approved  Free Minecraft YouTube Banners with Templates</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-trailblazers-top-intro-list-for-zooids/"><u>[New] 2024 Approved  Trailblazers Top Intro List for Zooids</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-blade-chroma-with-4k-camera-review/"><u>[New] Blade Chroma with 4K Camera Review</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unmatched-clarity-our-choice-of-the-top-10-camera-lenses/"><u>[New] Unmatched Clarity  Our Choice of the Top 10 Camera Lenses</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-utilizing-the-virtual-whiteboard-in-webinars-cross-platform-tips-and-tricks-for-2024/"><u>[New] Utilizing the Virtual Whiteboard in Webinars  Cross-Platform Tips and Tricks for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-fixer-regain-lost-network-print-visibility/"><u>[Print Issue Fixer] Regain Lost Network Print Visibility</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-local-print-spooler-service-not-running-on-windows/"><u>[SOLVED] Local Print Spooler Service Not Running on Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-basic-framework-for-crafting-persuasive-social-media-messages/"><u>[Updated] In 2024, Basic Framework for Crafting Persuasive Social Media Messages</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-elevateview-video-converter-software/"><u>[Updated] In 2024, ElevateView Video Converter Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unveiling-the-secrets-of-live-broadcasting-on-instagram-through-obs/"><u>[Updated] In 2024, Unveiling the Secrets of Live Broadcasting on Instagram Through OBS</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-instantaneous-screen-logging-chromebooks/"><u>2024 Approved  Instantaneous Screen Logging (Chromebooks)</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-guide-to-smoothly-linking-canon-printers/"><u>A Guide to Smoothly Linking Canon Printers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-infinix-smart-8-plus-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Infinix Smart 8 Plus</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574061275-b200-bug-fixed-ready-to-go/"><u>B200 Bug Fixed, Ready to Go</u></a></li>
<li><a href="https://printer-issues.techidaily.com/blank-page-dilemma-hp-printer-now-printing-correctly/"><u>Blank Page Dilemma: HP Printer Now Printing Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-gaps-connecting-canon-to-wireless-networks/"><u>Bridging Gaps: Connecting Canon to Wireless Networks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-remove-printer-on-windows-solved/"><u>Can't Remove Printer on Windows [Solved]</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-shareable-instagram-stories-that-spread-like-wildfire/"><u>Crafting Shareable Instagram Stories That Spread Like Wildfire</u></a></li>
<li><a href="https://screen-capture.techidaily.com/crafting-your-dream-minecraft-house-with-ease-for-2024/"><u>Crafting Your Dream Minecraft House with Ease for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-the-leading-unwired-phone-models-for-a-crystal-clear-call/"><u>Discover the Leading Unwired Phone Models for a Crystal Clear Call</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573877149-effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-disconnect-resolved/"><u>Epson Disconnect Resolved</u></a></li>
<li><a href="https://vp-tips.techidaily.com/essential-10-hd-android-video-player-apps-list/"><u>Essential 10 HD Android Video Player Apps List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-fixes-for-non-starting-print-spooler-on-pcs/"><u>Essential Fixes for Non-Starting Print Spooler on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-on-how-to-remove-crashdump-data-in-windows-11/"><u>Expert Tips on How To Remove Crashdump Data in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-speed-and-accuracy-on-windows-11/"><u>Fix Printing Speed and Accuracy on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-disappearing-printers-in-windows-810/"><u>How to Fix Disappearing Printers in WIndows 8/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ignoring-my-printer-what-to-do/"><u>Ignoring My Printer - What to Do?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17e-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17e to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-unleash-creativity-personalizing-your-google-meet-interface/"><u>In 2024, Unleash Creativity  Personalizing Your Google Meet Interface</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-deletion-of-printers-on-pc/"><u>Mastering the Deletion of Printers on PC</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/y-youtube-video-visibility-with-ease-for-2024/"><u>Modify YouTube Video Visibility with Ease for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/monitor-misbehaving-cant-show-full-screen-11-windows/"><u>Monitor Misbehaving: Can't Show Full Screen 11 Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-a-silent-printer-in-office/"><u>Navigating a Silent Printer in Office</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-epsons-error-0x97-maze/"><u>Navigating Epson's Error 0X97 Maze</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-fix-printer-online-now/"><u>Network Fix: PRINTER Online Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-text-only-paper-the-epson-printer-glitch/"><u>No Text, Only Paper: The Epson Printer Glitch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-error-on-windows-fixed/"><u>Printer Not Responding Error on Windows Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-shown-solutions-for-network-print-issues/"><u>Printer Not Shown: Solutions for Network Print Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinforce-win10s-networked-printer-setup/"><u>Reinforce WIN10's Networked Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reset-scanner-connection-status-on-pc-windows-10/"><u>Reset Scanner Connection Status on PC, Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-officejets-no-print-malaise/"><u>Solving OfficeJet's No Print Malaise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-release-from-print-lineup/"><u>Speedy Release From Print Lineup</u></a></li>
<li><a href="https://os-tips.techidaily.com/speedy-reset-tactics-mastering-the-art-of-quick-android-phone-reboots/"><u>Speedy Reset Tactics: Mastering the Art of Quick Android Phone Reboots</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-resolve-print-spooler-shutdown-woes-win-10-11-and-7/"><u>Steps to Resolve Print Spooler Shutdown Woes (Win 10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-printer-connectivity-issues-in-w11/"><u>Tackle Printer Connectivity Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-black-screen-issue-on-hp-printer/"><u>Tackling Black Screen Issue on HP Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/techniques-for-eliminating-drivers-without-error/"><u>Techniques for Eliminating Drivers Without Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-produce-full-color-prints/"><u>Unable to Produce Full-Color Prints</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-freedom-top-8-tools-transforming-youtube-into-avis-for-2024/"><u>Video Freedom  Top 8 Tools Transforming YouTube Into Avis for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-fix-printer-not-responding-anymore/"><u>Win11 Fix: Printer Not Responding Anymore</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-usb-printer-reset-problems-post-sleep-cycle/"><u>Win7 USB Printer Reset: Problems Post-Sleep Cycle</u></a></li>
</ul></div>
