---
title: ID3DX11EffectRasterizerVariable UndoSetRasterizerState method
description: Reverts a previously set rasterizer state.
ms.assetid: 2801479c-cb70-4950-9888-73e271b669aa
keywords:
- UndoSetRasterizerState method Direct3D 11
- UndoSetRasterizerState method Direct3D 11 , ID3DX11EffectRasterizerVariable interface
- ID3DX11EffectRasterizerVariable interface Direct3D 11 , UndoSetRasterizerState method
topic_type:
- apiref
api_name:
- ID3DX11EffectRasterizerVariable.UndoSetRasterizerState
api_location:
- N/A
- N/A.dll
api_type:
- COM
ms.topic: article
ms.date: 05/31/2018
---

# ID3DX11EffectRasterizerVariable::UndoSetRasterizerState method

Reverts a previously set rasterizer state.

## Syntax


```C++
HRESULT UndoSetRasterizerState(
   UINT Index
);
```



## Parameters

<dl> <dt>

*Index* 
</dt> <dd>

Type: **[**UINT**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)**

Index into an array of rasterizer interfaces. If there is only one rasterizer interface, use 0.

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/en-us/library/Bb401631(v=MSDN.10).aspx)**

Returns one of the following [Direct3D 11 Return Codes](d3d11-graphics-reference-returnvalues.md).

## Remarks

> [!Note]  
> The DirectX SDK does not supply any compiled binaries for effects. You must use Effects 11 source to build your effects-type application. For more information about using Effects 11 source, see [Differences Between Effects 10 and Effects 11](d3d11-graphics-programming-guide-effects-differences.md).

 

## Requirements



|                    |                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx11effect.h</dt> </dl>                                                    |
| Library<br/> | <dl> <dt>N/A (An Effects 11 library is available online as shared source.)</dt> </dl> |



## See also

<dl> <dt>

[ID3DX11EffectRasterizerVariable](id3dx11effectrasterizervariable.md)
</dt> </dl>

 

 





