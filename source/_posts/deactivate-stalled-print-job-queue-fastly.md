---
title: Deactivate Stalled Print Job Queue Fastly
date: 2024-08-22T09:40:52.005Z
updated: 2024-08-23T09:40:52.005Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Deactivate Stalled Print Job Queue Fastly
excerpt: This Article Describes Deactivate Stalled Print Job Queue Fastly
keywords: Stalled Print Job Queue,Fastly Deactivation,Print Job Queue Management,Fast Print Job Resolution,Queue Clearance Techniques,Interrupt Print Job Queue,Optimize Print Processes with Fastly
thumbnail: https://thmb.techidaily.com/18c9dd2cba19f0ecf97513cafd5088c9e4acab9c65510cdf2678db2edca6954d.jpg
---

## Deactivate Stalled Print Job Queue Fastly

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

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://printer-issues.techidaily.com/compatibility-problem-windows-10-cant-find-mp620-drivers/"><u>[Compatibility Problem] Windows 10 Can't Find MP620 Drivers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-explore-8plus-places-for-gratis-hdr-environments-and-clips/"><u>[New] 2024 Approved  Explore 8+ Places for Gratis HDR Environments & Clips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-improve-instagram-video-loading-times-effectively/"><u>[New] Improve Instagram Video Loading Times Effectively</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-efficient-methods-for-youtube-video-preservation/"><u>[New] In 2024, Efficient Methods for YouTube Video Preservation</u></a></li>
<li><a href="https://article-files.techidaily.com/new-instagram-image-enhancement-tips/"><u>[New] Instagram Image Enhancement Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-counter-flow-strategy-reversing-your-youtube-video-sequence/"><u>[New] The Counter-Flow Strategy  Reversing Your YouTube Video Sequence</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-troubleshoot-completed/"><u>[PRINTER] Troubleshoot Completed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-epson-error-code-0xf1/"><u>[SOLVED] Epson Error Code 0Xf1</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-diversify-laptop-editing-with-alternatives-to-inshot/"><u>[Updated] 2024 Approved  Diversify Laptop Editing with Alternatives to Inshot</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-academic-history-lovers-guide-to-top-yt-content-for-2024/"><u>[Updated] Academic History Lovers' Guide to Top YT Content for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-maximize-browser-functionality-chromes-full-screen-video-playback/"><u>[Updated] Maximize Browser Functionality  Chrome's Full-Screen Video Playback</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-quick-and-accurate-audio-to-text-conversion-on-youtube-free-methods/"><u>[Updated] Quick and Accurate Audio-to-Text Conversion on YouTube – Free Methods</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-verdict-on-inshot-master-editor/"><u>[Updated] The Verdict on InShot  Master Editor?</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-flying-toys-for-kids-and-family-fun/"><u>2024 Approved  Best Flying Toys for Kids & Family Fun</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-premier-virtual-microphones/"><u>2024 Approved  Premier Virtual Microphones</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-blueprint-for-on-screen-dialogues/"><u>2024 Approved  The Blueprint for On-Screen Dialogues</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-top-chromebook-visual-recorder/"><u>2024 Approved  Top Chromebook Visual Recorder</u></a></li>
<li><a href="https://printer-issues.techidaily.com/a-guide-to-smoothly-linking-canon-printers/"><u>A Guide to Smoothly Linking Canon Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/active-directory-maintenentic-failure-printer-issue/"><u>Active Directory Maintenentic Failure: Printer Issue</u></a></li>
<li><a href="https://win-answers.techidaily.com/civil-case-civ-6-understanding-the-2024-resolution-on-access-denial-issues/"><u>Civil Case #CIV 6 - Understanding the 2024 Resolution on Access Denial Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compreeed-software-bundle-officejet-pro-8600-windows-integration/"><u>Compreeed Software Bundle: OfficeJet Pro 8600, Windows Integration</u></a></li>
<li><a href="https://printer-issues.techidaily.com/default-printer-dilemma-windows-error-0x00000709-squashed/"><u>Default Printer Dilemma: Windows Error (0X00000709) Squashed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-setup-brothers-mfc-9330cdw/"><u>Easy Setup: Brother's MFC-9330CDW</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-end-print-job-wait/"><u>Efficiently End Print Job Wait</u></a></li>
<li><a href="https://article-tips.techidaily.com/effortless-approach-perfecting-time-lapses-using-samsungs/"><u>Effortless Approach  Perfecting Time-Lapses Using Samsungs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/end-of-missing-pages-with-new-tech-update/"><u>End of Missing Pages with New Tech Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/expert-advice-swiftly-dealing-with-pcl-xl-fails/"><u>Expert Advice: Swiftly Dealing with PCL XL Fails</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebook-video-maker-how-to-make-facebook-video-for-2024/"><u>Facebook Video Maker  How to Make Facebook Video for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fine-tune-your-prints-install-new-v305-driver-in-win7/"><u>Fine-Tune Your Prints: Install New V305 Driver in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-speed-and-accuracy-on-windows-11/"><u>Fix Printing Speed and Accuracy on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-offline-printer-on-windows-xpvista7/"><u>Fixing Offline Printer on Windows XP/Vista/7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/from-blank-to-brilliant-overcoming-print-troubles/"><u>From Blank to Brilliant: Overcoming Print Troubles</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-unlock-your-iphone-15-plus-learn-all-4-methods-drfone-by-drfone-ios/"><u>How Do You Unlock your iPhone 15 Plus? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-non-responsive-canon-printer/"><u>How to Fix Non-Responsive Canon Printer</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-note-30i-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Infinix Note 30i Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-integrating-printer-model-8720-in-pc/"><u>How-To: Integrating Printer Model 8720 in PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ignoring-my-printer-what-to-do/"><u>Ignoring My Printer - What to Do?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-honor-x8b-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Honor X8b</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-your-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From your iPhone 6s Plus</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-vivo-y28-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Vivo Y28 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-motorola-moto-g-stylus-2023-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Motorola Moto G Stylus (2023) Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-realme-narzo-60x-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Realme Narzo 60x 5G?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrated-printer-utilities-hp-officejet-pro-8600-win32-version/"><u>Integrated Printer Utilities: HP OfficeJet Pro 8600, Win32 Version</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/management-strategies-for-fetal-alcohol-syndrome-for-2024/"><u>Management Strategies for Fetal Alcohol Syndrome for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/method-to-forget-your-printer-in-windows/"><u>Method to Forget Your Printer in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/non-reactivity-in-canon-printer-mode/"><u>Non-Reactivity in Canon Printer Mode</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-print-performance-dells-latest-aio-upgrades-in-win7/"><u>Optimize Print Performance: Dell's Latest AIO Upgrades in Win7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-spooler-crashing-strategies-for-win-users/"><u>Overcoming Spooler Crashing: Strategies for Win Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-upgrade-paperless-print-error-rectified/"><u>Post-Upgrade, Paperless Print Error Rectified</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-setback-configuration-conundrum/"><u>Print Setback: Configuration Conundrum</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinforce-win10s-networked-printer-setup/"><u>Reinforce WIN10's Networked Printer Setup</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reset-scanner-connection-status-on-pc-windows-10/"><u>Reset Scanner Connection Status on PC, Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-your-prints-install-latest-v305-driver-in-win7/"><u>Revitalize Your Prints: Install Latest V305 Driver in Win7</u></a></li>
<li><a href="https://extra-resources.techidaily.com/soaring-past-competitors-mastering-drone-racing-and-best-fpv-drones/"><u>Soaring Past Competitors  Mastering Drone Racing and Best FPV Drones</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/streamline-your-print-experience-with-win-hp-printer-guide/"><u>Streamline Your Print Experience with Win HP Printer Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-printer-connectivity-issues-in-w11/"><u>Tackle Printer Connectivity Issues in W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackling-noisy-or-disruptive-printers/"><u>Tackling Noisy or Disruptive Printers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-y100i-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-offline-issue-with-ease-in-this-guide/"><u>Troubleshoot Offline Issue with Ease in This Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-graphics-experience-new-geforce-210-drivers-on-windows-nandora-x64/"><u>Update Your Graphics Experience: New GeForce 210 Drivers on Windows Nandora-X64</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/wacky-warriors-tiktoks-most-ingenious-gaming-experienences/"><u>Wacky Warriors  TikTok's Most Ingenious Gaming Experienences</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-sony-xperia-1-v-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Sony Xperia 1 V Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7810-networking-guide-for-inkjet-hp-issues/"><u>Win7/8/10 Networking Guide for Inkjet HP Issues</u></a></li>
</ul></div>
