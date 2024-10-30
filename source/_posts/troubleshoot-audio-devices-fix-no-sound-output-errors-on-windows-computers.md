---
title: "Troubleshoot Audio Devices: Fix No Sound Output Errors on Windows Computers"
date: 2024-10-23T17:48:54.021Z
updated: 2024-10-30T16:05:01.731Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshoot Audio Devices: Fix No Sound Output Errors on Windows Computers"
excerpt: "This Article Describes Troubleshoot Audio Devices: Fix No Sound Output Errors on Windows Computers"
thumbnail: https://thmb.techidaily.com/fb4a67269b09db2a7f2f5849b8bae34d180258d63241c7d8da96fca41cce9da8.jpg
---

## Error Code 0X80072F8F on Your Computer? Here's How You Can Troubleshoot Windows 11/10 Issues Easily

 Error code**0x80072f8f** is a typical notification that pops up in various cases. You may see this code in Windows update, activation, and store. This post is divided into 3 parts to grapple with this issue respectively.

1. **[Windows update error 0x80072f8f](#windows-update)**
2. **[Activation error 0x80072f8f](#windows-activation)**
3. **[Windows store error 0x80072f8f](#microsoft-store)**
4. **[Bonus tip](#bonus)**

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Windows update error 0x80072f8f

 If you see this error code during Windows update, try the 3 methods below.

### Fix 1 Install root certificate update

 Some users reported that the installation of root certificate update helps fix error 0x80072f8f. Since this update is expected to fix issues related to your computer’s connection with the Windows Update server, we can give it a shot.

1. Navigate to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx)**  . Type**Root Certificate Update** and click**Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_15-18-59.jpg)
2. Find the version that matches your computer and download it.  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_15-19-56.jpg)
3. Then follow the on-screen instruction to complete the installation.

 Then run a Windows update to check if the error code is resolved. If not, move on to try fix 2.

### Fix 2 Re-register DLL files

 If some DLL (Dynamic Link Library) files on your computer are malfunctioning, they may cause problems when connecting to the Windows Update servers. Hence, you may want to re-register these files with the following steps:

1. Type**cmd** in the Windows search box and click**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/cmd.jpg)
2. Copy and paste the following commands. Hit**Enter** after each.  

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

   * `**regsvr32 softpub.dll /s**`  
   * `**regsvr32 wintrust.dll /s**`  
   * `**regsvr32 initpki.dll /s**`  
   * `**regsvr32 mssip32.dl**` **`l /s`**  
   ![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_15-48-58.jpg)

 Now reboot the computer. After that, update your PC to see if the error is fixed.

---

 Sometimes system files like DLL files may go wrong without notification but hinder the system performance. In this case, an automatic system repair tool[**Fortect**](https://tools.techidaily.com/drivereasy/download/) may suit your need.

 Fortect is a powerful software that restores or replaces Windows files automatically after scanning. Apart from that, it’s able to remove malware threats, free precious disk space, restore max performance, and so on.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and run a free scan. Wait for the program to detect and diagnose issues for you.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
3. At the end of the scan, you can check your computer’s Hardware, Security, and Stability in comparison with a worldwide average. Besides, a summary of the issues detected will show up. Click**Start Repair** and you’ll be prompted to purchase.  

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

 Fortect comes with a**60-day Money-Back** Guarantee so you can refund anytime if Fortect doesn’t fix your problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 3 Turn off Firewall temporarily

 Windows Firewall is likely to overprotect and block the connection with the Windows update server. To figure that out, just temporarily disable the Firewall to have a test.

 Be extra careful to access the Internet during this period as your computer is vulnerable without protection.

1. Type**defender firewall** in the Windows search bar and click**Windows Defender Firewall** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/0x800f0922-7.jpg)
2. Choose**Turn Windows Defender Firewall on or off** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/0x800f0922-8.jpg)
3. **Turn off** Windows Defender Firewall for**Domain** ,**Private** and**Public** networks. Then click**OK** to save the change.  
![](https://images.drivereasy.com/wp-content/uploads/2022/05/0x800f0922-9.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you have installed any other third-party antivirus, also disable them temporarily by exiting or following the official guideline.

 Then you can run the Windows Update again to check for any improvement. Remember to turn on these protections after the testing.

## 0x80072f8f Windows activation error code

Encounter 0x80072f8f when activating Windows? Try 2 fixes below.

### Fix 1 Check the Date & time settings

 You need to have the correct date and time settings on your computer to access Windows services. So follow the steps to check it:

1. Press the**Windows logo key** and**I** on your keyboard to invoke Settings. Click**Time & Language** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_14-47-26.jpg)
2. On the Date & time tab, turn on**Set time automatically** and**Set time zone automatically** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_14-48-12.jpg)
3. Click**Region** on the left tab. Make sure the**Country or region** is set to the country where you live in.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_14-49-17.jpg)

