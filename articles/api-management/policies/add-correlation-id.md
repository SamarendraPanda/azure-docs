---
title: Azure API managment policy sample - Add a header containing a correlation id | Microsoft Docs
description: Azure API managment policy sample - Demonstrates how to add a header containing a correlation id to the inbound request.
services: api-management
documentationcenter: ''
author: vladvino
manager: cfowler
editor: ''

ms.service: api-management
ms.workload: mobile
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 10/13/2017
ms.author: apimpm
---

# Add a header containing a correlation id

This article shows an Azure API management policy sample that demonstrates how to add a header containing a correlation id to the inbound request. To set or edit a policy code, follow the steps described in [Set or edit a policy](../set-edit-policies.md). To see other examples, see [policy samples](../policy-samples.md).

## Policy

Paste the code into the **inbound** block.

[!code-xml[Main](../../../api-management-policy-samples/Snippets/Add correlation id to inbound request.policy.xml)]

## Next steps

Learn more about APIM policies:

+ [Transformation policies](../api-management-transformation-policies.md)
+ [Policy samples](../policy-samples.md)

