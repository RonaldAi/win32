---
Description: Retrieves a Boolean value that indicates whether the dataEncipherment bit is set.
ms.assetid: 9b29a76f-1494-4db3-a5d7-69fe631ca1dd
title: KeyUsage.IsDataEnciphermentEnabled property
ms.topic: article
ms.date: 05/31/2018
topic_type:
- APIRef
- kbSyntax
api_name:
- KeyUsage.IsDataEnciphermentEnabled
api_type:
- COM
api_location:
- Capicom.dll
---

# KeyUsage.IsDataEnciphermentEnabled property

\[The **IsDataEnciphermentEnabled** property is available for use in the operating systems specified in the Requirements section. Instead, use the [**X509EnhancedKeyUsageExtension Class**](https://msdn.microsoft.com/library/6f6fz8xs(v=VS.100).aspx) in the [**System.Security.Cryptography.X509Certificates**](https://msdn.microsoft.com/library/73091bzx(v=VS.71).aspx) namespace.\]

The **IsDataEnciphermentEnabled** property retrieves a Boolean value that indicates whether the dataEncipherment bit is set.

## Syntax


```VB
KeyUsage.IsDataEnciphermentEnabled As Boolean
```



## Property value

If **true**, the dataEncipherment bit is set.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**KeyUsage**](keyusage.md)
</dt> </dl>

 

 




