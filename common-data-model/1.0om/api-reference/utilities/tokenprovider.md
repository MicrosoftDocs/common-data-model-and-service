---
title: Token Provider | Microsoft Docs
description: API reference for TokenProvider.
author: yidi

ms.reviewer: deonhe 
ms.topic: article
ms.date: 02/25/2020
ms.author: yidi
---

# Token Provider

This is the interface to be implemented by users to provision their customized token provider.

```csharp
public interface TokenProvider
```
*This interface is substituted with a regular class in Python.*

## Methods
|Name|Description|Return Type|
|---|---|---|
|**GetToken()**|Returns the token string with the authentication type included (for example, "Bearer XXXXX"). It's expected that the returned token has been validated for expiration upfront by the implementer of the interface. The audience for the token should be set as granular as possible, including limiting permissions to only read or write depending on the intent.|string|
