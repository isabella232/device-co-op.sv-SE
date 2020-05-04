---
description: Ditt företag måste uppfylla dessa minimistandarder innan du kan börja använda Experience Cloud Device Co-op.
seo-description: Ditt företag måste uppfylla dessa minimistandarder innan du kan börja använda Experience Cloud Device Co-op.
seo-title: Krav för medlemskap
title: Krav för medlemskap
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c

---


# Krav för medlemskap{#membership-requirements}

Ditt företag måste uppfylla dessa minimistandarder innan du kan börja använda Experience Cloud Device Co-op.

## Krav {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Tala med din [!DNL Adobe representative to get started]. Om du inte har någon Adobe-representant kan du gå till [Device Co-op-medlemsportalen](http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html) och fylla i onlineformuläret.

Adobe förbehåller sig rätten att neka alla potentiella kundmedlemskap i Experience Cloud Device Co-op om Adobe fastställer att en presumtiv kunds deltagande i Device Co-op kan (1) bryta mot tillämplig lag. eller (2) medföra en väsentlig risk för säkerheten eller driften av Adobe eller någon av dess kunder.

## Krav för Experience Cloud {#section-76218a50385d43e6b9323e49f598394a}

Du måste vara aktiverad för [!DNL Adobe Experience Cloud] och använda följande lösningar och tjänster för att delta i samarbetet.

**Lösningar**

Sökande måste använda minst en av följande [!DNL Adobe]lösningar:

* [Analyser](http://www.adobe.com/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Mål](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**Kärntjänster**

Sökande måste implementera [Experience Cloud ID Service](https://docs.adobe.com/content/help/en/id-service/using/home.html).

## Krav för Adobes kodbibliotek {#section-931a3fca1ce54afd90b88ba032e75f05}

I följande tabell visas de lägsta versionerna av kodbiblioteken eller SDK:er som används av olika [!DNL Experience Cloud] lösningar och tjänster. Om du använder någon av dessa koder och vill delta i Device Co-op måste du se till att dessa minimikrav uppfylls.

>[!TIP]
>
>Vi rekommenderar att du använder de senaste kodversionerna i stället för de nödvändiga minimumen.

**AppMeasurement (Flash)**

Kräver version 4.1. Se [AppMeasurement for Flash, Flex och AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Kräver version 1.5.4. Se [AppMeasurement for Flash, Flex och AIR](https://docs.adobe.com/content/help/en/analytics/implementation/js/migrate-from-hcode.html).

**SDK för mobiler**

Lägsta krav för mobil SDK:

* Android version 4.8.3.
* iOS version 4.8.5.

SDK-koden måste vara aktiverad för [!DNL Experience Cloud] ID-tjänsten. Aktivera och hämta den senaste SDK-koden för varje app i ditt [Adobe Mobile Services](https://mobilemarketing.adobe.com/) -konto. Se [Konfigurera tjänstalternativ](https://docs.adobe.com/content/help/en/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html)för SDK Visitor ID.

Använd rätt `visitorSyncIdentifier` metod för varje SDK. Se:

* [Android Experience Cloud ID-tjänstmetoder](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [Tjänstmetoder för iOS Experience Cloud ID](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Kräver version 1.5.4.

[!DNL Analytics] kunder kan hämta VisitorAPI.js-biblioteket från [!DNL Code Manager]. Den finns i JavaScript-filerna (Nytt) eller JavaScript-filerna (äldre). Kontakta [kundtjänst](https://helpx.adobe.com/marketing-cloud/contact-support.html) om du inte har tillgång till [!DNL Code Manager].

**Målbibliotek**

Kräver något av följande [!DNL Target] JavaScript-bibliotek:

* at.js (alla versioner)
* mbox.js version 58 eller senare

