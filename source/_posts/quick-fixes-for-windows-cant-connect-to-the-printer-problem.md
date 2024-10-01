---
title: Quick Fixes for 'Windows Can't Connect to the Printer' Problem
date: 2024-09-28T07:37:39.357Z
updated: 2024-10-01T00:42:05.080Z
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-advanced-cards-for-crystal-clear-output/"><u>[New] 2024 Approved Advanced Cards for Crystal Clear Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-missing-hp-support-in-windows-1110/"><u>[Print] Missing HP Support in Windows 11/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-needed-drivers-not-installing-hp-deskjet-d1360-on-windows/"><u>[Update Needed] Drivers Not Installing: HP Deskjet D1360 on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-google-pixel-fold-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Google Pixel Fold? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-sheet-overflow-in-an-epson-device/"><u>Correcting Sheet Overflow in an Epson Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-printer-malfunctions-post-win11-rollout/"><u>Fixed: Printer Malfunctions Post Win11 Rollout</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-infinix-gt-10-pro-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Infinix GT 10 Pro Back to Operation | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-back-to-normal-goodbye-ghost-bars/"><u>HP Printer Back to Normal: Goodbye, Ghost Bars</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-discover-the-10-best-cookie-places-in-town-with-unbeatable-taste/"><u>In 2024, Discover the 10 Best Cookie Places in Town with Unbeatable Taste</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-iphone-xs-max-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On iPhone XS Max in the Best Ways</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printer-blank-pages-challenge/"><u>Overcoming HP Printer Blank Pages Challenge</u></a></li>
<li><a href="https://extra-resources.techidaily.com/reducing-jitter-in-visual-content-creation/"><u>Reducing Jitter in Visual Content Creation</u></a></li>
<li><a href="https://extra-support.techidaily.com/render-dynamic-depth-on-digital-imagery-for-2024/"><u>Render Dynamic Depth on Digital Imagery for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/secure-your-contents-success-with-proper-srt-upload-methods-to-social-media/"><u>Secure Your Content's Success with Proper SRT Upload Methods to Social Media</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-inkjet-hp-not-printing-error/"><u>Solved: Inkjet HP Not Printing Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-strategies-correcting-pcl-xl-faults/"><u>Swift Strategies: Correcting PCL XL Faults</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-comprequad-video-captioning-techniques-for-youtube/"><u>The Comprequad Video Captioning Techniques for YouTube</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137972/21526" target="_top" id="2137972">
  <img src="//a.impactradius-go.com/display-ad/21526-2137972" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137972/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

