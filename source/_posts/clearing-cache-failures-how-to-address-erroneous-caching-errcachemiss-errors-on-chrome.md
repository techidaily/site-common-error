---
title: "Clearing Cache Failures: How to Address Erroneous Caching (ERR_CACHE_MISS) Errors on Chrome"
date: 2024-09-11T16:11:52.529Z
updated: 2024-09-15T16:02:55.789Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Clearing Cache Failures: How to Address Erroneous Caching (ERR_CACHE_MISS) Errors on Chrome"
excerpt: "This Article Describes Clearing Cache Failures: How to Address Erroneous Caching (ERR_CACHE_MISS) Errors on Chrome"
thumbnail: https://thmb.techidaily.com/589975317cd54578e2464cf37ff9c3436a24bffda2b797c9a9ae1ed0b5abaff9.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Change the DNS server settings**

 If your Windows 7 gets stuck when it is checking for updates, this may be a network issue. You can try changing the DNS server in your PC to  the**Google Public DNS addresses** .  Google Public DNS provides you with   **a speed boost**  and   **an increased security.**  Here is how to do it:

1. On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Then type **control** and press **Enter** to open the Control Panel.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap21-3.jpg)
2. **View**  the Control Panel **by Category** . Click **View network status and tasks**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap22-4.jpg)
3. In the pop-up window, click **Change adapter settings**  .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap23-6.jpg)
4. **Right-click**  your current network and then select **Properties**  .  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap24-4.jpg)
5. Double-click **Internet Protocol Version 4(TCP/IPv4)**  to view its properties.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap25-6.jpg)
6. Select **Obtain an IP address automatically**  and   **Use the following DNS server addresses** .  
   * **For the Preferred DNS server** , enter the Google Public DNS address: **8.8.8.8** ;  
   * **For the Alternative DNS server** , enter the Google Public DNS address: **8.8.4.4**  . Then click **OK** to save the changes.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap26-2.jpg)
7. Restart your PC and try performing a Windows update.

 See if the Windows 7 update stuck issue reappears. If not, you’ve fixed this annoying issue.

### **Fix 4: Run System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you run into the Windows 7 update stuck issue, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and t ype **cmd.**  In the list of search results, right-click **cmd**  and select**Run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run the **Command Prompt**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap28-2.jpg)
2. On your keyboard, type the command lines below and press **Enter**  .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap29-1.jpg)  
 It may take several minutes for this command operation to be completed.
3. Close the Command Prompt when this command operation completed.

 See if you can perform a Windows update or not. If not, you may need to download updates from **Microsoft Update Catalog**  manually to resolve this annoying problem.

### **Fix 5: Download updates from Microsoft Update Catalog manually**

 If this annoying issue persists, try downloading the updates you failed to install from [**Microsoft Update Catalog**](http://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Follow the instructions below to download updates from Microsoft Update Catalog manually:

1. **View your system type first:**  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap27-2.jpg)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115928/19272" target="_top" id="2115928">
  <img src="//a.impactradius-go.com/display-ad/19272-2115928" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap32-3.jpg)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
2. **View your update history:**  
   1. On your keyboard, press**the Windows logo key** and type **windows update** . In the list of search results, select**Windows Update** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap33-1.jpg)  
   2. On the left panel, click**View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap34-4.jpg)
3. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-become-a-facetime-pro-skype-call-basics-for-mobile-users/"><u>[New] 2024 Approved Become a Facetime Pro Skype Call Basics for Mobile Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-windows-photo-viewer-a-1111-edition-guide/"><u>Bring Back Windows Photo Viewer: A 11/11 Edition Guide</u></a></li>
<li><a href="https://discover-docs.techidaily.com/convert-mov-files-to-mp4-free-online-tool-compatible-with-mac-and-windows-11/"><u>Convert MOV Files to MP4 Free Online Tool - Compatible with Mac and Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212143161-experience-uninterrupted-updates-on-windows-11-solve-error-code-0x800f0922-using-our-top-fixes/"><u>Experience Uninterrupted Updates on Windows 11: Solve ERROR CODE 0X800F0922 Using Our Top Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Infinix Hot 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-concept-to-reality-selecting-top-3d-animators-software/"><u>In 2024, From Concept to Reality Selecting Top 3D Animators' Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a78-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A78 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-unlock-youtubes-power-for-free-educational-sessions/"><u>In 2024, Unlock YouTube's Power for FREE Educational Sessions</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-fixes-for-the-elusive-error-in-windows-installer-services/"><u>Mastering Fixes for the Elusive Error in Windows Installer Services</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-to-combat-high-resource-drain-caused-by-wudfhostexe-on-windows-10-systems/"><u>Tips to Combat High Resource Drain Caused by WUDFHost.exe on Windows 10 Systems</u></a></li>
</ul></div>
