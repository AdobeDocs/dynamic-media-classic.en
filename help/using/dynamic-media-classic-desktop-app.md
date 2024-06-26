---
title: Adobe Dynamic Media Classic desktop
description: Learn more about the Adobe Dynamic Media Classic desktop application that is now available.
contentOwner: rbrough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/introducing_adobe_dynamic_media_classic
feature: Dynamic Media Classic
role: Admin,User
exl-id: 604b4630-4704-4254-84b5-91b33bb19d58
topic: Administration
level: Intermediate
---
# Available now: Adobe Dynamic Media Classic desktop app {#dynamic-media-classic-desktop-app}

Adobe Dynamic Media Classic users now have access to a new desktop app experience that no longer relies on Adobe Flash technology in the browser.

This new app is now available for Windows&reg; and macOS.

>[!IMPORTANT]
>
>Adobe recommends that you install the new Adobe Dynamic Media Classic desktop app by October 1, 2020. Doing so will ensure you have a smooth transition before Adobe Flash Player is deprecated on December 31, 2020. After that date, you cannot log on to the browser version of Adobe Dynamic Media Classic user interface, labeled as Adobe Dynamic Media Classic in the product.

See the FAQ for the [New Adobe Dynamic Media Classic sign in now available.](/help/using/new-ui-2020.md)

## System requirements for Adobe Dynamic Media Classic desktop app {#system-requirements-dmc-app}

The Adobe Dynamic Media Classic desktop app is compatible with the following operating systems:

* macOS 10.10 or newer.
* Windows&reg; 7 or newer.

See the full system requirements at [System requirements for Adobe Dynamic Media Classic desktop app](/help/using/system-requirements.md).

Upgrade notification within the Adobe Dynamic Media Classic desktop application is not generated for *minor* releases. Customers who benefit from fixes in a minor release can upgrade.

## Fixed in the latest release (20.22.2) macOS only {#release-feb2022}

* macOS Monterey: File upload page froze on subsequent uploads. <!-- https://jira.corp.adobe.com/browse/ASSETS-7948 -->

## Fixes in the latest release (20.22.1) {#release-jan2022}

* When editing an image, the **[!UICONTROL Save]** buttons were non-functional.
* In the Set editors, the **[!UICONTROL Close]**, **[!UICONTROL Save]**, and **[!UICONTROL Save As]** buttons become disabled after scrolling assets in the **[!UICONTROL Add Assets]** panel.
* The **[!UICONTROL Play]** button in Video Detail view did not work.
* Could not enter `d` and `e` in **[!UICONTROL Username]** and **[!UICONTROL Password]** fields when running macOS Monterey.
* Moved the remaining analytics APIs to version 2.0.

## Fixes in release 20.21.3 {#release-sept2021}

