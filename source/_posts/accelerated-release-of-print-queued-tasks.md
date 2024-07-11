---
title: Accelerated Release of Print Queued Tasks
date: 2024-07-10T17:02:19.884Z
updated: 2024-07-11T17:02:19.884Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerated Release of Print Queued Tasks
excerpt: This Article Describes Accelerated Release of Print Queued Tasks
keywords: Print Job Scheduling,Rapid Print Processing,Print Queue Optimization,Accelerated Print Workflows,Print Task Release Enhancement,Enhanced Print Queue Management,Faster Printer Task Execution
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Accelerated Release of Print Queued Tasks

 Have you ever run into a situation like this: you sent a job to the printer, but it just refused to print? Your print job fails and gets stuck in a queue. However you try to delete or cancel your print job, it just won’t go away!

 Don’t panic. Many users have reported the same issue, and it’s quite easy to fix.

## Try these fixes

* **Fix 1 –[Clear the print queue](#m1)**  
   1. [Restart the Print Spooler Service](#f1)  
   2. [Use Command Prompt to Clear Stuck Files](#f2)  
   3. [Create a Bat file for permanent use](#f3)
* **Fix 2 –[Reinstall your printer driver](#m2)**

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
<li><a href="https://printer-issues.techidaily.com/revive-windows-9598-print-jobs-that-wont-respond/"><u>Revive Windows 95/98 Print Jobs That Won't Respond</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-up-your-hp-laserjet-remote-connection/"><u>Setting Up Your HP LaserJet Remote Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-incompatible-printer-drivers-for-hp-d1360-in-windows/"><u>Resolving Incompatible Printer Drivers for HP D1360 in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mending-non-operational-printers/"><u>Mending Non-Operational Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/making-offline-brother-printer-a-priority-again/"><u>Making Offline Brother Printer a Priority Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-printers-victory-over-the-white-paper-plague/"><u>A Printer's Victory Over the White Paper Plague</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-canon-printer-fixes-for-windows-users/"><u>Effortless Canon Printer Fixes for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-detected-unable-to-connect-pixma-mp620-to-win10/"><u>[Driver Not Detected] Unable to Connect Pixma MP620 to WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-printer-woes-time-to-act/"><u>Windows 11 Printer Woes? Time to Act</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-full-potential-of-hp-printers-in-windows/"><u>Unlocking the Full Potential of HP Printers in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-xerox-halt-error-codes/"><u>Fix: Xerox Halt - Error Codes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dont-let-offline-be-the-end-for-your-canon-printer/"><u>Don’t Let Offline Be the End for Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recovering-windows-hp-printer-status/"><u>Recovering Windows HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canons-error-b200/"><u>Fixed Canon's Error: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inability-to-print-in-full-colors/"><u>Inability to Print in Full Colors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-misstep-unanticipated-setup-fiasco/"><u>Printer Misstep: Unanticipated Setup Fiasco</u></a></li>
<li><a href="https://printer-issues.techidaily.com/white-sheet-woes-end-with-hp-printer-update-fixed/"><u>White Sheet Woes End with HP Printer Update Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-troubleshoot-printer-hiccups/"><u>Windows 11 Troubleshoot Printer Hiccups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-xerox-document-generation/"><u>Restoring Xerox Document Generation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-connectivity-crunch-windows-7-usb-printer-dormancy/"><u>[Resolved] Connectivity Crunch: Windows 7 USB Printer Dormancy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-print-drivers-troubleshooting-across-windows-versions/"><u>HP Deskjet D1360 Print Drivers: Troubleshooting Across Windows Versions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printing-issues-post-suspend-with-win7/"><u>USB Printing Issues Post-Suspend with Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-printer-driver-glitches-on-win10-pc/"><u>Repair Printer Driver Glitches on WIN10 PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-efficient-data-flow-for-printers/"><u>Restoring Efficient Data Flow for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/bridge-the-gap-reactivate-and-recover-from-printer-disconnect/"><u>Bridge the Gap: Reactivate and Recover From Printer Disconnect</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-ghost-print-job-errors/"><u>Eliminating Ghost Print Job Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/success-story-unshackling-printer-from-update-chains/"><u>Success Story: Unshackling Printer From Update Chains</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tech-tip-revive-missing-windows-xp10-printer/"><u>[Tech Tip] Revive Missing Windows XP/10 Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-all-in-one-printers-connectivity-armored-up/"><u>HP All-in-One Printer's Connectivity Armored Up</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unified-printer-software-solution-officejet-pro-8600-for-windows-pcs/"><u>Unified Printer Software Solution: Officejet Pro 8600 for Windows PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-print-process-uncover-these-simple-steps-for-non-printing-canon-on-windows-11/"><u>Streamline Print Process: Uncover These Simple Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solution-to-hp-inkjet-non-operational-on-win11/"><u>Solution to HP Inkjet Non-Operational on Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/inkjet-resumed-solved-epson-printer/"><u>Inkjet Resumed: Solved [Epson Printer]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-remedies-for-slow-printers/"><u>Quick Remedies for Slow Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574160377-reconnect-your-silent-canon-printer-now/"><u>Reconnect Your Silent Canon Printer Now</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-identifying-instagrams-newly-disconnected/"><u>2024 Approved  Identifying Instagram's Newly Disconnected</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-ace-screen-recorders-list-for-the-winning-setup/"><u>[Updated] The Ace Screen Recorders List - For the Winning Setup</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-motorola-moto-g73-5g-by-drfone-android/"><u>Three Ways to Sim Unlock Motorola Moto G73 5G</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-2024-approved-best-video-translator-app-for-pc-cannot-miss/"><u>New 2024 Approved Best Video Translator App for PC Cannot Miss</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-ultimate-selection-10-budget-friendly-youtube-caption-tools/"><u>[New] Ultimate Selection  10 Budget-Friendly YouTube Caption Tools</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-pioneering-editing-snapseed-for-the-newcomer/"><u>2024 Approved  Pioneering Editing  Snapseed for the Newcomer</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-vivo-y78t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-flex-your-viewing-muscles-handling-multiple-youtube-videos-for-2024/"><u>[New] Flex Your Viewing Muscles  Handling Multiple YouTube Videos for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-motorola-edge-40-neo-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Motorola Edge 40 Neo Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-microsofts-phone-link-on-mobile-devices/"><u>How to Utilize Microsoft's Phone Link on Mobile Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfecting-chromes-sound-best-apps-for-online-text-to-speech-transformation/"><u>In 2024, Perfecting Chrome's Sound  Best Apps for Online Text-to-Speech Transformation</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-samsung-galaxy-z-fold-5-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Samsung Galaxy Z Fold 5 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-seamless-mp4-extraction-your-fb-video-fix/"><u>[Updated] Seamless MP4 Extraction – Your FB Video Fix</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/digging-into-sharex-assessment-and-choices/"><u>Digging Into ShareX  Assessment & Choices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-audacity-masterclass-techniques-for-flawless-sound-de-noising/"><u>[New] 2024 Approved  Audacity Masterclass  Techniques for Flawless Sound De-Noising</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-convert-video-to-gif-with-ease-28-top-tools-for-2024/"><u>New Convert Video to GIF with Ease 28 Top Tools for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-ultimate-guide-to-photo-and-video-collage-software/"><u>Updated In 2024, The Ultimate Guide to Photo and Video Collage Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-huawei-nova-y71-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Huawei Nova Y71 for Streaming | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-are-podcasters-paid/"><u>[New] How Are Podcasters Paid?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ideas-on-boosting-gopro-energy-retention/"><u>[Updated] Ideas on Boosting GoPro Energy Retention</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-infinix-smart-8-pro-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Infinix Smart 8 Pro without App | Dr.fone</u></a></li>
</ul></div>
