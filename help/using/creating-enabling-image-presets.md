---
title: Create and enable Image Presets
description: Learn how to create and enable Image Presets in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/media_portal
feature: Dynamic Media Classic,Collaboration,Image Presets,Asset Management
role: Admin,User
exl-id: 94c6c388-226b-4172-a6c7-a8dcf9c0f0cf
topic: Content Management
level: Intermediate
---
# Create and enable Image Presets{#creating-and-enabling-image-presets}

When users export image assets using Media Portal, they can choose an Image Preset in the Export Selected Assets dialog box. An Image Preset is a collection of pre-defined settings. These settings can change the size, image quality, format, resolution, and other aspects of an image's appearance when it is exported.

Media Portal administrators can create Image Presets to control how images are reformatted when they are exported. Image Presets reformat images to the specifications of your company when users export images from the Adobe Dynamic Media Classic. Rather than reformatting images on their own, users export them to the precise specifications of an Image Preset.

The following restrictions apply when you export image assets:

* The width &times; height must be less than or equal to 100 MB per image. For example, the image cannot exceed 10 K &times; 10 K, or any aspect variation below, such as 8 K &times; 12 K.
* There is a maximum of 1-GB total file size per export job.
* You can have a maximum of 500 total assets per export job.

>[!NOTE]
>
>These restrictions apply only to the exporting of derived image assets, not the exporting of primary files.

To create Image Presets, see [Image Presets](application-setup.md#image_presets).

To enable users to choose Image Presets when they export files, see [Specifying export options available to Media Portal users](specifying-export-options-available-media.md#specifying_export_options_available_to_media_portal_users).

To choose which Image Presets are available to the members of a group, see [Choose Image Preset access permissions for a group](creating-media-portal-groups.md#choosing_image_preset_access_permissions_for_a_group).
