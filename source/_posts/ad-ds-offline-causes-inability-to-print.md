---
title: AD DS Offline Causes Inability To Print
date: 2024-07-29T00:29:46.309Z
updated: 2024-07-30T00:29:46.309Z
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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

## Method 2: Using Registry Editor

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/driver-missing-canon-pixma-mp620-printer-not-finding-win10/"><u>[Driver Missing] Canon Pixma MP620 Printer Not Finding WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-printer-hp-deskjet-d1360-struggles-on-various-windows-platforms/"><u>[Installing Printer]: HP Deskjet D1360 Struggles on Various Windows Platforms</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-problems-windows-xp-10-printer-vanishes/"><u>[Network Problems] Windows XP-10, Printer Vanishes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-secure-vimeo-to-local-downloaders/"><u>[Updated] 2024 Approved  Secure Vimeo to Local Downloaders</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-unlocking-audio-enhancement-three-inexpensive-apple-techniques-for-films/"><u>[Updated] 2024 Approved  Unlocking Audio Enhancement  Three Inexpensive Apple Techniques for Films</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-disconnected-chapters-to-cohesive-narratives-with-kinemaster/"><u>[Updated] From Disconnected Chapters to Cohesive Narratives with Kinemaster</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-iphone-14-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from iPhone 14</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-common-canon-printer-woes-in-windows-10-settings/"><u>Address Common Canon Printer Woes in Windows 10 Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-corrective-action-complete/"><u>B200 Corrective Action Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breakthrough-techniques-joining-your-laptop-and-hp-in-156-characters-or-less/"><u>Breakthrough Techniques: Joining Your Laptop and HP in 156 Characters or Less</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridging-the-gap-how-to-merge-your-laptop-and-hp-printer-quickly/"><u>Bridging the Gap: How to Merge Your Laptop and HP Printer Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/colors-missing-in-document-output/"><u>Colors Missing in Document Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/combating-printers-error-x97-in-epson/"><u>Combating Printer's Error X97 in Epson</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-canon-printer-fixes-for-windows-users/"><u>Effortless Canon Printer Fixes for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-incessant-print-service-pauses-in-win-systems/"><u>End Incessant Print Service Pauses in Win Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-paper-shortage-2024-printer-update/"><u>Ending Paper Shortage: 2024 Printer Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-document-saving-functionality-in-windows-11/"><u>Enhance Document Saving Functionality in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensuring-smooth-performance-mf4770n-in-win11win8w7/"><u>Ensuring Smooth Performance: MF4770n in Win11/Win8/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-printer-repair-success/"><u>Epson Printer Repair Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-on-epson-dispelled/"><u>Error Code 0X97 on Epson Dispelled</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-meizu-21-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hardware-setup-hp-printer-driver-not-in-windows-os/"><u>Hardware Setup: HP Printer Driver Not in Windows OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-resolve-iphone-standby-issues-a-guide-to-4-essential-fixes/"><u>How to Resolve iPhone Standby Issues: A Guide to 4 Essential Fixes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-apple-iphone-6-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on Apple iPhone 6 online without jailbreak</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-iphone-6s-lock-screen-with-notifications-by-drfone-ios/"><u>In 2024, How to Make the Most of Your iPhone 6s Lock Screen with Notifications?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-momentum-in-motion-top-20-instagram-ideas-for-mentoring-the-masses/"><u>In 2024, Momentum in Motion  Top 20 Instagram Ideas for Mentoring the Masses</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inability-to-print-in-full-colors/"><u>Inability to Print in Full Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-manual-hp-smartoffice-800-series/"><u>Installation Manual: HP SmartOffice 800 Series</u></a></li>
<li><a href="https://printer-issues.techidaily.com/journeys-end-successfully-setting-up-hp-printer-in-win-os/"><u>Journey's End: Successfully Setting Up HP Printer in Win OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-canons-print-to-wi-fi-journey/"><u>Navigating Canon's Print to Wi-Fi Journey</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-response-from-my-canon-printout-machine/"><u>No Response From My Canon Printout Machine</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-error-code-oxc4eb827f/"><u>Overcoming HP Printer Error Code: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-paper-queue-freeze-on-windows-oses-10-11-and-7/"><u>Overcoming Paper Queue Freeze on Windows OSes (10, 11 & 7)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-perfection-achieved-say-goodbye-to-ghosts/"><u>Print Perfection Achieved: Say Goodbye to Ghosts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connected-in-minutes-no-problems/"><u>Printer Connected in Minutes, No Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hiccup-configuration-issue-surfaced/"><u>Printer Hiccup: Configuration Issue Surfaced</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-network-reestablished-windows-7/"><u>Printer Network Reestablished, Windows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionize-your-printing-3-futuristic-solutions-to-connect-hp-and-laptop/"><u>Revolutionize Your Printing: 3 Futuristic Solutions to Connect HP & Laptop</u></a></li>
<li><a href="https://printer-issues.techidaily.com/spooler-error-preventing-successful-prints/"><u>Spooler Error Preventing Successful Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-printers/"><u>Steps to Troubleshoot Unresponsive HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-trouble-incorrect-printer-configuration/"><u>Tech Trouble: Incorrect Printer Configuration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574032401-trouble-printing-on-windows-11-lets-fix-it/"><u>Trouble Printing on Windows 11? Let's Fix It!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unite-your-workspace-3-cutting-edge-solutions-for-hp-and-laptop-connection/"><u>Unite Your Workspace: 3 Cutting-Edge Solutions for HP and Laptop Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-hidden-printer-error-messages/"><u>Unveiling Hidden Printer Error Messages</u></a></li>
<li><a href="https://printer-issues.techidaily.com/what-to-do-when-your-printer-is-offline/"><u>What To Do When Your Printer Is Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-3x-print-hiccup-quick-fixes-needed/"><u>Windows 3.x Print Hiccup - Quick Fixes Needed</u></a></li>
</ul></div>
