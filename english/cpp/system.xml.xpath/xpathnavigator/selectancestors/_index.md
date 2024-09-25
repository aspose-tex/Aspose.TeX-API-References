---
title: System::Xml::XPath::XPathNavigator::SelectAncestors method
linktitle: SelectAncestors
second_title: Aspose.TeX for C++
description: 'System::Xml::XPath::XPathNavigator::SelectAncestors method. Selects all the ancestor nodes of the current node that have a matching XPathNodeType in C++.'
type: docs
weight: 6600
url: /cpp/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Selects all the ancestor nodes of the current node that have a matching XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The XPathNodeType of the ancestor nodes. |
| matchSelf | bool | To include the context node in the selection, **true**; otherwise, **false**. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes. The returned nodes are in reverse document order.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.TeX for C++](../../../)
## XPathNavigator::SelectAncestors(String, String, bool) method


Selects all the ancestor nodes of the current node that have the specified local name and namespace URI.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the ancestor nodes. |
| namespaceURI | String | The namespace URI of the ancestor nodes. |
| matchSelf | bool | To include the context node in the selection, **true**; otherwise, **false**. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes. The returned nodes are in reverse document order.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.TeX for C++](../../../)
