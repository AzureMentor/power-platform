---
title: "Supported web browsers and mobile devices  | MicrosoftDocs"
description: Supported web browsers and mobile devices 
author: jimholtz
manager: kvivek
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 11/21/2020
ms.author: jimholtz
search.audienceType: 
  - admin
search.app:
  - D365CE
  - PowerApps
  - Powerplatform
  - Flow
---
# Supported web browsers and mobile devices

Users can access the model-driven apps with the most recent versions of these popular browsers:  
  
- Microsoft Edge (recommended: [Chromium-based Edge](https://support.microsoft.com/help/4501095/download-the-new-microsoft-edge-based-on-chromium))
- Chrome
- Firefox  
- Safari
- Internet Explorer (not recommended)

> [!TIP]
> For optimal performance and experience, we recommend you use the latest version of a modern browser. 
  
For more detailed information about supported browsers, see [Web application requirements](web-application-requirements.md).  
  
For a mobile device, such as an iPad or smartphone, the following apps are available for model-driven apps and Dynamics 365 apps (such as Dynamics 365 Sales and Dynamics 365 Marketing):

- [Power Apps mobile](/powerapps/user/run-canvas-and-model-apps-on-mobile) app  
- [Dynamics 365 for phones and Dynamics 365 for tablets](https://docs.microsoft.com/dynamics365/mobile-app/install-dynamics-365-for-phones-and-tablets)
  
> [!NOTE]
> - Users who try to view model-driven apps on an unsupported browser are redirected to the Unified Interface experience. For more information, see [Unified Interface Overview](about-unified-interface.md).  
> -  If you have added content to forms or dashboards in an iFrame, you might have implemented security restrictions around certain actions in that content, such as external links. Keep in mind that in [!INCLUDE[tn_Firefox](../includes/tn-firefox.md)], this security restriction code will likely be unsupported.  
  
<a name="BKMK_browserIssues"></a>   
## Known issues when you run model-driven apps with certain web browsers  
 This section describes the known issues when you run model-driven apps in a web browser.  
  
### Limited copy and paste support in Firefox and Chrome  
 Copy and paste functionality by using the clipboard is not yet fully supported on the [!INCLUDE[tn_Firefox](../includes/tn-firefox.md)] and [!INCLUDE[tn_chrome](../includes/tn-chrome.md)] web browsers; the **Copy a Link** button at the top of the page may not function as expected.  
  
### You receive an error opening an Excel worksheet when you use Safari  
 If you export an [!INCLUDE[pn_MS_Excel_Full](../includes/pn-ms-excel-full.md)] worksheet as a Dynamic Worksheet while using [!INCLUDE[tn_Safari](../includes/tn-safari.md)], you may receive an error when trying to open the file. To remedy this, right-click the file, click **Get Info**, and, under **Open With**, select [!INCLUDE[pn_Excel_short](../includes/pn-excel-short.md)].  
  
### See Also  
 [Supported web browsers and mobile devices - earlier versions](https://technet.microsoft.com/library/dn531055.aspx)
