---
title: Integrera [!DNL Analytics] med [!DNL Target] självstudiekurs
description: Lär dig hur du integrerar Adobe [!DNL Analytics] med Adobe [!DNL Target].
solution: Analytics, Target
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integrering" type="positive"
exl-id: 4ab6c61f-f14e-408a-a700-53f7b3d0600a
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 1%

---

# Integrera [!DNL Analytics] med [!DNL Target]


## Integrationsvärde och konfiguration

I videofilmerna nedan visas värdet av att använda den här integreringen samt information om hur du får integreringsinställningarna.

>[!NOTE]
>
>I de här videofilmerna visas implementering och validering för [!DNL Target] at.js och [!DNL Analytics] appMeasurement.js. Information om vilka biblioteksversioner som krävs i båda verktygen finns i [dokumentationen](https://experienceleague.adobe.com/docs/target/using/integrate/a4t/a4timplementation.html?lang=sv-SE).

### Konfigurerar A4T ([!DNL Analytics] för [!DNL Target])

I den här videon, som är avsedd för en utvecklare, får du lära dig att:

* Förklara hur [!DNL Analytics]- och [!DNL Target]-begäranden binds med SDID
* Beskriv implementeringskrav för Adobe [!DNL Analytics] med Adobe [!DNL Target] (A4T)

>[!VIDEO](https://video.tv.adobe.com/v/35146/?quality=12&learn=on)

### Använd [!DNL Analytics] som Data Source för [!DNL Target]

I den här videon, som är avsedd för yrkesverksamma, får du lära dig:

* Vad är A4T och varför skulle jag använda det?
* Hur fungerar A4T?
* Vilka är förutsättningarna för att använda A4T?

>[!VIDEO](https://video.tv.adobe.com/v/17384/?quality=12&learn=on)


## Vanliga användningsfall

I videofilmerna nedan visas olika funktioner, aktivitetstyper och fördelar med att integrera via A4T.

### [!DNL Analytics] för panelen [!DNL Target] (A4T) i Analysis Workspace

På panelen [!DNL Analytics] för [!DNL Target] (A4T) kan du analysera dina aktiviteter och upplevelser på Adobe [!DNL Target], med lyft och förtroende, i Analysis Workspace.

>[!VIDEO](https://video.tv.adobe.com/v/37247/?quality=12&learn=on)

### Analysera en automatisk-[!DNL Target]-aktivitet med A4T-panelen

I den här videon får du lära dig hur du använder panelen [!DNL Analytics] för [!DNL Target] för att visualisera resultatet av ett [!DNL Target] -test.

>[!VIDEO](https://video.tv.adobe.com/v/333270/?quality=12&learn=on)

Vi har också två stegvisa självstudiekurser som visar hur du konfigurerar A4T-rapporter i Analysis Workspace för aktiviteter som &quot;autoallokering&quot; och &quot;automål&quot;:

## Konfigurera A4T-rapporter i Analysis Workspace för automatisk allokering av aktiviteter {#a4t-auto-allocate}

En autoallokeringsaktivitet identifierar en vinnare av två eller flera upplevelser och omfördelar automatiskt mer trafik till vinnaren medan testet fortsätter att köras och lära sig. Integreringen [!DNL Analytics] för [!DNL Target] (A4T) för automatisk allokering gör att du kan se dina rapportdata i Adobe [!DNL Analytics], och du kan även optimera för anpassade händelser eller mått som definieras i [!DNL Analytics].

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-allocate-activities.html?lang=sv-SE" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> Konfigurera A4T-rapporter för automatisk allokering av aktiviteter </span>
</a>

## Konfigurera A4T-rapporter i Analysis Workspace för [!DNL Target]-aktiviteter automatiskt {#a4t-auto-target}

Integreringen [!DNL Analytics] för [!DNL Target] (A4T) för [!DNL Target]-aktiviteter använder HTML-algoritmerna (Adobe [!DNL Target] ensemble Machine Learning) för att välja den bästa upplevelsen för varje besökare utifrån deras profil, beteende och kontext, allt med ett Adobe [!DNL Analytics] -målmått.

Även om det finns omfattande analysfunktioner i Adobe [!DNL Analytics] Analysis Workspace krävs det några ändringar i standardinställningen [!DNL Analytics] för [!DNL Target]-panelen för att autofunktioner [!DNL Target] ska kunna tolkas korrekt, på grund av skillnader mellan experimentaktiviteter (manuell A/B-test och automatisk fördelning) och personaliseringsaktiviteter (Auto-[!DNL Target]).

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-target-activities.html?lang=sv-SE" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> Konfigurera A4T-rapporter för automatiska-[!DNL Target] aktiviteter </span>
</a>
