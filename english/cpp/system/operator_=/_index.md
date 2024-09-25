---
title: System::operator<= method
linktitle: operator<=
second_title: Aspose.TeX for C++
description: 'How to use operator<= method of  class in C++.'
type: docs
weight: 17200
url: /cpp/system/operator_=/
---
## System::operator<=(std::nullptr_t, DateTime) method




```cpp
bool System::operator<=(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator<=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) method


Always returns false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator<=(const T1\&, const Nullable\<T2\>\&) method


Determines if the specified value is less or equal to the value represented by the specified [Nullable](../nullable/) object by applying [operator<=()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const Nullable\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### ReturnValue

True if the first comparand is less or equal to the second comparand, otherwise - false

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator<=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<=(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
---
title: System::operator>= method
linktitle: operator>=
second_title: Aspose.TeX for C++
description: 'How to use operator>= method of  class in C++.'
type: docs
weight: 18200
url: /cpp/system/operator_=/
---
## System::operator>=(std::nullptr_t, DateTime) method




```cpp
bool System::operator>=(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator>=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) method


Always returns false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator>=(const T1\&, const Nullable\<T2\>\&) method


Determines if the specified value is greater or equal to the value represented by the specified [Nullable](../nullable/) object by applying [operator>=()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const Nullable\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### ReturnValue

True if the first comparand is greater or equal than the second comparand, otherwise - false

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
## System::operator>=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>=(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.TeX for C++](../../)
