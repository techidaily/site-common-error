---
title: How to Resolve 'Appropriate Driver Not Installed' Error on Lenovo Devices
date: 2024-10-08T20:30:09.364Z
updated: 2024-10-12T21:25:53.466Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Resolve 'Appropriate Driver Not Installed' Error on Lenovo Devices
excerpt: This Article Describes How to Resolve 'Appropriate Driver Not Installed' Error on Lenovo Devices
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## How to Resolve the Persistent Windows Store Error 0X80072EE7: Proven Solutions Unveiled

If you’re greeted with **0x80072EE7** error code when opening**Windows Store** , you’re not alone.

But don’t worry, it’s not hard to fix at all…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 5 fixes for **0x80072EE7**

 All the fixes below work in**Windows 10** . You may not have to try all of them; just work from top down the list until your Windows Store runs smoothly again.

1. **[Start Windows Store service and change Windows Update startup type](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your graphics driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Change the DNS server address](https://tools.techidaily.com/drivereasy/download/)**
5. **[Register Windows Store package](https://tools.techidaily.com/drivereasy/download/)**

### Fix 1: Start Windows Store service and change Windows Update startup type

 Starting**Windows Store service** and change**Windows Update startup type** is a proven effective fix for our **0x80072ee7** in our Windows Store. To do so:

1. On your keyboard, press **the Windows logo key**   ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)  and **R**  at the same time, then copy & paste **services.msc** into the box and press   **Enter**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ef3aff37fc.jpg)
2. Right-click on**Microsoft Store Install Service** and click**Start** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b515a7b35011.jpg)
3. Scroll down to the bottom and double-click on**Windows Update** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51623b61cf7.jpg)
4. Select**Manual** in**Startup type** , click**Apply** \>**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51629aa2ad6.jpg)
5. Launch your Windows Store again and see if the problem has been solved.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### Fix 2: Run the DISM tool

**DISM**  (**Deployment Image & Servicing Management** ) is a tool in Windows that helps us fix Windows-corruption-caused errors.  Sometimes this XXXX problem happens because of corruption and misconfigurations on our computer. If that’s the case, we’ll have to run DISM to check and fix the error.

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)
2. Type **the following command** and press **Enter** :  

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**DISM.exe /Online /Cleanup-image /Restorehealth**  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30abe4b92d4.jpg)  
 Wait a while for the whole process to finish.

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type **sfc /scannow**  and press **Enter** .
4. Restart your computer, run Windows Store again and see if it works properly this time.

---

### Fix 3: Update your graphics driver

 A corrupt/outdated/missing/wrong graphics driver is one of the common cause of this Windows store **0x80072ee7** error code. So you might have to**update your graphics driver to the latest** to make sure things won’t go worse (like snowy screens, blue screens of death) if unattended. There’re two ways you can update your device drivers — manually or automatically:

**Update your drivers manually** – You can update your device drivers manually by going to the manufacturer’s website, and searching for the most recent correct driver for the exact device. Be sure to choose only drivers that are compatible with your variant of Windows system versions.

**OR**

