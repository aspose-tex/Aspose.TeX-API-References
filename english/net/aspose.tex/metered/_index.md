---
title: Class Metered
second_title: Aspose.TeX for .NET API Reference
description: Aspose.TeX.Metered class. Provides methods to set metered key
type: docs
weight: 310
url: /net/aspose.tex/metered/
---
## Metered class

Provides methods to set metered key.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [SetMeteredKey](../../aspose.tex/metered/setmeteredkey/)(string, string) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| static [GetConsumptionCredit](../../aspose.tex/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../aspose.tex/metered/getconsumptionquantity/)() | Gets consumption file size |

## Examples

In this example, an attempt will be made to set metered public and private key

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### See Also

* namespace [Aspose.TeX](../../aspose.tex/)
* assembly [Aspose.TeX](../../)


