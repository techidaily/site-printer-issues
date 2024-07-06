---
title: Installation of Printer Finalized
date: 2024-06-28T07:21:31.943Z
updated: 2024-06-29T07:21:31.943Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Installation of Printer Finalized
excerpt: This Article Describes Installation of Printer Finalized
keywords: Printer Setup Guide,How to Install Printer at Home,Complete Printer Installation Tutorial,Printer Setup Instructions for Beginners,DIY Printer Installation Guide,Printer Installation Steps,Troubleshooting Printer Setup Issues
thumbnail: https://thmb.techidaily.com/6029eec233aad0fb3c2ba7e54dc1e274f5e9fe224df2564f74c71f59044219de.jpg
---

## Installation of Printer Finalized

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
<li><a href="https://printer-issues.techidaily.com/troubleshooted-epson-printer-malfunction/"><u>Troubleshooted Epson Printer Malfunction</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-your-canon-printers-non-print-problem-with-these-top-five-tricks-in-windows-11/"><u>Fix Your Canon Printer's Non-Print Problem with These Top Five Tricks in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curb-intermittent-printer-halt-a-win-guide/"><u>Curb Intermittent Printer Halt: A Win Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-installed-network-printer/"><u>Successfully Installed Network Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prompt-recovery-from-idle-printer-job-queue/"><u>Prompt Recovery From Idle Printer Job Queue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ignoring-my-printer-what-to-do/"><u>Ignoring My Printer - What to Do?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tackle-scanning-problems-improve-print-driver-in-windows-10/"><u>Tackle Scanning Problems, Improve Print Driver in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-secrets-to-dell-scanner-issues/"><u>Unlocking Secrets to Dell Scanner Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/paper-trail-points-to-unidentified-user/"><u>Paper Trail Points to Unidentified User</u></a></li>
<li><a href="https://printer-issues.techidaily.com/swift-solutions-to-printer-delays/"><u>Swift Solutions to Printer Delays</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-ultimate-list-10-free-online-video-compressors-without-downloads/"><u>New 2024 Approved The Ultimate List 10 Free Online Video Compressors Without Downloads</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-sonic-alchemy-transforming-footage-through-piano-inspired-soundtracks/"><u>Updated 2024 Approved Sonic Alchemy Transforming Footage Through Piano-Inspired Soundtracks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-free-youtube-outro-kings-6-top-suggestions/"><u>[New] Free YouTube Outro Kings  6 TOP Suggestions!</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-elevate-small-screen-experience-with-these-leading-and-affordable-tools-to-download-youtubes-tiny-videos/"><u>[Updated] 2024 Approved  Elevate Small Screen Experience with These Leading & Affordable Tools to Download YouTubes' Tiny Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-striking-the-perfect-balance-in-profile-videos/"><u>[Updated] In 2024, Striking the Perfect Balance in Profile Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/side-splitting-scripts-crafting-7-hilarious-youtube-scenes-for-2024/"><u>Side-Splitting Scripts  Crafting 7 Hilarious YouTube Scenes for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-samsung-galaxy-m54-5g-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Samsung Galaxy M54 5G Phone</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-honor-magic-v2-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-samsung-galaxy-xcover-7-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Samsung Galaxy XCover 7 Screen | Dr.fone</u></a></li>
</ul></div>
