---
title: "[TROUBLESHOOT] Print Service Non-Functioning Windows"
date: 2024-07-10T17:24:29.469Z
updated: 2024-07-11T17:24:29.469Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes [TROUBLESHOOT] Print Service Non-Functioning Windows
excerpt: This Article Describes [TROUBLESHOOT] Print Service Non-Functioning Windows
keywords: Printer Issues Resolution,Troubleshoot Non-Working Printers,Fix Print Device Malfunctions,Common Problems with Inkjet Printers,How to Resolve Printing Errors,Non-Functioning Laser Printers Solutions,Identifying and Solving Print Device Failures
thumbnail: https://thmb.techidaily.com/bab43c6ebbd68c7b02aa8931b44c8b3c5cf156c7a7bd1aa24fbe3ea34de877b1.jpg
---

## [TROUBLESHOOT] Print Service Non-Functioning Windows

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
<li><a href="https://printer-issues.techidaily.com/colors-missing-in-document-output/"><u>Colors Missing in Document Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cdw-duo-fan-guide-for-brother-9330c/"><u>CDW Duo Fan Guide for Brother 9330C</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-not-responding-error-on-windows-fixed/"><u>Printer Not Responding Error on Windows Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionizing-printer-laptop-connection-new-techniques-explored/"><u>Revolutionizing Printer-Laptop Connection: New Techniques Explored</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-driver-missing-from-pc-os/"><u>Printer Driver Missing From PC OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/seamless-printer-function-release/"><u>Seamless Printer Function Release</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamlining-laser-troubleshooting/"><u>Streamlining Laser Troubleshooting</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-rectify-canons-no-print-issue-with-these-5-window-11-tips/"><u>Effortlessly Rectify Canon's No-Print Issue with These 5 Window 11 Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-overcoming-post-upgrade-prints/"><u>Successfully Overcoming Post-Upgrade Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-print-spooler-failure/"><u>Overcome Print Spooler Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-canon-printer-issues-on-windows-10/"><u>Resolving Canon Printer Issues on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-hp-printer-issues/"><u>Unblocking HP-Printer Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hidden-network-printer-how-to-find-it-on-your-os/"><u>Hidden Network Printer: How to Find It on Your OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-deadprint-a-step-by-step-guide/"><u>Reviving a Deadprint: A Step-by-Step Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-integrating-printer-model-8720-in-pc/"><u>How-To: Integrating Printer Model 8720 in PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-software-conflicts-in-printing-hardware/"><u>Resolving Software Conflicts in Printing Hardware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-compatible-with-online-scanner-again/"><u>Win11 Compatible with Online Scanner Again</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-achieves-zero-blank-page-mishaps/"><u>HP Printer Achieves Zero Blank Page Mishaps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/lighten-your-load-fast-prints-guide/"><u>Lighten Your Load: Fast Prints Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/setting-primary-printer-failed-error-0x00000709-fixed/"><u>Setting Primary Printer Failed: Error 0X00000709 Fixed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connectivity-issue-cannot-add-printer-drivers-to-multiple-windows/"><u>[Connectivity Issue] Cannot Add Printer Drivers to Multiple Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-the-printer-not-printing-issue/"><u>How to Fix the Printer Not Printing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-hp-paper-jam-resolved/"><u>Win11 HP Paper Jam Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-empty-pages-a-printers-success-story/"><u>Eliminating Empty Pages: A Printer's Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-update-the-silent-printer/"><u>Windows Update: The Silent Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ensure-reliability-update-printer-software-for-win7-users/"><u>Ensure Reliability: Update Printer Software for Win7 Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-access-to-domain-services-printer-not-responding/"><u>No Access To Domain Services, Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unwanted-blank-sheets-a-common-epson-complaint/"><u>Unwanted Blank Sheets: A Common Epson Complaint</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fixes-for-canon-printer-non-operational-in-windows-10/"><u>Quick Fixes for Canon Printer Non-Operational in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-printer-from-jamming-in-windows-11/"><u>Stop Your Printer From Jamming in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cracking-code-0x00000709-to-fix-default-printer-setup/"><u>Cracking Code 0X00000709 to Fix Default Printer Setup</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unlocking-the-power-of-cross-platform-social-media-with-youtube-and-instagram-stories/"><u>In 2024, Unlocking the Power of Cross-Platform Social Media with YouTube & Instagram Stories</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-replace-missing-watch-playback-icons/"><u>In 2024, Replace Missing Watch Playback Icons</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-soundsreview-insight/"><u>[Updated] SoundsReview Insight</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-realme-c55-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Realme C55 to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-connect-movie-files-in-youtv-catalog/"><u>[Updated] Connect Movie Files in YouTV Catalog</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-how-to-safely-dissolve-an-inactive-linkedin-account/"><u>[New] In 2024, How to Safely Dissolve an Inactive LinkedIn Account</u></a></li>
<li><a href="https://driver-install.techidaily.com/reviving-gpu-performance-master-the-newest-ddu-tactics/"><u>Reviving GPU Performance - Master the Newest DDU Tactics</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-free-video-cutting-apps-your-go-to-list-for-2024/"><u>[New] Best Free Video Cutting Apps  Your Go-To List for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/relaxed-rhythms-essential-20-country-tracks-to-dance-away-stress-tiktok/"><u>Relaxed Rhythms  Essential 20 Country Tracks to Dance Away Stress (TikTok)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-ultimate-mp4-to-social-media-focus-on-facebook/"><u>[Updated] 2024 Approved  Ultimate MP4 to Social Media  Focus on Facebook</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mp4-reimagined-effortlessly-adding-srt/"><u>[New] MP4 Reimagined  Effortlessly Adding SRT</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-strategies-for-effortlessly-sharing-youtube-videos-on-fb/"><u>[Updated] In 2024, Strategies for Effortlessly Sharing YouTube Videos on FB</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-precision-in-motion-apowersofts-pc-screen-recorder-review/"><u>In 2024, Precision in Motion  Apowersoft's PC Screen Recorder Review</u></a></li>
<li><a href="https://extra-information.techidaily.com/soundscapes-enhancing-photography-online/"><u>Soundscapes Enhancing Photography Online</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-simple-method-for-great-insta-posts/"><u>In 2024, Simple Method for Great Insta Posts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-top-6-cost-free-web-accessible-tiktok-to-mp3-extractors/"><u>[New] 2024 Approved  Top 6 Cost-Free, Web-Accessible TikTok To MP3 Extractors</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-expert-insights-streamlining-filters-integration-in-media-production/"><u>In 2024, Expert Insights  Streamlining Filters Integration in Media Production</u></a></li>
<li><a href="https://extra-hints.techidaily.com/annual-reveal-best-free-luts-with-direct-access-links/"><u>Annual Reveal - Best FREE LUTs with Direct Access Links</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unlocking-ig-potential-strategies-for-accumulating-1000plus-likesmonth-for-2024/"><u>[New] Unlocking IG Potential  Strategies for Accumulating 1,000+ Likes/Month for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-channel-labeling-101-how-to-make-yourself-hard-to-ignore/"><u>2024 Approved  Channel Labeling 101  How to Make Yourself Hard to Ignore</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-mastering-windows-movie-maker-a-free-download-and-tutorial-guid/"><u>2024 Approved Mastering Windows Movie Maker A Free Download and Tutorial Guid</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-building-your-brand-as-a-reviewer-of-cars-and-automotive-gear/"><u>[New] Building Your Brand as a Reviewer of Cars and Automotive Gear</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-switching-on-windows-11-for-automatic-hdr-mode/"><u>In 2024, Switching On Windows 11 for Automatic HDR Mode</u></a></li>
<li><a href="https://some-techniques.techidaily.com/excellent-storage-upgrade-for-sony-a7s-ii-cameras-for-2024/"><u>Excellent Storage Upgrade for Sony A7S II Cameras for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unseen-social-media-hits-top-10-meme-pages/"><u>[Updated] Unseen Social Media Hits – Top 10 Meme Pages</u></a></li>
</ul></div>
