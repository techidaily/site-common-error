---
title: "(Resolution) Unlocking PC Performance: Eliminating Shell-Induced High CPU Load on Modern OSes"
date: 2024-08-27T13:50:01.810Z
updated: 2024-08-28T13:50:01.810Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes (Resolution) Unlocking PC Performance: Eliminating Shell-Induced High CPU Load on Modern OSes"
excerpt: "This Article Describes (Resolution) Unlocking PC Performance: Eliminating Shell-Induced High CPU Load on Modern OSes"
thumbnail: https://thmb.techidaily.com/4c1fc861d688eb17793358701272fcb990bfc951646524d04a51586ab07132c7.jpg
---

## Unlocking Progress: How to Resolve Frozen Update States on Outdated OSs Like Win7 (Solutions and Troubleshooting Guide)

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap2-10.jpg)

**Get stuck** when you perform a Windows update on your**Windows 7** PC? Don’t Worry! You’re not alone. Many people are reporting this annoying issue. We’ve put together some fixes to help you resolve this issue. You should be able to fix this problem easily with one of the fixes in this article.

## **Fixes to try:**

 You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Run the Windows Update Troubleshooter**](#a)
2. [**Restart your Windows Update service**](#b)
3. [**Change the DNS server settings**](#c)
4. [**Run System File Checker**](#d)
5. [**Download updates from Microsoft Update Catalog manually**](#e)

---

### **Fix 1: Run the Windows Update Troubleshooter**

**Running the built-in Windows Update troubleshoote** r is the easiest fix you can try. Follow the steps below to run the Windows Update Troubleshooter:

1. On your keyboard, press**the Windows logo key** and type**troubleshooting**  in the search box. Then select **Troubleshooting**  in the list of search results.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap3-9.jpg)
2. In the **System and Security**  section, click**Fix problems with** **Windows Update**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap4-9.jpg)
3. In the pop-up window, click **Advanced**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap5-8.jpg)
4. **Check** the box next to**Apply repairs automatically** and then click **Run as administrator**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap6-5.jpg)
5. Click**Next** .  Windows will detect and fix the problems automatically. The process may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap7-6.jpg)

 When the process is done, see if the Windows 7 update stuck issue is resolved. If not, try the next fix.

### **Fix 2: Restart your Windows Update service**

**Try restarting the Windows Update service manually** to see if you can fix the Windows 7 update stuck issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap9-7.jpg)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap10-7.jpg)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.`C:\Windows\SoftwareDistribution\DataStore`  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap11-8.jpg)
4. Delete all the files in the folder **DataStore**  .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap12-6.jpg)
5. On your File Explorer, c opy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.`C:\Windows\SoftwareDistribution\Download`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap13-3.jpg)
6. Delete all the files in the folder   **Download**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap14-6.jpg)
7. In the Services window, right-click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap16-6.jpg)

 Go and check Windows Update again to see whether the issue persists or not. If the issue reappears, don’t worry, there are more fixes for you to try.

### **Fix 3: Change the DNS server settings**

 If your Windows 7 gets stuck when it is checking for updates, this may be a network issue. You can try changing the DNS server in your PC to  the**Google Public DNS addresses** .  Google Public DNS provides you with   **a speed boost**  and   **an increased security.**  Here is how to do it:

1. On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Then type **control** and press **Enter** to open the Control Panel.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap21-3.jpg)
2. **View**  the Control Panel **by Category** . Click **View network status and tasks**  .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap22-4.jpg)
3. In the pop-up window, click **Change adapter settings**  .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap23-6.jpg)
4. **Right-click**  your current network and then select **Properties**  .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap24-4.jpg)
5. Double-click **Internet Protocol Version 4(TCP/IPv4)**  to view its properties.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap25-6.jpg)
6. Select **Obtain an IP address automatically**  and   **Use the following DNS server addresses** .  
   * **For the Preferred DNS server** , enter the Google Public DNS address: **8.8.8.8** ;  
   * **For the Alternative DNS server** , enter the Google Public DNS address: **8.8.4.4**  . Then click **OK** to save the changes.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap26-2.jpg)
7. Restart your PC and try performing a Windows update.
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 See if the Windows 7 update stuck issue reappears. If not, you’ve fixed this annoying issue.

### **Fix 4: Run System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you run into the Windows 7 update stuck issue, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and t ype **cmd.**  In the list of search results, right-click **cmd**  and select**Run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run the **Command Prompt**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap28-2.jpg)
2. On your keyboard, type the command lines below and press **Enter**  .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap29-1.jpg)  
 It may take several minutes for this command operation to be completed.
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Close the Command Prompt when this command operation completed.

 See if you can perform a Windows update or not. If not, you may need to download updates from **Microsoft Update Catalog**  manually to resolve this annoying problem.

### **Fix 5: Download updates from Microsoft Update Catalog manually**

 If this annoying issue persists, try downloading the updates you failed to install from [**Microsoft Update Catalog**](http://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Follow the instructions below to download updates from Microsoft Update Catalog manually:

1. **View your system type first:**  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap27-2.jpg)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap32-3.jpg)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
2. **View your update history:**  
   1. On your keyboard, press**the Windows logo key** and type **windows update** . In the list of search results, select**Windows Update** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap33-1.jpg)  
   2. On the left panel, click**View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap34-4.jpg)
3. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type the update number (KBxxxxxxx) that you failed to install before and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap40-1.jpg)
5. In the list of search results, select right update for your operating system and click **Download**  .  
 If your Windows OS is **64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap37-1.jpg)
6. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap38-1.jpg)
7. Double-click the downloaded file and follow the on-screen instructions to install the updates.  
 After you install all the updates you failed to install before, perform a Windows update to see if this issue persists.
8. If the Window 7 update stuck issue persists, you need to download the updates**KB3020369** , **KB3172605** ,**KB3125574** and **KB3177467 from [Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  . Then install them one by one on your PC.

After installing these updates, this issue should be resolved.

 Hopefully, one of the fixes above can help you resolve this annoying issue. Please leave your comment below if you have any questions.

* [Windows 7](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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


