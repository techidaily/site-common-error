---
title: Untangling the Windows 10 Update Mess - Error 0Xc1900208 Fixed Here
date: 2024-09-16T18:48:41.210Z
updated: 2024-09-20T16:34:41.201Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Untangling the Windows 10 Update Mess - Error 0Xc1900208 Fixed Here
excerpt: This Article Describes Untangling the Windows 10 Update Mess - Error 0Xc1900208 Fixed Here
thumbnail: https://thmb.techidaily.com/deaea135ad5d9b523c81b174542d97bf19684476eed26249d5d0957bb4c9f421.jpg
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

### **Fix 2: Restart the Windows Update service**

 You may see the error code 0xc1900208 if there is something wrong with the Windows Update service. Try restarting the Windows Update service to see if you can resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**   and **R**   at the same time to open the Run dialog, then type **services.msc** and press **Enter**   to open the Services window.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap396.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap397.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.**`C:\Windows\SoftwareDistribution\DataStore`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap398.png)  
 Please paste it in the address bar.
4. **Delete** all the files in the folder **DataStore** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap399.png)  
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.**`C:\Windows\SoftwareDistribution\Download`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap400.png)  
 Please paste it in the address bar.
6. **Delete** all the files in the folder   **Download** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap401.png)  
 When all the files are deleted, you shall see “This folder is empty”.
 Perform a Windows update again. If it still doesn’t work, try the next fix.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
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
3. Close Command Prompt when the restore operation completed.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap406.png)
 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 5: Downloading updates from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Here is how to do it:

1. On your keyboard, press   **the Windows Logo Key**  and type **Windows Update** . Then press **Enter**  to open**Windows Update**  window.
2. Click **View update history**   to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Before you download the update, follow the instructions below to view your system type:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap409.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap410.png)  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

    “**X64-based PC** ” indicates that your Windows OS is**64-bit** ; “**X86-based PC** ” means that your Windows OS is**32-bit** .
4. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)** .
5. Type the update number that you want to download. In this example, type KB  3006137 and then click **Search** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap411.png)
6. In the list of search results, select right update for your operating system and click **Download** .  
 If your**Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap412.png)
7. In the pop-up window, click the link to start downloading the updates.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap413.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. **Double-click** the downloaded file and follow the on-screen instructions to install the update.
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-optimizing-your-fb-video-ads-20-best-tips-for-success/"><u>[New] In 2024, Optimizing Your FB Video Ads 20 Best Tips for Success</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-quick-fix-valorant-thumbnails-professionally-done-now/"><u>[Updated] Quick-Fix Valorant Thumbnails Professionally Done Now</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-selective-software-optimal-blu-ray-players-free-to-pay/"><u>[Updated] Selective Software Optimal Blu-Ray Players (Free to Pay)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/decoding-facebooks-status-vids-download-process-explained/"><u>Decoding Facebook's Status Vids Download Process Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-non-responsive-volume-buttons-in-windows-10/"><u>Expert Tips for Fixing Non-Responsive Volume Buttons in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-corrupted-windows-store-caches-effective-strategies-and-solutions/"><u>Fix Corrupted Windows Store Caches: Effective Strategies and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204423354-fix-lol-pvpnet-patcher-kernel-has-stopped-working-easily/"><u>Fix LOL “PvP.net Patcher Kernel Has Stopped Working” Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-wwe-2k-battlegrounds-and-enable-dx11-feature-level-100-without-issues/"><u>How to Fix WWE 2K Battlegrounds and Enable DX11, Feature Level 10.0 without Issues</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-14-plus-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From iPhone 14 Plus?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-incompatible-timing-settings-on-your-computers-display/"><u>How to Resolve Incompatible Timing Settings on Your Computer's Display</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastery-in-minutes-repair-techniques-for-remote-server-not-reachable-error/"><u>Mastery in Minutes: Repair Techniques for 'Remote Server Not Reachable' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-security-by-tackling-pin-troubles-in-win10win11/"><u>Streamline Your PC Security by Tackling Pin Troubles in Win10/Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/transform-your-keyboards-performance-proven-strategies-to-effectively-refresh-and-restart/"><u>Transform Your Keyboard's Performance: Proven Strategies to Effectively Refresh and Restart!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlock-ultra-hd-excellence-optimize-your-samsung-4k-tv-settings/"><u>Unlock Ultra HD Excellence: Optimize Your Samsung 4K TV Settings</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/what-to-do-when-you-cant-remember-your-iphone-password-wipe-and-start-over-tips/"><u>What To Do When You Can’t Remember Your iPhone Password – Wipe & Start Over Tips</u></a></li>
</ul></div>
