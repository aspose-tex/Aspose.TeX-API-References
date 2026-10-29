---
title: System::Buffers::MemoryHandle class
linktitle: MemoryHandle
second_title: Aspose.TeX for C++
description: 'System::Buffers::MemoryHandle class. Represents a handle to a block of memory in C++.'
type: docs
weight: 100
url: /cpp/system.buffers/memoryhandle/
---
## MemoryHandle class


Represents a handle to a block of memory.

```cpp
class MemoryHandle : public System::IDisposable,
                     public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() |  |
| virtual [Dispose](./dispose/)() | Releases resources held by the memory handle. |
| [get_Pointer](./get_pointer/)() const | Gets the raw memory pointer associated with this handle. |
| [MemoryHandle](./memoryhandle/)(void *) | Initializes a new instance of the [MemoryHandle](./) type. |
## Remarks


This value type wraps a raw memory pointer and provides a disposable handle abstraction. It is used to represent ownership of a memory region in buffer-related APIs. Actual memory management (allocation and deallocation) is not performed by this type. All objects is unmovable in C++, so it simply holds a pointer to the memory block. 
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Buffers](../)
* Library [Aspose.TeX for C++](../../)
