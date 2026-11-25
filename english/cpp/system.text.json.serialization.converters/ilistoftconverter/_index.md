---
title: System::Text::Json::Serialization::Converters::IListOfTConverter class
linktitle: IListOfTConverter
second_title: Aspose.TeX for C++
description: 'How to use System::Text::Json::Serialization::Converters::IListOfTConverter class in C++.'
type: docs
weight: 2300
url: /cpp/system.text.json.serialization.converters/ilistoftconverter/
---
## IListOfTConverter class




```cpp
template<typename TCollection,typename TElement>class IListOfTConverter : public System::Text::Json::Serialization::Converters::IEnumerableDefaultConverter<TCollection, TElement>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [IEnumerableDefaultConverter](../ienumerabledefaultconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.TeX for C++](../../)
