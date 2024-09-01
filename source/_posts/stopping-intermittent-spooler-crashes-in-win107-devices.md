---
title: Stopping Intermittent Spooler Crashes in Win10/7 Devices
date: 2024-08-31T04:36:57.612Z
updated: 2024-09-01T04:36:57.612Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stopping Intermittent Spooler Crashes in Win10/7 Devices
excerpt: This Article Describes Stopping Intermittent Spooler Crashes in Win10/7 Devices
keywords: Intermittent Spooler Crash Fix,Stop SPOOLER in Windows 10/7,Spooler Crashes Resolution,Windows 10/7 Spooler Troubleshooting,Spooler Crash Prevention in Win 10/7,Intermittent Spooler Errors Windows Fix,Spooler Stability in Win10 Devices
thumbnail: https://thmb.techidaily.com/ee5c0d7e477d155cf7c4d7a41bb4baf523bd4dd370c1eec84bd95b2e762714db.png
---

## Stopping Intermittent Spooler Crashes in Win10/7 Devices

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-24.jpg)

 If you’re on Windows 7 or 10, and you’re seeing this error saying your**print spooler isn’t running** , you’re not alone. Many Windows users are reporting it. But the good news is you can fix it. This article gives you 5 solutions to try.

## What’s the print spooler?

 The print spooler is a Windows service that manages all the print jobs you send to your printer. If the service isn’t running, your printer won’t work.

## How do I fix print spooler keeps stopping?

 Here are 5 solutions you can try to fix this problem. You may not have to try them all; just work your way down the list until you find the one that works.**Note:** The screens shown below are from Windows 10, but all the fixes also apply to Windows 7 too.

1. **[Restart the Print Spooler service](#F1)**
2. **[Check if the Print Spooler service is set to Automatic](#F2)**
3. **[Change the Print Spooler Recovery options](#F3)**
4. **[Delete your print spooler files](#F4)**
5. **[Update your printer driver](#F5)**

### Method 1: Restart the Print Spooler service

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type **services.msc** and press **Enter** to open the **Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Click **Print Spooler** , then **Restart** .  

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a515fac43cb.jpg)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Check to see if your printer works.

### Method 2: Check if the Print Spooler service is set to Automatic

 If the print spooler service isn’t set to automatic, it won’t turn on when Windows starts, and your printer won’t work until you manually start the service.

To set it to auto:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

3) Right-click **Print Spooler** , then click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a54177dc82e.jpg)

 4) Make sure Startup type is set to **Automatic**  , then click**Apply** \> **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a51825cb795.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5) Check to see if your printer works.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
### Method 3: Change the Print Spooler Recovery options

 If your print spooler recovery settings are incorrect, your print spooler won’t automatically restart if it fails for some reason.

 To set your recovery settings correctly:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 3) Right-click **Print Spooler** , then click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a54177dc82e.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Click **Recovery** , ensure all **three** **failure fields** are set to **Restart the Service**  and click**Apply** \> **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a51c37d1a84.png)

 5) Check to see if your printer works.  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
### Method 4: Delete your print spooler files

 If your pending print jobs are not few, they can cause your print spooler to stop. Deleting your print spooler files to clear pending print jobs sometimes resolve the problem.

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

3) Click **Print Spooler** , then **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a5269d7216e.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 4) Click**—** to minimize the Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/minimize.jpg)

 5) On your keyboard, press the   **Windows logo key**  and **E**  at the same time to open Windows File Explorer.  

 6) Go to **C:\\Windows\\System32\\spool\\PRINTERS** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you’re prompted about permission, click **Continue** .

 7)**Delete all the files** in PRINTERS folder.You should then see **This folder is empty** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/empty.jpg)

8) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

9) Type control and press**Enter** to open Control Panel:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a53a72eb0b7.png)

 10) On the open window, choose to view by**Catalog** . Then click**View devices and printers** .

![](https://images.drivereasy.com/wp-content/uploads/2017/04/control-Panel.jpg)

 11) Right-click on your printer and click **Remove device** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/REMOVE.jpg)

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 12) Click**Services** icon in your taskbar to return to Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/SETTINGS-WINDOW.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
 13) Click on**Print Spooler** then**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a538386c9a4.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 14)Click the **Devices and Printers icon**  in your taskbar to return to the Devices and Printers window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS-ICON.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
 15) **Right-click on the blank area** and click **Add a printer**  , then follow the on-screen instructions to re-add your printer:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a542a63d1d0.png)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
16) Check to see if your printer works.

### Method 5: Update your printer driver

 This error may also be caused by an old or incorrect printer driver. You can update your printer driver manually or, if you’re not confident playing around with drivers, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975af310cda9.jpg)

