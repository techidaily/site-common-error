---
title: Bypassing Trouble with Windows Network Issue - Fix Error Code 0X800704CF Now
date: 2024-10-01T05:07:50.057Z
updated: 2024-10-06T17:43:08.932Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypassing Trouble with Windows Network Issue - Fix Error Code 0X800704CF Now
excerpt: This Article Describes Bypassing Trouble with Windows Network Issue - Fix Error Code 0X800704CF Now
thumbnail: https://thmb.techidaily.com/80456f09fe4efb7c4b8a390fbf6961e252df6f4afa54102d41b41a895101e337.jpg
---

## Bypassing Trouble with Windows Network Issue - Fix Error Code 0X800704CF Now

When you fail to access another computer of the same network, or when you cannot log in to the Microsoft Store, you may see the 0x800704cf error code. This string seems quite confusing, but in fact it’s not hard to solve the problem.

 We cover solutions for both situations listed above. You may not try them all; simply work down the list until you find the one that does the trick.

* **[If you see 0x800704cf error when connecting to a network PC](https://tools.techidaily.com/drivereasy/download/)**
* **[If you see 0x800704cf error when accessing Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**
* **[Bonus tips: Update your network driver](https://tools.techidaily.com/drivereasy/download/)**

---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fix 0x800704cf error when connecting to a network PC**

![Fix 0x800704cf error when connecting to a network PC](https://images.drivereasy.com/wp-content/uploads/2020/08/case1.jpg)

 It’s very frustrating when you want to access another network PC to share files or perform specific tasks but are interrupted by the 0x800704cf error. No worries. You can follow the guide below to put things back on track.

1. **[Change adapter options](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset TCP/IP](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reinstall the network adapter](https://tools.techidaily.com/drivereasy/download/)**

 The screenshot below comes from Windows 10, but the fixes also apply to Windows 7/8/11.

### Fix 1 – Change adapter options

 The network adapter enables your computer to transmit and receive data on a local area network. If you’re having the 0x800704cf error, try changing the adapter settings to see if that resolves the problem.

**1)** Right-click the**network icon** in the notification area.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-1-5.jpg)

**2)** Click**Open Network & Internet settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-2-8.jpg)

**3)** Select**Status** . Then, click**Change adapter options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-3-2.jpg)

**4)** Right-click the network you’re currently using, and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-4.jpg)

**5)** Uncheck**Client for Microsoft Networks** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-5.jpg)

 Restart your device and check if the 0x800704cf goes away. If not, continue with the next fix below.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 2 – Reset TCP/IP

 TCP/IP is a suite of rules that allow computers to communicate on a network. So if there’s something wrong with the[TCP/IP](https://en.wikipedia.org/wiki/Internet%5Fprotocol%5Fsuite) settings, the 0x800704cf error may occur. To see if that’s the case, you can simply do a reset.

**1)** Type**cmd** in the search box. Then, right-click**Command Prompt** and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-1-7.jpg)

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Click**Yes** when you’re prompted to continue.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-3-2.jpg)

**3)** In the command prompt window, type in the following commands and press the **Enter** key after each command.

ipconfig /flushdns

nbtstat -RR

netsh winsock reset

netsh int ip reset

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-2-4.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that the DNS cache is cleared, NetBIOS entries are refreshed, and both the IP settings and Winsock catalog is reset, you should reboot your computer for the changes to take effect. After that, check if the issue persists; if yes, head towards the last fix.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 3 – Reinstall the network adapter

 If all the methods above ended nowhere, you should reinstall the network adapter in case it’s corrupted and causes the 0x800704cf error.

**1)** On your keyboard, press the**Windows logo key** and**R** at the same time to open the Run box. Then, type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-1-6.jpg)

**2)** Select the**View** tab, and click**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-2-8.jpg)

**3)** Double-click**Network adapters** to view all the devices under this category.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-3-4.jpg)

**4)** Right-click a device and click**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-5-1.jpg)

**5)** Click**Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-4-3.jpg)

**6)** Delete all the devices one by one under Network adapters.

 After completing the steps above, restart your machine, and Windows will automatically reinstall the network adapters. The 0x800704cf error should be gone now and you can connect to another network PC without hassle.

---

## **Fix 0x800704cf error when accessing the Microsoft Store**

![Fix 0x800704cf error when accessing the Microsoft Store on Windows 10](https://images.drivereasy.com/wp-content/uploads/2020/08/error-case-2.jpg)

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When you fail to access the Microsoft Store on Windows 10 or 11, this 0x800704cf error will appear. It implies you’re not connected to the Internet, even though you are, as you can use the browser and other applications normally. But don’t worry; here’s a list of fixes that can help.

1. **[Sign in with Microsoft account](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the Windows troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reset the Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**

### Fix 1 – Sign in with Microsoft account

 The 0x800704cf error can arise when you’re logged in using a local account. Try signing in to your Microsoft account and see if the issue is resolved.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-9.jpg)

**2)** Click**Accounts** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-2-7.jpg)

