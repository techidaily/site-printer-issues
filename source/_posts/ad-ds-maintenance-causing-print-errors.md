---
title: AD DS Maintenance Causing Print Errors
date: 2024-09-29T16:56:32.468Z
updated: 2024-10-06T18:41:06.752Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes AD DS Maintenance Causing Print Errors
excerpt: This Article Describes AD DS Maintenance Causing Print Errors
keywords: Active Directory Maintenance,Print Errors During AD DS Updates,AD Domain Services Print Issues,Print Server Configuration in AD DS,Troubleshooting Print Errors with AD DS,Print Problems in Active Directory Domain Services,Resolving Print Errors During Domain Service Updates
thumbnail: https://thmb.techidaily.com/4a91ae3eac077409c5986958190c10004fbc3c08316a24c33029f0a844ae5b88.jpg
---

## AD DS Maintenance Causing Print Errors

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

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://printer-issues.techidaily.com/compatibility-canon-pixma-mp620-and-windows-11-clash/"><u>[Compatibility] Canon Pixma MP620 and Windows 11 Clash</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixation-local-network-printer-spooler-stuck/"><u>[FIXATION] Local Network Printer Spooler Stuck</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-mov-in-the-cloud-top-six-techniques-for-windows-11-users-for-2024/"><u>[New] .MOV in the Cloud - Top Six Techniques for Windows 11 Users for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-ps4-gameplay-to-video-an-in-depth-obs-recording-guide/"><u>[Updated] In 2024, PS4 Gameplay to Video - An In-Depth OBS Recording Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/acancel-free-setup-for-wi-fi-connected-printers/"><u>Acancel-Free Setup for Wi-Fi Connected Printers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/charting-the-course-for-unmatched-cloud-storage-for-2024/"><u>Charting the Course for Unmatched Cloud Storage for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-from-apple-iphone-6s-by-drfone-ios/"><u>How to Fix Locked Apple ID from Apple iPhone 6s</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-streamlining-the-process-for-free-pictured-frame-files/"><u>In 2024, Streamlining the Process for Free Pictured Frame Files</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/puns-and-plots-developing-7-funny-video-storylines/"><u>Puns & Plots Developing 7 Funny Video Storylines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-connect-protocol-printer-online/"><u>Quick Connect Protocol: Printer Online</u></a></li>
<li><a href="https://fox-direct.techidaily.com/streamline-your-screens-youtube-video-resizing-tricks/"><u>Streamline Your Screens YouTube Video Resizing Tricks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-dell-aio-printer-software-in-windows-7/"><u>Upgrade: Dell AIO Printer Software in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winning-against-the-new-windows-printing-issue/"><u>Winning Against the New Windows Printing Issue</u></a></li>
</ul></div>

