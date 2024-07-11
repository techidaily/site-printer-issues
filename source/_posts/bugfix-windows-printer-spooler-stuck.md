---
title: "[BUGFIX] Windows Printer Spooler Stuck"
date: 2024-07-10T16:58:38.121Z
updated: 2024-07-11T16:58:38.121Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes [BUGFIX] Windows Printer Spooler Stuck
excerpt: This Article Describes [BUGFIX] Windows Printer Spooler Stuck
keywords: Fixing Printer Spooler Issues,Resolving Windows Printer Errors,Troubleshooting Spooled Files in Windows OS,How to Unstuck Windows Print Spooler,Windows Printer Queue Fix Guide,Spooler Stuck on Windows Computer Solution,Printer Driver Troubleshooting for Windows
thumbnail: https://thmb.techidaily.com/1ccc74ee674e5bb21d96568f803e367c477d95c5c3cb7fed4a8969e3e80f00a3.jpg
---

## [BUGFIX] Windows Printer Spooler Stuck

![](https://images.drivereasy.com/wp-content/uploads/2022/05/local-print-spooler-service-not-running.jpg)

 The Print Spooler service is an essential component to get your printer working properly. The “**local print spooler service is not running** ” error could indicate a faulty configuration, or it could mean something is wrong with the computer drivers. While there may be many reasons behind this error, it’s usually not that hard to fix.

## Try these fixes

 You might not need to try them all. Simply work your way down until you find the one that does the trick.

1. [**Reconfigure the Print Spooler service**](#fix1)
2. [**Run the troubleshooter**](#fix2)
3. [**Reinstall your printer driver**](#fix3)
4. [**Install all Windows updates**](#fix4)
5. **[Check for corrupted system files](#fix5)**

### Fix 1:**Reconfigure the printer service**

 First you can start by troubleshooting settings of services. By default the Print Spooler service runs automatically, but you should check to**make sure everything is configured properly** .

1. On your keyboard, press**Win+R** (the Windows logo key and the R key) to open the Run box. Type or paste**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/08/services-msc.jpg)
2. Right click**Print Spooler** and select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/print-spooler-services-properties.jpg)
3. Make sure**Startup type** is set to**Automatic** . You can also try to manually start the service by clicking**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/print-spooler-services-properties-2.jpg)
4. Navigate to the**Recovery** tab. Make sure**First failure** and**Second failure** are set to**Restart the Service** ,**Reset fail count after** is set to**1** days,**Restart service** after**1** minutes. Once completed, click**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/print-spooler-services-properties-3.jpg)
5. Restart your PC and check if the Print Spooler service is up and running. If you have access to the printer, give it a reboot as well.

If the error persists, you can check out the next fix.

### Fix 2: **Run the troubleshooter**

 Windows provides a built-in troubleshooter to help you figure out what’s causing the issue. In some cases, it may provide a better insight if it’s a common error.

1. On your keyboard, press**Win+I** (the Windows logo key and the I key) to open**Windows Settings** . Select**Update & Security.**  
![](https://images.drivereasy.com/wp-content/uploads/2021/11/update-and-security.png)
2. On the left pane, select**Troubleshoot** . Click**Additional troubleshooters** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/03/additional-troubleshooters.jpg)
3. Select**Printer** . Then follow the on-screen instructions to troubleshoot.  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/troubleshooter-printer.jpg)

 If the troubleshooter can’t help you fix the issue, take a look at the next method.

### Fix 3:**Reinstall your printer driver**

 Drivers are a set of computer software that let your PC communicate with the hardware. Some users reported that this could be a driver issue that can be fixed by**reinstalling the printer driver** . You can use to following steps to reinstall the printer driver correctly:

1. On your keyboard, press**Win+R** (the Windows logo key and the R key) at the same time to invoke the**Run box** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/just-a-run-box.jpg)
2. Type or paste**devmgmt.msc** . Then click**OK** to open Device Manager.  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/device-manager-run-box-ok.jpg)
3. Click to expand the**Print queues** category. Right-click your printer and select**Uninstall device** . (If you can’t find your printer in Device Manager, you can [download Driver Easy](https://tools.techidaily.com/drivereasy/download/) to scan for missing drivers.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/device-manager-reinstall-printer-02.jpg)
4. Click**Uninstall** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/device-manager-reinstall-printer-03.jpg)

 Usually Windows will install the missing printer driver automatically after a reboot. But if it doesn’t, you need to go to**your printer manufacturer’s website** and search for your printer model. Be sure to download the latest correct driver installer that’s compatible with your system. If you’re not familiar with computer drivers, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) to**repair and update drivers automatically** .

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2021/09/scan-now.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system.  
 (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. If you don’t want to pay for the Pro version, you can still download and install all the drivers you need with the free version; you just have to download them one at a time, and manually install them, the normal Windows way.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/de-update-printer-m477.jpg)

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 After updating all the drivers, restart your PC and check if the printer is working now.

 If the latest driver doesn’t give you luck, simply move on to the next solution.

