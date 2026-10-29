---
title: Aspose::TeX::IO::InputZipDirectory class
linktitle: InputZipDirectory
second_title: Aspose.TeX for C++
description: 'Aspose::TeX::IO::InputZipDirectory class. Implements the method for getting a file stream to write to when working directory is a ZIP archive in C++.'
type: docs
weight: 600
url: /cpp/aspose.tex.io/inputzipdirectory/
---
## InputZipDirectory class


Implements the method for getting a file stream to write to when working directory is a ZIP archive.

```cpp
class InputZipDirectory : public Aspose::TeX::IO::IInputWorkingDirectory,
                          public Aspose::TeX::IO::IFileCollector
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the instance. |
| [GetFile](./getfile/)(const System::String\&, bool) override | Returns the stream to read from. |
| [GetFileNamesByExtension](./getfilenamesbyextension/)(const System::String\&, const System::String\&) override | Returns the array of file names by an extension. |
| [InputZipDirectory](./inputzipdirectory/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Creates new instance. |
## See Also

* Class [IInputWorkingDirectory](../iinputworkingdirectory/)
* Class [IFileCollector](../ifilecollector/)
* Namespace [Aspose::TeX::IO](../)
* Library [Aspose.TeX for C++](../../)
