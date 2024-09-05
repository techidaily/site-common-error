---
title: Solutions for Handling Sudden Shutdowns While Gaming on Multiple Versions of Windows Operating Systems
date: 2024-09-04T20:33:22.402Z
updated: 2024-09-05T20:33:22.402Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Handling Sudden Shutdowns While Gaming on Multiple Versions of Windows Operating Systems
excerpt: This Article Describes Solutions for Handling Sudden Shutdowns While Gaming on Multiple Versions of Windows Operating Systems
thumbnail: https://thmb.techidaily.com/14a25359b86e19d1002308583500dde5e5cec05558fa18656a09087a1aaee21b.jpg
---

## Overcoming Problems with Windows 10 Version 1903 Update (KB4056892) – Solutions Inside

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
4. Follow the on-screen instructions to troubleshoot this issue.

 Perform a Windows update again to see if you can install the update. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Restarting Windows Update service**

 You may run into this issue if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap791.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap792.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**`C:\Windows\SoftwareDistribution\DataStore`**  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap794.png)
4. Delete all the files in the folder **DataStore**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap795.png)  
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  

**`C:\Windows\SoftwareDistribution\Download**  
**`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap796.png)
6. Delete all the files in the folder   **Download**  .  
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap797.png)  
 When all the files are deleted, you shall see “This folder is empty”.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. In the Services window, right-click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap798.png)

 Check Windows Update again to see whether you can install the update. If not, try the next fix, below.

### **Fix 3: Setting the TrustedInstaller service to auto start**

 This issue may occur if you didn’t set the trustedInstaller service to auto start. So try setting the TrustedInstaller service to auto start before you install the update KB4056892\. Here is how to do it:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the command line below and press enter:  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**SC config trustedinstaller start=auto**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap800.png)
3. Close Command Prompt and restart your PC.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2031472/7443" target="_top" id="2031472">
  <img src="//a.impactradius-go.com/display-ad/7443-2031472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2031472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Perform Windows Update again after your restart your PC. See if you can install the update KB4056892\. If you can install it, congratulations! You’ve fixed this issue.

### **Fix 4: Running System File Checker**

**System File Checker**  can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the following command and press **Enter**  .  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**sfc /scannow**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap801.png)  
 It may take some time for the command operation to be completed.
3. When this command operation is completed, close Command Prompt.

Run Windows Update  again to check whether this fix works or not. If you still fail to install the update KB4056892 for your Windows system, try downloading it from Microsoft Update Catalog manually.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 5: Downloading the update KB4056892 from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  and install them manually. Here is how to do it:

1. Follow the instructions below to**view your system type** before you download the update KB4056892 from Microsoft Update Catalog manually:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap802.png)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
2. Visit[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx) .
3. Type**KB4056892**  and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap803.png)
4. In the list of search results, select right update for your operating system and click **Download**  .  
 If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap806.png)
