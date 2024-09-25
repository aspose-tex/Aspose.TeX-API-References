---
title: System::Xml::XPath::XPathNavigator::MoveToNamespace method
linktitle: MoveToNamespace
second_title: Aspose.TeX for C++
description: 'System::Xml::XPath::XPathNavigator::MoveToNamespace method. Moves the XPathNavigator to the namespace node with the specified namespace prefix in C++.'
type: docs
weight: 4300
url: /cpp/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace method


Moves the [XPathNavigator](../) to the namespace node with the specified namespace prefix.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The namespace prefix of the namespace node. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the specified namespace; **false** if a matching namespace node was not found, or if the [XPathNavigator](../) is not positioned on an element node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.TeX for C++](../../../)
