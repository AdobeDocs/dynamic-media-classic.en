---
title: "Quick Start: Video in Adobe Dynamic Media Classic"
description: An introduction and Quick Start to Adobe Dynamic Media Classic Video to help you get up and running quickly.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/video
feature: Dynamic Media Classic,Viewers,Video
role: User
exl-id: 1157400c-b33a-422e-848c-258660ddc748
topic: Content Management
level: Beginner
---
# Quick Start: Video in Adobe Dynamic Media Classic{#quick-start-video}

 Adobe Dynamic Media Classic Video is an end-to-end solution that makes it easy to publish high-quality Adaptive Video for streaming across multiple screens, including desktop, iOS, Android&trade;, BlackBerry&reg;, and Windows&reg; mobile devices. An Adaptive Video Set groups versions of the same video that are encoded at different bit rates and formats such as 400 kbps, 800 kbps, and 1000 kbps. The desktop computer or mobile device detects the available bandwidth.

For example, on an iOS mobile device, it detects a bandwidth such as 3G, 4G, or Wi-Fi. Then, it automatically selects the right encoded video from among the various video bit rates within the Adaptive Video Set. The video is streamed to desktops, mobile devices, or tablets.

In addition, video quality is dynamically switched automatically if network conditions change on the desktop or on the mobile device. Also, if a customer enters full-screen mode on a desktop, the Adaptive Video Set responds by using a better resolution, improving the customer's viewing experience. Using Adaptive Video Sets provides you with the best possible playback. It is best for customers playing Adobe Dynamic Media Classic Video on multiple screens and devices.

The logic that a video player uses to determine which encoded video to play or to select during playback is based on the following algorithm:

1. The video player loads the initial video fragment based on the bit rate that is closest to the value that is set for "initial bitrate" in the player itself.
1. Video player switches based on changes to the bandwidth speed using the following criteria:

    1. The player picks the highest bandwidth stream below or equal to the estimated bandwidth. 
    1. Player considers only 80% of the available bandwidth. However, if it is switching up, it is more conservative at only 70% to avoid overestimating and immediately switch back.

See the algorithm's logic at [https://android.googlesource.com/platform/frameworks/av/+/master/media/libstagefright/httplive/LiveSession.cpp](https://android.googlesource.com/platform/frameworks/av/+/master/media/libstagefright/httplive/LiveSession.cpp) for technical information about it.

For managing single videos, and Adaptive Video Sets, Adobe Dynamic Media Classic supports the following:

* Uploading video from numerous supported video formats. And, uploading audio formats and encoding video to MP4 H.264 format for playback across multiple screens. You can use predefined Adobe Dynamic Media Classic Adaptive Video presets, single video encoding presets, or customize your own encoding to control the quality and size of the video.

