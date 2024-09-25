---
title: System::Xml::XmlElement::GetAttributeNode method
linktitle: GetAttributeNode
second_title: Aspose.TeX for C++
description: 'System::Xml::XmlElement::GetAttributeNode method. Returns the XmlAttribute with the specified name in C++.'
type: docs
weight: 2000
url: /cpp/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) method


Returns the [XmlAttribute](../../xmlattribute/) with the specified name.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the attribute to retrieve. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### ReturnValue

The specified [XmlAttribute](../../xmlattribute/) or **nullptr** if a matching attribute was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
## XmlElement::GetAttributeNode(String, String) method


Returns the [XmlAttribute](../../xmlattribute/) with the specified local name and namespace URI.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The specified [XmlAttribute](../../xmlattribute/) or **nullptr** if a matching attribute was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
