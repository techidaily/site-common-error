---
title: "Resolving the Windows Update Issue: Fixing Error Code 0X802e401c on Win10/Win11"
date: 2025-01-11T16:02:40.038Z
updated: 2025-01-16T16:19:01.985Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the Windows Update Issue: Fixing Error Code 0X802e401c on Win10/Win11"
excerpt: "This Article Describes Resolving the Windows Update Issue: Fixing Error Code 0X802e401c on Win10/Win11"
thumbnail: https://thmb.techidaily.com/06d94324402f19737805b6dd681a3b55315b5b4572a08bdb43f1ad90737fa0c7.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Click**Apply this fix** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap395.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows Update troubleshooter will try to fix the issue for you. You can restart your PC and try to perform a Windows update again. If it still doesn’t work, try the next fix, below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Close Command Prompt when the restore operation completed.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap406.png)
 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

### **Fix 4: Running System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you see the error code 0xc1900208, it may be caused by some corruption error. Running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and then type **cmd**  in the search box. When you see **Command Prompt**  in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **OK**  to run **Command Prompt**  .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap407.png)
2. On your keyboard, type the following command and press **Enter** .  

**sfc /scannow**  
 It may take some time for the command operation to be completed.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap408.png)
3. When this command operation is completed, close **Command Prompt** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Run Windows Update  again to check whether this fix works or not. If you still fail to install updates for your Windows system, don’t worry. Try the next fix.

### **Fix 5: Downloading updates from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Here is how to do it:

1. On your keyboard, press   **the Windows Logo Key**  and type **Windows Update** . Then press **Enter**  to open**Windows Update**  window.
2. Click **View update history**   to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Before you download the update, follow the instructions below to view your system type:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap409.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap410.png)  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

    “**X64-based PC** ” indicates that your Windows OS is**64-bit** ; “**X86-based PC** ” means that your Windows OS is**32-bit** .
4. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)** .
5. Type the update number that you want to download. In this example, type KB  3006137 and then click **Search** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap411.png)
6. In the list of search results, select right update for your operating system and click **Download** .  

 If your**Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap412.png)
7. In the pop-up window, click the link to start downloading the updates.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap413.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-how-to-find-youtube-partners-and-make-collab-videos/"><u>[New] How to Find YouTube Partners and Make Collab Videos?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-mastering-instagrams-latest-trends-reels-and-stories/"><u>2024 Approved Mastering Instagram's Latest Trends Reels and Stories</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/becoming-a-video-wizard-with-screencast-insider-tips/"><u>Becoming a Video Wizard with Screencast Insider Tips</u></a></li>
<li><a href="https://win-great.techidaily.com/capturing-live-webcam-footage-directly-in-windows-screen-recordings-tutorial/"><u>Capturing Live Webcam Footage Directly in Windows Screen Recordings Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/constraint-a-the-footnotes-must-be-numbered-sequentially-starting-with-1/"><u>Constraint A: The Footnotes Must Be Numbered Sequentially Starting with [^1]</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-asus-webcam-black-screen-windows-10-issue/"><u>Fix ASUS Webcam Black Screen Windows 10 Issue</u></a></li>
<li><a href="https://facebook.techidaily.com/friendship-reborn-or-reimagined-through-facebook/"><u>Friendship Reborn or Reimagined Through Facebook?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-modern-ar-laptops-without-displays-are-outshining-their-predecessors-in-both-features-and-price-zdnet-insights/"><u>How Modern AR Laptops Without Displays Are Outshining Their Predecessors in Both Features and Price | ZDNET Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-through-installation-issues-how-to-tackle-error-code-0x800f081f-with-net-framework-35/"><u>Navigating Through Installation Issues: How to Tackle Error Code 0X800F081F with .NET Framework 3.5</u></a></li>
<li><a href="https://common-error.techidaily.com/say-goodbye-to-frustrating-response-rates-correcting-your-windows-11-keyboards-sluggishness/"><u>Say Goodbye to Frustrating Response Rates: Correcting Your Windows 11 Keyboard's Sluggishness</u></a></li>
<li><a href="https://win-dash.techidaily.com/sddvd/"><u>SDカードにDVDコンテンツを変換して表示する方法 - ナビゲーション、タブレット利用ガイド</u></a></li>
<li><a href="https://discover-community.techidaily.com/step-by-step-guide-converting-various-audio-and-video-file-types-effortlessly/"><u>Step-by-Step Guide: Converting Various Audio and Video File Types Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-critical-failure-during-program-installation-error-1603/"><u>Step-by-Step Solution to Overcome Critical Failure During Program Installation (Error 1603)</u></a></li>
</ul></div>

