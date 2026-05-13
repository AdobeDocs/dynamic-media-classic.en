---
title: Push offer sets to Adobe Target Standard/Premium
description: Learn how to push offer sets to Adobe Target Standard/Premium from Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/target_integration
feature: Dynamic Media Classic
role: Developer,Admin,User
exl-id: 778fd54b-a9e5-40c5-aff1-a156a5c15923
topic: Integrations, Development
level: Experienced
autotag-review: '2026-05-13T19:55:22.850Z'
TQID: 'https://experienceleague.adobe.com/8j9sRn1zhAhgj-wMV6hYix1F9aARZjDUiFZofcVVcBw'
product_v2:
  - id: beaff0dd-a904-4c6b-8290-b527cd877d75
    internal-label: Dynamic Media Classic
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
---
# Push offer sets to Adobe Target Standard/Premium {#pushing-offer-sets-to-target}

After you create or edit an offer set, push it to Adobe Target Standard/Premium by following these steps:

1. In the Test&Target Offer Set screen, select **[!UICONTROL Push Offers]**. 
1. Enter your client code and login credentials.
1. Select **[!UICONTROL Login]**.

During the transfer to Adobe Target Standard/Premium, the prefix `S7_` is attached automatically to the start of offer names. This prefix is attached to ensure that you can easily find Adobe Dynamic Media Classic offers in the Test&Target offer list. For example, the offer appears as `S7_<name of offer set>_<offer name>`.

Adobe Dynamic Media Classic pushes into Adobe Target Standard/Premium widget offers. You can use Widget offers to host your own offered content on Adobe Target Standard/Premium. Widget offers are similar to a standard offer hosted by Adobe Target Standard/Prermium. They allow Adobe Target Standard/Premium to deploy offer content that is stored on your server, allowing for more sophisticated and dynamic usage. Widget offers can retrieve content from a URL, caching and serving that content for approximately two hours. Widget offers provide some dynamic content generation capabilities that other offers outside Adobe Target Standard/Preimium do not. If the mbox serving the offer contains mbox parameters, such as `mboxProductID` and `mbox.offerId`, the `productId=[PRODUCT_ID]`and `offerID=[OFFERID]` URL parameters are appended to the requested URL. These parameters are used by a service available at the Widget offer URL to return content outside Adobe Target Standard/Premium that uses product or order information from your mboxes. The Widget offer is also accessible through the API so you can programmatically create offers outside Adobe Target Standard/Premium.
