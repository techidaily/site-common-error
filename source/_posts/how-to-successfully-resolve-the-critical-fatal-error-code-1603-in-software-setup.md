---
title: How to Successfully Resolve the Critical Fatal Error (Code 1603) in Software Setup
date: 2025-01-08T23:50:46.767Z
updated: 2025-01-10T23:20:31.734Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Resolve the Critical Fatal Error (Code 1603) in Software Setup
excerpt: This Article Describes How to Successfully Resolve the Critical Fatal Error (Code 1603) in Software Setup
thumbnail: https://thmb.techidaily.com/d4a38ebeef7fcde8439a2a50391d7bd9b46cb2287710359624ae1485aff3b993.jpg
---

## Master the Fix: Successful Steps to Resolve Error Code 1 # New Best SEO Titles for Google Search - Fatal Installer Glitch (Error 1603) Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca1709cae9.png)

You may encounter an error with a code of **1603** when you are attempting to install something on your Windows. The error message is basically something like “**Error: -1603 Fatal error during installation.**” It usually occurs when you are using a Windows Installer package to install the program. You can try the methods below that can be help you fix the error. **1)[Change installation location](https://tools.techidaily.com/drivereasy/download/)**   **2) [Completely uninstall the same program installed](https://tools.techidaily.com/drivereasy/download/)**   **3)[Start and re-register Microsoft Installer service](https://tools.techidaily.com/drivereasy/download/)**   **4)[Acquire full permissions on the drive for installation](https://tools.techidaily.com/drivereasy/download/)**

## 1) Change installation location

You may encounter an error 1603 because the installation location is you choose is not available due to various reasons — such as being encrypted. You can use another installation folder to install the program and see if the error is gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2) Completely uninstall the same program installed

If you have previously installed the same program (or its earlier version), the error can occur when you try to install the application again. If you want to install your program successfully, you need to perform a **clean uninstall** of the one installed on your computer. This means you need to remove all the temporary files and preferences it leaves in addition to the major program. Sometimes you may lose the desktop shortcut of a program due to some reasons and therefore you may forget that you have installed it. In this case you can go to**Control Panel**to check if it is still on your computer: Press**Win + R**, and enter “ _**control**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9bf012d25.png)

Find and open**Programs and Features**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9c81105c5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then you can check if the application is listed here. If it is, uninstall it.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9d00544d7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3) Start and re-register Microsoft Installer service

There may be something going wrong with**Microsoft Installer service**and therefore resulting in error 1603\. You can fix the problem by (re)starting and re-registering Microsoft Installer service. To**start**Windows Installer service:**a)** Press**Win + R**and enter “_**services.msc**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca68fd8714.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**b)** Find and double click on**Windows Installer**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca70c399c1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**c)** Hit**Start**button under**Service status**and hit**OK**. (If its service status is**running**, you should click on**Stop**first and then hit**Start**.)

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca7cbbdf36.png)

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

**h)** Do the same operation above for**SYSTEM**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb8202ef5a.png)

**i)** Click on**OK** all the way out. Now you have acquired full permissions on this drive. Try installing your application and see if the issue is fixed.

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
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-prime-streaming-platforms-for-authors/"><u>[Updated] 2024 Approved Prime Streaming Platforms for Authors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-for-broadcasting-is-obs-superior-to-twitch-studio-in-2024/"><u>[Updated] Best for Broadcasting Is OBS Superior to Twitch Studio, In 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cutting-and-compositing-for-youtube-videos-using-premiere-pro-for-2024/"><u>[Updated] Cutting and Compositing for YouTube Videos Using Premiere Pro for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-professional-guidelines-for-text-overlays-vimeo-for-2024/"><u>[Updated] Professional Guidelines for Text Overlays (Vimeo) for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-power-surge-errors-on-networking-hubs/"><u>Diagnosing and Repairing Power Surge Errors on Networking Hubs</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-responsive-dvd-and-cd-players-in-the-windows-operating-system/"><u>Fixing Non-Responsive DVD and CD Players in the Windows Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-problem-of-sticky-keys-in-windows-a-step-by-step-guide/"><u>Fixing the Problem of Sticky Keys in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208196024-hidden-sd-card-reveal-and-repair-steps/"><u>Hidden SD Card? Reveal & Repair Steps</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-tecno-spark-10-4g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Tecno Spark 10 4G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-hurdle-of-windows-11-installation-error-80240020-a-comprehensive-fix/"><u>Overcoming the Hurdle of Windows 11 Installation Error 80240020 - A Comprehensive Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-typographic-hurdles-resolving-spacebar-problems-on-windows-11-systems/"><u>Overcoming Typographic Hurdles - Resolving Spacebar Problems on Windows 11 Systems</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/s-most-popular-video-editing-apps-for-iphone-and-ipad/"><u>S Most Popular Video Editing Apps for iPhone and iPad</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-troubleshooting-guide-for-stalled-torrent-downloads/"><u>The Ultimate Troubleshooting Guide for Stalled Torrent Downloads</u></a></li>
</ul></div>

