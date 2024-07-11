---
title: "[ISSUE] Can't Print - Spooler Disabled"
date: 2024-07-10T16:40:11.895Z
updated: 2024-07-11T16:40:11.895Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes [ISSUE] Can't Print - Spooler Disabled
excerpt: This Article Describes [ISSUE] Can't Print - Spooler Disabled
keywords: Print Errors,Spooler Issue Troubleshooting,Disable Print Spooler Windows 10/11,Print Service Configuration in Windows,How to Fix Print Spooler Disabled,Print Driver Problems Solutions,Printer Management in Windows
thumbnail: https://thmb.techidaily.com/0244557d86d8e1a27dc054dedba4a1385b1696e504c943e408d092d2c07266c8.jpg
---

## [ISSUE] Can't Print - Spooler Disabled

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
<li><a href="https://printer-issues.techidaily.com/visual-guide-configure-your-new-canon-printer/"><u>Visual Guide: Configure Your New Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-non-operational-usb-printers-in-sleep-mode-w7/"><u>Troubleshooting Non-Operational USB Printers in Sleep Mode, W7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574106588-fixing-hp-printer-fatal-error-oxc4eb827f/"><u>Fixing HP Printer Fatal Error: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ending-unwanted-spooler-pauses-on-windows-devices/"><u>Ending Unwanted Spooler Pauses on Windows Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-hiccup-config-settings-amiss/"><u>Printer Hiccup: Config Settings Amiss</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-halted-win10-doesnt-recognize-mp620-driver/"><u>Printer Setup Halted: WIN10 Doesn't Recognize MP620 Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/scanner-restoration-completed-for-win11/"><u>Scanner Restoration Completed for Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breathe-new-life-into-non-printing-brother-printer-in-windows-1011/"><u>Breathe New Life Into Non-Printing Brother Printer in Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-silence-to-service-restoring-online-status-in-printer/"><u>From Silence to Service: Restoring Online Status in Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-error-unable-to-install-mp620-printer-driver/"><u>Windows Error: Unable to Install MP620 Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-11-update-linked-to-non-operational-printer/"><u>Win 11 Update Linked to Non-Operational Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-down-print-operation-fails/"><u>Active Directory Down - Print Operation Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-your-brother-printers-print-a-win1011-guide-to-fixing-issues/"><u>Revive Your Brother Printer's Print: A Win10/11 Guide to Fixing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recommendations-for-reactivating-inactive-hp-paper-feeders/"><u>Recommendations for Reactivating Inactive HP Paper Feeders</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-b200-no-longer-exists/"><u>Error B200 No Longer Exists</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-error-code-0x97/"><u>[Solved] Epson Error Code 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-printer-code-xf34/"><u>Troubleshooting HP Printer Code #XF34</u></a></li>
<li><a href="https://printer-issues.techidaily.com/latest-firmware-for-mf4770n-on-windows-systems/"><u>Latest Firmware for MF4770n on Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/help-needed-printers-unplanned-shift/"><u>Help Needed: Printer's Unplanned Shift</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-w11-scanner-output-issues/"><u>Fix W11 Scanner Output Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/farewell-to-printer-frustration-win-10s-solution-found/"><u>Farewell to Printer Frustration: Win 10'S Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reversing-printer-freezes/"><u>Reversing Printer Freezes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-persistent-spooler-problems-in-windows-systems/"><u>Remedying Persistent Spooler Problems in Windows Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-active-directory-service-unavailable/"><u>PPrintError: Active Directory Service Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rectify-cups-errors-streamline-win10-printer-services/"><u>Rectify CUPS Errors: Streamline WIN10 Printer Services</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-continuous-blank-output-resolved/"><u>HP Printer: Continuous Blank Output Resolved</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-expert-guide-to-bypassing-watermarks-while-downloading-tiktoks-on-iphones/"><u>2024 Approved  Expert Guide to Bypassing Watermarks While Downloading TikToks on iPhones</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-transforming-vision-into-visual-impact-on-tiktok-via-templates/"><u>In 2024, Transforming Vision Into Visual Impact on TikTok via Templates</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/easy-video-reversal-top-online-solutions/"><u>Easy Video Reversal Top Online Solutions</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/auditory-excellence-in-action-how-to-identify-the-sound-editor-of-your-dreams-for-2024/"><u>Auditory Excellence in Action How to Identify the Sound Editor of Your Dreams for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-expert-curated-win-screenshot-and-recorders-list/"><u>[Updated] 2024 Approved  Expert-Curated Win Screenshot and Recorders List</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-samsung-galaxy-z-fold-5-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Samsung Galaxy Z Fold 5 Phones? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-microsoft-excel-2016-error-code-0x800a03ec-stellar-by-stellar-guide/"><u>How to Fix Microsoft Excel 2016 Error Code 0x800A03EC? | Stellar</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-ways-to-erase-apple-iphone-15-when-its-locked-within-seconds-by-drfone-ios/"><u>In 2024, 3 Ways to Erase Apple iPhone 15 When Its Locked Within Seconds</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-motorola-g54-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Motorola G54 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-boost-mobile-iphone-12-mini-before-the-plan-expires-by-drfone-ios/"><u>In 2024, Unlock Your Boost Mobile iPhone 12 mini Before the Plan Expires</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-secure-recording-of-conversations-what-you-need-to-know-about-whatsapp/"><u>[Updated] In 2024, Secure Recording of Conversations  What You Need to Know About WhatsApp</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-explore-deep-with-these-immersive-vr-clips/"><u>In 2024, Explore Deep with These Immersive VR Clips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-vivo-y27-4g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Vivo Y27 4G Location | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-meizu-21-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Meizu 21 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-motorola-moto-g24-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Motorola Moto G24 Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/crafting-your-perfect-minecraft-shelter-for-2024/"><u>Crafting Your Perfect Minecraft Shelter for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-channel-size-independent-strategies-for-securing-sponsors/"><u>[New] 2024 Approved  Channel-Size-Independent Strategies for Securing Sponsors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-cutting-edge-televisions-top-10-4ks/"><u>[Updated] Cutting-Edge Televisions – Top 10 4Ks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-empower-your-video-creation-blending-youtube-and-imovie-for-impressive-results/"><u>2024 Approved  Empower Your Video Creation  Blending YouTube and iMovie for Impressive Results</u></a></li>
</ul></div>
