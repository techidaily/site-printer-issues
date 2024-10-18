---
title: Unavailable Domain Services Prevents Printer Access
date: 2024-10-16T02:57:29.355Z
updated: 2024-10-17T21:05:55.585Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Unavailable Domain Services Prevents Printer Access
excerpt: This Article Describes Unavailable Domain Services Prevents Printer Access
keywords: Printer Access Issues,Domain Configuration Errors,Unavailable Domain Services Impact,Print Server Unavailability,Printer Network Troubleshooting,Domain Name Server (DNS) Errors Affecting Printers,Print Access Denial Due to Domain Issues
thumbnail: https://thmb.techidaily.com/c2522eefb8fbc96fa570f56849cfdf92d72e221bd3a27b7e0b7d3fec1332bd02.png
---

## Unavailable Domain Services Prevents Printer Access

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
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
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
  

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-navigating-the-copyright-symphony-of-instagrams-sounds/"><u>[New] In 2024, Navigating the Copyright Symphony of Instagram's Sounds</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-unable-to-locate-hp-driver-winxo/"><u>[Printer Setup] Unable to Locate HP Driver WINXO</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-unable-to-install-printeroperation-could-not-be-completed/"><u>[Solved] Unable to Install Printer.Operation Could Not Be Completed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beginners-guide-to-simple-yet-effective-filming-gear/"><u>In 2024, Beginner's Guide to Simple, Yet Effective Filming Gear</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-expert-review-of-bandicams-efficacy-in-multimedia-projects/"><u>In 2024, Expert Review of Bandicam's Efficacy in Multimedia Projects</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-white-paper-output-on-hp-printer/"><u>Resolving White Paper Output on HP Printer</u></a></li>
<li><a href="https://fox-that.techidaily.com/simple-steps-to-change-your-device-password-for-ios-and-macos-security-settings/"><u>Simple Steps to Change Your Device Password for iOS and macOS Security Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-scan-to-computer-is-no-longer-activated-on-windows-10/"><u>Solved: Scan to Computer Is No Longer Activated on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlined-device-management-officejet-pro-8600-drivers-pc-friendly/"><u>Streamlined Device Management: Officejet Pro 8600 Drivers, PC-Friendly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/systematic-mf4770n-software-enhancement-windows-wise/"><u>Systematic MF4770n Software Enhancement Windows-Wise</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-asus-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Asus Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-tool-list-beyond-sharex/"><u>The Ultimate Tool List Beyond ShareX</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transformez-votre-photographie-avec-ces-techniques-de-defloutage-rapides-et-facilement-accessibles/"><u>Transformez Votre Photographie Avec Ces Techniques De Défloutage Rapides Et Facilement Accessibles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-access-printer-driver-in-windows/"><u>Unable to Access Printer Driver in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/winx-iphone-video-converter/"><u>WinX iPhone Video Converterを使って簡単な方法：動画変換ガイド</u></a></li>
</ul></div>

