---
title: Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines
date: 2024-09-04T20:22:02.572Z
updated: 2024-09-05T20:22:02.572Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines
excerpt: This Article Describes Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines
thumbnail: https://thmb.techidaily.com/414457a7bef8541a22e0759e005db32e7bc53d10e956cf3519881385b0e0955c.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030385/7443" target="_top" id="2030385">
  <img src="//a.impactradius-go.com/display-ad/7443-2030385" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030385/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-channel-marketing-making-a-trailer-that-sells-more/"><u>[New] 2024 Approved  Channel Marketing  Making a Trailer that Sells More</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-protocols-for-preserving-instagram-footage-on-windowsmacos-platforms/"><u>[New] 2024 Approved  Protocols for Preserving Instagram Footage on Windows/macOS Platforms</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-uncover-recent-instagram-unfollow-patterns/"><u>[New] 2024 Approved  Uncover Recent Instagram Unfollow Patterns</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-4k-clarity-redefined-an-intensive-overview-of-the-dell-p2715q-screen/"><u>[New] 4K Clarity Redefined  An Intensive Overview of the Dell P2715Q Screen</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-stepwise-guide-to-convert-vimeo-media-to-mp3/"><u>[New] In 2024, Stepwise Guide to Convert Vimeo Media to MP3</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unleash-potential-creating-a-youtube-channel-that-shines-in-games/"><u>[New] Unleash Potential  Creating a YouTube Channel that Shines in Games</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-cutting-edge-techniques-for-audience-engagement-on-twitch/"><u>2024 Approved  Cutting-Edge Techniques for Audience Engagement on Twitch</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-the-full-laptop-screencapture-experience/"><u>2024 Approved  The Full Laptop ScreenCapture Experience</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleashing-wit-within-walls-a-guide-to-crafting-metaverse-jokes/"><u>2024 Approved  Unleashing Wit Within Walls – A Guide to Crafting Metaverse Jokes</u></a></li>
