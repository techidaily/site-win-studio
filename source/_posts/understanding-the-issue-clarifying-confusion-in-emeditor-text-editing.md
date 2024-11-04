---
title: "Understanding the Issue: Clarifying Confusion in EmEditor Text Editing"
date: 2024-10-30T17:04:25.051Z
updated: 2024-11-03T17:07:58.477Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/78573d1d50e3fe1a208211e6210a893de5cb63383e5008c1e4699b06b4a4f916.jpg
---

## Understanding the Issue: Clarifying Confusion in EmEditor Text Editing

November 15, 2008 at 6:27 am [#6603](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

> webern wrote:  
> I have the problem with the macro below:
> 
> with (document.selection){  
> 
>  Replace("^","* ", eeFindNext | eeReplaceSelOnly | eeReplaceAll | eeFindReplaceRegExp);  
> 
>  Replace("**(?<!(.)$)$", ".**", eeFindNext | eeReplaceSelOnly | eeReplaceAll | eeFindReplaceRegExp);  
> 
> }
> 
> Something wrong with the above (highlighted) regexp. I know this regexp is not perfect, but I get exactly what I want with it on EE**7**.  
> The results are different on EE**8**.
> 
> Steps to reproduce:  
> **1.** Apply the macro to the text below:
> 
> [font=Verdana]EmEditor Text Editor is a lightweight  
> 
> EmEditor Text Editor is a lightweight  
> 
> EmEditor Text Editor is a lightweight.  
> 
> EmEditor Text Editor is a lightweight.
> 
>  
> (a) On EE**7** the results are as follows (changes are highlighted):
> 
> * EmEditor Text Editor is a lightweight**.**  
> 
> * EmEditor Text Editor is a lightweight**.**  
> 
> * EmEditor Text Editor is a lightweight.  
> 
> * EmEditor Text Editor is a lightweight.
> 
> (b) On EE**8** I got something wrong (highlighted):
> 
> * EmEditor Text Editor is a lightweight.  
> 
> * EmEditor Text Editor is a lightweight..  
> 
> * EmEditor Text Editor is a lightweight.  
> 
> .* EmEditor Text Editor is a lightweight.
> 
> **2.** Press **Ctrl+Z** right after applying the macro on EE**8** then look at the screen to see what the **Undo** have produced.
> 
> **P.S.** A friend of mine suggested me to replace the imperfective “(?<!(.)$)$", ".” with more reliable “(\[^.\])$”, “1.“  
> but after applying it added an unwanted extra to the end of the selection.  
> \[/font\]

 RC 5 addressed this issue. Please try again with RC 5\. Thank you!

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
<li><a href="https://vp-tips.techidaily.com/2024-approved-blueprint-for-a-viral-solitary-audio-experience/"><u>2024 Approved Blueprint for a Viral Solitary Audio Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-the-depths-of-time-lapse-photography-with-gopro/"><u>2024 Approved Exploring the Depths of Time-Lapse Photography with GoPro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-effective-spotify-promotion/"><u>2024 Approved Mastering the Art of Effective Spotify Promotion</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-prime-products-best-free-and-paid-macpc-video-decoders/"><u>2024 Approved Prime Products Best Free & Paid Mac/PC Video Decoders</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/amplify-your-voice-on-youtube-mastery-through-tubebuddy/"><u>Amplify Your Voice on YouTube - Mastery Through TubeBuddy</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/eling-changes-transition-to-youtubes-updated-membership-model-for-2024/"><u>Channeling Changes Transition to YouTube's Updated Membership Model for 2024</u></a></li>
<li><a href="https://win-studio.techidaily.com/enable-pure-password-authentication-and-skip-security-queries-for-windows-11-accounts/"><u>Enable Pure Password Authentication and Skip Security Queries for Windows 11 Accounts</u></a></li>
<li><a href="https://win-studio.techidaily.com/1728503414071-excel/"><u>Excelデータ損失からの回復 - 最新方法で未保存または上書きされたファイルを取り戻す</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-and-instagram-synergy-posting-content-easily/"><u>In 2024, YouTube and Instagram Synergy Posting Content Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/lunch-mixed-greens-salad-with-grilled-shrimp-cherry-tomatoes-cucumber-red-onion-and-lemon-olive-oil-dressing/"><u>Lunch: Mixed Greens Salad with Grilled Shrimp, Cherry Tomatoes, Cucumber, Red Onion, and Lemon-Olive Oil Dressing.</u></a></li>
<li><a href="https://win-studio.techidaily.com/mastering-the-art-of-problem-solving-essential-skills-and-methods/"><u>Mastering the Art of Problem Solving: Essential Skills and Methods</u></a></li>
<li><a href="https://win-studio.techidaily.com/maximize-storage-potential-with-newly-updated-kingston-ssd-firmware-for-superior-performance-gains/"><u>Maximize Storage Potential with Newly Updated Kingston SSD Firmware for Superior Performance Gains</u></a></li>
<li><a href="https://win-studio.techidaily.com/schnelle-losungen-fur-den-windows-11-startmanger-reparaturprozess-ein-leitfaden-von-myrecover/"><u>Schnelle Lösungen Für Den Windows 11 Startmanger-Reparaturprozess – Ein Leitfaden Von MyRecover</u></a></li>
<li><a href="https://win-studio.techidaily.com/top-losungen-zum-wiederherstellen-von-geloschten-profilen-unter-windows-10-eine-umfassende-liste/"><u>Top-Lösungen Zum Wiederherstellen Von Gelöschten Profilen Unter Windows 10: Eine Umfassende Liste!</u></a></li>
<li><a href="https://win-studio.techidaily.com/troubleshooting-sql-server-backup-errors-top-techniques-and-secondary-options/"><u>Troubleshooting SQL Server Backup Errors: Top Techniques and Secondary Options</u></a></li>
<li><a href="https://win-able.techidaily.com/unlocking-excels-secrets-11-uncommon-yet-essential-features-for-enhanced-efficiency/"><u>Unlocking Excel's Secrets: 11 Uncommon Yet Essential Features for Enhanced Efficiency</u></a></li>
<li><a href="https://win-studio.techidaily.com/taazyz-altofr-imkanat-alkta-aaalya-alsraaa-lastnsakh-byanat-krs-slb-usb-aldlyl-alahdth/"><u>تعزيز التوفر: إمكانات القطة عالية السرعة لاستنساخ بيانات قرص صلب USB - الدليل الأحدث</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896532/19272" target="_top" id="1896532">
  <img src="//a.impactradius-go.com/display-ad/19272-1896532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896532/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

