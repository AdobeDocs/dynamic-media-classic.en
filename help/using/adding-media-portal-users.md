---
title: Add and manage Media Portal users
description: Learn how to add and manage Media Portal users in Adobe Dynamic Media Classic.
contentOwner: Rick Brough
content-type: reference
products: SG_EXPERIENCEMANAGER/Dynamic-Media-Classic
geptopics: SG_SCENESEVENONDEMAND_PK/categories/media_portal
feature: Dynamic Media Classic,Collaboration,Asset Management
role: Admin,User
exl-id: 9590c53c-fd38-4bf2-b723-cd7369702364
topic: Administration
level: Intermediate
---
# Add and manage Media Portal users{#adding-and-managing-media-portal-users}

As an administrator, you can add and manage users, decide whether they can change passwords, edit user information, and upload user lists. These tasks are accomplished on the User Administration screen. To access this screen, navigate to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.

>[!NOTE]
>
>Before you add users, set up groups for administering them. Media Portal does not let you add a user without assigning the user to one or more groups. For more information, see [Create and manage Media Portal groups](creating-media-portal-groups.md#creating_and_managing_media_portal_groups).

## Administration of Media Portal passwords {#handling-media-portal-passwords}

Media Portal users, contributors, and contributor-users are sent a Welcome e-mail message with a password when you sign them up. Administrators can decide whether Media Portal users can change this password.

1. Navigate to **[!UICONTROL Setup]** > **[!UICONTROL Media Portal Setup]** > **[!UICONTROL General Settings]**.
1. On the General Settings page, select or deselect **[!UICONTROL Allow Media Portal user to change Password]**. 
1. Select **[!UICONTROL Save]**.

>[!NOTE]
>
>Media Portal users who are allowed to change passwords can do so by selecting **[!UICONTROL Setup]** > **[!UICONTROL Personal Setup]** and changing passwords on the Personal Setup screen.

## Add a Media Portal user {#adding-a-media-portal-user}

1. Navigate to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. On the User Administration page, select **Add**.
1. In the **[!UICONTROL `Add User`]** dialog box, in the User Info panel, enter the First Name, Last Name, and Email address of the user, and then select **[!UICONTROL Next]**.
1. In the Company/Role panel, in the Companies drop-down list, select a company or companies for the user.
1. In the Role list, select a Media Portal role, and then select **[!UICONTROL Next]**.

   See [Media Portal user roles](media-portal-user-roles.md#media_portal_user_roles).

1. In the Access Groups panel, select one or more groups.

   See [Create and manage Media Portal groups](creating-media-portal-groups.md#creating_and_managing_media_portal_groups).

1. (Optional) Select **[!UICONTROL Email Settings]** to choose e-mail settings different from the default settings.

   See [Set up the Welcome e-mail message for Media Portal users](adding-media-portal-users.md#setting_up_the_welcome_e_mail_message_for_media_portal_users).

1. Select **[!UICONTROL Add User]**.

After you add a user, Media Portal sends the user a Welcome e-mail message. The message includes a temporary password and the Media Portal URL.

## Upload a Media Portal user list {#uploading-a-media-portal-user-list}

If you have numerous users to add, you can upload a user list. The users are added automatically to the currently selected account.

Create the user list as a CSV (comma-separated values) file containing the user information. After the list is uploaded, the users in the list are automatically added to the account with their specified group assignments. A Welcome e-mail is sent to each new user, including a link to Media Portal and a temporary password.

### Create the CSV file {#create-the-csv-file}

Create a CSV file (filename.csv) that conforms to the following format and fields. The first row of the file must contain the column headings listed in this table; you can order these columns as desired. All columns are required.

|Column name|Description|
|--- |--- |
|First Name|The first name.|
|Last Name|The last name.|
|Email|A valid e-mail address.|
|Password|A case-sensitive password string.|
|User Role|MediaPortalAdminMediaPortalUserMediaPortalContributorMediaPortalContributorUser|
|Groups|List of one or more account group assignments for each user, separated by commas. You specify the group by prefixing the account name, separated by forward slash (/). For example, PortalCo/IT, where PortalCo is the account and IT is the group within the PortalCo account.|

The following sample spreadsheet demonstrates how to lay out a CSV file:

|First Name|Last Name|Email|Password|User Role|Groups|
|--- |--- |--- |--- |--- |--- |
|Prairie|Kat|`prairiek@company.com`|welcome|MediaPortalAdmin|PortalCo/IT, PortalCo/Admin|
|Rick|Brough|`rickb@myco.com`|welcome|MediaPortalUser|PortalCo/MktgGroup, PortalCo/test|

### Upload the CSV file {#uploading-the-csv-file}

1. Open the User Administration Setup screen.
1. Select **[!UICONTROL Upload User List]**.
1. In the Select File to Upload dialog box, select the CSV file, and then select **[!UICONTROL Open]**.

Each user in the list is automatically added to the specified groups. A Welcome e-mail message is sent to each.

>[!NOTE]
>
>If the CSV file was not formatted correctly, the following error message appears: "An error occurred while processing the uploaded CSV file. Check the file contents for valid data." In addition, if the CSV contains an existing IP or IPS user, the user is not added to the User List.

## Generate a selectable list of Media Portal users {#generating-a-selectable-list-of-media-portal-users}

You can display the names and e-mail addresses of Media Portal users in a pop-up window. This list is useful if you want to cut and paste user names and addresses for use outside Media Portal.

1. Navigate to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. In the **[!UICONTROL By User Role]** drop-down list, choose the name of a Media Portal user role, and select **[!UICONTROL Refresh]** to display the names of one class of Media Portal user.
1. Select **[!UICONTROL Popup List]**. Copy and paste this list.

## Set up the Welcome e-mail message for Media Portal users {#setting-up-the-welcome-e-mail-message-for-media-portal-users}

You can send a Welcome e-mail when you add new Media Portal users, contributors, and contributor-users. You can configure this e-mail message or tell Adobe Dynamic Media Classic not to send it.

1. Navigate to **[!UICONTROL Setup]** > **[!UICONTROL Application Setup]** > **[!UICONTROL Administration Setup]** > **[!UICONTROL User Administration]**.
1. In the User Administration Setup screen, select **[!UICONTROL Email Settings]**.
1. In the Email Settings dialog box, specify any of the following settings:

   * **[!UICONTROL Send Email]** - Deselect this option to inform new users by e-mail that you have signed them up.

   * **[!UICONTROL Default Password]** - Enter a temporary password for new users, or leave the field empty to have Adobe Dynamic Media Classic generate random passwords. Users are asked to change passwords the first time they sign in.

   * **[!UICONTROL Replacement URL]** - Enter a URL different from the default if your users access Adobe Dynamic Media Classic through a different URL.

## Other user management tasks {#other-user-management-tasks}

Starting on the User Administration Setup screen, you can also do these tasks:

* **[!UICONTROL Filter and sort the user list]** - Filter the list of Media Portal users to locate users.

* **[!UICONTROL Delete users]** - Remove a user from the list.

* **[!UICONTROL Activate and deactivate users]** - Suspend a user from accessing folders.

* **[!UICONTROL Edit user information]** - Enter up-to-date information about a user.

* **[!UICONTROL Create user-defined fields]** - Create custom, user-defined metadata fields so they can help you organize assets in the Adobe Dynamic Media Classic. The fields can also be activated or deactivated, as necessary.

See [User-Defined Fields](application-setup.md#user_defined_fields).
