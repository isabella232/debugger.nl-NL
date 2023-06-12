---
description: Experience Cloud Debugger-gereedschappen, scherm
keywords: foutopsporing;ervaring met cloudfoutopsporingsextensie;chroom;extensie;gereedschappen;dtm;target
seo-description: Experience Cloud Debugger Tools screen
seo-title: Tools
title: Tools
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
exl-id: ad108515-030f-4790-a29c-70f82e58a55d
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 1%

---

# Tools{#tools}

Op het scherm van Hulpmiddelen, kunt u diverse hulpmiddelen voor de geïnstalleerde oplossing toelaten of onbruikbaar maken. U kunt bijvoorbeeld de foutopsporingsinstructies voor de console van Target inschakelen of de DTM Staging Library gebruiken. Deze gereedschappen zijn alleen beschikbaar als Target en DTM op de pagina zijn geïnstalleerd.

![](assets/tools.jpg)

U kunt Adobe Experience Platform Launch of DTM dynamisch op elke pagina invoegen om iets te testen op een pagina waarop geen Platform launch of DTM is geïnstalleerd. Klik op de knop **[!UICONTROL Embed Code]** pictogram, dan typ uw [code insluiten](https://docs.adobe.com/content/help/en/dtm/using/client-side/deployment.html) en klik op **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## DTM-informatie {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Gereedschap </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> Logboekregistratie DTM-console </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel stelt DTM-specifieke het zuiveren verklaringen aan de browser console bloot. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Staging-bibliotheek gebruiken </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel gebruikt de Staging bibliotheek voor DTM het zuiveren informatie. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>DTM uitschakelen </p> </td> 
   <td colname="col2"> <p>Met dit gereedschap wordt voorkomen dat DTM-informatie wordt gecontroleerd. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> DTM dynamisch invoegen </p> </td> 
   <td colname="col2"> <p> Met dit gereedschap wordt DTM-code op de pagina ingevoegd. Gebruik de Ingebedde redacteur van de Code om de code uit te geven die wordt opgenomen. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Doelgegevens {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Gereedschap </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Logboekregistratie doelconsole </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel stelt doel-specifieke het zuiveren verklaringen aan de browser console bloot, allen die met het beginnen van <span class="codeph"> AT:</span> prefix, door een geroepen koekje toe te voegen <span class="codeph"> mboxDebug=true</span> naar uw browser. Op dit ogenblik, verschijnen de consoleverklaringen niet binnen het Debugger Logs scherm, maar zijn zichtbaar in de browser inheemse het zuiveren console. </p> <p> Voor dit gereedschap is 0.js 0.9.6+ vereist. Als u een oudere versie van at.js gebruikt, kunt u toevoegen <span class="codeph"> ?mboxDebug=true</span> de parameter van het vraagkoord aan uw URL om consoleregistratie aan te zetten. Als u mbox.js gebruikt, kunt u toevoegen <span class="codeph"> ?_AT_Debug=console</span> parameter om consoleregistratie aan te zetten beperkt tot de activiteiten van Visual Experience Composer. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox-sporen inschakelen </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel voegt gedetailleerde informatie aan de Reacties van het Doel toe, die in <span class="uicontrol"> Doel&gt;Mbox-overtrek</span> scherm van debugger. </p> <p> U moet op een van uw tabbladen van Chrome zijn aangemeld bij de Experience Cloud om dit gereedschap in te schakelen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Doel uitschakelen </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel maakt alle verzoeken van het Doel onbruikbaar door een koekje toe te voegen genoemd <span class="codeph"> mboxDisable=true</span> naar uw browser. </p> <p> Voor dit gereedschap is 0.js 0.9.6+ vereist. Als u een oudere versie gebruikt, kunt u de opdracht <span class="codeph"> ?mboxDisable=true </span>de parameter van het vraagkoord aan uw URL om dozen onbruikbaar te maken. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox Highlight </p> </td> 
   <td colname="col2"> <p> Met dit gereedschap tekent u een rood kader rond verouderde, omloopstijlvakken. </p> </td> 
  </tr> 
 </tbody> 
</table>

In de volgende video wordt uitgelegd hoe u de extensie Foutopsporing kunt gebruiken met Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
