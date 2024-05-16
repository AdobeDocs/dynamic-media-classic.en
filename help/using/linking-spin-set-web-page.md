---
title: Link a Spin Set to a Web page
description: Learn how to link a Spin Set to a Web page in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/spin_sets
feature: Dynamic Media Classic,Viewers,Spin Sets
role: User
exl-id: af75547e-20e8-44c2-b165-01532d6e21d0
topic: Content Management
level: Intermediate
---
# Link a Spin Set to a Web page{#linking-a-spin-set-to-a-web-page}

Web sites and applications access Dynamic Media Image Server content, including Spin Sets, by way of URL strings or embedded code. These URL strings are activated during the publishing process. To place the URL string or Embed Code for your Spin Set in your Web pages and applications, you copy it from Adobe Dynamic Media Classic.

>[!NOTE]
>
>The URL is not active until you publish the asset.

## Copy a Spin Set URL {#copying-a-spin-set-url}

1. In the Asset Browse panel, in the Show drop-down list, select **[!UICONTROL Spin Set]**.
1. in the Asset Library panel on the left side, navigate to the asset folder that contains the Spin Set whose Embed Code you want to copy.
1. Above the Asset Browse panel, on the right side of the toolbar, do one of the following:

    * Select **[!UICONTROL Grid View]**. In the Asset Browse panel, double-click a single asset to open it in Detail View. In the URLs and Embed Code panel on the right, select **[!UICONTROL Copy URL]** to the right of the viewer you want.
    * Select **[!UICONTROL Grid View]**. In the Asset Browse panel, select a single asset, and then below the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

    * Select **[!UICONTROL List View]**. In the Asset Browse panel, select a single asset, and then to the right of the thumbnail image, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

    * Select **[!UICONTROL Grid View]**, **[!UICONTROL List View]**, or **[!UICONTROL Detail View]**. On the same toolbar, go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**.

      In the Viewer List page, under the Actions column of the table, select **[!UICONTROL Copy URL]**.

## Add Spin Set URLs to your Web page {#adding-spin-set-urls-to-your-web-page}

Spin Sets are deployed like all zoom viewers, by way of a dynamic page (ASP or JSP) that displays the Spin Set in a zoom window. The URL call to the Adobe Dynamic Media Classic platform follows the same protocol on the zoom viewer. However, the Viewer Preset name depends on the Preset that your administrator defined as the default Spin Set Viewer Preset. For example, the following non-live, URL syntax example includes a Preset name called `viewer.jsp` and the SKU parameter is now the Spin Set name:

```as3
https://sample.scene7.com/s7ondemand/spin/viewer.jsp?company=S7Web&sku=backpack_spin
```

In this URL syntax example (the link is not live), notice a SKU number ( `sku=backpack_spin`). The string after `sku=` is the Spin Set name ( `backpack spin`).

## Copy the Embed Code of a Spin Set viewer {#copying-the-embed-code-of-a-spin-set-viewer}

Using the Embed Code feature lets you review the viewer code for the selected Spin Set. You can also copy the code to the clipboard so you can paste it in your Web pages for deployment of the viewer. Editing of the code is not permitted in the Embed Code dialog box.

**To copy the Embed Code of a Spin Set viewer:**

1. In the Asset Browse panel, in the Show drop-down list, select **[!UICONTROL Spin Set]**.
1. in the Asset Library panel on the left side, navigate to the asset folder that contains the Spin Set whose Embed Code you want to copy.
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
