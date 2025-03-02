---
title: How to Tackle and Solve the Frustrating 0X80073712 Error Code in Windows 11
date: 2025-02-26T22:56:07.659Z
updated: 2025-03-01T23:42:31.836Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Tackle and Solve the Frustrating 0X80073712 Error Code in Windows 11
excerpt: This Article Describes How to Tackle and Solve the Frustrating 0X80073712 Error Code in Windows 11
thumbnail: https://thmb.techidaily.com/25dfc703be5473423edfc66113d30469d26da4408f6261979d298982619597ae.jpg
---

## Overcome the 0X80073712 Error in Windows 10: Tips and Tricks for a Smooth Operating Experience

If you got a **0x80073712** error code in the midst of a Windows update, don’t panic. Here’re 5 fixes that have helped other users resolve the error. So read on and check them out…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 You may not have to try all these fixes; just work your way down the list until the problem goes away.

1. **[Run Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the SFC scan](https://tools.techidaily.com/drivereasy/download/)**
3. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
4. **[Delete Windows Update Cache](https://tools.techidaily.com/drivereasy/download/)**
5. **[Use Media Creation Tool to have a clean installation of Windows 10](https://tools.techidaily.com/drivereasy/download/)**
6. [**Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### Fix 1: Run Windows Update Troubleshooter

**Windows Update Troubleshooter**   is a useful troubleshooting tool that helps us solve common Windows update issues. Here’s how to run Troubleshooter:

 1) On your keyboard, press   **the Windows logo key  ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**   and type **troubleshoot** , then click **Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30a29f39ffd.jpg)

 2) Click **Windows Update**   \> **Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30a523037e9.jpg)

3) Follow the on-screen instructions to troubleshoot.

4) Restart your computer, try Windows Update again and hopefully this problem has been fixed.

---

### Fix 2: Run the SFC scan

**System File Checker** (**SFC** ) is a handy feature in Windows that helps scan your system files and repair missing or corrupted system files(including those related to **error 0x80073712** ). To **run the SFC scan** :

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

 Click **Yes**   when prompted to confirm.

2) In the command prompt window, type **sfc /scannow**   and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28aee247664.jpg)

 It’ll take some time for the SFC to replace the corrupted system files with new ones if it detects any, so please be patient. ?  
 3) Restart your computer and see if the error**0x80073712**   has been solved.

---

### Fix 3: Run **the DISM tool**

**DISM**  (**Deployment Image & Servicing Management** ) is another tool that helps us fix Windows-corruption-caused errors (**0x80073712** in this case). To run **DISM** :

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

 2) Type **the following command**   and press **Enter** :

**DISM.exe /Online /Cleanup-image /Restorehealth**

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30abe4b92d4.jpg)

Wait for a while for the whole process to finishes.
  
 3) Restart your computer and **run the SFC** (see**Fix 2** ) again so it will help you replace any corrupted files with the correct ones.

 4) Check Windows Update and see if it works this time.

---

### Fix 4: Delete Windows Update Cache

 Deleting Windows Update Cache is another useful method to help us fix the **0x80073712** error code. Here’s how:

 1) On your keyboard, press the **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**   and **R**   at the same time. Then copy & paste **services.msc**   into the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b220b691f96a.png)

 2) Scroll down to the bottom, right-click on **Windows Update**  . Then click**Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b45a89c68a29.jpg)

 3) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**   and **R**   at the same time, then copy & paste **C:\\Windows\\SoftwareDistribution\\Download** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b45a92deb7fc.png)

 4) Press**Ctrl** and**A** at the same time, then right-click to pop up a menu and click**Delete** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b45a98e3f0f6.jpg)

 5) When asked to provide administrator permission, check**the box** before**Do this for all current items** and click**Continue** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b45ab04cd2f7.png)

 6) Back to the**Services** window, right-click on**Windows Update** and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b45ac06c5a8a.jpg)

 7) Restart your computer and try the Windows update again to see if the error code disappears.

### Fix 5: Use **Media Creation Tool** to have a clean installation of Windows 10

 If all else fails, and_that_ Windows update is too important to miss, then you might consider using **Media Creation Tool** for a clean installation of Windows 10\. You can click[here](https://www.microsoft.com/en-us/software-download/windows10) for reference and proceed with caution.

 After that, check if the**0x80073712** error code problem has been sorted.

---

### Fix 6: Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**   (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

---

 That’s it – top 5 fixes for your **0x80073712** error code in Windows 10\. Hope this helps and feel free to comment below if you have any further questions. 🙂

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-beginners-guide-to-av1-codec/"><u>[New] 2024 Approved Beginner's Guide to AV1 Codec</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-universal-method-for-screen-recording-across-systems/"><u>[New] Universal Method for Screen Recording Across Systems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-learn-the-procedure-for-automatic-video-broadcasting-on-facebook/"><u>[Updated] Learn the Procedure for Automatic Video Broadcasting on Facebook</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-perfect-phone-match-up-for-samsungs-virtual-reality-dreams-update-2023/"><u>2024 Approved Perfect Phone Match-Up for Samsung's Virtual Reality Dreams - Update 2023</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unlocking-instagram-memories-with-these-apps/"><u>2024 Approved Unlocking Instagram Memories with These Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-restricted-input-settings-for-touchscreens-and-pen-devices/"><u>Bypassing the Restricted Input Settings for Touchscreens and Pen Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-dvd-playback-problems-on-windows-machines/"><u>Diagnosing and Repairing DVD Playback Problems on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-strategies-for-fixing-your-lenovo-fn-key-without-delay/"><u>Efficient Strategies for Fixing Your Lenovo Fn Key Without Delay</u></a></li>
<li><a href="https://common-error.techidaily.com/error-800020-during-windows-11-installation-understanding-and-solutions-for-a-smooth-update/"><u>Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-fixing-unresponsive-integrated-cameras-in-windows-environments/"><u>Expert Advice: Fixing Unresponsive Integrated Cameras in Windows Environments</u></a></li>
<li><a href="https://win-best.techidaily.com/how-to-fix-when-scanners-wont-link-up-to-your-laptop-or-desktop-tips-from-yl-software-experts/"><u>How to Fix When Scanners Won't Link Up to Your Laptop or Desktop – Tips From YL Software Experts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-vivo-y78-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Vivo Y78 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-media-player-settings-for-smooth-playback/"><u>Optimizing Media Player Settings for Smooth Playback</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-excessive-energy-flow-in-data-hub-connectors/"><u>Troubleshooting Excessive Energy Flow in Data Hub Connectors</u></a></li>
</ul></div>

