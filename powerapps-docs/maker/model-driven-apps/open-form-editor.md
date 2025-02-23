---
title: "Open the model-driven app form editor in PowerApps | MicrosoftDocs"
ms.custom: ""
ms.date: 06/27/2018
ms.reviewer: ""
ms.service: powerapps
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
  - "powerapps"
author: "Mattp123"
ms.assetid: 8478a07a-c697-4784-874b-36958eb4f95d
caps.latest.revision: 63
ms.author: "matp"
manager: "kvivek"
search.audienceType: 
  - maker
search.app: 
  - PowerApps
  - D365CE
---

# Open the model-driven app form editor 
The form editor is where you design forms by dropping components such as sections, tabs, fields, and controls onto the form editor canvas. In this topic you learn how several different ways to access the form editor.
 
If you create any new solution components in the process of editing the form, for example web resources, the names of the components will use the solution publisher customization prefix for the default solution and these components will only be included in the default solution. If you want any new solution components to be included in a specific unmanaged solution, you should open the form editor through that unmanaged solution.  

## Access the form editor from the PowerApps site

1. Sign in to [PowerApps](https://make.powerapps.com/). 

2. Select **Data** > **Entities** > and then select the entity you want, such as the account entity. 

3. Select the **Forms** tab and then open the form you want, such as the **Account** main form.

## Access the form editor from solution explorer
  
1.  Open [solution explorer](advanced-navigation.md#solution-explorer).
  
2.  Under **Components**, expand **Entities**, and then the entity you want, and click **Forms**.  
  
3.  In the list of forms, click the form you want to edit.  
  

## Access the form editor through the command bar within a model-driven app 
  
1.  Open a record.  
  
2.  If there are multiple main forms for the entity, verify that the form is the one you want to edit. If it isn’t, use the form selector to choose the form you want to edit.  
  
3.  Select the **More Commands** button ![More Commands button in Appointment Activity](media/more-commands.gif "More Commands button in Appointment Activity").  
  
4.  Select **Form Editor**.  

## Access the form editor from within app
  
 You can access the form editor through the command bar or the ribbon, depending on the entity. Both of these methods will open the form in the context of the default solution. 

## Access the form editor for an unmanaged solution  
  
1.  Open [Solutions](advanced-navigation.md#solutions).  
  
2.  Double-click the unmanaged solution you want to work with.  
  
3.  Locate the entity with the form you want to edit. If the entity isn’t there, you’ll need to add it. More information: [Add an entity to an unmanaged solution](#add-an-entity-to-an-unmanaged-solution) 
  
### Add an entity to an unmanaged solution  
  
1.  Select the **Entities** node and, in the toolbar above the list, click **Add Existing**.  
  
2.  In the **Select Solution Components** dialog box, with the **Component Type** selector set to **Entity**, select the entity you want to add and click **OK**.  
  
3.  If the **Missing Required Components** dialog box appears, you can click **No, do not include required components** if you don’t intend to export this unmanaged solution to another environment. If you choose not to include missing required components at this time, you can add them later. You’ll receive notification again if you export this solution in the future.  
  
5.  In the solution explorer expand the entity with the form you want to edit and select **Forms**.  
  
6.  In the list of forms, double-click the form you want to edit.  

## Next steps

[Create and design forms](create-design-forms.md)
