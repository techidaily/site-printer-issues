---
title: No Access To Domain Services, Printer Not Responding
date: 2024-07-29T00:28:36.179Z
updated: 2024-07-30T00:28:36.179Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes No Access To Domain Services, Printer Not Responding
excerpt: This Article Describes No Access To Domain Services, Printer Not Responding
keywords: Printer Access Issues,Domain Services Printer Troubleshooting,Restarting Non-Responsive Print Devices,Printer Connectivity and Access Issues,Print Server Configuration Errors,Network Print Device Compatibility Issues,Managing Printer Domain Services Access
thumbnail: https://thmb.techidaily.com/740b68b56d6bbac7152f3eef9f605d6bffa61f7111e01d3d9d9931aeb1f4b3a1.jpg
---

## No Access To Domain Services, Printer Not Responding

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Method 1: Change Printer Spooler settings

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-elevate-your-brand-with-these-essential-fb-strategies-for-all/"><u>[New] 2024 Approved  Elevate Your Brand with These Essential FB Strategies (for All)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-formulating-engaging-content-excerpts-for-streaming/"><u>[New] Formulating Engaging Content Excerpts for Streaming</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-vocal-ventures-merging-music-and-video-on-snapchat-for-2024/"><u>[New] Vocal Ventures  Merging Music & Video on Snapchat for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connectivity-win1110-cant-find-hp-driver/"><u>[Printer Connectivity] Win11/10 Can't Find HP Driver</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-sonic-savant-archive-acquire-and-examine-tracks/"><u>[Updated] 2024 Approved  Sonic Savant Archive  Acquire & Examine Tracks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-snap-it-up-innovative-ig-images-that-inspire-for-2024/"><u>[Updated] Snap It Up! Innovative IG Images That Inspire for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-times-tail-in-snapchat-video-backtracking-guide-for-2024/"><u>[Updated] Time's Tail in Snapchat  Video Backtracking Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unlocking-potential-in-instagram-engagement-with-advanced-data-tools-for-2024/"><u>[Updated] Unlocking Potential in Instagram Engagement with Advanced Data Tools for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/2024-3-fixes-to-connect-hp-printer-to-laptop/"><u>2024 | 3 Fixes to Connect HP Printer to Laptop</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-enhancing-your-photos-essential-mobile-tools/"><u>2024 Approved  Enhancing Your Photos  Essential Mobile Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-joyfuljourney-sign-up-share-and-create-fun-videos/"><u>2024 Approved  JoyfulJourney  Sign Up, Share and Create Fun Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-masterclass-in-connecting-ig-and-tiktok/"><u>2024 Approved  Masterclass in Connecting IG & TikTok</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-transform-ideas-into-laughter-generate-text-memes/"><u>2024 Approved  Transform Ideas Into Laughter  Generate Text Memes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-correction-implemented/"><u>B200 Correction Implemented</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-fix-achieved/"><u>B200 Fix Achieved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-mfc-9330cdw-driver-download-and-install-guide/"><u>Brother MFC-9330CDW Driver Download & Install Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ease-into-plc-error-resolution/"><u>Ease Into PLC Error Resolution</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6-plus-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6 Plus To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-status-on-windows-117-solved/"><u>HP Printer Offline Status on Windows 11/7 [Solved]</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nokia-c32-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nokia C32 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-6-plus-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 6 Plus You Should Try Out</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-tips-mfc-9330cdw-driver/"><u>Installation Tips: MFC-9330CDW Driver</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-out-loud-crafting-humorous-video-ideas-for-short-films/"><u>Laugh Out Loud  Crafting Humorous Video Ideas for Short Films</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719573904602-local-printer-spooler-not-responding-help/"><u>Local Printer Spooler Not Responding, Help!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/making-your-canon-printers-wi-fi-life-easier/"><u>Making Your Canon Printer's Wi-Fi Life Easier</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-the-process-essential-techniques-and-strategies-for-green-screen-filmmaking-for-2024/"><u>Mastering the Process  Essential Techniques & Strategies for Green Screen Filmmaking for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-horizons-in-workspace-tech-converging-hp-and-laptops-flawlessly/"><u>New Horizons in Workspace Tech - Converging HP and Laptops Flawlessly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-easily-create-a-free-eye-catching-intro-videos-with-invideo/"><u>New How to Easily Create a Free Eye-Catching Intro Videos with Invideo</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-unprinted-pages-on-hp-printer-now/"><u>No More Unprinted Pages on HP Printer Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-failure-in-hp-model-xyz/"><u>Overcome Printing Failure in HP Model XYZ</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-windows-117-hp-printer-errors/"><u>Overcoming Windows 11/7 HP Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-not-found/"><u>Printer OS Error: Drivers Not Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-puzzle-resolved-error-0x00000709/"><u>Printer Setup Puzzle: Resolved Error 0X00000709</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-completed-without-problems/"><u>Printer Setup: Completed Without Problems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnecting-brothers-print-to-end-offline-status-woes/"><u>Reconnecting Brothers Print to End Offline Status Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-windows-2000-xp-print-errors-quickly/"><u>Resolve Windows 2000 XP Print Errors Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-fault-eco-error/"><u>Resolved: Printer Fault #Eco-Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-respondent-printer-on-windows-3x-edition/"><u>Revive Non-Respondent Printer on Windows 3.x Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-activation-restored-for-windows-10-users/"><u>Scanner Activation Restored for Windows 10 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-primary-printer-failed-error-0x00000709-fixed/"><u>Setting Primary Printer Failed: Error 0X00000709 Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-printer-solutions-unveiled/"><u>Speedy Printer Solutions Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stopping-printer-service-pauses-solutions-for-windows-10w7w11/"><u>Stopping Printer Service Pauses: Solutions for Windows 10/W7/W11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/take-it-upward-expert-techniques-for-phones/"><u>Take It Upward  Expert Techniques for Phones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-starting-point-for-film-designers-for-2024/"><u>The Starting Point for Film Designers for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-canon-non-print-issue/"><u>Troubleshooting Canon Non-Print Issue</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-6s-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server On iPhone 6s</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-driven-print-screws/"><u>Unblocking Driven Print Screws</u></a></li>
<li><a href="https://printer-issues.techidaily.com/wake-up-call-faulty-usb-printers-in-windows-7-mode/"><u>Wake Up Call: Faulty USB Printers in Windows 7 Mode</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/where-is-the-best-place-to-catch-dratini-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-hp-paper-jam-resolved/"><u>Win11 HP Paper Jam Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-inactivity-post-sleep-fix-guide/"><u>Win7 Printer Inactivity Post-Sleep: Fix Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-online-after-repair/"><u>Win7 Printer Online After Repair</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-issues-quick-solutions-needed/"><u>Windows 11 Printer Issues - Quick Solutions Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-printer-not-responding-spooler-issue/"><u>Windows Printer Not Responding: Spooler Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-users-guide-to-hp-printer-installation/"><u>Windows User's Guide to HP Printer Installation</u></a></li>
</ul></div>