Restart your PC to make changes apply. Then try activating again.

### Fix 2 Change the value data of registry key

 However, if the above method fails to help you solve the problem, try editing the registry editor.

1. Press the**Windows logo key** and**R** to open the Run window. Type**regedit** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_17-45-56.jpg)
2. Locate to the destination by following the path below.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 **HKEY\_LOCAL\_MACHINE/Software/Microsoft/Windows/CurrentVersion/Setup/OOBE**
3. Double-click**MediaBootInstall** . Then set the Value data to**0** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/regedit-activate-windows-8.jpg)
4. After exiting the Registry Editor, type**cmd** in the Windows search box and click**Run as administrator** .  

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/05/cmd.jpg)
5. Copy and paste**slmgr /rearm** . Then hit**Enter** . If you see a message with**Command completed successfully** , click**OK** to restart your computer.  

![](https://images.drivereasy.com/wp-content/uploads/2022/06/0628.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Try to run the activation process again to see if the error is fixed.

## Microsoft store error 0x80072f8f

 Here are 2 fixes for you who’s prompted with the error code in Microsoft store.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1 Run Windows Store Apps Troubleshooter

1. On your keyboard, press the**Windows logo key** and**I** to open Settings. Click**Update & Security** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/setting-updatesecurity.jpg)
2. Choose**Troubleshoot** in the left tab. Click**Additional troubleshooters** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/additional-troubleshooter.jpg)
3. Scroll down to click**Windows Store Apps** . Then click**Run the troubleshooter** .  

![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-27_18-13-47.jpg)

 Wait for the program to run and detect problems. However, if the error 0x80072f8f still persists, continue to try the next one.

### Fix 2 Reset Microsoft Store

 If any cached files or folders are causing a conflict to your Store when connecting to Microsoft server, try to reset Microsoft store.

1. Right-click the**Windows logo key** and select**Windows PowerShell (Admin)** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-28_15-24-45.jpg)
2. Copy and paste the command below. And then hit**Enter** .  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}`  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/2022-06-28_16-21-45.jpg)

Now try to use Microsoft store again to see if the issue is fixed.

## Bonus tip

 You should always keep your drivers up to date as outdated or faulty drivers may cause issues like slow network, malfunctioned hardware, or crashing programs. Updating drivers may resolve many computer problems for you.

 There are two ways you can get the right drivers for your computer: manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website of your hardness, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

**Automatic driver update** – If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . Driver Easy will automatically recognize your system and find the correct drivers for your hardness, and your Windows version, and it will download and install them correctly:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2022/07/DE-scan-5.8.png)
3. Click the **Update**  button next to the driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
 Or click **Update All** to automatically download and install the correct version of _all_ the drivers. (This requires the [Pro version](https://tools.techidaily.com/drivereasy/download/) which comes with a 30-day money-back guarantee. You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2022/06/update-rift-sensor-driver.jpg)

 The**Pro version** of Driver Easy comes with**full technical support** . If you need assistance, please contact Driver Easy’s support team at [**support@drivereasy.com**](https://vapordna.pxf.io/vnbxna) .

---

 These are the most common and helpful methods to **fix the 0x80072f8f** **error code** on Windows 11/10\. Hope you find this post helpful. If you have any other questions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows store](/tag-search/?tagId=21777)

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-youtube-prodigy-vs-creative-hub-beta-edition/"><u>[New] In 2024, YouTube Prodigy Vs. Creative Hub Beta Edition</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-liberate-yourself-with-free-movie-player-software/"><u>[New] Liberate Yourself with FREE MOVIE PLAYER Software</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-text-overlays-on-photos-in-windows-10s-photos-app/"><u>[New] Mastering Text Overlays on Photos in Windows 10'S Photos App</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-mastering-video-privacy-techniques-for-obscuring-details/"><u>[Updated] In 2024, Mastering Video Privacy Techniques for Obscuring Details</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-skype-video-not-working-on-windows-10/"><u>Easy to Fix Skype Video Not Working on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-broken-spacebar-functionality-on-windows-10-pcs/"><u>How to Repair a Broken Spacebar Functionality on Windows 10 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restart-your-audio-services-on-a-win-7-machine/"><u>How to Restart Your Audio Services on a Win 7 Machine</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-complete-studio-exploration-in-depth-xvideoexamine/"><u>In 2024, Complete Studio Exploration In-Depth XVideoExamine</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-echoing-ethos-with-closing-credits/"><u>In 2024, Echoing Ethos with Closing Credits</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-how-to-restore-pen-and-touch-interaction-on-your-screen/"><u>Troubleshooting: How to Restore Pen & Touch Interaction on Your Screen</u></a></li>
</ul></div>

