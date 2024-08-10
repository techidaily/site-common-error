---
title: "Troubleshooting WRAP Error: Fixing 'Windows Resource Protection Failed' Issues"
date: 2024-08-09T00:49:47.932Z
updated: 2024-08-10T00:49:47.932Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting WRAP Error: Fixing 'Windows Resource Protection Failed' Issues"
excerpt: "This Article Describes Troubleshooting WRAP Error: Fixing 'Windows Resource Protection Failed' Issues"
thumbnail: https://thmb.techidaily.com/cc47b698f923f727c15f0c1061cbe2a60849e3112495eb0d057b6f746e88f4ee.jpg
---

## Troubleshooting and Repairing 'Windows Can't Reset Your PC' Message – Solved

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-18.jpg)

 This post is going to tell you how to fix **“There was a problem resetting your PC”**  error on your Windows 10\. It may occur when you try to reset your Windows 10 to its default state. Microsoft also noticed such known error. And they have given the following 4 conditions under which your Windows 10 reset may fail. If unluckily you’re also facing such error, please go on with the fixes step by step to solve the error.

**The 4 conditions:**
 ❶ Your PC came with Windows 10 pre-installed, and was not an upgrade from Windows 7 or Windows 8.1.  
 ❷ The PC manufacturer enabled compression to reduce the disk space required for preinstalled applications.  
 ❸ You created a USB recovery drive using the “Create a recovery drive” feature in Windows 10.  
 ❹ You booted the PC to the USB recovery drive and selected, Troubleshoot > Reset this PC > Remove everything.

 **How to fix the error:**
 Click **Close**  icon of the error notification window and go on with the fix below.

**Fix 1.Check your system file**

 1)  

 Click Power button from Start menu.  
 Then while holding **Shift**  key, click **Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-17.jpg)

 2)  

 Click **Troubleshoot**  \>**Advanced options**  \> **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-18.jpg)

 3)  

 Select your administrator account and then enter the password if you set one before.  
 Click **Continue**  to go on.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-20.jpg)

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-14.jpg)

 4)  

 Wait a few seconds for command prompt window poping-up.  
 Then type the following commands in the window and hit **Enter**  after each.  
 **cd %windir%\\system32\\config**
 **ren system system.001**
**ren software software.001**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-15.jpg)

 5)  

 After it’s done, close command prompt window.  
 Then it will be back to boot option page.  
 Click **Continue** to boot into your Windows 10.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-9.jpg)

 6)  

 Try to reset your Windows 10 now and see if the error has been solved.

**Fix 2\. Recover your PC from USB recovery USB**

 1)  

 Insert an empty USB Flash drive(16GB recommended) into your computer.

 2)  

 Type **recovery drive**  in the search box from Start menu.  
 Then click **Create a recovery drive**  from the top result.  
 Click **Yes**  when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-10.jpg)

 3)  

 Click **Next** .  
**Note:**
 Recover your PC from a drive will remove all your files and apps, you can choose to tick on **Back up system files to the recovery drive** in this step to back up.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-7.jpg)

 4)  

 Select your USB drive and click **Next** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/12-2.jpg)

 5)  

 Click **Create** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/13-1.jpg)

 When it’s done, click **Finish** .

 6)  

 Now reboot your Windows 10.  
 Press the specific key, like **F12** or any other key your PC tells to enter boot option page.  
 Go on to choose to boot from your USB recovery drive.

 7)  

 Click **Recovery from a drive** .

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/14-2.jpg)

Go on to follow the on-screen instructions to complete the reinstalling.

 That’s all there is to it. Hope the solution here can help you fix the error.  
 Any questions please feel free to leave comment below, thanks.

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
