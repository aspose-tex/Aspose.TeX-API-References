---
title: System::Nullable::Equals method
linktitle: Equals
second_title: Aspose.TeX for C++
description: 'System::Nullable::Equals method. Determines if the value represented by the current object is equal to the value represented by the specified Nullable object in C++.'
type: docs
weight: 1000
url: /cpp/system/nullable/equals/
---
## Nullable::Equals method


Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the [Nullable](../) object to compare with |

### ReturnValue

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.TeX for C++](../../../)
