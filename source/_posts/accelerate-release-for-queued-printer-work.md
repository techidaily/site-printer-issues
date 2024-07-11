---
title: Accelerate Release for Queued Printer Work
date: 2024-07-10T17:15:32.760Z
updated: 2024-07-11T17:15:32.760Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Accelerate Release for Queued Printer Work
excerpt: This Article Describes Accelerate Release for Queued Printer Work
keywords: Accelerated Print Release,Queued Printer Workflow Optimization,Reduce Printer Job Queue Time,Improve Printer Efficiency,Fast-Tracking Printer Operations,Enhanced Printer Process Speedup,Streamline Printer Tasks and Release
thumbnail: https://thmb.techidaily.com/95e300018e980291f8509be45c3e360fa38c440741dbce7d87b862e7e88474bb.jpg
---

## Accelerate Release for Queued Printer Work

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
<li><a href="https://printer-issues.techidaily.com/reviving-a-silent-canon-printer/"><u>Reviving a Silent Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/syncing-devices-to-share-printer-settings/"><u>Syncing Devices to Share Printer Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-code-0x97-the-epson-fix/"><u>Error Code 0X97: The Epson Fix</u></a></li>
<li><a href="https://printer-issues.techidaily.com/the-end-of-the-road-for-printer-errors-with-windows-update/"><u>The End of the Road for Printer Errors with Windows Update</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overhauling-epsons-error-0x97/"><u>Overhauling Epson's Error 0X97</u></a></li>
<li><a href="https://printer-issues.techidaily.com/oddity-in-output-multiple-users-on-one-printer/"><u>Oddity in Output: Multiple Users on One Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-bring-your-windows-xps-hp-online/"><u>How to Bring Your Windows XP's HP Online</u></a></li>
<li><a href="https://printer-issues.techidaily.com/breaking-the-spell-of-paper-misfeeding/"><u>Breaking the Spell of Paper Misfeeding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-every-single-printer-page-solution/"><u>Print Every Single Printer Page [Solution]</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-resolution-achieved/"><u>Code B200 Resolution Achieved</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-tip-uninstalling-default-print-devices/"><u>Quick Tip: Uninstalling Default Print Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-hp-printing-blockade-oxc4eb827f/"><u>Overcoming HP Printing Blockade: OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshoot-windows-11-printing-glitches/"><u>Troubleshoot Windows 11 Printing Glitches</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcome-canon-printer-puzzles-in-windows-11-here-are-five-easy-solutions/"><u>Overcome Canon Printer Puzzles in Windows 11 - Here Are Five Easy Solutions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/turn-around-canons-no-prints-with-these-5-effective-fixes-for-windows-11/"><u>Turn Around Canon's No-Prints with These 5 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printers-no-more-missing-pages-heres-why/"><u>Printers: No More Missing Pages, Here's Why</u></a></li>
<li><a href="https://printer-issues.techidaily.com/network-printer-vanishes-whats-the-remedy/"><u>Network Printer Vanishes, What's the Remedy?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/1719574178084-printer-woes-in-windows-11-help-needed/"><u>Printer Woes in Windows 11 - Help Needed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/efficiently-setting-up-and-connecting-your-canon-printer/"><u>Efficiently Setting Up and Connecting Your Canon Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mend-w11-printer-communication-errors/"><u>Mend W11 Printer Communication Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/manual-setting-up-hp-officejet-on-desktop-system/"><u>Manual: Setting up HP Officejet on Desktop System</u></a></li>
<li><a href="https://printer-issues.techidaily.com/warning-spooler-error-affects-print-output/"><u>[WARNING] Spooler Error Affects Print Output</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-erratic-printer-spooler-behavior-win-11-and-older/"><u>Fixing Erratic Printer Spooler Behavior (Win 11 & Older)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-needed-drivers-not-installing-hp-deskjet-d1360-on-windows/"><u>[Update Needed] Drivers Not Installing: HP Deskjet D1360 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-inkjet-printer-installation-guide/"><u>HP Inkjet Printer Installation Guide</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-fix-hp-printer-not-responding/"><u>How to Fix HP Printer Not Responding</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-no-response-from-networked-printer/"><u>Resolving No Response From Networked Printer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/purging-hp-printer-error-code-oxc4eb827f/"><u>Purging HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://printer-issues.techidaily.com/error-elimination-windows-printer-setback-0x00000709/"><u>Error Elimination: Windows Printer Setback (0X00000709)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-integrating-printer-model-8720-in-pc/"><u>How-To: Integrating Printer Model 8720 in PC</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-laser-print-quality-concerns/"><u>Resolving Laser Print Quality Concerns</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win711-hp-printer-network-recovery-tips/"><u>Win7/11 HP Printer Network Recovery Tips</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-laser-print-glitches/"><u>Clearing Up Laser Print Glitches</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-lip-sync-videos-are-a-great-source-of-fun-and-producing-them-doesnt-require-you-to-have-a-professional-video-or-sound-equipment-in-thi/"><u>Updated 2024 Approved Lip Sync Videos Are a Great Source of Fun, and Producing Them Doesnt Require You to Have a Professional Video or Sound Equipment. In This Article, We Are Going to Introduce You to some of the Best Li</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-complete-process-to-reinvent-your-tiktok-look/"><u>[Updated] In 2024, The Complete Process to Reinvent Your TikTok Look</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-best-of-the-best-9-free-video-compression-tools-for-windows-10/"><u>Updated In 2024, Best of the Best 9 Free Video Compression Tools for Windows 10</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-commanding-attention-techniques-for-higher-pitched-voice-in-digital-storytelling/"><u>Updated Commanding Attention Techniques for Higher Pitched Voice in Digital Storytelling</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-joining-the-dots-obs-and-zoom-pairing-explained/"><u>[New] In 2024, Joining the Dots  OBS & Zoom Pairing Explained</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-gionee-f3-pro-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Gionee F3 Pro FRP Locks</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-fixing-overencoded-obs-videos-for-2024/"><u>[Updated] Fixing Overencoded OBS Videos for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-essential-steps-for-crafting-stunning-slow-motion-content-on-tiktok-for-2024/"><u>[New] Essential Steps for Crafting Stunning Slow Motion Content on TikTok for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Realme C53? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/can-you-unlock-apple-iphone-x-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>Can You Unlock Apple iPhone X After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-full-motion-assessment-2023/"><u>In 2024, Full Motion Assessment 2023</u></a></li>
<li><a href="https://driver-install.techidaily.com/speed-up-your-system-secure-scsi-drivers-direct-download/"><u>Speed Up Your System: Secure SCSI Drivers Direct Download</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-path-from-twitter-video-to-fb-sharing/"><u>In 2024, The Path From Twitter Video to FB Sharing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-oppo-a79-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Oppo A79 5G Location | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/remedy-for-nvidiaintel-graphic-switch-failure/"><u>Remedy for NVIDIA/Intel Graphic Switch Failure</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-issue-partial-window-view-on-windows-10-monitor-display/"><u>Fixed Issue: Partial Window View on Windows 10 Monitor Display</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-vivo-y100-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Vivo Y100 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/strategies-for-effective-content-promotion-on-youtube-for-2024/"><u>Strategies for Effective Content Promotion on YouTube for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/5-excellent-video-conference-devices-for-professionals/"><u>5 Excellent Video Conference Devices for Professionals</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-humor-pay-nothing-easymeme-tools-guide-for-2024/"><u>Unlock Humor, Pay Nothing  EasyMeme Tools Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-deal-with-youtube-trolls-and-negative-comments-for-2024/"><u>[New] How To Deal with YouTube Trolls and Negative Comments for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-samsung-galaxy-s24-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Samsung Galaxy S24 Phone Pattern Lock</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-top-15-discord-emotes-and-emotes-makers-that-crushed/"><u>[Updated] Top 15 Discord Emotes and Emotes Makers that Crushed</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>How to Change Location On Facebook Dating for your Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-journey-to-greatness-top-10-travel-youtubers/"><u>2024 Approved  Journey to Greatness  Top 10 Travel Youtubers</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/enriched-visuals-and-melodies-the-art-of-integrating-filters-and-music-windows-photos/"><u>Enriched Visuals & Melodies  The Art of Integrating Filters & Music (Windows Photos)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gopros-greatest-hits-max-360-vs-hero-11-comparison-for-2024/"><u>GoPro's Greatest Hits  Max 360 vs Hero 11 Comparison for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/elevate-your-live-recordings-on-facebook-with-4-methods/"><u>Elevate Your Live Recordings on Facebook with 4 Methods</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-is-your-iphone-x-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>In 2024, Is Your iPhone X in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://extra-resources.techidaily.com/time-travel-tech-how-to-reverse-ios-video/"><u>Time Travel Tech  How to Reverse iOS Video</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-finding-your-voice-on-youtube-a-guide-to-selective-audiences/"><u>[New] Finding Your Voice on YouTube  A Guide to Selective Audiences</u></a></li>
</ul></div>
