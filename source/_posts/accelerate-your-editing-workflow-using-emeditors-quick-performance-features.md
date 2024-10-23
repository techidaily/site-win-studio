---
title: Accelerate Your Editing Workflow Using EmEditor's Quick Performance Features
date: 2024-10-21T17:27:50.363Z
updated: 2024-10-22T19:57:13.771Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/662c307b916403e88dc997e74395824da6bd2c6533fd74096afaf9205f685325.jpg
---

## Accelerate Your Editing Workflow Using EmEditor's Quick Performance Features

Viewing 20 posts - 1 through 20 (of 20 total)

* Author  
Posts
* April 27, 2008 at 9:56 am [#5712](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/4fce9359c4f87c7939c6c498b14b940c?s=80&d=identicon&r=g)thylocene](https://www.emeditor.com/forums/users/thylocene/ "View thylocene's profile")  
Member  
Hi  
 I have downloaded an eval copy of the EmEditor to compare against other editors (I am looking for a good fast replacement for notepad). Whilst I can see great potential in the program, I am finding it a bit slow when compared to other products that I have tried such as textpad, notepad++, etc. for things like paging through large text files, search and replace etc. For example textpad is 2 x to 3 x faster at search and replace and much faster at paging.  
 My question is do you guys aim to address this in the near future?  
April 27, 2008 at 5:40 pm [#5713](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> thylocene wrote:  
> Hi  
> I have downloaded an eval copy of the EmEditor to compare against other editors (I am looking for a good fast replacement for notepad). Whilst I can see great potential in the program, I am finding it a bit slow when compared to other products that I have tried such as textpad, notepad++, etc. for things like paging through large text files, search and replace etc. For example textpad is 2 x to 3 x faster at search and replace and much faster at paging.  
>  
> My question is do you guys aim to address this in the near future?  
 First, a few simple questions: What is the typical size of text file you are trying to page or search/replace? Have you changed any settings on the Advanced tab of the Customize dialog box (on the Tools menu)? We certainly want to optimize the speed in all cases.  
April 28, 2008 at 12:23 am [#5716](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/4fce9359c4f87c7939c6c498b14b940c?s=80&d=identicon&r=g)thylocene](https://www.emeditor.com/forums/users/thylocene/ "View thylocene's profile")  
Member  
Hi  
 The size of the text file is around 26 Mb (around 119,000 lines). EmEditor settings are out-of-the-box. In all cases each editor I have tested is with the same file, window size etc,etc.  
April 29, 2008 at 3:08 am [#5724](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> thylocene wrote:  
> Hi  
> The size of the text file is around 26 Mb (around 119,000 lines). EmEditor settings are out-of-the-box. In all cases each editor I have tested is with the same file, window size etc,etc.  
 I am trying to reproduce your issue, but please let me know more details:  
 – what is your search term?  
 – “Match Case”, “Escape Sequence”, “Regular Expressions”?  
 – Did you select “Wrap by Window” or “Wrap by Characters”?  
 – If possible, please email me a sample file (after zipped) at [tech@emurasoft.com](https://tools.techidaily.com/emeditor/products/)  
 I will try to reproduce, and will cerntainly try to fix your issue.  
 Thank you.  
May 2, 2008 at 12:28 am [#5737](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/4fce9359c4f87c7939c6c498b14b940c?s=80&d=identicon&r=g)thylocene](https://www.emeditor.com/forums/users/thylocene/ "View thylocene's profile")  
Member  
As I said, my settings were out-of-the-box.  
 Search and replace string did not include regex  
 ex. Replace AND with XXXXXXXXXX  
 Pretty simple  
 My environment is Vista 64-bit, but I do not think that has anything to do with it since the other programs are 32-bit as well so some thunking should be taking place.  
May 2, 2008 at 5:34 pm [#5742](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> thylocene wrote:  
> As I said, my settings were out-of-the-box.  
>  
> Search and replace string did not include regex  
>  
> ex. Replace AND with XXXXXXXXXX  
>  
> Pretty simple  
>  
> My environment is Vista 64-bit, but I do not think that has anything to do with it since the other programs are 32-bit as well so some thunking should be taking place.  
 I have 1 million line text (81MB), and did a simple replace (Replace “abc” with “XXXXXXXXXX”). In my machine it took about 8 seconds (when “Match Case” is off), and 3 seconds (when “Match Case” is on). Is this comparable to your results? You might want to try “Match Case” on, since this changes the speed dramatically. I will still look into more details. Thank you!  
May 9, 2008 at 11:58 am [#5759](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/4fce9359c4f87c7939c6c498b14b940c?s=80&d=identicon&r=g)thylocene](https://www.emeditor.com/forums/users/thylocene/ "View thylocene's profile")  
Member  
Hi  
 I have carried out some more testing. Sorry for the time lag but I only seem to get time on weekends nowadays. Your suggestion of using Match Case is really not usable since in most cases I don’t really care about the case of a search / replace string.  
 In my testing the target file is a plain text file with 1 million lines (137 Mb)  
 9/05/2008 19:30 137,109,008 target.txt  
 137,109,008 bytes in 1 file and 0 dirs 137,109,504 bytes allocated  
 The host is Windows XP SP2 with 2 GB of ram. I am replacing the word Feature with abcD – 7112 occurences. I have carried out the test with three editors; Textpad, Notepad++ 4.8.5, and emEditor v7.00.5\. I carried out the tests several times and then averaged the results. As you can see Textpad is the outright winner. Its no case matching search and replace is actually faster than emEdit with Case matching. At the moment Textpad gets my vote.  
 Textpad 5.0.3 32-bit:  
 No case matching: 5 secs  
 Match case: 3 secs  
 Notepad++:  
 No case matching: 47 secs  
 Match case: 14 secs  
 EmEditor v7.00.5  
 No case matching: 36 secs  
 Match case: 7 secs  
 Cheers  
 thylocene  
May 9, 2008 at 5:21 pm [#5761](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I have 1 million line US-ASCII text (80.9MB), and the content is:  
    
	1-abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz  
	2-abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz  
	3-abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz  
	...  
	 I replaced “abc” with “XXXXXXXXXX”. That means there are 2 tokens in each line to replace when case matching, or 3 tokens when no case matching, total of 2 (or 3) million tokens in the entire file. The host is Windows XP SP2 (English) in Virtual PC 2007 (within Windows Vista 64-bit Intel Core 2 Quad Q6600, 8GB RAM). All software programs are freshly installed.  
 Here is my result:  
 Textpad 5.2.0 32-bit  
 No case matching: 34 sec  
 Match case: 22 sec  
 Notepad++ 4.7.5  
 No case matching: 10 min 3 sec  
 Match case: 6 min 32 sec  
 EmEditor Professional 7.00.5  
 No case matching: 9 sec  
 Match case: 5 sec  
 Thus, EmEditor Professional was the fastest of all these three. I also found something noteworthy: Only EmEditor allows you to cancel replacing during the operation. Other programs do not allow you to abort once you hit “Replace All” until the operation is finished. TextPad does not allow you open Unicode files (such as Japanese characters) correctly (it opens but converts Unicode characters into a substitute character “?”). I wanted to compare Unicode files, but couldn’t because of this.  
 I don’t know why you have the different result. Maybe because you have only a few tokens to replace, or your file might be encoded in a different encoding. This is the reason it would be more helpful if you could email me your sample file so I can reproduce your issue. Is your Windows system encoding English? (You can find out from Control Panel > Regional Language Options > Advanced tab – “Language for non-Unicode programs”)  
May 9, 2008 at 10:14 pm [#5762](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9a160576bf8e0d3296fd3bcf91b933fd?s=80&d=identicon&r=g)gan](https://www.emeditor.com/forums/users/gan/ "View gan's profile")  
Participant  
I’m a textpad and emeditor user as well so i found this a bit interesting and did some testing on my computer as well which is a laptop with 2.4GHz Core Duo (T7700) with 2gb RAM running English Windows Vista SP1 (32-bit). Regional settings and keyboard is set to Norwegian.  
**Info about the file:**  
 Filesize: 113mb  
 Lines: 2183617  
 10608 entries to replace  
**Emeditor 7.00.5:**  
 Open file: 4.9 sec  
 No case match: 20 sec  
 Case match: 3.5 sec  
 (Everything else unchecked)  
**Textpad 5.2:**  
 Open file: 1.1 sec  
 No case match: 1.5 sec  
 Case match: 1.1 sec  
 (Text and Active documents selected and everything else unchecked.)  
 So my results is the same as thylocene where textpad is much faster for this operation. Maybe the dialogbox that show the progress using emeditor is the reason why textpad is so much faster since textpad does not show the progress like that?  
 I’m aware of lack of unicode support using textpad and while emeditor is able to open files with unlimited size textpad is very limited…..that is a couple of the reasons why i need two text editors.  
 Regards  
 Gan  
May 14, 2008 at 4:03 pm [#5777](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/29b0d3f8d0f5c2abda5c02c663bdbdb0?s=80&d=identicon&r=g)chabulier](https://www.emeditor.com/forums/users/chabulier/ "View chabulier's profile")  
Member  
it’s true.  
 In my local test. 2G mem T60  
 File Size: 114M  
 Total Lines: 1,183,428  
 search “INFO”  
 replace with “\[INFORMATION\]”  
 Matched 63,158  
 not match case  
 both open blank display  
 TextPad 5.2  
 2.60 secs  
 EmEditor 7.05  
 25\~26 secs  
 However Emeditor give more function:  
 1) process bar and highlight.  
 2) emeditor empty display more pretty.  
 3) Emeditor’s fronts support customize looks more better.  
 4) Emeditor can open huge files, but Textpad have a limit.  
May 14, 2008 at 5:25 pm [#5778](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
The point is the number of tokens (occurrences). If you have a million of tokens to replace, you will see EmEditor is faster. Also, it is not fair to compare EmEditor with a non-Unicode text editor. There is a big difference between ANSI comparison and Unicode comparison.  
May 14, 2008 at 8:49 pm [#5780](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9a160576bf8e0d3296fd3bcf91b933fd?s=80&d=identicon&r=g)gan](https://www.emeditor.com/forums/users/gan/ "View gan's profile")  
Participant  
I did a test on the same file, but with 1129344 entries to replace and as you said in this case emeditor is faster without any doubt…..especially when “Match case” is checked.  
 I don’t know if textpad use ANSI comparison or not, but if that is the case i guess it can make a difference as well as you also said.  
 In any case i don’t find the speed to be a problem for either of them so it was never mean’t as a complaint…..just an observation.  
 Regards  
 Gan  
May 15, 2008 at 9:20 pm [#5781](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> gan wrote:  
> I did a test on the same file, but with 1129344 entries to replace and as you said in this case emeditor is faster without any doubt…..especially when “Match case” is checked.  
>  
> I don’t know if textpad use ANSI comparison or not, but if that is the case i guess it can make a difference as well as you also said.  
>  
> In any case i don’t find the speed to be a problem for either of them so it was never mean’t as a complaint…..just an observation.  
>  
> Regards  
> Gan  
 I’ve played around with the source code, and succeeded to optimize the Replace function. The next minor version (7.00.7) will become much faster than previous versions (about 5X faster when ignoring case, and 2X faster when matching case in my test).  
May 15, 2008 at 9:29 pm [#5782](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9a160576bf8e0d3296fd3bcf91b933fd?s=80&d=identicon&r=g)gan](https://www.emeditor.com/forums/users/gan/ "View gan's profile")  
Participant  
> Yutaka wrote:  
>  
> I’ve played around with the source code, and succeeded to optimize the Replace function. The next minor version (7.00.7) will become much faster than previous versions (about 5X faster when ignoring case, and 2X faster when matching case in my test).  
 Nice work. Even if the current version is working great it’s always nice when it’s enhanced further.  
 Thanks  
 Gan  
May 25, 2008 at 10:05 am [#5836](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/183e57a7d4e7476473b6fb148e217c32?s=80&d=identicon&r=g)doctorow](https://www.emeditor.com/forums/users/doctorow/ "View doctorow's profile")  
Participant  
7.00.7 is out. Has anyone tested and compared it to the previous versions?  
May 25, 2008 at 11:20 am [#5837](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9a160576bf8e0d3296fd3bcf91b933fd?s=80&d=identicon&r=g)gan](https://www.emeditor.com/forums/users/gan/ "View gan's profile")  
Participant  
I tested and found 7.00.7 to be pretty much faster then 7.00.5\. Also faster then any other text editor i tried. There is almost no difference between case sensitive and case insensitive searching now while using 7.00.5 the difference could be pretty big.  
 But it seems like 7.00.8 is out now as well as 7.00.9 RC1.  
June 4, 2008 at 12:31 pm [#5875](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/2e1c9efc2430993c71be903dc5b131c3?s=80&d=identicon&r=g)owilsky](https://www.emeditor.com/forums/users/owilsky/ "View owilsky's profile")  
Participant  
Unfortunately I didn’t have the possibility to test the new version yet.  
 For me Search/Replace with RegEx enabled was very slow in bigger files in the last versions.  
 Is RegEx Search/Replace also faster now?  
June 5, 2008 at 11:41 am [#5876](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/9a160576bf8e0d3296fd3bcf91b933fd?s=80&d=identicon&r=g)gan](https://www.emeditor.com/forums/users/gan/ "View gan's profile")  
Participant  
Yes search and replace is much faster in general.  
July 19, 2008 at 9:47 pm [#6040](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/af0f40739493764d2eed70aa94314d20?s=80&d=identicon&r=g)secox0](https://www.emeditor.com/forums/users/secox0/ "View secox0's profile")  
Participant  
I purchased EmEditor to help me edit large (4.8 GB and larger) ASCII text files. I have a duo core laptop, WinXP Pro and 2 GB ram.  
 Can you recommend settings to optimize the Finding and Editing of text ?  
 Thanks :-)  
July 24, 2008 at 12:40 am [#6044](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> secox0 wrote:  
> I purchased EmEditor to help me edit large (4.8 GB and larger) ASCII text files. I have a duo core laptop, WinXP Pro and 2 GB ram.  
>  
> Can you recommend settings to optimize the Finding and Editing of text ?  
>  
> Thanks :-)  
 You should be able to use EmEditor at default settings for maximum speed. However, if the text is not .txt file, you might want to try Text configuration to start with, and you might want to disable all plug-ins.
* Author  
Posts

Viewing 20 posts - 1 through 20 (of 20 total)

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-iphone-video-editing-showdown-cameo-against-filmorago/"><u>[New] 2024 Approved IPhone Video Editing Showdown Cameo Against FilmoraGo</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-gaming-heaven-a-treasure-trove-of-superb-offline-ios-game-titles/"><u>[Updated] In 2024, Gaming Heaven A Treasure Trove of Superb Offline iOS Game Titles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instavoice-top-100-captions-that-define-your-personal-narrative-for-2024/"><u>[Updated] InstaVoice Top 100 Captions That Define Your Personal Narrative for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-ultimate-guide-7-preferred-android-ad-blocking-tools/"><u>[Updated] Ultimate Guide 7 Preferred Android Ad Blocking Tools</u></a></li>
<li><a href="https://win-studio.techidaily.com/7-strategien-zur-sichtbarmachung-versteckter-dateien-in-verzeichnissen-auf-windows-1087-seo-optimiert/"><u>7 Strategien Zur Sichtbarmachung Versteckter Dateien in Verzeichnissen Auf Windows 10/8/7 - SEO-Optimiert</u></a></li>
<li><a href="https://win-studio.techidaily.com/1728501585748-windows-3/"><u>如何在 Windows 系统中迁移硬盘中已有照片：3个彻底解决方案</u></a></li>
<li><a href="https://article-files.techidaily.com/action-replay-gopro-hero5-black-meets-hero4-silver-edition-for-2024/"><u>Action Replay GoPro Hero5 Black Meets Hero4 Silver Edition for 2024</u></a></li>
<li><a href="https://win-studio.techidaily.com/complete-samsung-t1-drive-reset-instructions-official-and-non-official-methods-explored/"><u>Complete Samsung T1 Drive Reset Instructions - Official and Non-Official Methods Explored</u></a></li>
<li><a href="https://win-studio.techidaily.com/d-drive-daten-wiederherstellung-losungen-easy-tipps-zur-selbsthilfe/"><u>D-Drive Daten Wiederherstellung Lösungen: Easy Tipps Zur Selbsthilfe</u></a></li>
<li><a href="https://extra-resources.techidaily.com/imovie-cropping-query-the-hidden-logic-behind-it/"><u>IMovie Cropping Query The Hidden Logic Behind It</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-top-10-games-like-gta-v/"><u>In 2024, Top 10 Games Like GTA V</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/investigating-authenticitys-role-in-social-media-selfie-presentation/"><u>Investigating Authenticity’s Role in Social Media Selfie Presentation</u></a></li>
<li><a href="https://win-studio.techidaily.com/resolving-windows/"><u>Resolving Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/virtual-attendees-blueprint-how-to-join-and-watch-samsungs-tech-reveals-online/"><u>Virtual Attendee's Blueprint: How to Join and Watch Samsung's Tech Reveals Online</u></a></li>
<li><a href="https://win-studio.techidaily.com/windows-11-peusb/"><u>Windows 11 PEの使用:容易なブート可能USB作成ガイド</u></a></li>
<li><a href="https://win-studio.techidaily.com/windows-server-201cuo-r2/"><u>Windows Server 201Cuo R2 淘汰雙重存取: 三個有效解決方案</u></a></li>
<li><a href="https://win-studio.techidaily.com/youtube5/"><u>YouTube動画復活ガイド：失われたビデオをスムーズに再生可能にする5つの方法</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

