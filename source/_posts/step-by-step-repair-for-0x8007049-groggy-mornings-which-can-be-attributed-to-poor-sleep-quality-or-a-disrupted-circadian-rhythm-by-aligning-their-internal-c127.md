---
title: Step-by-Step Repair for 0X8007049 Groggy Mornings, Which Can Be Attributed to Poor Sleep Quality or a Disrupted Circadian Rhythm. By Aligning Their Internal Clocks with Natural Light Exposure and Regulating Melatonin Secretion Through Timely Darkness, Individuals Can Improve Overall Sleep Patterns and Reduce Fatigue
date: 2024-08-08 15:56:37
updated: 2024-08-09 10:19:41
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Repair for 0X8007049 Groggy Mornings, Which Can Be Attributed to Poor Sleep Quality or a Disrupted Circadian Rhythm. By Aligning Their Internal Clocks with Natural Light Exposure and Regulating Melatonin Secretion Through Timely Darkness, Individuals Can Improve Overall Sleep Patterns and Reduce Fatigue
excerpt: This Article Describes Step-by-Step Repair for 0X8007049 Groggy Mornings, Which Can Be Attributed to Poor Sleep Quality or a Disrupted Circadian Rhythm. By Aligning Their Internal Clocks with Natural Light Exposure and Regulating Melatonin Secretion Through Timely Darkness, Individuals Can Improve Overall Sleep Patterns and Reduce Fatigue
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

## Step-by-Step Repair for 0X8007049 Groggy Mornings, Which Can Be Attributed to Poor Sleep Quality or a Disrupted Circadian Rhythm. By Aligning Their Internal Clocks with Natural Light Exposure and Regulating Melatonin Secretion Through Timely Darkness, Individuals Can Improve Overall Sleep Patterns and Reduce Fatigue

If you are met with Windows **0x80070490** error, don’t panic. It’s often not hard to fix at all…

## What you might want to know about **0x80070490**

 The **0x80070490** error mostly happens when users are doing a Windows update, upgrading their Windows system, or trying to purchase/install an app from Windows Store. It can be due to  misconfigured system files, a virus or adware/spyware attack etc.

## Try these fixes

 All the fixes below work in**Windows 10** . You may not have to try all of them; just work your way down the list until the error goes away:

1. **[Run Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the SFC scan](https://tools.techidaily.com/drivereasy/download/)**
3. **[Run DISM](https://tools.techidaily.com/drivereasy/download/)**
4. **[Reset the Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
5. [**Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### Fix 1: Run Windows Update Troubleshooter

**Windows Update Troubleshooter** is a useful troubleshooting tool that helps us solve update issues. Here’s how to run Troubleshooter:

 1) On your keyboard, press **the Windows logo key  ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type**troubleshoot** , then click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30a29f39ffd.jpg)

 2) Click**Windows Update** \>**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30a523037e9.jpg)

3) Follow the on-screen instructions to troubleshoot.

4) Restart your computer and see if this has fixed the error.

---

### Fix 2: Run the SFC scan

**System File Checker** (**SFC** ) is a handy feature in Windows that helps scan your system files and repair missing or corrupted system files(including those related to**error 0x80070490** ). To**run the SFC scan** :

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

 Click **Yes**   when prompted to confirm.

2) In the command prompt window, type **sfc /scannow**   and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28aee247664.jpg)

 It’ll take some time for the SFC to replace the corrupted system files with new ones if it detects any, so please be patient. ?  
 3) Restart your computer and see if the error **0x80070490** has been solved.

---

### Fix 3: Run DISM

**DISM**  (**Deployment Image & Servicing Management** ) is another tool that helps us fix Windows-corruption-caused errors (**0x80070490** in this case). To run**DISM** :

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

 2) Type**the following command** and press**Enter** :

**DISM.exe /Online /Cleanup-image /Restorehealth**

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30abe4b92d4.jpg)

Wait a while for the whole process to finish.

 3) Type **sfc /scannow** and press**Enter** .

 4) Restart your computer, perform the update again and see if it works successfully this time.

---

### Fix 4:  Reset the Windows Update components

 The corrupted **Windows Update components** can also be responsible for our error code **0x80070490** . If this is the case, then we might have to reset the components in order to solve the problem. To**reset the Windows Update components** :

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

 2) Type**the following commands** and press **Enter** after each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

 (These commands will stop the services that Windows Update requires to download and install updates.)

 3) Copy & paste **the following commands** and press **Enter** after each:

Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old
Ren %systemroot%\system32\catroot2 catroot2.old

 4) Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:

_**net start bits**_
_**net start wuauserv**_
_**net start appidsvc**_
_**net start cryptsvc**_

 5) Check and see if this has fixed the **0x80070490** error code.

---

### Fix 5: Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**   (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

---

 How have the fixes above helped you with your troubleshooting? Do you have any ideas or tips to share with us? Drop a comment below and let us know your thoughts.

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
