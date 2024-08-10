---
title: The Role of msdia80.dll in Your System - Delete or Preserve?
date: 2024-08-09T00:49:15.581Z
updated: 2024-08-10T00:49:15.581Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes The Role of msdia80.dll in Your System - Delete or Preserve?
excerpt: This Article Describes The Role of msdia80.dll in Your System - Delete or Preserve?
thumbnail: https://thmb.techidaily.com/5bbb0b2b291780ca3cbfea599130f07779f3c6fbfd15f1bfb20995977850f864.jpg
---

## Error Code 0X800F081F on Your Mind? Solving the DotNet 3.5 Install Problems

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Method 1: Configure Group Policy

 The 0x800F081F error may occur because the component setting in Group Policy is disabled. You should enable it to see if this fixes the error. To do so:

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
**1)** On your keyboard, press the   **Windows logo key![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png)**  and**R** **key** at the same time to invoke the Run box.

**2)**  Type “**gpedit.msc** ” and press**Enter** on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b46182da0.png)

**3)**  Go to **Computer Configuration -> Administrative Templates -> System** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b4b628c80.jpg)

**4)** Double click **Specify settings for optional component installation and component repair** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cb90d9ace.jpg)

**5)** Select**Enabled** . Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cd1538e66.jpg)

**6)** Try installing .NET Framework 3.5\. If this method works for you, you won’t see the error again. Otherwise, you should try the method below.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

**5)**  Try installing .NET Framework 3.5 and see if the error disappears.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
