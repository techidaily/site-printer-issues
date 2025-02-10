---
title: Active Directory Unavailable, Print Error Noted
date: 2025-02-04T00:10:24.894Z
updated: 2025-02-09T20:59:15.341Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Active Directory Unavailable, Print Error Noted
excerpt: This Article Describes Active Directory Unavailable, Print Error Noted
keywords: Print Server Issues,Active Directory Troubleshooting,Print Errors Active Directory,Network Print Problems,Print Server Unavailable Error,Active Directory Failure Solutions,Print Service Discovery Errors
thumbnail: https://thmb.techidaily.com/35eb7ec70c3d68bdd6223aba9efbf03bc030e84e65b3cf939f3e4c2fcf3f5d40.jpg
---

## Active Directory Unavailable, Print Error Noted

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  

 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-best-practices-expert-picks-for-4k-dslr-mounts/"><u>[New] Best Practices Expert Picks for 4K DSLR Mounts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanner-activation-after-updating-win10/"><u>Enable Scanner Activation After Updating Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-easy-wi-fi-connectivity-for-canon/"><u>Enabling Easy Wi-Fi Connectivity for Canon</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-12-mini-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone 12 mini Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-resumption-of-prints/"><u>Immediate Resumption of Prints</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-pcl-xl-errors-with-ease/"><u>Navigating Through PCL XL Errors with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solidify-printing-integrity-fixing-issues-on-win10/"><u>Solidify Printing Integrity, Fixing Issues on Win10</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/step-into-cinematic-quality-using-instagrams-chroma-keying-effect/"><u>Step Into Cinematic Quality Using Instagram’s Chroma Keying Effect</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-top-8-excellent-free-online-srt-translators-for-efficiency-for-2024/"><u>Unveiling Top 8 Excellent Free Online SRT Translators for Efficiency for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/what-is-virtual-reality-video-for-2024/"><u>What Is Virtual Reality Video for 2024</u></a></li>
</ul></div>

