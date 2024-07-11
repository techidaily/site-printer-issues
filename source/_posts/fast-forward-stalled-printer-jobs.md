---
title: Fast-Forward Stalled Printer Jobs
date: 2024-07-10T17:27:11.985Z
updated: 2024-07-11T17:27:11.985Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Fast-Forward Stalled Printer Jobs
excerpt: This Article Describes Fast-Forward Stalled Printer Jobs
keywords: Printer Job Stall,Fast-Forward Printer Error,Print Spooler Stalling,Printer Queue Management,Resolve Print Job Failure,Print Spooler Service Errors,Optimize Print Job Performance
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## Fast-Forward Stalled Printer Jobs

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

**OR** click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  . You will get full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click_Update All_ .)  
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
<li><a href="https://printer-issues.techidaily.com/printer-failure-no-drive-found-on-win/"><u>[PRINTER FAILURE] No Drive Found on Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolved-shared-printer-usage-concern/"><u>Resolved: Shared Printer Usage Concern</u></a></li>
<li><a href="https://printer-issues.techidaily.com/search-unsuccessful-for-windows-printer-driver/"><u>Search Unsuccessful for Windows Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/no-more-white-pages-a-printers-triumph-story/"><u>No More White Pages: A Printer's Triumph Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/endless-white-refills-in-epson-printing-issue/"><u>Endless White Refills in Epson Printing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-sync-with-print-devices/"><u>Restoring Sync with Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mfc-9330-wireless-setup-guide-for-brother-fans/"><u>MFC-9330 Wireless Setup Guide for Brother Fans</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnect-your-silent-canon-printer-now/"><u>Reconnect Your Silent Canon Printer Now!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/revitalize-non-responding-printer-on-windows-me-version/"><u>Revitalize Non-Responding Printer on Windows ME Version</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-printer-connection-remedy/"><u>Quick Printer Connection Remedy</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhancing-mf4770n-performance-in-windows-108/"><u>Enhancing MF4770n Performance in WIndows 10/8</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-successful/"><u>Printer Setup: Successful</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reactivating-online-status-of-windowshp-multi-function/"><u>Reactivating Online Status of Windows/HP Multi-Function</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-react-printer-disconnects-during-print-job/"><u>How To React: Printer Disconnects During Print Job</u></a></li>
<li><a href="https://printer-issues.techidaily.com/os-mismatch-unable-to-load-printer-driver/"><u>[OS MISMATCH] Unable to Load Printer Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-canon-error-b200/"><u>Eradicated Canon Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eliminating-empty-pages-a-printers-success-story/"><u>Eliminating Empty Pages: A Printer's Success Story</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-due-to-domain-service-outage/"><u>Printer Problem Due to Domain Service Outage</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-d1360-printer-drivers-not-working-on-windows-7-10/"><u>[Fix] D1360 Printer Drivers Not Working on Windows 7-10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-non-operational-scanner-on-windows-11/"><u>Fixing Non-Operational Scanner on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/stop-your-wastelanded-printer-on-windows-11/"><u>Stop Your Wastelanded Printer on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-print-issue-with-brother-printer-in-windows-oses/"><u>Resolving No-Print Issue with Brother Printer in Windows OSes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-setup-crisis-averted-zeroing-out-error-0x00000709/"><u>Printer Setup Crisis Averted - Zeroing Out Error (0X00000709)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-guide-to-effective-video-capturing-via-screencastify/"><u>In 2024, Guide to Effective Video Capturing via Screencastify</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-avoiding-common-nocturnal-photography-errors/"><u>[Updated] In 2024, Avoiding Common Nocturnal Photography Errors</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-nokia-g42-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tailored-tips-for-maximizing-vlc-playback-potential/"><u>In 2024, Tailored Tips for Maximizing VLC Playback Potential</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-beyond-typography-decoding-the-subtext-of-snapchat-emojis-for-2024/"><u>[Updated] Beyond Typography  Decoding the Subtext of Snapchat Emojis for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-xiaomi-redmi-a2plus-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Xiaomi Redmi A2+ Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-laughter-is-free-access-to-top-meme-creations/"><u>2024 Approved  Laughter Is Free  Access to Top Meme Creations</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-quick-guide-to-sharing-your-favorite-gifs-on-instagram/"><u>[Updated] Quick Guide to Sharing Your Favorite GIFs on Instagram</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-best-youtube-hubs-for-professional-insights/"><u>[Updated] Best YouTube Hubs for Professional Insights</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/onnected-video-experience-joining-on-youtube-for-2024/"><u>One Connected Video Experience  Joining on YouTube for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-newcomers-elite-entryway-list-for-zooids/"><u>[Updated] Newcomers’ Elite Entryway List for Zooids</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-exploring-key-components-and-creation-process-of-ai-face-generators-for-2024/"><u>New Exploring Key Components and Creation Process of AI Face Generators for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/convenience-at-your-fingertips-enable-autoplay-of-youtube-videos-on-fb-for-2024/"><u>Convenience at Your Fingertips  Enable Autoplay of YouTube Videos on FB for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-unlock-your-music-expert-advice-on-converting-soundcloud-to-mp3/"><u>New Unlock Your Music Expert Advice on Converting Soundcloud to MP3</u></a></li>
</ul></div>
