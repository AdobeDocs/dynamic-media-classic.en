---
title: Delete an uploaded raster image asset
description: Learn how to delete an uploaded asset in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
feature: Dynamic Media Classic
role: User
exl-id: d845bcb2-f914-4727-8df2-049dc172f266
topic: Content Management
level: Intermediate
TQID: https://experienceleague.adobe.com/M4HobWgKu7Qs6RtUJWbRqlaApj2S8iLuwDeWUqzFMLQ
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
# Delete an uploaded asset{#deleting-an-uploaded-asset}

You can use the `delete` parameter in this format to delete an asset:

```as3
https://s7ugc1.scene7.com/ugc/image?op=delete&shared_secret=fece4b21-87ee-47fc-9b99-2e29b78b602&image_name=1442564.tif
```

The following is an example of a response when an image asset is deleted:

```as3
<?xml version="1.0" encoding="UTF-8" standalone="no" ?> 
<scene7> 
    <user_generated_content> 
        <response> 
            <serviceName>User Generated Content: Images</serviceName> 
            <version>1.0.0</version> 
            <operationName>delete</operationName> 
            <serviceStatus>SUCCESS</serviceStatus> 
            <title>Delete request for1442564.tif</title> 
            <message>Your file was successfully deleted</message> 
        </response> 
    </user_generated_content> 
</scene7>
```

You can use the following fields in the URL query string to delete an asset:

| URL parameter | Required/optional | Value |
| --- | --- | --- |
| `op` | Required | delete |
| `shared_secret` | Required | The key that is a shared-secret for the company. |
|`image_name` | Required | Name of the asset to delete. |

<!-- <li>For Vector:fxg_name</li> -->

>[!IMPORTANT]
>
>Starting May 1, 2023, UGC assets in Dynamic Media will be available for use up to 60 days from the date of upload. After 60 days, the assets will be removed.

>[!NOTE]
>
>Support for new or existing UGC vector image assets in Adobe Dynamic Media Classic ended on September 30, 2021.

**Sample image URL:**

`https://s7ugc1.scene7.com/ugc/image?op=delete&shared_secret=fece4b21-87ee-47fc-9b99-2e29b78b602&image_name=1442564.tif`

<!-- 
**Sample vector URL:**

`https://s7ugc1.scene7.com/ugc/vector?op=delete&shared_secret=2160a8fa-cec6-45ba-8d59- ca595f6d2b47& &fxg_name=8875744.fxg` 
-->
