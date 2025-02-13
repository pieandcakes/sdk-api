---
UID: NF:tapi3if.ITTAPI.get_Addresses
title: ITTAPI::get_Addresses (tapi3if.h)
description: The get_Addresses method creates a collection of addresses that are currently available. Provided for Automation client applications, such as those written in Visual Basic. C and C++ applications must use the EnumerateAddresses method.
old-location: tapi3\ittapi_get_addresses.htm
tech.root: Tapi
ms.assetid: 9e70ae94-20a2-4ba4-ab39-794f611011d8
ms.date: 12/05/2018
ms.keywords: ITTAPI interface [TAPI 2.2],get_Addresses method, ITTAPI.get_Addresses, ITTAPI::get_Addresses, _tapi3_ittapi_get_addresses, get_Addresses, get_Addresses method [TAPI 2.2], get_Addresses method [TAPI 2.2],ITTAPI interface, tapi3.ittapi_get_addresses, tapi3if/ITTAPI::get_Addresses
f1_keywords:
- tapi3if/ITTAPI.get_Addresses
dev_langs:
- c++
req.header: tapi3if.h
req.include-header: Tapi3.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Uuid.lib
req.dll: Tapi3.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Tapi3.dll
api_name:
- ITTAPI.get_Addresses
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITTAPI::get_Addresses


## -description


The 
<b>get_Addresses</b> method creates a collection of addresses that are currently available. Provided for Automation client applications, such as those written in Visual Basic. C and C++ applications must use the 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nf-tapi3if-ittapi-enumerateaddresses">EnumerateAddresses</a> method.


## -parameters




### -param pVariant [out]

Pointer to a <b>VARIANT</b> containing an 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itcollection">ITCollection</a> of 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itaddress">ITAddress</a> interface pointers (address objects).


## -returns



This method can return one of these values.

<table>
<tr>
<th>Value</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
The <i>pVariant</i> parameter is not valid.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Insufficient memory exists to perform the operation.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
The <i>pVariant</i> parameter is not a valid pointer.

</td>
</tr>
</table>
 




## -remarks



TAPI calls the <b>Addref</b> method on the 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itaddress">ITAddress</a> interface returned by <b>ITTAPI::get_Addesses</b>. The application must call <b>Release</b> on the 
<b>ITAddress</b> interface to free resources associated with it.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nf-tapi3if-ittapi-enumerateaddresses">EnumerateAddresses</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-ienumaddress">IEnumAddress</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itaddress">ITAddress</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itcollection">ITCollection</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-ittapi">ITTAPI</a>



<a href="https://docs.microsoft.com/windows/desktop/Tapi/tapi-object">TAPI Object</a>
 

 

