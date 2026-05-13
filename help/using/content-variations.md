---
title: Manage content variations
description: Learn how to manage content variations in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/template_basics
feature: Dynamic Media Classic
role: User
exl-id: 65b8c314-7ec1-417f-8a7b-aa13762072a1
topic: Content Management
level: Intermediate
autotag-review: '2026-05-13T17:40:29.070Z'
TQID: 'https://experienceleague.adobe.com/KjKdz4CAeSdJ3P-LKvdmsoGlkroeOZ60AvydF2FBHaI'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
---
# Manage content variations{#managing-content-variations}

Use template sets to manage the way asset variations are published.

Create a template set to manage variations of a template. You can control which variation is used without changing the code on your site. This method helps content managers rotate content without requiring IT to change a URL in the Web code.

Universal URLs are used to display the template variation that appears on the page, based on the order they are listed in the set. The template at the top of the template set list is always published.

You can use any Image Preset URL from the list. Image Preset URLs are like universal URLs. There can be more than one Image Preset URL.

1. Go to **[!UICONTROL Build]** > **[!UICONTROL Template Sets]**.
1. In the builder, select a template, then select **[!UICONTROL Add/Preview]**.
1. Modify the template properties and select **[!UICONTROL Save As]** to create another version.
1. Type a name, and then select **[!UICONTROL Save]**.

   Both the asset and the template must be published.

1. Go to the Detail page to get a copy URL from the URLs section.

You can move a template in the template order (for example, to the top of the list) by dragging it to its new location. Publish again to submit the new order.

>[!NOTE]
>
>If necessary, clear the cache to see the changes. The change only appears on the website after the change has made its way through the cache cycle.
