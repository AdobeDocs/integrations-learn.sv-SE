---
title: Integrera [!DNL Analytics] och kunddata i realtid [!DNL Platform] med Experience [!DNL Platform] källanslutningens självstudiekurs
description: Lär dig hur du integrerar Adobe [!DNL Analytics] med kunddata i realtid [!DNL Platform] med Experience [!DNL Platform] source-kontakten.
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13728
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integrering" type="positive"
exl-id: 1e27555d-e609-4a04-91ca-9518898ad699
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# Integrera Adobe [!DNL Analytics] och kunddata i realtid [!DNL Platform] med Experience [!DNL Platform]-källkopplingen

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer">Skapa scheman</a> för data som ska importeras.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Skapa datauppsättningar</a> för data som ska importeras.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Konfigurera rätt identiteter och identitetsnamnutrymmen i schemat</a> för att vara säker på att inkapslade data kan sammanfogas med en enhetlig profil.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html" _target="_blank" rel="noopener noreferrer">Aktivera scheman och datauppsättningar för profilen </a>.</li>
    <li>Infoga [!DNL Analytics]-data på Experience-plattformen med <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html" _target="_blank" rel="noopener noreferrer"> Adobe [!DNL Analytics]-källkopplingen </a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer">Skapa segment i upplevelsen [!DNL Platform].</a> Systemet avgör automatiskt om segmentet utvärderas som batch (dataanslutning) eller direktuppspelning (Edge-nätverk).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">Konfigurera mål för delning av profilattribut och målgruppsmedlemskap till önskade mål.</a></li>   
</ol>

>[!NOTE]
>
>Standardarbetsflödesstegen för källkopplingen för Adobe [!DNL Analytics] skapar det schema och den datauppsättning som används för att importera data från [!DNL Analytics] &quot;as-is&quot;. Därför hanteras de första två stegen av systemet. Mappningsarbetsflödet kräver att du skapar anpassade attribut. Följ därför stegen helt.
