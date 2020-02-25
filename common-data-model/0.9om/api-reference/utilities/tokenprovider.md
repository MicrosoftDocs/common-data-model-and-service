---
title: Token Provider | Microsoft Docs
description: API reference for ResolveOptions.
author: yidi
ms.service: common-data-model
ms.reviewer: deonhe 
ms.topic: article
ms.date: 02/25/2020
ms.author: yidi
---

# Token Provider

This is the interface to be implemented by users to encapsulate their customized token provider.

```
public interface TokenProvider
```
*TokenProvider is a class in Python.*

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetToken()**|Returns the token string with the authentication type included, e.g. "Bearer XXXXX". It is expected that the returned token has been validated for expiration upfront by the implementer of the interface.|string|
