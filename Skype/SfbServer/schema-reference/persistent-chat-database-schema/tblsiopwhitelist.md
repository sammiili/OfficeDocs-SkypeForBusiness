---
title: "tblSiopWhiteList"
ms.reviewer: 
ms.author: v-mahoffman
author: HowlinWolf-92
manager: serdars
ms.date: 3/9/2015
audience: ITPro
ms.topic: article
ms.prod: skype-for-business-itpro
f1.keywords:
- NOCSH
ms.localizationpriority: medium
ms.assetid: 05fc1df4-32eb-4d46-9d1c-e0b607091142
description: "tblSiopWhiteList is the list of registered add-ins that can be associated with nodes."
---

# tblSiopWhiteList
 
tblSiopWhiteList is the list of registered add-ins that can be associated with nodes.
  
**Columns**

|**Column**|**Type**|**Description**|
|:-----|:-----|:-----|
|siopID  <br/> |GUID, not null  <br/> |GUID of the add-in.  <br/> |
|siopName  <br/> |nvarchar (50), not null  <br/> |Display-name of the add-in.  <br/> |
|siopUrl  <br/> |nvarchar (255), not null  <br/> |URL of the add-in.  <br/> |
   
**Key**

|**Column**|**Description**|
|:-----|:-----|
|siopID  <br/> |Primary key.  <br/> |
   

