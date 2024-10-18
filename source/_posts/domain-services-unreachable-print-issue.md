---
title: Domain Services Unreachable, Print Issue
date: 2024-10-13T19:31:48.061Z
updated: 2024-10-18T04:38:27.726Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Domain Services Unreachable, Print Issue
excerpt: This Article Describes Domain Services Unreachable, Print Issue
keywords: Domain Services Outage Support,Fixing Unreachable Domain Server,Print Driver Error Resolution,Domain Configuration Troubleshooting,Restoring Access to Online Services,Technical Assistance for Website Downtime,Remote Print Service Recovery
thumbnail: https://thmb.techidaily.com/9a9907ac5dbaa04f31e369bac93b279f477635cd1d417e1d02f2db8686c1981a.jpg
---

## Domain Services Unreachable, Print Issue

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
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
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484951/16446" target="_top" id="1484951">
  <img src="//a.impactradius-go.com/display-ad/16446-1484951" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484951/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  

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
<li><a href="https://screen-recording.techidaily.com/new-step-by-step-screen-shotting-for-xbox-enthusiasts-for-2024/"><u>[New] Step-by-Step Screen Shotting for Xbox Enthusiasts for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-top-snapchat-content-strategies-to-stand-out-for-2024/"><u>[New] Top Snapchat Content Strategies to Stand Out for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-wirecast-analysis-with-equivalents/"><u>[Updated] 2024 Approved WireCast Analysis with Equivalents</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-digital-wealth-creation-through-video-networking/"><u>[Updated] In 2024, Digital Wealth Creation Through Video Networking</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flaunt-your-funny-side-the-art-of-using-cartoon-snaps-on-snapchat/"><u>2024 Approved Flaunt Your Funny Side The Art of Using Cartoon Snaps on Snapchat</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-constant-spooler-pauses-across-win-versions/"><u>Eliminate Constant Spooler Pauses Across Win Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-connectivity-now-functional/"><u>Epson Connectivity Now Functional</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hasten-printer-job-advancement/"><u>Hasten Printer Job Advancement</u></a></li>
<li><a href="https://os-tips.techidaily.com/icloud-keychain-integration-with-windows-unlocking-the-secrets-for-seamless-cross-platform-use/"><u>ICloud Keychain Integration with Windows: Unlocking the Secrets for Seamless Cross-Platform Use</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immaculate-documents-from-hp-printer-post-correction/"><u>Immaculate Documents From HP Printer Post-Correction</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy M34 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-virtual-validation-subscribers-buttons-reward-system/"><u>In 2024, Virtual Validation Subscribers, Buttons Reward System</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-v29-pro-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo V29 Pro Phone FRP Lock</u></a></li>
<li><a href="https://printer-issues.techidaily.com/oddity-in-output-multiple-users-on-one-printer/"><u>Oddity in Output: Multiple Users on One Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-enabling-online-scanner-in-win11/"><u>Re-Enabling Online Scanner in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-711-spooler-stops-quick-fix-guide/"><u>Win 7/11 Spooler Stops: Quick Fix Guide</u></a></li>
</ul></div>

