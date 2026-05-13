---
title: Upload template files
description: Learn how to upload template files in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/template_basics
feature: Dynamic Media Classic
role: User
exl-id: a105c18a-7e06-43cb-938c-a3bcdc3e9d22
topic: Content Management
level: Experienced
autotag-review: '2026-05-13T19:58:21.817Z'
TQID: 'https://experienceleague.adobe.com/pwmEOjYzNJNV-yxeBfOz3xQBT3rJ9u9imU6cdNgQLDA'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
---
# Upload template files{#uploading-template-files}

Upload the files that you need for your template into Adobe Dynamic Media Classic before you begin building the template. You can build templates from an Adobe&reg; Photoshop&reg; PSD or an image file. TIFF and PNG images are recommended because they allow for transparency.

>[!NOTE]
>
>Adobe Dynamic Media Classic recommends using transparent TIFF or PSD images in your templates at the exact size that you want to display them on your Web site. When you publish the template, call the image with an Image Preset that is also the same size. Paying attention to size ensures that your template is not resized (resampled) at a size larger or smaller than the size at which it was designed.

Templates can be created from Adobe Photoshop PSD files or image files.

For detailed instructions on uploading files, see [Upload files](uploading-files.md#uploading_files). Keep the following in mind when uploading template files:

* If you are uploading a PSD file, you can create a template from it. Adobe Dynamic Media Classic creates a separate image for each layer in the PSD. In the Upload Job Options dialog box, select **[!UICONTROL Photoshop Options]**, and select **[!UICONTROL Maintain Layers]** and **[!UICONTROL Create Template]**. Then choose an option from the **[!UICONTROL Layer Naming]** drop-down list for naming the images that Adobe Dynamic Media Classic creates from layers in the PSD. 
See [PSD upload options](psd-files.md#psd_upload_options).

<!--
THERE IS NO LONGER AN IMAGE EDITING OPTIONS MENU * If you are uploading images, you can create a mask from its clipping path. This option applies to images created with image-editing applications in which a clipping path was created. In the Upload Job Options dialog box, select Image Editing Options and select the Create Mask From Clipping Path option. 
See [Image editing options at upload](image-editing-options-upload.md#image-editing-options-at-upload). 
-->

>[!MORELIKETHIS]
>
>* [Upload your files](uploading-files.md#uploading_your_files)
>* [Work with PSD files](psd-files.md#working_with_psd_files)
