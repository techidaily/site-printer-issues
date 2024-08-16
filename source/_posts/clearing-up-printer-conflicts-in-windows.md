---
title: Clearing Up Printer Conflicts in Windows
date: 2024-08-15T03:17:06.773Z
updated: 2024-08-16T03:17:06.773Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Clearing Up Printer Conflicts in Windows
excerpt: This Article Describes Clearing Up Printer Conflicts in Windows
keywords: Resolving Printer Issues,Fixing Windows Print Errors,Printer Conflict Troubleshooting,Windows Device Manager Guide,Printer Driver Update Steps,Windows Print Configuration Tips,Managing Multiple Printers in Windows
thumbnail: https://thmb.techidaily.com/c476c76efa4305c4184325fe1ddf82b7177bf5ea101e0b8dd34c17b0c21488b1.jpg
---

## Clearing Up Printer Conflicts in Windows

You just purchased a new printer and would like to replace the old one at home. You think you have removed the printer and its driver, but when you reboot your computer, you can still see the printer’s icon, the only difference is that the icon all grayed out. In this case, it becomes impossible for you to uninstall or remove it again.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-grey-out.png)

Luckily, this is an easy problem to solve. Follow the steps below to fix the problem by yourself. 1) Click the**Start**button and type**cmd.exe** in the search box. Then right-click **c** **md** and click**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-ad-administrator.jpg) 2) Type in the command**print /s /t2**and hit**Enter**key on your keyboard. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/printui-s-t2.png) 3) Then you will be lead to this page. Try remove your printer driver now by selecting it and click the**Remove**button. Please remember to press**OK**to save the change. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-printer.jpg) 4) Then go to**Devices and Printers**panel by following this path: **Control Panel> Hardware and Sound> Devices and Printers**. Locate the printer that you would like to remove and right click it to choose**Remove device**.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-device.jpg)

5) If the above steps don’t work, press the   **Windows key ![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-key.png)** and**R**at the same time to invoke a Run command. Type**services.msc** and press **Enter**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/services-msc-in-run.png) 6) Locate**PrinterSpooler**service. Right-click it and select **Properties**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/printerspooler-service.jpg) 7) Then select **Stop**service. Click**OK**to exit. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/stop-printer-service.png) 8) Follow the path **My Computer\\C:\\Windows\\System32\\spool\\Printers**.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-folder-600x281.jpg)

If prompted for permission to go to this folder, click**Continue**or**Yes**to continue the procedure.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b4334888efa.png)

9) Press**Ctrl + A**to select all the information in this folder and right click to click **Delete**. 10) Go to**Services**panel again to restart the**PrinterSpooler**service.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-service-restart.jpg)

Click**Start**. Then click**OK**to exit.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/restart-services-printer.png)

You might want to reboot your computer at this point. 11) Repeat step 1) to step 4). This time it should work. 12) If necessary, please go to**Ports**tab and see if you need to remove any TCP/IP ports that are associated with the old printer.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-port.jpg)

