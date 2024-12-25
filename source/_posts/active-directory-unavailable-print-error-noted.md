---
title: Active Directory Unavailable, Print Error Noted
date: 2024-12-23T17:19:01.423Z
updated: 2024-12-24T22:23:05.757Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  

 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  

 5) Close the Services window and check if you could print files successfully.  

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-data-realm-renaissance-pioneering-cloud-services-s-needs/"><u>[New] Data Realm Renaissance Pioneering Cloud Services 'S Needs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-diverse-windows-based-film-editing-software-for-2024/"><u>[Updated] Diverse Windows-Based Film Editing Software for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-6-ways-to-increase-audience-retention-on-youtube-filmora/"><u>2024 Approved 6 Ways To Increase Audience Retention on YouTube - Filmora</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-mastering-creative-expression-adding-video-filters-in-zoom/"><u>2024 Approved Mastering Creative Expression Adding Video Filters in Zoom</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-honor-magic-6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instantly-resolve-disconnected-print-issue/"><u>Instantly Resolve Disconnected Print Issue</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-the-best-of-the-best-top-rated-2d-animation-software-free-trials-and-paid-plans/"><u>New In 2024, The Best of the Best Top-Rated 2D Animation Software Free Trials & Paid Plans</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-silence-speaks-louder-than-no-response/"><u>Printer's Silence Speaks Louder Than No Response</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printing-with-simple-tips-for-canon-windows/"><u>Reignite Printing with Simple Tips for Canon, Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-system-flaw-b200/"><u>Solved: System Flaw B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unjamming-print-heads-a-practical-approach/"><u>Unjamming Print Heads: A Practical Approach</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-tech-trends-on-toms-hardware-portal/"><u>Unveiling the Latest Tech Trends on Tom's Hardware Portal</u></a></li>
</ul></div>

