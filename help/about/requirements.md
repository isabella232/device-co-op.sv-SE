---
description: Ditt företag måste uppfylla dessa minimistandarder innan du kan börja använda Experience Cloud Device Co-op.
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: Krav för medlemskap
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 5%

---

# Krav för medlemskap{#membership-requirements}

Ditt företag måste uppfylla dessa minimistandarder innan du kan börja använda Experience Cloud Device Co-op.

## Krav {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Tala med [!DNL Adobe representative to get started]. Adobe förbehåller sig rätten att neka alla potentiella kundmedlemskap till Experience Cloud Device Co-op om Adobe fastställer att en presumtiv kunds deltagande i Device Co-op kan (1) bryta mot tillämplig lag. eller (2) medföra en väsentlig risk för säkerheten eller verksamheten i Adobe eller för någon av dess kunder.

## Krav för Experience Cloud {#section-76218a50385d43e6b9323e49f598394a}

Du måste aktivera för [!DNL Adobe Experience Cloud] och använd följande lösningar och tjänster för att delta i samarbetet.

**Lösningar**

Sökanden måste använda minst ett av följande [!DNL Adobe]lösningar:

* [Analyser](http://www.adobe.com/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**Kärntjänster**

De sökande måste genomföra [Experience Cloud ID-tjänst](https://docs.adobe.com/content/help/sv-SE/id-service/using/home.html).

## Adobe krav för kodbibliotek {#section-931a3fca1ce54afd90b88ba032e75f05}

I följande tabell visas de lägsta versionerna av kodbiblioteken eller SDK:er som används av olika [!DNL Experience Cloud] lösningar och tjänster. Om du använder någon av dessa koder och vill delta i Device Co-op måste du se till att dessa minimikrav uppfylls.

>[!TIP]
>
>Vi rekommenderar att du använder de senaste kodversionerna i stället för de nödvändiga minimumen.

**AppMeasurement (Flash)**

Kräver version 4.1. Se [AppMeasurement för Flash, Flex och AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Kräver version 1.5.4. Se [AppMeasurement för Flash, Flex och AIR](https://docs.adobe.com/content/help/en/analytics/implementation/js/migrate-from-hcode.html).

**SDK för mobiler**

Lägsta krav för mobil SDK:

* Android version 4.8.3.
* iOS version 4.8.5.

SDK-koden måste vara aktiverad för [!DNL Experience Cloud] ID-tjänst. Aktivera och hämta den senaste SDK-koden för varje app i [Adobe Mobile Services](https://mobilemarketing.adobe.com/) konto. Se [Konfigurera tjänstalternativ för SDK Visitor ID](https://docs.adobe.com/content/help/en/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Använd lämplig `visitorSyncIdentifier` som passar era behov. Se:

* [Tjänstmetoder för Android Experience Cloud ID](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [Tjänstmetoder för iOS Experience Cloud ID](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Kräver version 1.5.4.

[!DNL Analytics] kunder kan hämta VisitorAPI.js-biblioteket från [!DNL Code Manager]. Den finns i JavaScript-filerna (Nytt) eller JavaScript-filerna (äldre). Kontakt [Kundtjänst](https://helpx.adobe.com/marketing-cloud/contact-support.html) om du inte har tillgång till [!DNL Code Manager].

**Målbibliotek**

Kräver något av följande [!DNL Target] JavaScript-bibliotek:

* at.js (alla versioner)
* mbox.js version 58 eller senare
