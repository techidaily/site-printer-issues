---
title: Active Directory Down - Print Operation Fails
date: 2024-10-09T07:42:26.928Z
updated: 2024-10-12T00:59:40.609Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Active Directory Down - Print Operation Fails
excerpt: This Article Describes Active Directory Down - Print Operation Fails
keywords: Active Directory Failure,Print Operations Error,AD Server Issues,Network Printer Connection Troubleshooting,Windows Domain Print Problems,Remote Access Printing Malfunction,Administrative Services Downtime
thumbnail: https://thmb.techidaily.com/f567dab373423469fdd9df8f70e7990588879bfed38e1184b365dd128527e555.jpg
---

## Active Directory Down - Print Operation Fails

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
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-enhance-your-creative-edge-top-10-free-macos-compatible-tiktok-editors/"><u>[Updated] 2024 Approved Enhance Your Creative Edge Top 10 Free, MacOS-Compatible TikTok Editors</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-mastering-srt-file-playback-on-both-oses/"><u>[Updated] 2024 Approved Mastering SRT File Playback on Both OSes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-steam-playback-perfection-in-video-games-for-2024/"><u>[Updated] Steam Playback Perfection in Video Games for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-xiaomi-13t-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Xiaomi 13T Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-ultimate-checklist-12-must-have-cameras-for-vlogging-professionals/"><u>In 2024, The Ultimate Checklist 12 Must-Have Cameras for Vlogging Professionals</u></a></li>
<li><a href="https://buynow-info.techidaily.com/organization-local-multicasts-can-be-routed-outside-of-a-single-organization-if-necessary/"><u>Organization-Local Multicasts Can Be Routed Outside of a Single Organization if Necessary.</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-successfully/"><u>Printer Setup Completed Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapidly-reconnecting-to-your-printer/"><u>Rapidly Reconnecting to Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-hp-printer-oxc4eb827f-fatality-problem/"><u>Solving HP Printer OXC4EB827F Fatality Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
</ul></div>

