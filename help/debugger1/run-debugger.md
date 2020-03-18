---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: Samenvattingsscherm
title: Samenvattingsscherm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: d7a54ea531ac09ea6bee356e47a1da835b3880e8

---


# Samenvattingsscherm{#summary-screen}

Als u Foutopsporing in de cloud wilt uitvoeren, klikt u op het extensiepictogram in de extensiebalk en opent u vervolgens de pagina die u wilt onderzoeken in Chrome.

![](assets/start-icon.jpg)

Het scherm Adobe Experience Cloud Debugger Summary wordt weergegeven.

![](assets/summary.jpg)

In dit scherm ziet u een miniatuur van de pagina, de URL en de titel van de pagina. Het bevat ook informatie over elke Adobe Experience Cloud-oplossing. De getoonde informatie varieert per oplossing, maar omvat typisch informatie met inbegrip van de oplossingsbibliotheek en versie (bijvoorbeeld, &quot;AppMeasurement v2.9&quot;) en rekeningsherkenningstekens (zoals de het rapportsuite identiteitskaart van de Analyse, de de cliëntcode van het Doel, de de partneridentiteitskaart van de Manager van het Publiek, etc.)

De aantallen in blauw naast de lusjes bij de bovenkant van het venster tonen het aantal servervraag die is gemaakt. U kunt deze terugstellen aan nul door binnen **[!UICONTROL Clear All Requests]** het respectieve lusje te klikken.

In de volgende afbeelding ziet u bijvoorbeeld informatie over Adobe Target. Merk op dat om de hieronder getoonde activiteitendetails zonder authentificatie bloot te stellen, u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager moet uitvoeren en de noodzakelijke [reactietokens](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) in het Doel UI aanzetten.

![](assets/summary-target2.jpg)

## Audit uitvoeren in Auditor {#section-82bc57440406461ebf27a16855b71655}

U kunt Adobe Auditor gebruiken om een reeks controles op uw pagina in werking te stellen. Als u Auditor wilt uitvoeren, klikt u **[!UICONTROL Auditor]** in het bovenste menu en vervolgens op **[!UICONTROL Audit Page Now]**. Klik op Adobe Auditor om deze te openen **[!UICONTROL Run Multi-Page Audit Now]**.

## Informatie die wordt weergegeven in Foutopsporing {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Debugger toont de volgende informatie voor elke oplossing:

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
   <td colname="col2"> <p>De naam die is opgegeven in de tag <span class="codeph"> &lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsuite(s) </p> </td> 
   <td colname="col2"> <p>Een <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> rapportsuite</a> definieert de volledige, onafhankelijke rapportage op een gekozen website, set websites of subset van webpagina's </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> versie AppMeasurement</a> die is gedefinieerd voor de pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie bezoeker </p> </td> 
   <td colname="col2"> <p>De versie van de bibliotheek met <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> bezoekersidentiteitskaart</a> . </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Paginanaam </p> </td> 
   <td colname="col2"> <p>De variabele <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> die naar Analytics wordt verzonden die een gebruikersvriendelijke naam van de site bevat. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Modules </p> </td> 
   <td colname="col2"> <p>De modules die door Adobe Analytics zijn geladen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Auditiebeheer**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> partnernaam</a> voor de instantie DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>Het<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> versienummer</a> van de instantie DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> unieke gebruikersnaam</a> die aan het DIL-exemplaar is gekoppeld </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Naam </p> </td> 
   <td colname="col2"> <p>De naam van de <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> eigenschap Adobe Launch</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Bouwdatum </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> bouwdatum van de bibliotheek</a> starten </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Omgeving </p> </td> 
   <td colname="col2"> <p>De <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> omgeving</a> die wordt gebruikt door de Launch-bibliotheek </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Scriptmap </p> </td> 
   <td colname="col2"> <p>De map waarin het script Launch is opgeslagen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bibliotheeknaam </p> </td> 
   <td colname="col2"> <p>De naam van de Adobe DTM<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> -bibliotheek</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Bouwdatum </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> bouwdatum van de bibliotheek</a> starten </p> </td> 
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
   <td colname="col2"> <p>Je <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> organisatie-id</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van de bibliotheek met<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> bezoekersidentiteitskaart</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe-doel**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Clientcode </p> </td> 
   <td colname="col2"> <p>Uw doelclientcode <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"></a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>Uw huidige versie <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> of mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Algemene naam van box </p> </td> 
   <td colname="col2"> <p>Het<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> globale mbox</a> verwijst naar de enige servervraag die bij de bovenkant van elke Web-pagina in uw implementatie van het Doel wordt gemaakt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox-naam </p> </td> 
   <td colname="col2"> <p>De naam van een vak rond een <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> locatie</a> op de pagina. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam activiteit </p> </td> 
   <td colname="col2"> <p>De naam van de doelcampagne of -activiteit <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"></a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Activiteits-id </p> </td> 
   <td colname="col2"> <p>De id van de doelactiviteit. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam ontvanger </p> </td> 
   <td colname="col2"> <p>De naam van de <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> ervaring</a>van het Doel. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Recipe-id </p> </td> 
   <td colname="col2"> <p>De id van het doelrecept. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Voorstel </p> </td> 
   <td colname="col2"> <p>De naam van de <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> aanbieding</a>van het Doel. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aanbieding-id </p> </td> 
   <td colname="col2"> <p>De id van de Target-aanbieding. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens</a> in het Doel UI aanzet. </p> </td> 
  </tr> 
 </tbody> 
</table>
