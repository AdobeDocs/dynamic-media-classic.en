---
title: Link Zoom viewers to your Web pages
description: Learn how to link Zoom viewers to your Web pages in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/zoom
feature: Dynamic Media Classic,Viewers,Zoom
role: User
exl-id: 2073d95b-1600-481f-8038-d29e8acacf7d
topic: Administration, Content Management, Development
level: Intermediate
autotag-review: '2026-05-13T20:03:57.696Z'
TQID: 'https://experienceleague.adobe.com/Urf0qGJqj7tCCGDfNwprZnxf6YfDgavWb44pThwds0I'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Link Zoom viewers to your Web pages{#linking-zoom-viewers-to-your-web-pages}

Your Web sites and applications access Dynamic Media Image Server content by way of URL strings or embedded code. That access includes primary images and associated Zoom Targets. It also includes Zoom Viewer Presets. These URL strings are activated during the publishing process. To place these URL strings or the embedded code in your Web pages and applications, you copy them from Adobe Dynamic Media Classic.

>[!NOTE]
>
>The URL is not active until you publish the asset.

## Copy a Zoom viewer URL {#copying-a-zoom-viewer-url}

1. in the Asset Library panel on the left side, navigate to the asset folder that contains the Zoom viewer whose URL you want to copy.
1. Above the Asset Browse panel, on the right side of the toolbar, do one of the following:

    * Select **[!UICONTROL Grid View]** or **[!UICONTROL List View]**. In the Asset Browse panel, double-click a single asset to open it in Detail View. In the URLs and Embed Code panel on the right, select **[!UICONTROL Copy URL]** to the right of the viewer you want.
    * Select **[!UICONTROL Grid View]**. In the Asset Browse panel, select a single asset, and then below the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

    * Select **[!UICONTROL List View]**. In the Asset Browse panel, select a single asset, and then to the right of the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

    * Select **[!UICONTROL Grid View]**, **[!UICONTROL List View]**, or **[!UICONTROL Detail View]**. On the same toolbar, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

## Add Zoom viewer URLs to your Web page {#adding-zoom-viewer-urls-to-your-web-page}

Typically, visitors zoom images on a website by first selecting a Zoom icon (often the icon shows the image of a magnifying glass). Selecting this icon launches a dynamic Web page (ASP or JSP) that displays the image in a pop-up window. The pop-up window is where visitors actually zoom the image.

For more details and code samples, see the [Embedded HTML5 Basic Zoom Viewer](https://experienceleague.adobe.com/en/docs/dynamic-media-developer-resources/library/viewers-aem-assets-dmc/basic-zoom/c-html5-20-basic-zoom-viewer-about#section-e1c3106f5b3e445d9b95be337c2f94e2) in the Adobe Viewers Reference Guide.

## Copy the embedded copy of a Zoom viewer {#copying-the-embed-copy-of-a-zoom-viewer}

Using the embedded code feature lets you review the viewer code for the selected Zoom viewer. You can also copy the code to the clipboard so you can paste it in your Web pages for deployment of the viewer. Editing of the code is not permitted in the Embed Code dialog box.

**To copy the embedded code of a Zoom viewer:**

1. in the Asset Library panel on the left side, navigate to the asset folder that contains the Zoom viewer whose Embed Code you want to copy.
1. Above the Asset Browse panel, on the right side of the toolbar, do one of the following:

    * Select **[!UICONTROL Grid View]**. In the Asset Browse panel, double-click a single asset to open it in Detail View. In the URLs and Embed Code panel on the right, select **[!UICONTROL Embed Code]** to the right of the viewer you want.
    * Select **[!UICONTROL Grid View]**. In the Asset Browse panel, select a single asset, and then below the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Embed Code]**.

    * Select **[!UICONTROL List View]**. In the Asset Browse panel, select a single asset, and then to the right of the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Embed Code]**.

    * Select **[!UICONTROL Grid View]**, **[!UICONTROL List View]**, or **[!UICONTROL Detail View]**. On the same toolbar, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Embed Code]**.

1. In the Embed Code dialog box, select **[!UICONTROL Copy to Clipboard]**.

   Editing the code is not permitted in the Embed Code dialog box.

1. Select **[!UICONTROL Close]**.
