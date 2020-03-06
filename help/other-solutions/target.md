---
description: Lär dig hur du använder Device Co-op-data i Adobe Target-aktiviteter.
seo-description: Lär dig hur du använder Device Co-op-data i Adobe Target-aktiviteter.
seo-title: Mål - A/B-tester, multivariata tester och målinriktad upplevelse
title: Mål - A/B-tester, multivariata tester och målinriktad upplevelse
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Mål - A/B-tester, multivariata tester och målinriktad upplevelse{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Lär dig hur du använder Device Co-op-data i Adobe Target-aktiviteter.

Du kan använda Device Co-op-data i A/B-tester, multivariata tester (MVT) och aktiviteter för målinriktning av upplevelser. Alternativet Device Co-op är tillgängligt när aktiviteter skapas på [!DNL Goals & Settings] sidan i det guidade arbetsflödet i [!DNL Target] tre steg.

Du kan inte använda Device Co-op-data i automatiserade personaliseringsaktiviteter, rekommendationsaktiviteter eller aktiviteter med [!DNL Adobe Analytics] som rapportkälla ( [!DNL Target] och [!DNL Analytics] integrering, kallas A4T).

>[!NOTE]
>
>Kontrollera att du har rätt version av `mbox.js`. Du kan använda vilken version som helst av `at.js`. Mer information finns i [Krav](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)för medlemskap.

## Leverera relevant innehåll oavsett enhet {#section-bba8d41e96914c82a6d267a54f776354}

Marknadsförarna vill leverera den mest relevanta upplevelsen till varje besökare, oavsett vilken enhet besökaren använder för att interagera med sitt företag eller varumärke.

Användarna interagerar med samma företag eller varumärke från många olika enheter: bärbara datorer, hemdatorer, iPad, iPhone, olika webbläsare osv. Om ni inte känner igen att varje specifik enhet eller webbläsare används av samma person som tidigare interagerat med ert varumärke på en annan enhet eller webbläsare, kan ni inte leverera en enhetlig och målinriktad upplevelse till den personen.

Med Device Co-op kan en användares olika enheter identifieras som om de används av samma användare. När en användare ser en sida med [!DNL Target] aktiviteter - antingen aktiviteter eller riktat innehåll - [!DNL Target] kan användaren se samma upplevelse som på en annan enhet.

## Analysera målaktiviteter av människor i stället för av besökare {#section-c25cf4f8483942d7836d60756235e62c}

Marknadsförarna vill analysera [!DNL Target] aktiviteter med&quot;människor&quot; istället för&quot;besökare&quot;.

Varje person interagerar troligtvis med samma företag eller varumärke på olika enheter och webbläsare, men utan Device Co-op betraktas varje enskild enhet eller webbläsare som en separat&quot;besökare&quot; i [!DNL Target] rapporter.

Att visa rapporter från enskilda enheter och webbläsare ökar antalet besökare till ett högre antal än antalet olika personer som interagerar med företaget eller varumärket. Dessa personer konverterar vanligtvis bara en gång till olika enheter och webbläsare, så konverteringsgraden blir lägre än i verkligheten eftersom fler&quot;besökare&quot; räknas för en enda konvertering.

Med Device Co-op levereras och rapporteras innehåll på personnivå, så rapporterna visar exakt hur många olika personer som såg aktiviteten och hur många av dem som konverterades.

Utan Device Co-op-data kan du fastställa att en viss aktivitet är vinnaren; Men eftersom rapporteringen är mer korrekt med Device Co-op kan en annan aktivitet faktiskt ha en högre konverteringsgrad och därför vara vinnare.

Mer information om det här konceptet finns i [Analytics: People Metric](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Använd Device Co-op-data per aktivitet {#section-fb46fae482654023abb1a1e26564db9a}

Marknadsförarna kan välja att använda Device Co-op-data per aktivitet. Vissa [!DNL Target] aktiviteter kanske inte passar för Device Co-op-data, som:

* Specifikt innehåll som passar användare på en iPad.

   Användare som först visar en upplevelse på en iPad kommer även fortsättningsvis att se den upplevelsen på sina hemdatorer.

* Ett ränteerbjudande som endast är tillgängligt för ett strikt segment av besökare.
* Produkter får endast annonseras i en viss delstat (t.ex. en försäkring med licensbegränsningar).

När marknadsförare skapar målgrupper i [!DNL Target]får de ett varningsmeddelande om målgruppen inte passar för dataaktiverade aktiviteter i Device Co-op. Lämpliga målgrupper är alla besökare, nya besökare och återkommande besökare.
