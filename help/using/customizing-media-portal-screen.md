---
title: Customize the Media Portal screen
description: Learn how to customize the Media Portal screen in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/media_portal
feature: Dynamic Media Classic,Collaboration,Asset Management
role: Admin,User
exl-id: b0c5f70a-2388-42aa-a1ed-fd745ff90518
topic: Collaboration, Content Management
level: Intermediate
autotag-review: '2026-05-13T19:43:32.877Z'
TQID: 'https://experienceleague.adobe.com/tIJ90TIWEvVbRT1LR-z8ajTrx2zEXg33V8Q9SgOfzKY'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
---
# Customize the Media Portal screen{#customizing-the-media-portal-screen}

The Media Portal style settings allow you to brand the Media Portal screen with your company logo and colors. Use the style settings to put your company branding on Media Portal.

To access the style settings, go to **[!UICONTROL Setup]** > **[!UICONTROL Media Portal Setup]** > **[!UICONTROL Style Settings]**. Be sure you select **[!UICONTROL Save]** to save your settings after you make them. You can select **[!UICONTROL Restore]** to bring back the default settings. As you make your choices, the Preview panel shows you how they appear.

* **[!UICONTROL Logo]**: Select **[!UICONTROL Browse]**, and then choose a graphic in the Select Logo Image window.

* **[!UICONTROL Application]**: Create a gradient color blend by making choices on the menus of the Background Gradient Colors.

* **[!UICONTROL Tree]**: Choose a rollover color and selection color.

* **[!UICONTROL Accordion]**: Choose background colors, a border style, and rollover and selected colors for the accordion that appears on the right side of the screen in Details view.

* **[!UICONTROL Accordion Header]**: Choose whether to make text in the accordion header boldface.

* **[!UICONTROL Datagrid]**: Choose colors for the header row in data grids.

* **[!UICONTROL Alert]**: Choose a background color for alert message boxes.

* **[!UICONTROL Progress Bar]**: Choose a color for the bar that indicates the progress of uploads and downloads.

For Media Portal users to see the style settings that you chose, they must append `?company=(company name)` to the URL with which they access Media Portal. For example, to see style settings, Media Portal users who access the PortalCo company at the following:

`https://s7sps1.scene7.com/MediaPortal`

Use the following URL instead:

`https://s7sps1.scene7.com/MediaPortal?company=PortalCo`

Including the company name in the URL enables Media Portal to recognize which company a user wants to access and apply the company's style settings accordingly.

You can learn more about communicating URL changes to Media Portal users, and setting up a Welcome e-mail message so new users receive the correct Media Portal URL.

See [Set up the Welcome e-mail message for Media Portal users](adding-media-portal-users.md#setting_up_the_welcome_e_mail_message_for_media_portal_users).
