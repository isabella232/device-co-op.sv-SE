---
keywords: adobe experience cloud cloud;Adobe Experience Cloud;device co-op;Device Co-op;end of life
solution: Adobe Experience Cloud
title: Device Co-op - frågor och svar om upphörande av livscykel
description: Läs mer om slutversionsplanerna för Device Co-op.
source-git-commit: b9e21ba2f749b7a4ad69c122e2273b7f3309da58
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 1%

---

# Device Co-op - frågor och svar om upphörande av livscykel

I det här dokumentet finns svar på vanliga frågor om Adobe Experience Cloud Device Co-op End-of-life-planen (EOL). När denna plan träder i kraft kommer Adobe att lämna ett meddelande i förväg i [versionsinformationen för Experience Cloud](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html) och [Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html).

## Vanliga frågor och svar 

Nedan följer en lista med svar på vanliga frågor om [!DNL Device Co-op] EOL-planen.

## Varför är [!DNL Device Co-op] föråldrat?

De kommande förändringarna i AdTech-miljön förväntas leda till att [!DNL Device Co-op] blir en föråldrad lösning under de närmaste åren. [!DNL Device Co-op] omfattar mestadels cookies från tredje part och  [!DNL Google's] information om att de kommer att blockera cookies från tredje part  [!DNL Google Chrome] senast 2022 kommer att minska effektiviteten hos  [!DNL Device Co-op]. [!DNL Chrome] har cirka 65 % av webbläsarens marknadsandel och andra större webbläsare har redan infört blockering av cookies från tredje part. När [!DNL Chrome] blockerar cookies från tredje part blockeras merparten av cookies från tredje part och [!DNL Device Co-op] blir inaktuellt.

## Varför avslutar Adobe [!DNL Device Co-op]-registreringar nu?

Registreringar upphör för att förhindra risken för att inte uppfylla kundernas förväntningar på grund av kommande branschförändringar kring cookies från tredje part. [!DNL Device Co-op] tar några månader att förbereda och ytterligare några månader att extrahera värdet från tjänsten. Ytterligare registreringar kan leda till att varumärken inte upplever det fullständiga värdet [!DNL Device Co-op].

## Kan nya kunder anmäla sig?

Från och med 11 juni 2021 accepterar Adobe inte längre nya registreringar till [!DNL Device Co-op].

## Förnyas befintliga kontrakt?

Från och med 11 juni 2021 kommer Adobe inte längre att förnya [!DNL Device Co-op]-kontrakt. Om du vill fortsätta använda [!DNL Device Co-op]-tjänster kan du fortsätta att göra det enligt de aktuella licensvillkoren tills programmet avslutas.

## Vilket är det exakta slutdatumet för [!DNL Device Co-op]-programmet?

Programmet [!DNL Device Co-op] upphör 2022. Den specifika tidpunkten och datumet beror på när [!DNL Google] börjar blockera cookies från tredje part.

## Vilka program kommer att påverkas av Device Co-op?

Följande program kommer att påverkas av [!DNL Device Co-op]-proceduren för att avsluta livscykeln:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## Vilka alternativ har jag som alternativ till [!DNL Device Co-op]?

### [!DNL Analytics]

Du kan använda funktionen [!DNL Analytics] [Cross-Device Analytics (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) eftersom den har stöd för både Adobe Experience Platform Identity Service [Private Graph](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) och [Fältbaserad Stitching](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] har integreringar med tredjepartspartners för enhetsgrafer, inklusive  [!DNL LiveRamp] och  [!DNL Tapad]även om du måste etablera kommersiella relationer direkt med diagrampartners för att kunna utnyttja  [!DNL Audience Manager].

### [!DNL Real-time Customer Data Platform]

Det finns inga planer på att ändra aktuell [!DNL Audience Manager Data Management Platform] (DMP). Borttagning av cookies från tredje part kommer dock troligtvis att medföra stora utmaningar för de flesta DMP-användare. För att hjälpa kunderna att utveckla sina rutiner för datahantering uppmuntrar Adobe till att minska beroendet av identifierare som kommer att drabbas av begränsningar under det kommande året. Marknadsföringsteamen måste bygga förstahandsstrategier för data med fokus på varaktiga identifierare som innehåller personligt identifierbar information (PII), som kan lösas med [!DNL Real-time Customer Data Platform] (CDP i realtid).

[!DNL Real-time CDP] minskar beroendet av cookies och enhets-ID från tredje part genom att utöka den uppsättning identifierare som är tillgänglig för målgruppsskapande till att omfatta PII. Foundational för [!DNL Real-time CDP] är en kundprofil i realtid som sammanför personattributdata med beteendedata i realtid och gör det möjligt för marknadsförare att skapa avancerade målgruppssegment med patenterade datastyrningskontroller. Precis som [!DNL Audience Manager] ger [!DNL Real-time CDP] insikter om och användningsfall för personalisering, men genererar också mer detaljerade insikter på personnivå och kan aktivera målgrupper för ett större urval av destinationer som omfattar olika marknadsföringsteknologier och marknadsföringsteknologier, inklusive betalda medier, sociala medier, e-post och kundsystem.

[!DNL Real-time CDP] ger också tillgång till  [Adobe Experience Platform Segment Match (Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en), som gör det möjligt för varumärken att utöka sina egna datauppsättningar genom partnerskap och få bättre insikter och personalisering.

### [!DNL Target]

Det finns för närvarande inga alternativ för [!DNL Target] eftersom [!DNL Target] har en deterministisk funktion för identitetsutssammanfogning mellan enheter som kallas `mbox3rdPartyId`, som fungerar på samma sätt som Adobe Customer ID. Med den här funktionen kan [!DNL Target]-kunder sammanfoga profiler och aktivitetsdeltagande i [!DNL Target]-tester och personalisering görs i inkommande kanaler.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] kunderna inte längre kan använda  [!DNL Device Co-op] för målgruppsanpassning och mätning över olika enheter. Med [!DNL Advertising Cloud] kommer du fortfarande att kunna utnyttja Adobe [!DNL Device Graph]-partnerskap med [!DNL LiveRamp] för att fortsätta utföra dessa funktioner i den utsträckning som möjligheten och skalan för [!DNL LiveRamp’s] tillåter. Du måste tillåta kampanjer som använder [!DNL Device Co-op] att avslutas och sedan antingen växla till enhetsdiagramleverantören [!DNL LiveRamp] eller inte längre utnyttja personbaserad målgruppsanpassning.

## Vilka befintliga funktioner och implementeringar kan hjälpa mig att förbereda mig för en framtid utan cookies?

Implementeringen av din befintliga Visitor ID-tjänst ger Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) kraft. Om ditt befintliga deklarerade ID är ett hashade e-postmeddelande kan det användas för att driva följande funktioner:

- [!DNL Audience Manager] [Personbaserade destinationer](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform segmentmatchning (alfa)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en).

## Får jag behålla mina data från [!DNL Device Co-op]?

För [!DNL Audience Manager]- och [!DNL Advertising Cloud]-användare är data från [!DNL Device Co-op] inte tillgängliga för överföring till tredjepartsdiagram. [!DNL Device Co-op] data migreras endast för  [!DNL Analytics Ultimate] användare som använder CDA med  [!DNL Device Co-op] växling till fältbaserad namngivning. Alla andra lösningar kommer inte att ha sina data migrerade.

## Är det obligatoriskt att använda andra funktioner?

Även om det inte är obligatoriskt att använda andra funktioner i Adobe bör du påbörja implementeringen av andra funktioner så snart som möjligt för att ge tid och lämplig samordning innan [!DNL Device Co-op]-borttagningen påbörjas.

## När måste jag anta alternativa lösningar om jag väljer att göra det?

Andra funktioner är inte obligatoriska. Vi rekommenderar endast om du vill fortsätta att behandla användningsfall som har åtgärdats av [!DNL Device Co-op]. Om du väljer att använda andra funktioner måste du göra det senast 2022 (exakt tajmning ska tillkännages) innan [!DNL Device Co-op]-programmet avslutas.

## Hur lång tid tar antagandet?

Detta beror på funktionen. Om till exempel en Analytics Ultimate-kund som använder enhetsövergripande analys med [!DNL Device Co-op] behöver migrera till privat enhetsgrafik i realtid eller fältbaserad anpassning, tar det lite tid att implementera.