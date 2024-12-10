---
title: "Troubleshooting Guide: When Microsoft's Wireless Display Stick Fails to Link Up With Windows 10 Systems"
date: 2024-12-05T22:44:49.379Z
updated: 2024-12-10T22:53:48.069Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: When Microsoft's Wireless Display Stick Fails to Link Up With Windows 10 Systems"
excerpt: "This Article Describes Troubleshooting Guide: When Microsoft's Wireless Display Stick Fails to Link Up With Windows 10 Systems"
thumbnail: https://thmb.techidaily.com/70c37a7401073f1bcbf47eb7a020f3d12c21a20e9f862ecf54abef66ad7c8a53.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

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
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-customizing-teams-background-priorpost-meeting/"><u>[Updated] In 2024, Customizing Teams Background Prior/Post-Meeting</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-discover-the-secrets-to-customizing-game-sounds-with-our-step-by-step-process-no-charge/"><u>2024 Approved Discover the Secrets to Customizing Game Sounds with Our Step-by-Step Process (No Charge!)</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-by-step-zoom-livestream-setup-guide-for-youtube-enthusiasts/"><u>2024 Approved Step-by-Step Zoom Livestream Setup Guide for YouTube Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211218181-address-counterarguments-eg-some-may-argue-that-other-qualities-are-more-important-for-professional-success-and-rebut-them-with-convincing-evidence/"><u>Address Counterarguments (E.g., some May Argue that Other Qualities Are More Important for Professional Success) and Rebut Them with Convincing Evidence</u></a></li>
<li><a href="https://win-net.techidaily.com/complete-guide-to-saving-your-data-using-the-windows-control-panel/"><u>Complete Guide to Saving Your Data: Using the Windows Control Panel</u></a></li>
<li><a href="https://win-exclusive.techidaily.com/erstellen-von-sicherungsdateien-auf-einer-externen-festplatte-mit-zwei-methoden-bei-synology-nas-systems/"><u>Erstellen Von Sicherungsdateien Auf Einer Externen Festplatte Mit Zwei Methoden Bei Synology NAS Systems</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-reasons-behind-the-triumph-of-nintendos-wii-u/"><u>Exploring the Reasons Behind the Triumph of Nintendo's Wii U</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-oppo-find-x6-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-lenovo-laptops-video-camera-back-to-working-order-tips-and-tricks/"><u>Getting Your Lenovo Laptop's Video Camera Back to Working Order: Tips & Tricks</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-iphone-14-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and iPhone 14 without Apple Account</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-simplify-multitasking-on-iphone-activatedeactivate-youtubes-pip-feature/"><u>In 2024, Simplify Multitasking on iPhone Activate/Deactivate YouTube's PIP Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-functions-intermittently/"><u>Keyboard Functions Intermittently</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-how-to-resolve-dns-server-not-responding-issues/"><u>Quick Solutions: How to Resolve 'DNS Server Not Responding' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-resource-protection-error-resolution-steps/"><u>Troubleshooting 'Windows Resource Protection' Error: Resolution Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-a-non-charging-playstation-4-controller/"><u>Troubleshooting Tips for a Non-Charging PlayStation 4 Controller</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-system-cant-find-a-required-module/"><u>Troubleshooting When Your System Can’t Find a Required Module</u></a></li>
<li><a href="https://common-error.techidaily.com/verify-organization-level-settings-enforcement-on-your-windows-machine/"><u>Verify Organization-Level Settings Enforcement on Your Windows Machine</u></a></li>
</ul></div>

