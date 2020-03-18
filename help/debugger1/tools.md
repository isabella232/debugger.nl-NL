---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: Gereedschappen
title: Gereedschappen
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: d7a54ea531ac09ea6bee356e47a1da835b3880e8

---


# Gereedschappen{#tools}

Op het scherm van Hulpmiddelen, kunt u diverse hulpmiddelen voor de geïnstalleerde oplossing toelaten of onbruikbaar maken. U kunt bijvoorbeeld de foutopsporingsinstructies voor de console van Target inschakelen of de DTM Staging Library gebruiken. Deze gereedschappen zijn alleen beschikbaar als Target en DTM op de pagina zijn geïnstalleerd.

![](assets/tools.jpg)

U kunt Launch of DTM dynamisch invoegen op elke pagina om iets te testen op een pagina waarop Launch of DTM niet is geïnstalleerd. Klik op het **[!UICONTROL Embed Code]** pictogram, typ de [insluitcode](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) en klik op **[!UICONTROL Save]**.

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
   <td colname="col2"> <p>Dit hulpmiddel stelt doel-specifieke het zuiveren verklaringen aan de browser console, allen die met <span class="codeph"> AT beginnen bloot:</span> door een cookie met de naam <span class="codeph"> mboxDebug=true</span> aan uw browser toe te voegen. Op dit ogenblik, verschijnen de consoleverklaringen niet binnen het Debugger Logs scherm, maar zijn zichtbaar in de browser inheemse het zuiveren console. </p> <p> Voor dit gereedschap is 0.js 0.9.6+ vereist. Als u een oudere versie van at.js gebruikt, kunt u de parameter van het <span class="codeph"> ?mboxDebug=true</span> vraagkoord aan uw URL toevoegen om consoleregistratie aan te zetten. Als u mbox.js gebruikt, kunt u de parameter toevoegen <span class="codeph"> ?_AT_Debug=console</span> om consoleregistratie aan te zetten die tot de activiteiten van Composer van de Visuele Ervaring wordt beperkt. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox-sporen inschakelen </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel voegt gedetailleerde informatie aan de Reacties van het Doel toe, die in het <span class="uicontrol"> Doel&gt;scherm van het Spoor</span> van het Debugger kan worden onderzocht. </p> <p> U moet op een van uw tabbladen voor Chrome zijn aangemeld bij de Experience Cloud om dit gereedschap in te schakelen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Doel uitschakelen </p> </td> 
   <td colname="col2"> <p>Dit hulpmiddel maakt alle verzoeken van het Doel onbruikbaar door een koekje genoemd <span class="codeph"> mboxDisable=true</span> aan uw browser toe te voegen. </p> <p> Voor dit gereedschap is 0.js 0.9.6+ vereist. Als u een oudere versie gebruikt, kunt u de parameter van het <span class="codeph"> ?mboxDisable=true </span>vraagkoord aan uw URL toevoegen om dozen onbruikbaar te maken. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox Highlight </p> </td> 
   <td colname="col2"> <p> Met dit gereedschap tekent u een rood kader rond verouderde, omloopstijlvakken. </p> </td> 
  </tr> 
 </tbody> 
</table>

In de volgende video wordt uitgelegd hoe u de extensie Foutopsporing kunt gebruiken met Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
