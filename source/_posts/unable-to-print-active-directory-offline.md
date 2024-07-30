---
title: "Unable To Print: Active Directory Offline"
date: 2024-07-29T00:26:12.977Z
updated: 2024-07-30T00:26:12.977Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Unable To Print: Active Directory Offline"
excerpt: "This Article Describes Unable To Print: Active Directory Offline"
keywords: Unable To Print Issue,Active Directory Offline Troubleshooting,Print Services Failure in AD,Domain Join Failures,Printing Errors Active Directory,Printer Connectivity & AD Issues,Offline Domain Controller
thumbnail: https://thmb.techidaily.com/497e0cf4a494c643d111720df0c9d81e356ffb4889a6eb2b11c281fd2cb5d878.jpg
---

## Unable To Print: Active Directory Offline

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Method 2: Using Registry Editor

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/issue-missing-printer-driver-in-win/"><u>[ISSUE] Missing Printer Driver in Win</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ecoding-the-secrets-of-highly-successful-youtube-shorts-templates/"><u>[New] Decoding the Secrets of Highly Successful YouTube Shorts Templates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fine-tune-your-visual-storytelling-in-videoleap-footage/"><u>[New] Fine-Tune Your Visual Storytelling in Videoleap Footage</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps/"><u>[New] In 2024, Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevate-your-hashtag-game-on-instagram-a-comprehensive-guide-for-2024/"><u>[Updated] Elevate Your Hashtag Game on Instagram  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-crafting-a-youtube-video-essential-writing-guide/"><u>[Updated] In 2024, Crafting a YouTube Video  Essential Writing Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-record-everything-pay-nothing-screen-tools-for-all-users/"><u>[Updated] Record Everything, Pay Nothing - Screen Tools for All Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-time-travelers-treasure-a-look-at-goofy-movie/"><u>[Updated] Time Traveler’s Treasure  A Look at 'Goofy Movie'</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-optimize-your-gaming-by-learning-ps3-video-capture-techniques/"><u>2024 Approved  Optimize Your Gaming by Learning PS3 Video Capture Techniques</u></a></li>
<li><a href="https://facebook.techidaily.com/boundaries-in-the-virtual-world-key-privacy-protectors-to-know/"><u>Boundaries in the Virtual World: Key Privacy Protectors to Know</u></a></li>
<li><a href="https://printer-issues.techidaily.com/color-printing-malfunction-detected/"><u>Color Printing Malfunction Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-woes-when-print-devices-go-offline/"><u>Connectivity Woes: When Print Devices Go Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correct-printer-configuration-errors-in-w11/"><u>Correct Printer Configuration Errors in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrective-measures-in-place-for-hp-printers-blanks/"><u>Corrective Measures in Place for HP Printer's Blanks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-hp-printer-on-windows-107/"><u>Enabling HP Printer on Windows 10/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-remove-print-spooler-service/"><u>How To Remove Print Spooler Service</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabled-apple-iphone-13-mini-how-to-unlock-a-disabled-apple-iphone-13-mini-drfone-by-drfone-ios/"><u>In 2024, Disabled Apple iPhone 13 mini How to Unlock a Disabled Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-safe-surveillance-strategies-blurring-sensitive-content/"><u>In 2024, Safe Surveillance Strategies  Blurring Sensitive Content</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transforming-videos-through-skillful-narration-techniques/"><u>In 2024, Transforming Videos Through Skillful Narration Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructions-installing-hp-officejet-on-pc-interface/"><u>Instructions: Installing HP Officejet on PC Interface</u></a></li>
<li><a href="https://extra-skills.techidaily.com/moviemaker-masterwin8-for-2024/"><u>MovieMaker MasterWin8 for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-error-unforeseen-setup-glitch-detected/"><u>Print Error: Unforeseen Setup Glitch Detected</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-release-of-stuck-prints/"><u>Rapid Release of Stuck Prints</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-print-no-hassle-method/"><u>Reconnect Print: No Hassle Method</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-print-job-failures-on-windows-11/"><u>Rectify Print Job Failures on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-install-errors/"><u>Resolved Printer Install Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-dead-printers-on-windows-11-os/"><u>Revive Dead Printers on Windows 11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574042518-stop-the-print-jamming-on-windows-11-now/"><u>Stop the Print Jamming on Windows 11 Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1719345925022-the-forgotten-tools-of-windows-11-dont-miss-them/"><u>The Forgotten Tools of Windows 11 - Don’t Miss Them</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-connect-domains-and-printers-offline/"><u>Unable To Connect: Domains and Printers Offline</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Infinix Note 30i? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-and-mp620-printer-wheres-the-compatibility/"><u>Win11 & MP620 Printer: Where's the Compatibility?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-resuming-scan-capabilities-immediately/"><u>Win11: Resuming Scan Capabilities Immediately</u></a></li>
</ul></div>
