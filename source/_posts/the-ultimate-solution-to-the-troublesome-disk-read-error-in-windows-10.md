---
title: The Ultimate Solution to the Troublesome 'Disk Read Error' In Windows 10
date: 2024-10-01T03:36:55.164Z
updated: 2024-10-02T03:03:16.982Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes The Ultimate Solution to the Troublesome 'Disk Read Error' In Windows 10
excerpt: This Article Describes The Ultimate Solution to the Troublesome 'Disk Read Error' In Windows 10
thumbnail: https://thmb.techidaily.com/77611f2e0e7b4b101c92af3b172df9c62d2c1071591d3411a278cc0334c16e37.jpg
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

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1: Start Windows Store service and change Windows Update startup type

 Starting**Windows Store service** and change**Windows Update startup type** is a proven effective fix for our **0x80072ee7** in our Windows Store. To do so:

1. On your keyboard, press **the Windows logo key**   ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)  and **R**  at the same time, then copy & paste **services.msc** into the box and press   **Enter**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ef3aff37fc.jpg)
2. Right-click on**Microsoft Store Install Service** and click**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b515a7b35011.jpg)
3. Scroll down to the bottom and double-click on**Windows Update** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51623b61cf7.jpg)
4. Select**Manual** in**Startup type** , click**Apply** \>**OK** .  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51629aa2ad6.jpg)
5. Launch your Windows Store again and see if the problem has been solved.

---

### Fix 2: Run the DISM tool

**DISM**  (**Deployment Image & Servicing Management** ) is a tool in Windows that helps us fix Windows-corruption-caused errors.  Sometimes this XXXX problem happens because of corruption and misconfigurations on our computer. If that’s the case, we’ll have to run DISM to check and fix the error.

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type **the following command** and press **Enter** :  
**DISM.exe /Online /Cleanup-image /Restorehealth**  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30abe4b92d4.jpg)  
 Wait a while for the whole process to finish.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 4: Change the DNS server address

 Another possible cause for this issue is  the unstable network connection or the misconfiguration of DNS servers settings. So we might have to change the DNS server address to see if it gets fixed:

1. On your keyboard, press   **the Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)** and **R**  at the same time. Then copy & paste **control /name Microsoft.NetworkAndSharingCenter** into the box and click   **OK**  .  
**![](https://images.drivereasy.com/wp-content/uploads/2018/05/img_5af921398c56a.png)**
2. **Click Change adapter settings .**  
**![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae2935c0967f.jpg)**
3. Right-click on**the network adpater** (Ethernet in my case) and click **Properties** .  

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b22081a8ea67.jpg)
4. Click **Internet Protocol Version 4 (TCP/IPv4)**  and then click **Properties** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2228b800796.jpg)
5. Click option **Use the following DNS server addreses** ,

 for **Preferred DNS server** , enter **8.8.8.8** ;

 for **Alternate DNS server** , enter **8.8.4.4.**

 Then click **OK** .  
 ![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2229e75f892.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Restart your computer and re-launch your Windows Store to see if it works fine now.

---

### **Fix 5: Register Windows Store package**

 Fix 5 is about registering Windows Store package. This can help fix many issues(not opening, hanging, error codes etc) on Windows Store. To do this:

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)
2. Copy & paste**the following command** into the window and press**Enter** .  
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
<li><a href="https://some-guidance.techidaily.com/new-navigating-htc-vive-experience-without-nausea/"><u>[New] Navigating HTC Vive Experience Without Nausea</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-essential-checklist-purging-backdrops-with-affinity-photo/"><u>[New] The Essential Checklist Purging Backdrops with Affinity Photo</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/he-secret-sauce-to-outstanding-online-identity-creation/"><u>[New] The Secret Sauce to Outstanding Online Identity Creation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-essential-tech-top-10-webcam-recorders-in-win-11/"><u>[Updated] Essential Tech Top 10 Webcam Recorders in Win 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-video-editing-journeys-end-discover-the-best-10-tools/"><u>[Updated] In 2024, Video Editing Journey's End Discover the Best 10 Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/accelerated-artistry-instant-collage-creation-on-fb/"><u>Accelerated Artistry Instant Collage Creation on FB</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-the-critical-process-died-error-0xc00000e9-on-your-pc/"><u>Diagnosing and Repairing the Critical Process Died Error (0xC00000E9) on Your PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-guide-how-to-overcome-the-battlefield-4-not-opening-on-pc-dilemma/"><u>Expert Guide: How to Overcome the 'Battlefield 4 Not Opening on PC' Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-airpods-connectivity-problems-with-windows-1011-updated-guide/"><u>Fixing AirPods Connectivity Problems with Windows 10/11 - Updated Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-samsung-galaxy-m54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-persistent-windows-10-freezing-issues-when-booting-up/"><u>How to Overcome Persistent Windows 10 Freezing Issues When Booting Up</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-steps-how-to-quickly-freshen-up-or-restart-your-windows-11-system/"><u>Simple Steps: How to Quickly Freshen Up or Restart Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210105106-unstuck-your-touchscreen-on-windows-10-try-these-5-troubleshooting-tactics/"><u>Unstuck Your Touchscreen on Windows 10? Try These 5 Troubleshooting Tactics</u></a></li>
</ul></div>

