---
title: "Unable To Access: Domain Service Not Available"
date: 2024-07-10T17:26:39.367Z
updated: 2024-07-11T17:26:39.367Z
tags:
  - win11
  - win10
  - win7
categories:
  - PrinterIssues
description: "This Article Describes Unable To Access: Domain Service Not Available"
excerpt: "This Article Describes Unable To Access: Domain Service Not Available"
keywords: Domain Downtime,Service Outage Domain,Website Unresponsive Domain,Domain Availability Check,Site Access Issue Domain,Service Availability Status Domain,Domain Service Interruption
thumbnail: https://thmb.techidaily.com/8c939daafbcd042f39c237e82182653fc156f3f064bef6cc6988deae36a1c0c9.jpg
---

## Unable To Access: Domain Service Not Available

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-29.jpg)
  
 Your printer stops working? Probably you’re seeing this error saying **The Active Directory Domain Services is currently unavailable** . Don’t panic. You’re not alone. Many printer users are reporting this error. More important, you can fix it easily by yourself with this guide.

 Here’re 2 methods you can try to fix this problem. Try the second method if the first one doesn’t work.

1. **[Change the Printer Spooler settings](#method1)**
2. **[Using Registry Editor](#method2)**

## Method 1: Change Printer Spooler settings

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.

2) Type **services.msc**  and press **Enter**  to open the **Services**  window:

![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a50a818f88a.png)

 3) Right-click on **Printer Spooler**  service and click **Start** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-31.jpg)
  
 4) After Printer Spooler gets started, double-click on it. Set its startup type to **Automatic** . Then click **OK**  to save the setting.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-33.jpg)
  
 5) Close the Services window and check if you could print files successfully.  

## Method 2: Using Registry Editor

1) On your keyboard, press the   **Windows logo key** ![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png) and **R**  at the same time to invoke the Run box.
  
2) Type **regedit**  and press **Enter** to open Registry Editor.  
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-23.jpg)**

 Click **Yes** when prompted by User Account Control,.
 3) On Registry window, go to **HKEY\_CURRENT\_USER** \> **Software**  \> **Microsoft**  \> **Windows NT**  \> **CurrentVersion** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-2.png)

 4) Right-click on **Devices**  under **CurrentVersion**  dialog.  
 Then click **Permissions** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-14.jpg)
  
 5) Click your account and tick on**Allow** of **Full Control** . Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-13.jpg)
  
 6) Do the same settings to give your account full control of **PrinterPorts**  and **Windows** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-12.jpg)
  
 7) Close the Registry Editor window and check to see if you could print files successfully.

* [printer](https://tools.techidaily.com/drivereasy/download/)

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



