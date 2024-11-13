---
title: EmEditor Text Editor with Smart Codepage Detection
date: 2024-11-07T16:35:10.624Z
updated: 2024-11-12T23:09:46.818Z
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
<li><a href="https://screen-activity-recording.techidaily.com/1715859568042-new-leading-12-screen-recorders-no-time-limit/"><u>[New] Leading 12 Screen Recorders, No Time Limit!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-leading-edge-webcams-the-best-on-windows-10/"><u>[New] Leading Edge Webcams The Best on Windows 10</u></a></li>
<li><a href="https://win-studio.techidaily.com/comment-debloquer-et-reparer-la-cle-usb-bloquee-sur-votre-systeme-dexploitation-windows-11/"><u>Comment Débloquer Et Réparer La Clé USB Bloquée Sur Votre Système D’exploitation Windows 11</u></a></li>
<li><a href="https://win-studio.techidaily.com/comment-demarrer-avec-succes-un-ordinateur-a-partir-dun-disque-dur-externe-guide-pour-windows-11-utilisateurs/"><u>Comment Démarrer Avec Succès Un Ordinateur À Partir D'un Disque Dur Externe - Guide Pour Windows 11 Utilisateurs</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminated-stretching-effect-on-extended-windows-views/"><u>Eliminated Stretching Effect on Extended Windows Views</u></a></li>
<li><a href="https://win-studio.techidaily.com/guide-complet-a-la-restauration-de-votre-serveur-windows-server-2016-deux-methodes-eprouvees/"><u>Guide Complet À La Restauration De Votre Serveur Windows Server 2016 - Deux Méthodes Éprouvées</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-h1-an-easy-guide-for-how-to-add-photos-on-instagram/"><u>In 2024, H1 An Easy Guide for How to Add Photos on Instagram</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-portable-balancing-system-for-video-capture/"><u>In 2024, Portable Balancing System for Video Capture</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/752690-9788472452787-la-conciencia-sin-fronteras/"><u>La conciencia sin fronteras | Free Book</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-ai-control-mechanisms/"><u>Navigating AI Control Mechanisms</u></a></li>
<li><a href="https://win-studio.techidaily.com/overblijvende-back-up-oplossingen-voor-windows-versies-11-10-8-en-eindigende-7-met-hoe-norton-ghost/"><u>Overblijvende Back-Up Oplossingen Voor Windows Versies 11, 10, 8 en Eindigende 7 Met Hoe Norton Ghost</u></a></li>
<li><a href="https://buynow-info.techidaily.com/secure-and-optimize-from-windows-10-home-to-pro/"><u>Secure and Optimize: From Windows 10 Home to Pro</u></a></li>
<li><a href="https://win-studio.techidaily.com/transferieren-sie-ihre-lieblings-musik-von-iphone-zu-externem-speicherplatz-effiziente-methoden-and-tools-wie-fonebackup/"><u>Transferieren Sie Ihre Lieblings-Musik Von iPhone Zu Externem Speicherplatz - Effiziente Methoden & Tools Wie FoneBackup</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/winxvideo-ai-transformando-la-calidad-de-tus-imagenes-a-resoluciones-ultra-hd-4k-8k-y-10k/"><u>WinxVideo AI: Transformando La Calidad De Tus Imágenes a Resoluciones Ultra HD - 4K, 8K Y 10K</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

