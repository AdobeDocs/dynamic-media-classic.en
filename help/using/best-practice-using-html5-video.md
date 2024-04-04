---
title: Best practice for using the HTML5 Video viewer
description: Learn about best practices for using the HTML5 video viewer.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/video
feature: Dynamic Media Classic,Viewers,Video
role: User
exl-id: ce49e4ce-8dc0-41e1-865a-249f23757553
topic: Content Management
level: Intermediate
---
# Best practices for using the HTML5 Video viewer{#best-practice-using-the-html-video-viewer}

The Adobe Dynamic Media Classic HTML5 Video viewer presets are robust video players. On the design side of the player, you can create the video player's entire functionality using standard web development tools. For example, you can design the buttons, controls, and custom poster image background using HTML5 and CSS to help you reach your customers with a customized appearance.

On the playback side of the viewer, it automatically detects the browser's video capability. It then serves the video using HLS (HTTP Live Streaming), also known as adaptive video streaming. Or, if that delivery method is not present then HTML5 progressive is used instead.

By combining into a single player the following abilities:

* Playback components designed using HTML5 and CSS
* Embedded playback
* Use of adaptive and progressive streaming based on the browser's capability

You extend the reach of your rich media content to desktop and mobile users. You also ensure a streamlined video experience.

See also [About HTML5 Viewers](https://experienceleague.adobe.com/en/docs/dynamic-media-developer-resources/library/viewers-for-aem-assets-only/c-html5-aem-asset-viewers#viewers-for-aem-assets-only) in the Adobe Viewers Reference Guide.

See also [Viewer presets](https://s7d5.scene7.com/s7viewers/html5/VideoViewer.html?videoserverurl=https://s7d5.scene7.com/is/content/&emailurl=https://s7d5.scene7.com/s7/emailFriend&serverUrl=https://s7d5.scene7.com/is/image/&config=Scene7SharedAssets/Universal_HTML5_Video&contenturl=https://s7d5.scene7.com/skins/&asset=S7tutorials/550_viewer-presets_converted%20renamed_Done-AVS) training video.

## Playback of video on desktop computers and mobile devices using the Adobe Dynamic Media Classic Video Viewer {#playback-of-video-on-desktop-computers-and-mobile-devices-using-the-scene-video-viewer}

For desktop and mobile adaptive video streaming, the videos used for bit rate switching are based on all MP4 videos in the Adaptive Video Set.

Video playback occurs using either HLS or progressive video. HLS (HTTP Live Streaming) is an Apple standard for adaptive video streaming that automatically adjusts playback based on network bandwidth capacity. It also lets the customer "seek" to any point in the video without the need to wait for the rest of the video to download. See also [HTTP Live Streaming](https://developer.apple.com/streaming/). Progressive video is delivered by downloading and storing the video locally to a user's desktop screen or mobile device.

The following table describes the device, browser, and playback method of videos on desktop computers and mobile devices using the Adobe Dynamic Media Classic Video Viewer.

|Device|Browser|Video playback mode|
|--- |--- |--- |
|Desktop|Internet Explorer 9 and 10|Progressive download.|
|Desktop|Internet Explorer 11+|HLS video streaming.|
|Desktop|Firefox 23-44|Progressive download.|
|Desktop|Firefox 45 or later|HLS video streaming.|
|Desktop|Chrome|HLS video streaming.|
|Desktop|Safari (Mac)|HLS video streaming.|
|Mobile|Chrome (Android&trade; 6 or earlier)|Progressive download.|
|Mobile|Chrome (Android&trade; 7 or later)|HLS video streaming.|
|Mobile|Android&trade; (Default browser)|Progressive download.|
|Mobile|Safari (iOS)|HLS video streaming.|
|Mobile|Chrome (iOS)|HLS video streaming.|
|Mobile|BlackBerry&reg;|HLS video streaming.|
