---
description: När en person har enheter som inte används för att interagera med ert varumärke kallas dessa enheter för okända enheter.
seo-description: När en person har enheter som inte används för att interagera med ert varumärke kallas dessa enheter för okända enheter.
seo-title: Okända enheter
title: Okända enheter
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Okända enheter{#unknown-devices}

När en person har enheter som inte används för att interagera med ert varumärke kallas dessa enheter för okända enheter.

## Okända enhetskategorier {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Det finns flera sätt eller kategorier genom vilka en enhet kan anses vara&quot;okänd&quot;. Bland dessa finns:

* **Första partsbesök hos andra medlemmar i Device Co-op:** Besök hos andra [!DNL Device Co-op] medlemswebbplatser eller annonser hos en enhet gör inte i sig en enhet känd för ert varumärke.

* **Ej spårad annonslager:** Ett annonslager som är tillgängligt, men som ännu inte har levererats eller kapslats, ger inte en enhet som är känd för ert varumärke.
* **Avanmäl dig till kund:** För att tillgodose konsumenternas önskemål anses enheter som har valts ut inte vara kända enheter.

Till skillnad från kända enheter är okända enheter inte länkade till andra enheter eller kopplade till enskilda personer.

## Regler för att ange känd/okänd status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

Den [!DNL Device Graph] försöker vara så omfattande som möjligt när enheter klassificeras som kända jämfört med okända. Reglerna som hjälper till att fastställa känd/okänd status fungerar i prioritetsordning (1 är högst) enligt nedan:

* **Regel 1:** Är enheten avanmäld? Om ja, är enheten okänd.
* **Regel 2:** Är enheten känd av *någon* metod? Om ja, är enheten känd.

* **Regel 3: ** Om föregående inte gäller är enheten okänd.

>[!MORELIKETHIS]
>
>* [Kända enheter](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

