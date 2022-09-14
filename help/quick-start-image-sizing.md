---
title: "Quick Start: Image Sizing"
description: An introduction and Quick Start to Image Sizing to help you get up and running quickly with Image Sizing techniques in Adobe Dynamic Media Classic.
uuid: 6c4ad4b7-549d-4daa-b6b9-5997a8427af8
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/image_sizing
discoiquuid: dcaa9b21-b925-4dbb-865e-7918cdbda50c
feature: Dynamic Media Classic,Asset Management
role: User
exl-id: f1d46f03-57a1-43d8-a0ee-74b92b590736
---
# Quick Start: Image Sizing{#quick-start-image-sizing}

Image Sizing refers to the ability of Adobe Dynamic Media Classic to create multiple derivative images based on a single high-resolution image. Rather than manually creating several images—for example, a thumbnail and enlarged-view image—for your web site or application, you provide a single primary image. Adobe Dynamic Media Classic generates all modified images just as you request them. Being able to deliver images dynamically from a single primary image has many advantages:

* You do not have to manually create several copies of the image at different sizes. You supply one primary image to Adobe Dynamic Media Classic, and Adobe Dynamic Media Classic generates different-sized derivatives from the primary image. 
* You can quickly change the size of an image type throughout your web site or application. For example, to change all thumbnail images, you can modify the “thumbnail” Image Preset. An Image Preset—it’s similar to a macro—is a collection of size and formatting attributes. You can modify the “thumbnail” Image Preset to change the size of all thumbnail images throughout your web site or application. 
* You do not have to manage the primary files and all the various derivatives in any of your content or asset management systems internally or externally.

![You can create multiple derivative images at different sized from the same high-resolution primary file.](/help/assets/is_derivative_sizes_popup.png)

See [Image sizing: Dynamic Imaging](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/557_Image%20Sizing_converted%20renamed_Dynamic%20Imaging-AVS) training video.

The following Image Sizing Quick Start is designed to help you get up and running quickly with Image Sizing techniques in Adobe Dynamic Media Classic. Follow steps 1-5. After each step, there is a cross-reference where you can find more information if you need it.

## 1. Upload primary images

Start by uploading your primary images to Adobe Dynamic Media Classic. As to size, Adobe Dynamic Media Classic recommends using images that are the largest size you anticipate using on your web site or application. For example, if you want viewers to zoom images, upload images that are at least 2000 pixels in the largest size. Adobe Dynamic Media Classic supports many image file formats, but lossless TIFF and PNG images are recommended.

On the Global Navigation bar, select **[!UICONTROL Upload]** to upload files from your computer to a folder on Adobe Dynamic Media Classic. See [Upload primary images](uploading-master-images.md#uploading_master_images).

## 2. Set up Image Presets

Like a macro, an Image Preset is a collection of predefined size and formatting commands saved under a name. An Image Preset governs the size and formatting with which images are delivered from Dynamic Media Image Servers. You can set up Image Presets on your own if you have company administrator status. Adobe Dynamic Media Classic also comes with default Image Presets, and you can use them to dynamically deliver images.

To create an Image Preset (if you are an administrator), on the Global Navigation bar, go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Image Presets]**. Then select **[!UICONTROL Add]** to create an Image Preset, or select **[!UICONTROL Edit]** to change an existing Image Preset.

The Image Preset you create is added to the Image Preset menu on the Preview page. You can use your new Image Preset to display images dynamically on your web sites and applications. See [Set up Image Presets](setting-image-presets.md#setting_up_image_presets).

## 3. Preview Image Presets

The next step is to preview the Image Presets your administrator set up at the different preset sizes.

To explore Image Presets, on the Global Navigation bar, go to **[!UICONTROL Setup]** > **[!UICONTROL Image Presets]**, and then browse to an Image Preset.

Experiment with the different Image Presets. Find out how your image appears when it is delivered dynamically to your web site or application at different sizes.

See [Preview an image asset based on its Image Preset](previewing-asset.md#previewing_an_image_asset_based_on_its_image_preset).

## 4. Publish your primary images

Publishing your primary image files serves two essential purposes:

* Publishing your primary images to Dynamic Media Image Servers so that images can be dynamically delivered to your web site and application.
* Publishing activates the URL strings for calling images from Dynamic Media Image Servers to your web site or application. After publishing, you can copy and place the Adobe Dynamic Media Classic-generated URLs where necessary in your web site or application.

On the Global Navigation bar, select **[!UICONTROL Publish]** to start a publish job. On the Publish dialog box, select **[!UICONTROL Submit Publish]**. See [Publish primary images](publishing-master-images.md#publishing_master_images).

## 5. Link URLs to your web application

Adobe Dynamic Media Classic creates URL callout strings for images. When you publish images to Dynamic Media Image Servers, the URLs become active. You can copy these URL strings from the Browse Panel (in Detail View) or Preview screen. After you copy the URL strings, you can use them in your web site and applications. The URL for image sizing replaces the reference to a static image name in your web page code. The URL references a primary image name, which is replaced by your database for each new image to display.

URL strings generated with Image Presets contain the name of an Image Preset. This name is enclosed in dollar signs (`$`). For example, `$thumbnail$` can be the Image Preset designed to show primary images at thumbnail size. See [Link URLs to your web application](linking-urls-web-application.md#linking_urls_to_your_web_application).
