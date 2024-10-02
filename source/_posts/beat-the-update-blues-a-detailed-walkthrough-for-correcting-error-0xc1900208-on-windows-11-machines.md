---
title: "Beat the Update Blues: A Detailed Walkthrough for Correcting Error 0xC1900208 on Windows 11 Machines"
date: 2024-09-26T22:16:37.652Z
updated: 2024-10-01T20:27:39.729Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Beat the Update Blues: A Detailed Walkthrough for Correcting Error 0xC1900208 on Windows 11 Machines"
excerpt: "This Article Describes Beat the Update Blues: A Detailed Walkthrough for Correcting Error 0xC1900208 on Windows 11 Machines"
thumbnail: https://thmb.techidaily.com/37188c2ac0547dbb668f9ed584425f62c5411d081b5606c8c487c2ccf4f6d577.jpg
---

## Untangling the Windows 10 Update Mess - Error 0Xc1900208 Fixed Here

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap391.png)Seeing the error code**0xc1900208**when you’re performing a Windows update? Don’t worry… Although it’s incredibly frustrating, you’re definitely not the only one to experience this problem. Thousands of Windows 10 users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fixes to try**

 Here’s a list of fixes that have resolved this problem for other Windows 10 users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. [**Run Windows Update troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart the Windows Update service**](https://tools.techidaily.com/drivereasy/download/)
3. [**Run the DISM tool**](https://tools.techidaily.com/drivereasy/download/)
4. [**Running System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Downloading updates from Microsoft Update Catalog manually**](https://tools.techidaily.com/drivereasy/download/)
6. [**Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### **Fix 1: Run Windows Update troubleshooter**

This is the quickest and easiest fix to try when you’re seeing the error code **0xc1900208**. Windows Update troubleshooter is a built-in tool in Windows operating system that can automatically diagnose and resolve any issues regarding Windows Update. Follow the instructions below to run Windows Update troubleshooter:

1. On your keyboard, press**the Windows logo key** and type**troubleshoot** . In the list of search results, select **Troubleshoot** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap392-1.png)
2. In the pop-up window, select**Windows Update** and click**Run the troubleshooter** . You’ll be prompted for permission. Click**Yes** to run**Windows Update troubleshooter** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap393.png)
3. Click**Apply this fix** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap395.png)
 Windows Update troubleshooter will try to fix the issue for you. You can restart your PC and try to perform a Windows update again. If it still doesn’t work, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 2: Restart the Windows Update service**

 You may see the error code 0xc1900208 if there is something wrong with the Windows Update service. Try restarting the Windows Update service to see if you can resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**   and **R**   at the same time to open the Run dialog, then type **services.msc** and press **Enter**   to open the Services window.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap396.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap397.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.**`C:\Windows\SoftwareDistribution\DataStore`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap398.png)  
 Please paste it in the address bar.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Delete** all the files in the folder **DataStore** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap399.png)  
 When all the files are deleted, you shall see “This folder is empty”.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.**`C:\Windows\SoftwareDistribution\Download`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap400.png)  
 Please paste it in the address bar.
6. **Delete** all the files in the folder   **Download** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap401.png)  
 When all the files are deleted, you shall see “This folder is empty”.
 Perform a Windows update again. If it still doesn’t work, try the next fix.

<!-- affiliate ads begin -->
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Run the DISM tool**

 The error code 0xc1900208 can also be triggered by the corrupted Windows update files. In this case, running **the Deployment Image Servicing and Management (DISM) tool**  may resolve this issue. Just follow the step-by-step instructions below to run the DISM tool:

1. On your keyboard, press **the Windows Logo Key**  and **R**  at the same time to open the Run dialog. Type **cmd** and then press **Ctrl** , **Shift** , and **Enter** on your keyboard   at the same time to **run Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run **Command Prompt**  .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap402.png)
2. On your keyboard, type the command lines below one by one and press **Enter** .  
   1. **Dism /Online /Cleanup-Image /ScanHealth**  
    When you run command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap403.png)  
    It may take several minutes for this command operation to be completed.  
   2. **Dism /Online /Cleanup-Image /CheckHealth**  
    When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap404.png)  
    It may take several minutes for this command operation to be completed.  
   3. **Dism /Online /Cleanup-Image /RestoreHealth**  
    The command line**Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap405.png)  
    It may take several minutes for this command operation to be completed.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Close Command Prompt when the restore operation completed.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap406.png)
 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 4: Running System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you see the error code 0xc1900208, it may be caused by some corruption error. Running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and then type **cmd**  in the search box. When you see **Command Prompt**  in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **OK**  to run **Command Prompt**  .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap407.png)
