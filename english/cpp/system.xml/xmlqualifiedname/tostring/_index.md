---
title: System::Xml::XmlQualifiedName::ToString method
linktitle: ToString
second_title: Aspose.TeX for C++
description: 'System::Xml::XmlQualifiedName::ToString method. Returns the string value of the XmlQualifiedName in C++.'
type: docs
weight: 700
url: /cpp/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const method


Returns the string value of the [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### ReturnValue

The string value of the [XmlQualifiedName](../) in the format of **namespace:localname**. If the object does not have a namespace defined, this method returns just the local name.

## See Also

* Class [String](../../../system/string/)
* Class [XmlQualifiedName](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
## XmlQualifiedName::ToString(const String\&, const String\&) method


Returns the string value of the [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the object. |
| ns | const String\& | The namespace of the object. |

### ReturnValue

The string value of the [XmlQualifiedName](../) in the format of **namespace:localname**. If the object does not have a namespace defined, this method returns just the local name.

## See Also

* Class [String](../../../system/string/)
* Class [XmlQualifiedName](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
