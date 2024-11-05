---
title: "Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
date: 2024-10-31T01:39:17.612Z
updated: 2024-11-05T03:17:22.358Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
excerpt: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
thumbnail: https://thmb.techidaily.com/063f04ddcc12d7ad0c40343a71ed623fbddb1ebfb8c3b581a5d414d7d362a54b.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857865/11832" target="_top" id="857865">
  <img src="//a.impactradius-go.com/display-ad/11832-857865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857865/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

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
<li><a href="https://fox-glue.techidaily.com/new-the-pinnacle-of-new-zooids-in-panzoids-for-2024/"><u>[New] The Pinnacle of New Zooids in Panzoids for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-comprehensive-guide-to-using-claude-2/"><u>A Comprehensive Guide to Using Claude 2</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-errors-that-prevent-your-machine-from-booting-up/"><u>Diagnosing and Fixing Errors That Prevent Your Machine From Booting Up</u></a></li>
<li><a href="https://tech-haven.techidaily.com/evaluating-privacy-in-chatgpt-engagements/"><u>Evaluating Privacy in ChatGPT Engagements</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-itel-p40-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Itel P40 Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-discontinued-shockwave-flash-problem-on-google-chrome/"><u>How to Fix the Discontinued Shockwave Flash Problem on Google Chrome</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/hp-laptop-mastery-learn-effortless-screenshotting-methods/"><u>HP Laptop Mastery: Learn Effortless Screenshotting Methods</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hidden-echoes-to-silence-audacitys-technique-guide/"><u>In 2024, Hidden Echoes to Silence Audacity's Technique Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premier-music-selections-for-movie-making/"><u>In 2024, Premier Music Selections for Movie Making</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-ranking-the-best-budget-friendly-live-streaming-options-today/"><u>In 2024, Ranking the Best Budget-Friendly Live Streaming Options Today</u></a></li>
<li><a href="https://tech-haven.techidaily.com/integrating-gpt-chat-a-practical-api-overview/"><u>Integrating GPT-Chat: A Practical API Overview</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-10-update-freeze-expert-solutions-to-restart-your-system-effortlessly/"><u>Overcoming Windows 10 Update Freeze: Expert Solutions to Restart Your System Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-how-to-resolve-logitech-keyboard-malfunction/"><u>Quick Solutions: How To Resolve Logitech Keyboard Malfunction</u></a></li>
<li><a href="https://common-error.techidaily.com/restarting-your-night-shift-feature-on-the-latest-windows-operating-system/"><u>Restarting Your Night Shift Feature on the Latest Windows Operating System</u></a></li>
</ul></div>

