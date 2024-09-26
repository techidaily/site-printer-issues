---
title: How to Uninstall a Print Driver in Windows
date: 2024-08-31T04:34:27.487Z
updated: 2024-09-01T04:34:27.487Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: This Article Describes How to Uninstall a Print Driver in Windows
excerpt: This Article Describes How to Uninstall a Print Driver in Windows
keywords: Uninstalling Print Driver,Windows Print Driver Removal,How to Delete Windows Print Driver,Print Driver Uninstall Guide,Windows Printer Driver Removal Steps,Remove Printer Software From Windows,Troubleshooting Deleted Print Drivers in Windows
thumbnail: https://thmb.techidaily.com/519c0ecb3a4e958d4703170c89bc9f0f4e206bb0aa2219c94653cd1097dc9a0c.jpg
---

## How to Uninstall a Print Driver in Windows

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->