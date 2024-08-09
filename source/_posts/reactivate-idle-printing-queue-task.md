---
title: Reactivate Idle Printing Queue Task
date: 2024-08-08T01:10:46.242Z
updated: 2024-08-09T01:10:46.242Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Reactivate Idle Printing Queue Task
excerpt: This Article Describes Reactivate Idle Printing Queue Task
keywords: Reactivate IDLE Printer Queue,Idle Printing Queue Management,Resume Idle Print Jobs,Restart Printer Queue Task,Printing Queue Idle Issue Resolution,Enable Idle Printer Tasks,Revive Non-Active Printer Queue
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Reactivate Idle Printing Queue Task

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Clear the print queue

 There are three options for you to clear the print queue. You don’t have to try them all; just take your pick.

#### Option 1: Restart the Print Spooler Service

1. On your keyboard, press the**Windows logo key** +**R** at the same time to open the**Run** box.
2. In the Run window, type**services.msc** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt-admin.jpg)
2. In the Command Prompt window, enter the following commands separately:

net stop spooler

del %systemroot%\System32\spool\printers\* /Q **/F /S**

net start spooler

This will clear all of your print jobs stuck in a queue.

#### Option 3: Create a Bat file for permanent use

 If you don’t want to go through all the trouble again, there’s a permanent fix for you to do this. Create your own batch file and you just need to open it every time you want to clear the print queue. Here is how to do it:

1. Open Notepad or Notepad++ (but not a word processor like Microsoft Word.)
2. Enter the following lines:  
 **net stop spooler**  
 **del %systemroot%\\System32\\spool\\printers\* /Q /F /S**  
 **net start spooler**  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/note.jpg)
