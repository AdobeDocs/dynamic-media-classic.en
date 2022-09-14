---
title: Set up Zoom Viewer Presets
description: Learn how to set up Zoom Viewer Presets in Adobe Dynamic Media Classic.
uuid: 202d80cb-8282-45d4-89e8-942c8677aa93
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/zoom
discoiquuid: 5023a933-e229-4d3c-8e91-3ac5e9f4970b
feature: Dynamic Media Classic,Viewers,Zoom
role: User
exl-id: ddaaff6c-5447-408e-9c92-bcdfd1a0e72e
---
# Set up Zoom Viewer Presets{#setting-up-zoom-viewer-presets}

Zoom Viewer Presets determine the style, behavior, and look of your Zoom viewers. Adobe Dynamic Media Classic offers many options for customizing and skinning Viewers. Adobe Dynamic Media Classic comes with default basic (fast), fly-out, and custom Zoom Viewer Presets. If you are an administrator, you can create company Zoom Viewer Presets or edit a default preset and save it with a new name.

All Zoom Viewers have buttons for zooming in, zooming out, panning, and resetting the image to its original state after zooming. What these buttons look like and how the window itself appears depends on your choice of Zoom Viewer Presets. You can configure a Zoom Viewer Preset with different colors, borders, fonts, and image settings. When configuring a Guided Zoom Viewer, you can also choose where to place the zoom targets. Zoom targets are the thumbnails that users click to zoom to areas you specify.

## About Zoom Viewer Presets {#about-zoom-viewer-presets}

Adobe Dynamic Media Classic offers these Zoom Viewer Presets:

* **Zoom Viewer: Basic** - Provides a basic zoom on original image.

* **Zoom Viewer: Fly-out** - Displays a second image of the zoomed area next to the original image. There are no controls to use, users simply move the selection over the area they want to view.

When determining the complete bandwidth usage for this viewer, consider that both the main image and the flyout image are served in the viewer. The flyout image size is determined by the main image size (Stage Width and Height) and the Zoom Factor. To keep the flyout file size from becoming too large, balance these two values: if you have a large main image size, lower the Zoom Factor value. (The Flyout Width and Flyout Height determine the size of the flyout window, but not the size of the flyout image that is served into the viewer.)

For example, if your main image size is 350 by 350 pixels, with a Zoom Factor of 3, the resulting flyout image is 1050 by 1050 pixels. If your main image size is 300 by 300 pixels, with a Zoom Factor of 4, the flyout image is 1200 by 1200 pixels. Depending on the JPEG quality setting (recommended settings are between 80-90), you can decrease the file size significantly. Recommended zoom factors are 2.5 to 4, depending on the size of your main image.

Adobe Dynamic Media Classic recommends the following parameters for fly-out Zoom Viewer Presets:

* **Enlarged image size** - Approximately 1500 by 1500 pixels, not to exceed 2000 by 2000 pixels.

* **Image size** - 100 KB or under, not to exceed 150 KB (compress the file to keep it under 150 KB).

* **Zoom Viewer: Custom** - Provides guided or unguided zoom with images, Image Sets with multiple views, or Color Swatch Sets.

## Create and edit Zoom Viewer Presets {#creating-and-editing-zoom-viewer-presets}

1. On the Global Navigation bar, go to **[!UICONTROL Setup]** > **[!UICONTROL Viewer Presets]**.
1. Do one of the following:

   * **Create a preset** - Select **[!UICONTROL Add]**. In the Add Viewer Preset dialog box, choose a platform, choose a Zoom Viewer, and then select **[!UICONTROL Add]**. Enter a name for the preset in the Preset Name box.

   * **Edit a preset** - Select a Zoom Viewer Preset, then select **[!UICONTROL Edit]**.

1. Specify settings as desired.

   To see a description of an option, select the **[!UICONTROL Info Tip]** icon next to the option.

   The Preview page displays the viewer as you update and change settings.

1. Select **[!UICONTROL Save]** or **[!UICONTROL Save As]**.
1. On the Viewer Presets page, examine the Zoom Viewer Preset or Guided Zoom Viewer Preset you created. If it needs adjusting, select **[!UICONTROL Edit]**, change settings on the Configure Viewer page, and then select **[!UICONTROL Save]**.

For information about managing Viewer Presets on the Viewer Presets screen, see [Viewer Presets](application-setup.md#viewer_presets).

>[!MORELIKETHIS]
>
>* [Create and edit Viewer Presets](application-setup.md#adding_and_editing_viewer_presets)