5. In the pop-up window, click the link to start downloading the updates.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap807.png)
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-ideal-mic-matches-for-dynamic-camera-use/"><u>[New] 2024 Approved  Ideal Mic Matches for Dynamic Camera Use</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-best-10-digital-landscape-replacers-for-videos/"><u>[New] In 2024, Best 10 Digital Landscape Replacers for Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-crafting-your-gaming-channel-on-youtube/"><u>[New] In 2024, Crafting Your Gaming Channel on YouTube</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-wireless-mouse-randomly-stops-working-on-windows-1110/"><u>[Solved] Wireless Mouse Randomly Stops Working on Windows 11/10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-chasing-charm-innovative-photo-techniques-to-ignite-insta-for-2024/"><u>[Updated] Chasing Charm  Innovative Photo Techniques to Ignite Insta for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-cinematic-edge-master-the-top-5-camera-skills/"><u>[Updated] The Cinematic Edge  Master the Top 5 Camera Skills</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-master-the-art-of-excluding-commercial-videos-from-social-media/"><u>2024 Approved  Master the Art of Excluding Commercial Videos From Social Media</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Itel A05s | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/browsing-woes-solve-the-black-screen-mystery-on-chromesafari-facebook-live/"><u>Browsing Woes? Solve the Black Screen Mystery on Chrome/Safari Facebook Live</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-non-functional-shortcut-win-shift-and-s-on-microsoft-windows-versions/"><u>Effective Fixes for Non-Functional Shortcut: Win, Shift, and S on Microsoft Windows Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/error-resolution-addressing-the-windows-resource-protection-error/"><u>Error Resolution: Addressing the 'Windows Resource Protection Error'</u></a></li>
<li><a href="https://howto.techidaily.com/fix-samsung-galaxy-f54-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Samsung Galaxy F54 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-operational-audio-on-win-11-and-10/"><u>Fixing Non-Operational Audio on Win 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-recurring-restart-problems-in-windows-11-effortlessly/"><u>How to Resolve Recurring Restart Problems in Windows 11 Effortlessly</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/icue-detection-failure-identifying-and-solving-the-common-issues/"><u>ICUE Detection Failure: Identifying and Solving the Common Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-easy-to-use-screen-recording-tools-for-windows-10/"><u>In 2024, Free, Easy-To-Use Screen Recording Tools For Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-realme-narzo-60-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Realme Narzo 60 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/iphone-screen-sharing-made-simple-for-2024/"><u>IPhone Screen Sharing Made Simple for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-to-enable-your-devices-bluetooth-feature-on-windows-11-or-10/"><u>Quick Fixes to Enable Your Device's Bluetooth Feature on Windows 11 or 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-kodi-streaming-lag-how-to-fix-buffering-problems/"><u>Resolve Kodi Streaming Lag: How to Fix Buffering Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-touchpad-scrolling-difficulties-effective-methods-proven-to-work/"><u>Resolving Touchpad Scrolling Difficulties: Effective Methods Proven to Work</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-brightness-solutions-for-unlit-leds-on-your-corsair-keyboard/"><u>Restoring Brightness: Solutions for Unlit LEDs on Your Corsair Keyboard</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/revive-your-silent-iphone-understanding-and-resolving-the-no-ringtone-issue/"><u>Revive Your Silent iPhone: Understanding & Resolving the No-Ringtone Issue</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/skyrim-on-nintendo-switch-a-deep-dive-into-an-epic-rpg-adventure/"><u>Skyrim on Nintendo Switch: A Deep Dive Into an Epic RPG Adventure</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-repair-your-lenovos-malfunctioning-biometric-scanner/"><u>Step-by-Step Guide to Repair Your Lenovo's Malfunctioning Biometric Scanner</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-responsive-keyboard-on-windows-pcs-tips-and-tricks-solved/"><u>Troubleshooting a Non-Responsive Keyboard on Windows PCs - Tips & Tricks [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-the-print-driver-host-has-stopped-working-on-32-bit-systems/"><u>Troubleshooting Guide - Resolving 'The Print Driver Host Has Stopped Working' On 32-Bit Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-minecraft-local-network-multiplayer-issues/"><u>Troubleshooting Guide: Fixing 'Minecraft Local Network Multiplayer' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-safari-errors-easily-fix-pages-that-wont-open/"><u>Troubleshooting Safari Errors: Easily Fix Pages That Won't Open</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-windows-11-installation-error-80240020-solved/"><u>Troubleshooting Tips for Fixing Windows 11 Installation Error 80240020 [Solved]</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-best-5-udemy-subtitle-translator-auto-translation-for-2024/"><u>Updated Best 5 Udemy Subtitle Translator (Auto Translation) for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212134259-windows-11-touchpad-not-scrolling-heres-the-solution/"><u>Windows 11 Touchpad Not Scrolling? Here's the Solution!</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-inconsistent-copy-operation/"><u>Windows 11: Inconsistent Copy Operation</u></a></li>
<li><a href="https://common-error.techidaily.com/xbox-one-joystick-pc-compatibility-fixes/"><u>Xbox One Joystick: PC Compatibility Fixes</u></a></li>
</ul></div>
