---
description: Om kända enheter i Device Graph.
seo-description: About known devices in the Device Graph.
seo-title: Known devices
title: Kända enheter
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
exl-id: 4eaf104f-022b-447b-8ce2-f0d0d1177cdf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 1%

---

# Kända enheter{#known-devices}

Om kända enheter i Device Graph.

I Device Graph har vi begreppet *`known device`*. En känd enhet är en enhet som en kund använder för att interagera med ert varumärke.

>[!NOTE]
>
>I [!DNL Adobe Experience Cloud Device Co-op], termer som *`device`*, *`person`*, *`identity`* osv. har en specifik betydelse. &quot;device&quot; kan till exempel avse fysisk maskinvara som en telefon eller surfplatta och de program som körs på den maskinvaran. Se [ordlista](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) för definitioner.

## Stödja mål med den kända enheten {#section-80deae33660e4280ac65c659ceff5601}

Det kända enhetskonceptet har stöd för några viktiga mål som är viktiga för att skapa och underhålla ett effektivt [!DNL Device Co-op] program. En känd enhet är en som [!DNL Device Co-op] Medlemmen känner till från viss interaktion med en konsument (t.ex. ett webbplatsbesök eller via en mobilapp). Baserat på dessa åtgärder har [!DNL Device Graph] länkar kända enheter i en [!DNL Device Co-op] medlem till enheter som andra bidragit med [!DNL Device Co-op] medlemmar. Dessa länkar kan vara [deterministisk eller sannolik](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). Fördelar [!DNL Device Co-op] medlemmar eftersom de får:

* Mer information om deras kända enheter.
* Ny information om andra länkade enheter.

![](assets/known-device.png)

The [!DNL Device Graph] kommer inte att tillhandahålla information om enhetskluster som en Device Co-op-medlem inte har sett.

## Mål för Device Co-op {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Tre huvudmål animerar [!DNL Device Co-op]. Bland dessa finns:

* **Skala:** Dela maximalt antal möjliga länkar mellan olika användningsområden.
* **Ökthet:** Se till att alla medlemmar i [!DNL Device Co-op] förmåner på ett sätt som står i proportion till deras avgifter.

* **Förtroende:** Bevara och bygga upp konsumenternas förtroende genom att säkerställa att konsumentupplevelsen på olika enheter inbegriper varumärken som de redan känner till och litar på.

## Skala och känd enhet {#section-67f734109762457ca62ec306284ea082}

Följande metoder är de vanligaste sätten som en enhet kvalificerar som en känd enhet. Med dessa metoder [!DNL Device Co-op] -medlemmar har nästan alltid minst en känd enhet. Detta stöder målet att ge maximal skala till alla medlemmar i [!DNL Device Co-op].

**Organic**

* Från kundens besök på er webbplats eller via er app. Detta är kvalificering från förstahandsdata.
* Genom att introducera nya kunder från ett CRM-system.

**Marketplace**

* Köpa segmentdata från Audience Marketplace.
* Från att köpa data från en tredjepartsleverantör.

**Advertising**

Genom att vinna lager på en auktion och leverera en annons till en enhet. Enheten blir en känd enhet om annonsen innehåller en [!DNL Audience Manager] pixel.

## Kända enheter och användningsfall för rättvisa {#section-0543188729d845d6b95db70b8b25e9f8}

Medlemmar i [!DNL Device Co-op] få länkar som motsvarar deras bidrag till [!DNL Device Graph]. Företag som arbetar med många enheter för [!DNL Device Graph] får fler länkar än medlemmar som bidrar med bara några få. Vi tror att det här bidrar till att [!DNL Device Co-op] rättvisa för alla dess medlemmar. Låt oss titta på hur detta fungerar med de stora och små användningsfall som beskrivs nedan.

**Varumärke A: stor användning**

I det här exemplet har Brand A 100 webbplatsbesökare varje månad och påbörjar en ny varumärkeskampanj på olika enheter. För enkelhetens skull, anta [!DNL Device Graph] känner till att alla besökare på varumärke A är länkade till ytterligare en enhet. Det innebär att varumärke A kan nå ytterligare 100 enheter. Dessutom finns [!DNL Device Graph] innehåller cirka 200 enheter som är länkade tillsammans.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Kända enheter/månad </th> 
   <th colname="col2" class="entry"> Länkade enheter som tagits emot från Device Co-op </th> 
   <th colname="col3" class="entry"> Totalt antal enheter för kampanj </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Varumärke B: Gemener**

I det här exemplet har Brand B 100 webbplatsbesökare varje månad och påbörjar en ny varumärkeskampanj på olika enheter. För enkelhetens skull, anta [!DNL Device Graph] känner till att alla besökare på varumärke B är kopplade till ytterligare 50 enheter. Det innebär att varumärke B kan nå 150 enheter. Dessutom finns [!DNL Device Graph] innehåller cirka 1 000 enheter som är kopplade till varandra.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Kända enheter/månad </th> 
   <th colname="col2" class="entry"> Länkade enheter som tagits emot från Device Co-op </th> 
   <th colname="col3" class="entry"> Totalt antal enheter för kampanj </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [Okända enheter](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

