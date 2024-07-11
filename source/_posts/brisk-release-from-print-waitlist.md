---
title: Brisk Release From Print Waitlist
date: 2024-07-10T17:32:34.349Z
updated: 2024-07-11T17:32:34.349Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Brisk Release From Print Waitlist
excerpt: This Article Describes Brisk Release From Print Waitlist
keywords: Brisk Print Release,Print Waitlist Removal,Fast Printing Service,Printer Access Fast Track,Quick Booking and Printing,Expedited Printing Solutions,Express Publishing Services
thumbnail: https://thmb.techidaily.com/77d2b3ef679b5fcf16ae0f3446de13ba438b3d48f4673334fb3a900060d9f0bc.jpg
---

## Brisk Release From Print Waitlist

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
<li><a href="https://printer-issues.techidaily.com/solving-error-epson-fault-code/"><u>Solving Error: Epson Fault Code</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-worklift-printer-setup-and-use/"><u>HP WorkLift Printer Setup and Use</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unveiling-the-secret-behind-empty-printouts/"><u>Unveiling the Secret Behind Empty Printouts</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brew-the-latest-printer-driver-potion-in-windows-7/"><u>Brew the Latest Printer Driver Potion in WIndows 7</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-duo-fan-setup-instructions/"><u>Brother CDW Duo Fan Setup Instructions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-printer-config-issue-alert/"><u>Unexpected Printer Config Issue Alert</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-stops-printing-post-win11-installation/"><u>Printer Stops Printing Post Win11 Installation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-11-unblocked-scan-functionality/"><u>Windows 11: Unblocked Scan Functionality</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-mf4770n-with-latest-windows-update/"><u>Enhance MF4770n with Latest Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/winning-against-the-new-windows-printing-issue/"><u>Winning Against the New Windows Printing Issue</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tip-uninstalling-default-print-devices/"><u>Quick Tip: Uninstalling Default Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-printer-malfunction-mystery/"><u>Unraveling Printer Malfunction Mystery</u></a></li>
<li><a href="https://printer-issues.techidaily.com/optimize-printing-roll-out-latest-windows-7-dell-updates/"><u>Optimize Printing: Roll-Out Latest Windows 7 Dell Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-woes-after-suspend-on-windows-7-systems/"><u>Printer Woes After Suspend on Windows 7 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-scanner-after-windows-10-update/"><u>Enabling Scanner After Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-optimization-made-simple/"><u>Printer Optimization Made Simple</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-erratic-printer-spooler-behavior-win-11-and-older/"><u>Fixing Erratic Printer Spooler Behavior (Win 11 & Older)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guiding-you-to-a-hassle-free-canon-print-connection/"><u>Guiding You to a Hassle-Free Canon Print Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-configuring-officejet-pro-in-your-pc/"><u>Tutorial: Configuring OfficeJet Pro in Your PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-10-struggles-cannot-find-mp620-printer-drivers/"><u>Windows 10 Struggles: Cannot Find MP620 Printer Drivers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-scanner-disconnection-issue-in-windows-10/"><u>Fixing Scanner Disconnection Issue in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reestablish-printer-with-ease-and-speed/"><u>Reestablish Printer with Ease & Speed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solutions-for-halted-hp-print-operations/"><u>Solutions for Halted HP Print Operations</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-5-ways-to-denoise-a-video-for-2024/"><u>Updated 5 Ways to Denoise a Video for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, Protecting Your Privacy How To Remove Apple ID From Apple iPhone 14 Plus</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-engaging-creativity-crafting-compelling-facebook-ads/"><u>[Updated] 2024 Approved  Engaging Creativity  Crafting Compelling Facebook Ads</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/profiling-perfection-a-visual-guide/"><u>Profiling Perfection  A Visual Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-skype-soundtrack-hub-finding-the-right-tones-online/"><u>[New] 2024 Approved  Skype Soundtrack Hub  Finding the Right Tones Online</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-5-ways-to-send-ringtones-from-apple-iphone-se-2020-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 5 Ways to Send Ringtones from Apple iPhone SE (2020) to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/cost-effective-action-cams-unveiled/"><u>Cost-Effective Action Cams Unveiled</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-elevating-live-game-coverage-tips-and-tricks/"><u>2024 Approved  Elevating Live Game Coverage  Tips and Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/circle-construction-techniques-for-the-aspiring-minecraft-artist/"><u>Circle Construction Techniques for the Aspiring Minecraft Artist</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-xiaomi-13-ultra-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Xiaomi 13 Ultra?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-xr21-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia XR21 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-snapchat-enhancing-images-and-videos/"><u>[New] Mastering Snapchat  Enhancing Images & Videos</u></a></li>
</ul></div>
