---
title: How to Stop and Repair Spooler on Windows Versions 7-11
date: 2024-06-28T07:13:19.223Z
updated: 2024-06-29T07:13:19.223Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Stop and Repair Spooler on Windows Versions 7-11
excerpt: This Article Describes How to Stop and Repair Spooler on Windows Versions 7-11
keywords: Stop Spooler,Spooler Repair,Windows 7 Spooler Stop,Windows 10 Spooler Repair,Windows Versions Stop Spooler,Windows 8 Spooler Fix,Windows Server Spooler Stop
thumbnail: https://thmb.techidaily.com/c39d96a0392062878f0d55bc9ae4650b6150e40d84fd4972f36d7344db4ba87f.jpg
---

## How to Stop and Repair Spooler on Windows Versions 7-11

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
<li><a href="https://printer-issues.techidaily.com/precision-guided-instructions-your-ultimate-guide-to-hp-printer-installation/"><u>Precision-Guided Instructions: Your Ultimate Guide to HP Printer Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-guide-to-installing-hp-envy-504-printers/"><u>Step-by-Step Guide to Installing HP Envy 504 Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stepwise-tech-incorporating-hp-printer-into-pc-workflow/"><u>Stepwise Tech: Incorporating HP Printer Into PC Workflow</u></a></li>
<li><a href="https://printer-issues.techidaily.com/zero-in-on-the-problem-discover-these-5-ways-to-help-your-canon-printer-print/"><u>Zero in on the Problem: Discover These 5 Ways to Help Your Canon Printer Print</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-respondent-printer-on-windows-3x-edition/"><u>Revive Non-Respondent Printer on Windows 3.x Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/post-update-printer-stands-silent-no-more/"><u>Post-Update, Printer Stands Silent No More</u></a></li>
<li><a href="https://printer-issues.techidaily.com/cutting-edge-tips-quickly-rectify-pcl-xl-mistakes/"><u>Cutting-Edge Tips: Quickly Rectify PCL XL Mistakes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/easy-steps-to-accelerate-prints/"><u>Easy Steps to Accelerate Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/precision-tactics-to-overcome-non-printing-brother-printer-in-oses/"><u>Precision Tactics to Overcome Non-Printing Brother Printer in OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivate-idle-printing-queue-task/"><u>Reactivate Idle Printing Queue Task</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/tips-for-recording-and-saving-google-voice-interactions/"><u>Tips for Recording and Saving Google Voice Interactions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-streaming-seminar-essential-information-unveiled-for-2024/"><u>Updated Streaming Seminar Essential Information Unveiled for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/leading-platforms-mimicking-twitters-network-for-2024/"><u>Leading Platforms Mimicking Twitter's Network for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-20plus-secrets-to-insta-wonderful-videos/"><u>[Updated] In 2024, 20+ Secrets to Insta-Wonderful Videos</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-samsung-galaxy-f54-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Samsung Galaxy F54 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-intova-edge-x-action-camera-review/"><u>[New] Intova Edge X Action Camera Review</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-perfecting-the-art-of-borders-in-instagram-photos/"><u>In 2024, Perfecting the Art of Borders in Instagram Photos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-guide-to-writing-captivating-docu-scripts-for-2024/"><u>Step-By-Step Guide to Writing Captivating Docu-Scripts for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-enhancing-audio-clarity-in-diy-home-film-production/"><u>New Enhancing Audio Clarity in DIY Home Film Production</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-vivid-storytelling-through-these-top-7-graders-strategies/"><u>In 2024, Vivid Storytelling Through These Top 7 Graders' Strategies</u></a></li>
</ul></div>