---
title: "edgeCookiePolicy enum type"
description: "Possible values to specify which cookies are allowed in Microsoft Edge."
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: enumPageType
ms.date: 08/01/2024
---

# edgeCookiePolicy enum type

Namespace: microsoft.graph

> **Important:** Microsoft supports Intune /beta APIs, but they are subject to more frequent change. Microsoft recommends using version v1.0 when possible. Check an API's availability in version v1.0 using the Version selector.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Possible values to specify which cookies are allowed in Microsoft Edge.

## Members
|Member|Value|Description|
|:---|:---|:---|
|userDefined|0|Allow the user to set.|
|allow|1|Allow.|
|blockThirdParty|2|Block only third party cookies.|
|blockAll|3|Block all cookies.|