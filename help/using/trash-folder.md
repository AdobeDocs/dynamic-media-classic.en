---
title: Manage the Trash folder
description: Learn how to manage the Trash folder.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/managing_assets
feature: Dynamic Media Classic,Asset Management
role: User
exl-id: cffeec19-43fd-4a97-bdcc-df81af108ddd
topic: Content Management
level: Intermediate
---
# Manage the Trash folder{#managing-the-trash-folder}

Items that you delete from Adobe Dynamic Media Classic are moved to the Trash folder. These deleted items remain in this folder for seven days until they are restored or permanently deleted. You can examine deleted items by selecting the **[!UICONTROL Trash]** icon at the bottom of the Asset Library, and viewing items in the Trash folder page.

All users can restore items in the Trash folder to the folders from which they were deleted. All users can also empty the Trash folder of all its contents.

Deleting items from the Trash folder permanently deletes items from Adobe Dynamic Media Classic; items deleted from the Trash folder can no longer be restored. For information on setting up notifications for company administrators when assets are about to be automatically deleted from the Trash, see [Application General Settings](application-setup.md#general_settings).

>[!NOTE]
>
>Assets that have been moved to the Trash folder are still registered on Adobe Dynamic Media Classic. For example, suppose you try to upload a file that has the same name as a deleted file in the Trash folder. Adobe Dynamic Media Classic treats the asset that you want to upload as a duplicate asset. As such a case, a number is appended to its name.

## About the Trash folder {#about-the-trash-folder}

Deleting an item in a folder places the item in the Trash folder. The following happens when you delete an item and move it to the Trash folder:

* Although the item is removed from your Adobe Dynamic Media Classic folder, its ID cannot be assigned to another asset while it remains in the Trash folder. If you try to upload an asset with the same name as a file in the Trash folder, Adobe Dynamic Media Classic appends a numeral to the name of the asset. 
* The item cannot be published. Even if the item was marked for publish when you deleted it, it is not published.
* The item remains in the Trash folder until it is restored, seven days pass, or someone chooses the **[!UICONTROL Empty the Trash]** command. After seven days, an automatic clean-up operation permanently deletes the item.

## Restore assets from the Trash folder {#restoring-assets-from-the-trash-folder}

It is not necessary for the person who deleted an asset to restore it; anyone can restore assets from the Trash folder. Assets that are restored are placed in the folders from which they were deleted. If these folders no longer exist, Adobe Dynamic Media Classic re-creates them, and the restored assets are placed in the re-created folders.

To restore assets from the Trash folder to the folders from which they were deleted, do the following:

1. At the bottom of the Asset Library panel, select the **[!UICONTROL Trash]** icon to open the Trash folder.
1. Select the asset or assets that you want to restore.
1. Go to **[!UICONTROL File]** > **[!UICONTROL Restore from trash]**.

## Permanently deleting assets in the Trash folder {#permanently-deleting-assets-in-the-trash-folder}

When you delete assets in the Trash folder, the assets are permanently deleted. Assets are automatically deleted from the Trash folder after seven days.

You can permanently delete assets from the Trash folder by electing the **[!UICONTROL Trash]** icon. On the Trash folder page, do any of the following:

* **Deleting individual assets**: You can permanently delete assets. Select the assets that you want, then click **[!UICONTROL File]** > **[!UICONTROL Empty From Trash]**.

* **Deleting all assets**: Go to **[!UICONTROL File]** > **[!UICONTROL Empty trash]**.

>[!MORELIKETHIS]
>
>* [Delete assets](moving-renaming-deleting-assets.md#delete_assets)
