---
title: "Overcoming Application Launch Issues: Understanding & Correcting Error Code 0Xc000007b"
date: 2024-09-16T18:41:02.734Z
updated: 2024-09-20T19:15:15.905Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Application Launch Issues: Understanding & Correcting Error Code 0Xc000007b"
excerpt: "This Article Describes Overcoming Application Launch Issues: Understanding & Correcting Error Code 0Xc000007b"
thumbnail: https://thmb.techidaily.com/414457a7bef8541a22e0759e005db32e7bc53d10e956cf3519881385b0e0955c.jpg
---

## Resolve Error Code 8007000E on Windows Updates: Fast and Effective Solutions

![](https://images.drivereasy.com/wp-content/uploads/2019/10/Windows-Update-error-800700e.jpg)

 If you’re seeing an **error code 8007000e** when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of Windows system. The reason behind it is that some update files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below.

## Try these fixes

 You may not have to try them all. Just work your way down the list until you find the one that works.

1. **[Install the latest version of IE for Windows 7](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
3. **[Restart the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
4. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
5. **[Run System File Checker](https://tools.techidaily.com/drivereasy/download/)**
6. **[Download updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**
7. **[Want us to fix the problem for you?](https://tools.techidaily.com/drivereasy/download/)**

---

### Fix 1: Install the latest version of IE for Windows 7

 This fix is for the users who are using **Windows 7** operating system. If the current OS of your PC is not Windows 7, you can skip this fix.

 An outdated IE web browser and certain Hot fixes may trigger the **Windows Update error 8007000e** . Try updating your IE to the latest version and removing two hot fixes to see if this issue persists. Here is how to do it:

1. Click **[here](https://www.microsoft.com/en-us/download/Internet-Explorer-11-for-Windows-7-details.aspx)**  to visit Microsoft Download Center.
2. Click Download to download the latest version of IE 11.  
![download the latest version of IE 11](https://images.drivereasy.com/wp-content/uploads/2018/09/download-the-latest-version-of-IE-11.jpg)
3. Install the latest version of IE 11 on your PC.
4. On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Then Type **control** and press **Enter** to open the Control Panel.  
![step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/step-4.jpg)
5. In the search box in the upper-right corner, type **installed update** . Click **View installed updates** under **Programs and Features**  to view installed updates on your PC.  
![View installed updates](https://images.drivereasy.com/wp-content/uploads/2018/09/View-installed-updates.jpg)
6. Delete **Hotfix for Microsoft Windows (KB2534111)** and **Hotfix for Microsoft Windows (KB2639308)** .   **If you don’t find these two hot fixes, please skip this step.**  
![step 6](https://images.drivereasy.com/wp-content/uploads/2018/09/step-6.jpg)
7. Restart your PC.
8. Open IE and go through the welcome screen. Then close all the tabs to close IE.
9. Restart your PC.

 Go and check Windows Update again to see whether you can perform the Windows update or not. If you can perform a Windows update, then you’ve fix this issue.

### Fix 2: Run the Windows Update Troubleshooter

 You can download and run **the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update. Here is how to do it:

1. Click **[here](http://aka.ms/diag%5Fwu)** to download the Windows Update Troubleshooter.
2. **Double-click** the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click **Next** .  
![Windows Update](https://images.drivereasy.com/wp-content/uploads/2018/09/Windows-Update.jpg)  
**Note:** If your current operating system is **Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result. If your current operating system is **Windows 8** or **Windows 10** , you may need to follow the steps below.
3. If there is a more recent version of Windows Update troubleshooter available, click to run it.  
![Updated Troubleshooter Available](https://images.drivereasy.com/wp-content/uploads/2018/09/Updated-Troubleshooter-Available.jpg)
4. In the new version of Windows Update troubleshooter, click **Next** . The troubleshooter will check the available updates for your machine.  
![Fix 2 Step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-2-Step-4.jpg)
5. Click **Apply this fix**  to start the update process in the background immediately.  
![Fix 2 Step 5](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-2-Step-5.jpg)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try performing the Windows update again. If it still doesn’t work, please try the next fix.

### Fix 3: Restart the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog, then type **services.msc** and press **Enter** to open the Services window.  
![Fix 3 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-1.jpg)
2. Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
![Fix 3 step 2](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-2.jpg)
3. On your keyboard, press **the Windows Logo Key** and **E** at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.  

**C:\\Windows\\SoftwareDistribution\\DataStore**  

![Fix 3 step 3](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-3.jpg)
4. Delete all the files in the folder **DataStore** .
5. On your keyboard, press **the Windows Logo Key** and **E** at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter** on your keyboard to open the **Download**  folder.  

**C:\\Windows\\SoftwareDistribution\\Download**  

![Fix 3 step 5](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-5.jpg)
6. Delete all the files in the folder **Download** .

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. In the Services window, right-click **Windows Update**  and select **Start** .  
![Fix 3 step 7](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-7.jpg)

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next fix.

### Fix 4: Run the DISM tool

 This annoying issue is probably caused by the corrupted Windows update files. In this case, running   **the Deployment Image Servicing and Management (DISM) tool** may resolve this issue. Just follow the step-by-step instructions to run the DISM tool:

1. On your keyboard, press **the Windows Logo Key** and **R** at the same time to open the Run dialog. Type**cmd**  and then press **Ctrl** , **Shift** , and **Enter**  on your keyboard at the same time to **run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes** to run the **Command Prompt** .  
![Fix 4 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-4-step-1.jpg)
2. On your keyboard, type the command lines below one by one and press **Enter** .  

**Dism /Online /Cleanup-Image /ScanHealth**  
![DISM ScanHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-ScanHealth.jpg)  
**Note:** When you run the command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.  

**Dism /Online /Cleanup-Image /CheckHealth**  
![DISM CheckHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-CheckHealth.jpg)  
**Note:** When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.  

**Dism /Online /Cleanup-Image /RestoreHealth**  
![DISM RestoreHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-RestoreHealth.jpg)  
 Note: The command line **Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.
3. Close Command Prompt when the restore operation completed.  
![Fix 4 step 3](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-4-step-3.jpg)

 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

### Fix 5: Run System File Checker

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press **the Windows Logo Key** and then type **cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **OK** to run **Command Prompt** .  
![Fix 5 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-5-step-1.jpg)
2. On your keyboard, type the following command and press **Enter** .  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**sfc /scannow**  
![sfc sacannow](https://images.drivereasy.com/wp-content/uploads/2018/09/sfc-sacannow.jpg)
3. When this command operation is completed, close the Command Prompt.

 Run Windows Update again to check whether this fix works or not. If you still fail to install updates for your Windows system, please try the next fix.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 6: Download updates from Microsoft Update Catalog manually

 If all the fixes above don’t work for you, you can try downloading the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

 Before downloading Windows updates manually, you need to know the system type of your Windows OS. You can follow the steps below to view the system type information:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Enter** to open the Command Prompt.
2. Type the command line **systeminfo** and press **Enter** to view your system type.  
![view system type](https://images.drivereasy.com/wp-content/uploads/2018/09/view-system-type.jpg)

 “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

**To download and install Windows updates manually:**

1. On your keyboard, press **the Windows Logo Key** and type **Windows Update** , and then press **Enter** to open Windows Update.
2. Click **View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .
4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![Fix 6 step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-6-step-4.jpg)
5. In the list of search results, select right update for your operating system and click **Download** .  

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.
6. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-6-step-6.jpg)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

## This issue persists?

### Want us to fix the problem for you?

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.

![](https://images.drivereasy.com/wp-content/uploads/2022/04/Free-Tech-Support.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 All you need to do is **[buy a 1-year subscription to Driver Easy (just $29.95) and you get free technical support as part of your purchase](https://www.drivereasy.com/buy.php?comeid=de-buy-indirect)**  . Then you can contact our computer technicians directly, explain your problem, and they’ll investigate to see if they can resolve it remotely.

 Hopefully one of the fixes above can help you resolve this annoying issue. Please leave your comment below if you have any questions!

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-from-first-steps-to-proficiency-in-iphone-voice-memos-for-2024/"><u>[New] From First Steps to Proficiency in iPhone Voice Memos for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-vivo-y77t-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Vivo Y77t to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-bluetooth-hurdle-resolving-unsupported-miracast-devices/"><u>Beat the Bluetooth Hurdle: Resolving Unsupported Miracast Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-world-of-streaming-media-equipment/"><u>Exploring the World of Streaming Media Equipment</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-samsung-galaxy-m34-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-memes-access-to-premium-free-designs/"><u>Master Memes Access to Premium FREE Designs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-the-art-of-simplified-live-streaming/"><u>Mastering the Art of Simplified LIVE Streaming</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/no-more-glitches-working-obs-cameras-for-2024/"><u>No More Glitches Working OBS Cameras for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-system-error-correcting-msvcp140dll-absence/"><u>Resolving System Error: Correcting MSVCP140.dll Absence</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-tutorial-enjoying-high-quality-4k-hevc-content-on-mac-pro-macbook-air-and-macbook-pro-computers/"><u>Step-by-Step Tutorial: Enjoying High-Quality 4K HEVC Content on Mac Pro, Macbook Air & MacBook Pro Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-repairing-your-logitech-mouses-unresponsive-scroll-wheel/"><u>Troubleshooting Guide: Repairing Your Logitech Mouse's Unresponsive Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-the-puzzling-unknown-usb-device-descriptor-request-failed-message-on-your-pc/"><u>Troubleshooting Tips: Fixing the Puzzling 'Unknown USB Device - Descriptor Request Failed' Message on Your PC</u></a></li>
</ul></div>

