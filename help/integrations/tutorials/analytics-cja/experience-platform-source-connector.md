---
title: Integrera [!DNL Analytics] och kundresan [!DNL Analytics] med Experience [!DNL Platform] källanslutningskurs
description: Lär dig hur du integrerar Adobe [!DNL Analytics] med kundresan [!DNL Analytics] med hjälp av Experience [!DNL Platform] source-kontakten.
solution: Customer Journey [!DNL Analytics], [!DNL Target]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integrering" type="positive"
exl-id: f0dbd59d-d5e5-40e6-b4a4-e4789e7dd7e3
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 0%

---

# Integrera Adobe [!DNL Analytics] och kundresan [!DNL Analytics] med Experience [!DNL Platform]-källkopplingen

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer">Skapa scheman</a> för data som ska importeras.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Skapa datauppsättningar</a> för data som ska importeras.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Konfigurera rätt identiteter och identitetsnamnutrymmen i schemat</a> för att vara säker på att inkapslade data kan sammanfogas med en enhetlig profil.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html" _target="_blank" rel="noopener noreferrer">Aktivera scheman och datauppsättningar för profilen </a>.</li>
    <li>Infoga data i upplevelsen [!DNL Platform] med <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics]-källkopplingen</a></li>
    <li><i>(Valfritt)</i>. Om du använder flera datauppsättningar sammanfogar du person-ID:n till <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html" _target="_blank" rel="noopener noreferrer">genererar en kombinerad datauppsättning</a>. Hoppa över det här steget om du använder en enskild [!DNL Analytics]-datauppsättning, eller om det finns en gemensam identifierare för alla datauppsättningar som du tänker använda i kundresan [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html" _target="_blank" rel="noopener noreferrer">Skapa en anslutning</a> i kundresan [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html" _target="_blank" rel="noopener noreferrer">Skapa en datavy</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html" _target="_blank" rel="noopener noreferrer">konfigurera komponentinställningarna</a> och <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html" _target="_blank" rel="noopener noreferrer">formatera mätvärden</a> i kundresan [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html" _target="_blank" rel="noopener noreferrer">Skapa ett projekt i kundresan [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Standardarbetsflödesstegen för källkopplingen för Adobe [!DNL Analytics] skapar det schema och den datauppsättning som används för att importera data från [!DNL Analytics] &quot;as-is&quot;. Därför hanteras de första två stegen av systemet. Mappningsarbetsflödet kräver att du skapar anpassade attribut. Följ därför stegen helt.
