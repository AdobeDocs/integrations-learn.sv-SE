---
title: Integrera [!DNL Analytics] och kunddata i realtid [!DNL Platform] med Experience [!DNL Platform] Edge-självstudiekursen
description: Lär dig hur du integrerar Adobe [!DNL Analytics] med kunddata i realtid [!DNL Platform] med AEP Web SDK, AEP Mobile SDK eller Edge Network Server-API:t.
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: 13732
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integrering" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 1%

---

# Integrera Adobe [!DNL Analytics] och kunddata i realtid [!DNL Platform] med Edge självstudiekurs i Experience [!DNL Platform]

<ol>
    <li><a href="https://experienceleague.adobe.com/sv?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer">Skapa scheman</a> för data som ska importeras.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Skapa datauppsättningar</a> för data som ska importeras.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Konfigurera rätt identiteter och identitetsnamnutrymmen i schemat</a> för att vara säker på att inkapslade data kan sammanfogas med en enhetlig profil.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Aktivera scheman och datauppsättningar för profilen </a>.</li>
    <li>Infoga data i upplevelsen [!DNL Platform] med någon av följande metoder:</li>
        <ul>
           <li>Upplev [!DNL Platform] Web SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Självstudiekurs</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Checklista</a></li>
                </ul>
            <li>Upplev [!DNL Platform] Mobile SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Självstudiekurs</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Checklista</a></li>
                </ul></li>
            <li>Edge Network Server-API:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Självstudiekurs</a></li>
                </ul>
       </ul>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Skapa segment i upplevelsen [!DNL Platform].</a> Systemet avgör automatiskt om segmentet utvärderas som batch (dataanslutning) eller direktuppspelning (Edge-nätverk).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html?lang=sv-SE" _target="_blank" rel="noopener noreferrer">Konfigurera mål för delning av profilattribut och målgruppsmedlemskap till önskade mål.</a></li>
</ol>

>[!NOTE]
>
>Standardarbetsflödesstegen för källkopplingen för Adobe [!DNL Analytics] skapar det schema och den datauppsättning som används för att importera data från [!DNL Analytics] &quot;as-is&quot;. Därför hanteras de första två stegen av systemet. Mappningsarbetsflödet kräver att du skapar anpassade attribut. Följ därför stegen helt.
