---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2024-12-03T18:41:19.266Z
updated: 2024-12-10T21:46:27.630Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
excerpt: This Article Describes How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
thumbnail: https://thmb.techidaily.com/995d8276c073ea6830ba619ba4614fd047fc0375a4d1ae8bef82547a42248f63.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

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
<li><a href="https://desktop-recording.techidaily.com/new-exclusive-screenflow-examination-for-mac-users-for-2024/"><u>[New] Exclusive ScreenFlow Examination for Mac Users for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-video-cutting-with-vivacut-detailed-review-and-guidebook-24/"><u>2024 Approved Master Video Cutting with VivaCut Detailed Review & Guidebook '24</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-unlock-your-youtube-potential-idea-generation-guide/"><u>2024 Approved Unlock Your YouTube Potential Idea Generation Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/amplify-your-videos-impact-with-strategically-placed-time-markers/"><u>Amplify Your Video's Impact with Strategically Placed Time Markers</u></a></li>
<li><a href="https://common-error.techidaily.com/battle-the-high-resource-hog-svchostexe-strategies-to-optimize-windows-11-performance/"><u>Battle the High Resource Hog svchost.exe: Strategies to Optimize Windows 11 Performance</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/blurring-the-boundary-a-comprehensive-look-at-story-bokeh/"><u>Blurring the Boundary A Comprehensive Look at Story Bokeh</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1067-explained-a-step-by-step-solution-for-when-your-windows-application-abruptly-stops/"><u>Error 1067 Explained: A Step-by-Step Solution for When Your Windows Application Abruptly Stops</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-diagnose-and-address-teredo-unable-to-qualify-issues/"><u>How To Successfully Diagnose and Address 'Teredo Unable to Qualify' Issues</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-oppo-a59-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-action-required-local-security-authority-guardrails-engaged-once-more/"><u>Immediate Action Required: Local Security Authority Guardrails Engaged Once More</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-transforming-tiktok-to-pop-with-top-gif-tools/"><u>In 2024, Transforming TikTok to Pop with Top GIF Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/innovative-solutions-for-windows-10-screen-saver-problems-step-by-step-guide/"><u>Innovative Solutions for Windows 10 Screen Saver Problems - Step by Step Guide</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/revolutionizing-browsing-ai-in-microsofts-bing/"><u>Revolutionizing Browsing: AI in Microsoft's Bing</u></a></li>
<li><a href="https://common-error.techidaily.com/slash-your-pcs-graphics-performance-hit-5-methods-to-optimize-the-desktop-window-manager-on-windows/"><u>Slash Your PC's Graphics Performance Hit: 5 Methods to Optimize the Desktop Window Manager on Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-finest-gopro-complementary-items-for-2024/"><u>The Finest Gopro Complementary Items for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-free-fixes-for-a-laptop-that-wont-hold-a-charge-expert-advice-inside/"><u>Trouble-Free Fixes for a Laptop That Won't Hold A Charge: Expert Advice Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-0x800705b4-error-on-windows-update-for-windows-10-users/"><u>Troubleshoot & Fix 0X800705b4 Error on Windows Update for Windows 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-flickering-display-on-windows-10-computers/"><u>Troubleshooting and Repairing Flickering Display on Windows 10 Computers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-mystery-behind-chatgpts-ownership/"><u>Unraveling the Mystery Behind ChatGPT's Ownership</u></a></li>
</ul></div>

