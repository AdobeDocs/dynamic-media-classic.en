---
title: "Quick Start: Spin Sets"
description: An introduction and Quick Start to Spin Set to help you get up and running quickly.
uuid: d0af9db6-cb6f-48f0-89f6-f3ab2da0659f
contentOwner: admin
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/spin_sets
discoiquuid: 282b8e83-b20f-43f7-b9f8-6eebd5b1c5a7
feature: Dynamic Media Classic,Viewers,Spin Sets
role: User
exl-id: 26e3cd5b-f070-4b92-af36-25631723460e
---
# Quick Start: Spin Sets{#quick-start-spin-sets}

A Spin Set simulates the real-world act of turning an object to examine it. Spin Sets make it possible to view items from any angle, gaining the key visual details from any angle. A Spin Set simulates a 360-degree viewing experience. Dynamic Media Classic offers one-dimensional Spin Sets in which viewers can rotate an item, and two-dimensional Spin Sets in which viewers can rotate and flip the item. Moreover, users can "free-form" zoom and pan any of the views with a few simple mouse-clicks. In this way, users can examine an item more closely from a particular viewpoint. 

![Images for a spin set.](/help/assets/spin_set.png)

Spin Sets also accept Image Maps. An Image Map is a region on an image within the Spin Set that displays a rollover panel with text. When the user clicks an Image Map, an action of some kind is triggered. For example, a web page is launched so that the user can learn more about a product. To point out an image map in a Spin Set, an outline appears around the Image Map itself when the user moves their mouse pointer over it.

See [Creating Image Maps](creating-image-maps.md).

This Spin Sets Quick Start is designed to get up and running quickly with Spin Set techniques in Dynamic Media Classic. Follow steps 1 through 7. At the end of each step, you can click a topic link to learn more.

## 1. Creating and uploading the images

At minimum, you need 8-12 shots of an item for a one-dimensional Spin Set and 16-24 for a two-dimensional Spin Set. The shots must be taken at regular intervals to give the impression that the item is rotating and being flipped. For example, if a one-dimensional Spin Set includes 12 shots, rotate the item 30?? (360/12) for each shot.

On the Global Navigation bar, click **[!UICONTROL Upload]** to upload spin images from your computer or network to Dynamic Media Classic.

See [Guidelines for shooting Spin Set images](creating-spin-set.md#guidelines-for-shooting-spin-set-images).

## 2. Creating a Spin Set

To create a Spin Set, on the Global Navigation bar, click **[!UICONTROL Build]** > **[!UICONTROL Spin Sets]**. In the Spin Set Size dialog box, choose how many rows and cells you want, and click **[!UICONTROL OK]**. Then drag images into the grid on the Spin Set page.

See [Creating a Spin Set](creating-spin-set.md#creating-a-spin-set).

<!-- 

Comment Type: remark
Last Modified By: unknown unknown 
Last Modified Date: 

<p>See <a href="#UnresolvedLink-sc7_spinsets_sp.xml#WS98ca2e6790647c06-245331fc135ab744793-8000">Including Image Maps in Spin Sets</a> to add clickable, hotspot regions, known as Image Maps, to images in a Spin Set. </p>

 -->

<!-- 

Comment Type: remark
Last Modified By: unknown unknown 
Last Modified Date: 

<p>See also <a href="#UnresolvedLink-sc7_spinsets_sp.xml#WS98ca2e6790647c06229f600f135ab7cc461-8000">Managing InfoPanel content</a>.</p>

 -->

## 3. Editing a Spin Set

To edit a Spin Set, on the Global Navigation bar, click **[!UICONTROL Setup]** > **[!UICONTROL Viewer Presets]**. Select a spin set, and then click **[!UICONTROL Edit]**. Add, remove, and change the position of images. You can change the position of rows in two-dimensional spin sets.

See [Editing a Spin Set](creating-spin-set.md#editing-a-spin-set).

## 4. Setting up Spin Set Viewer Presets

Administrators can create Spin Set Viewer Presets. These presets determine the look of the Spin Set Viewer. To set up a new Spin Set Viewer Preset, on the Global Navigation bar, click **[!UICONTROL Setup]** > **[!UICONTROL Viewer Presets]**.

On the Viewer Presets page, click **[!UICONTROL Add]**, then select **[!UICONTROL Spin Set Viewer]** from the drop-down list, and then click **[!UICONTROL Add]**. Choose options in the Configure Viewer page, then click **[!UICONTROL Save]**.

See [Setting up Spin Set Viewer Presets](setting-spin-set-viewer-presets.md#setting-up-spin-set-viewer-presets).

## 5. Previewing a Spin Set

Select your Spin Set in the Browse Panel, and then click **[!UICONTROL Preview]**. On the Preview page, hold down the mouse button and drag the pointer left or right to visually ???spin??? the item.

See [Previewing a Spin Set](previewing-spin-set.md#previewing-a-spin-set).

## 6. Publishing a Spin Set

Publishing a Spin Set places it on Dynamic Media Classic servers so it can be dynamically delivered to your web site or application. It also activates the URL string that calls the Spin Set from Dynamic Media Image servers to your web site or application.

To publish a Spin Set, mark it for publish by selecting the **[!UICONTROL Mark for Publish]** icon beside its name in the Browse Panel. On the Global Navigation bar, click **[!UICONTROL Publish]** to initiate a publish. On the Publish screen, click **[!UICONTROL Submit Publish]**.

See [Publishing a Spin Set](publishing-spin-set.md#publishing-a-spin-set).

## 7. Linking a Spin Set to a web page

Dynamic Media Classic creates URL callout strings for Spin Sets, and activates them after you publish them. You can copy these URLs from the Preview page.

Select the Spin Set, and then click **[!UICONTROL Preview]**. Select a Spin Set Viewer Preset. Then click **[!UICONTROL Copy URL]**.

See [Linking a Spin Set to a web page](linking-spin-set-web-page.md#linking-a-spin-set-to-a-web-page).
