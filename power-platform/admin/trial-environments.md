---
title: Trial environments | Microsoft Docs
description: Get early access to functionalities with Power Apps Preview Program
author: jimholtz
ms.reviewer: manasmams
manager: kvivek
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 10/15/2019
ms.author: jimholtz
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---

# About trial environments

Currently, you can create two types of Common Data Service environments: trial or production. A trial environment is useful for trying out model-driven apps in Dynamics 365, such as Dynamics 365 Sales and Customer Service, at no cost. Trial environments expire after 30 days.

Open the **Environments** page to see the environment types you have and the upcoming expiration date for trial environments:

> [!div class="mx-imgBorder"] 
> ![Power Apps environments](media/powerapps-environments75b.png "Power Apps environments")

## Convert a trial environment to production

While using the trial environment, if you created resources you want to retain longer than 30 days, convert the trial to a production environment.

If you have 1GB of available database capacity, you can convert a trial environment to production. You might need to free up or purchase additional capacity if the trial database exceeds 1GB. To determine the size of the trial database see: [Common Data Service storage capacity](capacity-storage.md).

Follow these steps to convert a trial environment to a production environment:

1. Go to [https://admin.powerapps.com/environments](https://admin.powerapps.com/environments), and sign in as an admin.
 
2. Open the **Environments** page, and select the trial environment you want to convert to production:

    > [!div class="mx-imgBorder"] 
    > ![Select trial environment](media/powerapps-environments75b-select-trial.png "Select trial environment")

3. On the **Details** tab, select **Convert**:

    > [!div class="mx-imgBorder"] 
    > ![Select Convert](media/powerapps-trial-select-convert.png "Select Convert")

4. Select **Confirm**:

    > [!div class="mx-imgBorder"] 
    > ![Select Confirm](media/powerapps-trial-select-confirm.png "Select Confirm")

If your environment has a database, it might take several hours to convert to a production environment. You can monitor the progress through the notification on the **Details** tab:

  > [!div class="mx-imgBorder"] 
  > ![Conversion started](media/powerapps-trial-conversion-started.png "Conversion started")

## Frequently asked questions

### Who can convert a trial environment to a production environment?

If you have 1GB of available database capacity, you can convert a trial environment to production. You might need to free up or purchase additional capacity if the trial database exceeds 1GB. To determine the size of the trial database see: [Common Data Service storage capacity](capacity-storage.md).

### What if I don’t have available quota for production environments?

Contact your Office 365 Global admin or Azure Active Directory (Azure AD) tenant admin to:
- Assign a Power Apps plan to you. 
- Locate another user who has available production environment quota.

You can also purchase a Power Apps plan.

### Can every Office 365 Global admin or Azure AD tenant admin convert a trial environment to a production environment?

No. Global admins and Azure AD tenant admins need to have available quota for production environments to be able to convert a trial environment to a production environment.

### How can I retain my data and resources if I don’t have a way to convert the trial environment to a production environment?

You can export your resources and data to another environment. If you want to retain them for a longer time, we recommend you create a production environment or an individual environment (with Power Apps Community Plan) and export your resources to that environment. 

Here are some guidelines for exporting resources.

|Type of resource in the environment  |How do I export it?  |
|---------|---------|
|Apps (canvas and model-driven) and flows     |You can use [packaging](environment-and-tenant-migration.md) to export apps and flows from one environment.         |
|Data in the database (Common Data Service environment)     |You have multiple options:<br/><ul><li>[Export to Excel](/powerapps/user/export-data-excel) and save the data. You can [import the data](/powerapps/user/import-data) into another environment.</li><br/><li>You can use [Data Integrator services](data-integrator.md) and APIs to export data into another environment.</li></ul> |

We delete trial environments that haven’t had any activity in the environment databases for 30 days.

### How can I create a production or an individual environment?

You need to have a Power Apps plan that provides production environment creation. <!-- For more information, see [Creating an environment](environments-overview.md#creating-an-environment). -->

You can create an individual environment by signing up for the [Power Apps Community Plan](https://powerapps.microsoft.com/communityplan/). Note that there are restrictions on sharing apps in individual environments—these environments are meant for personal use only.

### How do I identify my plan(s)?

To determine your plan(s), select the **Gear** icon (![Gear icon](media/selection-rule-gear-button.png)) in the upper-right corner of the Power Apps site, and then select **Plan(s)**.

> [!div class="mx-imgBorder"] 
> ![Select Plans](media/powerapps-plans.png "Select Plans")

### See also
[Administer environments in Power Apps](environments-administration.md)<br/>
[Environments overview](environments-overview.md)<br/>
[Choose the right plans for your team](https://powerapps.microsoft.com/pricing/)<br/>
[Licensing overview](pricing-billing-skus.md)<br/>
