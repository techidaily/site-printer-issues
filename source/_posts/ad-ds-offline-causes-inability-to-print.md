---
title: AD DS Offline Causes Inability To Print
date: 2024-10-13T16:42:50.435Z
updated: 2024-10-18T07:43:16.621Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes AD DS Offline Causes Inability To Print
excerpt: This Article Describes AD DS Offline Causes Inability To Print
keywords: Active Directory Domain Services (AD DS) Issues,Printer Connectivity Problems,Print Server Offline Error,AD DS Offline Printing Troubleshooting,Troubleshoot Inability to Print Due to AD DS,Offline Status Affecting Printer Functionality,Network-Related Errors Preventing Printing on AD DS Systems
thumbnail: https://thmb.techidaily.com/0e8ec29ee6248aac03a17afe8cf5cfd2ec9d4e36dfc8648cae868f4622fb576a.jpg
---

## AD DS Offline Causes Inability To Print

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
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948909/19272" target="_top" id="1948909">
  <img src="//a.impactradius-go.com/display-ad/19272-1948909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-5-dynamic-fitness-series-ideas-to-enhance-viewer-retention-for-2024/"><u>[New] 5 Dynamic Fitness Series Ideas to Enhance Viewer Retention for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/achieve-peak-performance-in-officejets-by-latest-driver-update/"><u>Achieve Peak Performance in Officejets by Latest Driver Update</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-oppo-reno-10-proplus-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Oppo Reno 10 Pro+ 5G is off? | Dr.fone</u></a></li>
<li><a href="https://win-manuals.techidaily.com/comment-utiliser-la-fonction-sauvegarde-et-reprendre-pour-construire-un-nouveau-sysimage-sur-windows/"><u>Comment Utiliser La Fonction Sauvegarde Et Reprendre Pour Construire Un Nouveau Sysimage Sur Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/elite-digital-image-grabbers/"><u>Elite Digital Image Grabbers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fast-and-simple-printer-back-online-now/"><u>Fast & Simple: Printer Back Online Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-the-best-performance-from-your-logiteein-g29-wheel-with-updated-drivers-for-all-windows-versions-11107/"><u>How to Get the Best Performance From Your Logiteein G29 Wheel with Updated Drivers for All Windows Versions (11/10/7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-an-idle-brothers-printer-networkly/"><u>How to Reactivate an Idle Brothers Printer Networkly</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Sony Xperia 10 V? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-help-for-windows-11-printer-problems/"><u>Immediate Help for Windows 11 Printer Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-printer-malfunction-code-0x97/"><u>Mending Printer Malfunction: Code 0X97</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-unleash-your-creativity-top-free-video-editing-apps/"><u>New In 2024, Unleash Your Creativity Top Free Video Editing Apps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-functionality-upgrading-mf4770n-on-w11w8w7-os/"><u>Optimize Functionality: Upgrading MF4770n on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-your-non-printing-brother-printer-in-win1011/"><u>Reviving Your Non-Printing Brother Printer in Win10/11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solution-for-rtwlanesys-critical-stop-error-fix/"><u>Solution for RTWLane.SYS Critical Stop Error Fix</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solutions-to-resolve-missing-d3dx939dll-files/"><u>Solutions to Resolve Missing d3dx9_39.dll Files</u></a></li>
</ul></div>

