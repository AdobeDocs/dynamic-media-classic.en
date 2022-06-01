---
title: Work with PDFs
description: Learn how to work with PDFs in Adobe Dynamic Media Classic.
uuid: 26d70d28-9393-49b1-9051-d70456deca67
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/master_files
discoiquuid: 5a073de3-6b1d-4c3e-8c03-9182f9f3874a
feature: Dynamic Media Classic,Asset Management
role: User
exl-id: 02892514-61fe-48ba-a2e3-eeb30580a1e4
---
# Work with PDFs{#working-with-pdfs}

PDF (Portable Document Format) files are most often used in Adobe Dynamic Media Classic to create eCatalogs. When you upload a PDF file, Adobe Dynamic Media Classic rasterizes, or rips, the pages by default so that the pages can be used to build rich media.

**Extracted PDF pages constraint**

When you upload a PDF for page extraction, Adobe imposes the following constraint:

| Asset type | Limit type | Best practice: Recommended number by Adobe | Enforced maximum number |
| --- | --- | --- | --- |
| Image Set | Number of duplicate assets per set | 20 | 20 |
|  | Maximum number of images per set | 1000 | 1000 |
|Spin Set | Maximum number of rows/columns per 2D set | 1000 | 1000 |
| PDF | Maximum number of pages per PDF that are considered for extraction | 100 | 1000 (for refresh uploads) | 

## PDF upload options {#pdf-upload-options}

When you upload a PDF file, you can format it in various ways. You crop its pages, extract search words, enter a pixels-per-inch resolution, and choose a color space. PDF files often contain a trim margin, crop marks, registration marks, and other printer’s marks. You can crop these marks from the sides of pages as you upload a PDF file.

Options for uploading PDF files are on the Upload page under PDF Options.

### Processing options

**[!UICONTROL Rasterize]** - (Default) Rips the pages in the PDF file and converts vector graphics to bitmap images. To create an eCatalog, choose this option.

**[!UICONTROL Extract Search Words]** - Extracts words from the PDF file so that the file can be searched by keyword in an eCatalog Viewer.

**[!UICONTROL Extract Links]** - Extracts links from the PDF files and coverts them to Image Maps that are used in an eCatalog Viewer.

**[!UICONTROL Auto-Generate eCatalog With Multi-page PDF]** - Automatically creates an eCatalog from the PDF file. The eCatalog is named after the PDF file you uploaded. (This option is only available if you rasterize the PDF file as you upload it.)

### Resolution

Determines the resolution setting. This setting determines how many pixels are displayed per inch in the PDF file. The default is 150.

### Color Space options

Select the Color Space menu and choose a color space for the PDF file. Most PDF files have both RGB and CMYK color images. The RGB color space is preferable for online viewing.

* **[!UICONTROL Detect Automatically]** - Retains the color space of the PDF file.

* **[!UICONTROL Force As RGB]** - Converts to the RGB color space.

* **[!UICONTROL Force As CMYK]** - Converts to the CMYK color space.

* **[!UICONTROL Force As Grayscale]** - Converts to the Grayscale color space.

### Color Profile options

* **[!UICONTROL Convert To sRGB]** - Converts to sRGB (Standard Red Green Blue). sRGB is the recommended color space for displaying images on web pages.

* **[!UICONTROL Keep Original Color Space]** - Retains the original color space.

* **[!UICONTROL Custom From]** > **[!UICONTROL To]** - Opens menus so you can choose a Convert From and Convert To color space. You can choose a standard Photoshop color space or a color space you uploaded to Adobe Dynamic Media Classic.

See also [ICC profiles](/help/icc-profiles.md#icc_profiles).

## Crop white space from a PDF file {#cropping-white-space-from-a-pdf-file}

1. To automatically crop white-space pixels from a PDF file as you upload it, select the Crop menu and choose Trim. 
1. Specify the following options:

   * **[!UICONTROL Trim Away Based On]** - Choose whether to crop based on color or transparency:

     * **[!UICONTROL Color]** - Choose the Color option. Then select the **[!UICONTROL Corner]** menu and choose the corner of the PDF with the color that best represents the white-space color you want to crop.

     * **[!UICONTROL Transparency]** - Choose the Transparency option.

   * **[!UICONTROL Tolerance]** - Drag the slider to specify a tolerance from 0 through 1.

   * **[!UICONTROL Trimming based on color]** - Specify 0 to crop pixels only if they exactly match the color you selected in the corner of the PDF. Numbers closer to 1 allow for more color difference.

   * **[!UICONTROL Trimming based on transparency]** - Specify 0 to crop pixels only if they are transparent; numbers closer to 1 allow for more transparency.

## Crop from the sides of PDF pages {#cropping-from-the-sides-of-pdf-pages}

You can manually remove printer’s marks from the sides of the pages in a PDF file as you upload it.

1. From the Crop menu, select **[!UICONTROL Manual]**.
1. Enter pixel settings in the Top, Right, Bottom, and Left text boxes to crop from the top, bottom, and sides of pages.

How much of the page is cropped depends on the Resolution PX/Inch setting you enter for the PDF file. For example, if you enter 150 (the default) as the Resolution PX/Inch setting and crop 75 pixels from the sides of pages, a half-inch is cropped; at 150 pixels per inch, 75 pixels equals a half-inch.
