---
title: Referentie voor test met tagaanwezigheid
description: Leer hoe de controlefunctie de aanwezigheid van tags in Adobe Experience Platform Debugger test.
exl-id: 8f01f89e-2a3b-41bc-b971-f3c60d0ae3fa
source-git-commit: f18828bcaa0d244bd5b117fd8bf1c1cdba4d4b52
workflow-type: tm+mt
source-wordcount: '605'
ht-degree: 4%

---

# Referentie voor de test met de aanwezigheid van de tag

Deze verwijzing verstrekt meer informatie over hoe de controleureigenschap in Debugger van Adobe Experience Platform op markeringsaanwezigheid test.

>[!NOTE]
>
>For more information on auditor tests in Platform Debugger, see the [auditor feature overview](./overview.md).

Tests met tagaanwezigheid evalueren of bepaalde tags op de pagina voorkomen en of deze zich op de juiste plaats in de paginacode bevinden.

| Testen | Dikte | Criteria | Aanbeveling |
| --- | --- | --- | --- |
| Advertising Cloud - Code-aanwezigheid | 5 | De Advertising Cloud-tag is niet beschikbaar in het DOM. | Implement the Advertising Cloud tag using the [Advertising Cloud tag extension](https://experienceleague.adobe.com/docs/experience-platform/destinations/catalog/advertising/adobe-advertising-cloud.html). |
| Advertising Cloud - Geïmplementeerde segmentpixel | 5 | Upgrade your Advertising Cloud segment pixels to the new Advertising Cloud image-only tags. Het gebruik van verouderde AMO-segmenttags kan leiden tot gegevensverlies. | Implement the Advertising Cloud segment pixel using the [Advertising Cloud tag extension](https://experienceleague.adobe.com/docs/experience-platform/destinations/catalog/advertising/adobe-advertising-cloud.html). |
| Analyse - geladen in DOM | 5 | De Adobe Analytics-tag is niet gedetecteerd. | Install the latest version of Analytics. <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/analytics/implementation/home.html) |
| Starten - Bibliotheek geladen | 5 | A `global _satellite` object was not found in the DOM, meaning that the tag library is either not installed or failing to execute. | Verify that the tag library is implemented on the page and is not blocked by subsequent script activities. |
| Starten - Er zijn niet meerdere ingesloten scripts | 5 | Productieplaatsen mogen slechts één insluitcode per pagina laden. | Verify that only the production library is loading on the page. |
| Starten - `pageBottom` callback bestaat in `<body>` | 5 | De vereiste `_satellite.pageBottom()` callback is niet gevonden in het dialoogvenster `<body>` van de pagina. Deze test mislukt als de `pageBottom` de vraag wordt niet gevonden bij allen op de pagina, of als het in `<head>` -tag (of een andere onverwachte locatie). Het gaat alleen door als `pageBottom` bevindt zich ergens in de `<body>` tag. | Voeg het inlinescript onmiddellijk vóór het sluiten toe `</body>` -tags gebruiken voor de juiste functionaliteit van tags.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-platform/tags/client-side/asynchronous-deployment.html) |
| Starten - `pageBottom` callback zou niet moeten bestaan wanneer asynchroon opgesteld | 5 | De `_satellite.pageBottom()` callback is gevonden op de pagina, wat niet het geval zou moeten zijn wanneer de markeringen asynchroon worden opgesteld. | Remove the `_satellite.pageBottom()` script to enable proper tags functionality. <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-platform/tags/client-side/asynchronous-deployment.html) |
| Experience Cloud ID-service - Code-aanwezigheid | 5 | De Experience Cloud ID-servicecode is niet gevonden. Using Experience Cloud IDs (ECIDs) is highly recommended to ensure you get the most value out of your Experience Cloud solutions and is critical to ID management across Experience Cloud solutions. | Installeer de meest recente versie van ECID.<br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/id-service/using/intro/overview.html) |
| Experience Cloud ID Service - Cookie presence | 5 | The `AMCV_` cookie was not found. U moet een bezoekersobject instantiëren vanuit het dialoogvenster `VisitorAPI.js` code. | Als dit een implementatie van tags is, controleert u of de AdobeOrg-id correct is ingevoerd in de ECID-tool. <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/id-service/using/intro/cookies.html) |
| Experience Cloud ID-service - MID-waarde aanwezig | 5 | The MID value was not found in the `AMCV_` cookie. | Test opnieuw om te controleren op een eventuele vertraging van de ECID API. If the condition persists, contact Adobe Customer Care. <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/id-service/using/intro/cookies.html) |
| Doel - Code-aanwezigheid | 5 | Adobe Target moet in het DOM worden gedefinieerd. | Installeer de meest recente versie van Target (at.js). <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/target/using/implement-target/implementing-target.html) |
| Target - Library loaded in `<head>` | 4 | De doelbibliotheek moet in het dialoogvenster `<head>` tag. | Controleer of de doelbibliotheek is geladen in het dialoogvenster `<head>` tag. <br><br>[Aanvullende informatie](https://experienceleague.adobe.com/docs/target/using/implement-target/implementing-target.html) |

{style=&quot;table-layout:auto&quot;}
