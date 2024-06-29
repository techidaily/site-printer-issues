---
title: AD DS Maintenance Causing Print Errors
date: 2024-06-28T07:12:08.568Z
updated: 2024-06-29T07:12:08.568Z
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
<li><a href="https://printer-issues.techidaily.com/seamless-wireless-hookup-for-canon-devices/"><u>Seamless Wireless Hookup for Canon Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-epson-workflow-flow/"><u>Restored Epson Workflow Flow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-intermittent-printing-on-hp-deskjet-305dn/"><u>Fixed Intermittent Printing on HP DeskJet 305Dn</u></a></li>
<li><a href="https://printer-issues.techidaily.com/essential-steps-to-connect-canon-to-network-wirelessly/"><u>Essential Steps to Connect Canon to Network Wirelessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-code-0x00000709-to-fix-default-printer-setup/"><u>Cracking Code 0X00000709 to Fix Default Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-print-drivers-troubleshooting-across-windows-versions/"><u>HP Deskjet D1360 Print Drivers: Troubleshooting Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-printer-spooler-non-responsive/"><u>Windows 10 Printer Spooler Non-Responsive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapidly-reconnecting-to-your-printer/"><u>Rapidly Reconnecting to Your Printer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/audiovisual-harmony-incorporating-audio-into-powerpoint-presentations-for-2024/"><u>Audiovisual Harmony  Incorporating Audio Into PowerPoint Presentations for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-realme-narzo-60-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Realme Narzo 60 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-top-5-must-see-music-video-animations-free-and-premium-options/"><u>New 2024 Approved Top 5 Must-See Music Video Animations Free & Premium Options</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-accelerate-your-videos-top-speed-changer-apps-for-pc-and-mac/"><u>Updated 2024 Approved Accelerate Your Videos Top Speed Changer Apps for PC and Mac</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-dji-inspire-2-full-review/"><u>[New] 2024 Approved  DJI Inspire 2 Full Review</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-youtube-sound-ripper-collection-top-17-extractors-revealed-for-2024/"><u>[New] Free YouTube Sound Ripper Collection  Top 17 Extractors Revealed for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-instruction-1-same-diffits-level-provide-a-list-of-five-alternative-phrases-that-convey-similar-meaning-to-thrilling-adventure-series-for-young-expl/"><u>Updated Instruction 1 (Same Diffits Level) Provide a List of Five Alternative Phrases that Convey Similar Meaning to Thrilling Adventure Series for Young Explorers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/tiktok-foundations-a-complete-users-manual-for-2024/"><u>TikTok Foundations  A Complete User's Manual for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-art-of-slow-motion-a-guide-for-instagrams-next-viral-reels/"><u>[New] 2024 Approved  The Art of Slow-Motion  A Guide for Instagram's Next Viral Reels</u></a></li>
</ul></div>
