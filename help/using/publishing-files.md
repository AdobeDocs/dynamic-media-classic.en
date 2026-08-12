---
title: Publish Files
description: Learn how to publish your assets to Dynamic Media Image Servers.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/upload_and_publish_assets
feature: Dynamic Media Classic,Asset Management
role: User
exl-id: 91b73a09-c5b5-4001-b36f-6bebe65717ff
topic: Content Management
level: Intermediate
autotag-review: '2026-05-13T20:08:38.271Z'
TQID: 'https://experienceleague.adobe.com/-eX-BNe5fu-v-hnD9F2qkBkpPZYx3TAvN4Lisgz3mHk'
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
# Publish files{#publishing-files}

You publish your assets to Dynamic Media Image Servers. You can publish assets on a one-time basis or arrange for Adobe Dynamic Media Classic to publish assets on a recurring schedule. After your assets are published, they are available to you for delivery. You can copy the URL calls from Adobe Dynamic Media Classic and add them to your website or application.

Adobe Dynamic Media Classic now supports the delivery of all images and video over HTTP/2. That is, a published URL or Embed Code for the image or video is available to be integrated with any application that accepts a hosted asset. That published asset uses the HTTP/2 protocol to deliver it. This method of delivery improves the way browsers and servers communicate, resulting in improved response and load times for all your Adobe Dynamic Media Classic assets. See [HTTP2 Delivery of Content FAQ](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/dynamic/http2).

## Publish after uploading {#publish-after-uploading}

Assets are either in a published or unpublished state. By default, any assets that you upload into Adobe Dynamic Media Classic are automatically marked for publishing.

For more information, see the [Instant Publish Notice PDF](/help/using/assets/rendering-instant-publish-notification.pdf).

Use these techniques to mark assets for publishing:

* **[!UICONTROL Publish After Uploading]**: On the Upload page, near the bottom, select **[!UICONTROL Publish After Uploading]**. The default is a selected state.

* **[!UICONTROL Publish After Uploading]**: In the Job Options dialog box, select **[!UICONTROL Publish After Uploading]**. The default is a selected state.

Some dependent assets are automatically marked for publishing when their parent assets are marked for publishing. This table lists child assets that are marked for publishing automatically.

| Parent (group) item | Child (member) items |
| --- | --- |
| Image Sets | Images within the set. |
| Swatch Sets | Swatches within the set. |
| Spin Sets | Images within the set. |
| Templates | Template files, pages, and images. |

Derived images are also automatically marked for publishing when their parent images are published. Derived images include images you adjusted with image-editing options. You can see these derived images in Detail View under Built & Derivatives.

## Create a publish job {#creating-a-publish-job}

Create a publish job to publish assets you have uploaded to Adobe Dynamic Media Classic servers. Use this for assets that you do not want published automatically. You can perform a one-time publishing job or schedule jobs to recur regularly. Adobe Dynamic Media Classic offers advanced publishing options for publishing to specific servers and options for republishing assets that have already been published.

**To create a publishing job:**