3. Then click**File** \>**Save as…**  
   * Change the file type to**All files**  
   * Name your file whatever you want, but add a**.bat** suffix.  
   * Make sure the Encoding type is**ANSI** .  
   * Save the file. (Note where the file is saved.)  
   ![](https://images.drivereasy.com/wp-content/uploads/2020/01/batch-file.jpg)
4. Double-click the batch file to clear the print queue anytime you want.

### Fix 2: Reinstall the printer driver

 If your print jobs still get stuck in a queue, the main cause is a wrong or outdated printer driver. So you should update your printer driver to see if it fixes your problem.

 There are two ways to update your printer driver: manually or automatically.

#### Option 1: Install the printer driver manually

 Printer manufacturers such as HP, Canon, Brother, Dell, and Epson keep releasing new printer drivers to fix bugs and improve performance. To get them, you can go to your printer manufacturer’s website (always in the Support or Download section) and download the latest driver and install it manually.

* HP:[HP software and Driver Downloads](https://support.hp.com/us-en/drivers)
* Canon:[Canon Drivers & Downloads](https://www.usa.canon.com/internet/portal/us/home/support/drivers-downloads)
* Brother:[Brother Driver Downloads](https://www.brother-usa.com/brother-support/driver-downloads)
* Dell:[Dell Drivers & Downloads](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fsupport%2Fhome%2Fus%2Fen%2F04%3Fapp%3Ddrivers)
* Epson:[Epson Products & Drivers](https://global.epson.com/products%5Fand%5Fdrivers/)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/kisspng-pixel-illustration-printer-5a983b8a6f6aa4.5830009615199261544564.png)

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
5. Try printing again. Your printer should be working properly now.

---

 Hopefully, your printer can work like a charm now. However, if none of the fixes above solved your printer stuck in a queue, please check the USB or Wireless connection to make sure that your printer is communicating well with your computer or mobile phone.

Feel free to drop us a comment if you have any questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [printer](https://tools.techidaily.com/drivereasy/download/)
* [printer driver](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://printer-issues.techidaily.com/hardware-hp-printer-unresponsive-in-winxo/"><u>[Hardware] HP Printer Unresponsive in WINXO</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-best-practices-for-youtube-outro-design/"><u>[New] 2024 Approved  Best Practices for YouTube Outro Design</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-channel-discoveries-in-asmr-for-2024/"><u>[New] Best Channel Discoveries in ASMR for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-budget-friendly-video-stock-sites-for-2024/"><u>[Updated] Best Budget-Friendly Video Stock Sites for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-social-media-power-up-grouping-multiple-photos-and-vids-for-instagram/"><u>[Updated] Social Media Power-Up  Grouping Multiple Photos & Vids for Instagram</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-strategies-for-effective-360-video-broadcasts-on-fb-for-2024/"><u>[Updated] Strategies for Effective 360 Video Broadcasts on FB for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/3-top-ranked-fixes-for-integrated-hp-and-laptop-operation/"><u>3 Top-Ranked Fixes for Integrated HP and Laptop Operation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressing-the-blank-pages-from-your-epson-printer/"><u>Addressing the Blank Pages From Your Epson Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boost-print-speed-and-quality-download-hp-officejet-firmware/"><u>Boost Print Speed & Quality - Download HP Officejet Firmware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-code-b200/"><u>Corrected Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-laser-printer-errors/"><u>Decoding Laser Printer Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ease-into-plc-error-resolution/"><u>Ease Into PLC Error Resolution</u></a></li>
<li><a href="https://driver-install.techidaily.com/efficient-installation-windows-ie-management-drivers/"><u>Efficient Installation: Windows IE Management Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-printing-on-your-hp-printer-setup/"><u>Enabling Duplex Printing on Your HP Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-efficiency-printer-software-update-for-dell-and-win7/"><u>Enhance Efficiency: Printer Software Update for Dell & Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-printing-quick-fixes-for-canon-windows-10-compatibility/"><u>Enhance Printing: Quick Fixes for Canon, Windows 10 Compatibility</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-fixing-the-nspr4dll-file-not-detected-mistake/"><u>Expert Tips for Fixing the Nspr4.dll File Not Detected Mistake</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-epson-out-of-service/"><u>Fixed Epson Out Of Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/halted-outputs-ceased-on-epson-model/"><u>Halted Outputs Ceased on Epson Model</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>How Can I Use a Fake GPS Without Mock Location On Apple iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-vivo-y100mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Vivo Y100Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574168670-how-to-fix-a-printer-that-wont-print/"><u>How to Fix a Printer That Won’t Print</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-3-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord 3 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-engaging-essentials-leading-ig-filters/"><u>In 2024, Engaging Essentials  Leading IG Filters</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-honor-100-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Honor 100 Devices | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-9-apple-iphone-13-pro-max-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 9 Apple iPhone 13 Pro Max Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-tips-mfc-9330cdw-driver/"><u>Installation Tips: MFC-9330CDW Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/making-offline-brother-printer-a-priority-again/"><u>Making Offline Brother Printer a Priority Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/navigating-through-toner-trouble/"><u>Navigating Through Toner Trouble</u></a></li>
<li><a href="https://printer-issues.techidaily.com/new-mf4770n-software-package-for-windows-users/"><u>New MF4770n Software Package for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-issue-communications-unavailable/"><u>Print Issue: Communications Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-fixed-after-new-windows-version-patch/"><u>Printer Fixed After New Windows Version Patch</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hijacked-multiple-sessions-spotted/"><u>Printer Hijacked? Multiple Sessions Spotted</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-spooling-failure-in-windows-10/"><u>Printer Spooling Failure in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/realign-printer-settings-in-win10-environment/"><u>Realign Printer Settings in Win10 Environment</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recovering-windows-hp-printer-status/"><u>Recovering Windows HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-spits-out-unprinted-sheets/"><u>Resolved: Printer Spits Out Unprinted Sheets</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-canon-printer-issues-on-windows-10/"><u>Resolving Canon Printer Issues on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-reactivation-achieved-in-windows-11/"><u>Scanner Reactivation Achieved in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-stopped-working-after-windows-11-update/"><u>SOLVED: Printer Stopped Working After Windows 11 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-printer-solutions-unveiled/"><u>Speedy Printer Solutions Unveiled</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-non-responsive-printer-errors-in-nt-systems/"><u>Tackling Non-Responsive Printer Errors in NT Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-note-taking-game-with-chatgpt-pro-hacks-and-insights/"><u>Transform Your Note-Taking Game with ChatGPT: Pro Hacks and Insights</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-operational-usb-printers-in-sleep-mode-w7/"><u>Troubleshooting Non-Operational USB Printers in Sleep Mode, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-printer-config-issue-alert/"><u>Unexpected Printer Config Issue Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/visual-installation-guide-for-a-new-canon-printer/"><u>Visual Installation Guide for a New Canon Printer</u></a></li>
</ul></div>
