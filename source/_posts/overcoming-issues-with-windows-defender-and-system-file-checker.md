---
title: Overcoming Issues with Windows Defender and System File Checker
date: 2024-09-09T08:55:03.373Z
updated: 2024-09-10T08:55:03.373Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming Issues with Windows Defender and System File Checker
excerpt: This Article Describes Overcoming Issues with Windows Defender and System File Checker
thumbnail: https://thmb.techidaily.com/d6f225de23330f252c6d5195ffc58e836dfeb5e08b530725208b4f5fec9ae8dd.JPG
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Tips for Windows 10 Issues with The Duo Approach: System File Checker (SFC) and Deployment Image Servicing (DISM)

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586c9a4e6db41.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Windows 10 is equipped with some very handy tools that allow you to solve your computer problems.**System File Checker** and**Deployment Image & Servicing Management** tools are ones of them.

You should consider using these tools when:

**a) troubleshooting a buggy Windows system;**
**b) blue screen of death errors occur;**
**c) applications crash;**
**d) some Windows features are not working properly.**

and etc.

 In this post, we will show you some tools that you can use to solve your computer problems:

[**System File Checker tool**](#1)
[**Deployment Image & Servicing Management tool**](#2)
[**System Restore**](#3)

**Run SFC Command to Repair System Files**

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115926/19272" target="_top" id="2115926">
  <img src="//a.impactradius-go.com/display-ad/19272-2115926" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115926/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) In the Command Prompt window, type in the following command:

sfc /scannow

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca221df44e.jpg)

Leave the Command Prompt window on until the command completes.

 3) If you see the message saying that   **Windows Resource Protection did not find any integrity violations** , then everything is fine with your system.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca520c7e49.png)

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) If you see a message saying   **Windows Resource Protection found corrupt files but was unable to fix some of them** , then you need to go to[**safe mode**](https://tools.techidaily.com/drivereasy/download/) and run the system file checker again.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca59f1f21f.jpg)

 If the SFC command doesn’t work well, please mve on to the next section to run the DISM command to fix the SFC command problem and then run SFC command again.

**Run the DISM Command to Fix SFC Problems**

**DISM** stands for Deployment Image & Servicing Management, which is a tool that can fix component store corruption that prevents the SFC command from working properly.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca8464439b.jpg)

Wait for a while for the whole process to finishes.

 3) When the whole process finishes, restart your computer. Then run SFC command again so it will help you replace any corrupted files with the correct ones.

 **System Refresh or Reset**

 If the above tools cannot help you solve your computer problems, you can have a try at refreshing or resetting your Windows 10.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586caacd9f489.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
For more detailed information, please go to the posts below:

[**How to refresh Windows 10?**](https://tools.techidaily.com/drivereasy/download/)
[**How to reset Windows 10?**](https://tools.techidaily.com/drivereasy/download/)

**Pro Tip:**
 In many cases, most of your computer problems can be solved by updating your device drivers to their latest versions unless the problems are with the hardware, in which case, you will need to get your hardware replaced.

 To update device drivers, you can use[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) for assistance. It automatically detects, downloads and updates your missing and outdated device drivers and allow you to finish the whole process in just a couple of minutes.

![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e8abc65e6ec.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to have your own professional tech support and tons of other features in Driver Easy such as driver back up and driver restore, by all means, have a try at the[**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It allows you to update all your device drivers in just ONE click and poof, your computer problems are gone!

 You can always ask for a refund thirty days within the purchase if you are not satisfied with it. What’s with the hold up, come on and have a try at[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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


