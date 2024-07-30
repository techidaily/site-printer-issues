---
title: Prompt Recovery From Idle Printer Job Queue
date: 2024-07-29T00:28:40.940Z
updated: 2024-07-30T00:28:40.940Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Prompt Recovery From Idle Printer Job Queue
excerpt: This Article Describes Prompt Recovery From Idle Printer Job Queue
keywords: Idle Printer Management,Printer Job Queue Optimization,Recovering Stalled Print Jobs,Faster Printer Processing,Idle Printer Solutions,Streamline Print Job Queue,Prevent Printer Idle State
thumbnail: https://thmb.techidaily.com/b26ebe6269139cbbd405443b637f006fbb51cb0816412b85d5c12d4c87d21986.jpg
---

## Prompt Recovery From Idle Printer Job Queue

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/services-run-box.jpg)
3. Scroll down to**Print Spooler** .
4. Right-click**Print Spooler** and select**Stop** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/stop-the-service.jpg)
5. Navigate to**C:\\Windows\\System32\\spool\\PRINTERS** and delete all files in the folder. (Do NOT delete the folder itself.)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/delete.jpg)
6. In the Services window, right-click**Print Spooler** and select**Start** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/start-service.jpg)
7. Go back to the**Print Job** queue. All print jobs should have been removed now and you can start printing again normally.

**Have trouble deleting the files?**
  
 Before deleting the files in the PRINTERS folder, you need to stop the Printer Spooler first. Otherwise, you’ll get an error message that says something like**The action cannot be completed because the file is open** .  
  
 After deleting the files, don’t forget to restart the service again.

#### Option 2: Use Command Prompt to Clear Stuck Files

 The fastest way to clear the print queue is through the command prompt. It just takes a few commands:

1. Type**cmd** in the search box and Run it as administrator.  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
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
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/kisspng-pixel-illustration-printer-5a983b8a6f6aa4.5830009615199261544564.png)

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-probing-into-asuss-proart-pa-329q-professional-4k-display-review-insights/"><u>[New] 2024 Approved  Probing Into Asus's ProArt PA 329Q – Professional 4K Display Review Insights</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-speak-with-ease-simple-pubg-sound-tweaks/"><u>[New] In 2024, Speak with Ease  Simple PUBG Sound Tweaks</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chorus-to-clips-soundtracking-in-imovie/"><u>[Updated] Chorus to Clips  Soundtracking in iMovie</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-win11s-best-videography-applications-explored/"><u>[Updated] Win11's Best Videography Applications Explored</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unraveling-iphone-photo-blur-techniques-4-ways-explored/"><u>2024 Approved  Unraveling iPhone Photo Blur Techniques - 4 Ways Explored</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/avoiding-constant-printer-service-interruptions-on-win7win10/"><u>Avoiding Constant Printer Service Interruptions on Win7/Win10</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/boost-your-posts-with-these-8-instagram-scheduling-apps-for-2024/"><u>Boost Your Posts with These 8 Instagram Scheduling Apps for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/deciphering-hp-printers-error-code-oxc4eb827f/"><u>Deciphering HP Printer's Error Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/diagnose-and-cure-win10-print-spooler-hiccups/"><u>Diagnose & Cure WIN10 Print Spooler Hiccups</u></a></li>
<li><a href="https://printer-issues.techidaily.com/domain-services-unreachable-print-issue/"><u>Domain Services Unreachable, Print Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-your-hp-printer-via-win32-api/"><u>Efficiently Setting Up Your HP Printer via Win32 API</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortlessly-bridge-your-printer-and-wifi-with-canon/"><u>Effortlessly Bridge Your Printer and Wifi with Canon</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-non-responsive-epson-device/"><u>Fixed Non-Responsive Epson Device</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-erratic-printer-spooler-behavior-win-11-and-older/"><u>Fixing Erratic Printer Spooler Behavior (Win 11 & Older)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/healed-printer-communication-link/"><u>Healed Printer Communication Link</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-samsung-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Samsung ’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-d1360-overcoming-driver-installation-obstacles-in-multiple-os-environments/"><u>HP D1360: Overcoming Driver Installation Obstacles in Multiple OS Environments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-not-printing-solved/"><u>HP Printer Not Printing [SOLVED]</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-do-reviewers-monetize-their-critiques-in-media/"><u>In 2024, Do Reviewers Monetize Their Critiques in Media?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/install-brother-wireless-9330cdw-fan/"><u>Install Brother Wireless 9330CDW Fan</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-inaccessible-printer-connection/"><u>Mended Inaccessible Printer Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-snag-another-systems-footprint-found/"><u>Printer Snag: Another System's Footprint Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-fix-for-broken-feeders/"><u>Quick-Fix for Broken Feeders</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quickly-rectify-non-printing-problem-top-5-techniques-to-aid-canon-print-on-window-11/"><u>Quickly Rectify Non-Printing Problem: Top 5 Techniques to Aid Canon Print on Window 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/re-establishing-connection-between-printer-and-wifi/"><u>Re-Establishing Connection Between Printer & WiFi</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-hp-photosmart-205n-printer-functions/"><u>Repaired HP Photosmart 205N Printer Functions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-non-responding-printer-on-windows-me-version/"><u>Revitalize Non-Responding Printer on Windows ME Version</u></a></li>
<li><a href="https://fix-guide.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-installation-of-multi-function-printer/"><u>Successful Installation of Multi-Function Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-printer-operation-post-windows-10-update/"><u>Unblocking Printer Operation Post-Windows 10 Update</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-video-potential-with-top-titler-ai-for-2024/"><u>Unlock Video Potential with Top Titler AI for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/unmatched-pixels-the-exclusive-advantages-of-hp-envy-27-for-2024/"><u>Unmatched Pixels  The Exclusive Advantages of HP Envy 27 for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/upgrading-to-flawless-mf4770n-operation-in-windows-1187/"><u>Upgrading to Flawless MF4770n Operation in Windows 11/8/7</u></a></li>
</ul></div>
