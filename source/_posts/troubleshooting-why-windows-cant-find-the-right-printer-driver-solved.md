---
title: "Troubleshooting: Why Windows Can't Find the Right Printer Driver (SOLVED)"
date: 2024-08-15T11:10:51.150Z
updated: 2024-08-16T11:10:51.150Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Why Windows Can't Find the Right Printer Driver (SOLVED)"
excerpt: "This Article Describes Troubleshooting: Why Windows Can't Find the Right Printer Driver (SOLVED)"
thumbnail: https://thmb.techidaily.com/275ca9774c095e0be2ae30797f9894bae65deae9ea5691cd95cdc33842a228b1.jpg
---

## Troubleshooting the KB4056892 Error for Smooth Windows 10 Updates - Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap787-300x95.png)

**Failed to install KB4056892** when you perform Windows Update on your Windows 10 PC? Don’t worry…  Although it’s incredibly frustrating, you’re definitely not the only person to experience this problem. Thousands of Windows 10 users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

## **Try these fixes**

1. [**Running Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restarting Windows Update service**](https://tools.techidaily.com/drivereasy/download/)
3. [**Setting the trustedInstaller service to auto start**](https://tools.techidaily.com/drivereasy/download/)
4. [**Running System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Downloading update KB4056892 from Microsoft Update Catalog manually**](https://tools.techidaily.com/drivereasy/download/)
6. [**Pro tip: Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### **Fix 1: Running Windows Update Troubleshooter**

 Windows Update troubleshooter is a built-in tool that can help you analyze and resolve issues related to Windows update. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows logo key**  and type **troubleshoot** . In the list of search results, select **Troubleshoot**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap788.png)
2. In the pop-up window, select **Windows Update**   and click **Run the troubleshooter** . You’ll be prompted for permission. Click **Yes**   to run Windows Update troubleshooter.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap789.png)
3. Click **Apply this fix**   to continue.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap790.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
4. Follow the on-screen instructions to troubleshoot this issue.

 Perform a Windows update again to see if you can install the update. If not, try the next fix, below.

### **Fix 2: Restarting Windows Update service**

 You may run into this issue if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap791.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap792.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.  

**`C:\Windows\SoftwareDistribution\DataStore`**  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap794.png)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
4. Delete all the files in the folder **DataStore**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap795.png)  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  

**`C:\Windows\SoftwareDistribution\Download**  
**`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap796.png)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
6. Delete all the files in the folder   **Download**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap797.png)  
 When all the files are deleted, you shall see “This folder is empty”.
7. In the Services window, right-click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap798.png)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check Windows Update again to see whether you can install the update. If not, try the next fix, below.

### **Fix 3: Setting the TrustedInstaller service to auto start**

 This issue may occur if you didn’t set the trustedInstaller service to auto start. So try setting the TrustedInstaller service to auto start before you install the update KB4056892\. Here is how to do it:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the command line below and press enter:  
**SC config trustedinstaller start=auto**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap800.png)
3. Close Command Prompt and restart your PC.

 Perform Windows Update again after your restart your PC. See if you can install the update KB4056892\. If you can install it, congratulations! You’ve fixed this issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 4: Running System File Checker**

**System File Checker**  can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
2. In Command Prompt, type the following command and press **Enter**  .  
**sfc /scannow**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap801.png)  
 It may take some time for the command operation to be completed.
3. When this command operation is completed, close Command Prompt.

Run Windows Update  again to check whether this fix works or not. If you still fail to install the update KB4056892 for your Windows system, try downloading it from Microsoft Update Catalog manually.

### **Fix 5: Downloading the update KB4056892 from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  and install them manually. Here is how to do it:

1. Follow the instructions below to**view your system type** before you download the update KB4056892 from Microsoft Update Catalog manually:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap802.png)  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
2. Visit[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx) .
3. Type**KB4056892**  and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap803.png)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the list of search results, select right update for your operating system and click **Download**  .  
 If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap806.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
5. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap807.png)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
6. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

See if you can install the update. If not, try the next fix, below.

### **Pro tip: Want us to fix the problem for you?**

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.

 All you need to do is[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/) (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:**  Please attach **the URL of this article** when you contact us, so we could help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the **Driver Easy Feedback tool** . To learn how to use this tool, please visit this link: [https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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


