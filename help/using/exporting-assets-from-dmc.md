---
title: Export assets from Adobe Dynamic Media Classic
description: Learn how to export assets from Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/managing_assets
feature: Dynamic Media Classic,Asset Management
role: User
exl-id: 5e3b0002-5ae2-4437-862f-caa098b04362
topic: Content Management
level: Intermediate
---
# Export assets from Adobe Dynamic Media Classic{#exporting-assets-from-dmc}

You can save assets you edited in Adobe Dynamic Media Classic to a local network drive. Exported assets are bundled in a ZIP file for downloading or sending by e-mail.

The compressed Zip file has a maximum file size of 1 GB for the export job. Also, you are allowed a maximum of 500 total assets per export job.

Adobe Dynamic Media Classic keeps a record of exporting jobs in the Jobs screen.

**To export assets from Adobe Dynamic Media Classic:**

1. Select the assets that you want to export, and then go to **[!UICONTROL File]** > **[!UICONTROL Export]**. 
1. In the Export Selected Assets window, click **[!UICONTROL Image Options]**, and then specify any of the following options (administrators determine which options are available to their users):

   * **[!UICONTROL Presets]** - Optionally, choose an Image Preset to format the asset when you export it. If you choose an Image Preset, the other formatting options are not available, as the asset adopts the formats defined by the Image Preset.

   * **[!UICONTROL Conversion]** - Convert the asset file or the original image.

   * **[!UICONTROL Size]** - You can select a standard size. Or, you can select **[!UICONTROL Other]** from the **[!UICONTROL Size]** drop-down list, choose the desired unit of measure, and then specify the width and the height.

        See also [Specify export options available to Media Portal users](specifying-export-options-available-media.md#specifying_export_options_available_to_media_portal_users).

   * **[!UICONTROL Format]** - Choose an image format.

   * **[!UICONTROL Color]** - Choose RGB, CMYK, or Gray.

   * **[!UICONTROL Resolution]** - Choose 72 ppi, 150 ppi, or 300 ppi.

   * **[!UICONTROL Job Name]** - You can assign a job name to the export.

   * **[!UICONTROL Send Email To]** - Optionally, enter an e-mail address if you intend to send the assets by e-mail. The e-mail message lists the URL where the recipient can go to download the assets.

1. Select **[!UICONTROL Export]**.

Three basic export actions are supported:

* Original File (export the original file for the asset)
* Convert Using Preset (use an image preset to format the asset)
* Convert Without Preset (use the export dialog to specify image modifiers)

The following asset types cannot be exported. All others generate an export.

* Image Sets
* Render Sets
* Spin Sets
* Media Sets
* Multibitrate Sets
* eCatalogs

In addition, templates cannot be exported as an "original file."

You can use conversion to export the following asset types:

* Images
* Templates
* Adjusted Images
* PDF (generates converted pages)
* PostScript&reg;

The following behavior results when a large selection of various asset types are fed into the exporter:

* All asset types which cannot be exported are removed from the list before job submittal 
* If a conversion is requested, all types which can be converted are, and all others are exported as original
