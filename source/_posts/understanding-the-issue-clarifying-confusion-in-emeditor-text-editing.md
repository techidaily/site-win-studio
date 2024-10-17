---
title: "Understanding the Issue: Clarifying Confusion in EmEditor Text Editing"
date: 2024-10-10T16:35:20.297Z
updated: 2024-10-17T16:25:38.106Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-top-6-reel-enhancing-applications-for-instagram/"><u>[New] 2024 Approved Top 6 Reel-Enhancing Applications for Instagram</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-will-2023-see-an-increase-in-televising-video-content-in-2024/"><u>[New] Will 2023 See an Increase in Televising Video Content, In 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-3-beyond-youtube-innovative-videostreaming-communities/"><u>[Updated] Top 3 Beyond Youtube Innovative Videostreaming Communities</u></a></li>
<li><a href="https://win-studio.techidaily.com/1-como-recuperar-archivos-desaparecidos-de-microsoft-el-onedrive-en-su-pc/"><u>1. ¿Cómo Recuperar Archivos Desaparecidos De Microsoft (El) OneDrive en Su PC?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-igtv-content-extraction-for-mobile-users/"><u>2024 Approved IGTV Content Extraction for Mobile Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-immersive-storytelling-through-total-environmental-capture/"><u>2024 Approved Immersive Storytelling Through Total Environmental Capture</u></a></li>
<li><a href="https://win-best.techidaily.com/3sd/"><u>3ステップで救う:フォーマットされたSDメモリにある情報を再生化</u></a></li>
<li><a href="https://win-studio.techidaily.com/aomei-backupper-umfassendes-ubersichts-und-sicherungsprogramm-fur-ihre-daten/"><u>AOMEI Backupper: Umfassendes Übersichts- Und Sicherungsprogramm Für Ihre Daten</u></a></li>
<li><a href="https://win-studio.techidaily.com/best-of-the-best-discover-6-leading-software-to-safeguard-your-data-on-windows-111087/"><u>Best of the Best: Discover 6 Leading Software to Safeguard Your Data on Windows 11/10/8/7</u></a></li>
<li><a href="https://win-studio.techidaily.com/como-migraremos-windows/"><u>Cómo Migraremos Windows</u></a></li>
<li><a href="https://win-studio.techidaily.com/comprehensive-instructions-effective-strategies-for-hyper-v-virtual-machine-snapshots-and-restores/"><u>Comprehensive Instructions: Effective Strategies for Hyper-V Virtual Machine Snapshots and Restores</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>How to Come up With the Best Pokemon Team On Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://win-studio.techidaily.com/lokasi-favorit-anda-di-google-cloud-rujuk-silakan/"><u>Lokasi Favorit Anda Di Google Cloud: Rujuk Silakan?</u></a></li>
<li><a href="https://win-studio.techidaily.com/mac-time-machine-recovery-schritt-fur-schritt-anleitungen-zum-wiederherstellen-ihrer-dateien/"><u>Mac Time Machine Recovery: Schritt-Für-Schritt Anleitungen Zum Wiederherstellen Ihrer Dateien</u></a></li>
<li><a href="https://win-studio.techidaily.com/ps4-datenwiederherstellung-schritt-fur-schritt-anleitung-zur-wiederbeschaffung-verlorener-dateien/"><u>PS4-Datenwiederherstellung: Schritt-Für-Schritt-Anleitung Zur Wiederbeschaffung Verlorener Dateien</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-setup-for-reliable-security-download-our-validity-fingerprint-sensor-drivers-today/"><u>Quick Setup for Reliable Security – Download Our Validity Fingerprint Sensor Drivers Today!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/value-meets-style-why-motorola-one-offers-iphone-like-looks-without-breaking-your-budget/"><u>Value Meets Style: Why Motorola One Offers iPhone-Like Looks Without Breaking Your Budget</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

