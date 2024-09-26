---
title: Streamlining Print Devices From Win 10/11
date: 2024-09-04T06:12:55.196Z
updated: 2024-09-05T06:12:55.196Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes Streamlining Print Devices From Win 10/11
excerpt: This Article Describes Streamlining Print Devices From Win 10/11
keywords: Streamline Printing with Windows 10/11,Optimize Print Devices for Windows 10/11,Simplify Printing on Windows 10/11,Enhance Print Performance on Windows 10/11,Improve Efficiency of Printers Running on Windows 10/11,Automate Print Tasks for Windows 10/11 Users,Integrating Print Solutions with Windows 10/11
thumbnail: https://thmb.techidaily.com/59ebf54bbd2728b1cee67f80e126289c9f6737977aace37b8f0906719738cd6b.jpg
---

## Streamlining Print Devices From Win 10/11

You just purchased a new printer and would like to replace the old one at home. You think you have removed the printer and its driver, but when you reboot your computer, you can still see the printer’s icon, the only difference is that the icon all grayed out. In this case, it becomes impossible for you to uninstall or remove it again.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-grey-out.png)

Luckily, this is an easy problem to solve. Follow the steps below to fix the problem by yourself. 1) Click the**Start**button and type**cmd.exe** in the search box. Then right-click **c** **md** and click**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-ad-administrator.jpg) 2) Type in the command**print /s /t2**and hit**Enter**key on your keyboard. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/printui-s-t2.png) 3) Then you will be lead to this page. Try remove your printer driver now by selecting it and click the**Remove**button. Please remember to press**OK**to save the change. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-printer.jpg) 4) Then go to**Devices and Printers**panel by following this path: **Control Panel> Hardware and Sound> Devices and Printers**. Locate the printer that you would like to remove and right click it to choose**Remove device**.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-device.jpg)

5) If the above steps don’t work, press the   **Windows key ![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-key.png)** and**R**at the same time to invoke a Run command. Type**services.msc** and press **Enter**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/services-msc-in-run.png) 6) Locate**PrinterSpooler**service. Right-click it and select **Properties**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/printerspooler-service.jpg) 7) Then select **Stop**service. Click**OK**to exit. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/stop-printer-service.png) 8) Follow the path **My Computer\\C:\\Windows\\System32\\spool\\Printers**.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-folder-600x281.jpg)

If prompted for permission to go to this folder, click**Continue**or**Yes**to continue the procedure.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b4334888efa.png)

9) Press**Ctrl + A**to select all the information in this folder and right click to click **Delete**. 10) Go to**Services**panel again to restart the**PrinterSpooler**service.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/printer-service-restart.jpg)

Click**Start**. Then click**OK**to exit.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/restart-services-printer.png)

You might want to reboot your computer at this point. 11) Repeat step 1) to step 4). This time it should work. 12) If necessary, please go to**Ports**tab and see if you need to remove any TCP/IP ports that are associated with the old printer.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/remove-port.jpg)

That’s all you need to do!

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







<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->