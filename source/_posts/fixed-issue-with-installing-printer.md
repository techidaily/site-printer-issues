---
title: Fixed Issue with Installing Printer
date: 2024-06-28T07:02:35.390Z
updated: 2024-06-29T07:02:35.390Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fixed Issue with Installing Printer
excerpt: This Article Describes Fixed Issue with Installing Printer
keywords: Printer Installation Troubleshooting,Resolved Print Driver Installation Errors,How to Fix Common Printer Setup Issues,Guides for Successful Printer Installation,Step-by-Step Guide for Printer Connection and Configuration,Tips for Correcting Printer Hardware Installation Problems,Help with Printer Driver Installation
thumbnail: https://thmb.techidaily.com/2bedac5967dc2670719be619f6173feb9adb0500628b631392642fa41c539d87.jpg
---

## Fixed Issue with Installing Printer

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57971bf8a9ed1.png)

 “**Unable to install Printer.Operation could not be completed** ” could occur during installing printer or using the printer, especially after a Windows upgrade or reinstall. The problem can be caused by several issues. If you run into this problem, just try the **three**  solutions below and the problem should resolve.

## Solution**1: Start the Print Spooler service**

 The problem can occur if the print spooler service is stopped. So make sure the service is started. If it’s stopped, start it. To check and start the service, follow these steps:

1) Press **Win+R**  (Windows logo key and R key) at the same time to invoke the Run box.

2) Type **services.msc** in the run box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57870f53c80aa.png)

3) Double-click on**Sprint Spooler** to open the Properties dialog box.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57870fec6b0f3.png)
  
 4) If the “Service status” is Stopped, click the **Start** button. And make sure the “Startup type” has been set as**Automatic** . After that, click the **OK** button to save the change.  

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5797242d45d94.png)

5) Reboot your PC for the change to take effect.

This should fix the problem. If not, proceed to solution 2.

---

## **Solution 2: Update the printer driver**

 A faulty, corrupt or missing printer driver can caused “Unable to install Printer.Operation could not be completed” error. To resolve the issue, you can update the printer driver.

 If you don’t have time, patience and computer skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. **But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee)** :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b6276881dc81.jpg)

 3) Click the **Update** button next to the printer driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b627664eb496.jpg)

4) After updating the driver, check to see if the problem is resolved.

---

## **Solution 3: Delete the printer keys**

 The problem can be caused by driver conflicting. To resolve the problem, you can delete the certain registry entries.

**IMPORTANT** : Modifying registry incorrectly can cause serious system issues. Before following the below procedures, it’s recommended that you back up the registry first, then you could restore them if necessary. See [How to Back Up and Restore Registry](https://tools.techidaily.com/drivereasy/download/) .

To delete the printer keys, here’s what you need to do:

**Firstly, Stop the “Print Spooler” service first** (Refer to**Solution 1** to stop the Print Spooler service). Then follow steps below:

1) Delete all contents from following folders:

**C:\\Windows\\System32\\Spool\\Printers**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5797354018fd8.png)
  
 **C:\\Windows\\System32\\Spool\\Drivers\\w32x86**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57973526811ea.png)

2) Press **Win+R** (Windows logo key and R key) at the same time to invoke the Run box.

3) Type**regedit**  in the run box and click **OK** to open  the Registry Editor dialog box.  

![](https://images.drivereasy.com/wp-content/uploads/2016/03/img_56fb391581cd9.png)

 4) Locate the following registry key according to the system version installed on your PC . If you’re not sure what specific version of Windows you have, refer to [Quickly Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) .

 For**32-bit** operating system:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Print\\Environments\\Windows NT x86\\Drivers\\Version-x** (Note x will be a different number in different PC. In my case, it is version-3.)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972e8c6def5.png)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972ed64a5f9.png)

For   **64-bit** operating system:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Print\\Environments\\Windows x64\\Drivers\\Version-x**  (Note x will be a different number in different PC. In my case, itis version-3.)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972e8c6def5.png)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972f5298c63.png)

 5) Select this folder and you will see all printer registry entries in right pane. Right-click on the entry and select**Delete** from the context menu. Delete all registry entries here.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57981fd9161d2.png)

6) Start the “Print Spooler” service.

7) Reboot your PC and check to see if the problem is resolved.

---

 Hopefully solutions here will help you fix the “Unable to install Printer.Operation could not be completed” error. If you have any questions, feel free to leave your comments below. We’d love to hear of any ideas or suggestions.

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
<li><a href="https://printer-issues.techidaily.com/epsons-confounding-error-0x97-explained/"><u>Epson's Confounding Error 0X97 Explained</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensuring-regular-maintenayer-print-function/"><u>Ensuring Regular Maintenayer Print Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unknown-computer-known-printer-case-closed/"><u>Unknown Computer, Known Printer - Case Closed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-lexmark-printer-glitches/"><u>Addressing Lexmark Printer Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/realign-printer-settings-in-win10-environment/"><u>Realign Printer Settings in Win10 Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-non-responsive-print-devices/"><u>Solutions for Non-Responsive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-installation-guide-for-windows/"><u>HP Printer Installation Guide for Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-page-without-a-glitch-now/"><u>Print Every Page without a Glitch, Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/method-to-forget-your-printer-in-windows/"><u>Method to Forget Your Printer in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-the-mystery-of-epson-error-0x97/"><u>Solving the Mystery of Epson Error 0X97</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-action-recorders-for-motion-compensation/"><u>In 2024, Premium Action Recorders for Motion Compensation</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/unveiling-top-audio-capture-alternatives-your-ultimate-resource-guide-to-free-voice-recorders-for-the-upcoming-year-for-2024/"><u>Unveiling Top Audio Capture Alternatives Your Ultimate Resource Guide to Free Voice Recorders for the Upcoming Year for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-proven-leaders-in-yoga-the-best-10-youtube-video-resources/"><u>[New] Proven Leaders in Yoga  The Best 10 YouTube Video Resources</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-ultimate-gameplay-visualization-tools-for-2024/"><u>[New] Ultimate Gameplay Visualization Tools for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-12-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>In 2024, Unlocking iPhone 12 Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-unlocking-the-full-potential-of-obs-for-your-mac/"><u>[Updated] 2024 Approved  Unlocking the Full Potential of OBS for Your Mac</u></a></li>
<li><a href="https://screen-capture.techidaily.com/delving-into-recmeisters-capabilities-for-quality-video-capture-for-2024/"><u>Delving Into Recmeister’s Capabilities for Quality Video Capture for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-streamlining-your-approach-to-downloading-large-amounts-on-tiktok-for-2024/"><u>[Updated] Streamlining Your Approach to Downloading Large Amounts on TikTok for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-cataloging-spots-to-purchase-authentic-glass-bashing-noises/"><u>New 2024 Approved Cataloging Spots to Purchase Authentic Glass-Bashing Noises</u></a></li>
</ul></div>