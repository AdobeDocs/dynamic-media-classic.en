---
title: Adobe Dynamic Media Classic Desktop app
description: Adobe Dynamic Media Classic users can now experience a complete refresh of the user interface.
contentOwner: rbrough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
feature: Dynamic Media Classic
role: Admin,User
exl-id: d61ea80a-a98e-43e6-9e2e-4389962134f1
topic: Administration
level: Intermediate
---
# Adobe Dynamic Media Classic Desktop app: Now available {#new-ui-2020}

See the [Adobe Dynamic Media Classic desktop app](/help/using/dynamic-media-classic-desktop-app.md) to review system requirements, download and install the new app, and then sign in to it.

## _Last revision June 30, 2020_

Adobe Dynamic Media Classic users now have access to a new sign-in that no longer relies on Adobe Flash technology in the browser.

## Frequently Asked Questions

+++**_When browsers stop supporting Adobe Flash on December 31, 2020, will there be any impact to Adobe Dynamic Media Classic (formerly Scene7)?_**
Adobe Flash Player was a Web browser plug-in that allowed Web browsers to use content developed on the Adobe Flash Platform. The Web user interface of Adobe Dynamic Media Classic (currently labeled [!DNL Scene7 Publishing System] or [!DNL SPS] in the product) required the Adobe Flash Player. When Adobe Flash is deprecated December 31, 2020, Adobe Dynamic Media Classic customers will no longer be able to log into the Web user interface. Because of this change, Adobe has provided customers with a desktop app that replaces the browser experience.
+++

+++**_How do I access the new desktop app?_**
The new desktop app is available as a `.dmg` installer for macOS or as an `.exe` installer for Windows&reg;.

See the [Adobe Dynamic Media Classic desktop app](/help/using/dynamic-media-classic-desktop-app.md) to review system requirements, download, and install the new app, and then sign in to it.
+++

