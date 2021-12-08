---
keywords: adobe experience cloud cloud;Adobe Experience Cloud;device co-op;Device Co-op;end of life
title: Device Co-op - frågor och svar om upphörande av livscykel
description: Läs mer om slutversionsplanerna för Device Co-op.
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: 8896718ce5fec25cb72f7a2a5ccb4573433e0bb1
workflow-type: tm+mt
source-wordcount: '1019'
ht-degree: 1%

---

# Device Co-op - frågor och svar om upphörande av livscykel

I det här dokumentet finns svar på vanliga frågor om Adobe Experience Cloud Device Co-op End-of-life-planen (EOL). När denna plan träder i kraft kommer Adobe att lämna ett förhandsmeddelande i [Versionsinformation för Experience Cloud](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html) och [Prioriterad produktuppdatering](https://www.adobe.com/subscription/priority-product-update.html).

## Vanliga frågor och svar 

Här följer en lista med svar på vanliga frågor om [!DNL Device Co-op] EOL-plan.

## Varför [!DNL Device Co-op] är borttagen?

De kommande ändringarna i AdTech-miljön förväntas resultera i [!DNL Device Co-op] att bli en föråldrad lösning under de närmaste åren. [!DNL Device Co-op] består huvudsakligen av cookies från tredje part och [!DNL Google's] meddelande om att de kommer att blockera cookies från tredje part på [!DNL Google Chrome] 2022 kommer att minska [!DNL Device Co-op]. [!DNL Chrome] har cirka 65 % av webbläsarens marknadsandel och andra större webbläsare har redan infört blockering av cookies från tredje part. En gång [!DNL Chrome] blockerar cookies från tredje part blockerar merparten av cookies från tredje part och [!DNL Device Co-op] kommer att bli föråldrad.

## Varför slutar Adobe [!DNL Device Co-op] registreringar nu?

Registreringar upphör för att förhindra risken för att inte uppfylla kundernas förväntningar på grund av kommande branschförändringar kring cookies från tredje part. [!DNL Device Co-op] tar några månader att förbereda och ytterligare några månader att extrahera värdet från tjänsten. Ytterligare registreringar kan leda till att varumärken inte får det fulla värdet av [!DNL Device Co-op].

## Kan nya kunder anmäla sig?

Från och med 11 juni 2021 accepterar Adobe inte längre nya registreringar till [!DNL Device Co-op].

## Förnyas befintliga kontrakt?

Från och med 11 juni 2021 kommer Adobe inte längre att förnya [!DNL Device Co-op] kontrakt. Om du vill fortsätta använda [!DNL Device Co-op] kan du fortsätta göra det i enlighet med de gällande licensvillkoren tills programmet upphör.

## Vad är det exakta slutdatumet för [!DNL Device Co-op] program?

The [!DNL Device Co-op] Programmet avslutas 2022. Den specifika tidpunkten och datumet beror på när [!DNL Google] börjar blockera cookies från tredje part.

## Vilka program kommer att påverkas av Device Co-op?

Följande program påverkas av [!DNL Device Co-op] förfaranden vid avslutad livstid:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## Vilka alternativ har jag som alternativ till [!DNL Device Co-op]?

### [!DNL Analytics]

Du kan använda [!DNL Analytics] [Enhetsövergripande analys (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) eftersom den har stöd för båda Adobe Experience Platform Identity Service [Privat diagram](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) och [Fältbaserad textning](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] behåller integreringar med tredjeparts partner för enhetsgrafer, inklusive [!DNL LiveRamp] och [!DNL Tapad]även om du måste etablera kommersiella relationer direkt med diagrampartners för att kunna utnyttja [!DNL Audience Manager].

### [!DNL Real-time Customer Data Platform]

Det finns inga planer på att ändra den aktuella [!DNL Audience Manager Data Management Platform] (DMP). Borttagning av cookies från tredje part kommer dock troligtvis att medföra stora utmaningar för de flesta DMP-användare. För att hjälpa kunderna att utveckla sina rutiner för datahantering uppmuntrar Adobe till att minska beroendet av identifierare som kommer att drabbas av begränsningar under det kommande året. Marknadsföringsteamen måste bygga strategier för förstahandsdata med fokus på varaktiga identifierare som innehåller personligt identifierbar information, som kan lösas med [!DNL Real-time Customer Data Platform] (CDP i realtid).

[!DNL Real-time CDP] minskar beroendet av cookies och enhets-ID från tredje part genom att utöka den uppsättning identifierare som är tillgänglig för målgruppsskapande till att omfatta PII. Från grunden till [!DNL Real-time CDP] är kundprofil i realtid, som sammanför personattributdata med beteendedata i realtid och gör det möjligt för marknadsförare att skapa avancerade målgruppssegment med patenterade datastyrningskontroller. Gilla [!DNL Audience Manager], [!DNL Real-time CDP] ger er insikter om och användningsexempel på personalisering, men också genererar mer detaljerade insikter på personnivå och kan aktivera målgrupper för ett större urval av destinationer som omfattar marknadsföringsteknologier och marknadsföringsteknologier, inklusive betalda medier, sociala medier, e-post och kundsystem.

[!DNL Real-time CDP] ger även tillgång till [Adobe Experience Platform Segment Match (beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en), som gör det möjligt för varumärken att utöka sina egna datauppsättningar från första part genom partnerskap och få bättre insikter och personalisering.

### [!DNL Target]

Det finns för närvarande inga alternativ för [!DNL Target] därför [!DNL Target] ger en deterministisk funktion för stygning av identiteter mellan olika enheter som kallas `mbox3rdPartyId`, som fungerar på samma sätt som Adobe Customer ID. Den här funktionen tillåter [!DNL Target] kunder för att slå samman profiler och aktivitetsdeltagande mellan [!DNL Target] tester och personalisering utförs i inkommande kanaler.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] kunderna inte längre kan använda [!DNL Device Co-op] för målgruppsanpassning och mätning på olika enheter. Med [!DNL Advertising Cloud]kommer du fortfarande att kunna utnyttja Adobe [!DNL Device Graph] partnerskap med [!DNL LiveRamp] fortsätta att utföra dessa funktioner i den utsträckning som [!DNL LiveRamp’s] förmåga och skala. Ni måste tillåta kampanjer som använder [!DNL Device Co-op] till slutet och sedan växla till [!DNL LiveRamp] enhetsdiagramleverantör, eller inte längre utnyttja personbaserad målgruppsanpassning.

## Vilka befintliga funktioner och implementeringar kan hjälpa mig att förbereda mig för en framtid utan cookies?

Implementeringen av din befintliga Visitor ID-tjänst ger Analytics kraft [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). Om ditt befintliga deklarerade ID är ett hashade e-postmeddelande kan det användas för att driva följande funktioner:

- [!DNL Audience Manager] [Personbaserade destinationer](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform segmentmatchning (betaversion)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en).

## Får jag behålla mina data från [!DNL Device Co-op]?

För [!DNL Audience Manager] och [!DNL Advertising Cloud] användare, data från [!DNL Device Co-op] kommer inte att kunna överföras till diagram från tredje part. [!DNL Device Co-op] data migreras endast för [!DNL Analytics Ultimate] användare som använder CDA med [!DNL Device Co-op] gå över till fältbaserad textning. Alla andra lösningar kommer inte att ha sina data migrerade.

## Är det obligatoriskt att använda andra funktioner?

Även om det inte är obligatoriskt att använda andra Adobe-funktioner bör du påbörja implementeringen av andra funktioner så snart som möjligt för att ge tid och lämplig samordning i förväg [!DNL Device Co-op] borttagning.

## När måste jag anta alternativa lösningar om jag väljer att göra det?

Andra funktioner är inte obligatoriska. Vi rekommenderar endast om du vill fortsätta att behandla användningsfall som har åtgärdats av [!DNL Device Co-op]. Om du väljer att använda andra funktioner måste du göra det senast 2022 (exakt tajmning ska tillkännages) före [!DNL Device Co-op] programmet avslutas.

## Hur lång tid tar antagandet?

Detta beror på funktionen. Om en Analytics Ultimate-kund till exempel använder enhetsövergripande analys med [!DNL Device Co-op] måste migrera till Privat enhetsgrafik i realtid eller fältbaserad svällning, men implementeringen tar lite tid.
