---
title: Successfully Installed Printer.
date: 2024-07-10T17:34:20.904Z
updated: 2024-07-11T17:34:20.904Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Successfully Installed Printer.
excerpt: This Article Describes Successfully Installed Printer.
keywords: Printer Installation Guide,How to Set Up Printer,Easy Printer Installation Tips,Step-by-Step Printer Setup,Troubleshooting Printer Installation Issues,Optimizing Printer Setup for Success,Wireless Vs. Wired Printer Installation Guide
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Successfully Installed Printer

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
<li><a href="https://printer-issues.techidaily.com/fix-inkjet-and-laser-issues-win10-style/"><u>Fix Inkjet & Laser Issues, Win10 Style</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-locate-canon-pixma-mp620-drivers-on-win10/"><u>Unable to Locate Canon Pixma MP620 Drivers on WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-hp-officejet-4630-latest-software-releases/"><u>Elevate HP Officejet 4630: Latest Software Releases</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printing-blockade-oxc4eb827f/"><u>Overcoming HP Printing Blockade: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-your-hp-printer-via-win32-api/"><u>Efficiently Setting Up Your HP Printer via Win32 API</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-printer-fault-resolutions/"><u>Mastering Printer Fault Resolutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-and-canons-mp620-a-driver-match/"><u>Windows 11 & Canon's MP620: A Driver Match?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectifying-fedex-printer-connectivity-troubles/"><u>Rectifying FedEx Printer Connectivity Troubles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-offline-workflow-blockage/"><u>Fixed Offline Workflow Blockage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-phantom-error-messages-on-printers/"><u>Repairing Phantom Error Messages on Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-alert-unable-to-locate-on-windows-10/"><u>[Printer Driver Alert]: Unable to Locate on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-office-printer-breakdowns/"><u>Overcoming Office Printer Breakdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installing-your-canon-printer-an-illustrated-tutorial/"><u>Installing Your Canon Printer - An Illustrated Tutorial</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-drive-efficiency-mf4770n-and-windows-systems/"><u>Boosting Drive Efficiency: MF4770n & Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574061275-b200-bug-fixed-ready-to-go/"><u>B200 Bug Fixed, Ready to Go</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-alert-canon-printer-not-detected-in-win10/"><u>[Update Alert] Canon Printer Not Detected in WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-incorrante-connectivity-linking-officejet-pro-to-pc/"><u>Guide: Incorrante Connectivity: Linking OfficeJet Pro to PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrade-dell-aio-printer-software-in-windows-7/"><u>Upgrade: Dell AIO Printer Software in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-driver-installation-complete/"><u>Print Driver Installation Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-continuous-spooler-failures-on-w10w11w7/"><u>Preventing Continuous Spooler Failures on W10/W11/W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-functional-print-devices/"><u>Troubleshooting Non-Functional Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-pcl-xl-errors-with-ease/"><u>Navigating Through PCL XL Errors with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-printerevolving-spooler-error-wx-w10-and-w11/"><u>Stop Printer'evolving Spooler Error (WX, W10 & W11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-delete-inactive-printers-in-windows-easy-way/"><u>How To Delete Inactive Printers in Windows Easy Way</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-printer-driver-glitches-on-win10-pc/"><u>Repair Printer Driver Glitches on WIN10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-errors-detected-during-printer-setup/"><u>No Errors Detected During Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-non-operation-on-windows-7-post-sleep/"><u>USB Printer Non-Operation on Windows 7 Post Sleep</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/what-is-t-series-income-on-youtube-for-2024/"><u>What Is T Series Income on YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-keyword-compendium-for-gamers-youtube-vids/"><u>[Updated] The Ultimate Keyword Compendium for Gamers' YouTube Vids</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-vivo-y100-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Vivo Y100 FRP Bypass</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-motorola-moto-g-stylus-2023-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-honor-90-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Honor 90 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dji-quadcopters-grades-budget-edition-enhanced-pro-elite-uhd/"><u>DJI Quadcopters Grades  Budget Edition, Enhanced Pro, Elite UHD</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-how-to-make-a-photo-video-with-pixiz/"><u>2024 Approved  How to Make a Photo Video with Pixiz ?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-tech-savvy-solutions-for-iphone-screenshots/"><u>[Updated] Tech Savvy Solutions for iPhone Screenshots</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-decoding-app-dynamics-an-in-depth-analysis-of-tiktok-and-snaps-similarities/"><u>[New] 2024 Approved  Decoding App Dynamics  An In-Depth Analysis of TikTok & Snap's Similarities</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-apple-iphone-8-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile Apple iPhone 8 online without SIM Card?</u></a></li>
</ul></div>
