---
description: Om länkdelning i enhetsdiagrammet.
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: Länkdelning i enhetsdiagram
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
exl-id: 91ecc493-89d8-40d6-a98b-c2349e25c854
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---

# Länkdelning i enhetsdiagram{#link-sharing-in-the-device-graph}

Om länkdelning i enhetsdiagrammet.

The [!DNL Device Graph] delar deterministiska och sannolika länkar med olika medlemmar i Adobe Experience Cloud Device Co-op. Länkdelning är det som gör [!DNL Device Co-op] så kraftfull. Det utökar det som varje medlem känner till om enheterna som är kopplade till en anonym person, men bara om du har sett minst en av enheterna för den anonyma personen tidigare.

## Sammanfattningsgranskning av enhetsdiagram {#section-7858e9f61b5644c981ffb53626fcc19d}

Innan vi börjar ska vi titta närmare på hur [!DNL Device Graph] fungerar. Medlemmar i [!DNL Device Co-op] skicka data till [!DNL Device Graph]. The [!DNL Device Graph] använder dessa data för att konstruera en persons identitet från [deterministiska och sannolika länkar](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) mellan enheter. Som [!DNL Device Co-op] dessa länkar ger dig insikt om relationen mellan dina autentiserade användare, andra användare och deras enheter. Låt oss titta på hur detta fungerar i avsnittet nedan.

## Exempel på länkdelning {#section-cb410d827cf14f76bc9b0bd4d31ed767}

I följande exempel visas möjligheterna med länkdelning i Device Co-op. I det här exemplet har vi två fiktiva företag, News Company och Finance Company. Båda företagen är medlemmar i [!DNL Device Co-op]. Person A är en konsument som antingen loggar in eller bläddrar på respektive företags webbplatser från flera olika enheter.

![](assets/share1.png)

Eftersom person A har autentiserat sig på nyhetswebbplatsen med sin mobiltelefon och surfplatta identifierar News Company dem med ett konsument-ID. Det ID:t skickas till [!DNL Device Graph] som en kryptografisk hash. Finansföretaget har sett de här enheterna förut, men person A har inte loggat in på webbplatsen. Följaktligen vet inte finansföretaget om eller hur dessa enheter är relaterade till varandra eller hur de är kopplade till person A.

![](assets/share2.png)

Med tanke på den kryptografiska hashen för konsument-ID:t [!DNL Device Graph] känner igen att dessa enheter är relaterade till varandra och en viss person. Till företag som inte deltar i [!DNL Device Co-op] Dessa besök på platsen förefaller komma från separata, slumpmässiga enheter. I vilket fall som helst när [!DNL Device Graph] har det hash-kodade ID:t:

* Känns till att mobiltelefoner och bärbara datorer är kopplade till varandra.
* Europaparlamentet är medvetet om att finansföretaget vill veta om mobiltelefonen och den bärbara datorn är kopplade till varandra.

Med hänsyn till dessa villkor är [!DNL Device Graph] delar nu länken mellan dessa enheter för News Company och Finance Company. Under den här processen [!DNL Device Graph] duplicerar och delar länken från en medverkande medlem till en annan.

![](assets/share3.png)

Nu är [!DNL Device Graph] har utfört sin roll. Både News Company och Finance Company har en tydlig bild av en identitet. De kan nå Person A korrekt på alla sina enheter.

## Sekretess och länkdelning {#section-7b566018b3304420a4b3e4c079826110}

Bevara konsumenternas integritet och dataintegritet för [!DNL Device Co-op] Medlemmarna är avgörande under hela länkdelningsprocessen. Under processen för att identifiera och dela kunder [!DNL Device Graph] inte:

* Berätta för finansföretaget att länken kom från News Company.
* Dela det kund-ID som används av en [!DNL Device Co-op] medlem med en annan.
* Ange all annan information än den som mobilenheten och den bärbara datorn delar en gemensam länk.

## Nästa steg {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Genom att läsa dokumentationen om identitet, länkning och länkdelning får du en bra uppfattning om hur [!DNL Device Graph] sammanställer data internt. Som ett nästa steg rekommenderar vi att du tar en titt på vår dokumentation som beskriver hur begreppet *`known device`* levererar enhetslänkar till medlemmar i Device Co-op. Se [Kända enheter](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) och [Okända enheter](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
