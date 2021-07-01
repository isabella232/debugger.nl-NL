---
description: Experience Cloud Debugger wordt uitgevoerd
keywords: foutopsporing;ervaring met de extensie voor foutopsporing in de cloud;chroom;extensie;samenvatting;wissen;verzoeken;overzichtsscherm;oplossing;informatie;analyse;doel;dtm;publieksbeheer;starten;id-service
seo-description: Experience Cloud Debugger wordt uitgevoerd
seo-title: Samenvattingsscherm
title: Samenvattingsscherm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 0ee0314b-1611-4581-ae54-2c784e0e56ff
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '1069'
ht-degree: 2%

---

# Samenvattingsscherm{#summary-screen}

Als u Foutopsporing voor Adobe Experience Cloud wilt uitvoeren, klikt u op het extensiepictogram in de extensiebalk en opent u de pagina die u wilt onderzoeken in Chrome.

![](assets/start-icon.jpg)

Het scherm Experience Cloud Debugger Summary wordt weergegeven.

![](assets/summary.jpg)

In dit scherm ziet u een miniatuur van de pagina, de URL en de titel van de pagina. Het toont ook informatie over elke oplossing van Adobe Experience Cloud. De getoonde informatie varieert per oplossing, maar omvat typisch informatie met inbegrip van de oplossingsbibliotheek en versie (bijvoorbeeld, &quot;AppMeasurement v2.9&quot;) en rekeningsherkenningstekens (zoals de het rapportsuite identiteitskaart van de Analyse, de cliëntcode van het Doel, identiteitskaart van de partner van de Audience Manager, etc.)

De aantallen in blauw naast de lusjes bij de bovenkant van het venster tonen het aantal servervraag die is gemaakt. U kunt deze aan nul terugstellen door **[!UICONTROL Clear All Requests]** binnen het respectieve lusje te klikken.

In de volgende afbeelding wordt bijvoorbeeld informatie over Adobe Target weergegeven. Merk op dat om de hieronder getoonde activiteitendetails zonder authentificatie bloot te stellen, u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager moet uitvoeren en de noodzakelijke [reactietokens ](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) in het Doel UI aanzetten.

![](assets/summary-target2.jpg)

## Een audit uitvoeren in Adobe Experience Platform Auditor {#section-82bc57440406461ebf27a16855b71655}

U kunt de Auditor van het Platform gebruiken om een reeks controles op uw pagina in werking te stellen. Om de Auditor van het Platform in werking te stellen, klik **[!UICONTROL Auditor]** in het hoogste menu, dan klik **[!UICONTROL Audit Page Now]**. Om de Auditor van het Platform te openen, klik **[!UICONTROL Run Multi-Page Audit Now]**.

## Informatie weergegeven in Experience Cloud Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger geeft voor elke oplossing de volgende informatie:

**Pagina-informatie**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Pagina-schermafbeelding </p> </td> 
   <td colname="col2"> <p>Miniatuur van de pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL van de pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titel </p> </td> 
   <td colname="col2"> <p>De naam die is opgegeven in de <span class="codeph"> &lt;TITLE&gt;</span>-tag </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsuite(s) </p> </td> 
   <td colname="col2"> <p>Een <a href="https://docs.adobe.com/content/help/en/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external"> rapportsuite</a> definieert de volledige, onafhankelijke rapportage op een gekozen website, een set websites of een subset van webpagina's </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobe.com/content/help/en/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a> versie die voor de pagina wordt bepaald </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie bezoeker </p> </td> 
   <td colname="col2"> <p>De versie van de <a href="https://docs.adobe.com/content/help/en/analytics/technotes/visitor-identification.html" format="html" scope="external"> bezoekersidentiteitskaart</a> bibliotheek. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Paginanaam </p> </td> 
   <td colname="col2"> <p>De variabele <a href="https://docs.adobe.com/content/help/en/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external"> pageName</a> die naar Analytics wordt verzonden die een gebruikersvriendelijke naam van de plaats bevat. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Modules </p> </td> 
   <td colname="col2"> <p>De door Adobe Analytics geladen modules </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external"> partnernaam</a> voor de instantie van DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>Het <a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external"> versienummer</a> voor de instantie van DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external"> Unieke gebruikersnaam</a> is gekoppeld aan de instantie DIL </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Naam </p> </td> 
   <td colname="col2"> <p>De naam van de Platform launch <a href="https://docs.adobe.com/content/help/en/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external"> eigenschap</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Bouwdatum </p> </td> 
   <td colname="col2"> <p>De Platform launch <a href="https://docs.adobe.com/content/help/en/launch/using/reference/publish/libraries.html" format="https" scope="external"> bibliotheek</a> bouwdatum </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Omgeving </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobe.com/content/help/en/launch/using/reference/publish/environments.html" format="https" scope="external"> omgeving</a> die door de bibliotheek van de Platform launch wordt gebruikt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Scriptmap </p> </td> 
   <td colname="col2"> <p>De map waarin het script Platform launch is opgeslagen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bibliotheeknaam </p> </td> 
   <td colname="col2"> <p>De naam van de Adobe DTM<a href="https://docs.adobe.com/content/help/en/dtm/using/library-management.html" format="html" scope="external">-bibliotheek</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Bouwdatum </p> </td> 
   <td colname="col2"> <p>De Platform launch <a href="https://docs.adobe.com/content/help/en/dtm/using/library-management.html" format="html" scope="external"> bibliotheek</a> bouwdatum </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Omgeving </p> </td> 
   <td colname="col2"> <p>De omgeving die door de DTM-bibliotheek wordt gebruikt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Scriptmap </p> </td> 
   <td colname="col2"> <p>De map waarin het DTM-script is opgeslagen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID Service**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID </p> </td> 
   <td colname="col2"> <p>Uw <a href="https://docs.adobe.com/content/help/en/id-service/using/home.html" format="https" scope="external"> Organisatie-id</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van de <a href="https://docs.adobe.com/content/help/en/analytics/technotes/visitor-identification.html" format="html" scope="external"> bezoekersidentiteitskaart</a> bibliotheek </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Clientcode </p> </td> 
   <td colname="col2"> <p>Uw doel <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Clientcode </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>Uw huidige <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> of mbox.js-versie </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Algemene naam van box </p> </td> 
   <td colname="col2"> <p>Globale mbox<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> verwijst naar de enige servervraag die bij de bovenkant van elke Web-pagina in uw implementatie van het Doel wordt gemaakt</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox-naam </p> </td> 
   <td colname="col2"> <p>De naam van een doos rond een <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> plaats</a> op de pagina. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam activiteit </p> </td> 
   <td colname="col2"> <p>De naam van het doel <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> campagne of activiteit</a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Activiteits-id </p> </td> 
   <td colname="col2"> <p>De id van de doelactiviteit. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam ontvanger </p> </td> 
   <td colname="col2"> <p>De naam van het Doel <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> ervaring</a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Recipe-id </p> </td> 
   <td colname="col2"> <p>De id van het doelrecept. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Voorstel </p> </td> 
   <td colname="col2"> <p>De naam van het doel <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> aanbieding</a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aanbieding-id </p> </td> 
   <td colname="col2"> <p>De id van de Target-aanbieding. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
 </tbody> 
</table>
