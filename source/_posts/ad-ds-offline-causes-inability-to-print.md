---
title: AD DS Offline Causes Inability To Print
date: 2024-06-28T06:53:38.292Z
updated: 2024-06-29T06:53:38.292Z
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
<li><a href="https://printer-issues.techidaily.com/expert-advice-swiftly-dealing-with-pcl-xl-fails/"><u>Expert Advice: Swiftly Dealing with PCL XL Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-os-error-drivers-not-found/"><u>Printer OS Error: Drivers Not Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solve-inkjet-driver-errors-on-w11/"><u>Solve Inkjet Driver Errors on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-non-responsive-hp-devices/"><u>Methods to Reactivate Non-Responsive HP Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restored-inkjet-efficiency-levels/"><u>Restored Inkjet Efficiency Levels</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-mf4770n-functions-on-w11w8w7-os/"><u>Streamlining MF4770n Functions on W11/W8/W7 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminate-paperjam-error-by-deleting-printer/"><u>Eliminate PaperJam Error by Deleting Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prevent-windows-10-printer-malfunctions-and-fails/"><u>Prevent Windows 10 Printer Malfunctions and Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-print-services-for-your-canon-device/"><u>Reclaiming Print Services for Your Canon Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-print-performance-dells-latest-aio-upgrades-in-win7/"><u>Optimize Print Performance: Dell's Latest AIO Upgrades in Win7</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-mp4-files-on-redmi-13c-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How to play MP4 files on Redmi 13C?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top-15-non-copyrighted-music-for-montages/"><u>New Top 15 Non Copyrighted Music for Montages</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pioneering-virtual-meetings-mastering-gmail-and-zoom-usage-together/"><u>[New] Pioneering Virtual Meetings  Mastering Gmail and Zoom Usage Together</u></a></li>
<li><a href="https://audio-editing.techidaily.com/mastering-pitch-adjustment-with-pristine-audacity-outputs-for-2024/"><u>Mastering Pitch Adjustment with Pristine Audacity Outputs for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-achieve-optimum-stability-incorrances-for-tripods-in-vlog-shoots/"><u>[New] 2024 Approved  Achieve Optimum Stability  Incorrances for Tripods in Vlog Shoots</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mobile-mastery-using-phone-as-a-camera-for-recording-for-2024/"><u>[Updated] Mobile Mastery  Using Phone as a Camera for Recording for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamline-success-blending-obs-zoom-made-easy-for-2024/"><u>Streamline Success  Blending OBS, Zoom Made Easy for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/free-video-trimmer-reviews-for-windows-10-online-and-offline-choices-for-2024/"><u>Free Video Trimmer Reviews for Windows 10 Online and Offline Choices for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-reclaim-lively-sounds-in-muted-video-tweets-for-2024/"><u>[Updated] Reclaim Lively Sounds in Muted Video Tweets for 2024</u></a></li>
</ul></div>
