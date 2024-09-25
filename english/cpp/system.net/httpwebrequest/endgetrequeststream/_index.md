---
title: System::Net::HttpWebRequest::EndGetRequestStream method
linktitle: EndGetRequestStream
second_title: Aspose.TeX for C++
description: 'System::Net::HttpWebRequest::EndGetRequestStream method. Waits until the specified asynchronous operation to get a stream completes in C++.'
type: docs
weight: 3800
url: /cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream method


Waits until the specified asynchronous operation to get a stream completes.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation to get a stream. |

### ReturnValue

The stream for writing data to the resource.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.TeX for C++](../../../)
