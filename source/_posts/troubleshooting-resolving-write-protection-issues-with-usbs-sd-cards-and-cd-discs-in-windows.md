---
title: "Troubleshooting: Resolving Write Protection Issues with USBs, SD Cards, and CD Discs in Windows"
date: 2024-09-19T21:50:46.845Z
updated: 2024-09-26T22:52:26.595Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Resolving Write Protection Issues with USBs, SD Cards, and CD Discs in Windows"
excerpt: "This Article Describes Troubleshooting: Resolving Write Protection Issues with USBs, SD Cards, and CD Discs in Windows"
thumbnail: https://thmb.techidaily.com/656378bfa436826a8517a6c678576be78969ead53968b002df8bcb5d506324cf.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-keep-your-identity-under-wraps-while-livestreaming/"><u>[New] Keep Your Identity Under Wraps While Livestreaming</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-step-by-step-to-stunning-timelapses-a-comprehensive-guide-using-gopro/"><u>[Updated] In 2024, Step-By-Step to Stunning Timelapses A Comprehensive Guide Using GoPro</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-dealing-with-the-notorious-0x8000ffff-windows-error-a-comprehensive-guide/"><u>Expert Advice on Dealing with the Notorious 0X8000ffff Windows Error – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-how-to-fix-an-inverted-display-on-your-portable-computer/"><u>Expert Advice on How to Fix an Inverted Display on Your Portable Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-high-memory-usage-in-red-dead-redemption-ii-how-to-increase-pagefile/"><u>Fix High Memory Usage in Red Dead Redemption II: How to Increase Pagefile</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206628429-fix-your-laptops-non-charging-issue-a-fast-simple-solution/"><u>Fix Your Laptop's Non-Charging Issue: A Fast, Simple Solution!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-and-repair-entrypointnotfound-bugs-within-windows-systems/"><u>How to Correctly Address and Repair 'EntryPointNotFound' Bugs Within Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-locate-the-start-menu-in-windows-11-a-step-by-step-guide/"><u>How to Locate the Start Menu in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-rectify-steamapidll-mismatch/"><u>How to Rectify SteamAPI_dll Mismatch</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chucklechief-easy-meme-design-tool/"><u>In 2024, ChuckleChief Easy Meme Design Tool</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-x-drfone-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone X? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-split-videos-like-a-pro-the-best-free-tools/"><u>In 2024, Split Videos Like a Pro The Best Free Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-driverpowerstatefailure-problem-step-by-step-guide/"><u>Solving the DRIVER_POWER_STATE_FAILURE Problem: Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/symas-budget-marvel-the-107g-rc-helicopter-unleashed-a-complete-product-evaluation-and-insights/"><u>Syma's Budget Marvel: The 107G RC Helicopter Unleashed – A Complete Product Evaluation and Insights</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-lenovo-ideapad-130s-a-closer-look-at-its-limited-processing-strength-and-surprising-usability/"><u>The Lenovo IdeaPad 130S - A Closer Look at Its Limited Processing Strength and Surprising Usability</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-inadequate-system-resources-complete-guide-to-repair-services/"><u>Troubleshooting Inadequate System Resources - Complete Guide to Repair Services</u></a></li>
<li><a href="https://some-guidance.techidaily.com/understanding-ars-capabilities-and-limits-for-2024/"><u>Understanding AR's Capabilities and Limits for 2024</u></a></li>
</ul></div>