See [Activate or deactivate adaptive video presets](/help/using/application-setup.md#activating-or-deactivating-adaptive-video-presets)

See also [Video presets](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/549_video-presets_converted%20renamed_Done-AVS) training video.

  When an Adaptive Video Set is generated, it includes MP4 videos.

  >[!NOTE]
  >
  >Primary/source videos and any other source format video are *not* added to an Adaptive Video Set. 

* Video captioning in the Univeral_HTML5_Video, Universal_HTML5_MixedMedia_dark, and Universal_HTML5_MixedMedia_light viewers and video chapter navigation in the Univeral_HTML5_Video, Universal_HTML5_MixedMedia_dark, and Universal_HTML5_MixedMedia_light viewers.

  See [Add captions to a video](adding-captions-video.md).

  See [Add chapter markers to a video](adding-chapter-markers-video.md).

* Organize, browse, and search video with full metadata support for efficient management of video assets.
* Deliver Adaptive Video Sets to the Web and to desktops and mobile devices, including the iPhone, iPad, Android&trade;, BlackBerry&reg;, and Windows&reg; phone.

  Adaptive video streaming is supported on various iOS platforms.

  See the latest support in the [Adobe Viewers Reference Guide](https://experienceleague.adobe.com/en/docs/dynamic-media-developer-resources).

  Adobe Dynamic Media Classic supports mobile video playback for MP4 H.264 video. <!-- LINK IS 404; NO SUITABLE REPLACEMENT WAS FOUND You can find BlackBerry&reg; devices that support this video format at the following website: -->

  <!-- See [Supported video formats on BlackBerry&reg;](https://support.blackberry.com/kb/articleDetail?ArticleNumber=000005482). -->

  You can find Windows&reg; devices that support this video format at the following:

  [Supported video formats on Windows&reg; Phone](https://learn.microsoft.com/en-us/windows/uwp/audio-video-camera/supported-codecs).

* Play back the video using Adobe Dynamic Media Classic Viewer Presets, including the following:

  * Single Video Viewers.
  * Mixed Media viewers that combine both video and image content.

* Configure video players to meet your branding needs.
* Integrate video to your website, mobile site, or mobile application with a simple URL or Embed Code.

See the following training videos:
* [MP4 video overview](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/563_MP4%20Video%20Overview_converted%20renamed_eVideos-AVS)

* [MP4 video preview](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/564_MP4%20Video%20Preview_converted%20renamed_eVideos-AVS)

* [MP4 video upload](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/565_MP4%20Video%20Upload_converted%20renamed_eVideos-AVS)

* [Streaming overview](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/567_Streaming%20Overview_master_eVideos_converted%20renamed_eVideos-AVS)

**Quick Start**

The following step-by-step workflow description is designed to help you get up and running quickly with Adaptive Video Sets in Adobe Dynamic Media Classic. After each step, there is a cross-reference to a topic heading where you can find more information.

## 1. Upload and encode videos

Upload and generate adaptive video sets using one of the following two scenarios:

* **Upload pre-encoded videos**: If your videos were already encoded externally from Adobe Dynamic Media Classic, on the Global Navigation bar, select **[!UICONTROL Upload]**. Browse and upload MP4 video files directly to Adobe Dynamic Media Classic. Then, go to **[!UICONTROL Build]** > **[!UICONTROL Adaptive Video Sets]**. Browse to your video files. Drag-and-drop the video files that you want into the Adaptive Video Set table, and then save the set.
* **Upload primary source videos**: If your videos are not encoded, on the Global Navigation bar, select **[!UICONTROL Upload]** to upload primary video source files (non-MP4). Adobe Dynamic Media Classic encodes them to MP4 files for you. In the **[!UICONTROL Upload Job Options]** dialog box, under **[!UICONTROL EVideo Options]**, select **[!UICONTROL Adaptive Video]**.

  With this preferred option, you can create Adaptive Video Sets. The correct encoding preset is automatically applied to the video, whether 16:9 or 4:3, to match the dimensions of the video you uploaded. When you submit your upload job, an Adaptive Video Set is automatically created for you that includes three encode video settings in the correct aspect ratio.

  Or, in the same **[!UICONTROL Job Options]** dialog box, under **[!UICONTROL EVideo Options]**, expand **[!UICONTROL Single Encoding Presets]**. Select the individual video encoding presets that you want. You can select **Desktop**, **Mobile (iPhone, iPad, Android&trade;)**, and **Tablet (iPad, Android&trade;)** to create the MP4 files.

* Or, you can reprocess a primary video using the **[!UICONTROL Reprocessing]** feature. The newly encoded videos are added to the existing Adaptive Video Set.

See [Upload and encode videos](uploading-encoding-videos.md#uploading_and_encoding_videos).

**Optional**

Adobe Dynamic Media Classic offers numerous predefined video encoding presets. These predefined presets reflect the most common video encoding settings used today and are optimized for playback on target pages.

However, if further customization is needed, administrators can create Video Presets to customize the size and playback experience of Videos to end users. Administrators can add and manage Video Presets from the Video Presets page available under **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Video Presets]** > **[!UICONTROL Single Encoding Presets]**. The Video Presets page offers options for adding, editing, deleting, and activating Video Presets.

See [Work with video encoding presets](uploading-encoding-videos.md#working_with_video_encoding_presets).

## 2. Preview videos in a video viewer

To see how a video plays for end users on a desktop, your website, or on a mobile device, select the video in the Browse panel. Then select **[!UICONTROL Preview]**.

See [Preview videos in a video viewer](previewing-videos-video-viewer.md#previewing_videos_in_a_video_viewer).

You can play the video on the Preview page. You can also choose different Video Viewers to find out how your video appears in different players. As a best practice, use the HTML5 video player for multi-screen playback on desktop, tablet, and mobile devices.

**Optional**

Viewer Preset customization: Adobe Dynamic Media Classic offers predefined Viewer Presets for delivering video. These presets determine the look of the Viewer and how its playback controls work. To customize the video viewer, Administrators can add and manage Viewer Presets from the Viewer Presets page. To open this page, in the upper-right corner of Adobe Dynamic Media Classic, go to **[!UICONTROL Setup]** > **[!UICONTROL Viewer Presets]**. The Viewer Presets page offers commands for adding, editing, deleting, and activating Viewer Presets.

See [Work with Video Viewer Presets](previewing-videos-video-viewer.md#working_with_video_viewer_presets).

See also [Video presets](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/549_video-presets_converted%20renamed_Done-AVS) training video.

## 3. Deploy videos to your websites and mobile sites

To integrate video into your website, you can do either one of the following:

* Display the video in its own pop-up or modal window, in which case use the **[!UICONTROL Copy URL]** feature.

  To obtain the URL for a video, in the Grid View or List View, select it in the Browse panel. Select **[!UICONTROL Preview]**, and then select **[!UICONTROL Copy URL]** to the right of `Universal_HTML5_Viewer`.

  When you select **[!UICONTROL Copy URL]**, the URL is copied to the Clipboard. Place this code in the HTML of your website, mobile site, or application.

  >[!NOTE]
  >
  >URLs are activated only after you publish the video or Adaptive Video Set.

* Display the video embedded on the Web page, in which case use the **[!UICONTROL Embed Code]** feature.

  To obtain the Embed Code for a video, in the Grid View or List View, select the video in the Browse panel. Go to **[!UICONTROL Preview]** > **[!UICONTROL Viewer List]**. Under the Actions column of the table, select **[!UICONTROL Embed Code]** to the right of `Universal_HTML5_Video`. Editing the code is not permitted.

  Select **[!UICONTROL Close]** and paste the Embed Code in one or more of your Web pages.

  >[!NOTE]
  >
  >The Embed Code is only activated after you publish the video or Adaptive Video Set.

See [Deploy video to your websites and mobile sites](deploying-video-websites-mobile-sites.md#deploying_video_to_your_websites_and_mobile_sites).

>[!MORELIKETHIS]
>
>* [Best practices for video encoding](uploading-encoding-videos.md#best_practices_for_video_encoding)
