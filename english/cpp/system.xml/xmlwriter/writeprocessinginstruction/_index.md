---
title: System::Xml::XmlWriter::WriteProcessingInstruction method
linktitle: WriteProcessingInstruction
second_title: Aspose.TeX for C++
description: 'System::Xml::XmlWriter::WriteProcessingInstruction method. When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: <?name text?> in C++.'
type: docs
weight: 1600
url: /cpp/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction method


When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the processing instruction. |
| text | String | The text to include in the processing instruction. |
## Remarks



This method is being used to create an XML declaration after [XmlWriter::WriteStartDocument](../writestartdocument/) has already been called. 
## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.TeX for C++](../../../)