That’s all you need to do!

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
<li><a href="https://printer-issues.techidaily.com/error-fixing-unable-to-add-hp-d1360-drivers-in-windows-oses/"><u>[Error Fixing] Unable to Add HP D1360 Drivers in Windows OSes</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-unlocking-the-potential-of-monetized-vlogs/"><u>[New] 2024 Approved  Unlocking the Potential of Monetized Vlogs</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-audio-artists-approach-to-video-unboxing/"><u>[New] The Audio Artist's Approach to Video Unboxing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlock-your-potential-with-outstanding-instagram-visuals-for-2024/"><u>[New] Unlock Your Potential with Outstanding Instagram Visuals for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-10/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-error-unable-to-install-mp620-drivers-in-win10/"><u>[System Error] Unable to Install MP620 Drivers in WIN10</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-enhance-and-unblur-photo-editing-tools-ranked-1-10/"><u>[Updated] 2024 Approved  Enhance and Unblur  Photo Editing Tools Ranked #1-10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-into-every-detailed-detail-expert-strategies-to-record-immersive-sims-4-adventures/"><u>[Updated] 2024 Approved  Into Every Detailed Detail  Expert Strategies to Record Immersive Sims 4 Adventures</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-enhancing-your-digital-presence-fb-video-creation-basics/"><u>[Updated] In 2024, Enhancing Your Digital Presence  FB Video Creation Basics</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unpacking-video-editing-excellence-is-inshot-at-the-top/"><u>2024 Approved  Unpacking Video Editing Excellence  Is InShot at the Top?</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-oppo-a79-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Oppo A79 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-printer-no-show-on-windows-me-edition/"><u>Addressing Printer No-Show on Windows ME Edition</u></a></li>
<li><a href="https://driver-install.techidaily.com/audio-device-compatibility-issues-no-more-in-windows/"><u>Audio Device Compatibility Issues No More in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-mf4770n-driver-update-in-windows-1087/"><u>Canon MF4770n Driver Update in Windows 10/8/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cant-connect-my-printer-help-required/"><u>Cant Connect My Printer - Help Required</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-ink-cartridge-errors-in-printers/"><u>Decoding Ink Cartridge Errors in Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/disabling-scanner-error-cleared-in-win11/"><u>Disabling Scanner Error Cleared in Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-correct-power-settings-on-devices/"><u>Enabling Correct Power Settings on Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printer-efficiency-quickly/"><u>Enhance Printer Efficiency Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhanced-performance-officejet-pro-8600-driver-for-windows/"><u>Enhanced Performance: Officejet Pro 8600 Driver for Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-poco-m6-pro-4g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Poco M6 Pro 4G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-connect-canon-printer-to-wifi-easily/"><u>How to Connect Canon Printer to Wifi Easily</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-ensure-optimal-performance-updating-the-logitech-c920-driver-on-multiple-windows-versions/"><u>How to Ensure Optimal Performance: Updating the Logitech C920 Driver on Multiple Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-overhaul-say-goodbye-to-unprinted-pages/"><u>HP Printer Overhaul: Say Goodbye to Unprinted Pages</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-extensive-review-the-360-degree-capture-of-samsung/"><u>In 2024, Extensive Review  The 360-Degree Capture of Samsung</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fast-forward-to-flawless-windows-11-photography/"><u>In 2024, Fast Forward to Flawless Windows 11 Photography</u></a></li>
<li><a href="https://printer-issues.techidaily.com/jumpstart-your-stationary-machine-fix-canon-printer-offline/"><u>Jumpstart Your Stationary Machine: Fix Canon Printer Offline</u></a></li>
<li><a href="https://printer-issues.techidaily.com/maximize-printer-potential-with-hp-inkjet-updates/"><u>Maximize Printer Potential with HP Inkjet Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-networked-printer-issues/"><u>Navigating Through Networked Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-mf4770n-functionality-in-windows-ecosystems/"><u>Optimize MF4770n Functionality in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-on-laptops-with-improved-hp-printer-links/"><u>Optimize Printing on Laptops with Improved HP Printer Links</u></a></li>
<li><a href="https://techidaily.com/solved-the-file-is-corrupted-and-cannot-be-opened-excel-2007-stellar-by-stellar-guide/"><u>Solved - The File is Corrupted and Cannot be Opened - Excel 2007 | Stellar</u></a></li>
<li><a href="https://extra-resources.techidaily.com/streamlined-process-for-avi-transformations-into-web-friendly-gif-using-filmora/"><u>Streamlined Process for AVI Transformations Into Web-Friendly GIF Using Filmora</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-laser-troubleshooting/"><u>Streamlining Laser Troubleshooting</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/understanding-fps-making-a-choice-between-30-and-60-hertz-for-2024/"><u>Understanding FPS  Making a Choice Between 30 & 60 Hertz for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-instantly-convert-dailymotion-videos-to-mp4-avi-etc-for-2024/"><u>Updated Instantly Convert Dailymotion Videos to MP4, AVI, Etc for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->