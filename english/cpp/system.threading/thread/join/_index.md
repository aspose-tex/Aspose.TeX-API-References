---
title: System::Threading::Thread::Join method
linktitle: Join
second_title: Aspose.TeX for C++
description: 'System::Threading::Thread::Join method. Joins managed thread. Performs unlimited waiting if required in C++.'
type: docs
weight: 1600
url: /cpp/system.threading/thread/join/
---
## Thread::Join() method


Joins managed thread. Performs unlimited waiting if required.

```cpp
void System::Threading::Thread::Join()
```

## See Also

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.TeX for C++](../../../)
## Thread::Join(int) method


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### ReturnValue

True if thread was successfully joined, false if timeout exceeded.

## See Also

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.TeX for C++](../../../)
## Thread::Join(TimeSpan) method


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| timeout | TimeSpan | A [TimeSpan](../../../system/timespan/) set to the amount of time to wait for the thread to terminate. |

### ReturnValue

True if thread was successfully joined, false if timeout exceeded.

## See Also

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.TeX for C++](../../../)