2. On your keyboard, type the following command and press **Enter** .  
**sfc /scannow**  
 It may take some time for the command operation to be completed.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap408.png)
3. When this command operation is completed, close **Command Prompt** .
Run Windows Update  again to check whether this fix works or not. If you still fail to install updates for your Windows system, don’t worry. Try the next fix.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 5: Downloading updates from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Here is how to do it:

1. On your keyboard, press   **the Windows Logo Key**  and type **Windows Update** . Then press **Enter**  to open**Windows Update**  window.
2. Click **View update history**   to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Before you download the update, follow the instructions below to view your system type:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap409.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap410.png)  
    “**X64-based PC** ” indicates that your Windows OS is**64-bit** ; “**X86-based PC** ” means that your Windows OS is**32-bit** .
4. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)** .
5. Type the update number that you want to download. In this example, type KB  3006137 and then click **Search** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap411.png)
6. In the list of search results, select right update for your operating system and click **Download** .  
 If your**Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap412.png)
7. In the pop-up window, click the link to start downloading the updates.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap413.png)
8. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

See if the error code 0xc1900208 reappears. If this error persists, try the next fix.

### **Pro tip: Want us to fix the problem for you?**

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.  All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:** Please attach**the URL of this article** when you contact us, so we could help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the**Driver Easy Feedback tool** . To learn how to use this tool, please visit this link: [https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-gigabyte-totals-for-extended-video-playback/"><u>[New] Gigabyte Totals for Extended Video Playback</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-huawei-p10-analysis-unveiling-performance-and-design-for-2024/"><u>[Updated] Huawei P10 Analysis Unveiling Performance & Design for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-how-to-record-your-screen-on-windows-8/"><u>[Updated] In 2024, How To Record Your Screen On Windows 8</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-lightning-fast-lore-resurrecting-reddit-articles-lost/"><u>[Updated] Lightning-Fast Lore Resurrecting Reddit Articles Lost</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208069021-enhance-windows-7-launch-speed-top-solutions-to-combat-delays/"><u>Enhance Windows 7 Launch Speed: Top Solutions to Combat Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-malfunctioning-microphone-on-your-laptop-step-by-step-guide/"><u>Fixing a Malfunctioning Microphone on Your Laptop - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-overcoming-errors-when-steams-vac-cant-validate-your-match/"><u>Guide: Overcoming Errors when Steam's VAC Can’t Validate Your Match</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-xiaomi-14-pro-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Xiaomi 14 Pro to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-laptop-running-again-fast-charging-solutions/"><u>How to Get Your Laptop Running Again: Fast Charging Solutions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-real-time-recorder-battle-go-obs-vs-shadowplay/"><u>In 2024, Real-Time Recorder Battle Go OBS! Vs. ShadowPlay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Motorola Moto G Stylus (2023)? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-resolution-eliminate-code-0x800f0831-with-ease-using-windows-update-features/"><u>Mastering Error Resolution: Eliminate Code 0X800^F0831 with Ease Using Windows Update Features</u></a></li>
<li><a href="https://win-blog.techidaily.com/msi-afterburner-and-windows-compatibility-solving-gpu-non-detection-problems-in-w10w11/"><u>MSI Afterburner and Windows Compatibility: Solving GPU Non-Detection Problems in W10/W11</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-intermittent-sounds-in-your-logitech-g930-wireless-earphones/"><u>Solution for Intermittent Sounds in Your Logitech G930 Wireless Earphones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-itel-s23-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Itel S23 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-issues-when-opening-geforce-experience/"><u>Troubleshooting Guide: Resolving Issues When Opening GeForce Experience</u></a></li>
</ul></div>

