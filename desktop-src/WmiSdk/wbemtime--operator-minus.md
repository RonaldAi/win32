---
Description: 'The WBEMTime class subtraction operator (&\#8211;) has been overloaded to:'
audience: developer
ms.assetid: 0fa51aab-7ea2-4af7-bb12-1646388b0405
ms.tgt_platform: multiple
title: WBEMTime::operator- operators
ms.date: 07/02/2019
ms.topic: article
---

# WBEMTime::operator- operators

\[The [**WBEMTime**](wbemtime.md) class is part of the WMI Provider Framework which is now considered in final state, and no further development, enhancements, or updates will be available for non-security related issues affecting these libraries. The [MI APIs](https://docs.microsoft.com/previous-versions/windows/desktop/wmi_v2/windows-management-infrastructure) should be used for all new development.\]

The [**WBEMTime**](wbemtime.md) class subtraction operator (�) has been overloaded to:

-   Subtract a time span from an object's time to produce a new time object that contains the resulting time.
-   Subtract a time from the object's time to produce a new time span object that contains the difference between the two times.

### Overload list



| Operator                                                                         | Description                                                                      |
|:---------------------------------------------------------------------------------|:---------------------------------------------------------------------------------|
| [**operator-(WBEMTime&)**](https://msdn.microsoft.com/en-us/library/Aa394037(v=VS.85).aspx)         | Subtracts a **WBEMTime** from a **WBEMTime**.<br/>                         |
| [**operator-(WBEMTimeSpan&)**](https://msdn.microsoft.com/en-us/library/Aa394036(v=VS.85).aspx) | Subtracts a [**WBEMTimeSpan**](https://msdn.microsoft.com/en-us/library/Aa393989(v=VS.85).aspx) from a **WBEMTime**.<br/> |



## Requirements



|                                     |                                                                                                                                                               |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista<br/>                                                                                                                                      |
| Minimum supported server<br/> | Windows Server�2008<br/>                                                                                                                                |
| Header<br/>                   | <dl> <dt>WbemTime.h</dt> </dl>                                                                         |
| DLL<br/>                      | <dl> <dt>FrameDynOS.dll; </dt> <dt>FrameDyn.dll</dt> </dl> |



�

�




