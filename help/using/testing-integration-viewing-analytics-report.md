---
title: Test the integration by viewing an Adobe Analytics report
description: Learn how to test the integration in Adobe Dynamic Media Classic by viewing an Adobe Analytics report.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/adobe_analytics_instrumentation_kit
feature: Dynamic Media Classic
role: Developer,Admin,User
exl-id: 6186fcf0-99b4-447d-ae94-b4124dcb405b
topic: Integrations, Development
level: Experienced
autotag-review: '2026-05-13T19:57:20.082Z'
TQID: 'https://experienceleague.adobe.com/BwQe9AuhBfi-bLCuO-j48kE-3gw9rgtz5GEI9nIBRjE'
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
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
---
# Test the integration by viewing an Adobe Analytics report{#testing-the-integration-by-viewing-an-adobe-analytics-report}

After you have created the necessary variables in Adobe Analytics, linked them to Adobe Dynamic Media Classic events, and completed the necessary implementation steps, you can test the setup. You can test and verify that the data is being captured inside Adobe Analytics itself. If the setup works here, then no further steps are needed. Assuming you followed the steps above and linked your Adobe Dynamic Media Classic event data to one or more Custom Traffic variables, then follow this workflow to test your data inside Adobe Analytics.

**To test the integration by viewing an Adobe Analytics report:**

1. Start an Adobe Dynamic Media Classic viewer from your account, particularly one that broadcasts the metric that you want to obtain, and interact with it to create some event data.

   For example, if you want to measure popular alternative views in an Image Set, then preview an Image Set and click the different thumbnails images.

1. Inside Adobe Analytics, go to **[!UICONTROL Custom Traffic]** > **[!UICONTROL Custom Traffic 1-10]** > [Name of prop], selecting your traffic prop name from the menu choices.

   For example, to access the **[!UICONTROL LoadAsset]** prop in the sample account, the proper menu choice is **[!UICONTROL Custom Traffic]** > **[!UICONTROL Custom Traffic 1-10]** > **[!UICONTROL LoadAsset]**. If you have more than ten custom props, you see other menu choices as well.

1. View the chart produced by Adobe Analytics. This chart is typically just the data for a single metric. If you also want to know with which asset this data is associated, obtain the asset data of this event. For example, it is often useful to know which video is watched only 50%, or which image in a set is popular.

>[!NOTE]
>
>All Adobe Dynamic Media Classic viewer data is displayed and reported in Custom Traffic reports or Custom Conversion reports of Adobe Analytics.

For more information, see [Analytics Tutorials](https://experienceleague.adobe.com/en/docs/analytics-learn/tutorials/overview).