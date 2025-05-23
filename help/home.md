---
keywords: Stöd för Experience Platform;plattformar;stöd för intelligenta tjänster; kundsupport; attribueringssupport; support för rtcdp; supportanmälan;kundsupport
title: Adobe Experience Cloud Customer One for Enterprise
description: Ny Adobe-upplevelse för kundsupport
seo-description: New Adobe Customer Support Experience
seo-title: Adobe Experience Cloud Customer One for Enterprise
exl-id: 276e0862-6f7e-491e-b63e-10a50b7238c2
source-git-commit: 79858d43281431431b980c71ee3b09f99b445c62
workflow-type: tm+mt
source-wordcount: '834'
ht-degree: 0%

---

# Adobe Customer Support Experience

## Experience League supportbiljetter

Supportärenden skickas nu via [Experience League](https://experienceleague.adobe.com/home?lang=sv-SE#support). Instruktioner om hur du skickar en supportanmälan finns i avsnittet om att [skicka en supportanmälan](#submit-ticket).

Vi arbetar för att förbättra ditt sätt att interagera med Adobe kundsupport. Vår vision är att effektivisera supportupplevelsen genom att gå över till en enda ingång med Experience League. När du är klar kommer din organisation enkelt att få tillgång till kundsupport på Adobe, få bättre insyn i servicehistoriken via ett gemensamt system för alla produkter samt begära hjälp via telefon, webben och chatt via en enda portal.

Om du är Adobe Commerce-användare läser du [Skicka ett supportärende](https://experienceleague.adobe.com/sv/docs/commerce-knowledge-base/kb/help-center-guide/magento-help-center-user-guide#support-case) i användarhandboken för Experience League Support för Adobe Commerce.

## Supportberättigade roller som krävs för att skicka in ärendet {#submit-ticket}

Om du vill skicka in en supportanmälan i [Experience League](https://experienceleague.adobe.com/home?lang=sv-SE#support) måste du ha tilldelats rollen som supportadministratör av en systemadministratör. Endast en systemadministratör i din organisation kan tilldela den här rollen. Produkt, produktprofil och andra administrativa roller kan inte tilldela supportadministratörsrollen och kan inte visa alternativet **[!UICONTROL Create Case]** som används för att skicka ett supportärende. Mer information om de olika typerna av administratörsroller och deras rättigheter finns i [Administratörsroller](admin-roles.md).

Om du använder Commerce är processen för att dela åtkomst till arbetet med supportärenden annorlunda. Mer information finns i [Delad åtkomst: ge andra användare behörighet att komma åt ditt konto](https://experienceleague.adobe.com/sv/docs/commerce-knowledge-base/kb/help-center-guide/magento-help-center-user-guide#shared-access) i användarhandboken för Experience League Support för Adobe Commerce.

### Lägga till support berättigar roller till en organisation

Supportadministratörsrollen är en icke-administrativ roll som har åtkomst till supportrelaterad information. Supportadministratörer kan visa, skapa och hantera problemrapporter.

Så här lägger du till eller bjuder in en administratör:

1. I Admin Console väljer du **[!UICONTROL Users]** > **[!UICONTROL Administrators]**.
1. Klicka på **[!UICONTROL Add Admin]**.
1. Ange namn eller e-postadress.

   Du kan söka efter befintliga användare eller lägga till en ny användare genom att ange en giltig e-postadress och fylla i informationen på skärmen.

   ![Lägg till administratör](assets/admin-console-add-admin.png)

1. Klicka på **[!UICONTROL Next]**. En lista med administratörsroller visas.

Så här tilldelar du en supportadministratörsroll till en användare (gör det möjligt för en användare att kontakta support):

1. Välj alternativet **[!UICONTROL Support administrator]**.

   ![Redigera administratörsrättigheter](assets/edit-admin-rights.png)

1. Välj något av följande två alternativ:

   * Alternativ 1: **[!UICONTROL Basic support administrator]**. Välj det här alternativet om du vill ge användarsupporten åtkomst till alla lösningar (utom Marketo Engage).
   * Alternativ 2: **[!UICONTROL Product support administrator]**: Välj det här alternativet om du vill ha stöd för Marketo Engage. Välj vilka Marketo Engage-instanser som ska ge användaren support åtkomst.

   ![Redigera administratörsrättigheter för Marketo](assets/edit-admin-rights-advanced.png)

1. När du har gjort markeringarna klickar du på **[!UICONTROL Save]**.

Användaren får en e-postinbjudan om de nya administratörsbehörigheterna från `message@adobe.com`.

Användarna måste klicka på **Kom igång** i e-postmeddelandet för att kunna gå med i organisationen. Om nya administratörer inte använder länken **Kom igång** i e-postinbjudan kan de inte logga in på Admin Console.

Som en del av inloggningsprocessen kan användare uppmanas att konfigurera en Adobe-profil om de inte redan har en. Om användare har flera profiler associerade med sin e-postadress måste användarna välja **Gå med i team** (om de uppmanas till det) och sedan välja den profil som är associerad med den nya organisationen.

![Bekräftelse av administratörsrättigheter](assets/admin-rights-confirmation.png)

Mer information finns i anvisningarna för [Redigera företagsadministratörsroll](admin-roles.md#add-enterprise-role) i dokumentationen för administrativa roller. Observera att endast en systemadministratör för din organisation kan tilldela den här rollen. Mer information om administrativ hierarki finns i dokumentationen för [administrativa roller](admin-roles.md).

### Skapa en supportanmälan med Experience League

Processen för att skicka in supportärenden är nu direkt integrerad med Experience League supportplattform. Det här är en självbetjäningsportal som nyligen har gjorts om för att erbjuda mer personalisering och användarvänlighet för berättigade kunder.

1. Om du vill skapa en biljett med [Experience League](https://experienceleague.adobe.com/home?lang=sv-SE#support) väljer du fliken **[!UICONTROL Support]** i den övre navigeringen.
   ![Fliken Stöd för Experience Leag](./assets/experience-league-support-tab.png)
1. På supportwebbplatsen kan du enkelt navigera till öppna supportärenden, logga ett nytt ärende, visa de viktigaste supportartiklarna eller få tillgång till ytterligare utbildningsmaterial.
   ![Experience Leag - supportresurser](./assets/experience-league-support-resources.png)
1. Välj **[!UICONTROL Open a support ticket]** om du vill skicka ett ärende. Välj även alternativet **[!UICONTROL Open Ticket]** på sidofältsmenyn. Du dirigeras till sidan för att skapa ärenden där du kan ange ditt produktnamn (Audience Manager, Campaign, Target, osv.), falltitel och fallbeskrivning. Om du vill snabba upp felsökningsprocessen bör du vara så beskrivande som möjligt när du beskriver det problem du står inför.
   ![Öppen biljett för Experience Leag](./assets/experience-league-open-ticket.png)
1. Fyll i följande fält mot formulärets slut. När du väljer en lösning får du följande frågor och en del lösningar har ytterligare fält:

   * Ärendeprioritet (låg, Medium, hög, kritisk)
   * Affärspåverkan
   * Kundens tidszon (Nord- och Sydamerika, EMEA, APAC)

![Upplev prioriteten för utbildningsbiljetter](./assets/experience-league-ticket-priority.png)

>[!TIP]
>
> Om du inte kan se alternativet **[!UICONTROL Create Case]** eller fliken **[!UICONTROL Support]** måste du kontakta en systemadministratör för att tilldela administratörsrollen för support.








>[!NOTE]
>
> Om problemet leder till avbrott eller allvarliga avbrott i ett produktionssystem tillhandahålls ett telefonnummer för omedelbar hjälp.




<!--

## What About the Legacy Systems?

New Tickets/Cases will no longer be able to be submitted in legacy systems as of May 11th.  The [Admin Console](https://adminconsole.adobe.com/) will be used to submit new tickets/cases.

### Existing Tickets/Cases

* Between May 11th and May 20th the legacy systems will remain available to work existing tickets/cases to completion.
* Beginning May 20th the support team will migrate remaining open cases from the legacy systems to the new support experience.  You will receive an email notification regarding how to contact support to continue to work these cases.
-->
