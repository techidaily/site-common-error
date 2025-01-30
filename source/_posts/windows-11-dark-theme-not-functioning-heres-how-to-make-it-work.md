---
title: Windows 11 Dark Theme Not Functioning? Here’s How to Make It Work
date: 2025-01-24T21:04:40.788Z
updated: 2025-01-30T01:32:34.118Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Dark Theme Not Functioning? Here’s How to Make It Work
excerpt: This Article Describes Windows 11 Dark Theme Not Functioning? Here’s How to Make It Work
thumbnail: https://thmb.techidaily.com/61e18062b10a05e50558d2765f20eeedf900f4f1438428a2471f9b4a0fdcaefb.jpg
---

## Windows 11 Dark Theme Not Functioning? Here’s How to Make It Work

![](https://images.drivereasy.com/wp-content/uploads/2022/08/night-light.jpg)

 Windows 10 and 11 have a built-in blue light filter, called**Night Light** . By enabling this feature, your display will show warmer colors at night to help you reduce eye strain and get to sleep. However, many users are experiencing problems with this feature. Some users reported that they couldn’t turn on the Night Light as this option is grayed out. Others said that the Night Light couldn’t turn off no matter what they did. If you happen to be one of them, don’t worry. Here are some working fixes you can try.

## 6 Fixes for Night Light not working

 You might not need to try them all. Just work down the list until you find the one that does the trick.

1. **[Sign out of your account and sign back in](#Fix1)**
2. **[Update your display driver](#Fix2)**
3. **[Reset Night Light settings manually](#Fix3)**
4. **[Check date and time settings](#Fix4)**
5. **[Turn on Location services](#Fix5)**
6. **[Check for Windows updates](#Fix6)**

### Fix 1: Sign out of your account and sign back in

 Sometimes, the Night Light not working issue could be caused by a temporary glitch. If that’s the case, you can try to fix the problem by signing out of your account and then signing back in.

![](https://images.drivereasy.com/wp-content/uploads/2022/08/windows-sign-out.jpg)

 Check if the Night Light starts working again. If your issue persists, go ahead and try the next fix.

### Fix 2: Update your display driver

 One of the most common causes of the Night Light not working is that you’re using a faulty or outdated display driver. So you should update your display driver to see if it fixes your problem.

 There are mainly two ways to update your display driver: manually or automatically.

**Manual driver update** – You can update your display drivers manually by going to the manufacturer’s website ([NVIDIA](https://tools.techidaily.com/drivereasy/download/) ,[AMD](https://www.amd.com/en/support) or[Intel](https://www.intel.com/content/www/us/en/download-center/home.html) ), and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

**Automatic driver update** – If you don’t have the time, patience, or computer skills to update your display drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact display adapter, and your Windows version, and it will download and install them correctly:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2021/09/de-scan-now-20-1.jpg)
3. Click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  — you’ll be prompted to upgrade when you click Update All.)  

 Or click the**Update** button next to the flagged display driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
![](https://images.drivereasy.com/wp-content/uploads/2021/09/de-nvidia-gtx-1080.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**The Pro version of Driver Easy** comes with full technical support. If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

 After updating your display driver, restart your computer and check if the Night Light works properly.

If your issue remains, check out the next fix.

### Fix 3: Reset Night Light settings manually

 If the Night Light option on your PC is grayed out, you can try resetting this feature by editing the Windows registry. Here’s how to do it:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** dialog. Then type**regedit** and click**OK** to open**Registry Editor** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/windows-r-regedit.jpg)
2. Click**Yes** if prompted by User Account Control.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/08/registry-editor-uac.jpg)
3. In Registry Editor, paste the following path into the address bar and press**Enter** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CloudStore\Store\DefaultAccount\Cloud`**  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/registry-editor-cloud.jpg)
4. Under the Cloud key,**right-click** and**delete** the first two registry keys one by one.  

**`default$windows.data.bluelightreduction.bluelightreductionstate`**  
`**default$windows.data.bluelightreduction.settings**  
` ![](https://images.drivereasy.com/wp-content/uploads/2022/08/blue-light-reduction-delete.jpg)
5. Once done, close and exit Registry Editor.
6. Restart your PC and check if your problem has been resolved.

 If the Night Light still doesn’t work properly, continue with the next fix.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 4: Check date and time settings

 Windows allows you to set a schedule to turn on and turn off the Night Light feature. If the date and time settings on your PC are set incorrectly, you might be unable to use this feature properly. To check your PC’s date and time settings:

1. On your taskbar, right-click the time and select**Adjust date/time** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/adjust-date-time.jpg)
2. In the pop-up window, make sure the date and time on your device are set correctly for your time zone. If not, you can click the**Change** button to change the date and time.  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/time-change.jpg)  
 Note: the options for**Set time automatically** and**Set time zone automatically** must be set to**Off** to make this change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Change the date and time according to your need, then click**Change** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/change-date-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the date and time are correct and you still encounter the Night Light not working issue, you may need to check Location services.

### Fix 5: Turn on Location services

 If you want to schedule the night light from sunset to sunrise, you need to turn on Location services, as the exact time of sunset and sunrise depends on your location and date. Here’s how to do it:

1. On your keyboard, press the**Windows logo key** and**I** together to open**Windows Settings** . Then click**Privacy** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/settings-privacy.jpg)
2. In the left panel, select**Location** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/settings-location.jpg)
3. Make sure the**Location for this device** is**On** . If not, you can click the**Change** button to turn it on. Also, make sure that**Allow apps to access your location** is set to**On** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/location-on.jpg)

 Now try to use the Night Light feature again and see if it works properly.

### Fix 6: Check for Windows updates

 Windows updates often include bug fixes, security patches, and some new features. So chances are that your problem can be solved by installing the new updates. To check for Windows updates:

1. In the search field on your taskbar, type**check for updates** . Then select it from the search results.  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/check-for-updates.jpg)
2. In the new window, click**Check for updates** . Windows will automatically download and install all pending updates if available.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2021/08/check-for-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve installed all updates, restart your PC and check if your issue has been resolved.

 If you’ve tried all fixes listed above and still can’t get the Night Light to work, consider using a third-party app like[f.lux](https://justgetflux.com/) to do the same work for you.

---

 That’s all for now. Hopefully, this post helped. If you have any further questions or suggestions, feel free to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-7-pro-tips-to-enhance-your-foodie-filmography/"><u>[New] 2024 Approved 7 Pro Tips to Enhance Your Foodie Filmography</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevating-your-music-crafting-stunning-lyric-videos-using-lyric-video-maker/"><u>[Updated] 2024 Approved Elevating Your Music Crafting Stunning Lyric Videos Using Lyric Video Maker</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-elevate-your-online-sound-experience-with-these-5-steps/"><u>2024 Approved Elevate Your Online Sound Experience with These 5 Steps</u></a></li>
<li><a href="https://ai-topics.techidaily.com/advanced-hardware-tips-and-tricks-from-toms-equipment-analysis/"><u>Advanced Hardware Tips and Tricks From Tom's Equipment Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-you-secure-with-obs-comprehensive-safety-tips-for-streaming-and-screen-capturing/"><u>Are You Secure with OBS?: Comprehensive Safety Tips for Streaming & Screen Capturing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-play-mp4-files-on-galaxy-s24-ultra-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Galaxy S24 Ultra</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/gourmet-visuals-in-motion-food-shot-tips-and-tricks/"><u>Gourmet Visuals in Motion Food Shot Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-critical-network-problem-error-0x800704cf-in-windows-systems/"><u>How To Fix The Critical Network Problem (Error 0X800704CF) In Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-cwindowssystem32configsystemprofiledesktop-access-errors/"><u>How to Resolve C: Windows system32 config systemprofile Desktop Access Errors</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-a-compreshift-guide-to-creating-profitable-and-engaging-youtube-collaborations/"><u>In 2024, A Compreshift Guide to Creating Profitable & Engaging YouTube Collaborations</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-malfunctioning-usb-input-devices-on-windows-7/"><u>Resolving Malfunctioning USB Input Devices on Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-non-functional-usb-ports-on-windows-1011-systems/"><u>Resolving Non-Functional USB Ports on Windows 10/11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-fixing-steam-update-download-failures/"><u>Step-by-Step Solution for Fixing Steam Update Download Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-troubleshooting-fixing-windows-update-issues/"><u>Successful Troubleshooting: Fixing Windows Update Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-fixing-airpod-pairing-on-your-pc-win-10-and-11-solutions/"><u>The Ultimate Guide to Fixing AirPod Pairing on Your PC: Win 10 & 11 Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-making-windows-hello-work-on-your-windows-11-pc/"><u>Troubleshooting Guide: Making Windows Hello Work on Your Windows 11 PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/understanding-and-correcting-starcraft-crashes-during-playtime-on-pc-setups/"><u>Understanding and Correcting StarCraft √ Crashes During Playtime on PC Setups</u></a></li>
</ul></div>

