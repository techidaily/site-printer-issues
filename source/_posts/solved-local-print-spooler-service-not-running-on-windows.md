---
title: "[SOLVED] Local Print Spooler Service Not Running on Windows"
date: 2024-07-10T17:14:57.932Z
updated: 2024-07-11T17:14:57.932Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes [SOLVED] Local Print Spooler Service Not Running on Windows
excerpt: This Article Describes [SOLVED] Local Print Spooler Service Not Running on Windows
keywords: Local Print Spooler Service,Windows,Print Spooler Service Not Running,Solved,Troubleshooting Windows Issue,System Error Fix,Print Spooler Service Troubleshooting,Local Print Spooler Service Not Running,Windows Print Spooler Service,Solved Problem for Users
thumbnail: https://thmb.techidaily.com/41d26f14bdf26696cf95984fdfd711f6541c07a00007a689ba883cae0cffeaf7.jpg
---

## [SOLVED] Local Print Spooler Service Not Running on Windows

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
<li><a href="https://printer-issues.techidaily.com/wake-up-call-faulty-usb-printers-in-windows-7-mode/"><u>Wake Up Call: Faulty USB Printers in Windows 7 Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructions-installing-hp-officejet-on-pc-interface/"><u>Instructions: Installing HP Officejet on PC Interface</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-failure-not-recognizing-canon-model/"><u>Printer Failure: Not Recognizing Canon Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-on-laptops-with-improved-hp-printer-links/"><u>Optimize Printing on Laptops with Improved HP Printer Links</u></a></li>
<li><a href="https://printer-issues.techidaily.com/joining-process-attaching-hp-officejet-to-desktop-pcs/"><u>Joining Process: Attaching HP Officejet to Desktop PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-pcl-xl-mistakes-with-ease/"><u>Tackling PCL XL Mistakes with Ease</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-print-service-not-starting-correctly/"><u>[WARNING] Print Service Not Starting Correctly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-and-connecting-your-canon-printer/"><u>Efficiently Setting Up and Connecting Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpectedly-blank-print-screens-in-win-710/"><u>Unexpectedly Blank Print Screens in Win 7/10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-hp-printer-status/"><u>How to Reactivate HP Printer Status</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-10/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-driver-windows-1011-error/"><u>HP Printer Driver - Windows 10/11 Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/in-depth-installing-and-tweaking-your-hp-printer-on-windows/"><u>In-Depth: Installing and Tweaking Your HP Printer on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-pixma-mp620-driver-missing-please-help/"><u>Canon Pixma MP620: Driver Missing, Please Help</u></a></li>
<li><a href="https://printer-issues.techidaily.com/immediate-actions-for-a-disconnected-printer/"><u>Immediate Actions for a Disconnected Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/decoding-and-fixing-epson-error-0x97/"><u>Decoding & Fixing Epson Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repair-guide-for-non-printing-machines/"><u>Repair Guide for Non-Printing Machines</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-not-printing-in-color/"><u>[SOLVED] Printer Not Printing in Color</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-your-non-printing-brother-printer-in-win1011/"><u>Reviving Your Non-Printing Brother Printer in Win10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-printing-glitch-error-0x00000709-resolved/"><u>Fixed the Printing Glitch - Error 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/triumph-over-the-printer-after-updating-woes/"><u>Triumph over the Printer After Updating Woes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quickly-rectify-non-printing-problem-top-5-techniques-to-aid-canon-print-on-window-11/"><u>Quickly Rectify Non-Printing Problem: Top 5 Techniques to Aid Canon Print on Window 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enable-scanned-device-functionality-in-windows-10/"><u>Enable Scanned Device Functionality in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/my-canon-printer-wont-respond-what-now/"><u>My Canon Printer Won't Respond, What Now?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compact-bundle-optimized-hp-officejet-pro-8600-drivers-win32/"><u>Compact Bundle: Optimized HP Officejet Pro 8600 Drivers, Win32</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-drive-issue-cant-connect-on-pc/"><u>Printer Drive Issue: Can't Connect on PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-your-canon-printers-non-print-problem-with-these-top-five-tricks-in-windows-11/"><u>Fix Your Canon Printer's Non-Print Problem with These Top Five Tricks in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mf4770n-updates-for-streamlined-windows-functionality/"><u>MF4770n Updates for Streamlined Windows Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-printer-fault-eco-error/"><u>Resolved: Printer Fault #Eco-Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/gear-up-glitch-printer-reconfigured-wrongly/"><u>Gear-Up Glitch: Printer Reconfigured Wrongly?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-paper-jamming-problem/"><u>Overcome Paper Jamming Problem</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secrets-of-efficiently-setting-up-hp-on-pcs/"><u>Unveiling the Secrets of Efficiently Setting Up HP on PCs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/system-shenanigans-unauthorized-printer-access/"><u>System Shenanigans: Unauthorized Printer Access</u></a></li>
<li><a href="https://printer-issues.techidaily.com/convenient-canon-printer-wireless-integration/"><u>Convenient Canon Printer Wireless Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-white-printouts-deciphering-the-epson-mishap/"><u>Endless White Printouts: Deciphering the Epson Mishap</u></a></li>
<li><a href="https://youtube-data.techidaily.com/aging-yt-playlist-features-for-site-enhancement/"><u>Leveraging YT Playlist Features for Site Enhancement</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-this-article-aims-to-provide-a-step-by-step-guide-to-changing-a-videos-speed-by-using-the-speed-adjustment-panel-and-duration-panel-on-wonders/"><u>2024 Approved This Article Aims to Provide a Step-by-Step Guide to Changing a Videos Speed by Using the Speed Adjustment Panel and Duration Panel on Wondershare Filmora</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-the-futures-past-digital-conversion-for-timeless-images/"><u>[New] Crafting the Future's Past  Digital Conversion for Timeless Images</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-best-of-the-best-video-editing-programs-compared/"><u>In 2024, The Best of the Best Video Editing Programs Compared</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-screen-recorder-showdown-apoyser-vs-emerging-alternatives-review/"><u>2024 Approved  Screen Recorder Showdown  Apoyser Vs Emerging Alternatives Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-overview-fb-video-dimension-categories/"><u>[Updated] Overview  FB Video Dimension Categories</u></a></li>
<li><a href="https://network-issues.techidaily.com/finalizing-setup-nvidia-fails-no-more/"><u>Finalizing Setup: NVIDIA Fails No More</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-steps-to-secure-unmarked-stock-photos-for-business/"><u>2024 Approved  Steps to Secure Unmarked Stock Photos for Business</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-ideal-extras-for-improving-gopro-experience/"><u>[New] Ideal Extras for Improving GoPro Experience</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-ultimate-non-twitter-social-sites-of-the-year/"><u>[Updated] In 2024, Ultimate Non-Twitter Social Sites of the Year</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-groupwatcher-pro-hd-downloader/"><u>2024 Approved  GroupWatcher Pro HD Downloader</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-how-to-add-emojis-to-discord-on-desktop-computer-and-mobile/"><u>Updated How to Add Emojis To Discord on Desktop Computer and Mobile</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-lowering-sound-gradually-a-logic-pro-method/"><u>2024 Approved  Lowering Sound Gradually  A Logic Pro Method</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/diversifying-audience-across-30plus-online-venues/"><u>Diversifying Audience Across 30+ Online Venues</u></a></li>
<li><a href="https://extra-information.techidaily.com/beyond-the-boundaries-limitations-in-vr-for-2024/"><u>Beyond the Boundaries  Limitations in VR for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-iphone-video-playback-cycles-for-2024/"><u>Mastering iPhone Video Playback Cycles for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-polaroid-cubeplus-camera-insight-for-fans-of-live-action/"><u>[New] Polaroid Cube+ Camera Insight for Fans of Live-Action</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-oppo-a38-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Oppo A38 FRP</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-investment-in-sound-quality-ranked-list-of-excellent-no-cost-and-full-priced-podcast-editors/"><u>Updated 2024 Approved The Investment in Sound Quality Ranked List of Excellent, No-Cost and Full-Priced Podcast Editors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-nubia-red-magic-8s-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Nubia Red Magic 8S Pro FRP</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-realme-v30t-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Realme V30T to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-asus-rog-phone-7-ultimate-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Asus ROG Phone 7 Ultimate FRP Bypass Instantly</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/streamlining-social-sharing-coordinating-vids-on-tweets-plus-tumbles-for-2024/"><u>Streamlining Social Sharing  Coordinating Vids on Tweets + Tumbles for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-12-tycoons-where-every-decision-forges-your-path-to-glory/"><u>Top 12 Tycoons - Where Every Decision Forges Your Path to Glory</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-perfecting-your-youtube-experience-stop-previews/"><u>[New] 2024 Approved  Perfecting Your YouTube Experience - Stop Previews</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-ethical-buying-of-tiktok-clout-increase/"><u>[Updated] 2024 Approved  Ethical Buying of TikTok Clout Increase</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-ranked-guide-to-premium-iosdesktop-video-change-tools/"><u>2024 Approved  Ranked Guide to Premium iOS/Desktop Video Change Tools</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-navigating-the-latest-tiktok-craze-wave/"><u>2024 Approved  Navigating the Latest TikTok Craze Wave</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-mastering-webcam-use-for-professional-meeting-records/"><u>[Updated] 2024 Approved  Mastering Webcam Use for Professional Meeting Records</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-oneplus-11r-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your OnePlus 11R Phone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-top-relaxing-country-bops-and-beats-for-dance-parties-on-tiktok/"><u>[Updated] 2024 Approved  Top Relaxing Country Bops & Beats for Dance Parties on TikTok</u></a></li>
<li><a href="https://extra-tips.techidaily.com/visionary-virtual-worlds-the-top-ten-sci-fi-films-of-the-metaverse-age/"><u>Visionary Virtual Worlds  The Top Ten Sci-Fi Films of the Metaverse Age</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-12-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone 12 Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-game-on-unbeatable-business-simulations-for-the-year/"><u>[New] 2024 Approved  Game On! - Unbeatable Business Simulations for the Year</u></a></li>
</ul></div>
