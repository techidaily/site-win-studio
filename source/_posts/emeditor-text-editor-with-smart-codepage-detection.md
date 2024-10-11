---
title: EmEditor Text Editor with Smart Codepage Detection
date: 2024-10-09T16:02:17.476Z
updated: 2024-10-11T01:07:02.777Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/38800d1bcd9a0db51e74a8d6e9d259f45c0a81d4cc5911dccf11c067ddd27a33.jpg
---

## EmEditor Text Editor with Smart Codepage Detection

Viewing 7 posts - 1 through 7 (of 7 total)

* Author  
Posts
* October 14, 2006 at 12:38 am [#3888](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/deb31b3e043ce35d6cf54e93403dcbc0?s=80&d=identicon&r=g)andres99](https://www.emeditor.com/forums/users/andres99/ "View andres99's profile")  
Participant  
I am presently looking for a text editor to suit all my needs. Basically, EmEditor does it. The free SuperEdi program also does it but I like EmEditor more for some configurability options.  
 I think that a valuable addition to EmEditor would be codepage autodetection on document open (without the program asking the user). SuperEdi has it already now (and it seems to work).  
 I have downloaded the test version of EmEditor Standard (which is smaller and I like it better), and it seems that EmEditor Standard already has the possibility to introduce codepage autodetection (basically it allows the user to select). An option for absolute autodetection would be very nice because I have files with different codepages and I sometimes just have to check the detect codepage dialog. I would prefer an automatic selection and if the codepage really is not detected, there should be an option to turn it off.  
 I am probably going to purchase EmEditor Standard but I’d like to think what the developers think about the possibility to add codepage autodetection in the future. Thank you.  
October 14, 2006 at 12:52 am [#3889](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
You can disable the Auto Detect result dialog box:  
 Select **Customize** on the Tools menu, select the **File** tab, uncheck **Always Show Detect All Result** check box.  
 By default this is checked because the Auto Detection can make mistakes sometimes especially in small files. But if that is not a problem, you can uncheck this option. If you see a mistake, you can always reload the file as a correct encoding by double-clicking the encoding on the status bar.  
October 14, 2006 at 2:48 pm [#3890](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/deb31b3e043ce35d6cf54e93403dcbc0?s=80&d=identicon&r=g)andres99](https://www.emeditor.com/forums/users/andres99/ "View andres99's profile")  
Participant  
Yes, I know that but what I meant was more the feature to “improve” autodetection.  
 For example, my native codepage on Windows XP is Windows-1257 (Baltic). For comfortability reasons, the “Opening encoding” for plaintext files is set as “System Default” (i.e. 1257).  
 I also work with some other codepages like Windows-1251 (Cyrillic), ISO-8859-15 (Latin 9, Pan European), ISO-8859-1, KOI-8 (Cyrillic) and, of course, UTF-8 / UTF-16.  
 Now, when I open UTF, there is no problem. Everything is detected automatically. There is no problem either when I open Windows-1257 files.  
 But when I open a Windows-1251 file (no matter whether I have Always display detect all result checked or not), EmEditor displays this in Windows-1257.  
 Another example, I have an ISO-8859-1 text file and when I open it, EmEditor thinks this is Windows-1257 again. When I use Reload as -> Detect All, EmEditor makes the correct guess that the file is ISO-8859-1.  
 When I open the same files in SuperEdi, I already get the correct display (SuperEdi detects the codepages without asking from me).  
 Now, what I meant was that EmEditor could have an option to automatically display a file in the most probable codepage (which I can already see in DetectAll results).  
 More specifically, when I open the Windows-1251 file, which is displayed incorrectly as Windows-1257, when I press “Detect All”, the box already shows that this file is most probably Windows-1251\. (EmEditor actually knows the correct or most probable codepage!) However, EmEditor still opens this in Windows-1257.  
 Since EmEditor actually seems to understand the correct codepage but for some reason does not open it correctly (maybe because the opening encoding for text files is set as “System default”, I thought something like this:  
 There could be an option in EmEditor called “Always open files with autodetected codepage” or “Autodetect codepages without asking” (which means “without displaying the “detect all” dialog”). In that case, EmEditor should internally operate DetectAll, discover that the most probable codepage for the file is e.g. Windows-1251 and then apply this codepage.  
 It seems that EmEditor is capable of this anyway (because in DetectAll, the correct codepage is already displayed but it is not applied).  
 I know that there could be mistakse but if EmEditor detects the codepage incorrectly, I can always use “Reopen” or uncheck the autodetection option. Presently I have checked about 100 files and EmEditor’s detect all has always discovered the right codepage. Therefore, I think, that the mistakes are not very probable (of course they can sometimes occur).  
 I do not have presently any big problems with that because I can really always use the AutoDetect dialog, but it would be much more comfortable to open any file right away with the correct (or most probable) codepage (without asking the user). Just comfortability :)  
 As to pragmatics, since I think that “Detect all” discovers the right codepage correctly in most cases, anyway, it would be more comfortable to have the files opened with autodetected codepages (and not always to use “detect all” manually. In those rare cases when a mistake occurs (or may occur), one can use “detect all” (from “Reload as”).  
October 14, 2006 at 3:55 pm [#3891](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Can you please send me a few Windows-1251 files or any files that can cause a problem (after zipped as .Zip) as an attachment. Please also write a list explaining which file should be opened as which encoding. My email address is [tech@emurasoft.com](https://tools.techidaily.com/emeditor/products/). I will need to repro your problem here to fix this issue. Thanks!  
October 14, 2006 at 7:02 pm [#3892](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/deb31b3e043ce35d6cf54e93403dcbc0?s=80&d=identicon&r=g)andres99](https://www.emeditor.com/forums/users/andres99/ "View andres99's profile")  
Participant  
I have sent you the files, please let me know :)  
 Thanks!  
October 15, 2006 at 3:41 am [#3895](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/deb31b3e043ce35d6cf54e93403dcbc0?s=80&d=identicon&r=g)andres99](https://www.emeditor.com/forums/users/andres99/ "View andres99's profile")  
Participant  
My bad! This can already be done in EmEditor as Mr. Yutaka Emura has now explained to me. Sorry for bringing up a void topic.  
October 15, 2006 at 4:15 am [#3896](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
No problem. For the rest of us, EmEditor already has a feature to auto-detect without displaying the result dialog box:  
 First, select Properties for Current Configuration (or All Configurations) on the Tools menu, select File tab, and check Detect All checkbox. Second, select Customize on the Tools menu, and clear Always Show Detect All Result checkbox. Now you can open a file with Auto Detect but without the Detect All Result dialog box.
* Author  
Posts

Viewing 7 posts - 1 through 7 (of 7 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://youtube-webster.techidaily.com/he-essential-guide-to-tracking-your-youtube-progress/"><u>[New] The Essential Guide to Tracking Your YouTube Progress</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-transform-your-archive-with-instagrams-filters-an-easy-guide-for-2024/"><u>[Updated] Transform Your Archive with Instagram’s Filters – An Easy Guide for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-clearing-up-instagrams-video-mishaps/"><u>In 2024, Clearing Up Instagram's Video Mishaps</u></a></li>
<li><a href="https://win-studio.techidaily.com/is-microsoft-planning-fees-for-future-windows-10-updates-expected-cost-breakdown-revealed-techinsights/"><u>Is Microsoft Planning Fees for Future Windows 10 Updates? Expected Cost Breakdown Revealed | TechInsights</u></a></li>
<li><a href="https://win-studio.techidaily.com/microsoft-claims-engineers-are-enthralled-by-windows-11s-innovative-features-insights-from-zdnet/"><u>Microsoft Claims Engineers Are Enthralled by Windows 11'S Innovative Features: Insights From ZDNet</u></a></li>
<li><a href="https://win-studio.techidaily.com/microsoft-cybersecurity-conference-focuses-on-avoiding-a-worldwide-tech-crisis-can-the-strategies-succeed/"><u>Microsoft Cybersecurity Conference Focuses on Avoiding a Worldwide Tech Crisis - Can the Strategies Succeed?</u></a></li>
<li><a href="https://win-studio.techidaily.com/microsoft-discontinues-support-for-amazons-appstore-on-windows-11-what-you-need-to-know-zdnet/"><u>Microsoft Discontinues Support for Amazon's Appstore on Windows 11: What You Need to Know - ZDNet</u></a></li>
<li><a href="https://fox-access.techidaily.com/photoshops-stabilization-an-essential-tool-or-overrated-feature-in-2024/"><u>Photoshop's Stabilization An Essential Tool or Overrated Feature, In 2024</u></a></li>
<li><a href="https://win-studio.techidaily.com/preparing-for-the-future-microsoft-announces-paid-windows-11-update-feature-find-out-what-it-costs/"><u>Preparing for the Future: Microsoft Announces Paid Windows 11 Update Feature – Find Out What It Costs!</u></a></li>
<li><a href="https://win-studio.techidaily.com/revitalize-your-aging-pc-with-5-key-methods-most-at-zero-cost-discover-how-on-the-latest-windows-11-update/"><u>Revitalize Your Aging PC with 5 Key Methods - Most at Zero Cost! Discover How on the Latest Windows 11 Update</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstaller-technique-to-delete-users-in-windows-11-efficiently/"><u>Revo Uninstaller Technique to Delete Users in Windows 11 Efficiently</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/stay-productive-for-days-with-the-latest-addition-to-lenovo-laptops-the-powerful-thinkpad-t14s-featuring-snapdragon-x-elite-cpu-and-massive-32gb-ram/"><u>Stay Productive for Days with the Latest Addition to Lenovo Laptops - The Powerful ThinkPad T14s Featuring Snapdragon X Elite CPU & Massive 32GB RAM</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-creative-processes-efficiently-adding-text-to-videos-with-microsoft-photos/"><u>Streamline Creative Processes Efficiently Adding Text to Videos with Microsoft Photos</u></a></li>
<li><a href="https://win-studio.techidaily.com/top-7-essential-microsoft-powertoys-you-need-on-your-windows-computer-discover-them-here/"><u>Top 7 Essential Microsoft PowerToys You Need on Your Windows Computer - Discover Them Here!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unraveling-vyncs-link-reviews-robust-monitoring-software-with-bewildering-payment-schemes/"><u>Unraveling Vyncs Link Reviews: Robust Monitoring Software with Bewildering Payment Schemes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