1. On the Global Navigation bar, select **[!UICONTROL Publish]**.
1. In the Publishing dialog box, choose whether you want a one-time or recurring publishing job.

   See [Create a one-time publishing job](publishing-files.md#creating_a_one_time_publish_job) and [Create a recurring publishing job](publishing-files.md#creating_a_recurring_publish_job).

1. Enter a job name.
1. Optionally, display the Advanced options and choose these options.

   See [Advanced publish options](publishing-files.md#advanced_publish_options).

1. Select **[!UICONTROL Submit Publish]**.

Adobe Dynamic Media Classic tracks publish jobs on the Jobs page. You can review publish jobs on that page.

>[!NOTE]
>
>Assets you republished (you have published them before) do not appear immediately on your website because of the web-caching mechanism on the content delivery network (CDN). See [Republished assets and CDN delays](publishing-files.md#republished_assets_and_cdn_delays).

### Create a one-time publish job {#creating-a-one-time-publish-job}

Create a one-time publishing job by selecting the **[!UICONTROL One-Time]** option on the Publishing page.

If you want the publishing job to occur later, in the Publishing page, select **[!UICONTROL One-Time]**. From the drop-down list, select **[!UICONTROL Schedule For Later]**. Use the Calendar and the Time slider to select a day and time to run the publish job.

### Create a recurring publishing job {#creating-a-recurring-publish-job}

Create a recurring publishing job by selecting **[!UICONTROL Recurring]** on the Publishing page.

Then choose a Repeat option of **[!UICONTROL Daily]**, **[!UICONTROL Weekly]**, **[!UICONTROL Monthly]**, or **[!UICONTROL Custom]**, then specify when you want the publishing job to recur. Adobe Dynamic Media Classic presents calendar tools for scheduling the recurring publishing job. You can select the **[!UICONTROL Custom]** option and enter a rule in the Rule text field to describe a custom job interval.

See [Create a custom upload or publish job time interval](checking-job-files.md#creating_a_custom_upload_or_publish_job_time_interval).

>[!NOTE]
>
>Recurring publish (and upload) jobs are listed on the Jobs page. You edit or delete a scheduled job by going to the Scheduled tab of the Jobs page.

### Advanced publish options {#advanced-publish-options}

You can display the Advanced options on the Publishing page and choose these options for handling a publishing job:

* **[!UICONTROL Publish To]**: To publish assets only to a specific server, choose a server type.

* **[!UICONTROL Publish]**: By default, Adobe Dynamic Media Classic publishes only assets that are new and have not been published before (the New Since Last Publish option). However, you can select **[!UICONTROL Full Publish]** so you can also publish assets that have been updated or changed since they were last published. Select **[!UICONTROL Full w/ Search Data]** if you are publishing an eCatalog and you want readers to be able to search it by keyword.

* **[!UICONTROL Run Job As]**: Choose a user name from the list. You can sort jobs by user name on the Jobs page. By choosing a name, you associate a publishing job with a user.

**[!UICONTROL HTTP Notification]**: Enter a URL to trigger subsequent publish jobs.

See [Use an upload or publish job as a trigger](checking-job-files.md#using_an_upload_or_publish_job_as_a_trigger).)

## Cancel a publishing job {#canceling-a-publish-job}

You can cancel a publishing job that is in progress. Moreover, if you are an administrator, you can cancel an in-progress publishing job from the company Jobs page.

To cancel a publishing job, go to the Jobs page and select **[!UICONTROL Cancel]**. On the Scheduled tab of the Jobs page, you can pause or resume a job by deselecting or selecting the check box in the job's Active column.

>[!NOTE]
>
>After you cancel a publish job, its status changes to "stopping" until the job reaches a point where it can stop safely. Stopping a publishing job can take some time if the job is in the process of getting data from the database.

## Publish assets manually {#manually-publishing-assets}

You can publish individual assets manually instead of creating a publishing job. When you publish sets, the parent and all children within that set get published.

A gray, round icon with a line through it (unpublished state) to the left of the asset's name indicates unpublished assets in the user interface. After an asset is published, the icon turns green and has a white check mark in the center (published state).

**To publish assets manually:**

1. Do one of the following:

    * In the Grid View, List View, or Details View, use standard file selection methods to select one or more unpublished assets.

      On the Global Navigation bar, go to **[!UICONTROL File]** > **[!UICONTROL Publish]**.

    * In the Grid View, List View, or Details View, select the gray, round icon with a line through it, to the left of the asset's name.

## Unpublish assets manually {#manually-unpublishing-assets}

You can unpublish individual assets manually. When you unpublish sets, the parent goes into an unpublished state. However, the members (or "children") within that set are not affected; instead, they each retain their existing published or unpublished state.

A round, green icon with a white check mark in the center (published state) to the left of the asset's name indicates published assets in the user interface. After an asset is unpublished, the icon turns gray with a line through it (unpublished state).

**To unpublish assets manually:**

1. Do one of the following:

    * In the Grid View, List View, or Details View, select one or more published assets.

      On the Global Navigation bar, go to **[!UICONTROL File]** > **[!UICONTROL Unpublish]**.

    * In the Grid View, List View, or Details View, select the round, green check mark icon to the left of the asset's name.

## Get an asset's publish history {#getting-an-asset-s-publish-history}

The last date that an asset was published is shown in Detail View at the top of the panel. You can get more details about the publishing history by opening the History & Published Servers panel in Detail View. From there, you can see when the asset was published and to which servers it was published.

## Republished assets and CDN delays {#republished-assets-and-cdn-delays}

Adobe Dynamic Media Classic assets are distributed on the content delivery network (CDN). CDN is a system of computer servers networked together. They work together to deliver content, especially large media content, to end users. In the CDN system, Web content is stored in Web caches across the Internet (called the edge cache network). Web content is delivered from the Web caches to end users to provide faster deliveries.

The first time someone downloads a Web page, the assets are delivered to a CDN Web cache server. This server stores them so that the next time someone in the same area accesses the Web page, the same cached content is delivered faster. The content is delivered faster because it is located closer to the end user. CDN enables faster Web page displays. It decreases bandwidth demands on the central server because content is delivered from the edge cache network, not from a central server in every instance.

Newly published Adobe Dynamic Media Classic content is available immediately to the end user and quickly populates the edge cache network. However, newly republished content—that is, images that have the same names as images previously published to an Image Server—are not updated on the CDN for up to ten hours. Instead, end users see what is in a Web cache on the CDN network. For this reason, your Adobe Dynamic Media Classic republished assets do not appear to end users for ten hours.

If you want your newly republished image assets to be available sooner than the ten-hour delay, you can flush Web caches on CDN. Flushing these Web caches removes old content from CDN Web caches and replaces it with your most recently published assets.

To flush the cache, on the Global Navigation bar, go to **[!UICONTROL File]** > **[!UICONTROL Invalidate CDN]**. All selected files are removed from the cache. If there are no publishable assets, or if you are not a company admin, the Remove from CDN option is not available.

>[!MORELIKETHIS]
>
>* [Check job files](checking-job-files.md)
>* [Edit, delete, pause, and resume recurring jobs](checking-job-files.md#editing-deleting-pausing-and-resuming-recurring-jobs)
