---
Description: Sets the security of an open registry key in an offline registry hive.
ms.assetid: 002866bb-1532-41ad-a4db-a32d6e1c0a6a
title: ORSetKeySecurity function
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- ORSetKeySecurity
api_type: 
- DllExport
api_location: 
- Offreg.dll
---

# ORSetKeySecurity function

Sets the security of an open registry key in an offline registry hive.

## Syntax


```C++
DWORD ORSetKeySecurity(
  _In_ ORHKEY               Handle,
  _In_ SECURITY_INFORMATION SecurityInformation,
  _In_ PSECURITY_DESCRIPTOR pSecurityDescriptor
);
```



## Parameters

<dl> <dt>

*Handle* \[in\]
</dt> <dd>

A handle to an open registry key in an offline registry hive.

</dd> <dt>

*SecurityInformation* \[in\]
</dt> <dd>

Bit flags that indicate the type of security information to set. This parameter can be a combination of the [SECURITY\_INFORMATION](https://go.microsoft.com/fwlink/p/?linkid=128774) bit flags.

</dd> <dt>

*pSecurityDescriptor* \[in\]
</dt> <dd>

A pointer to a [SECURITY\_DESCRIPTOR](https://go.microsoft.com/fwlink/p/?linkid=128770) structure that specifies the security attributes to set for the specified key.

</dd> </dl>

## Return value

If the function succeeds, the function returns ERROR\_SUCCESS.

If the function fails, it returns a nonzero error code defined in Winerror.h. You can use the [FormatMessage](https://go.microsoft.com/fwlink/p/?linkid=128767) function with the FORMAT\_MESSAGE\_FROM\_SYSTEM flag to get a generic description of the error.

## Requirements



|                            |                                                                                       |
|----------------------------|---------------------------------------------------------------------------------------|
| Redistributable<br/> | Windows Offline Registry library version 1.0 or later<br/>                      |
| Header<br/>          | <dl> <dt>Offreg.h</dt> </dl>   |
| DLL<br/>             | <dl> <dt>Offreg.dll</dt> </dl> |



## See also

<dl> <dt>

[**ORCloseKey**](orclosekey.md)
</dt> <dt>

[**ORDeleteKey**](ordeletekey.md)
</dt> <dt>

[**OROpenKey**](oropenkey.md)
</dt> <dt>

[**ORGetKeySecurity**](orgetkeysecurity.md)
</dt> <dt>

[SECURITY\_DESCRIPTOR](https://go.microsoft.com/fwlink/p/?linkid=128770)
</dt> <dt>

[SECURITY\_INFORMATION](https://go.microsoft.com/fwlink/p/?linkid=128774)
</dt> </dl>

 

 




