---
title: Rectifying 'Invalid Value for Registry' Errors on Windows 10 to Restore Functionality of Photo Viewer
date: 2024-09-12T19:59:46.581Z
updated: 2024-09-15T00:36:00.824Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Rectifying 'Invalid Value for Registry' Errors on Windows 10 to Restore Functionality of Photo Viewer
excerpt: This Article Describes Rectifying 'Invalid Value for Registry' Errors on Windows 10 to Restore Functionality of Photo Viewer
thumbnail: https://thmb.techidaily.com/81c104f653fc6628652d6140a521e94570f22aa2499ea9263be6a00f18fb658c.jpg
---

## How to Fix the Invalid Registry Setting Making Photos Not Open in Windows [Continue] <http://t4.spec.cx/resolve-invalid-registry-errors-on-windows-10/>

![](https://images.drivereasy.com/wp-content/uploads/2017/05/unnamed-file.jpg)
  
 Many Windows 10 users complained that, they cannot open their photo due to the error **“Invalid value for registry”** . What an annoying problem that you cannot view your pictures. Luckily, we’ve got the answer for you. Here in this article, we will be showing you how to fix “Invalid value for registry” error when opening photos on Windows 10\. Please take a few minutes on the easy steps below.
  
**Step 1.**
 Press **Windows**  key + **R**  key together to open Run box.  
 Then type **regedit**  in the box and hit **Enter**  to open Registry Editor window.  
 Click **Yes**  when prompted by User Account Control.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-20.jpg)
  
**Step 2.**
 On Registry Editor window, head to:  
**HKEY\_CURRENT\_USER \\**   **Software \\** **Classes \\** **Local Settings \\** **Software \\** **Microsoft \\** **Windows \\** **CurrentVersion \\** **AppModel \\** **Repository \\** **Families** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-22.jpg)
  
**Step 3.**
 Scroll down on Families dialog, find and expand **Microsoft.Windows.Photos** ….. folder.  
 In this folder you might find 8 Microsoft.Windows.Photos entries, it means that the outdated registry keys have been left.  
**Delete** the 4 entries with  older version number.  
**Note:** If you find 4 entries in total, delete 2 of them with older version number.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-20.jpg)
  
 As for deleting the entries in Registry Editor window, it’s not such easy as just clicking on it to delete. Firstly you should give your account the right to do that.  
 Follow the steps here:  
  
 1)  

 Right-click on the older version entry and click **Permissions…**
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-16.jpg)
  
 2)  

 Click **Advanced** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-17.jpg)
  
 3)  

 Click **Change** .  
 Then enter you account name in the box and click **Check Names** .  
 Click **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-10.jpg)
  
 4)  

 It will be back on the previous window.  
 Tick on **Replace owner on subcontainers and objects** .  
 Then click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-11.jpg)
  
 5)  

 Highlight the account you add just before.  
 Then tick the**Allow** box of **Full Control** .  
 Click **Apply**  \> **OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/05/9-11.jpg)
  
 Now you have own the right to delete the entry you set permission.  
 Set the permission by the same steps for each old version entry and then delete them.  
  
 That’s it.  
 Hope it can help you solve the error and you can view your pictures successfully right now.  
 Any questions just feel free to leave comment below, thanks.

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



<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

