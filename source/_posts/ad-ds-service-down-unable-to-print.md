---
title: "AD DS Service Down: Unable To Print"
date: 2024-07-29T00:31:12.602Z
updated: 2024-07-30T00:31:12.602Z
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

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

## Method 2: Using Registry Editor

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<li><a href="https://printer-issues.techidaily.com/driver-not-detected-unable-to-connect-pixma-mp620-to-win10/"><u>[Driver Not Detected] Unable to Connect Pixma MP620 to WIN10</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-renderer-resurgence-new-radeon-edition/"><u>[New] 2024 Approved  Renderer Resurgence  New Radeon Edition</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-share-wide-enhancing-instagram-stories-with-youtube-content/"><u>[New] 2024 Approved  Share Wide  Enhancing Instagram Stories With YouTube Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-from-silence-to-sounds-recording-with-audacity-on-a-mac/"><u>[New] In 2024, From Silence to Sounds  Recording with Audacity on a Mac</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-looking-for-permission-to-view-friends-entirely-shared-media-for-2024/"><u>[New] Looking for Permission to View Friend’s Entirely Shared Media for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-nostalgia-reimagined-transforming-your-vintage-photos-into-cutting-edge-videos/"><u>[New] Nostalgia Reimagined  Transforming Your Vintage Photos Into Cutting-Edge Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-secure-and-simple-photovideo-sharing-with-ios/"><u>[New] Secure and Simple Photo/Video Sharing with IOS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-instructions-for-using-telegram-online-professionally/"><u>[New] Step-By-Step Instructions For Using Telegram Online Professionally</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-gaming-channel-evolution-best-14-video-ideas-on-youtube/"><u>[Updated] Gaming Channel Evolution  Best 14 Video Ideas on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-8-premier-online-photo-frame-creators-revealed/"><u>[Updated] In 2024, 8 Premier Online Photo Frame Creators Revealed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-seminar-screen-recording/"><u>[Updated] In 2024, Seminar Screen Recording</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-harmonious-updates-musical-whatsapp-statues/"><u>2024 Approved  Harmonious Updates  Musical WhatsApp Statues</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-obs-full-screen-fix-announced/"><u>2024 Approved  Obs Full-Screen Fix Announced</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premium-audio-alerts-excellent-sites-compilation/"><u>2024 Approved  Premium Audio Alerts  Excellent Sites Compilation</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-top-eco-friendly-filming-tech-mastery-guide/"><u>2024 Approved  Top Eco-Friendly Filming Tech  Mastery Guide</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-xsplit-collection-comprehensive-gaming-review/"><u>2024 Approved  XSplit Collection  Comprehensive Gaming Review</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-on-apple-iphone-12-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock on Apple iPhone 12</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-hp-printers-blank-sheet-mystery/"><u>Clearing Up HP Printer's Blank Sheet Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/conquer-print-issues-with-comprehensive-windows-hp-guide/"><u>Conquer Print Issues with Comprehensive Windows HP Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/cross-platform-movie-recording-pc-mac-and-mobile-for-2024/"><u>Cross-Platform Movie Recording  PC, Mac & Mobile for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-hp-printers-error-0xoxc4eb827f/"><u>Disabling HP Printer's Error 0xOXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domains-offline-causing-printer-errors/"><u>Domains Offline - Causing Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-white-sheet-saga-with-hp-printer-fix/"><u>Ending White Sheet Saga with HP Printer Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-office-efficiency-3-fixes-for-printer-and-laptop-synergy/"><u>Enhancing Office Efficiency: 3 Fixes for Printer & Laptop Synergy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/farewell-to-printer-frustration-win-10s-solution-found/"><u>Farewell to Printer Frustration: Win 10'S Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-code-b200/"><u>Fixed: Error Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-network-printer-how-to-find-it-on-your-os/"><u>Hidden Network Printer: How to Find It on Your OS</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-make-a-cool-youtube-video-intro-in-imovie/"><u>How to Make a Cool YouTube Video Intro in iMovie?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-driver-compatibility-with-multiple-windows-oses/"><u>HP Deskjet D1360 Driver Compatibility with Multiple Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/image-guide-to-install-and-connect-canon-printers/"><u>Image Guide to Install and Connect Canon Printers</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-transforming-ideas-into-reality-best-6-nft-services-explored/"><u>In 2024, Transforming Ideas Into Reality  Best 6 NFT Services Explored</u></a></li>
<li><a href="https://facebook.techidaily.com/love-in-the-age-of-algorithms-decoding-facebooks-new-dating-features/"><u>Love in the Age of Algorithms: Decoding Facebook's New Dating Features</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-art-of-configuring-your-hp-printer-on-pcs/"><u>Mastering the Art of Configuring Your HP Printer on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-printer-driver-on-canon-mp620-help-required-for-win11/"><u>Missing Printer Driver on Canon MP620, Help Required for Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mp620-printer-searching-for-missing-windows-driver/"><u>MP620 Printer: Searching for Missing Windows Driver</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-make-a-photo-collage-using-iphoto/"><u>New How to Make a Photo Collage Using iPhoto?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/operation-print-device-added-without-issues/"><u>Operation: Print Device Added without Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-print-performance-dells-latest-aio-upgrades-in-win7/"><u>Optimize Print Performance: Dell's Latest AIO Upgrades in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-epsons-lack-of-print-feature/"><u>Overcoming Epson's Lack of Print Feature</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-continuous-spooler-failures-on-w10w11w7/"><u>Preventing Continuous Spooler Failures on W10/W11/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-troubleshooting-for-non-printing-canon-printers/"><u>Quick Troubleshooting for Non-Printing Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/secure-removal-of-drivers-for-printer-devices/"><u>Secure Removal of Drivers for Printer Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-windows-10-printer-setup-woes/"><u>Tackle Windows 10 Printer Setup Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-problem-discovered/"><u>Unexpected Print Problem Discovered</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-itels-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Itels Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
</ul></div>
