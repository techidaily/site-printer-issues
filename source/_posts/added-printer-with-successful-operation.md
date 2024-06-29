---
title: Added Printer with Successful Operation
date: 2024-06-28T07:02:19.589Z
updated: 2024-06-29T07:02:19.589Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Added Printer with Successful Operation
excerpt: This Article Describes Added Printer with Successful Operation
keywords: Buy Wireless Printer,Best Inkjet Printer Setup,Easy-to-Use Printer Installation Guide,Top 5 Printers with Reliable Performance,How to Troubleshoot a New Printer,Printer Connectivity and Compatibility,Optimize Office Printing Efficiency
thumbnail: https://thmb.techidaily.com/589975317cd54578e2464cf37ff9c3436a24bffda2b797c9a9ae1ed0b5abaff9.jpg
---

## Added Printer with Successful Operation

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
<li><a href="https://printer-issues.techidaily.com/win11-update-inkjet-issues-remedied/"><u>Win11 Update: Inkjet Issues Remedied</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-brother-inkjet-without-faults/"><u>Enabling Brother Inkjet Without Faults</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-error-unable-to-install-mp620-printer-driver/"><u>Windows Error: Unable to Install MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-inactive-hp-printing-units/"><u>Reviving Inactive HP Printing Units</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-offline-printer-back-online/"><u>Win7 Offline Printer Back Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-updates-for-streamlined-windows-functionality/"><u>MF4770n Updates for Streamlined Windows Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-relief-for-queued-print-tasks/"><u>Immediate Relief for Queued Print Tasks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-needed-drivers-not-installing-hp-deskjet-d1360-on-windows/"><u>[Update Needed] Drivers Not Installing: HP Deskjet D1360 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicate-brother-printers-no-print-dilemma-on-windows/"><u>Eradicate Brother Printer's No-Print Dilemma on Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-lava-yuva-2-pro-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-elite-virtual-reality-setups-for-uavs/"><u>In 2024, Elite Virtual Reality Setups for UAVs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-speedy-steps-for-assembling-image-collections-on-mac/"><u>In 2024, Speedy Steps for Assembling Image Collections on Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-versatile-video-tools-for-linux-windows-and-macos-for-2024/"><u>Free, Versatile Video Tools for Linux, Windows & MacOS for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-real-time-vs-recorded-entertainment-twitch-vs-youtube-analysis/"><u>[New] Real-Time vs Recorded Entertainment  Twitch vs YouTube Analysis</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-device-based-access-commence-google-meet-chat/"><u>[Updated] Device-Based Access  Commence Google Meet Chat</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-google-pixel-7a-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Google Pixel 7a Quickly | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-infinix-hot-40-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Infinix Hot 40 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-clarifying-gap-between-full-view-and-immersive-videos/"><u>[New] Clarifying Gap Between Full View & Immersive Videos</u></a></li>
</ul></div>
