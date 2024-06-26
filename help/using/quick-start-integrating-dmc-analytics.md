---
title: "Quick Start: Integrate Adobe Dynamic Media Classic and Adobe Analytics"
description: An introduction and Quick Start on how to integrate Adobe Dynamic Media Classic and Adobe Analytics.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/adobe_analytics_instrumentation_kit
feature: Dynamic Media Classic
role: Data Engineer,Admin,User
exl-id: a8fa2414-af01-4a58-bb33-dfd12c1056cc
topic: Integrations
level: Experienced
---
# Quick Start: Integrate Adobe Dynamic Media Classic and Adobe Analytics {#quick-start-integrating-dmc-analytics}

Adobe Analytics is the industry-leading product that provides marketers with one place where they can measure, analyze, and optimize integrated data from all online initiatives across multiple marketing channels.

After integrating Adobe Analytics with Adobe Dynamic Media Classic, you can get reports about the behavior of website visitors using Adobe Dynamic Media Classic viewers on your website. For example, when a website visitor selects a zoom target in an Adobe Dynamic Media Classic Zoom Viewer, Adobe Analytics records this action. Adobe Analytics reports can gather cumulative information about user activity in Adobe Dynamic Media Classic viewers.

Using Adobe Analytics reports, you can get a clear picture of the activity of customers on your website. You can determine which product presentations lead to conversion and which do not attract customer interest.

See also [Measure Video in Adobe Analytics](https://experienceleague.adobe.com/en/docs/media-analytics/using/media-overview).

>[!NOTE]
>
>A valid Adobe Analytics account is required to integrate Analytics with Adobe Dynamic Media Classic and generate Analytics reports.

This Quick Start is designed to get you up and running quickly with the Adobe Analytics Instrumentation Kit.

## 1. Log on to Adobe Analytics by way of Adobe Dynamic Media Classic and download the Adobe Analytics report variables

>[!NOTE]
>
>Verify that you are added as a member of the Web Service Access group in Adobe Analytics. Do this verification before you configure Adobe Analytics reports. And, before you match Adobe Analytics report variables to Adobe Dynamic Media Classic events. Members in this group can access all reports in the specified report suites. You can do so using the Experience Cloud's Web Services API regardless of the permissions set in the interface. To add a member to the group, in Adobe Analytics, go to **[!UICONTROL Admin Tools]** > **[!UICONTROL User Management]** > **[!UICONTROL Edit Groups]**.

After you have verified that you are a member of the Web Service Access group, in Adobe Dynamic Media Classic, go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Adobe Analytics]**. On the Adobe Analytics Configuration page, select **[!UICONTROL Adobe Analytics Login]**.

See [Log on to Adobe Analytics](log-analytics.md#log_in_to_adobe_analytics).

In the Adobe Analytics Login dialog box, type your Experience Cloud Org ID (optional), and your complete credentials, then select **[!UICONTROL Login]**. On the Report Suite drop-down menu, select the name of the report suite that you want to use.

## 2. Assign Adobe Analytics report variables to Adobe Dynamic Media Classic viewer events and Adobe Dynamic Media Classic variables

On the Adobe Analytics Configuration page, specify the information you want in Adobe Analytics reports. For each Adobe Dynamic Media Classic viewer event that you want information about, choose an Adobe Analytics variable (from your report suite) and an Adobe Dynamic Media Classic variable.

* Viewer events describe the user activity that you want to measure in reports.
* Adobe Dynamic Media Classic variables describe the data about user events that you want the reports to deliver.

The Adobe Analytics Configuration also offers tools for activating, editing, and deleting viewer events.

After you select **[!UICONTROL Save]** in the Adobe Analytics Configuration page, a customized tracking code for measuring user activity is inserted in Adobe Dynamic Media Classic viewers. This functionality lets you track user activity in Adobe Analytics reports.

See [Configure Adobe Analytics reports](configuring-analytics-reports.md#configuring_adobe_analytics_reports).

## 3. Publish your Adobe Dynamic Media Classic viewers

Publish your Adobe Dynamic Media Classic viewers so that the viewers (with code for tracking user activity in Adobe Analytics reports) are loaded on Adobe Dynamic Media Classic servers. After you publish, this information is included in viewers. Use it for analysis by Adobe Analytics.

See [Publish configuration information](publishing-analytics-configuration-information.md#publishing_adobe_analytics_configuration_information).

## 4. Place Adobe Dynamic Media Classic viewers on your website

Place the Adobe Dynamic Media Classic viewers with Adobe Analytics tracking code on your website.

## 5. Test the Adobe Analytics integration by viewing an Adobe Analytics report

To view Adobe Analytics reports, go to the Adobe Analytics website. The Reporting page lets you view data and generate graphs and charts to measure user activity with different viewers.

See [Test the Adobe Analytics integration by viewing an Adobe Analytics report](testing-integration-viewing-analytics-report.md#testing_the_integration_by_viewing_an_adobe_analytics_report).
