---
title: Administration Setup
description: Learn how to set up the administration area of Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
feature: Dynamic Media Classic
role: Admin
exl-id: 14e3d8be-f265-4cec-aa8e-19ef71526b68
topic: Administration
level: Intermediate
---
<!-- UPDATE TOPIC AFTER DECEMBER 31, 2020!!!! -->

# Administration setup{#administration-setup}

The Administration Setup screens are for administering Adobe Dynamic Media Classic users. Use these screens to enable users to work in Adobe Dynamic Media Classic and to communicate by e-mail with other users.

1. To access Administration Setup options, go to **Setup** > **Personal Setup** > **Administration Setup**.

## User administration {#user-administration}

All Adobe Dynamic Media Classic users are assigned a role that determines their privileges and access rights to features in Adobe Dynamic Media Classic. Administrators determine the different roles and responsibilities for the companies to which they are assigned.

Typically, Adobe Dynamic Media Classic configures the first set of companies and assigns a Company Administrator. The Company Administrator then sets up and administers Adobe Dynamic Media Classic users.

Adobe Dynamic Media Classic supports several user roles. These roles can access companies set up for the Adobe Dynamic Media Classic:

<!-- **Adobe Dynamic Media Classic Administrator** Can view and administer all features in Adobe Dynamic Media Classic, as well as set up companies and add administrators and users. -->

**Adobe Dynamic Media Classic User** Can access companies to which they have been assigned; cannot perform any administrative duties.

**Adobe Dynamic Media Classic Company Admin** Can view and administer only their own companies. A Company Administrator can also perform all administration functions, including adding administrators and users. A Company Administrator can add a user to the DMC company admin accounts. (This role is the default user role.)

After you add a user, Adobe Dynamic Media Classic sends the user a Welcome e-mail message. The message includes a password and the Adobe Dynamic Media Classic URL.

### Add a user or administrator {#adding-a-user-or-administrator}

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. Select **[!UICONTROL Add]**.
1. Enter the name and email address of the user or administrator that you want to add, then select **[!UICONTROL Next]**.

   >[!NOTE]
   >
   >The apostrophe character (`'`) is not allowed in email addresses.

