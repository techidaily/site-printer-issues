---
title: Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
date: 2024-10-11T20:08:28.408Z
updated: 2024-10-17T22:39:48.546Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
excerpt: This Article Describes Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively
thumbnail: https://thmb.techidaily.com/e4e90e7c9acadc523d8e4202425b18a9d8056d3f1cd618361a73d2cd13f94e4f.jpg
---

## Resolve 'Windows Can't Access Printer' Problem Quickly & Effectively

When you are trying to add a network shared printer, if you receive message “Windows cannot connect to the printer.”(commonly occur to Windows 7), you must be very frustrated. But don’t worry. You can use solutions in this post to fix the problem. Each solution has been reported to be useful. So try all of them until you have the problem fixed. 

 The error would appear with a specific error code like 0x0000007e. The most common error codes are as follows:

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59226592e8079.jpg) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x0000007e_ 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592265c744f96.png) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x00000002_ 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59226608a5031.jpg) 

 _Windows Cannot Connect to the Printer – Operation Failed with Error 0x0000007a_ 

[**Solution 1: Restart Print Spooler Service**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 2: Create a New Local Port**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 3: Delete Printer Drivers**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 4: Copy “mscms.dll” Manually**](https://tools.techidaily.com/drivereasy/download/)   
[**Solution 5: Delete a Subkey**](https://tools.techidaily.com/drivereasy/download/) 

##   **Solution 1: Restart Print Spooler Service** 

Follow steps below to stop Print Spooler service then start it again.

 1\. Press**Win+R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 2\. Type **services.msc** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592282c0cbfe5.png) 

 3\. In the**Name** list, locate and double-click on service **Print Spooler** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592282f40baaf.jpg) 

 3\. Under Service status, click**Stop** button. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228346254fb.png) 

 4\. Click**Start** button to start the service again.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922837fce75a.png) 

 5\. Click**OK** button.

 After that, add the printer again and see if the problem persists.

 ##  Solution 2: Create a New Local Port

Follow these steps:

 1\. Open[Control Panel](https://tools.techidaily.com/drivereasy/download/) .

 2\. View by Large icons, click**Devices and Printers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592284396a5e3.jpg) 

 3\. Click**Add a printer** at the top of the window.**Note:** To continue, you need to login to the computer as an administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592284c312e63.jpg) 

 4\. Select**Add a network, wireless or Bluetooth printer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592285527f2ca.jpg) 

 5\. Select**Create a new port** , change the “Type of port” to**Local Port** then click**Next** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922878323a31.jpg) 

 6.**Enter a port name** in the box. The port name is the printer’s address. The address format is **\\\\IP address or the Computer Name\\Printer’s Name** (refer to the following screen). Then click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228a6291554.png) 

 7\. Select the**printer model** from the directory and click**Next** button. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228e9593ce0.jpg) 

8\. Follow the rest on-screen instructions to finish adding the printer.

 ##   **Solution 3: Delete Printer Drivers** 

 The problem can be caused by printer drivers. So you can try to remove the drivers and install them again.

Follow steps below:

 1\. Press**Win+R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 2\. Type **printmanagement.msc** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59228fef1fe19.png) 

 3\. In the left pane, click**All Drivers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_59229062a2cbc.jpg) 

 4\. In the right pane, right-click on the printer driver and click**Delete** on the pop-up menu. 

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592290cca70ff.jpg) 

 If you see more than one printer driver names, repeat steps above to remove them one by one.

5\. Add the printer again. 

 If the problem persists, you may want to install the driver manually. You can download and install the driver from the printer manufacturer’s website. 

 If you have difficulty downloading the driver manually, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to help you. Driver Easy can scan your computer to detect all problem drivers then provide you with new drivers instantly. **[Download its Free version to have a try](https://tools.techidaily.com/drivereasy/download/)**  . If you find it helpful, you can consider upgrading to the Pro version. The Pro version allows you to update all drivers with just one-click.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592292ec90631.png) 

 ##  Solution 4: Copy “mscms.dll” Manually

 1\. Open**C:\\Windows\\system32** and find the file “**mscms.dll** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_592294768b3e2.jpg) 

2\. Copy the file to the following path:

 **C:\\windows\\system32\\spool\\drivers\\x64\\3\\ if you are using 64-bit windows**   
 **C:\\windows\\system32\\spool\\drivers\\w32x86\\3\\ if you are using 32-bit windows** 

 If you have no idea which version of Windows you are using, see[How to Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) .

3\. Try to connect to the printer again.

 ##  Solution 5: Delete a Subkey

 Modifying registry keys incorrectly may cause serious system problems. So before you get started, it is recommended that you[back up the registry key](https://tools.techidaily.com/drivereasy/download/) so you can restore it in case any problems occurs.

 1\. Stop **Print Spooler** service. (refer steps in Solution 1 to stop the service)

 2\. Press**Win + R** (Windows logo key and R key) at the same time. A Run dialog box will open.

 3\. Type **regedit** in the run box and click**OK** button.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/img_5922973c415cc.png) 

 4\. Expand   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows NT\\CurrentVersion\\Print\\Providers\\Client Side Rendering Print Provider** . Right-click on **Client Side Rendering Print Provider** and select**Delete.** 

5\. Start the Print Spooler service.

6\. Reboot your computer and try to add the printer again.

 Hope the solutions here will help you fix the printer not connecting issue.

* [printers](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://printer-issues.techidaily.com/error-alert-canon-pixma-mp620-not-detected-by-win10/"><u>[Error Alert] Canon Pixma MP620 Not Detected by WIN10</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-to-toolwiz-photosapp-for-photographers/"><u>[New] The Ultimate Guide to Toolwiz PhotosApp for Photographers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-from-front-to-back-mastering-instagram-video-spins-for-maximum-impact-for-2024/"><u>[Updated] From Front to Back Mastering Instagram Video Spins for Maximum Impact for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-gain-traction-with-effective-video-descriptions-and-tagging/"><u>[Updated] Gain Traction with Effective Video Descriptions and Tagging</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-the-online-marketplace-for-profitable-yt-content/"><u>[Updated] Navigating the Online Marketplace for Profitable YT Content</u></a></li>
<li><a href="https://driver-download.techidaily.com/complete-guide-how-to-install-and-update-logitech-g402-drivers/"><u>Complete Guide: How to Install and Update Logitech G402 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-tutorial-setting-up-an-hp-photosmart-x529i/"><u>Connectivity Tutorial: Setting Up an HP PhotoSmart X529i</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-the-problem-only-empty-prints-from-your-epson-device/"><u>Fix the Problem: Only Empty Prints From Your Epson Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/foreign-processors-print-job-revealed/"><u>Foreign Processor's Print Job Revealed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-offline-now-functioning/"><u>HP Printer Offline, Now Functioning</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventative-measures-against-spooler-shutdowns-win/"><u>Preventative Measures Against Spooler Shutdowns (Win)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-printer-output-5-effective-steps-for-non-printing-canon-on-windows-11/"><u>Reignite Printer Output: 5 Effective Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-realme-12-proplus-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Realme 12 Pro+ 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unboxing-truecaller-essential-review-for-potential-users/"><u>Unboxing TrueCaller: Essential Review for Potential Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgraded-os-resolved-printer-disruption/"><u>Upgraded OS, Resolved Printer Disruption</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-12-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Xiaomi Redmi 12 support - Turn Off Screen Lock.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

