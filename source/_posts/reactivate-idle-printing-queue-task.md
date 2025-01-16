---
title: Reactivate Idle Printing Queue Task
date: 2025-01-09T21:20:32.084Z
updated: 2025-01-15T22:29:04.638Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Reactivate Idle Printing Queue Task
excerpt: This Article Describes Reactivate Idle Printing Queue Task
keywords: Reactivate IDLE Printer Queue,Idle Printing Queue Management,Resume Idle Print Jobs,Restart Printer Queue Task,Printing Queue Idle Issue Resolution,Enable Idle Printer Tasks,Revive Non-Active Printer Queue
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Reactivate Idle Printing Queue Task

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

![](https://images.drivereasy.com/wp-content/uploads/2020/01/kisspng-pixel-illustration-printer-5a983b8a6f6aa4.5830009615199261544564.png)

#### Option 2: Automatic printer driver update (Recommended)

 If you don’t have the time, patience, or computer skills to update your audio driver manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your device.

 You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now-1.png)
3. Click the Update button next to your sound card driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers-1.jpg)
4. Restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-balance-youtube-with-a-full-time-job/"><u>[New] In 2024, How to Balance YouTube with a Full-Time Job</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-professional-insights-into-magix-acid-pro-and-alternatives/"><u>[Updated] 2024 Approved Professional Insights Into Magix ACID Pro and Alternatives</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-effortless-avi-gif-conversion-using-filmora-tools-for-2024/"><u>[Updated] Effortless AVI-GIF Conversion Using Filmora Tools for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-rhythmic-reworks-for-enhanced-imovie-experience/"><u>[Updated] Rhythmic Reworks for Enhanced iMovie Experience</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-vivo-y78plus-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Vivo Y78+ to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/cloudsafe-experts-opinion/"><u>CloudSafe Experts Opinion</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-issue-code-b200/"><u>Corrected Issue: Code B200</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-redmi-note-12-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi Redmi Note 12 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/installation-without-hurdles-for-printer/"><u>Installation Without Hurdles for Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instructive-blueprint-attaching-hp-printer-8720-to-windows-system/"><u>Instructive Blueprint: Attaching HP Printer 8720 to Windows System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/mjolnirs-legacy-new-era-dawned/"><u>Mjolnir's Legacy New Era Dawned</u></a></li>
<li><a href="https://printer-issues.techidaily.com/prevent-windows-10-printer-malfunctions-and-fails/"><u>Prevent Windows 10 Printer Malfunctions and Fails</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-connected-problems-resolved-quickly/"><u>Printer Connected, Problems Resolved Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-connectivity-disconnection/"><u>Solved Connectivity Disconnection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successfully-overcoming-post-upgrade-prints/"><u>Successfully Overcoming Post-Upgrade Prints</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-vivo-y36i-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Vivo Y36i Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-5-reasons-to-choose-apcs-back-ups-be6m1-with-integrated-usb-charging-functionality-reviewed/"><u>Top 5 Reasons to Choose APC's Back-UPS BE6#M1 with Integrated USB Charging Functionality Reviewed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-epson-paperless-operation-issue/"><u>Troubleshooting Epson Paperless Operation Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secret-behind-empty-printouts/"><u>Unveiling the Secret Behind Empty Printouts</u></a></li>
</ul></div>

