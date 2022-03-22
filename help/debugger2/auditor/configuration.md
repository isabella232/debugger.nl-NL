---
title: Configuration Test Reference
description: Leer hoe de controleeigenschap configuratie in Foutopsporing van Adobe Experience Platform test.
exl-id: 92b07224-57f1-4891-9923-aa079945e6bc
source-git-commit: f18828bcaa0d244bd5b117fd8bf1c1cdba4d4b52
workflow-type: tm+mt
source-wordcount: '763'
ht-degree: 4%

---

# Referentie voor configuratietest

Deze verwijzing verstrekt meer informatie over hoe de controleeigenschap in Debugger van Adobe Experience Platform configuratietests in werking stelt.

>[!NOTE]
>
>Voor meer informatie over controleurstests in Foutopsporing van het Platform, zie [overzicht van de controlefunctie](./overview.md).

De tests van de configuratie kunnen voor specifieke montages, waarden, of potentiële conflicten in uw implementatie aftasten. De Auditor van het Platform evalueert de markeringen tegen andere regels en geadviseerde beste praktijken.

| Testen | Weight | Criteria | Recommendation |
| --- | --- | --- | --- |
| Advertising Cloud - Conversienamen gebruiken alleen alfanumerieke tekens | 3 | De `ev_conversion_property_name` parameter mag alleen numerieke en decimale waarden bevatten, BEHALVE voor de `ev_transid` parameter, die tekst of numerieke waarden kan bevatten. Look for `everesttech.net` pixels that contain a URL parameter starting with  `ev_`. | Zorg ervoor dat de parameters van de transactieeigenschap alleen numerieke en decimale waarden bevatten.<br><br>Waarschuwing: Andere waardetypen kunnen gegevensverlies veroorzaken. |
| Advertising Cloud - Conversienamen gebruiken URL-veilige tekens | 3 | Namen van conversie-eigenschappen mogen geen en-teken of vraagteken bevatten. | Zorg ervoor dat de parameters van de transactieeigenschap geen niet-gecodeerd en/of vraagteken bevatten. Hiermee wordt de URL-indeling verbroken.<br><br>Warning: Property parameters that contain a non-encoded ampersand or question mark, (for example:  `ev_formComplete?=1` or  `ev_formComplete&Submit=1`), might result in data loss. |
| Advertising Cloud - Transactie-ID correct geïmplementeerd | 1 | The property name  `ev_transid=` should not be empty. | De eigenschapsnaam  `ev_transid=` mag niet zonder waarde worden gelaten. Als dit zonder een waarde wordt verlaten, zou er verlies van transactiegegevens kunnen zijn. Een waarde toewijzen aan `ev_transid=` of verwijder de parameter uit de pixel. |
| Analytics - Instantiated in DOM | 5 | De Adobe Analytics-code is niet geïnstalleerd of kan niet worden uitgevoerd. Retourneert 0 wanneer geen analytische code op de webpagina is gevonden. | Verify that the Analytics tag is implemented on the page and is not blocked by subsequent script activities.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/analytics/implementation/home.html) |
| Analyse - eenmaal geïnstantieerd | 5 | De Adobe Analytics-code is meerdere keren gedetecteerd op de pagina. . Returns 0 when no A-nalytics code is found on the web page. | Zorg ervoor dat er slechts één tag Analytics op de pagina staat.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/analytics/implementation/home.html) |
| Analytics - Latest version | 3 | De meest recente versie van de Codebibliotheek Analytics wordt niet uitgevoerd op uw pagina&#39;s. Code libraries that power Experience Cloud technologies are constantly being updated and tweaked in order to take advantage of performance improvements and provide the latest features. Retourneert 0 wanneer geen analytische code op de webpagina is gevonden. | Installeer de nieuwste versie van de bibliotheek Analytics.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html) |
| Starten - tags van derden worden asynchroon geladen nadat DOM gereed is | 3 | Om een evenwicht tussen een goede gebruikerservaring en het verzamelen van nauwkeurige gegevens te bereiken, zouden de markeringen van derde partijen bij DOM klaar moeten teweegbrengen. Zo zorgt u ervoor dat deze volgende scripts worden uitgevoerd zonder dat dit van invloed is op de functionaliteit van de site. | Los dit probleem op door alle regels aan te passen die derden-pixels uitvoeren om bij DOM Ready te branden.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-platform/tags/ui/rules.html) |
| Experience Cloud ID-service - Laatste versie | 2 | De meest recente versie van de codeblok van de Bezoeker-id-service, bezoekerAPI.js, wordt niet uitgevoerd op uw pagina&#39;s. Codebibliotheken die Experience Cloud-technologieën van stroom voorzien, worden voortdurend bijgewerkt en getweend om te profiteren van prestatieverbeteringen en de nieuwste functies te bieden. | Installeer de nieuwste versie van de bibliotheek met bezoekersidentiteiten.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/id-service/using/id-service-api/library.html) |
| Launch - Latest Version | 2 | These pages are not running the latest version of the tags code library (Turbine). Code libraries that power Experience Cloud technologies are constantly being updated and tweaked in order to take advantage of performance improvements and provide the latest features. | Maak de tagbibliotheek opnieuw en publiceer deze.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-platform/tags/get-started/quick-start.html) |
| Doel - Laatste versie | 2 | De meest recente versie van de doelcodebibliotheek wordt niet uitgevoerd op uw pagina&#39;s. Codebibliotheken die Experience Cloud-technologieën van stroom voorzien, worden voortdurend bijgewerkt en getweend om te profiteren van prestatieverbeteringen en de nieuwste functies te bieden. | Installeer de nieuwste versie van de doelbibliotheek.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/target/using/implement-target/client-side/implement-target-for-client-side-web.html) |
| Doel - mboxDefault komt eerder dan mboxCreate | 5 | Het juiste gebruik van mboxCreate ziet er als volgt uit:<br><br> `<div class="mboxDefault"><!-Customer content--></div><script>mboxCreate('myMboxName')</script>` | Zorg ervoor dat u een  `<div class="mboxDefault"></div>` tag voordat mboxCreate() wordt aangeroepen. om.js zal geen één voor u toevoegen.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/target/using/implement-target/client-side/implement-target-for-client-side-web.html) |
| Doel: geldig DOCTYPE | 5 | Er is een ongeldig DOCTYPE gedetecteerd. In dit scenario worden geen vakjes geactiveerd.  Voor at.js, moet DOCTYPE op de wijze van Normen zijn of het Doel zal niet werken. | Werk het DOCTYPE op de pagina bij.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/target/using/implement-target/client-side/at-js-implementation/faq-at-js/target-atjs-faq.html) |

{style=&quot;table-layout:auto&quot;}
