---
title: AD DS Offline Causes Inability To Print
date: 2024-07-10T16:47:43.004Z
updated: 2024-07-11T16:47:43.004Z
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
<li><a href="https://printer-issues.techidaily.com/os-troubleshoot-unseen-network-printer-on-windows-pcs/"><u>[OS Troubleshoot] Unseen Network Printer on Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-print-active-directory-offline/"><u>Unable To Print: Active Directory Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-printing-failure-in-hp-model-xyz/"><u>Overcome Printing Failure in HP Model XYZ</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-that-can-handle-full-document-sizes/"><u>Printers That Can Handle Full Document Sizes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-network-disconnectivity-in-hp-printers/"><u>Solving Network Disconnectivity in HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-erratic-printer-spooler-behavior-win-11-and-older/"><u>Fixing Erratic Printer Spooler Behavior (Win 11 & Older)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-error-code-following-device-suspend-w7/"><u>[Solved] Printer Error Code Following Device Suspend, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-adding-hp-printer-to-computer-network/"><u>Tutorial: Adding HP Printer to Computer Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/duplicate-device-printing-discovered-and-tackled/"><u>Duplicate Device Printing Discovered & Tackled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-pause-how-to-react/"><u>Canon Printer Pause: How To React?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ended-canons-code-b200-misstep/"><u>Ended Canon's Code B200 Misstep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-sheet-woes-end-with-hp-printer-update-fixed/"><u>White Sheet Woes End with HP Printer Update Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-full-potential-of-hp-printers-in-windows/"><u>Unlocking the Full Potential of HP Printers in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-perfection-achieved-say-goodbye-to-ghosts/"><u>Print Perfection Achieved: Say Goodbye to Ghosts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-print-problem-after-win-11-update/"><u>Resolved Print Problem After Win 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-clogged-toner-cartridges/"><u>Addressing Clogged Toner Cartridges</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructive-blueprint-attaching-hp-printer-8720-to-windows-system/"><u>Instructive Blueprint: Attaching HP Printer 8720 to Windows System</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-what-you-dont-know-about-mp3-converter-windows-but-should-a-revealing-article/"><u>Updated In 2024, What You Dont Know About Mp3 Converter Windows (But Should) A Revealing Article</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-front-runners-in-4k-gaming-graphics/"><u>In 2024, Front-Runners in 4K Gaming Graphics</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-rapidly-rendering-fortnite-cover-images-for-2024/"><u>[Updated] Rapidly Rendering Fortnite Cover Images for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/understanding-discord-the-ultimate-resource/"><u>Understanding Discord  The Ultimate Resource</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elite-collection-of-online-video-grabbers-and-savers/"><u>[Updated] In 2024, Elite Collection of Online Video Grabbers & Savers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-prodigious-plotlines-in-audio-playwriting/"><u>2024 Approved  Prodigious Plotlines in Audio Playwriting</u></a></li>
<li><a href="https://howto.techidaily.com/fix-vivo-v30-lite-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Vivo V30 Lite 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-achieving-peak-zoom-resolution-effective-techniques/"><u>[New] 2024 Approved  Achieving Peak Zoom Resolution  Effective Techniques</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-honor-70-lite-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-play-7t-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor Play 7T to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y100-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-step-by-step-harnessing-instagram-filters/"><u>[New] 2024 Approved  Step-by-Step  Harnessing Instagram Filters</u></a></li>
<li><a href="https://extra-information.techidaily.com/thoroughly-assessing-the-performance-of-theta-s/"><u>Thoroughly Assessing the Performance of Theta S</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-harmonize-your-preferences-how-to-create-an-engaging-youtube-playlist-for-2024/"><u>[Updated] Harmonize Your Preferences  How to Create an Engaging YouTube Playlist for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/xpert-tips-for-crafting-immersive-soundscapes-in-youtube-for-2024/"><u>[New] Expert Tips for Crafting Immersive Soundscapes in YouTube for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-uncover-the-top-10-for-capturing-live-events/"><u>[Updated] In 2024, Uncover the Top 10 for Capturing Live Events</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-poco-x6-frp-by-drfone-android/"><u>The Updated Method to Bypass Poco X6 FRP</u></a></li>
</ul></div>
