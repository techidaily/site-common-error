---
title: Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
date: 2024-12-20T20:27:15.601Z
updated: 2024-12-25T17:33:53.735Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
excerpt: This Article Describes Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
thumbnail: https://thmb.techidaily.com/63775cec08bea1f18045b716f908366237290c85d227f82f60742199283d96d9.jpg
---

## Unraveling the Mystery Behind .NET Framework 3.5'S Error Code 0X800F081F - Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Configure Group Policy

 The 0x800F081F error may occur because the component setting in Group Policy is disabled. You should enable it to see if this fixes the error. To do so:

**1)** On your keyboard, press the   **Windows logo key![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png)**  and**R** **key** at the same time to invoke the Run box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**2)**  Type “**gpedit.msc** ” and press**Enter** on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b46182da0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)**  Go to **Computer Configuration -> Administrative Templates -> System** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b4b628c80.jpg)

**4)** Double click **Specify settings for optional component installation and component repair** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cb90d9ace.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**5)** Select**Enabled** . Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cd1538e66.jpg)

**6)** Try installing .NET Framework 3.5\. If this method works for you, you won’t see the error again. Otherwise, you should try the method below.

## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

**5)**  Try installing .NET Framework 3.5 and see if the error disappears.

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
<li><a href="https://vp-tips.techidaily.com/new-continuous-rotation-vs-3d-image-construction-for-2024/"><u>[New] Continuous Rotation vs 3D Image Construction for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-mastering-video-playback-rate-adjustments-in-snapchat/"><u>[New] Mastering Video Playback Rate Adjustments in Snapchat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-mastering-windows-animation-top-9-apps-for-high-quality-gif-capture/"><u>[New] Mastering Windows Animation Top 9 Apps for High-Quality GIF Capture</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-methods-of-acquiring-ipodcasts-for-your-iphone/"><u>[New] The Ultimate Methods of Acquiring IPodcasts for Your iPhone</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-pubg-cannot-find-dxgidll-error/"><u>[Solved] PUBG Cannot Find dxgi.dll Error</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-pioneering-your-path-in-youtube-livestreams-on-mobiles/"><u>[Updated] In 2024, Pioneering Your Path in YouTube Livestreams on Mobiles</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-oppo-reno-9a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-broken-volume-controls-in-windows-10-solved/"><u>Effective Fixes for Broken Volume Controls in Windows 10 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-correct-user-profile-service-failure-on-windows-11-machines/"><u>Effective Solutions to Correct 'User Profile Service' Failure on Windows 11 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unsupported-graphics-cards-on-fortnite-windows-pc/"><u>How to Fix Unsupported Graphics Cards on Fortnite Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-critical-imaging-errors-in-your-windows-11-or-10-pc/"><u>How to Overcome Critical Imaging Errors in Your Windows 11 or 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-a-stuck-windows-10-update-process-expert-tips-and-tricks/"><u>How to Resolve a Stuck Windows 10 Update Process – Expert Tips & Tricks</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s24-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Samsung Galaxy S24 Phone Without Password?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-insight-into-the-finest-iphone-tools-for-image-watermarks/"><u>In 2024, Insight Into the Finest iPhone Tools for Image Watermarks</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-youtube-audio-issues-on-windows-11-a-comprehensive-guide/"><u>Resolve YouTube Audio Issues on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/the-art-of-incorporating-b-roll-in-video-production/"><u>The Art of Incorporating B Roll in Video Production</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-successfully-loading-sites-in-safari-when-problems-arise/"><u>Troubleshooting Guide: Successfully Loading Sites in Safari When Problems Arise</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-fixing-the-issue-when-windows-key-plus-shift-plus-s-is-unresponsive-on-windows-11-or-10/"><u>Troubleshooting Steps: Fixing the Issue When Windows Key + Shift + S Is Unresponsive on Windows 11 or 10</u></a></li>
</ul></div>

