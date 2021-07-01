---
description: Het scherm van het Netwerk van Foutopsporing van het Experience Platform
keywords: foutopsporing;ervaring met Platform debugger-extensie;chroom;extensie;netwerk;informatie
seo-description: Het scherm van het Netwerk van Foutopsporing van het Experience Platform
seo-title: Netwerkinformatie
title: Netwerkinformatie
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: ed0579ef-ec26-43df-9453-a395c105038a
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 2%

---

# Netwerk{#network}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger bevindt zich momenteel in bèta. De documentatie en de functionaliteit kunnen worden gewijzigd.

Klik op **[!UICONTROL Network]** om netwerkinformatie weer te geven.

Het scherm van het Netwerk aggregeert alle de oplossingsvraag van Adobe Experience Cloud die op de pagina wordt gemaakt en toont hen in orde van links naar rechts. Standaardparameters worden automatisch geëtiketteerd met vriendelijke namen en gerangschikt om gemeenschappelijke parameters op dezelfde rol te groeperen.

![](assets/network.jpg)

Dit scherm is nuttig om zeer belangrijke waardeparen over klappen te vergelijken. U kunt bevestigen dat de parameters die voor integratie worden gebruikt, zoals identiteitskaart van de Bezoeker van de Experience Cloud of Supplementale identiteitskaart van Gegevens, over integratie verenigbaar zijn.

>[!NOTE]
>
>Op dit ogenblik, zijn niet alle parameters die in de oplossingsvraag worden overgegaan (bijvoorbeeld, de contextvariabelen van Analytics, de douaneparameters van het Doel, of de Klant IDs van de Dienst van Experience Cloud ID) zichtbaar in het scherm van het Netwerk.

Om de informatie door oplossing te veranderen, selecteer de oplossing u van de lijst in linkernav wilt bekijken. In het volgende voorbeeld wordt alleen Analytics weergegeven:

![](assets/network-analytics.jpg)

Als u alle oplossingen wilt weergeven, klikt u op **[!UICONTROL Network]**

Klik op een item in de netwerkweergave om een uitgebreide weergave te zien. Vanuit het uitgevouwen weergavevenster kunt u de weergegeven informatie naar het klembord kopiëren.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Als u de lijst wilt wissen, klikt u op **[!UICONTROL Remove Events]**.

Als u een Excel-bestand met de informatie op dit scherm wilt downloaden, klikt u op **[!UICONTROL Download]**.
