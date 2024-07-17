---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 1%

---


# Integrera Adobe [!DNL Analytics] med kundresan [!DNL Analytics]

{{analytics-description}}

{{customer-journey-analytics-description}}

Integrering av Adobe [!DNL Analytics] med kundresan [!DNL Analytics] ger viktiga fördelar:

+ **Omfattande insikter** om kundbeteenden och -preferenser.
+ **Sömlös flerkanalsspårning** ger en helhetsbild.
+ **Enhetliga data och rapporter** för korrekt analys.
+ **Förbättrad personalisering** och förbättrat kundengagemang.
+ **Datainsikter i realtid** för smidigt beslutsfattande.

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
            <td rowspan="2">[!DNL Analytics] och kundresa [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform]-källkoppling</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Rekommenderat tillvägagångssätt för kunder som redan har implementerat Adobe [!DNL Analytics] och vill ha det snabbaste sättet att importera dessa data till Experience [!DNL Platform] att använda i kundresan [!DNL Analytics].</li>
                    <li>När datatillgängligheten för kundprofilen kan vara mellan 2 och 30 minuter från datainsamlingen och datasjön är tillgänglig i upp till 90 minuter.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Direkt, användargränssnittsinitierat arbetsflöde.</li>
                    <li>Mappar användargränssnittet för att kopiera [!DNL Analytics] utkast och eVars till nya XDM-fält.</li>
                    <li>Det snabbaste sättet att få värde från kundprofilen i realtid och kundresan [!DNL Analytics].</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Upplev [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Rekommenderad metod för nya [!DNL Analytics]-implementeringar eller när du vill implementera en långsiktig strategi.</li>
                    <li>Skickar data direkt från en enhet till upplevelsen [!DNL Platform] med AEP Web SDK, AEP Mobile SDK eller Edge Network Server-API:t.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Ger störst kontroll för data som samlats in för att stödja dina användningsfall.</li>
                    <li>Data på klientsidan mappas enkelt till XDM-fält.</li>
                    <li>Snabbaste datatillgänglighet för kundprofilen i realtid.</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
