---
UID: NF:ocidl.IEnumConnectionPoints.Skip
title: IEnumConnectionPoints::Skip (ocidl.h)
description: Skips over the specified number of items in the enumeration sequence.
old-location: com\ienumconnectionpoints_skip.htm
tech.root: com
ms.assetid: 53080d41-c8b8-46ad-a5f1-6eceb497aa9b
ms.date: 12/05/2018
ms.keywords: IEnumConnectionPoints interface [COM],Skip method, IEnumConnectionPoints.Skip, IEnumConnectionPoints::Skip, Skip, Skip method [COM], Skip method [COM],IEnumConnectionPoints interface, _com_ienumconnectionpoints_skip, com.ienumconnectionpoints_skip, ocidl/IEnumConnectionPoints::Skip
f1_keywords:
- ocidl/IEnumConnectionPoints.Skip
dev_langs:
- c++
req.header: ocidl.h
req.include-header: ObjIdl.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: ObjIdl.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- ocidl.h
api_name:
- IEnumConnectionPoints.Skip
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IEnumConnectionPoints::Skip


## -description


Skips over the specified number of items in the enumeration sequence.


## -parameters




### -param cConnections [in]

The number of items to be skipped.


## -returns



If the method skips the number of items requested, the return value is S_OK. Otherwise, it is S_FALSE.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/ocidl/nn-ocidl-ienumconnectionpoints">IEnumConnectionPoints</a>
 

 

