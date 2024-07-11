---
title: Speed Up Stalled Printer Tasks
date: 2024-07-10T16:54:19.256Z
updated: 2024-07-11T16:54:19.256Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Speed Up Stalled Printer Tasks
excerpt: This Article Describes Speed Up Stalled Printer Tasks
keywords: Printer Speed Optimization,Fixing Printer Lag Issues,Enhance Print Task Performance,Print Task Acceleration Tips,Resolve Printer Slowdowns,Improving Printer Workflow Efficiency,Printer Task Streamlining Techniques
thumbnail: https://thmb.techidaily.com/4e8500390862c71ba9fd3f45025661c15b6c8c5d9fdf1c818444f469b9c52d07.PNG
---

## Speed Up Stalled Printer Tasks

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
<li><a href="https://printer-issues.techidaily.com/streamline-print-process-uncover-these-simple-steps-for-non-printing-canon-on-windows-11/"><u>Streamline Print Process: Uncover These Simple Steps for Non-Printing Canon on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-non-printing-in-canon-printers-windows-edition/"><u>Overcome Non-Printing in Canon Printers, Windows Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-driver-installation-complete/"><u>Print Driver Installation Complete</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unite-your-workspace-3-cutting-edge-solutions-for-hp-and-laptop-connection/"><u>Unite Your Workspace: 3 Cutting-Edge Solutions for HP and Laptop Connection</u></a></li>
<li><a href="https://printer-issues.techidaily.com/pprinterror-active-directory-service-unavailable/"><u>PPrintError: Active Directory Service Unavailable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fix-printing-queue-error-messages-on-windows-11/"><u>Fix Printing Queue Error Messages on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-printer-stopped-working-after-windows-10-update/"><u>SOLVED: Printer Stopped Working After Windows 10 Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mastering-hp-printer-configuration-on-microsoft-systems/"><u>Mastering HP Printer Configuration on Microsoft Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/keep-your-v305-printing-fresh-with-windows-updates/"><u>Keep Your V305 Printing Fresh with WIndows Updates</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-steps-to-tackle-pcl-xl-setbacks/"><u>Effortless Steps to Tackle PCL XL Setbacks</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tactics-for-uninstalling-windows-printers/"><u>Tactics for Uninstalling Windows Printers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-nt-os-print-error-speed-up-responsiveness/"><u>Overcome NT OS Print Error: Speed Up Responsiveness</u></a></li>
<li><a href="https://printer-issues.techidaily.com/smooth-start-initiating-your-hp-printer-for-windows-users/"><u>Smooth Start: Initiating Your HP Printer for Windows Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/address-printer-driver-bugs-in-win10/"><u>Address Printer Driver Bugs in Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficient-operation-windows-compatible-driver-for-officejet-pro-8600/"><u>Efficient Operation: Windows Compatible Driver for Officejet Pro 8600</u></a></li>
<li><a href="https://printer-issues.techidaily.com/missing-component-pixma-mp620-driver-on-windows-10/"><u>[Missing Component] Pixma MP620 Driver on Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicated-canon-error-b200/"><u>Eradicated Canon Error B200</u></a></li>
<li><a href="https://printer-issues.techidaily.com/ultimate-guide-hp-and-laptop-interaction-3-key-fixes/"><u>Ultimate Guide: HP & Laptop Interaction - 3 Key Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-printer-unresponsiveness-in-windows-millennium-edition/"><u>Overcoming Printer Unresponsiveness in Windows Millennium Edition</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconnected-disabled-printer-service/"><u>Reconnected Disabled PRINTER Service</u></a></li>
<li><a href="https://printer-issues.techidaily.com/whiteout-printing-issue-plaguing-my-epson-model/"><u>Whiteout Printing Issue Plaguing My Epson Model</u></a></li>
<li><a href="https://printer-issues.techidaily.com/supercharge-dells-v305-inkjets-with-new-windows-driver/"><u>Supercharge Dell's V305 Inkjets with New Windows Driver</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-paper-jam-resolved-quickly/"><u>Epson Paper Jam, Resolved Quickly</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win11-and-mp620-printer-wheres-the-compatibility/"><u>Win11 & MP620 Printer: Where's the Compatibility?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-constructive-methods-for-muting-users/"><u>[New] 2024 Approved  Constructive Methods for Muting Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-higher-view-counts-through-sustained-compliance-with-youtube-cc-for-2024/"><u>Unlocking Higher View Counts Through Sustained Compliance with YouTube CC for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-sculpt-visual-jokes-adobe-memes-guide/"><u>[Updated] Sculpt Visual Jokes  Adobe Memes Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Lava Blaze 2 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-transform-low-res-videos-into-high-definition-masterpieces-for-2024/"><u>Updated Transform Low-Res Videos Into High-Definition Masterpieces for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/instantpause-live-image-save-tips/"><u>InstantPause  Live Image Save Tips</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-glitches-and-error-0xc00d36b4-on-windows/"><u>Troubleshooting Glitches & Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-review-of-yuneecs-aerodrone-typhoon-h-insights-and-results/"><u>2024 Approved  Review of Yuneec’s AeroDrone Typhoon H  Insights and Results</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sony-a6400-video-vanishing-how-to-stop-it-in-2024/"><u>Sony A6400 Video Vanishing - How to Stop It, In 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-top-8-audio-capture-tools-for-live-broadcasts-and-recordings/"><u>Updated In 2024, Top 8 Audio Capture Tools for Live Broadcasts and Recordings</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-13ipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on Apple iPhone 13/iPad/iPod</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-mastering-simple-multi-snap-chat-video-creation-and-editing/"><u>[New] In 2024, Mastering Simple Multi-Snap Chat Video Creation & Editing</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-top-5-methods-for-creating-an-impressive-tiktok-introduction-with-macos/"><u>2024 Approved  Top 5 Methods for Creating an Impressive TikTok Introduction with MacOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-free-clip-art-legally/"><u>[Updated] Harnessing Free Clip Art Legally</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-discovering-digital-dominance-which-is-superior-youtubes-shorts-or-tiktoks/"><u>[New] Discovering Digital Dominance  Which Is Superior, YouTubes Shorts or TikToks?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-vibrant-soundscapes-10-melodies-that-elevate-your-video-montages/"><u>2024 Approved Vibrant Soundscapes 10 Melodies That Elevate Your Video Montages</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-perfect-recording-companion-10-best-on-spotify-platforms/"><u>In 2024, Perfect Recording Companion  10 Best on Spotify Platforms</u></a></li>
<li><a href="https://extra-hints.techidaily.com/create-edges-of-images-with-rotational-softness-blend-psx/"><u>Create Edges of Images with Rotational Softness Blend PSX</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/no-limit-story-saving-at-the-tap-of-a-button-for-2024/"><u>No-Limit Story Saving at the Tap of a Button for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-7-without-passcode-4-easy-methods-by-drfone-ios/"><u>How To Unlock iPhone 7 Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-a-step-by-step-approach-to-pinpointing-stellar-photos-on-pexels/"><u>[New] 2024 Approved  A Step-by-Step Approach to Pinpointing Stellar Photos on Pexels</u></a></li>
</ul></div>