1. To assign a role to the user, choose a Role option.

   See [Adobe Dynamic Media Classic user roles and privileges](administration-setup.md#user_administration).

1. To add a user to a company, select a company name.
1. If you want to add the user to a group (if you are adding a Media Portal user or contributor), select **[!UICONTROL Next]** and add the user.
1. Select **[!UICONTROL Save]** to complete the user setup.

   After saving, a prompt asks if you want to add a user to another company. Select **[!UICONTROL Add]** if you want to add the user to a company.

   All new users are given a randomly generated password; users are required to change passwords the first time they sign in to the Adobe Dynamic Media Classic desktop application.

   New users are sent a Welcome e-mail after you add them. The e-mail provides a temporary password and explains how to sign in to Adobe Dynamic Media Classic.

   If the user does not receive the welcome email, have them go the Adobe Dynamic Media Classic sign in page (https://s7sps1.scene7.com), and select **[!UICONTROL Forgot My Password]**. The password is reset and a new email is sent. If the user does not receive the email and it is not in their Junk folder, contact Technical Support.

   When adding new Media Portal users, you can also go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL User Administration]**, then select **[!UICONTROL Upload User List]** and select a .csv file containing no more than 500 users.

### Delete a user {#delet-a-user}

You can delete users from Adobe Dynamic Media Classic by making them invalid. Invalid users are removed from the system and all accounts.

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. Select a user from the list, and then select **[!UICONTROL Edit]**.
1. Deselect Valid.
1. Select **[!UICONTROL Save]**.

### Activate or deactivate users {#activating-or-deactivating-users}

Users who have been deactivated no longer have permission to enter the account listed at the top of the Select Accounts To Access menu.

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. In the user list, select or deselect the **[!UICONTROL Active]** option next to the name of the user.

### Edit user information {#editing-user-information}

The user information that you can edit depends on your role as an administrator and the assigned role of the user whose information you want to edit. Options that are dimmed (unavailable) are not editable.

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. Select a user from the list, and then select **[!UICONTROL Edit]**.
1. Select the entry in the table that shows the company you are trying to modify permissions or access for, then select **[!UICONTROL Manage Company]**.
1. Select the user role.
1. If you want to change the user's group membership (if you are editing or adding a Media Portal user or contributor), select **[!UICONTROL Next]** and edit the group membership.
1. Select **[!UICONTROL Save]**.

### Filter and sort the user list {#filtering-and-sorting-the-user-list}

You can filter and sort the user list to locate users. All users in all accounts you administer appear in the Users list, regardless of the account selected in the Select Account To Access menu.

You can use the following user list-filtering techniques:

* **Filter by group**: Select the **[!UICONTROL By Group]** menu and choose an option to narrow the list to users in a group.

* **Filter by user role**: Select the **[!UICONTROL By User Role]** menu and choose an option to narrow the list to users or administrators of different types.

* **Filter by field name**: Select **[!UICONTROL Enable Filter By Field]**. Then select the **[!UICONTROL By Field Name]** menu, choose a column for filtering the list, and select the Filter Character menu and choose a letter. The list is filtered on one of the columns by the letter that you chose. To see the full list, deselect the **[!UICONTROL Enable Filter By Field]** option.

* **Filter out invalid users**: Deselect **[!UICONTROL Include Invalid]**. The search results display only users who are in the system. Invalid users have been deleted from the system and the accounts that you administer.

* **Sort by column heading**: Select a heading to sort all users by their status, alphabetically by first name, last name, or email. Or, sort by user role, or by valid/invalid status.

If you have many users, you can limit the size of the list by selecting the Max List Size menu and choosing a number.

<!-- CQDOC-16690 TOPIC REMOVED AS PER JIRA TICKET INSTRUCTIONS ### Linking an IMS user identity to an Adobe Dynamic Media Classic IPS user account {#linking-an-ims-user-identity-to-a-scene-ips-user-account}

You can link an Adobe IMS user identity to an Adobe Dynamic Media Classic IPS user account so you can use SSO (Single Sign On) to log on and launch Scene7 Publishing System from within Adobe Marketing Cloud.

1. Adobe should already have setup your account with an Adobe Marketing Cloud organization and linked it to your Scene7 Publishing System product context. If this setup is not yet done or you are unsure if it has been done, contact Adobe Customer Care.

   When the setup is complete, you can can log on to Adobe Marketing Cloud and link your Adobe Marketing Cloud identity to your Adobe Dynamic Media Classic user account by doing the following.

1. In Adobe Marketing Cloud, navigate to your account settings.
1. Select **Manage Organizations**.
1. Select **Link Account** or **Get Access**.
1. Select **Experience Manager**, and then type your credentials.

   Your credentials include your IPS company region, email address, and password.

1. Select **Link**.
1. When the link is set, you can launch Scene7 Publishing System from within Adobe Marketing Cloud, or you can launch it directly.

   Do one of the following:

    * To launch Adobe Dynamic Media Classic from within Adobe Marketing Cloud, in the left rail of Adobe Marketing Cloud, select **Solutions** > **Experience Manager**. Under the Adobe Dynamic Media Classic card, select **Launch**.
    * To log on to Scene7 Publishing System directly using your IMS credentials, use the following website:

      https://s7spsN.scene7.com/IpsWeb?ims=1

      Replace "N" in the above path with the number for your IPS company region. That is, N = 1 for North America; 3 for EMEA; or 5 for JAPAC.
 -->

## Bandwidth and storage {#bandwidth-storage}

Adobe Dynamic Media Classic Administrators can generate bandwidth, storage, and other types of reports for the companies they administer. These reports are available on the Bandwidth & Storage page.

To open this page, go to **[!UICONTROL Setup]** > **[!UICONTROL Personal Setup]**. Expand **[!UICONTROL Administration Setup]**, and then select **[!UICONTROL Bandwidth & Storage]**.

### Types of reports {#types-of-reports}

The following table describes reports that you can generate from the Bandwidth & Storage page:

| Report | Information | Use|
| --- | --- | --- |
| Bandwidth | | **IMPORTANT**: The Bandwidth tab is no longer supported. Although it still appears in the UI, bandwidth data is not available and all values display as `0`. |
| Storage | Storage usage | Track the amount of data uploaded by the company. |
| Image Content | Displays the total hits and image delivery volume broken down by request type and subtype. | Track the number of requests and volume for different image types including metrics from non-video assets. |
| Domain | The number of URL requests by domain | Track image usage based on the domain of the image request for a specific company. (Adobe Dynamic Media Classic can provide more than one domain per account. For more information, contact Technical Support.) |
| Video Streaming | Bandwidth usage for streaming video | Track streaming video usage by company over specific date ranges to determine traffic patterns. |
| Video Content | Playing time of different videos|Determine which are the most viewed and least viewed videos. |

The Image Content report provides information about requests for the following image types:

* **Image Request**: Requests for images.

* **Thumbnail Request**: Requests for swatch or alternate images in viewers.

* **Mask Request**: Requests to images returning gray-scale masks.

* **Viewer Tile Request**: Image requests loaded by a viewer.

* **VNT Object Request**: Image rendering requests that return an image with specified objects in the requested vignettes.

* **VNT Info Request**: Image rendering requests that return information concerning the requested vignettes.

>[!NOTE]
>
>The Video Streaming report applies to streaming videos only. It doesn't track the viewing of progressive videos.

### Generate a report {#generating-a-report}

To generate a bandwidth, storage, image content, domain, video streaming, or video content report:

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Personal Setup]**.
1. Expand Administration Setup, and then select **[!UICONTROL Bandwidth & Storage]**.
1. Select a tab: **[!UICONTROL Bandwidth]**, **[!UICONTROL Storage]**, **[!UICONTROL Image Content]**, **[!UICONTROL Domain]**, **[!UICONTROL Video Streaming]**, or **[!UICONTROL Video Content]**.

   See [Types of reports](administration-setup.md#types_of_reports).

### View data in different ways {#viewing-data-in-different-ways}

After you generate a report on the Bandwidth & Storage page, you can choose options for viewing information. You can choose how information is presented, view information in a chart or data grid, and specify a time period for capturing information. In Data view, you can also sort information and rearrange columns.

* **View data in a chart or data grid**: Select **[!UICONTROL Chart View]** to see data in a chart; select **[!UICONTROL Data View]** to view data in a data grid.

* **Choose a report presentation type**: On the Report Type menu, select **[!UICONTROL Summary]**, **[!UICONTROL Daily]**, or **[!UICONTROL Monthly]** to organize data in summary form, by day, or by month. Not all reports provide this option.

* **Specify a time period**: Choose options to define a time period for your report, and then select **[!UICONTROL Update]** after you define a time period:

* **Pre-defined time period**: On the Pre-defined Report menu, choose an option. For example, choose Last Month to capture data from the previous month.

* **Custom time period**: On the Pre-defined Report menu, select **[!UICONTROL Custom]**. Then choose a date on the **[!UICONTROL Start Month]** (or **[!UICONTROL Start Date]**) menu and a date on the # of Months (or # or Days) menu. For Domain and Video Content Reports, you can choose a specific start and end date for capturing report information.

* **Sort data (Data view only)**: Sort information in a column. Select the column's heading. Select again to sort in descending order.

* **Rearrange columns (Data view only)**: To move a column to a different location on the data grid, drag its heading.

### Export and print reports {#exporting-and-printing-reports}

After you generate a report, you can export its data for use in spreadsheets and other applications. You can also print reports.

* **Export report data**: In Data view, sort, and arrange the data as necessary. Then open the **[!UICONTROL Export]** menu and choose a format: **[!UICONTROL Tab Delimited]**, **[!UICONTROL Comma Separated]**, or **[!UICONTROL HTML Formatted]**. The data is copied to the Clipboard in the format that you chose. You can now paste the data into a spreadsheet or application.

* **Print a report**: Select **[!UICONTROL Print]**, choose the options you want in the Print dialog box, and then select **[!UICONTROL OK]**.

## Image Errors {#image-errors}

Adobe Dynamic Media Classic Administrators can generate Image Error reports. An Image Error report provides a list of the 20 most frequent image errors, for the past 24 hours, for the company you are currently logged in to. To generate an Image Error report, do the following:

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Personal Setup]**.
1. Expand Administration Setup, and then select **[!UICONTROL Image Errors]**.
1. (Optional) Do any of the following:

    * To sort errors by the heading information, select a heading. By default, errors are sorted by number of occurrences, highest to lowest.
    * Move the cursor over the Response field for an error to see the specific error message.
    * To see the link to the image or the referrer Web page, move the cursor over the URL field or the Referrer field.
    * To copy the link to the actual image, select **[!UICONTROL URL Copy URL]**. You can paste this link in a browser window to go to the image and investigate the error.
    * To copy the link to the referrer Web page, select **[!UICONTROL Referrer Copy URL]**.

Errors displayed are for the company that you are currently logged in to. Each error includes the following information:

* **Image ID**: ID for the offending image.

* **Time**: The time range of the first time the error was reported to the last time that the error was reported, within the last 24 hours.

* **Count**: The number of errors reported on the image.

* **Response**: The specific error message. Errors are either 4xx or 5xx.

* **URLs**: Lists the URL to the image on Adobe Dynamic Media Classic.

* **Referrer**: Specifies the URL for the Web site where the initial request came from. The referrer can be any Web site that has a link to the image.

The URL and Referrer columns have Copy URL associated with them to simplify testing.
