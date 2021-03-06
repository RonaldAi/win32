---
title: EAP Frequently Asked Questions
description: Provides answers to commonly-asked questions about the EAP APIs.
ms.assetid: 4e26df7b-3cce-4522-ab39-e24f06b4c4b4
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# EAP Frequently Asked Questions

The following topic provides answers to commonly-asked questions about the EAP APIs.



| Question                                                                                        | Answer                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| What is the lifetime of an EAP authentication?                                                  | In a typical situation the authentication consists of everything that occurs between calling the [**RapEapBegin**](https://msdn.microsoft.com/en-us/library/Aa363520(v=VS.85).aspx) and [**RasEapEnd**](https://msdn.microsoft.com/en-us/library/Aa363521(v=VS.85).aspx) functions. When a user chooses to configure an EAP provider in the RRAS snap-in, an authentication consists of everything that occurs between calling the [**Initialize**](/previous-versions/windows/desktop/api/Rrascfg/nf-rrascfg-ieapproviderconfig-initialize) and [**Uninitialize**](/previous-versions/windows/desktop/api/Rrascfg/nf-rrascfg-ieapproviderconfig-uninitialize) methods.<br/> |
| What is "group policy"?                                                                         | For a description of group policy, see [Group Policy Collection](Http://go.microsoft.com/fwlink/p/?linkid=84005).                                                                                                                                                                                                                                                                                                                                                    |
| Can EAP functions override configuration policy specified by group policy?                      | No, never. If group policy is in use, group policy settings will always override EAP configuration settings.                                                                                                                                                                                                                                                                                                                                                         |
| I need to warn users about invalid PIN attempts. Is it possible to capture an invalid pin code? | When the user enters the wrong PIN, Extensible Authentication Protocol-Transport Layer Security (EAP-TLS) will send an error codes to the VPN supplicant. Once an error code is returned, the supplicant can implement its preferred retry logic.                                                                                                                                                                                                                    |
| What is EAP-Transport Level Security (EAP-TLS)?                                                 | EAP-TLS is a client-server protocol in which distinct certificate profiles are typically used for the client and server.For more information, see [IETF RTC 2716](Http://go.microsoft.com/fwlink/p/?linkid=83935).<br/>                                                                                                                                                                                                                                        |



 

## Related topics

<dl> <dt>

[Using Extensible Authentication Protocol](using-extenstible-authentication-protocol.md)
</dt> </dl>

 

 





