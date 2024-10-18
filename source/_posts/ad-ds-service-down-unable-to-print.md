---
title: "AD DS Service Down: Unable To Print"
date: 2024-10-11T02:38:15.866Z
updated: 2024-10-18T07:50:21.532Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes AD DS Service Down: Unable To Print"
excerpt: "This Article Describes AD DS Service Down: Unable To Print"
keywords: Active Directory Service Downtime,Print Server Error With AD Domain Services,AD DS Outage Solutions,Print Infrastructure Failure (AD),Failed Printing Due To AD Domain Service Issue,Troubleshooting AD DS Network Printer Problems,Restore Print Services After AD Domain Disruption
thumbnail: https://thmb.techidaily.com/388b9b2fa822d07d170581d6fc602d4ca55180e6b7a80082d066387729af73ba.jpg
---

## AD DS Service Down: Unable To Print

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
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/updated-expert-advice-on-tailoring-game-sounds-to-stand-out-in-the-virtual-arena-of-free-fire/"><u>[Updated] Expert Advice on Tailoring Game Sounds to Stand Out in the Virtual Arena of Free Fire</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-debugged-successfully/"><u>Code B200 Debugged Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cure-non-engagement-in-older-windows-versions-printers/"><u>Cure Non-Engagement in Older Windows Versions' Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-toner-depletion-crisis/"><u>Curing Toner Depletion Crisis</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-silence-to-service-restoring-online-status-in-printer/"><u>From Silence to Service: Restoring Online Status in Printer</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-15-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-y36-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo Y36 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-paper-feeder-malfunction/"><u>Overcome Paper Feeder Malfunction</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-hardware-limitations-how-to-activate-windows-11-on-ineligible-processors-with-revouninstaller-techniques/"><u>Overcoming Hardware Limitations: How to Activate Windows 11 on Ineligible Processors with RevoUninstaller Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-for-languishing-printer-jobs/"><u>Quick Fix for Languishing Printer Jobs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-connected-successfully/"><u>Resolved: PRINTER Connected Successfully</u></a></li>
<li><a href="https://article-posts.techidaily.com/soft-onset-showcasing/"><u>Soft Onset Showcasing</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-solving-crashing-problems-in-cyberpunk-2077-on-your-computer/"><u>Troubleshooting and Solving Crashing Problems in Cyberpunk 2077 on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-netsvcs-understanding-svchostexe-and-solving-its-excessive-network-consumption/"><u>Troubleshooting NETSVCS: Understanding svchost.exe & Solving Its Excessive Network Consumption</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-your-wow-playthrough-solutions-to-prevent-crashes/"><u>Troubleshooting Your Wow Playthrough: Solutions to Prevent Crashes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-and-secure-printer-communication-in-win10/"><u>Upgrade and Secure Printer Communication in Win10</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Poco X6 Pro | Dr.fone</u></a></li>
</ul></div>

