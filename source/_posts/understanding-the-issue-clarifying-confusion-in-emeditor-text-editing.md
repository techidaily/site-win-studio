---
title: "Understanding the Issue: Clarifying Confusion in EmEditor Text Editing"
date: 2024-10-19T23:51:56.129Z
updated: 2024-10-23T02:57:55.899Z
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
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-personalize-facebook-page-with-video/"><u>[Updated] 2024 Approved Personalize Facebook Page with Video</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-intersecting-realities-metaverse-and-multiverse-differences/"><u>[Updated] Intersecting Realities Metaverse and Multiverse Differences</u></a></li>
<li><a href="https://win-studio.techidaily.com/crie-um-conteudo-informativo-passo-a-passo-explicando-a-maneira-de-recuperar-fotos-sem-precisar-de-software-adicional-lembre-se-de-usar-as-palavras-chave-no88/"><u>Crie Um Conteúdo Informativo, Passo-a-Passo Explicando a Maneira De Recuperar Fotos Sem Precisar De Software Adicional. Lembre-Se De Usar as Palavras-Chave Nos Textos Relevantes Para Otimizar O SEO.</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/essential-tips-for-correcting-popular-video-malfunctions/"><u>Essential Tips for Correcting Popular Video Malfunctions</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-motorola-moto-g23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-oppo-reno-9a-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Oppo Reno 9A Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-studio.techidaily.com/mac3/"><u>Macオペレーティングシステム用トップ3コピーソフトウェア：効率的なフォルダ複製</u></a></li>
<li><a href="https://win-studio.techidaily.com/mastering-windows-system-restore-a-dual-approach/"><u>Mastering Windows System Restore: A Dual Approach</u></a></li>
<li><a href="https://win-studio.techidaily.com/protege-tu-informacion-con-copias-de-seguridad-rapidas-y-sencillas-de-los-archivos-de-microsoft-outlook-para-usuarios-de-windows-nx/"><u>Protege Tu Información Con Copias De Seguridad Rápidas Y Sencillas De Los Archivos De Microsoft Outlook Para Usuarios De Windows nX</u></a></li>
<li><a href="https://discover-dash.techidaily.com/1728480212908-sd/"><u>SDカードのデータ蘇生:フォーマット後に可能か？</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/smooth-cinematography-premium-stabilizer-recommendations-for-2024/"><u>Smooth Cinematography Premium Stabilizer Recommendations for 2024</u></a></li>
<li><a href="https://win-studio.techidaily.com/step-by-step-guide-generating-a-windows-1110-bootable-iso-from-your-current-system/"><u>Step-by-Step Guide: Generating a Windows 11/10 Bootable ISO From Your Current System</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/1723262392171-top-gamers-choice-for-bargain-hunters-grab-a-powerhouse-pc-at-just-999rtx-4060-and-ultra-fast-ram/"><u>Top Gamers' Choice for Bargain Hunters: Grab a Powerhouse PC at Just $999—RTX 4060 & Ultra-Fast RAM!</u></a></li>
<li><a href="https://win-studio.techidaily.com/understanding-your-needs-the-essential-guide-to-picking-docker-over-vms-or-vice-versa/"><u>Understanding Your Needs: The Essential Guide to Picking Docker over VMs or Vice Versa</u></a></li>
<li><a href="https://win-studio.techidaily.com/1728467654972-windows-1110/"><u>Windows 11・10・サーバー向けに完璧なリカバリ手順：ベアメタルを極める</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

