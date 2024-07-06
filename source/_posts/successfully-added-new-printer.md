---
title: Successfully Added New Printer
date: 2024-06-28T07:22:52.523Z
updated: 2024-06-29T07:22:52.523Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Successfully Added New Printer
excerpt: This Article Describes Successfully Added New Printer
keywords: Adding New Printer Installation Guide,Successful Printer Setup Procedures,How to Add a New Printer Successfully,Guidelines for Adding New Office Printers,Easy Steps to Install a New Printing Device,Seamless Integration of New Printer in Businesses,New Printer Addition Techniques and Tips
thumbnail: https://thmb.techidaily.com/50d4bf6106cc2e789648c53429943f049229011e6f572fe9945c7d91985d72b7.jpg
---

## Successfully Added New Printer

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
<li><a href="https://printer-issues.techidaily.com/fix-windows-7-devices-not-recognizing-post-sleep-usb-printers/"><u>[Fix] Windows 7 Devices Not Recognizing Post Sleep USB Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/harmonizing-office-efficiency-with-quick-fixes-for-printerpluslaptop-linkage/"><u>Harmonizing Office Efficiency with Quick Fixes for Printer+Laptop Linkage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-tutorial-setting-up-an-hp-photosmart-x529i/"><u>Connectivity Tutorial: Setting Up an HP PhotoSmart X529i</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-tips-how-to-reinstall-a-lost-print-job/"><u>[Windows Tips] How to Reinstall a Lost Print Job</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-print-drivers-troubleshooting-across-windows-versions/"><u>HP Deskjet D1360 Print Drivers: Troubleshooting Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-b200/"><u>Error Resolution: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-hp-xp-paper-issue/"><u>Troubleshooting Offline HP XP Paper Issue</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-iphone-7-plus-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From iPhone 7 Plus in the Best Ways</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/peek-into-fb-episodes-unseen/"><u>Peek Into FB Episodes, Unseen</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-elevate-your-facebook-presence-optimizing-video-cover-size-and-quality-for-2024/"><u>Updated Elevate Your Facebook Presence Optimizing Video Cover Size and Quality for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-music-video-magic-10-essential-software-and-apps-for-creators/"><u>Updated Music Video Magic 10 Essential Software and Apps for Creators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-should-itop-screen-recorder-be-a-staple-in-your-kit/"><u>[Updated] In 2024, Should ITop Screen Recorder Be a Staple in Your Kit?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/leading-music-editor-tools-ranked-windows-and-mac-edition-top-10-for-2024/"><u>Leading Music Editor Tools Ranked Windows & Mac Edition, Top 10 for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo Find X6 | Dr.fone</u></a></li>
</ul></div>
