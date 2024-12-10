---
title: "PPrintError: Active Directory Service Unavailable"
date: 2024-12-06T00:52:34.655Z
updated: 2024-12-10T04:52:12.095Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes PPrintError: Active Directory Service Unavailable"
excerpt: "This Article Describes PPrintError: Active Directory Service Unavailable"
keywords: PPrintError,Active Directory Service Unavailable,AD Services Offline,Print Server Error,Domain Controller Down,Unable to Connect to AD,Troubleshooting AD Downtime
thumbnail: https://thmb.techidaily.com/39b1aa90cbe15af25eeef086af2b40b5abbe4ea0e44addc2aa4ec5af37792daa.jpg
---

## PPrintError: Active Directory Service Unavailable

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  

 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  

2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-youtube-crafting-made-easy-with-free-templates/"><u>[New] 2024 Approved YouTube Crafting Made Easy with FREE Templates</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-logo-magic-sprucing-up-your-podcasts-visual-appeal/"><u>[Updated] Logo Magic Sprucing Up Your Podcast's Visual Appeal</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-blank-pages-no-more-fixing-printer-issues/"><u>Endless Blank Pages No More: Fixing Printer Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-wacom-tablet-when-it-stops-responding/"><u>How To Repair Your Wacom Tablet When It Stops Responding</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-xiaomi-redmi-13c-phone-by-drfone-android/"><u>How to Unlock a Network Locked Xiaomi Redmi 13C Phone?</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-12-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 12 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-nokia-130-music-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Nokia 130 Music Device SIM</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-sleepy-hp-laser-printers/"><u>Methods to Reactivate Sleepy HP Laser Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-network-printer-how-to-restore-visibility/"><u>Missing Network Printer - How to Restore Visibility</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/cting-your-presence-mastery-of-title-and-tag-use-on-youtube-for-2024/"><u>Perfecting Your Presence Mastery of Title and Tag Use on YouTube for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-hp-printer-paper-jam-resolved/"><u>Repair: HP Printer Paper Jam Resolved</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-language-of-interaction-engaging-viewers-on-youtube/"><u>The Language of Interaction Engaging Viewers on YouTube</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ultimate-tips-for-canon-print-setup/"><u>Ultimate Tips for Canon Print Setup</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Infinix GT 10 Pro? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-printer-spool-error-detected/"><u>Windows Printer Spool Error Detected</u></a></li>
</ul></div>

