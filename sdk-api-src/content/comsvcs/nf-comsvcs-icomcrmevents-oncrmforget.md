---
UID: NF:comsvcs.IComCRMEvents.OnCRMForget
title: IComCRMEvents::OnCRMForget (comsvcs.h)
description: Generated when a CRM clerk receives a request to forget a log record, either from the CRM worker or from the CRM compensator.
old-location: cos\icomcrmevents_oncrmforget.htm
tech.root: cossdk
ms.assetid: 2e6c5bb1-aa99-434a-9376-c853b1fb1d12
ms.date: 12/05/2018
ms.keywords: IComCRMEvents interface [COM+],OnCRMForget method, IComCRMEvents.OnCRMForget, IComCRMEvents::OnCRMForget, OnCRMForget, OnCRMForget method [COM+], OnCRMForget method [COM+],IComCRMEvents interface, _dtc_IComCRMEvents_OnCRMForget, comsvcs/IComCRMEvents::OnCRMForget, cos.icomcrmevents_oncrmforget
f1_keywords:
- comsvcs/IComCRMEvents.OnCRMForget
dev_langs:
- c++
req.header: comsvcs.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
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
- ComSvcs.h
api_name:
- IComCRMEvents.OnCRMForget
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IComCRMEvents::OnCRMForget


## -description


Generated when a CRM clerk receives a request to forget a log record, either from the CRM worker or from the CRM compensator.


## -parameters




### -param pInfo [in]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/comsvcs/ns-comsvcs-comsvcseventinfo">COMSVCSEVENTINFO</a> structure.


### -param guidClerkCLSID [in]

The identifier of the CRM clerk.


## -returns



The user verifies the return values from this method.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/comsvcs/nn-comsvcs-icomcrmevents">IComCRMEvents</a>
 

 

