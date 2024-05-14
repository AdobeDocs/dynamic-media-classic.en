---
title: Enable Adobe Analytics Video Reports
description: Learn how to enable Adobe Analytics video reports in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/adobe_analytics_instrumentation_kit
feature: Dynamic Media Classic
role: Data Engineer,Admin,User
exl-id: 9d017742-1ed2-411d-a8a6-438102bf1557
topic: Development, Integrations
level: Experienced
---
# Enable Adobe Analytics Video Reports{#enabling-adobe-analytics-video-reports}

Using Adobe Analytics heartbeat-based video reporting, you no longer must enable the four video viewer events (Play, Pause, Stop, Milestone) when you configure Adobe Analytics in Adobe Dynamic Media Classic. Video Heartbeat works with out-of-the-box Adobe Dynamic Media Classic HTML5 Video and Mixed Media viewers. The video player generates tracking data for viewing within Adobe Analytics video reports.

* For an introduction to streaming media and 'heartbeat measurement,' see [About Adobe Analytics for Streaming Media](https://experienceleague.adobe.com/en/docs/media-analytics/using/media-overview).

* The integration of Adobe Analytics video reports with Adobe Dynamic Media Classic supports solution variables, but not custom variables.

  See [Audio and Video parameters](https://experienceleague.adobe.com/en/docs/media-analytics/using/implementation/variables/audio-video-parameters) for more information about solution variables and custom variables.

* Out-of-the-box segments of one-minute increments are supported. However, custom segment reporting, such as customer-defined milestones based on time increments, % milestones, or offset milestones, is not supported.

  For more information about streaming media requirements and setup, see [Measure Steaming Media in Adobe Analytics](https://experienceleague.adobe.com/en/docs/media-analytics/using/media-overview).

* For information about custom and solution variables, see [Media reports enablement](https://experienceleague.adobe.com/en/docs/media-analytics/using/media-reports/media-reports-enable#media-reports).

>[!NOTE]
>
>If your licensed solution of Adobe Analytics does not include Video Heartbeat, continue using the steps described in this chapter to assign Adobe Analytics variables to Adobe Dynamic Media Classic viewer events and variables.
