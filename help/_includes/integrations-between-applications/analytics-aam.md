---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# Integrering av [!DNL Analytics] och Audience Manager

{{analytics-description}}

{{audience-manager-description}}

Om du aktiverar den här integreringen genom att vidarebefordra [!DNL Analytics]-data på Adobe-servern till Audience Manager får Audience Manager en av de viktigaste datakällorna, nämligen kundbeteendedata online. Dessa data kan sedan kombineras med andra data, som CRM-data från första part eller partnerdata från tredje part, för att skapa avancerade kundsegment. Dessutom skickas segment i Audience Manager tillbaka till webbsidan som svar på ytterligare besökaranalys. Båda dessa värdefulla användningsområden beskrivs nedan.

De viktigaste fördelarna med att integrera Adobe [!DNL Analytics] och Audience Manager är:

+ **Förbättrad segmentering**: Kombinera data från Adobe [!DNL Analytics] och Audience Manager för precisa, personaliserade målgruppssegment i marknadsföringskampanjer.
+ **Enhetliga kundprofiler**: Integrera datakällor för att förstå interaktioner och beteenden och skapa omfattande kundprofiler.
+ **Förbättrad annonseffektivitet**: Optimera annonser med datadriven målinriktning från integrering mellan Adobe [!DNL Analytics] och Audience Manager.
+ **Datadrivna beslut**: Informera om val genom detaljerade insikter, slå samman data för Adobe [!DNL Analytics] och Audience Manager.
+ **Personaliserade upplevelser**: Skräddarsy innehåll och erbjudanden och förbättra kundinteraktionen över kontaktpunkter med båda plattformarna.

Den här integreringen sammanför värdefulla data och målgruppsinsikter. Det gör att företag kan skapa mer målinriktade och relevanta marknadsföringskampanjer och samtidigt få en djupare förståelse för kundernas preferenser och beteenden.

## Vanliga integreringar

<table>
    <thead>
        <tr>
            <th>Experience Cloud-program</th>
            <th>Integreras med</th>
            <th>När ska du använda</th>
            <th>Vanliga användningsfall</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] skickar data till Audience Manager</a>
            </td>
            <td>Adobe [!DNL Analytics]-taggtillägg eller AppMeasurement.js med vidarebefordran på serversidan aktiverad</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>När du vill skicka data från Adobe [!DNL Analytics] till Audience Manager för att skapa segment som kan delas med andra Adobe Experience Cloud-mål, personbaserade mål eller andra enhetsbaserade och anpassade mål som stöds av Audience Manager.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Dela segment till annonsplattformar som innehåller beteendeattribut som samlats in i [!DNL Analytics].</li>
                    <li>Förbättra segment med [!DNL Analytics]-data för att skapa värdefulla flerkanalssegment som kan användas för målinriktning på plats.</li>
                    <li>Lagra data i [!DNL Analytics] till segment som är genomskinliga av hash-kodade identifierare, t.ex. e-post, för användning på plattformar för sociala medier.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html" target="_blank" rel="noreferrer">Audience Manager skickar tillbaka data till [!DNL Analytics]</a>
            </td>
            <td>Adobe [!DNL Analytics]-taggtillägg eller AppMeasurement.js med vidarebefordran på serversidan aktiverad</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>När du vill dela segment från Audience Manager till [!DNL Analytics] för att informera om målgruppsidentifiering, segmentering och optimering.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Använd Audience Manager-segment som innehåller demografiska data från tredjepartsleverantörer i [!DNL Analytics]-rapporter.</li>
                    <li>Använd segment i Audience Manager som innehåller kampanjdata från annonsservrar i [!DNL Analytics]-rapporter.</li>
                    <li>Använd Audience Manager-segment som innehåller onboarddata för CRM i [!DNL Analytics]-rapporter.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
