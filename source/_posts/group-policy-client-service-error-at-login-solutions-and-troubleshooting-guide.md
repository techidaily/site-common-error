---
title: Group Policy Client Service Error at Login - Solutions and Troubleshooting Guide
date: 2024-09-23T16:34:33.707Z
updated: 2024-09-26T16:23:19.087Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Group Policy Client Service Error at Login - Solutions and Troubleshooting Guide
excerpt: This Article Describes Group Policy Client Service Error at Login - Solutions and Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/d3cde457e9e8c995d522bb2c4aea0f1da4fb181b0b6f82bcc2191cc041c5e90c.jpg
---

## Unlocking Progress: How to Resolve Frozen Update States on Outdated OSs Like Win7 (Solutions and Troubleshooting Guide)

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap2-10.jpg)

**Get stuck** when you perform a Windows update on your**Windows 7** PC? Don’t Worry! You’re not alone. Many people are reporting this annoying issue. We’ve put together some fixes to help you resolve this issue. You should be able to fix this problem easily with one of the fixes in this article.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap4-9.jpg)
3. In the pop-up window, click **Advanced**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap5-8.jpg)
4. **Check** the box next to**Apply repairs automatically** and then click **Run as administrator**  .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap6-5.jpg)
5. Click**Next** .  Windows will detect and fix the problems automatically. The process may take a few minutes.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap7-6.jpg)

 When the process is done, see if the Windows 7 update stuck issue is resolved. If not, try the next fix.

### **Fix 2: Restart your Windows Update service**

**Try restarting the Windows Update service manually** to see if you can fix the Windows 7 update stuck issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap9-7.jpg)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap10-7.jpg)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.`C:\Windows\SoftwareDistribution\DataStore`  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap11-8.jpg)
4. Delete all the files in the folder **DataStore**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap12-6.jpg)
5. On your File Explorer, c opy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.`C:\Windows\SoftwareDistribution\Download`  
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
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap22-4.jpg)
3. In the pop-up window, click **Change adapter settings**  .  

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap23-6.jpg)
4. **Right-click**  your current network and then select **Properties**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap24-4.jpg)
5. Double-click **Internet Protocol Version 4(TCP/IPv4)**  to view its properties.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap25-6.jpg)
6. Select **Obtain an IP address automatically**  and   **Use the following DNS server addresses** .  
   * **For the Preferred DNS server** , enter the Google Public DNS address: **8.8.8.8** ;  
   * **For the Alternative DNS server** , enter the Google Public DNS address: **8.8.4.4**  . Then click **OK** to save the changes.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap26-2.jpg)
7. Restart your PC and try performing a Windows update.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111964/7443" target="_top" id="2111964">
  <img src="//a.impactradius-go.com/display-ad/7443-2111964" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111964/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 See if the Windows 7 update stuck issue reappears. If not, you’ve fixed this annoying issue.

### **Fix 4: Run System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you run into the Windows 7 update stuck issue, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and t ype **cmd.**  In the list of search results, right-click **cmd**  and select**Run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run the **Command Prompt**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap28-2.jpg)
2. On your keyboard, type the command lines below and press **Enter**  .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap29-1.jpg)  
 It may take several minutes for this command operation to be completed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Close the Command Prompt when this command operation completed.

 See if you can perform a Windows update or not. If not, you may need to download updates from **Microsoft Update Catalog**  manually to resolve this annoying problem.

### **Fix 5: Download updates from Microsoft Update Catalog manually**

 If this annoying issue persists, try downloading the updates you failed to install from [**Microsoft Update Catalog**](http://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Follow the instructions below to download updates from Microsoft Update Catalog manually:

1. **View your system type first:**  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap27-2.jpg)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap32-3.jpg)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

2. **View your update history:**  
   1. On your keyboard, press**the Windows logo key** and type **windows update** . In the list of search results, select**Windows Update** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap33-1.jpg)  
   2. On the left panel, click**View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap34-4.jpg)
3. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://common-error.techidaily.com/dll-diagnosis-resolve-kernel-fails/"><u>[DLL Diagnosis] Resolve Kernel Fails</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-dial-back-your-playlist-quick-steps-to-reverse-order/"><u>[Updated] Dial Back Your Playlist Quick Steps to Reverse Order</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-fifas-best-players-trendy-videos-on-youtube-for-2024/"><u>[Updated] FIFA's Best Players Trendy Videos on YouTube for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-enhance-your-medias-exposure-on-the-platform/"><u>[Updated] In 2024, Enhance Your Media's Exposure on the Platform</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleashing-originality-in-virtual-meme-worlds/"><u>2024 Approved Unleashing Originality in Virtual Meme Worlds</u></a></li>
<li><a href="https://common-error.techidaily.com/airpods-wont-pair-heres-how-to-get-your-earbuds-working-on-windows-11-updated-guide/"><u>AirPods Won't Pair? Here's How to Get Your Earbuds Working on Windows 11 (Updated Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x80072f8f-on-your-pc-easy-fixes-for-windows-11-and-10/"><u>Error 0X80072F8F on Your PC? Easy Fixes for Windows 11 and 10</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-network-functionality-for-ethernet-adapters-on-pc-windows-10-and-7/"><u>Guide to Restoring Network Functionality for Ethernet Adapters on PC (Windows 10 & 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-laptop-stubbornly-staying-on-the-boot-screen/"><u>How To Fix Your Laptop Stubbornly Staying on the Boot Screen</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-from-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock from Apple iPhone SE (2022)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1726225281307-mp4avimovavi/"><u>MP4到AVI轉換指南：用Movavi快速簡單版教學</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-frozen-chrome-window-easy-restart-methods/"><u>Troubleshooting a Frozen Chrome Window – Easy Restart Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-how-to-install-device-drivers-for-windows-7-successfully/"><u>Troubleshooting Step-by-Step: How to Install Device Drivers for Windows 7 Successfully</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/various-methods-to-transfer-pictures-from-apple-iphone-15-pro-to-pc-drfone-by-drfone-transfer-from-ios/"><u>Various Methods to Transfer Pictures from Apple iPhone 15 Pro to PC | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
</ul></div>

