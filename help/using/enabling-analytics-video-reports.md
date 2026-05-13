---
title: Enable Adobe Analytics Video Reports
description: Learn how to enable Adobe Analytics video reports in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/adobe_analytics_instrumentation_kit
feature: Dynamic Media Classic
role: Developer,Admin,User
exl-id: 9d017742-1ed2-411d-a8a6-438102bf1557
topic: Development, Integrations
level: Experienced
autotag-review: '2026-05-13T19:47:00.853Z'
TQID: 'https://experienceleague.adobe.com/bXlrGU0zMEyfa-E-x-29-biChC17GJTEViBP8GoouTU'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: c2be0313-b3ae-45e0-b454-d20bf54b23f2
    internal-label: Measurement
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