### Fix 4:**Install all Windows updates**

 Windows system updates should fix glitches and improve the overall stability. If you don’t remember when was the last time you checked for system updates, definitely do it now.

 If you see this error after a system update, you can use [this link](ms-settings:windowsupdate-history?activationSource=SMC-Article-12415) to view and uninstall your system updates.

1. On your keyboard, press**Win+I** (the Windows logo key and the i key) to open the Windows Settings app. Click**Update & Security** .  
![update & security](https://images.drivereasy.com/wp-content/uploads/2020/10/update-security-2.jpg)
2. Click**Check for updates** . Windows will then download and install the available patches. It might take some time (up to 30 mins).  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/windows-security-update-click-check-for-update.jpg)

 To confirm you’ve installed _all_  the system updates, **repeat these steps** until it prompts “You’re up to date” when you click **Check for updates** .

 If this fix doesn’t give you luck, you can continue to the next one below.

### Fix 5:**Check for corrupted system files**

 In the worst case, you could be dealing with a system-level issue. This could mean that registry values are messed up, or it could also mean the whole system, or at least some important files are missing or corrupted. But before you try the nuclear method to reinstall Windows, you can first use a system repair tool to scan for system issues.

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a professional Windows repair tool that can scan your system’s overall status, diagnose your system configuration, identify faulty system files, and repair them automatically. It gives you entirely fresh system components with just one click, so you don’t have to reinstall Windows and all your programs.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a 60-day Money-Back Guarantee so you can refund anytime if Fortect doesn’t fix your problem).  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

---

 Hopefully this post helps you get your printer working again. If you have any questions or ideas, don’t hesitate to leave a comment down below.

