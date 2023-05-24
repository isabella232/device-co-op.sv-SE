---
description: Adobe Experience Cloud Device Co-op är ett program som gör att deltagare kan samarbeta för att bättre identifiera konsumenter i olika kontaktytor samtidigt som man säkerställer högsta sekretess och transparens. Experience Cloud Device Co-op ger deltagande varumärken möjlighet att identifiera sina konsumenter så att de kan leverera mer personaliserade upplevelser över enheter och appar i stor skala. Device Co-op är en bastjänst i Adobe Experience Cloud. Det är tillgängligt för Adobe-kunder som använder Analytics, Audience Manager, Media Optimizer eller Target.
seo-description: The Adobe Experience Cloud Device Co-op is a program that lets participants work together to better identify consumers across digital touch points while ensuring the highest level of privacy and transparency. The Experience Cloud Device Co-op empowers participating brands to recognize their consumers so they can deliver more personalized experiences across devices and apps at massive scale. The Device Co-op is a core service of the Adobe Experience Cloud. It is available to Adobe customers who use Analytics, Audience Manager, Media Optimizer, or Target.
seo-title: Overview
title: Översikt
uuid: 9e2502db-0dc6-4b0f-965f-71894fb1f9d4
exl-id: 8195162c-fab4-49d8-8f6f-1e9ed96ffaa7
source-git-commit: e7a53a4892a8769fc178f5f3f2b82201589177b2
workflow-type: tm+mt
source-wordcount: '794'
ht-degree: 0%

---

# Översikt{#overview}

Adobe Experience Cloud Device Co-op är ett program som gör att deltagare kan samarbeta för att bättre identifiera konsumenter i olika kontaktytor samtidigt som man säkerställer högsta sekretess och transparens. Experience Cloud Device Co-op ger deltagande varumärken möjlighet att identifiera sina konsumenter så att de kan leverera mer personaliserade upplevelser över enheter och appar i stor skala. Device Co-op är en bastjänst i Adobe Experience Cloud. Det är tillgängligt för Adobe-kunder som använder Analytics, Audience Manager, Media Optimizer eller Target.

## Fördelar {#section-ba8d23e1e5174bea8f84aab4642d4809}

Med Device Co-op kan deltagarna ge sina kunder en bättre och enhetligare innehållsupplevelse när de migrerar mellan olika enheter. Den gör detta genom att etablera länkar mellan en grupp enheter som används av okända konsumenter. Den här tekniken hjälper marknadsförare att förstå och reagera på konsumentbeteenden på olika enheter. Resultatet ger mer korrekta mått för webbplatsengagemang, mer personaliserat innehåll och mer målinriktade annonsupplevelser i sökmotorkampanjer, webbkampanjer och sociala kampanjer. Deltagande i [!DNL Adobe Experience Cloud] Device Co-op hjälper våra medlemmar att förbättra:

* **Kundförståelse:** Traditionell rapportering kan avslöja insikter för en viss enhet. Men enheter och kanaler köper inte saker - det gör folk. Med bättre rapportering kan Device Co-op hjälpa analytiker och marknadsförare att svara på de frågor som deras verksamhet verkligen är fokuserad på.
* **Innehållspersonalisering:** Konsumenter som inte loggar in på ett varumärkes webbplats eller app får oftast en upplevelse som är länkad till den enhet de använder just nu. Device Co-op hjälper marknadsförare att leverera enhetliga och värdefulla upplevelser baserade på information ett varumärke har om en person, och inte bara den enhet de använder.
* **Effektiv annonsering:** Device Co-op hjälper till att spara marknadsföringsbudgeten genom att fokusera annonseringen på människor, inte enheter. Eftersom frekvensomfång vanligtvis gäller för en enskild enhet kan en gräns på 5 annonser per konsument enkelt omvandlas till 5 annonser per enhet. Med Device Co-op kan marknadsförarna öka avkastningen genom att inrikta sig på personen, inte enheten.
* **Återmarknadsföring på olika enheter:** Nå ut till kunderna med hjälp av återmarknadsföring som är olåst över de mobiler, surfplattor, webbläsare och andra enheter de använder dagligen. Annonsering är betydligt effektivare om ni kan hålla er i framkanten och återmarknadsföring över flera enheter gör att ert varumärke kan göra precis det.

