---
title: Specify export options available to Media Portal users
description: Learn how to specify export options that are available to Media Portal users in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
feature: Dynamic Media Classic,Collaboration,Asset Management
role: Admin,User
exl-id: c27df6c2-76f4-441c-bd26-cee98203291e
topic: Collaboration, Content Management
level: Intermediate
---
# Specify export options available to Media Portal users {#specifying-export-options-available-to-media-portal-users}

If the administrator gives them permission, Media Portal users can reformat images as they export them. For example, they can change the size, file format, and image quality. Automatically reformatting images as they are exported saves time by not having to reformat images separately. Moreover, administrators can create a preset —a pre-established selection of image format settings. You can use a preset when exporting images to reformat them to the specifications of your company.

The following two restrictions apply if you export image assets by way of a user-defined conversion or if you export original primary images:

* The compressed Zip export file has a maximum file size of 1 GB for the export job.
* You can have a maximum of 500 total assets per export job.

See also [Export assets from Adobe Dynamic Media Classic](exporting-assets-from-dmc.md#exporting-assets-from_dmc).

**To specify export options available to Media Portal users:**

1. On the Global Navigation bar, go to **[!UICONTROL Setup]** > **[!UICONTROL Image Presets]**.
1. In the Image Presets window, select any of the following:

   * **Enable User-Defined Conversion**: When selected, this option lets users choose other from the **[!UICONTROL Size]** drop-down list in the Export Selected Assets window. Users can then choose a unit of measure such as pixels or centimeters, and then specify the desired width and the height. When they export or download these files, the image files are reformatted.

     When **[!UICONTROL pixels]** are chosen from the **[!UICONTROL Size]** drop-down list, the resulting image width &times; height cannot exceed 100 million pixels. This size equates to 10,000 &times; 10,000 pixels for a square image, or roughly 8,000 &times; 12,000 pixels for a 2x3 aspect ratio image. This size limitation does not apply if you export original primary images.

     Deselect this option for users to download files without reformatting them as they are downloaded.

   * **Enable Export Original**: Lets you export original primary images. In the **[!UICONTROL Export Selected Assets]** panel, users can open the **[!UICONTROL Conversion]** drop-down menu and choose **[!UICONTROL Export Original]** to export original files. Deselect this option if you want to force users to choose an Image Preset or choose conversion options when they export images.

>[!MORELIKETHIS]
>
>* [Image Presets](application-setup.md#image_presets)
>* [Choose Image Preset access permissions for a group](creating-media-portal-groups.md#choosing_image_preset_access_permissions_for_a_group)
