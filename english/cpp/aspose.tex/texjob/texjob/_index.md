---
title: Aspose::TeX::TeXJob::TeXJob constructor
linktitle: TeXJob
second_title: Aspose.TeX for C++
description: 'Aspose::TeX::TeXJob::TeXJob constructor. Creates a TeX job for running the engine in production mode to typeset a TeX document. The engine will prompt the file name as soon as it starts. Thus this run is supposed to be interactive in C++.'
type: docs
weight: 100
url: /cpp/aspose.tex/texjob/texjob/
---
## TeXJob::TeXJob(const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\&, const System::SharedPtr\<Aspose::TeX::TeXOptions\>\&) constructor


Creates a [TeX](../../) job for running the engine in production mode to typeset a [TeX](../../) document. The engine will prompt the file name as soon as it starts. Thus this run is supposed to be interactive.

```cpp
Aspose::TeX::TeXJob::TeXJob(const System::SharedPtr<Aspose::TeX::Presentation::Device> &device, const System::SharedPtr<Aspose::TeX::TeXOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\& | The device defining output representation. |
| options | const System::SharedPtr\<Aspose::TeX::TeXOptions\>\& | [TeX](../../) engine run options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Device](../../../aspose.tex.presentation/device/)
* Class [TeXOptions](../../texoptions/)
* Class [TeXJob](../)
* Namespace [Aspose::TeX](../../)
* Library [Aspose.TeX for C++](../../../)
## TeXJob::TeXJob(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\&, const System::SharedPtr\<Aspose::TeX::TeXOptions\>\&) constructor


Creates a [TeX](../../) job for running the engine in production mode to typeset a [TeX](../../) file.

```cpp
Aspose::TeX::TeXJob::TeXJob(const System::SharedPtr<System::IO::Stream> &stream, const System::SharedPtr<Aspose::TeX::Presentation::Device> &device, const System::SharedPtr<Aspose::TeX::TeXOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const System::SharedPtr\<System::IO::Stream\>\& | The stream containing the [TeX](../../) file. |
| device | const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\& | The device defining output representation. |
| options | const System::SharedPtr\<Aspose::TeX::TeXOptions\>\& | [TeX](../../) engine run options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Device](../../../aspose.tex.presentation/device/)
* Class [TeXOptions](../../texoptions/)
* Class [TeXJob](../)
* Namespace [Aspose::TeX](../../)
* Library [Aspose.TeX for C++](../../../)
## TeXJob::TeXJob(const System::String\&, const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\&, const System::SharedPtr\<Aspose::TeX::TeXOptions\>\&) constructor


Creates a [TeX](../../) job for running the engine in production mode to typeset a [TeX](../../) file.

```cpp
Aspose::TeX::TeXJob::TeXJob(const System::String &path, const System::SharedPtr<Aspose::TeX::Presentation::Device> &device, const System::SharedPtr<Aspose::TeX::TeXOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path to the [TeX](../../) file. |
| device | const System::SharedPtr\<Aspose::TeX::Presentation::Device\>\& | The device defining output representation. |
| options | const System::SharedPtr\<Aspose::TeX::TeXOptions\>\& | [TeX](../../) engine run options. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Device](../../../aspose.tex.presentation/device/)
* Class [TeXOptions](../../texoptions/)
* Class [TeXJob](../)
* Namespace [Aspose::TeX](../../)
* Library [Aspose.TeX for C++](../../../)
