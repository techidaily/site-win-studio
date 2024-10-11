---
title: "Understanding the Issue: Clarifying Confusion in EmEditor Text Editing"
date: 2024-10-04T17:53:13.810Z
updated: 2024-10-11T11:25:01.016Z
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-best-cameras-for-vlogging/"><u>[New] 2024 Approved Best Cameras for Vlogging</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-top-tier-iphone-camera-apps-for-amateurs-and-experts-alike/"><u>[New] 2024 Approved Top-Tier iPhone Camera Apps for Amateurs & Experts Alike</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-covert-observers-fb-flashbacks-reader/"><u>[New] In 2024, Covert Observers FB Flashbacks Reader</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-document-your-days-with-xiaomis-state-of-the-art-screenshot-tool/"><u>[Updated] 2024 Approved Document Your Days with Xiaomi's State-of-the-Art Screenshot Tool</u></a></li>
<li><a href="https://win-studio.techidaily.com/1-flipchm-pro-advanced-conversion-tool-from-3d-chm-files-to-interactive-ebooks-flipbuildercom/"><u>1. FlipCHM Pro: Advanced Conversion Tool From 3D CHM Files to Interactive eBooks - FlipBuilder.com</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-next-step-for-gopro-cameras-hero4-hero5/"><u>2024 Approved The Next Step for GoPro Cameras (Hero4, Hero5)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/access-and-organize-fb-pages-easily-with-top-8-tools-for-2024/"><u>Access and Organize FB Pages Easily with Top 8 Tools for 2024</u></a></li>
<li><a href="https://win-studio.techidaily.com/is-it-possible-to-embed-video-content-into-your-softwares-ebook-format-with-flash-on-flipbuilder/"><u>Is It Possible to Embed Video Content Into Your Software’s eBook Format with Flash on FlipBuilder?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/itel-a05s-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel A05s Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win-studio.techidaily.com/perfect-your-digital-presentation-the-ultimate-techniques-for-adjusting-flipbook-page-shadows/"><u>Perfect Your Digital Presentation: The Ultimate Techniques for Adjusting FlipBook Page Shadows</u></a></li>
<li><a href="https://win-studio.techidaily.com/step-by-step-tutorial-for-implementing-easy-flipbook-downloads-using-flipbuilder-technology/"><u>Step-by-Step Tutorial for Implementing Easy Flipbook Downloads Using FlipBuilder Technology</u></a></li>
<li><a href="https://win-studio.techidaily.com/step-by-step-tutorial-setting-up-autoplay-for-flipbooks-on-flipbuildercom/"><u>Step-by-Step Tutorial: Setting Up Autoplay for Flipbooks on FlipBuilder.com</u></a></li>
<li><a href="https://win-studio.techidaily.com/transform-your-images-into-engaging-presentations-page-flipping-flash-slide-show-made-easy-at-flipbuildercom/"><u>Transform Your Images Into Engaging Presentations: Page-Flipping Flash Slide Show Made Easy at FlipBuilder.com</u></a></li>
<li><a href="https://win-studio.techidaily.com/turn-pages-online-how-to-create-an-html-flipbook-for-your-site-via-flipbuilder-complete-tutorial/"><u>Turn Pages Online: How to Create an HTML Flipbook for Your Site via FlipBuilder – Complete Tutorial</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/videopad-video-editor-is-it-worth-the-investment-in-2024/"><u>Videopad Video Editor Is It Worth the Investment, In 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

