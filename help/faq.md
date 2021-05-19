---
description: Svar på vanliga frågor om Device Co-op (Identity Services Cooperative och Identity Graph).
title: Device Co-op - frågor och svar
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# Vanliga frågor och svar {#faq}

Beskrivningar och svar på vanliga frågor om Identity Services Cooperative och Identity Graph.

**Vad är  [!DNL Device Co-op]det?**

Device Co-op är ett digitalt samarbete för Adobe Experience Cloud-kunder som deltar i samarbetet för att bättre identifiera sina konsumenter på olika enheter.

**Vilka tekniker används i Device Co-op?**

Device Co-op består av två tekniker:

* **Experience Cloud ID-tjänst:** Denna bastjänst i Adobe Experience Cloud ger ett gemensamt ID för att identifiera konsumenter på ett enhetligt sätt i olika lösningar, kanaler, upplevelser och enheter.
* **Adobe Experience Cloud Device Co-op:** Den här tekniken länkar olika enheter som används av en konsument eller ett hushåll.

**Hur  [!DNL Device Co-op] fungerar det?**

När varumärken tonar i sin del av enhetsövergripande pussel genom anonyma inloggningar och webbplatsbesök bearbetar Adobe dessa data till att bilda enhetskluster som representerar en grupp enheter som används av en okänd person. De här enhetskluster ges till medlemmar i Device Co-op och används för att ge kunderna en bättre och enhetligare upplevelse.

**Hur fungerar  [!DNL Device Co-op] länkenheterna?**

Se [Deterministiska och sannolika länkar](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Vilka data tillhandahåller deltagarna  [!DNL Adobe]?**

Se [Välkomstverktyg, sekretess och enhetsdiagram](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Vilka data delas mellan  [!DNL Device Co-op] medlemmarna?**

Se [Länkdelning i enhetsdiagrammet](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Kan en  [!DNL Device Co-op] medlem se länkar till enheter de aldrig sett tidigare?**

Nej. Medlemmar i Device Co-op kan bara få data baserat på enheter som har besökt en av deras varumärkes webbegenskaper. Se [Kända enheter](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) och [Okända enheter](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Kommer jag att behöva dela någon av företagets marknadsföringsinformation?**

Nej. Varumärken tillhandahåller endast anonyma enhetsdata till Adobe.

**Använder  [!DNL Adobe] personuppgifter (PII) i  [!DNL Device Co-op]dokumentet?**

Nej. All personligt identifierbar information hashas innan den förs in i något Adobe-system, så kundinformationen överförs aldrig till Adobe.

**Får mindre varumärken som bidrar med mindre enhetsdata till Device Co-op mer värde än vad de lägger in, jämfört med deras större motsvarigheter?**

Nej. Alla medlemmar i kooperativ får tillbaka värdet i förhållande till vad de lägger in. Om ett varumärke till exempel bidrar med 10 000 enheter kan de få ytterligare länkad enhetsinformation som hör till dessa 10 000. Om man ser på helheten kan detta bidrag verka minimalt. Men när allt fler varumärken av alla storlekar förenas blir det samlade bidraget stort och ger den saknade länken till många enheter som många andra, kanske större, varumärken letar efter. Se [Känslighet och känd enhet](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**Hur  [!DNL Adobe] hanterar man IP-adresser om vissa länder betraktar en IP-adress som personuppgifter?**

Device Co-op släpps först i USA och Kanada där IP-adressen inte anses vara personlig information. När kooperativet släpps i länder där IP-adressen anses vara personuppgifter, används inte IP-adressen.
