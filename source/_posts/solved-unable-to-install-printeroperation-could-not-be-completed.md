---
title: "[Solved] Unable to Install Printer.Operation Could Not Be Completed"
date: 2024-06-28T07:12:50.116Z
updated: 2024-06-29T07:12:50.116Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes [Solved] Unable to Install Printer.Operation Could Not Be Completed
excerpt: This Article Describes [Solved] Unable to Install Printer.Operation Could Not Be Completed
keywords: Printer Installation Troubleshooting,Fix Unable Printer Installation,Resolve Print Setup Errors,Install Officejet Printer,Printer Setup Guide,How to Install Printer on Windows/Mac,Troubleshooting Print Device Setup
thumbnail: https://thmb.techidaily.com/7ad836b78743150f7926162559e15271095acf4f64d610e7943b29ad8777b2c6.jpg
---

## [Solved] Unable to Install Printer.Operation Could Not Be Completed

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
<li><a href="https://printer-issues.techidaily.com/reactivating-online-status-of-windowshp-multi-function/"><u>Reactivating Online Status of Windows/HP Multi-Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-now-solved/"><u>Error B200 Now Solved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-windows-hp-printer-offline/"><u>Resolving Windows HP Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-connected-successfully/"><u>Resolved: PRINTER Connected Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-online-after-repair/"><u>Win7 Printer Online After Repair</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-usb-printer-reset-problems-post-sleep-cycle/"><u>Win7 USB Printer Reset: Problems Post-Sleep Cycle</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resetting-failed-printer-defaults-error-code-0x00000709-overcome/"><u>Resetting Failed Printer Defaults: Error Code 0X00000709 Overcome</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/gecata-game-recorder-review-complete/"><u>Gecata Game Recorder Review [Complete]</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-ditch-adobe-top-10-premiere-elements-competitors-for-video-editing/"><u>New Ditch Adobe? Top 10 Premiere Elements Competitors for Video Editing</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-beginners-path-vrecord-instalment-manual/"><u>[New] In 2024, Beginners' Path  VRecord Instalment Manual</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-quick-steps-to-elevate-low-quality-webcam-vids/"><u>[Updated] 2024 Approved  Quick Steps to Elevate Low-Quality WebCam Vids</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-essential-recorder-applications-for-educators/"><u>In 2024, Essential Recorder Applications for Educators</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-a-beginners-guide-to-professional-gif-creation/"><u>[New] A Beginner's Guide to Professional GIF Creation</u></a></li>
<li><a href="https://some-tips.techidaily.com/transforming-everyday-moments-with-ioss-complete-life-story-for-2024/"><u>Transforming Everyday Moments with iOS's Complete Life Story for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-green-screen-journey-begins-on-yt-ideas-take-flight/"><u>2024 Approved  Green Screen Journey Begins on YT, Ideas Take Flight!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-mastering-live-twitch-streams-top-5-tips/"><u>[New] Mastering Live Twitch Streams  Top 5 Tips</u></a></li>
</ul></div>
