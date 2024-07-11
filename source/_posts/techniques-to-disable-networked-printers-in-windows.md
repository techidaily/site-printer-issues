---
title: Techniques to Disable Networked Printers in Windows
date: 2024-07-10T16:56:27.317Z
updated: 2024-07-11T16:56:27.317Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Techniques to Disable Networked Printers in Windows
excerpt: This Article Describes Techniques to Disable Networked Printers in Windows
keywords: Disable Network Printers,Windows Print Service Management,HP LaserJet Security,Canon Printer Access Control,Dell Inkjet Secure Configuration,Samsung Cartridge Lockdown,Brother Printer Privacy Settings
thumbnail: https://thmb.techidaily.com/43ea76cba9094b7e586764e6bda808f45025f38856a330aa448f0606df3e468d.jpg
---

## Techniques to Disable Networked Printers in Windows

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
<li><a href="https://printer-issues.techidaily.com/cdw-duo-fan-guide-for-brother-9330c/"><u>CDW Duo Fan Guide for Brother 9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-mf4770n-functionality-in-windows-ecosystems/"><u>Optimize MF4770n Functionality in Windows Ecosystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-pcl-xl-mistakes-with-ease/"><u>Tackling PCL XL Mistakes with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-connectivity-interruptions/"><u>Addressed Connectivity Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/untangling-non-responsiveness-in-canon-print/"><u>Untangling Non-Responsiveness in Canon Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-repaired-connectivity-issue/"><u>[PRINT] Repaired Connectivity Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-paper-feeder-malfunction/"><u>Overcome Paper Feeder Malfunction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-your-brother-printers-print-function-on-windows-1011/"><u>Reignite Your Brother Printer's Print Function on Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-not-responding-post-wake-from-sleep-w7/"><u>Printers Not Responding Post Wake From Sleep, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/exploring-efficient-methods-printer-and-laptop-harmony-achieved/"><u>Exploring Efficient Methods: Printer & Laptop Harmony Achieved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-document-output-on-windowshp/"><u>Streamlining Document Output on Windows/HP</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-steps-to-tackle-pcl-xl-setbacks/"><u>Effortless Steps to Tackle PCL XL Setbacks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-art-of-fixing-printer-problems-after-win-10/"><u>Mastering the Art of Fixing Printer Problems After Win 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-lan-configuration-for-w11-printers/"><u>Resolve LAN Configuration for W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-top-fixes-to-bridge-hp-printers-with-laptop-effortlessly/"><u>3 Top Fixes to Bridge HP Printers with Laptop Effortlessly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-pcl-xl-complications-swiftly/"><u>Navigating PCL XL Complications Swiftly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-solutions-to-overcome-pcl-xl-errors/"><u>Speedy Solutions to Overcome PCL XL Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-pixma-mp620-driver-elusive/"><u>Windows 11: Pixma MP620 Driver Elusive</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-epsons-error-x97/"><u>Fixing Epson's Error X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reestablish-links-essential-steps-to-solve-printer-woes/"><u>Reestablish Links: Essential Steps to Solve Printer Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-color-rejection/"><u>Printer's Color Rejection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-brother-printer-on-your-network/"><u>Troubleshooting Offline Brother Printer on Your Network</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-scan-failures-with-xerox/"><u>Correcting Scan Failures with Xerox</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-the-connection-process-of-hp-photosmart-all-in-one/"><u>Mastering the Connection Process of HP PhotoSmart All-In-One</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-path-problem-solved-error-code-0x00000709-conquered/"><u>Paper Path Problem Solved - Error Code 0X00000709 Conquered</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-epsons-ink-failure/"><u>Overcoming Epson's Ink Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-printer-driver-crashes-on-windows-11/"><u>Resolve Printer Driver Crashes on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-windows-photos-experience-with-music-and-aesthetic-filters/"><u>2024 Approved  Streamlining Windows Photos Experience with Music and Aesthetic Filters</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-pre-windows-10-era-to-windows-11-now/"><u>In 2024, From Pre-Windows 10 Era  To Windows 11 Now</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-crafting-compelling-iphone-shadow-images/"><u>[Updated] Crafting Compelling iPhone Shadow Images</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163288986-unlock-footballs-secrets-fc-manager-game-free-edition/"><u>Unlock Football's Secrets: FC Manager Game, Free Edition!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-tecno-camon-30-pro-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Tecno Camon 30 Pro 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-accelerate-your-footage-a-step-by-step-guide-to-time-lapse-videos/"><u>Updated 2024 Approved Accelerate Your Footage A Step-by-Step Guide to Time Lapse Videos</u></a></li>
<li><a href="https://techidaily.com/vivo-data-retrieval-tool-restore-lost-data-from-vivo-y100-5g-by-fonelab-android-recover-data/"><u>Vivo Data Retrieval tool – restore lost data from Vivo Y100 5G</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/00plus-gaming-channel-names-for-every-gamer-filmora-for-2024/"><u>[New] 100+ Gaming Channel Names for Every Gamer - Filmora for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/breakdown-of-profit-earning-potential-from-each-youtube-sponsored-post-for-2024/"><u>Breakdown of Profit  Earning Potential From Each YouTube Sponsored Post for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/getting-into-film-editing-made-easy/"><u>Getting Into Film Editing Made Easy</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-from-apple-iphone-7-plus-by-drfone-ios/"><u>How To Create an Apple Developer Account From Apple iPhone 7 Plus</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-updated-review-sonys-blu-ray-and-hd-masterpiece/"><u>[Updated] The Updated Review  Sony's Blu-Ray and HD Masterpiece</u></a></li>
</ul></div>