* Broken thumbnails for assets seen after a period of inactivity on the desktop app.
* The Desktop app stops responding, typically after Set operations.
* Request Obfuscation and Locking Mode auto-enabled under **[!UICONTROL Test Image Serving]**.

    See [The Secure Testing service](/help/using/testing-assets-making-them-public.md#testing-the-secure-testing-service).

* Updated authentication mechanism with Adobe Analytics. Relevant for new integrations or if some Analytics variables must be updated from within the Dynamic Media Classic desktop app.

    See [Log on to Adobe Analytics](/help/using/log-analytics.md) for updated steps.

## Fixes in release 20.21.2 {#minor-release}

* Known limitation in 20.21.1: the **[!UICONTROL Server]** drop-down list on the Sign-in screen was empty.
* In **[!UICONTROL Upload Job Options]**, the default Layer name value under **[!UICONTROL Photoshop Options]**, is now **[!UICONTROL Photoshop and Layer Name]**. Layers in the PSD file are uploaded as separate images.
  * The earlier default of **[!UICONTROL Layer name]**, named the images after their layer name or layer number in the PSD file. The layer number was used if the layer names in the PSD file were default Photoshop layer names.
  * The new default of **[!UICONTROL Photoshop and Layer Name]**, names the images after the PSD file followed by the layer name or layer number. The layer number is used if the layer names in the PSD file are default Photoshop layer names.
  * Given that layer images in Adobe Dynamic Media Classic now have unique names, no updates to existing PSD or Templates are going to happen (which shared layer names in the original PSD files).
* Broken thumbnails of assets.

## Fixes in release 20.21.1 {#latest-fixes-desktop-app}

* Sign in issues due to timeout resulting in the following message: *This user may be assigned to the group or groups without permission. Contact your administrator.*
* Viewer presets get duplicated with each incorrect password attempt.
* Desktop application becoming unresponsive due to many assets in the root folder. (Fixed on Windows&reg;; working as desired on macOS.)

## Fixes in release 20.20.2 {#previous-version-fixes-desktop-app}

* No limitation on the number of files that you can upload through the desktop app user interface for both macOS and Windows&reg;.
* No need to sign out of the desktop app to switch between companies.
* Ctrl+V for paste operation now works on Windows&reg;.
* In the future, when a new version of the desktop app is released, users are going to be notified within the desktop app itself.

## Download and install the latest Adobe Dynamic Media Classic desktop app on macOS or Windows&reg; {#installation-dmc-app}

See also:

* [Download and silently install the latest Adobe Dynamic Media Classic desktop app on Mac](#install-silent-mac-dmc-app)
* [Download and silently install the latest Adobe Dynamic Media Classic desktop app on Windows&reg;](#install-silent-windows-dmc-app)

1. Uninstall any older Adobe Dynamic Media Classic desktop app versions on your system.

1. Download the latest installer for the Adobe Dynamic Media Classic desktop app.

    * The latest version is available at the following:

        * [macOS (.DMG): Download](https://download.macromedia.com/dynamic-media-classic/20.22.2/adobe-dynamic-media-classic-20.22.2.dmg)
        * [Windows (.EXE): Download](https://download.macromedia.com/dynamic-media-classic/20.22.1/adobe-dynamic-media-classic-20.22.1.exe)

    * The previous version is available at the following:

        * [macOS (.DMG): Download](https://download.macromedia.com/dynamic-media-classic/20.22.1/adobe-dynamic-media-classic-20.22.1.dmg)
        * [Windows&reg; (.EXE): Download](https://download.macromedia.com/dynamic-media-classic/20.21.3/adobe-dynamic-media-classic-20.21.3.exe)

<!--         * [macOS (.DMG): Download](https://download.macromedia.com/dynamic-media-classic/20.21.3/adobe-dynamic-media-classic-20.21.3.dmg) -->

<!--    * [macOS (.DMG): Download](https://download.macromedia.com/dynamic-media-classic/20.21.2/adobe-dynamic-media-classic-20.21.2.dmg)
        * [Windows&reg; (.EXE): Download](https://download.macromedia.com/dynamic-media-classic/20.21.2/adobe-dynamic-media-classic-20.21.2.exe) -->

<!--    * [macOS (.DMG): Download.](https://download.macromedia.com/dynamic-media-classic/20.20.2/adobe-dynamic-media-classic-20.20.2.dmg)
        * [Windows (.EXE): Download.](https://download.macromedia.com/dynamic-media-classic/20.20.2/adobe-dynamic-media-classic-20.20.2.exe) -->


1. Do one of the following based on the installer that you downloaded.

    * **macOS** &ndash;In the **[!UICONTROL Drag & drop to install]** dialog box, drag **[!UICONTROL Adobe Dynamic Media Classic]** and drop it onto **[!UICONTROL Applications]**.

        ![Drag and drop install on macOS](/help/using/assets/dragondrop-install1.png)

    * In the **[!UICONTROL Applications]** folder, tap the Adobe Dynamic Media Classic icon.
    * In the dialog box, tap **[!UICONTROL Open]** to open the Adobe Dynamic Media Classic desktop app.

        ![Open downloaded app](/help/using/assets/open-dmclassicapp1.png)

    * **Windows** &ndash; Run the installer binary and follow the on-screen instructions to install the desktop app.

1. When you open the application, the new Adobe Dynamic Media Classic Sign-in page is displayed:

    ![Adobe Dynamic Media Classic sign in](/help/using/assets/dmclassic-login1.png)

1. To sign in to the Adobe Dynamic Media Classic desktop app, use the same credentials that you used to log on to Adobe Dynamic Media Classic in the browser.

    For the **[!UICONTROL Server]** to use, see the following mapping for the production environment:

    | Server | Browser URL |
    | --- | --- |
    | NA Production (North America) | https://s7sps1.scene7.com/ |
    | EMEA Production (Europe, Middle East, and Africa) | https://s7sps3.scene7.com/ |
    | APAC Production (Asia-Pacific) | https://s7sps5.scene7.com/ |

1. Following sign in, notice the familiar browser user interface experience. You can continue your day-to-day Adobe Dynamic Media Classic activity as usual on the desktop app.

## Download and *silently* install the latest Adobe Dynamic Media Classic desktop app on macOS {#install-silent-mac-dmc-app}

See also:

* [Download and install the latest Adobe Dynamic Media Classic desktop app on Mac or Windows&reg;](#installation-dmc-app)
* [Download and silently install the latest Adobe Dynamic Media Classic desktop app on Windows&reg;](#install-silent-windows-dmc-app)

To download and *silently* install the latest version of the Adobe Dynamic Media Classic desktop app on macOS:

1. Uninstall any older Adobe Dynamic Media Classic desktop app versions on your system.

1. Download the latest installer for the Adobe Dynamic Media Classic desktop app for macOS.

    * [macOS (.DMG): Download](https://download.macromedia.com/dynamic-media-classic/20.22.2/adobe-dynamic-media-classic-20.22.2.dmg)

1. Mount the downloaded Disk Image (.DMG) to a mountpoint location using the following command:

    `hdiutil attach adobe-dynamic-media-classic-20.22.2.dmg -mountpoint <mount_point_path>`

1. Copy the .APP file to **[!UICONTROL Applications]** using the following command:

    ```
    rsync -a <mount_point_path>/Adobe\ Dynamic\ Media\ Classic.app /Applications/
    Unmount DMG: hdiutil detach <mount_point_path>
    ```

1. When you open the application, the new Adobe Dynamic Media Classic Sign-in page is displayed:

    ![Adobe Dynamic Media Classic sign in](/help/using/assets/dmclassic-login1.png)

1. To sign in to the Adobe Dynamic Media Classic desktop app, use the same credentials that you used to log on to Adobe Dynamic Media Classic in the browser.

    For the **[!UICONTROL Server]** to use, see the following mapping for the production environment:

    | Server | Browser URL |
    | --- | --- |
    | NA Production (North America) | https://s7sps1.scene7.com/ |
    | EMEA Production (Europe, Middle East, and Africa) | https://s7sps3.scene7.com/ |
    | APAC Production (Asia-Pacific) | https://s7sps5.scene7.com/ |

## Download and *silently* install the latest Adobe Dynamic Media Classic desktop app on Windows&reg; {#install-silent-windows-dmc-app}

The command that you use is for a basic MSI silent installation. However, the Adobe Dynamic Media Classic desktop app installer is an InstallScript MSI installer created using InstallShield. When you run the installer in record mode, any user interaction is recorded in a response file. This response file is then used for a silent installation as described in [Running installations in silent mode](https://docs.revenera.com/installshield25helplib/installshield25helplib.htm#helplibrary/SilentInstall.htm).

See also:

* [Download and install the latest Adobe Dynamic Media Classic desktop app on Mac or Windows&reg;](#installation-dmc-app)

* [Download and silently install the latest Adobe Dynamic Media Classic desktop app on macOS](#install-silent-mac-dmc-app)

To download and *silently* install the latest version of the Adobe Dynamic Media Classic desktop app on Windows&reg;:

1. Uninstall any older Adobe Dynamic Media Classic desktop app versions on your system.

1. Download the latest installer for the Adobe Dynamic Media Classic desktop app.

    * [Windows&reg; (.EXE): Download](https://download.macromedia.com/dynamic-media-classic/20.22.1/adobe-dynamic-media-classic-20.22.1.exe)

1. Run the installer in record mode using the following command:

    `adobe-dynamic-media-classic-20.22.1.exe /r /f1"C:\Setup.iss"`

1. In the GUI installer window, follow the steps to install so that interactions/inputs, like install location, get recorded in `Setup.iss` file.

1. Copy the created `Setup.iss` file and `adobe-dynamic-media-classic-20.22.1.exe` to other computer.

1. Run the following command for a silent installation:

    `adobe-dynamic-media-classic-20.22.1.exe /s /f1"C:\Setup.iss"`

    Details about command-line parameters are available at [Setup.exe and Update.exe command-line parameters](https://docs.revenera.com/installshield25helplib/installshield25helplib.htm#helplibrary/IHelpSetup_EXECmdLine.htm?Highlight=Setup.exe%20and%20Update.exe%20Command-Line%20Parameters).

1. When you open the application, the new Adobe Dynamic Media Classic Sign-in page is displayed:

    ![Adobe Dynamic Media Classic sign in](/help/using/assets/dmclassic-login1.png)

1. To sign in to the Adobe Dynamic Media Classic desktop app, use the same credentials that you used to log on to Adobe Dynamic Media Classic in the browser.

    For the **[!UICONTROL Server]** to use, see the following mapping for the production environment:

    | Server | Browser URL |
    | --- | --- |
    | NA Production (North America) | https://s7sps1.scene7.com/ |
    | EMEA Production (Europe, Middle East, and Africa) | https://s7sps3.scene7.com/ |
    | APAC Production (Asia-Pacific) | https://s7sps5.scene7.com/ |

## Video walk-through on using Adobe Dynamic Media Classic Desktop App {#dmc-app-video-walk-through}

Watch a [video walk-through on using Adobe Dynamic Media Classic Desktop App](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-classic-desktop-application#dynamic-media) (Length: 2 minutes 36 seconds).

## Clearing the image cache and asset cache on your computer using the desktop app {#clear-cache}

1. In the Adobe Dynamic Media Classic desktop app, near the upper-right corner, tap **[!UICONTROL Setup]** > **[!UICONTROL Personal Setup]**.
1. On the **[!UICONTROL Personal Setup]** page, under the **[!UICONTROL Desktop]** heading, do any of the following:
    * To remove all Adobe Dynamic Media cached image files from your computer, tap **[!UICONTROL Clear Image Cache]**, then tap **[!UICONTROL OK]**.
    * To remove all Adobe Dynamic Media cached asset files from your computer, tap **[!UICONTROL Clear Asset Cache]**, then tap **[!UICONTROL OK]**.
1. In the lower-right corner of the page, tap **[!UICONTROL Close]**.

### Clearing the image cache and asset cache manually

Besides clearing the image and asset cache using the desktop app, you can manually clear the cache directly from the file system.

1. Based on your operating system, navigate to the following:

    * macOS: `~/Library/Application\ Support/com.adobe.DMCDesktop/Local\ Store/`
    * Windows&reg;: `C:\Users\YourUserName\AppData\Roaming\com.adobe.DMCDesktop\Local Store`

## Known limitations in Adobe Dynamic Media Classic 20.21.1

* The **[!UICONTROL Server]** drop-down list is empty after updating to Adobe Dynamic Media Classic desktop app 20.21.1: Scenario: You install and sign in to Adobe Dynamic Media Classic 20.20.1 or 20.20.2, then close the application. Then you update to Adobe Dynamic Media Classic 20.21.1. When you attempt to sign in, the **[!UICONTROL Server]** drop-down list in the **[!UICONTROL Sign-in to your account]** dialog box is empty. To work around this issue, you must [manually clear the cache](#clear-cache) (see steps above).

## Known limitations in Adobe Dynamic Media Classic 20.20.1 (fixed in 20.20.2)

**_Applies to Windows&reg; only &ndash; Is there a limitation on the number of files that can be uploaded through the desktop app UI?_**<br>Yes, a maximum of 150 files can be uploaded at a time using the desktop app UI.

**_Applies to Windows&reg; and macOS &ndash; How do I switch between companies?_**<br>To switch between companies, do the following:

* In the Adobe Dynamic Media Classic app, select the new company from the company drop-down list.
* When the pop-up window appears, tap **[!UICONTROL OK]** to sign out and close the app.

    ![To use the new company, restart the app](/help/using/assets/dmclassic-new-company1.png)

* Restart Adobe Dynamic Media Classic, then sign in as usual to work with the new company.

## Tips and Tricks

**_I am unable to see the Media Cart panel on the landing page of Adobe Dynamic Media Classic._**<br>In Adobe Dynamic Media Classic, tap **[!UICONTROL Setup > Personal Setup]**. In the Browser section, make sure **[!UICONTROL Show MediaPortal Features]** is selected (checked). Tap **[!UICONTROL Save > Close]**.

**_Publish state (green indicator) of an asset is not reflected correctly._**<br>In the browser user interface, a relogin to the UI was required to see the correct publish state of assets. In the desktop app, Adobe has introduced a **[!UICONTROL Refresh]** icon in the toolbar, to the right of the **[!UICONTROL Select None]** button. Tap the **[!UICONTROL Refresh]** icon to see the latest status of all the assets on the given page. No relogon required as with the browser UI.

![Refresh icon](/help/using/assets/refresh-icon1.png)
*Refresh icon*
 
**_I do not see batch set presets working in the desktop app._**<br>Tap **[!UICONTROL Upload > Job Options > Batch Set Presets]**. Ensure the relevant **[!UICONTROL Batch Set Preset]** is enabled. Click **[!UICONTROL Save and Submit upload]**.
