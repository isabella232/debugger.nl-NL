---
description: Opmerkingen bij de release voor Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: Opmerkingen bij de release voor Experience Cloud Debugger
seo-title: Release-opmerkingen
title: Release-opmerkingen
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: tm+mt
source-wordcount: '699'
ht-degree: 6%

---


# Release-opmerkingen{#release-notes}

## Release-opmerkingen {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Versie 0.0.817 mei 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Nieuwe functies {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nabewerkingsgegevens </p> </td> 
   <td colname="col2"> <p> De mogelijkheid om waarden weer te <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> geven bij treffers voor Analytics nadat de verwerkingsregels zijn uitgevoerd</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Versie 0.0.810 maart 6, 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Nieuwe functies {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Controles van accountants </p> </td> 
   <td colname="col2"> <p> Toegevoegde tests <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> van</a> Auditor aan Foutopsporing </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Foutopsporing geeft nu AAM reacties weer </p> </td> 
  </tr> 
 </tbody> 
</table>

## Bug Fixes {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Probleem verholpen waarbij de voettekst inhoud aan de onderkant van de pagina verbergt.

* De voettekst voor foutopsporing is bijgewerkt
* Het probleem waarbij verouderde terminologie voor Target werd gebruikt, is opgelost.

## Versie 0.0.809 februari 28, 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Nieuwe functies {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Codefuncties insluiten </p> </td> 
   <td colname="col2"> <p> Splits de functies voor het vervangen en invoegen van ingesloten code. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbeteringen {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Oplossing voor een mogelijke kwetsbaarheid die wordt veroorzaakt door niet-gemanipuleerde gebruikersinvoer.

## Bug Fixes {#section-556417ff055848c1bf037354dd43cbd0}

* Probleem verholpen waarbij AAM DIL-gebeurtenissen niet werden vastgelegd op het tabblad AAM. Dit probleem is nu opgelost.

* Probleem verholpen in Dynamisch het Lanceren van het Tussenvoegsel waar het gebruikersinterface aan een verschillende inbedcode leek in kaart te brengen wanneer het niet was
* Probleem verholpen in Launch dynamisch invoegen waarbij een ongeldige URL werd weergegeven. Dit probleem is nu opgelost.
* Probleem verholpen waarbij Foutopsporing de insluitcodes bleef vervangen, zelfs als het venster Foutopsporing werd gesloten. Dit probleem is nu opgelost.

## Versie 0.0.806 september 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Nieuwe functies {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Koppeling Analytics op tabblad Tools </p> </td> 
   <td colname="col2"> <p>Geef vriendelijke namen voor gebeurtenissen/props weer via Analytics API via de IMS-aanmelding. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Starten dynamisch invoegen </p> </td> 
   <td colname="col2"> <p>Via het tabblad Gereedschappen kunt u op elke pagina de functie Starten dynamisch invoegen om te testen wat zich op een pagina bevindt waarop Starten niet is geïnstalleerd. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Verbeteringen voor doel </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Toegevoegde prestatiestijdopnemers voor de verzoeken van het Doel. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Vastleggen adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbeteringen {#section-56003a12c32f4998bf1cf2a25a518592}

* De weergave van het tabblad Netwerk is verbeterd, zodat de hoogte van de tabel niet te groot wordt en de gebruiker verticaal moet schuiven voordat hij of zij horizontaal kan schuiven. Eerder werden de schuifbalken onder aan de tabel weergegeven. Omdat de tabel vrij groot kon worden, moesten gebruikers verticaal omlaag schuiven om ze te kunnen zien.
* De koppeling naar ObservePoint is bijgewerkt via het tabblad Extra.

## Bug Fixes {#section-d9231f5c77254d0888347e5f569a8b1d}

* Probleem verholpen waarbij het tabblad Experience Cloud niet werd bijgewerkt

* Probleem verholpen waarbij Media Optimizer in de rij Oplossing van het tabblad Netwerk werd weergegeven in plaats van de huidige naam &quot;Advertising Cloud&quot;. Dit probleem is nu opgelost.
* Probleem verholpen waarbij Foutopsporing _satelliet op elke pagina injecteerde.

## Versie 0.0.803 10 augustus 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

Versie 0.0.803 omvat geen klant-onder ogen ziet veranderingen.

## Versie 0.0.802 1 augustus 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Nieuwe functies {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Koppeling Auditor op tabblad Extra </p> </td> 
   <td colname="col2"> <p>Een koppeling van Foutopsporing naar Foutopsporing toegevoegd </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Samengevouwen tabs </p> </td> 
   <td colname="col2"> <p>Samengevouwen tabbladen blijven op de tabbladen Overzicht en Gereedschap staan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Klik om weer te geven </p> </td> 
   <td colname="col2"> <p> Functionaliteit voor klikken naar weergave toegevoegd aan alle tabbladen </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbeteringen {#section-0e7090e3e6a645f085d4553b983ecff8}

* Naam van Media Optimizer is gewijzigd in Advertising Cloud
* Verwijderde oplossingen van het lusje van het Netwerk als niet gevonden

## Bug Fixes {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Correctie van een probleem waarbij de functie &#39;Klik op cel om weer te geven&#39; niet was bijgewerkt. Dit probleem is nu opgelost.
* Probleem verholpen waarbij AAM treffers niet werden weergegeven op AAM tabblad

## Versie 0.0.798 14 juni 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Nieuwe functies {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Exportoptie voor Excel </p> </td> 
   <td colname="col2"> <p>De toegevoegde de uitvoeroptie van Excel aan het Netwerk tabel. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Verbeterde weergave </p> </td> 
   <td colname="col2"> <p>Het Chrome-extensiefont is bijgewerkt naar Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Trackpad vegen, functionaliteit </p> </td> 
   <td colname="col2"> <p>Vooruit-/achteruit-trackpad veegfunctie uitgeschakeld. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aanroepindicator van onbewerkte server </p> </td> 
   <td colname="col2"> <p>Toegevoegde indicator dat de ruwe koord van de servervraag is gekopieerd. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Tabblad Logbestanden opschonen </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Verberg oplossingen in de Filter van Oplossingen als geen lijnpunten voor die oplossing in de logboeken worden gevonden </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Verberg het filter Niveau als er geen DTM-aanroepen worden gevonden, omdat het alleen van toepassing is op DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Wijzig de pictogrammen in de kolom Niveau zodat ze er niet klikbaar uitzien wanneer er niets gebeurt wanneer u klikt </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Opmaak van "Code tonen" op DTM-regelitems standaardiseren </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Help-koppeling bijwerken in voettekst </p> </td> 
   <td colname="col2"> <p>Update Help link in footer to <a href="https://docs.adobe.com/content/help/en/debugger/using/experience-cloud-debugger.html" format="https" scope="external"> https://docs.adobe.com/content/help/en/debugger/using/experience-cloud-debugger.html</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Bug Fixes {#section-c292cf7dcb17463bb1928de73bd55121}

* Probleem verholpen waarbij het badnummer niet werd gewist
* Probleem verholpen waarbij een klant lege beknopte gegevens meldde.

## Versie 0.0.797 mei 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Nieuwe functies {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Functie </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Schakelen tussen gereedschappen </p> </td> 
   <td colname="col2"> <p>Er zijn mazen aan het tabblad Doel toegevoegd </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Filterinstellingen blijven nu ongewijzigd </p> </td> 
   <td colname="col2"> <p>De filterinstellingen blijven nu boven aan het scherm op de tabbladen Netwerk en Logboeken. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Netwerkwaarden weergeven en kopiëren </p> </td> 
   <td colname="col2"> <p>U kunt details bekijken en de waarde van om het even welke cel op het netwerklusje kopiëren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Juridische voettekstkoppelingen en copyright </p> </td> 
   <td colname="col2"> <p>Er zijn juridische voettekstkoppelingen en copyrightgegevens toegevoegd aan de gebruikersinterface. </p> </td> 
  </tr> 
 </tbody> 
</table>

