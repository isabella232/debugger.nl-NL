---
description: Samenvattingsscherm Foutopsporing Experience Platform
keywords: debugger;ervaring Platform Debugger uitbreiding;chroom;uitbreiding;samenvatting;duidelijk;verzoeken;samenvattingsscherm;oplossing;informatie;analyse;doel;dtm;publieksmanager;start;id de dienst
seo-description: Samenvattingsscherm Foutopsporing Experience Platform
seo-title: Samenvattingsscherm
title: Samenvattingsscherm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 91234125-15c4-4111-9ee4-f3af093a3c4d
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '979'
ht-degree: 2%

---

# Samenvattingsscherm{#summary-screen}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger bevindt zich momenteel in bèta. De documentatie en de functionaliteit kunnen worden gewijzigd.

Als u Adobe Experience Platform Debugger wilt uitvoeren, klikt u op het pictogram op de browserbalk en opent u de pagina die u wilt controleren in de browser.

![](assets/start-icon.jpg)

Het scherm Adobe Experience Platform Debugger Summary wordt weergegeven.

![](assets/summary.jpg)

Dit scherm bevat informatie over elke Adobe Experience Cloud-oplossing. De getoonde informatie varieert per oplossing, maar omvat typisch informatie met inbegrip van de oplossingsbibliotheek en versie (bijvoorbeeld, &quot;AppMeasurement v2.9&quot;) en rekeningsherkenningstekens (zoals de het rapportsuite identiteitskaart van de Analyse, de cliëntcode van het Doel, identiteitskaart van de partner van de Audience Manager, etc.)

## Informatie die wordt weergegeven in Foutopsporing Experience Platform

Foutopsporing van het Experience Platform toont de volgende informatie voor elke oplossing:

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsuite(s) </p> </td> 
   <td colname="col2"> <p>Een <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> rapportsuite</a> definieert de volledige, onafhankelijke rapportage op een gekozen website, een set websites of een subset van webpagina's </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> versie die voor de pagina wordt bepaald </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie bezoeker </p> </td> 
   <td colname="col2"> <p>De versie van de <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> bezoekersidentiteitskaart</a> bibliotheek. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Paginanaam </p> </td> 
   <td colname="col2"> <p>De variabele <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> die naar Analytics wordt verzonden die een gebruikersvriendelijke naam van de plaats bevat. </p> </td> 
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
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> partnernaam</a> voor de instantie van DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>Het <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> versienummer</a> voor de instantie van DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>De <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> Unieke gebruikersnaam</a> is gekoppeld aan de instantie DIL </p> </td> 
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
   <td colname="col2"> <p>De versie van Turbine</a> </p> </td> 
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
   <td colname="col1"> <p>Extensies </p> </td> 
   <td colname="col2"> <p>De extensies die op de pagina worden gebruikt </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Web SDK**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bibliotheekversie </p> </td> 
   <td colname="col2"> <p>Het nummer van de Adobe Experience Platform Web SDK <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">bibliotheekversie</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naamruimte</p> </td> 
   <td colname="col2"> <p>De naam die is geïdentificeerd in de extensie</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Eigenschap-id </p> </td> 
   <td colname="col2"> <p>De naam van de eigenschap Platform launch die is opgegeven in de extensie </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Edge-domein </p> </td> 
   <td colname="col2"> <p>Het domein dat de extensie Adobe Experience Platform verzendt en gegevens ontvangt van </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>IMS-organisatie-id </p> </td> 
   <td colname="col2"> <p>De organisatie waarnaar u de gegevens wilt verzenden die bij Adobe worden verzonden, zoals opgegeven in de extensie </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aanmelding ingeschakeld </p> </td> 
   <td colname="col2"> <p>Geeft aan of logboekregistratie is ingeschakeld voor deze eigenschap</p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID Service**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID </p> </td> 
   <td colname="col2"> <p>Uw <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organisatie-id</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versie </p> </td> 
   <td colname="col2"> <p>De versie van de <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> bezoekersidentiteitskaart</a> bibliotheek </p> </td> 
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
   <td colname="col1"> <p>Algemene aanvraagnaam </p> </td> 
   <td colname="col2"> <p>Globale mbox<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> verwijst naar de enige servervraag die bij de bovenkant van elke Web-pagina in uw implementatie van het Doel wordt gemaakt</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Gebeurtenis bij laden van pagina </p> </td> 
   <td colname="col2"> <p>Het type gebeurtenis <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">a1/&gt; dat wordt geactiveerd wanneer de pagina wordt geladen</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam aanvraag </p> </td> 
   <td colname="col2"> <p>De naam van een verzoek rond een <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> plaats</a> op de pagina. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
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
   <td colname="col1"> <p>Naam van ervaring </p> </td> 
   <td colname="col2"> <p>De naam van het Doel <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> ervaring</a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ervaring-id </p> </td> 
   <td colname="col2"> <p>De id van de doelervaring. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Naam voorstel</p> </td> 
   <td colname="col2"> <p>De naam van het doel <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> aanbieding</a>. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aanbieding-id </p> </td> 
   <td colname="col2"> <p>De id van de Target-aanbieding. Beschikbaar zonder authentificatie slechts als u de het Zuiveren gebeurtenisluisteraar in uw code of markeringsmanager implementeert en de noodzakelijke <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> reactietokens </a> in het Doel UI aanzet. </p> </td> 
  </tr> 
 </tbody> 
</table>
