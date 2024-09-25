---
title: System::Xml::XmlSignificantWhitespace::CloneNode method
linktitle: CloneNode
second_title: Aspose.TeX for C++
description: 'System::Xml::XmlSignificantWhitespace::CloneNode method. Creates a duplicate of this node in C++.'
type: docs
weight: 700
url: /cpp/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| deep | bool | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For significant white space nodes, the cloned node always includes the data value, regardless of the parameter setting. |

### ReturnValue

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
