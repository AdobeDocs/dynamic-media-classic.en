---
title: ICC (International Color Consortium) profiles
description: Learn about ICC profiles in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/support_files
feature: Dynamic Media Classic
role: User
exl-id: 989f2761-f5d0-4ece-b2a6-f7b4577aa8a2
topic: Administration, Content Management
level: Intermediate
---
# ICC profiles{#icc-profiles}

An ICC (International Color Consortium) profile is a file that describes how to correctly convert image files from one color space to another. ICC profiles help you to get the correct colors for your images. For example, to correctly display images designed for printing on a computer monitor, you can choose an ICC profile. This profile converts the image to a different color space and makes sure that the colors display correctly online.

In Adobe Dynamic Media Classic, you can choose an ICC profile to convert images to a different color space when you upload the images. All standard Photoshop ICC profiles are available by default on Adobe Dynamic Media Classic. To see the names of color profiles on the Upload screen, select the Color Profile menu. Then choose Custom From > To, and choose an ICC profile name on the Converted From and Converted To menus.

See [Image edit options at upload](image-editing-options-upload.md#image-editing-options-at-upload).

Besides using the default ICC profiles, you can upload other ICC profiles to Adobe Dynamic Media Classic and make them available for color space conversion. Switch to Detail View in the Browse Panel to investigate the profile class, color space type, and PCS type of an ICC profile.

## Upload ICC profiles {#uploading-icc-profiles}

Upload ICC profiles with the same techniques you use to upload files. You can store ICC profiles in any Adobe Dynamic Media Classic folder. 

See [Upload your files](uploading-files.md#uploading_your_files).

## Examine an ICC profile {#examining-an-icc-profile}

To examine an ICC profile, select it in the Browse Panel and display it in Detail View. Detail View provides this information about ICC profiles:

* **[!UICONTROL Profile Class]**: The ICC (International Color Consortium) defines each class to cover a type of application. For example, Input profiles apply to devices such as digital cameras and scanners, and Output profiles apply to printers.

* **[!UICONTROL Color Space Type]**: This number is the "input" color space of the profile, as defined by the ICC. The color space type defines the number of components of the color space and the interpretation of those components. For example, RGB is a color space with three components: red, green, and blue. The color space type does not define the particular color characteristics of the space (for example, the chromaticities of the primaries).

* **[!UICONTROL PCS Type]**: This PCS type is the "output" color space of the profile—its profile connection space. For example, a color profile can convert RGB to the PCS, which then converts it to CMYK.

For an input, display, or output profile useful for tagging colors or images, the PCS type is either XYZ or Lab. Interpret this profile as the corresponding specific color space defined in the ICC specification.
