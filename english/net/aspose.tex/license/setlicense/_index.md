---
title: License.SetLicense
second_title: Aspose.TeX for .NET API Reference
description: License method. Licenses the component
type: docs
weight: 30
url: /net/aspose.tex/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenses the component.

```csharp
public void SetLicense(string licenseName)
```

## Remarks

Tries to find the license in the following locations:

1. Explicit path.

2. The folder of the component assembly.

3. The folder of the client's calling assembly.

4. The folder of the entry assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

2. The folder of the component jar file.

## Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains  the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

the component jar file:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode.

### See Also

* class [License](../)
* namespace [Aspose.TeX](../../license/)
* assembly [Aspose.TeX](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenses the component.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream that contains the license. |

## Remarks

Use this method to load a license from a stream.

## Examples

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### See Also

* class [License](../)
* namespace [Aspose.TeX](../../license/)
* assembly [Aspose.TeX](../../../)


