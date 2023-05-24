---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op;slutet av livscykeln
title: Device Co-op - frågor och svar om upphörande av livscykel
description: Läs mer om planerna för slutet av livscykeln för Device Co-op.
source-git-commit: 8c372964824a33f31a5a3b11a38ebe1a49df35ea
workflow-type: tm+mt
source-wordcount: '1106'
ht-degree: 88%

---

# Device Co-op - frågor och svar om upphörande av livscykel

I det här dokumentet finns svar på vanliga frågor om Adobe Experience Cloud Device Co-op End-of-life-planen (EOL). När denna plan träder i kraft lämnar Adobe ett förhandsmeddelande i [Versionsinformationen för Experience Cloud](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=sv) och den [Prioriterade produktuppdateringen](https://www.adobe.com/subscription/priority-product-update.html).

Device Co-op var ett program där deltagarna kunde samarbeta för att bättre identifiera konsumenter över olika digitala kontaktytor samtidigt som man säkerställde högsta sekretess och transparens.

## Vanliga frågor och svar

Nedan följer en lista över vanliga frågor och svar som berör planen om slutet av livscykeln för [!DNL Device Co-op].

## Varför avvecklas [!DNL Device Co-op]?

De kommande ändringarna i AdTech-miljön förväntas resultera i att [!DNL Device Co-op] blir en föråldrad lösning under de kommande åren. [!DNL Device Co-op] består huvudsakligen av cookies från tredje part och meddelandet [!DNL Google's] om att cookies från tredje part blockeras på [!DNL Google Chrome] under 2022 minskar effektiviteten hos [!DNL Device Co-op]. [!DNL Chrome] har cirka 65 % av webbläsarens marknadsandel och andra större webbläsare har redan infört blockering av cookies från tredje part. När [!DNL Chrome] blockerar cookies från tredje part blockeras merparten av cookies från tredje part, något som resulterar i att [!DNL Device Co-op] föråldras.

## Varför avslutar Adobe [!DNL Device Co-op]-registreringar nu?

Registreringar avslutas för att förhindra risken med att inte uppfylla kundernas förväntningar på grund av kommande branschförändringar kring cookies från tredje part. [!DNL Device Co-op] tar några månader att förbereda och ytterligare några månader att extrahera värde från tjänsten. Ytterligare registreringar kan leda till att varumärken inte får det fulla värdet av [!DNL Device Co-op].

## Google meddelade under juli 2022 att avvecklingen av cookies från tredje part i Chrome försenades till 2024. Påverkar detta planerna för slutet av livscykeln för [!DNL Device Co-op]?

Nej, Adobes plan för slutet av livscykeln för [!DNL Device Co-op] fortsätter att vara densamma och förlängs inte.

## Kan nya kunder registrera sig?

Från och med 11 juni 2021 accepterar Adobe inte längre nya registreringar till [!DNL Device Co-op].

## Förnyas befintliga kontrakt?

Från och med 11 juni 2021 förnyar Adobe inte längre [!DNL Device Co-op]-kontrakt. Om du vill fortsätta använda [!DNL Device Co-op]-tjänsterna kan du fortsätta göra det i enlighet med de gällande licensvillkoren tills programmet upphör.

## Vad är det exakta slutdatumet för programmet [!DNL Device Co-op]?

Programmet [!DNL Device Co-op] avslutas 2022. Den specifika tidpunkten och datumet beror på när [!DNL Google] börjar blockera cookies från tredje part. Avvecklingsarbetet förväntas börja i september 2022.

## Vilka program påverkas av slutet av livscykeln för Device Co-op?

Följande program påverkas av förfarandena för slutet av livscykel för [!DNL Device Co-op]:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=sv)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=sv)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=sv)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=sv)

## Vilka alternativ har jag som alternativ till [!DNL Device Co-op]?

### [!DNL Analytics]

