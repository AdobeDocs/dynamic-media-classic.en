---
title: Share asset changes with peers in real time
description: Learn how to share asset changes with peers in real time in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/managing_assets
feature: Dynamic Media Classic,Asset Management,Collaboration
role: Admin,User
exl-id: d74b4966-fe43-4349-bbe1-3a379c49bf1f
topic: Administration, Collaboration
level: Intermediate
---
# Share asset changes with peers in real time{#sharing-asset-changes-with-peers-in-real-time}

Suppose you have multiple copies of Adobe Dynamic Media Classic running on computers in the same company. In such a scenario, the following actions from any Dynamic Media Classic client are updated in real time with all peer clients:

* Edit an asset (builder, image editor, and so on)
* Rename an asset
* Delete an asset
* Move an asset
* Upload one or more assets (both desktop and FTP)
* Create, delete, or rename a folder

After a change is made in the originating client, all peer clients signed into the same company are updated with the change. Changes are made to peers without notification, unless the peer is editing a changing asset in any of the image editors or builders.

When you signed in, you were prompted to allow or deny peer updates. You can "remember" the choice so you are only prompted once. To clear your choice, delete the appropriate site from the Peer Assisted Networking panel in Global Settings.

If you were editing an asset changed by a peer, you are prompted to ingest the change into the builder or editor. If you choose **[!UICONTROL Yes]**, then the builder or editor discards any changes made to the asset and imports the updated asset. If you chose **[!UICONTROL No]**, the asset is unchanged in the builder or editor and any changes you have made persist in that session.

When you saved the asset, you were notified that a newer version exists and asked if you want to overwrite the asset with your changes.
