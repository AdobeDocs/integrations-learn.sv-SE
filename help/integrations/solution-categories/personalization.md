---
title: Applikationsintegrationer för personalisering i stor skala
description: Gör personaliserade upplevelser till en del av varje ögonblick.
exl-id: 6d18813d-950c-40ae-8d5b-80bf389358fc
source-git-commit: 509b227f360718e81fb19d3a4d30aebf9de49e5a
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 1%

---

# Personalization i stor skala

I dagens mycket konkurrenskraftiga och digitalt drivna landskap har kunderna kommit att förvänta sig upplevelser som är skräddarsydda efter deras unika önskemål och behov. Genom att utnyttja funktionerna i Adobe Experience Cloud kan vi samla in och analysera omfattande kunddata, vilket ger ovärderliga insikter om beteenden, intressen och preferenser. Denna djupa förståelse underlättar leveransen av personaliserade upplevelser över olika kontaktytor och säkerställer meningsfull och engagerande interaktion. Genom att utnyttja kraften i Adobe Experience Cloud kan du utnyttja personaliseringens fulla potential, skapa starkare kundrelationer, stärka lojaliteten och få verksamheten att växa.

<table>
 <thead>
    <tr>
      <th>Användningsfall</th>
      <th>Beskrivning</th>
      <th>Exempel</th>
      <th>Program</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Skapa skräddarsydda PDF-dokument</strong></td>
      <td>
        Generera kommunikationsdokument för signering baserat på användare
        markeringar/inställningar.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Presentera ett dynamiskt genererat sekretessavtal baserat på data från en AEM
            Forms-inlämning för signering
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-acrobat-sign.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Forms och Sign</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Dataanalys och rapportering</strong></td>
      <td>
        Analysera beteendedata från digitala upplevelser <br />Använd Adobe
        [!DNL Analytics] Beteendedata i Analysis Workspace på kundresan
        [!DNL Analytics].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Analysera konverteringsbanor för över-/underkant</li>
          <li>Analysera kanalengagemang och -konvertering</li>
          <li>Förstå innehåll som visas högst upp</li>
          <li>Förstå de viktigaste produktkategorierna och produkterna</li>
          <li>
            Analysera användningen av verktyg för att optimera självbetjäning
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] och kundresa [!DNL Analytics]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Rapportering för personaliseringsaktiviteter<br />Analysera optimering
        testresultat, inklusive A/B-tester, genom att använda Adobe [!DNL Target] och
        generera omfattande rapporter via Adobe [!DNL Analytics] .
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Visa A/B-testresultat i innehållsrika analysrapporter</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] och [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Anpassa e-postleveranser</strong></td>
      <td>
        Anpassa e-postleveranser med dynamiskt innehåll genom att använda
        funktioner i Adobe [!DNL Target].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Lägg till personaliserade erbjudanden i kundens e-postmeddelanden</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/campaign//campaign-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Campaign] och [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <strong>Utöka målgrupper för personaliserings- och annonsplattformar</strong>
      </td>
      <td>
        Använd Audience Manager-segment för att skapa målgrupper i Real-Time CDP för att
        användning i personaliserings- och återmarknadsföringsstrategier.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Anonym målgruppsanpassning och personalisering på
            webbplatsen, mobilappen eller de annonskanaler som stöds
          </li>
          <li>
            Optimera landningssidan och förautentiseringsrutiner baserat på
            kända enhets- och beteendeegenskaper
          </li>
          <li>
            Utnyttja datanätverket från tredje part i Audience Manager för ytterligare
            förfina och utöka era målgrupper för målinriktning
          </li>
          <li>Dela segment i Audience Manager till RTCDP</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/aam/aam-rtcdp.md"
          target="_blank"
          rel="noopener noreferrer"
          >Kunddata för Audience Manager och realtid [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Använd [!DNL Analytics]-data för att skapa målgrupper som ska användas i personalisering eller
        återmarknadsföring.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Målgruppsanpassning och personalisering på enheter eller
            annonskanaler som stöds.
          </li>
          <li>
            Optimera kända kundlandningssidor och anonyma upplevelser
            baserat på enhets- och beteendeattribut.
          </li>
          <li>Aktivera målgrupper för kända kanaler, som e-post och SMS.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] och kunddata i realtid [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Personalisera webbupplevelser</strong></td>
      <td>
        Skräddarsy upplevelsen av single page-applikationer (SPA) genom att effektivt
        använder AEM Headless tillsammans med Adobe [!DNL Target].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>SPA och mobilappspersonalisering</li>
          <li>Personaliserade API-svar.</li>
          <li>[!DNL Target]leverans av avancerat innehåll.</li>
          <li>A/B-testvariationer.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Headless och [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Leverera skräddarsydda webbupplevelser genom att effektivt använda AEM Sites
        och Adobe [!DNL Target] för personalisering.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>AEM webbplatspersonalisering.</li>
          <li>Anpassa webbinnehåll.</li>
          <li>Optimera användarupplevelserna.</li>
          <li>A/B-testvariationer.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Sites och [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Personalisera digitala upplevelser</strong></td>
      <td>
        Använd kundprofiler i realtid och centralt hanterade [!DNL Platform] segment
        för att personalisera meddelanden över webben, mobiler och andra digitala kanaler
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Innehållspersonalisering för kända besökare</li>
          <li>Öka lojalitetsregistrering och deltagande</li>
          <li>Identifiera och engagera kunder som riskerar att falla samman</li>
          <li>Erbjudandepersonalisering i realtid</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Kunddata i realtid [!DNL Platform] och [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Förbättra leadgenerering</strong></td>
      <td>
        Använd kundprofiler i realtid och centralt hanterade [!DNL Platform] segment
        för att personalisera meddelanden över webben, mobiler och andra digitala kanaler
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Innehållspersonalisering för kända besökare</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Kunddata i realtid [!DNL Platform] och [!DNL Target]</a
        >
      </td>
    </tr>
  </tbody>
</table>