**3)** Select**Your info** in the left pane. Then, click**Sign in with a Microsoft account instead** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-3-9.jpg)

**4)** Enter your**account** and**password** to sign in.

**5)** Go back to**Your info** , and click**Verify** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-4-5.jpg)

 Follow the on-screen instruction to verify your identity. Then, open your Microsoft Store and see whether the 0x800704cf code still pops up or not. If this method isn’t helpful, don’t despair. Have a look at more fixes below.

---

### Fix 2 – Run the Windows troubleshooter

 If the 0x800704cf error keeps appearing when you’re using the Microsoft Store, the Windows built-in troubleshooter is an effective tool that may help you out.

**1)** Type**troubleshoot** in the search box and click**Troubleshooting settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-3.jpg)

**2)** Scroll down to click**Network Adapter** . Then, click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-2-3.jpg)

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Select**All network adapters** , and click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-3-2.jpg)

**4)** Wait for the troubleshooting process to complete, and close the troubleshooter.

**5)** Click**troubleshoot** in the search box and click**Troubleshooting settings** to open the troubleshoot menu again.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-4.jpg)

**6)** Scroll down to click**Windows Store Apps** and click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-4-2.jpg)

 Follow the on-screen instruction to fix any detected issues. Then, launch the Microsoft Store and check if it works without error. If not, please try the Fix 3 below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 3 – Reset the Microsoft store

 If your Microsoft isn’t working properly for whatever reason, one of the solutions is clearing the stored data and resetting it back to the default.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-10.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Click**Apps** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-2-4.jpg)

**3)** Select**Apps & features** . Then, scroll down to click**Microsoft Store** , and click**Advanced options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-3-2.jpg)

**4)** Scroll down and click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-4-1.jpg)

**5)** Click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-5-1.jpg)

 Open your Microsoft Store, and the 0x800704cf error won’t be disturbing you anymore.

 Network issue like 0x800704cf error is a common PC problem but it’s insufferable. There’s so much you can’t do without the Internet, and even worse, you can’t search a solution to fix it. If you’ve frequently run into this kind of issues such as no or slow Internet access, be sure to check our bonus tips below.

---

## Bonus tips: Update your network driver

 An outdated or a faulty network driver is known to be the culprit of most network problems. To keep your network connection smooth and strong, you should check if you install the up-to-date network adapter driver. If not, update them, in either way you want.

**Manual driver update** – You can update your network adapter driver manually by going to the manufacturer’s website, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly:

**1)** **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

**2)** Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-1-5.jpg)

**3)** Click the**Update** button next to the flagged network driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the**FREE version** ).

 Or click**Update All** to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system. (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click**Update All** ).

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-2-7.jpg)

 You can do it for free if you like, but it’s partly manual.

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://tools.techidaily.com/drivereasy/download/) .**

---

 Hopefully this post helped you get rid of the 0x800704cf error. If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [network adapter](https://tools.techidaily.com/drivereasy/download/)
* [network issue](https://tools.techidaily.com/drivereasy/download/)
* [network problem](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-mouse-cursor-goes-missing-in-windows-win-10-a-step-by-step-solution/"><u>[Troubleshooting] When Your Mouse Cursor Goes Missing in Windows (Win) [10]: A Step-by-Step Solution.</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-elevating-your-videos-visual-impact-youtubthumbnail-design-on-macos/"><u>[Updated] Elevating Your Video's Visual Impact YoutubThumbnail Design on macOS</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-blues-beat-windows-11s-pairing-problems-with-these-expert-solutions/"><u>Bluetooth Blues? Beat Windows 11'S Pairing Problems with These Expert Solutions</u></a></li>
<li><a href="https://data-wizards.techidaily.com/discover-the-future-of-data-recovery-stellars-mac-12v-edition/"><u>Discover the Future of Data Recovery: Stellar's Mac 12v Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-navigation-and-troubleshooting-for-windows-10s-file-explorer/"><u>Effortless Navigation and Troubleshooting for Windows 10'S File Explorer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/evaluating-the-capabilities-of-switchbot-universal-remote-control-more-than-just-an-all-purpose-device/"><u>Evaluating the Capabilities of SwitchBot Universal Remote Control: More Than Just an All-Purpose Device?</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>Fake the Location to Get Around the MLB Blackouts on Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-samsung-galaxy-a54-5g-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Samsung Galaxy A54 5G Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-apple-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-your-windows-11-copy-and-paste-malfunction-easily/"><u>Resolving Your Windows 11 'Copy & Paste' Malfunction Easily</u></a></li>
</ul></div>

