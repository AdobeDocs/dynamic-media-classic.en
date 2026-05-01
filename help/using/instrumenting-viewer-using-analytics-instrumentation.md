---
title: Instrument a viewer using the Adobe Analytics Instrumentation Kit
description: Learn how to instrument a viewer using the Adobe Analytics Instrumentation Kit in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/adobe_analytics_instrumentation_kit
feature: Dynamic Media Classic
role: Developer,Admin,User
exl-id: 9ea1546d-e6d1-4ba4-8fa1-26b4e69375ba
topic: Integrations, Development
level: Experienced
TQID: https://experienceleague.adobe.com/ZgVBu6q2JPOrcaDUvTF-hPbdeZcJAg4-pkeN4a4UPPY
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
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
---
# Instrument a viewer using the Adobe Analytics Instrumentation Kit{#instrumenting-a-viewer-using-the-adobe-analytics-instrumentation-kit}

You can use the Adobe Analytics Instrumentation Kit to integrate an HTML5 viewer with Adobe Analytics.

If you use any of the predefined Adobe Dynamic Media Classic HTML5 Viewer Presets, they already contain all the implementation code to send data to Adobe Analytics. You do not need to add any further instrumentation.

## Set up Adobe Analytics tracking from Adobe Dynamic Media Classic {#set-up-adobe-analytics-tracking-from-scene-publishing-system}

For all HTML5 viewers, add the following JavaScript to the HTML container, usually in the &lt;head> element:

```as3
<!-- ***** Adobe Analytics Tracking ***** --><script type="text/javascript" src="https://s7d6.scene7.com/s7viewers/s_code.jsp?company=<Adobe Dynamic Media Classic Company ID>&preset=companypreset-1"></script>
```

Where `Adobe Dynamic Media Classic Company ID` is set to the Adobe Dynamic Media Classic company name. And `&preset` is optional. If the company preset name is not `companypreset`, then it is not optional. In such cases, it could be `companypreset-1, companypreset-2`, and so on. The higher number is a newer instance of the preset. To determine the correct company preset value name, select **[!UICONTROL Copy URL]**, and then look at the `preset=`parameter to find the company preset name.

Continuing, now add a function that transmits the viewer event to the Adobe Analytics tracking code.

Add the `s7ComponentEvent()` function to the container HTML (or JSP, or ASPX or other):

```as3
function s7ComponentEvent(objectId, componentClass, instanceName, timeStamp, eventData) {     s7track(eventData); }
```

The function name is case-sensitive. The only parameter passed to `s7componentEvent`that is required is the last one: `eventData`. Where `s7track()` is defined in s_code.jsp included above. And `s7track` handles all tracking per each event. (You can further customize data transmitted to Adobe Analytics is this area.)

## Enable HREF and ITEM events {#enabling-href-and-item-events}

You can enable HREF (rollover) and ITEM (mouse clicks/touch) events in the viewers through Image Map editing. Define the identifiers for the HREF and ITEM within the Image Map that is associated with viewer content. Add a `&rolloverKey=` parameter to the HREF value within the Image Map.
