---
title: overview - Common Data Model | Microsoft Docs
description: core is a folder that contains standard entities related to the Common Data Model.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Preferred way to get OM library


## Nuget

1. Connect to CDM feed -https://commondatamodel.pkgs.visualstudio.com/_packaging/CDM/nuget/v3/index.json 
2. OM library is available in package Microsoft.CommonDataModel.ObjectModel 

## NPM

1. Add this feed to your project's .npmrc.

registry=https://commondatamodel.pkgs.visualstudio.com/_packaging/CDM/npm/registry/
always-auth=true

2. OM library is available in package cdm.objectmodel 

# Repos

<a href = "https://commondatamodel.visualstudio.com/CDM/_git/CDM.SchemaDocuments?version=GBfeatures%2Fcdm0.9">CDM.SchemaDocuments</a> – foundational types and Standard Entity Schema 

<a href = "https://commondatamodel.visualstudio.com/CDM/_git/CDM.ObjectModel.CSharp?version=GBfeatures%2Fcdm0.9">CDM.ObjectModel.CSharp</a> – contains the C# source code for the OM 

<a href = "https://commondatamodel.visualstudio.com/CDM/_git/CDM.ObjectModel.TS?version=GBfeatures%2Fcdm0.9">CDM.ObjectModel.TS</a> – contains the Typescript source code for the OM 

<a href = "https://commondatamodel.visualstudio.com/CDM/_git/CDM.Tools.Public?version=GBfeatures%2Fcdm0.9">CDM.Tools.Public</a> – set of public tools and SDK samples 


