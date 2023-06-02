---
title: Upgrade FAQ
description: Frequently asked questions (FAQ) when you upgrade from [!DNL Adobe Dynamic Media Classic] desktop application to [!DNL Dynamic Media] on [!DNL Adobe Experience Manager] Assets.
feature: Dynamic Media Classic
role: Admin,User
exl-id: 5c2e2937-fe4f-4b64-bee8-9572ca84695b
---
# Frequently asking questions about upgrading from [!DNL Dynamic Media Classic] to [!DNL Dynamic Media] 

## General information

+++**What is [!DNL Dynamic Media] in [!DNL Adobe Experience Manager] Assets?**
[!DNL Dynamic Media] is the next generation evolution of [!DNL Adobe Dynamic Media Classic] (formerly Scene7) capabilities within [!DNL Experience Manager] Assets. The solution combines the power of asset management with rich media delivery. Capabilities include the following:

* Single user interface and platform for managing images and video.
* Innovative merchandising features.
* Adobe's robust and proven delivery platform.
* Seamless unification with [!DNL Experience Manager] Assets.

+++

+++**What are the key benefits of upgrading to [!DNL Dynamic Media]?**

*   Collaboration and shared file sync with [!DNL Adobe Creative Cloud] applications.
*   Enterprise-level digital asset management with robust metadata support, smart search, lightbox and collections, version control, and secure asset sharing for use by vendors, partners, and franchisees
Review and approval workflows for work in process assets.
*   Ease of adoption and use with new UI.
*   Create Shoppable/Interactive Media experiences using images and video that drive conversion and enrich user engagement and satisfaction.
*   Combine campaign assets with product information to streamline click to cart.
*   Easily create, adjust, brand, and deploy interactive viewers using the WYSIWYG Viewer Designer.
*   Deliver optimized rich media to [!DNL Experience Cloud] solutions.
*   Integration with [!DNL Experience Cloud] for advanced asset analytics, targeting, and asset reuse across marketing touch points. Those touchpoints include [!DNL Adobe Campaign] for email, [!DNL Adobe Social] for social channels, and [!DNL Experience Manager] Sites for responsive web and mobile apps.

+++

+++**Does [!DNL Dynamic Media] use the existing Adobe CDN (Content Delivery Network)?**
Yes, [!DNL Dynamic Media] uses Adobe's robust, top-tier delivery network.

* Top rich media vendor to Internet Retail 1000, nine years in a row.
* 24/7/265 support, 99.95% SLAs.
* Proven infrastructure serving over 800 clients world wide, 3.5 petabytes traffic per month and more than 500 million assets in management, 60% growth in traffic year over year.

+++

+++**What is [!DNL Dynamic Media Classic]? Is Adobe changing the name of Adobe Scene7?**
Adobe changed the name of Adobe Scene7 to [!DNL Dynamic Media Classic].

+++

## Upgrade process and tools

+++**Who is eligible for the upgrade program?**
Current [!DNL Dynamic Media Classic] (formerly Scene7) customers who also have [!DNL Experience Manager].

+++

+++**How do I start the upgrade process?**
Contact your Adobe Account Team representative or [email s7support@adobe.com](mailto:s7support@adobe.com) with the subject line `[!DNL Dynamic Media] Upgrade Program`.

+++

+++**How is the upgrade process handled?**
The upgrade is handled by AGS (Adobe Global Services) and treated as a service project. Adobe provides migration of the assets only. The customer, AGS, or Partner is responsible for all other upgrade aspects and steps. At a summary level, an upgrade plan contains the following:

* Provision company/user accounts.
* Replicate assets from [!DNL Dynamic Media Classic] (formerly Scene7) to the [!DNL Dynamic Media] component of [!DNL Experience Manager] Assets (provided by Adobe through an automated upgrade tool).
* Configure settings for imaging and video.
* Modify production processes and train users.

+++

+++**How long does the upgrade process take?**
The upgrade process time varies based on several factors, including but not limited to: the number of assets and size of assets. AGS or Partner manages the project timeline.

+++

