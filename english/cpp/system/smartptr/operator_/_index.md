---
title: System::SmartPtr::operator* method
linktitle: operator*
second_title: Aspose.TeX for C++
description: 'System::SmartPtr::operator* method. Gets reference to pointed object. Asserts that pointer is not null in C++.'
type: docs
weight: 1600
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


Gets reference to pointed object. Asserts that pointer is not null.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

Reference to pointed object.

## See Also

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.TeX for C++](../../../)
---
title: System::SmartPtr::operator< method
linktitle: operator<
second_title: Aspose.TeX for C++
description: 'System::SmartPtr::operator< method. Provides less-compare semantics for SmartPtr class in C++.'
type: docs
weight: 1900
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(Y *) const method


Provides less-compare semantics for [SmartPtr](../) class.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

| Parameter | Type | Description |
| --- | --- | --- |
| p | Y * | Pointer to compare current one to. |

### ReturnValue

True if the object referenced by [SmartPtr](../) is 'less' than p and false otherwise.

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.TeX for C++](../../../)
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Provides less-compare semantics for [SmartPtr](../) class.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Pointer to compare current one to. |

### ReturnValue

True if the object referenced by [SmartPtr](../) is 'less' than x and false otherwise.

## See Also

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.TeX for C++](../../../)