* [printer](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://printer-issues.techidaily.com/fine-tune-your-prints-install-new-v305-driver-in-win7/"><u>Fine-Tune Your Prints: Install New V305 Driver in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-network-error/"><u>Mended Printer Network Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-memory-overuse-by-w11-printers/"><u>Address Memory Overuse by W11 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-print-service-not-starting-correctly/"><u>[WARNING] Print Service Not Starting Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-print-issues-5-simple-solutions-for-non-printing-canon-devices-in-windows-11/"><u>Streamlining Print Issues: 5 Simple Solutions for Non-Printing Canon Devices in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-windows-print-service-from-frequently-stopping/"><u>Stop Windows Print Service From Frequently Stopping</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solving-officejets-no-print-malaise/"><u>Solving OfficeJet's No Print Malaise</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-canon-printer-a-visual-walkthrough/"><u>How to Set Up a Canon Printer: A Visual Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winme-printer-no-response-how-to-remedy-it/"><u>WinME Printer No Response - How to Remedy It</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-error-on-hp-printer-oxc4eb827f/"><u>Resolving Error on HP Printer: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reclaiming-online-status-for-your-printer/"><u>Reclaiming Online Status for Your Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-communication-errors-with-printers/"><u>Clearing Up Communication Errors with Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-missing-driver-in-os/"><u>[PRINTER PROBLEM] Missing Driver in OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win711-hp-printer-network-recovery-tips/"><u>Win7/11 HP Printer Network Recovery Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-resolution-restoring-default-windows-printer-0x00000709/"><u>Error Resolution: Restoring Default Windows Printer (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-air-glide-instructions/"><u>Brother CDW Duo Air Glide Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hurry-to-reconnect-printer-now/"><u>Hurry to Reconnect Printer Now</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-the-mystery-of-non-printing-machines/"><u>Dismantling the Mystery of Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-error-0x00000709-on-printer-selection-in-windows/"><u>Fixed Error 0X00000709 on Printer Selection in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hiccup-configuration-issue-surfaced/"><u>Printer Hiccup: Configuration Issue Surfaced</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-halted-win10-doesnt-recognize-mp620-driver/"><u>Printer Setup Halted: WIN10 Doesn't Recognize MP620 Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-needed-drivers-not-installing-hp-deskjet-d1360-on-windows/"><u>[Update Needed] Drivers Not Installing: HP Deskjet D1360 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-hp-printers-oxc4eb827f-error/"><u>Resolving HP Printer's OXC4EB827F Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-sleephibernate-glitch-with-usb-printers-w7/"><u>[Resolved] Sleep/Hibernate Glitch with USB Printers, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/usb-printer-non-operation-on-windows-7-post-sleep/"><u>USB Printer Non-Operation on Windows 7 Post Sleep</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-non-authentic-printer-use-case/"><u>Resolved: Non-Authentic Printer Use Case</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1715859745150-updated-2023-browser-snapshot-winners-announced/"><u>[Updated] 2023 Browser Snapshot Winners Announced!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-no-cost-video-magic-the-best-online-editors-ranked/"><u>2024 Approved No-Cost Video Magic The Best Online Editors Ranked</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-honor-x7b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Honor X7b | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-elevate-your-online-presence-discord-picture-perfection/"><u>In 2024, Elevate Your Online Presence  Discord Picture Perfection</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-can-youtube-sub4sub-really-enhance-viewing-experience/"><u>[New] 2024 Approved  Can YouTube Sub4Sub Really Enhance Viewing Experience?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-vanguard-womans-phonetic-alteration-service-online-free-edition/"><u>In 2024, Vanguard Womans Phonetic Alteration Service Online - Free Edition</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-unlocking-features-advanced-logitech-webcam-techniques/"><u>[Updated] 2024 Approved  Unlocking Features  Advanced Logitech Webcam Techniques</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-xcover-7-support-mov-videos-by-aiseesoft-video-converter-play-mov-on-android/"><u>Does Samsung Galaxy XCover 7 support MOV videos ?</u></a></li>
<li><a href="https://video-capture.techidaily.com/1715859921553-2024-approved-next-gen-online-meeting-apps-azoom-no-more/"><u>2024 Approved  Next-Gen Online Meeting Apps  Azoom No More!</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-tecno-spark-20-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Tecno Spark 20? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-explore-laughter-tears-fusion-the-best-ig-accounts-ever/"><u>[New] 2024 Approved  Explore Laughter-Tears Fusion  The Best IG Accounts Ever</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-inspirational-audio-bridges-to-current-affairs-volume-15/"><u>Updated Inspirational Audio Bridges to Current Affairs Volume 15</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-narrating-real-life-how-to-write-engaging-docu-scripts/"><u>[New] Narrating Real Life  How to Write Engaging Docu-Scripts</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-free-video-stabilization-solutions-for-windows-and-macos-users/"><u>Updated 2024 Approved Free Video Stabilization Solutions for Windows and macOS Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-professionals-blueprint-for-investing-in-high-definition-viewing/"><u>[Updated] The Professional's Blueprint for Investing in High-Definition Viewing</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-transferring-twitter-videos-to-whatsapp-effortlessly/"><u>2024 Approved  Transferring Twitter Videos to WhatsApp Effortlessly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-professional-tips-for-capturing-audio-in-audacity/"><u>[New] Professional Tips for Capturing Audio in Audacity</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-the-art-of-photo-color-correction-for-2024/"><u>Mastering the Art of Photo Color Correction for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-lava-blaze-2-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Lava Blaze 2 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-channel-building-gear-a-quick-start-guide/"><u>[Updated] 2024 Approved  Channel-Building Gear  A Quick Start Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-amplify-audience-connection-best-creative-reacting-techniques-for-2024/"><u>[Updated] Amplify Audience Connection  Best Creative Reacting Techniques for 2024</u></a></li>
</ul></div>
