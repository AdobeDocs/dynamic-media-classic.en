---
title: Upgrade readiness
description: An upgrade readiness checklist when you want to advance from [!DNL Adobe Dynamic Media Classic] to [!DNL Dynamic Media] on [!DNL Adobe Experience Manager].
feature: Dynamic Media Classic
role: Admin,User
exl-id: 86537998-b7e9-449c-83eb-6fd04533a00f
topic: Administration, Migration
level: Intermediate
autotag-review: '2026-05-13T20:16:07.073Z'
TQID: 'https://experienceleague.adobe.com/3Kcp3UwvJV8Mkzk6RBRgOJQ7JKF3Ldek-SiOeqS5EKE'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Upgrade readiness checklist

Use the following checklist to help you understand and prepare for an upgrade from [!DNL Dynamic Media Classic] to [!DNL Dynamic Media].

|  | Task | Description |
| :--- | :--- | --- |
| **Phase 1: Licensing**  | Run contract  | Based on traffic and storage, the Adobe account team works with you to transition from the [!DNL Dynamic Media Classic] license to renew on the [!DNL Dynamic Media] license. |
| **Phase 2: Preparation** | Validate feature usage  | Confirm that the features being used in [!DNL Dynamic Media Classic] are available in [!DNL Dynamic Media]. See the [Feature Comparison](/help/using/upgrade-feature-comparison.md) page. Key capabilities not yet available in [!DNL Dynamic Media] include the following:<br>&bull; Visual Configurator (Image Author, Image Render).<br>&bull; Image Templates (1:1 Templating).<br>&bull; eCatalogs.<br>If the above features are being used, the upgrade can still occur with the assumption that those features would be accessible by way of [!DNL Dynamic Media Classic]. |
|   | Identify assets | Find and ready assets and presets to be used for upgrade. |
| **Phase 3: Environment**  | Upgrade [!DNL Adobe Experience Manager] | All instances of [!DNL Adobe Experience Manager] must be updated to the latest version. |
|   | Setup [!DNL Dynamic Media] | Adobe Consulting or Partner configures [!DNL Dynamic Media] with your credentials. |
| **Phase 4: Upgrade** | Replicate assets | During the upgrade process, designated [!DNL Dynamic Media Classic] assets are replicated over to Dynamic Media. |
| **Phase 5: Administrative Setup**  | Setup users and permissions | Create users and grant appropriate permissions. |
|   | Setup video encoding profiles | Create video encoding profiles. |
|   | Setup Viewer Presets | Create Viewer Presets. |
|   | Set Image Presets | Setup Image Presets. |
| **Phase 6: Validation** | Validation | Verify use cases, assets, links, and APIs. |
