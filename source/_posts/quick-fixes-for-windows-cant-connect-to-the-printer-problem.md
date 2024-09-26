---
title: Quick Fixes for 'Windows Can't Connect to the Printer' Problem
date: 2024-09-24T19:29:03.490Z
updated: 2024-09-25T17:04:03.175Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Quick Fixes for 'Windows Can't Connect to the Printer' Problem
excerpt: This Article Describes Quick Fixes for 'Windows Can't Connect to the Printer' Problem
thumbnail: https://thmb.techidaily.com/ddb387910e1ac858898cd3858da4a32a6126aed2333f21b240bf9f3028949436.jpg
---

## Quick Fixes for 'Windows Can't Connect to the Printer' Problem

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-perfectly-organizing-weekly-google-meeting-times-for-2024/"><u>[New] Perfectly Organizing Weekly Google Meeting Times for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-support-steps-to-fix-vanished-printer-on-pcs/"><u>[Tech Support] Steps to Fix Vanished Printer on PCs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-seamlessly-connect-the-3-step-guide-to-enhanced-communication-on-snapchat-for-2024/"><u>[Updated] Seamlessly Connect The 3-Step Guide to Enhanced Communication on Snapchat for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-mastering-virtual-sessions-a-compreayer-to-using-zoom-in-windows-10/"><u>2024 Approved Mastering Virtual Sessions A Compreayer to Using Zoom in Windows 10</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/from-reels-to-filters-a-closer-look-at-tiktok-vs-snaps-features-for-2024/"><u>From Reels to Filters A Closer Look at TikTok vs Snap's Features for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-craft-natural-motion-depth-in-ps/"><u>In 2024, Craft Natural Motion Depth in PS</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-top-strategies-for-changing-song-pace-on-spotify-app/"><u>In 2024, Top Strategies for Changing Song Pace on Spotify App</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-driver-for-hp-printer-on-windows/"><u>Missing Driver for HP Printer on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-motorola-g24-power-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Motorola G24 Power – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-steps-for-setting-up-your-canon-printer-visual-aids/"><u>Quick Steps for Setting up Your Canon Printer (Visual Aids)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reduce-latency-in-printing-routine/"><u>Reduce Latency in Printing Routine</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-samsung-galaxy-m54-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solution-guide-for-opening-origin-on-windows-10-and-11-systems/"><u>Solution Guide for Opening Origin on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlock-printer-output-simple-remedies-for-canons-no-print-issues-in-windows-11/"><u>Unlock Printer Output: Simple Remedies for Canon's No-Print Issues in Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

