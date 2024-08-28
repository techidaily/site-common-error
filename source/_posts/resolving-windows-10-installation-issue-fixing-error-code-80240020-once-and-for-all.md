---
title: "Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All"
date: 2024-08-27T13:44:19.907Z
updated: 2024-08-28T13:44:19.907Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All"
excerpt: "This Article Describes Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All"
thumbnail: https://thmb.techidaily.com/cb7e01d77e11396989975642eff6b3a0f5621896796311364cd34b031c122e69.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-recording.techidaily.com/new-eliminating-half-muted-facebook-gaming-videos-2023-fixes-for-2024/"><u>[New] Eliminating Half-Muted Facebook Gaming Videos (2023 Fixes) for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-best-practices-for-creating-compelling-hash-tags-on-facebook/"><u>[New] In 2024, Best Practices for Creating Compelling Hash Tags on Facebook</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-unlocking-data-movement-best-ways-to-transition-files-to-pc/"><u>[New] In 2024, Unlocking Data Movement  Best Ways to Transition Files to PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-easytime-timer-solutions-at-zero-cost/"><u>[New] Top EasyTime Timer Solutions at Zero Cost</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-teredo-is-unable-to-qualify/"><u>[SOLVED] Teredo Is Unable to Qualify</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-z2-play-analysis-next-gen-tech-insights/"><u>[Updated] 2024 Approved  Z2 Play Analysis  Next-Gen Tech Insights</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-highpoint-design-suite-examination/"><u>[Updated] Highpoint Design Suite Examination</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-explore-google-meets-full-potential-free-edition/"><u>[Updated] In 2024, Explore Google Meet's Full Potential (Free Edition)</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-funfactory-enjoy-video-making-with-ease/"><u>[Updated] In 2024, FunFactory  Enjoy Video Making with Ease</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-reinventing-speech-the-ultimate-guide-to-free-vocal-adjustments/"><u>[Updated] In 2024, Reinventing Speech  The Ultimate Guide to Free Vocal Adjustments</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-online-facebook-video-to-mp3-converters-how-to-convert-fb-to-mp3-in-2024/"><u>[Updated] Online Facebook Video to MP3 Converters | How to Convert FB to MP3, In 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-perfecting-your-youtube-music-order/"><u>[Updated] Perfecting Your YouTube Music Order</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-social-media-streamlining-iphoneandroid-tips-for-effective-feeds-for-2024/"><u>[Updated] Social Media Streamlining  IPhone/Android Tips for Effective Feeds for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-mastering-the-art-of-finding-cost-effective-graphics/"><u>2024 Approved  Mastering the Art of Finding Cost-Effective Graphics</u></a></li>
<li><a href="https://common-error.techidaily.com/argue-how-problem-solving-leads-to-creative-thinking-innovation-and-progress-in-various-fields-eg-technology-medicine/"><u>Argue How Problem-Solving Leads to Creative Thinking, Innovation, and Progress in Various Fields (E.g., Technology, Medicine)</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-the-shadows-effective-fixes-for-black-screens-on-google-chrome/"><u>Banish the Shadows: Effective Fixes for Black Screens on Google Chrome</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-youtube-entrance-videos-with-the-top-tools-for-2024/"><u>Crafting YouTube Entrance Videos with the Top Tools for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-for-repairing-unrecognized-external-hard-drives-in-windows-1087/"><u>Easy Steps for Repairing Unrecognized External Hard Drives in Windows 10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x802n200d-on-windows-update-a-detailed-solution-guide-to-restore-functionality/"><u>Error 0X802n200d on Windows Update: A Detailed Solution Guide to Restore Functionality</u></a></li>
<li><a href="https://buynow-help.techidaily.com/first-impressions-of-samsungs-latest-earbuds-the-galaxy-budsplus/"><u>First Impressions of Samsung's Latest Earbuds - The Galaxy Buds+</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205996325-fix-error-there-is-a-problem-with-your-games-setup-origin-games/"><u>Fix Error “There Is a Problem with Your Game’s Setup” | Origin Games</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-comprehensive-guide-to-address-d3dx939dll-missing-errors-effectively/"><u>Fixed: Comprehensive Guide to Address d3dx9_39.dll Missing Errors Effectively</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-proof-your-enterprise-5-vital-ai-applications-every-savvy-entrepreneur-should-master/"><u>Future-Proof Your Enterprise: 5 Vital AI Applications Every Savvy Entrepreneur Should Master</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-oneplus-nord-3-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change OnePlus Nord 3 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-and-understand-the-windows-update-error-0x80aturational-impact-of-media-on-children/"><u>How to Fix and Understand the Windows Update Error 0X80aturational Impact of Media on Children</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-set-user-settings-to-driver-failed-issue-a-step-by-step-guide/"><u>How to Overcome the 'Set User Settings To Driver Failed' Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-5-best-live-streaming-software-for-mac-you-must-know/"><u>In 2024, 5 Best Live Streaming Software for Mac You Must Know</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-oppo-a58-4g-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Oppo A58 4G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-iphone-7-plus-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From iPhone 7 Plus</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-startup-issues-how-to-fix-the-critical-error-0xc000007b/"><u>Mastering Startup Issues - How to Fix the Critical Error 0Xc000007b</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-recovery-of-windows-10-sound-settings-and-volume-buttons/"><u>Mastering the Recovery of Windows 10 Sound Settings and Volume Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-elevated-permission-issues-for-task-execution-on-windows-11-10-and-7/"><u>Overcoming Elevated Permission Issues for Task Execution on Windows 11, 10 and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-ethernet-challenges-a-users-manual-for-windows-10-and-7-users/"><u>Overcoming Ethernet Challenges: A User's Manual for Windows 10 & 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-destiny-srevz-nt-aevalebe-1ssuz-the-ultimate-troubleshooting-guide/"><u>Resolve Destiny ˈsɪrəvz Nɑt ˌævaɪləbəɫ 1Ssuːz: The Ultimate Troubleshooting Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-writing-failure-in-the-referenced-0xmemory-address/"><u>Resolved: Writing Failure in the Referenced 0xMemory Address</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-diagnostics-policy-service-is-offline-heres-what-to-do/"><u>Resolving 'Diagnostics Policy Service Is Offline – Here’s What To Do!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-update-error-code-802-a-comprehensive-guide/"><u>Resolving Windows Update Error Code 802#: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-to-resolve-the-http-error-503-service-temporarily-unavailable/"><u>Simple Solutions to Resolve the 'HTTP Error 503: Service Temporarily Unavailable'</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-0x80070643-issue-tips-and-tricks-for-smooth-windows-updates/"><u>Solving the 0X80070643 Issue: Tips and Tricks for Smooth Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-user-profile-service-failure-during-login-on-windows-1011/"><u>Solving User Profile Service Failure During Login on Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-getting-your-dell-camera-up-and-running-in-windows/"><u>Step-by-Step Guide: Getting Your Dell Camera Up and Running in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-when-your-diagnostics-policy-service-wont-start-up/"><u>The Ultimate Fix for When Your Diagnostics Policy Service Won’t Start Up</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-frozen-screen-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting a Frozen Screen on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-hp-laptop-webcam-issues-in-windows-11/"><u>Troubleshooting Guide: Resolving HP Laptop Webcam Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-restoring-usb-peripherals-mouse-keyboard-on-windows-woody/"><u>Troubleshooting Steps for Restoring USB Peripherals (Mouse, Keyboard) on Windows Woody</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy S24+ | Dr.fone</u></a></li>
</ul></div>
