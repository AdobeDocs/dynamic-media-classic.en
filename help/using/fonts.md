---
title: Fonts
description: Learn how to use fonts in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/support_files
feature: Dynamic Media Classic
role: User
exl-id: 186f4c7f-16f6-42f5-bc0e-55362c55e794
topic: Content Management
level: Intermediate
autotag-review: '2026-05-13T19:50:28.929Z'
TQID: 'https://experienceleague.adobe.com/g-A6M8KM6VT4m-JVyDp6KMMN82CtGTXcoUFVvQsoLps'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
---
# Fonts{#fonts}

Sometimes, Adobe Dynamic Media Classic requires you to upload a font file to enter or render text in a particular font. For example, to use a particular font for text on a template layer, upload the font file. To display eCatalog Viewer page numbers in a particular font, upload the font file.

Adobe Dynamic Media Classic supports these font types:

* All TrueType fonts
* PostScript&reg; fonts
* OpenType/TrueType fonts
* OpenType/PostScript fonts
* PhotoFonts

After a font file has been uploaded, you can change its Adobe Dynamic Media Classic ID, font name, and type information on the Edit Info screen.

>[!NOTE]
>
>Adobe Dynamic Media Classic recommends uploading all font styles (bold, italic, bold/italic, and regular) if you plan to use fonts in template layers. Adobe Dynamic Media Classic needs these font styles to process requests. Uploading all `PostScript/Adobe Type1` files associated with a font is also recommended because some of these fonts contain detailed kerning information.

## Upload font files {#uploading-font-files}

Upload font files with the same techniques you use to upload other files. You can store font files in any Adobe Dynamic Media Classic folder. See [Uploading your files](uploading-files.md#uploading_your_files).

## Edit font file information {#editing-font-file-information}

You can change the ID name of a font and its type information. Editing a font file can be helpful in searches and making fonts easier to identify.

In the Browse panel, select the font file you want to edit in Detail View and choose File > Edit Info. The Edit Info screen opens. Choose the following options and then select **[!UICONTROL Submit]**.

* **[!UICONTROL Font Name]**: This name identifies the font when it is published.

* **[!UICONTROL PostScript Name]**: This name is the full PostScript name for the font. It usually indicates the weight or style.

* **[!UICONTROL RTF Name]**: This name appears on a pop-up menu in the RTF editor where template text layers are created.

* **[!UICONTROL Font Family Name]**: This name lists the font name without the style, weight, or font-type indicator.

* **[!UICONTROL Font Style]**: The options are Plain, Bold, Italic, and Bold-Italic.

* **[!UICONTROL Font Type]**: The options are TrueType and Adobe Type 1. If you call these fonts by another name, you can enter it.

* **[!UICONTROL Font Type Abbreviation]**: The options are as follows:

  * **[!UICONTROL TTF]**: TrueType font files used for PDF/PostScript rendering and image serving.

  * **[!UICONTROL AFM]**: Adobe PostScript font files that contain Adobe Font Metrics information and are used for image serving.

  * **[!UICONTROL PFM]**: Adobe PostScript font files that contain binary font metric information.

  * **[!UICONTROL PFB]**: Adobe PostScript font files that contain binary font outline information and are used for PDF/PostScript rendering and image serving.