Du kan använda funktionen [!DNL Analytics] [Enhetsövergripande analys (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html?lang=sv) eftersom den stöder både [Privat diagram](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=sv) och [Fältbaserad sammanfogning](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=sv) i Identitetstjänsten för Adobe Experience Platform.

### [!DNL Audience Manager]

[!DNL Audience Manager] behåller integreringar med tredjeparts partner för enhetsgrafer, inklusive [!DNL LiveRamp] och [!DNL Tapad], även om du måste etablera kommersiella relationer direkt med diagrampartners för att kunna utnyttja [!DNL Audience Manager]. Alla kunder förväntas uppdatera eventuella samverkansregler för profilsammanslagning för att kunna utnyttja andra alternativ än [!DNL Device Co-op.]

### [!DNL Real-time Customer Data Platform]

Det finns inga planer på att ändra den aktuella [!DNL Audience Manager Data Management Platform] (DMP). Avvecklingen av cookies från tredje part medför dock troligtvis stora utmaningar för de flesta DMP-användare. För att hjälpa kunderna att utveckla sina rutiner för datahantering uppmuntrar Adobe till att minska beroendet av identifierare som kommer att drabbas av begränsningar under det kommande året. Marknadsföringsteamen måste bygga strategier för förstahandsdata med fokus på varaktiga identifierare som innehåller personligt identifierbar information (PII), som kan lösas med [!DNL Real-time Customer Data Platform] (Real-Time CDP).

[!DNL Real-time CDP] minskar beroendet av cookies och enhets-ID:n från tredje part genom att utöka den uppsättning identifierare som är tillgänglig för målgruppsskapande till att omfatta PII. Grundläggande för [!DNL Real-time CDP] är kundprofil i realtid, som sammanför personattributdata med beteendedata i realtid och låter marknadsförare skapa rika målgruppssegment med patenterade kontroller för datastyrning. Liksom [!DNL Audience Manager] driver [!DNL Real-time CDP] användningsfall av insikter och personalisering, men genererar också mer detaljerade insikter på personnivå och kan aktivera publik till ett bredare utbud av destinationer som spänner över reklamteknik och marknadsföringsteknik, inklusive betalmedia, sociala medier, e-post och kundsystem.

[!DNL Real-time CDP] ger även tillgång till [Segmentmatchning för Adobe Experience Platform (betaversion)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=sv), som gör det möjligt för varumärken att utöka sina egna datauppsättningar från första part genom partnerskap och få bättre insikter och personalisering.

### [!DNL Target]

Det finns för närvarande inga tillgängliga alternativ för [!DNL Target] eftersom [!DNL Target] tillhandahåller en deterministisk förmåga att sammanfoga identiteter över flera enheter, känd som `mbox3rdPartyId`, som fungerar på samma sätt som Adobes kund-ID. Den här funktionen låter [!DNL Target]-kunder att slå samman profiler och aktivitetsdeltagande mellan [!DNL Target]-tester och personalisering utförs i inkommande kanaler.

### Adobe Advertising Cloud

[!DNL Advertising Cloud]-kunder kan inte längre använda [!DNL Device Co-op] för målgruppsanpassning och mätning över flera enheter. Med [!DNL Advertising Cloud] kan du fortfarande utnyttja Adobes [!DNL Device Graph]-partnerskap med [!DNL LiveRamp], för att fortsätta att utföra dessa funktioner i den utsträckning som [!DNL LiveRamp's]:s förmåga- och skala tillåter. Du måste tillåta att kampanjer som använder [!DNL Device Co-op] avslutas och sedan växla till leverantören av enhetsdiagram för [!DNL LiveRamp], eller inte längre utnyttja personbaserad målgruppsanpassning.

## Vilka befintliga funktioner och implementeringar kan hjälpa mig att förbereda mig för en framtid utan cookies?

Implementeringen av din befintliga Visitor ID-tjänst ger Analytics kraft [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html?lang=sv). Om ditt befintliga deklarerade ID är ett hashade e-postmeddelande kan det användas för att driva följande funktioner:

- [!DNL Audience Manager] [Personbaserade mål](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html?lang=sv).
- [Segmentmatchning för Experience Platform (betaversion)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=sv).

## Får jag behålla mina data från [!DNL Device Co-op]?

För [!DNL Audience Manager] och [!DNL Advertising Cloud] användare, data från [!DNL Device Co-op] kommer inte att kunna överföras till diagram från tredje part. [!DNL Device Co-op]-data migreras endast för användare av [!DNL Analytics Ultimate] som använder CDA med [!DNL Device Co-op], som går över till fältbaserad sammanfogning. Alla andra lösningar migrerar inte sina data.

## Är det obligatoriskt att använda andra funktioner?

Även om det inte är obligatoriskt att använda andra Adobe-funktioner bör du påbörja implementeringen av andra funktioner så snart som möjligt för att ge tid och lämplig samordning i förväg [!DNL Device Co-op] borttagning.

## När måste jag anta alternativa lösningar om jag väljer att göra det?

Andra funktioner är inte obligatoriska. Det rekommenderas endast om du vill fortsätta att ta itu med användningsfall som behandlades av [!DNL Device Co-op]. Om du väljer att använda andra funktioner måste du göra det senast 2022 (det exakta datumet har ännu inte fastställts) före avvecklingen av programmet [!DNL Device Co-op].

## Hur lång tid tar antagandet?

Detta beror på funktionen. Antagandet tar tid, till exempel om en Analytics Ultimate-kund använder Enhetsövergripande analys med [!DNL Device Co-op] och måste migrera till Privat enhetsgrafik i realtid eller Fältbaserad sammanfogning.