+++**How do I check the status of my upgrade?**
The upgrade process time varies based on several factors, including but not limited to: the number of assets and size of assets. AGS or Partner manages the project timeline.

+++

+++**Are there any contract changes required to upgrade to [!DNL Dynamic Media]?**
The upgrade process time varies based on several factors, including but not limited to: the number of assets and size of assets. AGS or Partner manages the project timeline.

+++

+++**Is there a difference in licensing cost?**
Work with your Adobe Account Team representative for details regarding pricing.

+++

+++**Is there be any downtime associated with the upgrade process?**
No. [!DNL Dynamic Media Classic] continues to work uninterrupted during the upgrade process. After the upgrade is complete and content is validated, all users are working exclusively within the [!DNL Dynamic Media] component of [!DNL Experience Manager] Assets.

+++

+++**Are all the steps within the Upgrade Readiness Checklist required?**
No. The [readiness checklist](/help/upgrade-readiness.md) contains required and optional best practice steps.

+++

+++**Am I required to upgrade?**
No. Adobe continues to fully support and maintain [!DNL Dynamic Media Classic] (customer-requested bug fixes, security fixes, platform scalability, and reliability) now and into the future. 

You can upgrade when you are ready to take advantage of the new features offered by [!DNL Dynamic Media].

+++

+++**Can I continue to use [!DNL Dynamic Media Classic] (formerly Adobe Scene7) after I have upgraded to [!DNL Dynamic Media]?**
After you have upgraded to [!DNL Dynamic Media], you should only use Dynamic Media for imaging and video. You can continue to use [!DNL Dynamic Media Classic] only for features that are not yet available in [!DNL Dynamic Media] including the following:

* Visual configurator (image author, image render).
* Image templates.
* eCatalogs.

+++

+++**What tools does Adobe provide to automate the upgrade process?**
For the initial launch of the upgrade program, Adobe provides tools to automatically move assets from [!DNL Dynamic Media Classic] to [!DNL Dynamic Media] in [!DNL Experience Manager] Assets.

+++

+++**Do existing [!DNL Dynamic Media Classic] URLs, API integrations, and viewers continue to work during and after my upgrade?**
Yes. You can continue to use the [!DNL Dynamic Media Classic] (formerly Adobe Scene7) publishing and delivery infrastructure as-is in the [!DNL Dynamic Media] solution.

+++

+++**Do I have to update my production URLs?**
No. Adobe continues to use the [!DNL Dynamic Media Classic] publishing and delivery infrastructure as-is in the [!DNL Dynamic Media] solution. The benefit of this approach is that you do not have to change any production URLs on your web pages, therefore minimizing risk and effort of migration to [!DNL Dynamic Media].

+++

+++**Will I have to rewrite API integrations and other automation scripts?**
No. Adobe continues to use the [!DNL Dynamic Media Classic] publishing and delivery infrastructure as-is in the [!DNL Dynamic Media] solution. In addition, all assets are replicated over to [!DNL Dynamic Media Classic]. The benefit of this approach is that you do not have to rewrite any API-based integrations or automation scripts, therefore minimizing risk and effort of migration to [!DNL Dynamic Media].

+++

+++**Will I have to make changes or redevelop my custom viewers?**
No. Adobe continues to use the [!DNL Dynamic Media Classic] publishing and delivery infrastructure as-is in the [!DNL Dynamic Media] solution. The benefit of this approach is that you can continue to use your custom-built viewers, therefore minimizing risk and effort of migration to [!DNL Dynamic Media].
+++

+++**How do I migrate my settings (such as image presets, video encodings) to [!DNL Dynamic Media]?**
Presets and other settings must be recreated within [!DNL Dynamic Media]. As part of the service project, Adobe Global Services or Partner can assist.

+++

+++**How do I set up users and permissions (SSO or LDAP options)?**
Settings must be recreated within [!DNL Dynamic Media]. As part of the service project, AGS or Partner can assist. However, upgrading to [!DNL Dynamic Media] provides SSO/LDAP integration, making user management more efficient. In addition, [!DNL Dynamic Media] offers robust roles and privileges to control user access.

+++

