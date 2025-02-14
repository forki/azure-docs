---
title: 'Tutorial: Azure AD SSO integration with EAB Navigate Strategic Care'
description: Learn how to configure single sign-on between Azure Active Directory and EAB Navigate Strategic Care.
services: active-directory
author: jeevansd
manager: CelesteDG
ms.reviewer: celested
ms.service: active-directory
ms.subservice: saas-app-tutorial
ms.workload: identity
ms.topic: tutorial
ms.date: 09/20/2021
ms.author: jeedes
---

# Tutorial: Azure AD SSO integration with EAB Navigate Strategic Care

In this tutorial, you'll learn how to integrate EAB Navigate Strategic Care with Azure Active Directory (Azure AD). When you integrate EAB Navigate Strategic Care with Azure AD, you can:

* Control in Azure AD who has access to EAB Navigate Strategic Care.
* Enable your users to be automatically signed-in to EAB Navigate Strategic Care with their Azure AD accounts.
* Manage your accounts in one central location - the Azure portal.

## Prerequisites

To get started, you need the following items:

* An Azure AD subscription. If you don't have a subscription, you can get a [free account](https://azure.microsoft.com/free/).
* EAB Navigate Strategic Care single sign-on (SSO) enabled subscription.

## Scenario description

In this tutorial, you configure and test Azure AD SSO in a test environment.

* EAB Navigate Strategic Care supports **SP** initiated SSO.

> [!NOTE]
> Identifier of this application is a fixed string value so only one instance can be configured in one tenant.

## Add EAB Navigate Strategic Care from the gallery

To configure the integration of EAB Navigate Strategic Care into Azure AD, you need to add EAB Navigate Strategic Care from the gallery to your list of managed SaaS apps.

1. Sign in to the Azure portal using either a work or school account, or a personal Microsoft account.
1. On the left navigation pane, select the **Azure Active Directory** service.
1. Navigate to **Enterprise Applications** and then select **All Applications**.
1. To add new application, select **New application**.
1. In the **Add from the gallery** section, type **EAB Navigate Strategic Care** in the search box.
1. Select **EAB Navigate Strategic Care** from results panel and then add the app. Wait a few seconds while the app is added to your tenant.

## Configure and test Azure AD SSO for EAB Navigate Strategic Care

Configure and test Azure AD SSO with EAB Navigate Strategic Care using a test user called **B.Simon**. For SSO to work, you need to establish a link relationship between an Azure AD user and the related user in EAB Navigate Strategic Care.

To configure and test Azure AD SSO with EAB Navigate Strategic Care, perform the following steps:

1. **[Configure Azure AD SSO](#configure-azure-ad-sso)** - to enable your users to use this feature.
    1. **[Create an Azure AD test user](#create-an-azure-ad-test-user)** - to test Azure AD single sign-on with B.Simon.
    1. **[Assign the Azure AD test user](#assign-the-azure-ad-test-user)** - to enable B.Simon to use Azure AD single sign-on.
1. **[Configure EAB Navigate Strategic Care SSO](#configure-eab-navigate-strategic-care-sso)** - to configure the single sign-on settings on application side.
    1. **[Create EAB Navigate Strategic Care test user](#create-eab-navigate-strategic-care-test-user)** - to have a counterpart of B.Simon in EAB Navigate Strategic Care that is linked to the Azure AD representation of user.
1. **[Test SSO](#test-sso)** - to verify whether the configuration works.

## Configure Azure AD SSO

Follow these steps to enable Azure AD SSO in the Azure portal.

1. In the Azure portal, on the **EAB Navigate Strategic Care** application integration page, find the **Manage** section and select **single sign-on**.
1. On the **Select a single sign-on method** page, select **SAML**.
1. On the **Set up single sign-on with SAML** page, click the pencil icon for **Basic SAML Configuration** to edit the settings.

   ![Edit Basic SAML Configuration](common/edit-urls.png)

1. On the **Basic SAML Configuration** section, perform the following step:

    In the **Sign-on URL** text box, type a URL using the following pattern:
    `https://<CUSTOMERURL>.eab.com`

	> [!NOTE]
	> The value is not real. Update the value with the actual Sign-On URL. Contact [EAB Navigate Strategic Care Client support team](mailto:tech@gradesfirst.com) to get the value. You can also refer to the patterns shown in the **Basic SAML Configuration** section in the Azure portal.

1. On the **Set up single sign-on with SAML** page, In the **SAML Signing Certificate** section, click the copy button to copy **App Federation Metadata Url** and save it on your computer.

	![The Certificate download link](common/copy-metadataurl.png)

### Create an Azure AD test user

In this section, you'll create a test user in the Azure portal called B.Simon.

1. From the left pane in the Azure portal, select **Azure Active Directory**, select **Users**, and then select **All users**.
1. Select **New user** at the top of the screen.
1. In the **User** properties, follow these steps:
   1. In the **Name** field, enter `B.Simon`.  
   1. In the **User name** field, enter the username@companydomain.extension. For example, `B.Simon@contoso.com`.
   1. Select the **Show password** check box, and then write down the value that's displayed in the **Password** box.
   1. Click **Create**.

### Assign the Azure AD test user

In this section, you'll enable B.Simon to use Azure single sign-on by granting access to EAB Navigate Strategic Care.

1. In the Azure portal, select **Enterprise Applications**, and then select **All applications**.
1. In the applications list, select **EAB Navigate Strategic Care**.
1. In the app's overview page, find the **Manage** section and select **Users and groups**.
1. Select **Add user**, then select **Users and groups** in the **Add Assignment** dialog.
1. In the **Users and groups** dialog, select **B.Simon** from the Users list, then click the **Select** button at the bottom of the screen.
1. If you're expecting any role value in the SAML assertion, in the **Select Role** dialog, select the appropriate role for the user from the list and then click the **Select** button at the bottom of the screen.
1. In the **Add Assignment** dialog, click the **Assign** button.

## Configure EAB Navigate Strategic Care SSO

To configure single sign-on on **EAB Navigate Strategic Care** side, you need to send the **App Federation Metadata Url** to [EAB Navigate Strategic Care support team](mailto:tech@gradesfirst.com). They set this setting to have the SAML SSO connection set properly on both sides.

### Create EAB Navigate Strategic Care test user

In this section, you create a user called B.Simon in EAB Navigate Strategic Care. Work with [EAB Navigate Strategic Care support team](mailto:tech@gradesfirst.com) to add the users in the EAB Navigate Strategic Care platform. Users must be created and activated before you use single sign-on.

## Test SSO 

In this section, you test your Azure AD single sign-on configuration with following options. 

* Click on **Test this application** in Azure portal. This will redirect to EAB Navigate Strategic Care Sign-on URL where you can initiate the login flow. 

* Go to EAB Navigate Strategic Care Sign-on URL directly and initiate the login flow from there.

* You can use Microsoft My Apps. When you click the EAB Navigate Strategic Care tile in the My Apps, this will redirect to EAB Navigate Strategic Care Sign-on URL. For more information about the My Apps, see [Introduction to the My Apps](../user-help/my-apps-portal-end-user-access.md).

## Next steps

Once you configure EAB Navigate Strategic Care you can enforce session control, which protects exfiltration and infiltration of your organization’s sensitive data in real time. Session control extends from Conditional Access. [Learn how to enforce session control with Microsoft Cloud App Security](/cloud-app-security/proxy-deployment-aad).