3) Click the **Update**  button next to a flagged printer driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5976a910cca49.jpg)

 After you update your printer driver, restart your PC and check if your printer works.

 Hopefully your printer is now working. Please feel free to leave a comment below if you have any problems.

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
<li><a href="https://facebook-videos.techidaily.com/new-a-guide-to-tailoring-your-hashtag-strategy-for-maximum-engagement-and-conversion-rates-on-facebook-for-2024/"><u>[New] A Guide to Tailoring Your Hashtag Strategy for Maximum Engagement and Conversion Rates on Facebook for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-glitch-canon-pixma-mp620-drivers-on-win11-unseen/"><u>[Technical Glitch] Canon Pixma MP620 Drivers on Win11 Unseen</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-experience-professional-facebook-profile-picture-design-with-these-tools-for-2024/"><u>[Updated] Experience Professional Facebook Profile Picture Design with These Tools for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ice-cream-capture-technology-reviewed-deeply-for-2024/"><u>[Updated] Ice Cream Capture Technology Reviewed Deeply for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-multi-image-melding-on-computers/"><u>[Updated] Mastering Multi-Image Melding on Computers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unlocking-youtubes-hidden-gems-keyword-research/"><u>[Updated] Unlocking YouTube's Hidden Gems  Keyword Research</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quickshot-maker-for-videoplusimage-sync/"><u>2024 Approved  QuickShot Maker for Video+Image Sync</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-nubia-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Nubia Phone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/amazons-game-changing-halo-device-redefining-invasive-wellbeing-surveillance/"><u>Amazon's Game-Changing Halo Device: Redefining Invasive Wellbeing Surveillance</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-darkness-expert-tips-for-solving-obs-game-capturing-issues/"><u>Beat the Darkness: Expert Tips for Solving OBS Game Capturing Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-the-code-on-non-printing-printers/"><u>Breaking the Code on Non-Printing Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ceased-epson-standby-error/"><u>Ceased Epson Standby Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/connect-printer-with-a-click-no-delay/"><u>Connect Printer with a Click, No Delay</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ideal-iphone-location-tools-our-choice-of-top-5/"><u>Discover the Ideal iPhone Location Tools: Our Choice of Top 5</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-canons-error-b200/"><u>Fixed Canon's Error: B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-the-printing-glitch-error-0x00000709-resolved/"><u>Fixed the Printing Glitch - Error 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-blank-page-syndrome-in-print-devices/"><u>Fixing Blank Page Syndrome in Print Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-xiaomi-redmi-note-12-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Xiaomi Redmi Note 12 5G? Try These Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-react-printer-disconnects-during-print-job/"><u>How To React: Printer Disconnects During Print Job</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-set-up-a-wireless-printer-with-hp-color-life-series/"><u>How To: Set Up a Wireless Printer with HP Color Life Series</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-spectral-photography-takes-a-quantum-leap-with-blade-4k/"><u>In 2024, Spectral Photography Takes a Quantum Leap with Blade 4K</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-oneplus-11r-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on OnePlus 11R</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-installation-made-simple/"><u>MFC-9330 Installation Made Simple</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-no-response-issues-with-hp-printers/"><u>Overcoming No Response Issues with HP Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-in-pages-a-success-story-for-printers/"><u>Precision in Pages: A Success Story for Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-default-error-code-0x00000709-resolved/"><u>Printer Default Error Code 0X00000709 Resolved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574178084-printer-woes-in-windows-11-help-needed/"><u>Printer Woes in Windows 11 - Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-color-rejection/"><u>Printer's Color Rejection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/recommendations-for-reactivating-hp-print-headless-systems/"><u>Recommendations for Reactivating HP Print Headless Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reignite-your-brother-printers-print-function-on-windows-1011/"><u>Reignite Your Brother Printer's Print Function on Windows 10/11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-issue-code-b200/"><u>Resolved Issue Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackled-ink-cartridge-error/"><u>Tackled Ink Cartridge Error</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-offline-hp-xp-paper-issue/"><u>Troubleshooting Offline HP XP Paper Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-the-erratic-behavior-of-print-spooler-windows/"><u>Troubleshooting the Erratic Behavior of Print Spooler (Windows)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unblocking-offline-status-hp-printer-on-dos-systems/"><u>Unblocking Offline Status: HP Printer on DOS Systems</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-11-pro-lock-with-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 11 Pro lock with iCloud</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-hidden-cause-of-blank-printouts/"><u>Unveiling the Hidden Cause of Blank Printouts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-huawei-nova-y71-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Huawei Nova Y71? Fixed | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-paper-trail-issue-error-0x00000709-solution-found/"><u>Windows Paper Trail Issue - Error 0X00000709 Solution Found</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-xp-non-responsive-printer-issue-resolved/"><u>Windows XP: Non-Responsive Printer Issue Resolved</u></a></li>
</ul></div>