+++**Can I still use FTP to batch/bulk upload assets?**
Yes. You do not need to modify your existing workflows for ingestion and can continue to schedule FTP-based uploads.

+++

+++**What resources are available for training new users?**
Training is available through ADLS (Adobe Digital Learning Services). [!DNL Dynamic Media] capabilities are covered in two courses: Manage and Deliver Digital Assets and Customize Digital Assets.

+++

+++**Is [!DNL Dynamic Media] available for all geographies?**
Yes. Adobe has datacenters in North America, Europe, and Asia-Pacific.

+++

+++**How long is [!DNL Dynamic Media Classic] going to exist as a stand-alone product?**
Adobe continues to fully support and maintain [!DNL Dynamic Media Classic] (customer-requested bug fixes, security fixes, platform scalability, and reliability) now and into the future.

+++

+++**How much storage comes with [!DNL Dynamic Media]?**
Sixty gigabytes of storage is included. You can purchase additional storage in blocks of 250 GB. Check your contract details to obtain your current storage allotment.

+++

+++**What metric is used to measure [!DNL Dynamic Media] usage?**
Page Views per Month (PVM). Page View means a single view of an email or web page of an internet site. It also includes application screen views, application screen states, mobile web pages, and social network pages. Page Views occur each time a web page is loaded or refreshed, an application is loaded, or when content renders or is shown through an opened or viewed email.

+++

+++**When is Personalized Media going to be available with [!DNL Dynamic Media]?**
Adobe is aggressively working to add Personalized Media features to [!DNL Dynamic Media]. More information on release timing is forthcoming.

+++

+++**How are assets validated during the upgrade? Am I required to do manual validation?**
Adobe performs an automated validation on all assets that are moved over to [!DNL Dynamic Media]. A general manual validation of key sites, pages, and experiences powered by [!DNL Dynamic Media] is recommended.

+++

+++**Is there an SLA for [!DNL Dynamic Media]?**
Yes. Contact your Adobe Account Team representative for details.

+++

+++**Can I use my own CDN (Content Delivery Network) with [!DNL Dynamic Media]?**
Yes. You can use your own CDN with [!DNL Dynamic Media].

+++

+++**Does [!DNL Dynamic Media] have the features I need to upgrade? What features are available with [!DNL Dynamic Media] on [!DNL Experience Manager] Assets?**
See the [Feature Comparison](/help/upgrade-feature-comparison.md) page to learn more.

+++

+++**What features are still only available in [!DNL Dynamic Media Classic]? Can I still upgrade?**
Customers who require the following can continue to have access to [!DNL Dynamic Media Classic] powered features:

* Visual configurator (image author, image render).
* Image templates.
* eCatalogs.

See also the [Feature Comparison](/help/upgrade-feature-comparison.md) page to learn more.

+++

+++**What is happening with [!DNL Dynamic Media Classic] Media Portal solution?**
[!DNL Experience Manager] Brand Portal is the replacement offering for [!DNL Dynamic Media Classic] Media Portal.

+++

## Consulting services

+++**Can I complete the upgrade process on my own?**
No. Work with your Adobe representative and AGS to scope your upgrade.

+++

+++**What does the services project look like?**
Adobe works with you to plan the project. Adobe is responsible for provisioning and configuring accounts, replication of assets, testing, and validation.

Customers are primarily responsible for change management including training users, editing production processes, and rolling out new features.

+++

## Support and training

+++**How do I get support?**
24/7/365 Client Care support is available. [Contact technical support](https://experienceleague.adobe.com/?support-solution=General#support).

Phone: 1-800-898-9743 (US) | +44 (0)20 35641782 (UK) | +81-3-6743-9632 (Japan)

+++

+++**Where can I learn more about paid training options?**
See [Adobe Digital Learning Services](https://learning.adobe.com).

For custom or individual training, please contact your Adobe Account Team representative.

+++

## Additional resources                                  
 
+++**Where 
can I learn more about [!DNL Dynamic Media] and its features?**
See the [[!DNL Dynamic Media] microsite](https://landing.adobe.com/en/na/dynamic-media/ctir-2755/solutions.html) to learn more about [!DNL Dynamic Media].

+++