<!-- NEWSLETTER IS DEAD The download links are also available by way of the [Adobe Dynamic Media Classic newsletter subscription page.](https://www.adobe.com/subscription/dynamic-media-newsletter.html) -->

+++**_How does the new desktop app work?_**
After downloading, installing, and launching the desktop app, you are presented with a refreshed sign-in. By entering your existing user name and password and selecting the appropriate server based on your region, you can sign in to Adobe Dynamic Media Classic. The overall experience is the same as the familiar Web browser version that you are used to. From the desktop app, you can access the Adobe Dynamic Media Classic Production and Staging environments. You can also access Media Portal if you are credentialed for this capability.

>[!IMPORTANT]
>
>Only one instance of the desktop app can be installed *and* active at a time on a given computer. However, there is no restriction on the number of installations you can have across computers.

+++

+++**_What if I am using the Adobe Dynamic Media Classic APIs to access the product and do not sign in through the Web user interface?_**
There are no changes to the underlying APIs for Adobe Dynamic Media Classic.
+++

+++**_Does this new desktop app experience require any migrations or changes to third-party integrations?_**
No. Adobe Dynamic Media Classic customers do not have to migrate or change any third-party integrations to use the new desktop app.
+++

+++**_Does this change affect my automation scripts?_**
No. There is no impact to automation scripts. The new desktop app acts and behaves in a way that is similar to the browser-based experience that you are already familiar with.
+++

+++**_Will the new Adobe Dynamic Media Classic desktop app work on Macs and personal computers?_**
Yes. The new desktop app is a cross-platform solution and works on Macs and PCs. Linux&reg; is *not* supported.
+++

+++**_My company has strict security requirements. How does the new Adobe Dynamic Media Classic desktop app handle these requirements?_**
Adobe is committed to ensuring its products meet the security requirements of its customers. The new Adobe Dynamic Media Classic desktop app continues to provide customers with a highly secure experience that conforms to all Adobe security standards.
+++

+++**_My company does not let me install software and apps onto my computer. How do you recommend I get access to the new desktop app?_**
Some companies do not let you download and install software and apps onto your system without approval. In such cases, work with your IT team early to gain permission to access the new Adobe Dynamic Media Classic desktop app. Remember that after December 31, 2020 the browser version will be deprecated. It is important that you avoid waiting until the last minute to download the new desktop app.
+++

+++**_Can multiple instances of the new desktop app be open at the same time?_**
No. The AIR technology on which the new Adobe Dynamic Media Classic desktop app is built restricts a user from having multiple instances of the app open at a given time.
+++

+++**_Are there any restrictions on the number of files that can be uploaded to Adobe Dynamic Media Classic by way of a local computer?_**
When using the new Adobe Dynamic Media Classic desktop app on Windows&reg;, you can upload a maximum of 150 files at a time using the **[!UICONTROL Upload]** dialog box. This limitation was already addressed before the end of 2020. There are *no* upload restrictions on the macOS Platform.
+++

+++**_Does the new Adobe Dynamic Media Classic desktop app require a new SKU? Is there a license cost involved?_**
No to both questions. No SKU or license change is required to use the new Adobe Dynamic Media Classic desktop app.
+++

+++**_How are upgrades to Adobe Dynamic Media Classic desktop app enabled?_**
Following the release of the Adobe Dynamic Media Classic desktop app on June 30, 2020, if Adobe releases a new version, customers are required to download and install the new version (replace the existing app in **[!UICONTROL Applications]**). You are notified of the new release through your Adobe Account Team and an in-app upgrade notification mechanism that notifies users of an upgrade.
+++

+++**_How do I get help for any issues that I have with the Adobe Dynamic Media Classic desktop app?_**
Contact Adobe Support with any issues that you have while using the app.
+++

+++**_I want to make sure I'm optimizing my rich media strategy. How can I learn even more about Adobe Dynamic Media Classic?_** 
Adobe Dynamic Media Classic is a powerful, feature-rich solution designed to enhance your rich media strategies. To ensure you take advantage of all the capabilities, be sure you explore these practical resources:

* [Adobe Dynamic Media Classic Best Practices Tutorial](https://experienceleague.adobe.com/en/docs/experience-manager-learn/dynamic-media-classic-tutorial/overview)
* [Adobe Blog Posts](https://blog.adobe.com/)<!-- (https://blog.adobe.com/tag/dynamic-media/) -->
* [Adobe Dynamic Media Newsletter Archives](https://experienceleague.adobe.com/en/docs/dynamic-media-classic/using/dynamic-media-newsletter)
+++

<!-- HIDDEN AUGUST 2, 2021 BECAUSE THE NEWSLETTER WAS DISCONTINUED Plus, [subscribe to the Dynamic Media newsletter](https://www.adobe.com/subscription/dynamic-media-newsletter.html) to stay current on the latest news, information, training opportunities, powerful features available to you such as [Smart Imaging](https://experienceleague.adobe.com/docs/experience-manager-65/assets/dynamic/imaging-faq.html), and the complementary audit program. -->

+++**_I'm interested in learning more about upgrading to Adobe Dynamic Media with Adobe Experience Manager Assets. Where can I find more information?_**
To learn more about the benefits of upgrading to the next generation of rich media authoring, publishing, and dynamic delivery, visit the [Adobe Dynamic Media portal for upgrading](/help/using/upgrade.md).
+++

### Add multiple captions and audio tracks to your video {#add-msma}

Before you add multiple caption and audio tracks to your video, be sure you already have the following in-place:

* Dynamic Media is set up in an AEM environment.
* A [Dynamic Media Video profile is applied to the folder where your videos are ingested](/help/assets/dynamic-media/video-profiles.md#applying-a-video-profile-to-folders).
* [Multi-caption/audio tracks and AI-generated captions are enabled on your Dynamic Media account](#enable-dash).

Added captions are supported with WebVTT and Adobe VTT formats. And, added audio track files are supported with MP3 format.

>[!IMPORTANT]
>
>For videos uploaded *before* enabling multiple caption/audio track support or AI-generated captions on your Dynamic Media account, [you need to reprocess them](/help/assets/dynamic-media/about-image-video-profiles.md#reprocessing-assets). This reprocessing step ensures that these videos can use the multiple caption/audio track and AI-generated caption features. After reprocessing, the video URLs continue to function and play as usual.

**To add multiple captions and audio tracks to your video:**

1. [Upload your primary video to a folder](/help/assets/manage-video-assets.md#upload-and-preview-video-assets) that already has a video profile assigned to it. You do not need to publish the video until later in these steps.
1. Navigate to the uploaded video asset that you want to add multiple caption and audio tracks.
1. In asset selection mode, either from the List View or the Card View, select the video asset.
1. On the toolbar, select the Properties icon (a circle with an "i" in it).
![Selected video asset with checkmark over video thumbnail image and View Properties highlighted on the toolbar.](/help/assets/dynamic-media/assets/msma-selectedasset-propertiesbutton.png)*Selected video asset in Card view.*
1. On the video's Properties page, select the **[!UICONTROL Captions & Audio Tracks]** tab.

   >[!TIP]
   >If you do not see the **[!UICONTROL Captions & Audio Tracks]** tab, it means either one of two things:
   >
   >* The folder in which the selected video resides does not have a video profile assigned to it. In which case, see [Apply a video profile to the folder](/help/assets/dynamic-media/video-profiles.md#applying-video-profiles-to-specific-folders)
   >* Or, the video must be reprocessed by Dynamic Media. In which case, see [Reprocess Dynamic Media assets in a folder](/help/assets/dynamic-media/about-image-video-profiles.md#reprocessing-assets).
   >
   >When you have completed either one of the above tasks, return to these steps.
  
   ![Captions and Audio Tracks tab on the Properties page.](/help/assets/dynamic-media/assets/msma-audiotracks2.png)*Captions and Audio Tracks tab on the video's Properties page.*

1. To add one or more audio tracks to a video, do the following:
   1. Select **[!UICONTROL Upload Audio Tracks]**.
   1. Navigate to, and select, one or more .mp3 files and open them.
   1. For audio tracks to be visible in the **[!UICONTROL Select audio or caption]** pop-up list on the media player, you *must* add required details about *each* audio track file that you added. Select the pencil icon to the right of an audio track file name. In the **Edit Audio Track** dialog box, enter the following required details:
    
      | Audio Track metadata | Description |
      |--- |--- |
      | Filename | The default filename is derived from the original filename. The filename can be changed only while uploading and cannot be changed later. Filename character requirements are the same as for AEM Assets.<br>The same filename cannot be used for additional audio track files or caption files. |
      | Language | Select the correct language of the audio track. |
      | Type | Select the type of audio track that you are using.<br>**Original** &ndash; The audio track originally attached to the video and represented as `[Original]` in the label with `English` language selected by default. While **[!UICONTROL Label]** and **[!UICONTROL Language]** can be changed in the **[!UICONTROL Edit Audio Track]** dialog box, it defaults to the original values if the primary video is reprocessed.<br>**Standard** &ndash; An add-on audio track for a language other than the original.<br>**Audio description** &ndash; An audio track that also includes a descriptive narration of non-verbal actions and gestures in the video, making content more accessible for individuals who are visually impaired. |
      | Label | The text that is displayed as the audio track's name in the **[!UICONTROL Select audio or caption]** pop-up list in the media player. The label is what a customer sees that corresponds to an audio track. For example, `English [Original]`. The label of audio attached to a video is set to `[Original]` by default. |

      You can change or edit this audio track metadata later, if necessary. When the video is published, these details are reflected on public URLs in published videos.

   1. Near the upper-right corner the page, in the **[!UICONTROL Save & Close]** drop-down, click **[!UICONTROL Save]**.
   1. Do one of the following:
        * Repeat this process for each audio track file that you upload.
        * Continue to the next step to add captions to a video.

1. To add one or more caption files to a video, choose which one of the following use cases best fits your scenario:
   
   |  | Use case |
   | --- | --- |
   | **Option 1** | I have my own pre-existing caption files that are in the languages that I want to use.<br>See **Option 1** in step 8 below. |
   | **Option 2** | I want AI to generate my caption files in multiple languages.<br>See **Option 2** in step 8 below. |
   | **Option 3** | Text in a caption file (.vtt) needs to be corrected, reuploaded to replace the old .vtt file, then have AI translate the corrected file.<br>See **Option 3** in step 8 below. |


    +++**Option 1:** *I have my own pre-existing caption files that are in the languages that I want to use.*

    1. Near the upper-right side of the page, click **[!UICONTROL Create Caption]** > **[!UICONTROL Upload files]**.
    1. Navigate to, and select, one or more of your pre-existing .vtt (Video Text Tracks) files and open them.
    1. For captions to be visible on the media player, you *must* add the required details about *each* caption file that you upload. Select the pencil icon to the right of a caption file name. In the **Edit Caption** dialog box, enter the following required details about the file:
    
        | Caption metadata | Description |
        |--- |--- |
        | Filename | The default filename is derived from the original filename. The filename can be changed only while uploading and cannot be changed later. Filename character requirements are the same as for AEM Assets.<br>The same filename cannot be used for additional caption files and audio track files. |
        | Language | Select the language of the caption. After a caption file is processed, this language field becomes uneditable (dimmed) |
        | Type | Select the type of caption that you are using.<br>**Subtitle** &ndash; The caption text displayed with the video that translates or transcribes the dialogue.<br>**Caption** &ndash; The caption text also includes background noises, speaker differentiation, and other relevant information, along with the translation or transcription of the dialogue, making the content more accessible for individuals who are deaf or hard of hearing. |
        | Label | The text that is displayed for the caption's name in the **[!UICONTROL Select audio or caption]** pop-up list in the media player. The label is what a customer sees that corresponds to a subtitle or caption track. For example, `English (CC)`. |

        You can change or edit caption metadata later, if necessary. When the video is published, these details are reflected on public URLs in published videos.

    1. Near the upper-right corner the page, in the **[!UICONTROL Save & Close]** drop-down, click **[!UICONTROL Save]**. The files are uploaded and metadata processing begins, as seen in the **Status** column of the interface.

        >[!NOTE]
        >
        >Based on the caching settings of your instance, the metadata processing can take several minutes before it is reflected in preview and in published URLs.

    1. If you selected **[!UICONTROL Save & Close]** in the previous step, instead of selecting **[!UICONTROL Save]**, you can still view the processing status of the uploaded files. See [View the lifecycle status of uploaded caption and audio track files](#lifecycle-status-video).
    1. Continue to step 9.

    +++

    +++**Option 2:** *I want AI to generate my caption files in multiple languages.*

    1. Near the upper-right corner of the page, click **[!UICONTROL Create Caption]** > **[!UICONTROL Convert audio tracks]**.
    1. In the **Convert Audio Tracks** dialog box, set the following options:
    
        | Option | Description |
        |--- |--- |
        | Audio track to convert | In the drop-down list, choose the uploaded audio track file from which you want AI to generate captions.  |
        | Output languages | In the drop-down list, select one or more languages in which you want the caption file to appear.<br>To remove a selected language, click **X**.<br>During video playback, the list of languages appears in the media player in the order that you select them here. |

    1. Click **[!UICONTROL Done]**.
    1. Near the upper-right corner the page, in the **[!UICONTROL Save & Close]** drop-down, click **[!UICONTROL Save]**. One or more caption files are created and processing begins, as seen in the **Status** column of the interface. See also [View the lifecycle status of uploaded caption and audio track files](#lifecycle-status-video).

        >[!NOTE]
        >
        >Based on the caching settings of your instance, the metadata processing can take several minutes before it is reflected in preview and in published URLs.

    1. (Optional) Select the pencil icon to the right of a caption file name. In the **Edit Caption** dialog box, you can edit the following details about the file:

        | Caption metadata | Description |
        | --- | --- |
        | Type | Select the type of caption that you are using.<br>**Subtitle** &ndash; The caption text displayed with the video that translates or transcribes the dialogue.<br>**Caption** &ndash; The caption text also includes background noises, speaker differentiation, and other relevant information, along with the translation or transcription of the dialogue, making the content more accessible for individuals who are deaf or hard of hearing. |
        | Label | The text that is displayed for the caption's name in the **[!UICONTROL Select audio or caption]** pop-up list in the media player. The label is what a customer sees that corresponds to a subtitle or caption track. For example, `English (CC)`. |

        You can change or edit certain caption metadata later, if necessary. When the video is published, these metadata details are reflected on public URLs in published videos.
    1. Continue to step 9.

    +++

    +++**Option 3:** *Text in a caption file (.vtt) needs to be corrected, reuploaded to replace the old .vtt file, then have AI translate the corrected file.*

    1. Click **[!UICONTROL Create Caption]** > **[!UICONTROL Translate captions]**.
    1. In the **Translate caption** dialog box, set the following options:

        | Option | Description |
        |--- |--- |
        | Caption to translate | In the drop-down list, choose a caption file from which you want AI to translate the caption text. |
        | Output languages | In the drop-down list, select one or more languages in which you want the caption file to appear.<br>To remove a selected language, click **X**.<br>During video playback, the list of languages appears in the media player in the order that you select them here. |

    1. Click **[!UICONTROL Done]**.
    1. Near the upper-right corner the page, in the **[!UICONTROL Save & Close]** drop-down, click **[!UICONTROL Save]**. One or more caption files are created and processing begins, as seen in the **Status** column of the interface. See also [View the lifecycle status of uploaded caption and audio track files](#lifecycle-status-video).

        >[!NOTE]
        >
        >Based on the caching settings of your instance, the metadata processing can take several minutes before it is reflected in preview and in published URLs.

    1. (Optional) Select the pencil icon to the right of a caption file name. In the **Edit Caption** dialog box, you can edit the following details about the file:

        | Caption metadata | Description |
        | --- | --- |
        | Type | Select the type of caption that you are using.<br>**Subtitle** &ndash; The caption text displayed with the video that translates or transcribes the dialogue.<br>**Caption** &ndash; The caption text also includes background noises, speaker differentiation, and other relevant information, along with the translation or transcription of the dialogue, making the content more accessible for individuals who are deaf or hard of hearing. |
        | Label | The text that is displayed for the caption's name in the **[!UICONTROL Select audio or caption]** pop-up list in the media player. The label is what a customer sees that corresponds to a subtitle or caption track. For example, `English (CC)`. |

        You can change or edit certain caption metadata later, if necessary. When the video is published, these metadata details are reflected on public URLs in published videos.

    1. Continue to step 9.

    +++

1. (Optional) Preview the video before publishing to ensure the captions and audio work as expected. See [Preview a video that has multiple captions and audio tracks](#preview-video-audio-subtitle)

>[!MORELIKETHIS]
>
>* [Sign in to and out of the Adobe Dynamic Media Classic desktop application](/help/using/signing-out.md)
>* [Download and install the Adobe Dynamic Media Classic desktop application](/help/using/dynamic-media-classic-desktop-app.md)

<!-- SAVE: OLD LINK TO BEST PRACTICES GUIDE IN PDF https://www.adobe.com/content/dam/www/us/en/marketing/experience-manager-assets/dynamic-media/adobe-dynamic-media-classic-best-practices-guide.pdf -->