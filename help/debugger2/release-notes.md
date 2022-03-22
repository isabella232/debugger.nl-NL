---
description: Experience Platform Debugger release notes
keywords: debugger;experience Platform Debugger extension;chrome;extension;release notes
title: Release Notes Experience Platform Debugger
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 2778ba78de3350ed1da01d452e303476b04c0303
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 1%

---

# Aanvullende informatie{#release-notes}

## Aanvullende informatie {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 1.3.0 - January 28, 2022

* Koppeling Informatie toegevoegd om huidige releaseversie en notities weer te geven.
* Toegevoegde schakeloptie voor het weergeven van uitgevoerde resultaten voor analytische aanvragen. The toggle is available in the Analytics section.
* Probleem met externe foutopsporingssessie verholpen toen de sessie buiten foutopsporing werd gesloten.
* Het foutbericht dat werd weergegeven op het tabblad Edge Transactions van de Web SDK. Dit probleem is nu opgelost.
* Correctie van Adobe-tags op waarschuwing voor pagina-afdrukking wanneer de foutopsporing het object _satelliet heeft geopend.
* Probleem verholpen waarbij een instantie AppMeasurement niet op de pagina werd gevonden.
* Fixed page connection issue which occurred when first opening the debugger window.

## Versie 1.2.0 - 26 oktober 2021

* Gebeurtenissen weergeven vanaf alle browsertabbladen in de netwerkweergave. To only see the events from the current tab, click on the lock icon in the lower right corner of the debugger.
* Bijgewerkte branding.

## Versie 1.1.0 - 5 oktober 2021

* Visualisatie van foutopsporing op afstand - Organiseer de gebeurtenissen voor foutopsporing op afstand in een visueel stroomdiagram in de sectie Adobe Experience Platform Web SDK > Edge Transactions.
* Require the Adobe Experience Platform Web SDK IMS org used on the page match the logged in org when starting a new remote debugging session.
* Alleen de randtransacties voor het verbonden tabblad weergeven.

> **Note:** Target trace logs are still available in the Logs > Edge section.
* Sta afzonderlijke de configuratieopheffing van identiteitskaart van de gegevensstroom voor elke instantie van het Web SDK van Adobe Experience Platform op de pagina toe. Add debug enabled toggle.
* Probleem verholpen waarbij het Adobe Target-traceringstoken niet altijd werd verzonden met foutopsporingssessies op afstand voor de Adobe Experience Platform Web SDK.

## Versie 1.0.0 5 mei 2021

* Eerste hoofdrelease van foutopsporing van Experience Platform. Bedoeld om de Experience Cloud Debugger te vervangen.
