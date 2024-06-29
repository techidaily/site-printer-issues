---
title: Successfully Installed Network Printer
date: 2024-06-28T06:55:06.970Z
updated: 2024-06-29T06:55:06.970Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Successfully Installed Network Printer
excerpt: This Article Describes Successfully Installed Network Printer
keywords: Network Printer Installation,Setting Up Shared Printing Devices,Easy Network Printer Setup Guide,Home Office Printer Configuration,Network Printer Connectivity Tips,Guide to Installing Network Devices in Businesses,How to Set Up a Wireless Printer on Your Network
thumbnail: https://thmb.techidaily.com/83c5660b04b63555c35a3b29a7e2fd7ac8060798e2fb3cf7dc99c41ddcfc3162.jpg
---

## Successfully Installed Network Printer

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57971bf8a9ed1.png)

 “**Unable to install Printer.Operation could not be completed** ” could occur during installing printer or using the printer, especially after a Windows upgrade or reinstall. The problem can be caused by several issues. If you run into this problem, just try the **three**  solutions below and the problem should resolve.

## Solution**1: Start the Print Spooler service**

 The problem can occur if the print spooler service is stopped. So make sure the service is started. If it’s stopped, start it. To check and start the service, follow these steps:

1) Press **Win+R**  (Windows logo key and R key) at the same time to invoke the Run box.

2) Type **services.msc** in the run box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57870f53c80aa.png)

3) Double-click on**Sprint Spooler** to open the Properties dialog box.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57870fec6b0f3.png)
  
 4) If the “Service status” is Stopped, click the **Start** button. And make sure the “Startup type” has been set as**Automatic** . After that, click the **OK** button to save the change.  

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5797242d45d94.png)

5) Reboot your PC for the change to take effect.

This should fix the problem. If not, proceed to solution 2.

---

## **Solution 2: Update the printer driver**

 A faulty, corrupt or missing printer driver can caused “Unable to install Printer.Operation could not be completed” error. To resolve the issue, you can update the printer driver.

 If you don’t have time, patience and computer skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. **But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee)** :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b6276881dc81.jpg)

 3) Click the **Update** button next to the printer driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b627664eb496.jpg)

4) After updating the driver, check to see if the problem is resolved.

---

## **Solution 3: Delete the printer keys**

 The problem can be caused by driver conflicting. To resolve the problem, you can delete the certain registry entries.

**IMPORTANT** : Modifying registry incorrectly can cause serious system issues. Before following the below procedures, it’s recommended that you back up the registry first, then you could restore them if necessary. See [How to Back Up and Restore Registry](https://tools.techidaily.com/drivereasy/download/) .

To delete the printer keys, here’s what you need to do:

**Firstly, Stop the “Print Spooler” service first** (Refer to**Solution 1** to stop the Print Spooler service). Then follow steps below:

1) Delete all contents from following folders:

**C:\\Windows\\System32\\Spool\\Printers**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5797354018fd8.png)
  
 **C:\\Windows\\System32\\Spool\\Drivers\\w32x86**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57973526811ea.png)

2) Press **Win+R** (Windows logo key and R key) at the same time to invoke the Run box.

3) Type**regedit**  in the run box and click **OK** to open  the Registry Editor dialog box.  

![](https://images.drivereasy.com/wp-content/uploads/2016/03/img_56fb391581cd9.png)

 4) Locate the following registry key according to the system version installed on your PC . If you’re not sure what specific version of Windows you have, refer to [Quickly Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) .

 For**32-bit** operating system:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Print\\Environments\\Windows NT x86\\Drivers\\Version-x** (Note x will be a different number in different PC. In my case, it is version-3.)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972e8c6def5.png)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972ed64a5f9.png)

For   **64-bit** operating system:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Print\\Environments\\Windows x64\\Drivers\\Version-x**  (Note x will be a different number in different PC. In my case, itis version-3.)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972e8c6def5.png)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57972f5298c63.png)

 5) Select this folder and you will see all printer registry entries in right pane. Right-click on the entry and select**Delete** from the context menu. Delete all registry entries here.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57981fd9161d2.png)

6) Start the “Print Spooler” service.

7) Reboot your PC and check to see if the problem is resolved.

---

 Hopefully solutions here will help you fix the “Unable to install Printer.Operation could not be completed” error. If you have any questions, feel free to leave your comments below. We’d love to hear of any ideas or suggestions.

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
<li><a href="https://printer-issues.techidaily.com/resolved-printer-network-failure/"><u>Resolved Printer Network Failure</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revive-non-respondent-printer-on-windows-3x-edition/"><u>Revive Non-Respondent Printer on Windows 3.x Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-correct-power-settings-on-devices/"><u>Enabling Correct Power Settings on Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unable-to-produce-full-color-prints/"><u>Unable to Produce Full-Color Prints</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/b200-corrective-action-complete/"><u>B200 Corrective Action Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-epsons-lack-of-print-feature/"><u>Overcoming Epson's Lack of Print Feature</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/finding-your-perfect-tone-strategies-for-personalized-vocal-change/"><u>Finding Your Perfect Tone Strategies for Personalized Vocal Change</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-essential-skills-androids-screen-recording-functionality/"><u>[Updated] 2024 Approved  Essential Skills  Android's Screen Recording Functionality</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/video-editing-fixing-youtube-short-fails-for-2024/"><u>Video Editing  Fixing YouTube Short Fails for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-effortless-giggle-editor/"><u>[Updated] Ultimate Effortless Giggle Editor</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhancing-youtube-videos-with-professional-techniques-using-wmm-for-2024/"><u>[Updated] Enhancing YouTube Videos with Professional Techniques Using WMM for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-make-a-statement-10-best-animated-text-generators-for-eye-catching-content/"><u>Updated In 2024, Make a Statement 10 Best Animated Text Generators for Eye-Catching Content</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/itel-a70-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Itel A70 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-online-video-spinners-rotate-your-clips-with-ease/"><u>In 2024, Best Online Video Spinners Rotate Your Clips with Ease</u></a></li>
</ul></div>