<li><a href="https://common-error.techidaily.com/advanced-users-demand-missing-visual-tools-return/"><u>Advanced Users Demand Missing Visual Tools Return</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/all-about-apple-iphone-8-unlock-chip-you-need-to-know-by-drfone-ios/"><u>All About Apple iPhone 8 Unlock Chip You Need to Know</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212213016-avoid-upgrade-headaches-with-this-guide-to-fixing-the-0x80070002-windows-update-error/"><u>Avoid Upgrade Headaches with This Guide to Fixing the 0X80070002 Windows Update Error</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-to-resolving-game-crashes-in-total-war-rome-remastered/"><u>Complete Guide to Resolving Game Crashes in Total War: Rome Remastered</u></a></li>
<li><a href="https://common-error.techidaily.com/computer-conundrum-why-does-gaming-halt/"><u>Computer Conundrum: Why Does Gaming Halt?</u></a></li>
<li><a href="https://common-error.techidaily.com/enhancing-system-efficiency-by-correcting-windows-driver-foundation-and-minimizing-cpu-load/"><u>Enhancing System Efficiency by Correcting Windows Driver Foundation and Minimizing CPU Load</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212531349-error-on-your-origin-game-follow-these-steps-to-correct-the-setup-and-enjoy/"><u>Error on Your Origin Game? Follow These Steps to Correct the Setup & Enjoy</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-and-troubleshoot-unresponsive-touchpad-scrolling-issues-resolved/"><u>Fix & Troubleshoot: Unresponsive Touchpad Scrolling Issues Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-malfunctioning-alphabetic-keys-in-microsoft-windows-1er-11-environment/"><u>Fix Malfunctioning Alphabetic Keys in Microsoft Windows 1Er 11 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-unsupported-platform-detected-error-while-installing-your-intel-serial-io-driver/"><u>Fixing the 'Unsupported Platform Detected' Error While Installing Your Intel Serial IO Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-touchpad-back-to-work-fixing-scroll-issues-under-windows-10/"><u>Get Your Touchpad Back to Work: Fixing Scroll Issues Under Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-usb-device-unrecognized-error-a-step-by-step-guide/"><u>How to Fix 'USB Device Unrecognized' Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-make-the-most-of-your-iphone-x-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>How to Make the Most of Your iPhone X Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-14-pro-max-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 14 Pro Max Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-vivo-x100-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Vivo X100 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-se-2020-online-here-are-6-easy-ways-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone SE (2020) Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-inviolable-tactic-to-eliminate-youtube-shorts/"><u>In 2024, Inviolable Tactic to Eliminate YouTube Shorts</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-one-minute-color-magic/"><u>In 2024, One Minute Color Magic</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-the-photographers-pathway-transitioning-from-camera-to-computer-screen/"><u>In 2024, The Photographer's Pathway  Transitioning From Camera to Computer Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/instantly-fix-solve-no-battery-found-error-with-simple-steps/"><u>Instantly Fix: Solve 'No Battery Found' Error with Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-with-windows-11-version-1607-upgrade-failed-update-and-possible-solutions/"><u>Issue with Windows 11 Version 1607 Upgrade: Failed Update and Possible Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-touchpad-not-responding-heres-the-definitive-fix-for-windows-users/"><u>Lenovo Touchpad Not Responding? Here's the Definitive Fix for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-connection-settings-to-enable-smooth-access-to-party-chat-services/"><u>Mastering Connection Settings to Enable Smooth Access to Party Chat Services</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209634368-mastering-the-art-of-fixing-ps4-microphone-failures-top-strategies-inside/"><u>Mastering the Art of Fixing PS4 Microphone Failures – Top Strategies Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-solution-eliminate-your-pcs-pitch-black-predicament-on-windows-11/"><u>Mastering the Solution: Eliminate Your PC's Pitch-Black Predicament on Windows 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-6s-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone 6s to Android | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/next-level-computing-with-a-twist-discover-the-astonishing-features-and-subtle-quirks-in-our-review-of-the-latest-dell-xps-models-16-9640-and-14-9440/"><u>Next-Level Computing with a Twist: Discover the Astonishing Features & Subtle Quirks in Our Review of the Latest Dell XPS Models - 16 (9640) and 14 (9440)</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-pause-predicament-in-gameplay-ease/"><u>Overcome Pause Predicament in Gameplay Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-challenges-when-your-networks-dhcp-server-is-unreachable/"><u>Overcoming Challenges When Your Network's DHCP Server Is Unreachable</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-windows-11-screen-saver-feature-step-by-step-troubleshooting-guide/"><u>Revive Your Windows 11 Screen Saver Feature - Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sierra-edition-selecting-top-video-editing-software-on-mac-for-2024/"><u>Sierra Edition  Selecting Top Video Editing Software on Mac for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-headphone-woes-dealing-with-logitech-g930-outages/"><u>Solve Your Headphone Woes: Dealing with Logitech G930 Outages</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205856724-solved-couldnt-load-plugin-chrome-error-on-windows-10/"><u>Solved: Couldn't Load Plugin Chrome Error on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-overcome-mycopg-lan-gameplay-challenges-for-seamless-online-gaming/"><u>Steps to Overcome Mycopg LAN Gameplay Challenges for Seamless Online Gaming</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-asus-rog-phone-7-ultimate-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Asus ROG Phone 7 Ultimate for Streaming | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-repairing-a-malfunctioning-touch-screen-on-windows-10/"><u>Top 5 Solutions for Repairing a Malfunctioning Touch Screen on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-corrective-steps-for-damaged-windows-marketplace-cache-files/"><u>Troubleshooting and Corrective Steps for Damaged Windows Marketplace Cache Files</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-popscrackling-sounds-on-your-speakers-for-win-10-or-7/"><u>Troubleshooting and Fixing Pops/Crackling Sounds on Your Speakers for Win 10 or 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-sign-in-issues-user-profile-service-errors-in-windows/"><u>Troubleshooting Sign-In Issues: User Profile Service Errors in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-why-windows-10-cant-find-your-bluetooth-gadgets-and-how-to-fix-it/"><u>Troubleshooting: Why Windows 10 Can't Find Your Bluetooth Gadgets and How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solution-for-unresponsive-computers-step-by-step-fixes/"><u>Ultimate Solution for Unresponsive Computers – Step-by-Step Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-input-hiatus/"><u>Unexpected Input Hiatus</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-bluetooth-capabilities-on-windows-7-easy-fixes-for-users/"><u>Unlocking Bluetooth Capabilities on Windows 7: Easy Fixes for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/unstick-a-frozen-overwatch-voice-chat-steps-for-instant-resolution/"><u>Unstick a Frozen Overwatch Voice Chat: Steps for Instant Resolution</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-unresponsive-file-explorer-tips-for-windows-11-users/"><u>Winning the Battle Against Unresponsive File Explorer: Tips for Windows 11 Users</u></a></li>
</ul></div>
