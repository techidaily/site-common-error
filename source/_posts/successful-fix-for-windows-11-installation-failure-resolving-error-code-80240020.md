---
title: "Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
date: 2024-10-24T16:48:32.040Z
updated: 2024-10-30T16:49:42.811Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
excerpt: "This Article Describes Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
thumbnail: https://thmb.techidaily.com/227bd0353ed763348ef514468bae7b22e2b22e0109d88910437782328b50ad10.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
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
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/fixed-an-error-occurred-while-installing-updating-steam-games/"><u>[Fixed] An Error Occurred While Installing/ Updating Steam Games</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-learn-quick-image-text-alteration-online-resources/"><u>[New] 2024 Approved Learn Quick Image Text Alteration Online Resources</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-essential-guide-to-recording-gotomeet-sessions/"><u>[New] In 2024, Essential Guide to Recording GoToMeet Sessions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-step-by-step-techniques-downloading-and-crafting-instagram-stories/"><u>[New] Step-by-Step Techniques Downloading & Crafting Instagram Stories</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-must-have-offline-mobile-games-to-keep-you-entertained-on-android/"><u>2024 Approved Must-Have Offline Mobile Games to Keep You Entertained on Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-one-on-one-youtube-streams-on-mobile-without-thousanders-club/"><u>2024 Approved One-on-One Youtube Streams on Mobile Without Thousanders' Club</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-rectifying-non-functional-touchpad-scrolling-on-laptopspcs/"><u>Effective Remedies: Rectifying Non-Functional Touchpad Scrolling on Laptops/PCs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fade-techniques-in-audio-production-with-adobe-tools-for-2024/"><u>Fade Techniques in Audio Production with Adobe Tools for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-version-of-hp-deskjet-2540-drivers-for-free/"><u>Get the Latest Version of HP Deskjet 2540 Drivers for Free</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-fixing-windows-11s-inability-to-recognize-bluetooth-peripherals/"><u>Guide: Fixing Windows 11'S Inability to Recognize Bluetooth Peripherals</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-poco-m6-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Poco M6 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-reactivate-the-night-light-option-in-windows-11-when-it-stops-working/"><u>How to Reactivate the Night Light Option in Windows 11 when It Stops Working</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-from-snap-to-stunning-photo-editing-secrets/"><u>In 2024, From Snap to Stunning Photo Editing Secrets</u></a></li>
<li><a href="https://common-error.techidaily.com/say-goodbye-to-buffering-masterful-ways-to-improve-streaming-on-kodi/"><u>Say Goodbye to Buffering: Masterful Ways to Improve Streaming on Kodi</u></a></li>
<li><a href="https://common-error.techidaily.com/the-complete-fix-manual-what-to-do-when-you-encounter-a-black-screen-on-dell-systems/"><u>The Complete Fix Manual: What to Do When You Encounter a Black Screen on Dell Systems</u></a></li>
</ul></div>

