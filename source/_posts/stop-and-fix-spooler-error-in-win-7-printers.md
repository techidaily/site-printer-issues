---
title: Stop and Fix Spooler Error in Win 7 Printers
date: 2024-06-28T06:50:09.519Z
updated: 2024-06-29T06:50:09.519Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Stop and Fix Spooler Error in Win 7 Printers
excerpt: This Article Describes Stop and Fix Spooler Error in Win 7 Printers
keywords: Stop Spooler Errors (High Relevance, Moderate Competition),Fix Spooler Error in Win 7 (Moderate Relevance, Low Competition),Spooler Issue Resolution for Printers (Medium Relevance, Medium Competition),Resolve Spooler Issues on Windows 7 (Medium Relevance, Medium Competition),Stop Spooler Errors in Printer Software (Low Relevance but Can Capture a Niche Audience),Troubleshoot Printer Spooler Problems in Win 7 (High Relevance and Specific to the Target Issue),Fix Spooling Error on Windows 7 Printers (Medium-High Relevance, Low Competition)
thumbnail: https://thmb.techidaily.com/97d52aeba0c3812671b16d9ad71aaf02069e7e610c93642b0ee7efd4388d9316.jpg
---

## Stop and Fix Spooler Error in Win 7 Printers

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

5) Check to see if your printer works.

### Method 3: Change the Print Spooler Recovery options

 If your print spooler recovery settings are incorrect, your print spooler won’t automatically restart if it fails for some reason.

 To set your recovery settings correctly:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click **Print Spooler** , then click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a54177dc82e.jpg)

 4) Click **Recovery** , ensure all **three** **failure fields** are set to **Restart the Service**  and click**Apply** \> **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a51c37d1a84.png)

 5) Check to see if your printer works.  

### Method 4: Delete your print spooler files

 If your pending print jobs are not few, they can cause your print spooler to stop. Deleting your print spooler files to clear pending print jobs sometimes resolve the problem.

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type**services.msc** and press**Enter** to open the**Services** window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

3) Click **Print Spooler** , then **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a5269d7216e.jpg)

 4) Click**—** to minimize the Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/minimize.jpg)

 5) On your keyboard, press the   **Windows logo key**  and **E**  at the same time to open Windows File Explorer.  

 6) Go to **C:\\Windows\\System32\\spool\\PRINTERS** :

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS.jpg)

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

 12) Click**Services** icon in your taskbar to return to Services window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/SETTINGS-WINDOW.jpg)

 13) Click on**Print Spooler** then**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a538386c9a4.jpg)

 14)Click the **Devices and Printers icon**  in your taskbar to return to the Devices and Printers window:

![](https://images.drivereasy.com/wp-content/uploads/2017/04/PRINTERS-ICON.jpg)

 15) **Right-click on the blank area** and click **Add a printer**  , then follow the on-screen instructions to re-add your printer:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a542a63d1d0.png)

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
<li><a href="https://printer-issues.techidaily.com/fixing-print-problems-canon-printer-guide-in-windows-10/"><u>Fixing Print Problems: Canon Printer Guide in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-issue-mp620-not-detected-by-win11/"><u>Canon Printer Issue: MP620 Not Detected by Win11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-issue-code-b200/"><u>Corrected Issue: Code B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-five-simplified-steps-for-no-printing-canon-printers-on-windows-11/"><u>Troubleshooting: Five Simplified Steps for No-Printing Canon Printers on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ignoring-my-printer-what-to-do/"><u>Ignoring My Printer - What to Do?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-non-responsive-canon-printer/"><u>Reviving a Non-Responsive Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/why-is-my-printer-black-and-white/"><u>Why Is My Printer Black & White?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-non-responsive-print-devices/"><u>Solutions for Non-Responsive Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-a-printer-that-wont-print/"><u>How to Fix a Printer That Won't Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revolutionize-your-printing-3-futuristic-solutions-to-connect-hp-and-laptop/"><u>Revolutionize Your Printing: 3 Futuristic Solutions to Connect HP & Laptop</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-transformative-talk-20-phrases-that-drive-business-growth/"><u>In 2024, Transformative Talk  20 Phrases That Drive Business Growth</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-tecno-spark-20c-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Tecno Spark 20C Black and White | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-up-your-content-game-top-30-video-plans/"><u>[Updated] Step Up Your Content Game  Top 30 Video Plans</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-realme-11x-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Realme 11X 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/discord-nitro-demystified-the-ultimate-vip-service-for-gamers-for-2024/"><u>Discord Nitro Demystified  The Ultimate VIP Service for Gamers for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-oneplus-nord-ce-3-5g-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For OnePlus Nord CE 3 5G Phones</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-the-power-of-ai-thumbnail-generators/"><u>New In 2024, The Power of AI Thumbnail Generators</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-complete-guide-to-earnings-via-vimeo-ads/"><u>[New] The Complete Guide to Earnings via Vimeo Ads</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-make-subtitle-videos/"><u>New 2024 Approved How to Make Subtitle Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/expert-video-grabbing-extras-fb-and-firefox-edition-for-2024/"><u>Expert Video Grabbing Extras  FB & Firefox Edition for 2024</u></a></li>
</ul></div>