<!--
we may not want to share info in this with customers who have not signed. Also, removed directory from S3.
<p>Download our white-paper, <a href="https://marketing-stage.adobe.com/resources/help/en_US/mcdc/downloads/what_to_expect.pdf" format="https" scope="external"> What to Expect from the Device Co-op</a> for more information. </p>
-->

## Adobe Role in the Device Co-op {#section-f23c1c442ceb4c44821f10ec9aa7b828}

I [!DNL Device Co-op], [!DNL Adobe]:

* **Är en dataförvaltare:** Medlemmar i Device Co-op delar inte data direkt med varandra. Istället [!DNL Adobe], fungerar som en mäklare för att göra enhetslänksdata tillgängliga för medarbetaren via [!DNL Device Graph]. Medlemmar i Device Co-op får arbeta med dessa data via funktioner i deras aktiverade [!DNL Experience Cloud] lösningar.

* **Europaparlamentet anser att data är rättvisa:** Jämnt datadelning är ett viktigt koncept i Device Co-op. Alla [!DNL Device Co-op] medlemmar får ett värde som är relativt till vad de bidrar med. Om du aldrig har interagerat med en anonym person via ett webbplatsbesök eller ett annonsintryck får du ingen information om deras enheter i [!DNL Device Graph]. Device Co-op hjälper varumärken att identifiera välkända konsumenter med hjälp av okända enheter.

* **Stöder sekretessstandarder:** [!DNL Device Graph] data inte innehåller personligt identifierbar information. Att exkludera PII från enhetsdiagrammet hjälper till [!DNL Adobe] upprätthålla sekretessstandarder och upprätthålla förtroendet hos såväl medlemmarna som konsumenterna.

## Så fungerar det {#section-7f7a0138e54349278fc463764f03cd4b}

Medarbetarna ger Adobe åtkomst till kryptografiskt hash-kodade inloggnings-ID:n och HTTP-rubrikdata, som helt döljer en kunds identitet. Adobe bearbetar dessa data för att skapa grupper av enheter (&quot;enhetsgrupper&quot;) som används av en okänd person eller ett okänt hushåll. Adobe kommer sedan att visa upp dessa grupper av enheter genom sina digitala marknadsföringslösningar, så medlemmarna i Co-op kan mäta, segmentera, rikta och annonsera direkt till individer på alla sina enheter. Allt detta är möjligt utan att användarens identitet avslöjas eftersom [!DNL Device Co-op] *inte* dela personuppgifter som namn, e-postadresser, telefonnummer eller besöksdata på webbplatsen, osv. bland sina medlemmar.

Dessa regler hjälper till att ta itu med viktiga integritetsproblem som ofta uppstår i samband med olika typer av enheter. Med [!DNL Device Co-op], kommer konsumenterna att ha integritetskontroller som överträffar branschens standarder. The [!DNL Device Co-op] ger oöverträffad transparens genom att ge konsumenterna insikter om deltagande varumärken samt alla enheter som är kopplade till den enhet som används för närvarande. Se [Enhetsdiagram: Interna processer och utdata](../processes/links.md#concept-e9526af3476b478aab7c57b9ed0bab7c) för mer information.

## Komma igång {#section-53a47ffdc5bf47c88cedcb92dd65444b}

Ta dig tid att titta på [krav på medlemskap](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43) om du vill delta eller lära dig mer om [!DNL Device Co-op]. Se även [Arbeta med Device Co-op-data i andra Experience Cloud-lösningar](../other-solutions/other-solutions.md#concept-46278a50cfca4e1ab83a3b35077a585f) för en sammanfattning av hur andra [!DNL Adobe] -produkter har använt dessa data.
