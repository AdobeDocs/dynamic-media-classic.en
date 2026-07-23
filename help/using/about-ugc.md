---
title: About User-generated Content in Adobe Dynamic Media Classic
description: An introduction to user-generated content.
contentOwner: rbrough
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/user_generated_content
feature: Dynamic Media Classic
role: Admin,User
exl-id: 14729192-7b9d-4f42-99da-6564a3f35959
topic: Content Management
level: Intermediate
autotag-review: '2026-05-13T17:34:44.287Z'
TQID: 'https://experienceleague.adobe.com/SwNEO6U33qx45AECK79nff9f9kABWuOdq91d4X8SHd0'
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
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
---
# About User-generated content in Adobe Dynamic Media Classic {#about-user-generated-content}

UGC (user-generated content) consists of uploading assets to a dedicated [!DNL Adobe Dynamic Media Classic] storage repository and performing related operations.

UGC supports raster image file formats BMP, GIF, JPG, PNG, PSD, TIFF.

>[!IMPORTANT]
>
>Starting May 1, 2023, UGC assets in Dynamic Media remain available for use up to 60 days from the date of upload. After 60 days, the assets are removed.

<!-- * Vector: AI, EPS (EPS files from Adobe Illustrator 2018 are not supported), PDF (only when the PDF file is previously opened and saved in Adobe Illustrator CS6) -->

>[!NOTE]
>
>Support for new or existing UGC vector image assets in Adobe Dynamic Media Classic ended on September 30, 2021.

Before uploading assets, you must obtain a shared-secret key. You use this key to retrieve an upload token. You submit the upload token when you upload assets and perform other UGC tasks.

After you retrieve a shared-secret key and upload token, you can perform the following operations for user-generated content:

* Upload an asset.
* Get image asset metadata.
* Delete an uploaded asset.
* Get information about a company's disk space usage.
