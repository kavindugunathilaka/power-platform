---
title: "Manage email feature settings | MicrosoftDocs"
description: View and manage feature settings for Common Data Service for Apps.
ms.custom: ""
ms.date: 11/16/2018
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
caps.latest.revision: 31
author: "jimholtz"
ms.author: "jimholtz"
manager: "kvivek"
search.audienceType: 
  - admin
search.app: 
  - Powerplatform
---
# Manage feature settings 

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

Use Feature settings to adjust how Dynamics 365 for Customer Engagement apps features appear and function.

These settings can be found in the Power platform Admin center by going to **Environments** > [select an environment] > **Settings** > **Features**.

Make sure you have the System Administrator or System Customizer security role or equivalent permissions to update the business closures.

**Check your security role**

- Follow the steps in [View your user profile](https://docs.microsoft.com/dynamics365/customer-engagement/basics/view-your-user-profile).
- Don’t have the correct permissions? Contact your system administrator.

## Settings

|Settings|Description|  
|--------------|-----------------|  
|**Embedded content**||  
|Power BI visualization embedding|Default: Off. More information: [Add or edit Power BI visualizations on your dashboard](https://docs.microsoft.com/dynamics365/customer-engagement/basics/add-edit-power-bi-visualizations-dashboard)|  
|Bing Maps|Default: Off. If **On**, Dynamics 365 for Customer Engagement apps (on-premises) users will need to enter a Bing Maps key. Customer Engagement apps users don’t need to enter a key. |  
|Prevent social data in Dynamics|Default: Off. If you don’t want to receive social data in Dynamics 365, select **Off**. If you disable social engagement, your organization will not be able to receive social data in Dynamics 365. Users can continue to work with existing social data, however.|  
|**Communications**| |
|Skype presence|Default: On. If **On**, instant messaging will display the current status for users, contacts, opportunities, or leads. This only applies to lists and sub-lists for entities with an updated user interface.|  
|Enable country/region code prefixing for numbers|Default: On. If **On**, Customer Engagement apps will prefix the country/region code to numbers that users are trying to call.|  
|Set the telephony provider|Default: On. Choose which provider to enable outbound calls from within Dynamics 365. This setting doesn’t apply to Dynamics 365 for tablets or Dynamics 365 for phones.|  
|Use Skype| Default: enabled. [More information: Set up Dynamics 365 (online) to use Skype or Skype for Business](https://docs.microsoft.com/dynamics365/customer-engagement/admin/set-up-skype-or-skype-for-business)|
|Use Skype for Business| Default: not enabled. |
|**Search**||  
|Relevance Search|Default: Off. If **On**, you can use Relevance search to find records across multiple entities, sorted by relevance.|  
|Quick Find record limits|Default: On. If **On**, if more than 10,000 records are found, a message will be displayed that suggests a more selective search. More information: [Configure Relevance search for the organization](https://docs.microsoft.com/dynamics365/customer-engagement/admin/configure-relevance-search-organization)| 
|**Help features**||  
|Custom help for customizable entities|Default: Off. Select **On** to replace the default Help content with custom Help designed for your users. After you enable custom Help, you can enter a Global Custom Help URL.|  
|Global custom help URL| To replace the default Help with a single URL for all customizable record types (entities), enter the URL here. You also have the option of entering override URLs for each record type (entity) for customizable record types. More information: [Create your own guided help](https://docs.microsoft.com/dynamics365/customer-engagement/customize/create-guided-help-learning-path)|  
|Append parameters to URL|Default: Not selected.  Select **On** to append parameters to the URL, you can make your Help content more dynamic. For example, you can access parameters for User Language Code, Entity Name, Entry Point, and Form ID. More information: [Create your own guided help](https://docs.microsoft.com/dynamics365/customer-engagement/customize/create-guided-help-learning-path)|  
|Learning path|Default: Off. Changes access to Learning Path for an entire organization. More information: [On/off switch for Learning Path (guided help)](https://docs.microsoft.com/dynamics365/customer-engagement/admin/on-off-switch-for-learning-path-guided-help).|  
|Learning path authoring|Default: Off. Set to **On** if you want enable users to author Learning Path content. More information: [Create your own guided help (Learning Path) for your customers](https://docs.microsoft.com/dynamics365/customer-engagement/customize/create-guided-help-learning-path)|
|**Auditing**| |
|Audit entities|Default: Off. Start or stop auditing.|  
|Audit user access|Default: Off. If enabled, Customer Engagement apps tracks when the user started accessing Customer Engagement apps and whether or not the user accessed the application by using the web application or Dynamics 365 for Outlook.| 
|Audit read access|Default: Off. | 