**Update your drivers automatically** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either **[the FREE](https://tools.techidaily.com/drivereasy/download/)**  or **[the Pro version](https://tools.techidaily.com/drivereasy/download/)**   of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b46ffcde1143.jpg)
3. You can upgrade to **[the Pro version](https://tools.techidaily.com/drivereasy/download/)**  and click **Update All** to automatically download and install the correct version of **ALL**  the drivers that are missing or out of date on your system.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b472528c2b06.jpg) You can also click **Update** to do it for free if you like, but it’s partly manual.
4. Restart your computer and hope everything goes off without a hitch on your computer.

 If the problem still lingers on after trying Driver Easy, feel free to contact our support team at **<support@drivereasy.com>** . Be sure to attach **the URL of this article** for more expedient and efficient guidance. ?

---

### Fix 4: Change the DNS server address

 Another possible cause for this issue is  the unstable network connection or the misconfiguration of DNS servers settings. So we might have to change the DNS server address to see if it gets fixed:

1. On your keyboard, press   **the Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)** and **R**  at the same time. Then copy & paste **control /name Microsoft.NetworkAndSharingCenter** into the box and click   **OK**  .  
**![](https://images.drivereasy.com/wp-content/uploads/2018/05/img_5af921398c56a.png)**
2. **Click Change adapter settings .**  
**![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae2935c0967f.jpg)**
3. Right-click on**the network adpater** (Ethernet in my case) and click **Properties** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b22081a8ea67.jpg)
4. Click **Internet Protocol Version 4 (TCP/IPv4)**  and then click **Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2228b800796.jpg)
5. Click option **Use the following DNS server addreses** ,

 for **Preferred DNS server** , enter **8.8.8.8** ;

 for **Alternate DNS server** , enter **8.8.4.4.**

 Then click **OK** .  
 ![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2229e75f892.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Restart your computer and re-launch your Windows Store to see if it works fine now.

---

### **Fix 5: Register Windows Store package**

 Fix 5 is about registering Windows Store package. This can help fix many issues(not opening, hanging, error codes etc) on Windows Store. To do this:

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Copy & paste**the following command** into the window and press**Enter** .  

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141683/17092" target="_top" id="2141683">
  <img src="//a.impactradius-go.com/display-ad/17092-2141683" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141683/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**PowerShell -ExecutionPolicy Unrestricted -Command “& {$manifest = (Get-AppxPackage Microsoft.WindowsStore).InstallLocation + ‘\AppxManifest.xml’ ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}”**
3. Once it finishes, close the command prompt window.
4. Restart your computer, open Windows Store again and see if the error code has been fixed.

---

 That’s it – top 5 tips for fixing the 0x80072ee7 Windows Store problem on your Windows 10 computer. Hope this helps and feel free to comment below if you have any further questions or thoughts. 🙂

* [Windows store](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-masterful-thumbnails-in-a-flash-professional-valorant-creations/"><u>[Updated] 2024 Approved Masterful Thumbnails in a Flash Professional Valorant Creations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beyond-basics-leveraging-my-gpt-bots-in-chatgpt-to-excel-at-board-games-and-more/"><u>Beyond Basics: Leveraging My GPT Bots in ChatGPT to Excel at Board Games and More</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-resolving-issues-with-your-logitech-mouses-scroll-wheel/"><u>Expert Tips: Resolving Issues with Your Logitech Mouse's Scroll Wheel</u></a></li>
<li><a href="https://some-guidance.techidaily.com/gratuidade-converter-e-salvar-em-video-flv-ao-vivo-online-sem-custo-com-o-movavi/"><u>Gratuidade: Converter E Salvar Em Vídeo FLV Ao Vivo Online Sem Custo Com O Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-usb-device-unrecognized-error-that-constantly-appears/"><u>How to Fix the 'USB Device Unrecognized' Error That Constantly Appears</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-honor-play-7t-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Honor Play 7T Phone When You Forget the Password</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-realme-11-proplus-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Realme 11 Pro+</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-future-of-video-recording-insights-into-fraps/"><u>In 2024, The Future of Video Recording Insights Into Fraps</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ftdi-sys-issues-the-impact-of-incompatible-device-drivers-on-memory-safety/"><u>Troubleshooting FTDI Sys Issues: The Impact of Incompatible Device Drivers on Memory Safety</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-non-functional-bluetooth-mouse-in-windows/"><u>Troubleshooting Guide: Fixing a Non-Functional Bluetooth Mouse in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-microsofts-0x80004005-error-a-step-by-step-tutorial/"><u>Understanding and Correcting Microsoft's 0X80004005 Error: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-decline-of-chatgpt-jailbreak-success-unveiling-7-key-factors/"><u>Understanding the Decline of ChatGPT Jailbreak Success: Unveiling 7 Key Factors</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/which-is-superior-obs-or-streamlabs-for-your-livestream-needs/"><u>Which Is Superior, OBS or Streamlabs for Your Livestream Needs?</u></a></li>
<li><a href="https://common-error.techidaily.com/win-1011-audio-service-reset-completed/"><u>Win 10/11 Audio Service Reset Completed</u></a></li>
</ul></div>

