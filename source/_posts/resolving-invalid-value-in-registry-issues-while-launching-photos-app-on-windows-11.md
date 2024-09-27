---
title: Resolving 'Invalid Value in Registry' Issues While Launching Photos App on Windows 11
date: 2024-08-27T13:50:40.062Z
updated: 2024-08-28T13:50:40.062Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 'Invalid Value in Registry' Issues While Launching Photos App on Windows 11
excerpt: This Article Describes Resolving 'Invalid Value in Registry' Issues While Launching Photos App on Windows 11
thumbnail: https://thmb.techidaily.com/b77f4a1b111b54e2805878ed9aa3d1afc9409a9f5cc36ff257194dcf6821d1ac.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->