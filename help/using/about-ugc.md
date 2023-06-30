---
title: About User-generated content in Adobe Dynamic Media Classic
description: An introduction to user-generated content.
uuid: ba867a6a-84a4-4968-9a77-712f3ce5dad5
contentOwner: rbrough
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/user_generated_content
discoiquuid: c1594abf-8cc2-46dd-88bf-af93db7db607
feature: Dynamic Media Classic
role: Admin,User
exl-id: 14729192-7b9d-4f42-99da-6564a3f35959
topic: Content Management
level: Intermediate
---
# About User-generated content in Adobe Dynamic Media Classic {#about-user-generated-content}

Using UGC (user-generated content) consists of uploading assets to a dedicated Adobe Dynamic Media Classic storage repository and performing related operations.

UGC supports raster image file formats BMP, GIF, JPG, PNG, PSD, TIFF.

>[!IMPORTANT]
>
>Starting May 1, 2023, UGC assets in Dynamic Media will be available for use up to 60 days from the date of upload. After 60 days, the assets will be removed.

<!-- * Vector: AI, EPS (EPS files from Adobe Illustrator 2018 are not supported), PDF (only when the PDF file is previously opened and saved in Adobe Illustrator CS6) -->

>[!NOTE]
>
>Support for new or existing UGC vector image assets in Adobe Dynamic Media Classic ended on September 30, 2021.

Before uploading assets, you obtain a shared-secret key. You use this key to retrieve an upload token. You submit the upload token when you upload assets and perform other UGC tasks.

After you retrieve a shared-secret key and upload token, you can perform the following operations for user-generated content:

* Upload an asset.
* Get image asset metadata.
* Delete an uploaded asset.
* Get information about a company's disk space usage.
