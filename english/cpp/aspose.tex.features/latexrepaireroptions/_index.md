---
title: Aspose::TeX::Features::LaTeXRepairerOptions class
linktitle: LaTeXRepairerOptions
second_title: Aspose.TeX for C++
description: 'Aspose::TeX::Features::LaTeXRepairerOptions class. The class to provide options to the LaTeX Repairer in C++.'
type: docs
weight: 700
url: /cpp/aspose.tex.features/latexrepaireroptions/
---
## LaTeXRepairerOptions class


The class to provide options to the LaTeX Repairer.

```cpp
class LaTeXRepairerOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_GuessPackageCallback](./get_guesspackagecallback/)() const | Gets/sets the callback to externally guess a required package by command name. |
| [get_InputWorkingDirectory](./get_inputworkingdirectory/)() | Gets/sets input working directory. |
| [get_OutputWorkingDirectory](./get_outputworkingdirectory/)() | Gets/sets output working directory. |
| [get_RequiredInputDirectory](./get_requiredinputdirectory/)() | Gets/sets the directory for the required input, e.g., packages that are beyond [Aspose.TeX](../../aspose.tex/)'s LaTeX support. |
| [get_SearchCurrentDirectory](./get_searchcurrentdirectory/)() | Gets/sets the flag that instructs the engine whether to look for input files with relative names in the process's current directory and in the directory of the main input file before looking in [InputWorkingDirectory](../), [RequiredInputDirectory](../) and [OutputWorkingDirectory](../). Files with absolute names are opened directly regardless of this setting. Default value is **true**. |
| [LaTeXRepairerOptions](./latexrepaireroptions/)() | Cretes a new instance. |
| [set_GuessPackageCallback](./set_guesspackagecallback/)(const System::SharedPtr\<Aspose::TeX::Features::IGuessPackageCallback\>\&) | Gets/sets the callback to externally guess a required package by command name. |
| [set_InputWorkingDirectory](./set_inputworkingdirectory/)(const System::SharedPtr\<Aspose::TeX::IO::IInputWorkingDirectory\>\&) | Gets/sets input working directory. |
| [set_OutputWorkingDirectory](./set_outputworkingdirectory/)(const System::SharedPtr\<Aspose::TeX::IO::IOutputWorkingDirectory\>\&) | Gets/sets output working directory. |
| [set_RequiredInputDirectory](./set_requiredinputdirectory/)(const System::SharedPtr\<Aspose::TeX::IO::IInputWorkingDirectory\>\&) | Gets/sets the directory for the required input, e.g., packages that are beyond [Aspose.TeX](../../aspose.tex/)'s LaTeX support. |
| [set_SearchCurrentDirectory](./set_searchcurrentdirectory/)(bool) | Gets/sets the flag that instructs the engine whether to look for input files with relative names in the process's current directory and in the directory of the main input file before looking in [InputWorkingDirectory](../), [RequiredInputDirectory](../) and [OutputWorkingDirectory](../). Files with absolute names are opened directly regardless of this setting. Default value is **true**. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::TeX::Features](../)
* Library [Aspose.TeX for C++](../../)
