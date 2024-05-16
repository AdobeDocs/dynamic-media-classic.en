---
title: Set up Image Presets
description: Learn how to set up Image Presets in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/image_sizing
feature: Dynamic Media Classic,Image Presets
role: User
exl-id: 336802cc-b032-49b2-b2e6-d699bc997ee5
topic: Content Management
level: Intermediate
---
# Set up Image Presets{#setting-up-image-presets}

Like a macro, an Image Preset is a predefined collection of sizing and formatting commands saved under a name. To understand how Image Presets work, suppose that your Web site requires each product image to appear at two different sizes: 500 &times; 500 pixels and 150 &times; 150 pixels. You create two Image Presets, one called "Enlarge" to display images at 500x500 pixels and one called "Thumbnail" to display images at 150 &times; 150 pixels. To deliver images at the "Enlarge" and "Thumbnail" size, a Dynamic Media Image Server looks up the definition of the "Enlarge Image Preset" and "Thumbnail Image Preset." Then the server dynamically generates an image at the size and formatting specifications of each Image Preset.

Adobe Dynamic Media Classic comes with several "best practice" Image Presets that are already set up for you to use. Administrators can create Image Presets as well. To create an Image Preset, you can start from scratch or you can start from an existing one and save it under a new name.

Images that are reduced in size when they are delivered dynamically from a server can lose sharpness and detail. For this reason, each Image Preset contains formatting controls for optimizing an image when it is delivered at a particular size. These controls make sure that your images are sharp and clear when they are delivered to your Web site or application.

## Create an Image Preset {#creating-an-image-preset}

You can create your own Image Presets if you are a company administrator. You can create Image Presets or start with a default Image Preset that Adobe Dynamic Media Classic provides, edit it, and save it with a new name.

**To create an Image Preset:**

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Image Presets]**.

   You can browse to an Image Preset name on this screen to preview an existing Image Preset. When you select an Image Preset name, the sample image in the Preview window changes size and appearance.

1. Do one of the following:

   * **Create an Image Preset**: Select **[!UICONTROL Add]**.
   * **Edit an Image Preset**: Browse to the Image Preset that is most like the one you want to create and then select **[!UICONTROL Edit]**.

1. Enter a name for the Image Preset.
1. Enter Width and Height measurements in pixels. These measurements determine the size at which images are delivered.
1. Fill in the Add Preset or Edit Preset screen. For details, see [Image Preset options](application-setup.md#image_preset_options).

   Adobe Dynamic Media Classic recommends these "best practice" option choices to start:

   * **[!UICONTROL Format]**: Choose JPEG or another format that meets your requirements. All Web browsers support the JPEG image format; it offers a good balance between small file sizes and image quality. However, JPEG images use a lossy compression scheme that can introduce unwanted image artifacts if the compression setting is too low. For that reason, Adobe Dynamic Media Classic recommends setting the compression quality (on the slider) to 75. This setting offers a good balance between image quality and small file size.

   * **[!UICONTROL Sharpening]**: Do not select Sharpening (this sharpening filter offers less control than **[!UICONTROL Unsharp Masking]** settings).

   * **[!UICONTROL Resample Mode]**: Choose **[!UICONTROL Bi-Cubic]**.

   * **[!UICONTROL Unsharp Masking]** (USM): Enter the following settings:

    | Preset type | Size | USM: Amount | USM: Radius | USM: Threshold |
    | --- | --- | --- | --- | --- |
    | Cross-Sell (mini-thumbnail) | 75 &times; 75| 1.5 | 0.8 | 5 |
    | Thumbnail | 150 &times; 150 | 1.1 | 1 | 5 |
    | Main | 350 &times; 350 | 1 | 1 | 6 |
    | Enlarge | 500 &times; 500 | 1.2 | 1.2 | 5 |

1. Select **[!UICONTROL Save]**.

The Adobe Dynamic Media Classic "best practice" options for creating Image Presets listed here are general recommendations; sharpening is highly subjective. These "best practice" settings were based on a 2000 &times; 2000 primary image; settings for larger or smaller primary files can be different. If you want to adjust the Unsharp Masking settings, Adobe Dynamic Media Classic recommends these ranges:

* **[!UICONTROL Amount]**: Between `.8` and `1.5`.

* **[!UICONTROL Radius]**: Between `.6` and `2`.

* **[!UICONTROL Threshold]**: From `1` through `6`.

To delete an Image Preset, select it on the Image Presets screen, and then elect **[!UICONTROL Delete]**.

>[!MORELIKETHIS]
>
>* [Create and edit Image Presets](application-setup.md#creating_and_editing_image_presets)
>* [Image Preset options](application-setup.md#image_preset_options)
>* [Preview an image asset based on its Image Preset](previewing-asset.md#previewing_an_image_asset_based_on_its_image_preset)
