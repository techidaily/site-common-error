---
title: Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
date: 2024-12-23T16:36:31.925Z
updated: 2024-12-25T16:19:39.908Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
excerpt: This Article Describes Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
thumbnail: https://thmb.techidaily.com/e4e90e7c9acadc523d8e4202425b18a9d8056d3f1cd618361a73d2cd13f94e4f.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://fox-cloud.techidaily.com/new-enhance-your-images-with-focus-effects/"><u>[New] Enhance Your Images with Focus Effects</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-from-viral-beats-to-ringtones-transforming-tiktok-sounds-for-2024/"><u>[New] From Viral Beats to Ringtones Transforming TikTok Sounds for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-assessing-the-full-video-range-within-a-64128gb-memory-pool-for-2024/"><u>[Updated] Assessing the Full Video Range Within a 64/128GB Memory Pool for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-large-file-sharing-iphone-to-mac-streamlined-guide/"><u>Effortless Large File Sharing IPhone to Mac Streamlined Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204948165-fortnite-troubleshooting-launch-success/"><u>Fortnite Troubleshooting: Launch Success!</u></a></li>
<li><a href="https://common-error.techidaily.com/hosted-network-troubleshooting-successfully-resolved-for-windows-11-users/"><u>Hosted Network Troubleshooting Successfully Resolved for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hotkey-hack-innovative-text-pasting-shortcuts/"><u>Hotkey Hack: Innovative Text Pasting Shortcuts</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-unresponsive-numeric-keys-on-a-computer-keyboard/"><u>How to Repair Unresponsive Numeric Keys on a Computer Keyboard</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-premier-collection-of-popular-mobile-alert-melodies/"><u>In 2024, Premier Collection of Popular Mobile Alert Melodies</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-startup-struggles-break-free-from-constant-restarts-in-windows-1110/"><u>Overcome Startup Struggles: Break Free From Constant Restarts in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-connectivity-hurdles-a-thorough-guide-to-diagnosing-and-fixing-nat-types/"><u>PS4 Connectivity Hurdles? A Thorough Guide to Diagnosing & Fixing NAT Types</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204042973-quick-fixes-for-defective-usb-connections-expert-tips/"><u>Quick Fixes for Defective USB Connections - Expert Tips!</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-oppo-reno-11-pro-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unable-to-reach-file-location-in-windows-error-quickly/"><u>Resolving 'Unable to Reach File Location in Windows' Error Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-stuck-keys-on-your-windows-pc-comprehensive-fixes-inside/"><u>Reviving Stuck Keys on Your Windows PC - Comprehensive Fixes Inside</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-review-comprehensive-guide-to-top-hardware-picks/"><u>Tom's Tech Review: Comprehensive Guide to Top Hardware Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-making-your-lenovo-mouse-pad-work-again-on-pcs-with-windows-1187-operating-systems/"><u>Ultimate Guide: Making Your Lenovo Mouse Pad Work Again on PCs with Windows 11/8/7 Operating Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-vibrant-visuals-with-post-color-techniques-for-2024/"><u>Unlocking Vibrant Visuals with Post-Color Techniques for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-is-my-iphone-display-sticking-around-troubleshoot-and-fix-now/"><u>Why Is My iPhone Display Sticking Around? Troubleshoot & Fix Now!</u></a></li>
</ul></div>

