---
title: Class LaTeXRepairerOptions
second_title: Aspose.TeX for .NET API Reference
description: Aspose.TeX.Features.LaTeXRepairerOptions class. The class to provide options to the LaTeX Repairer
type: docs
weight: 110
url: /net/aspose.tex.features/latexrepaireroptions/
---
## LaTeXRepairerOptions class

The class to provide options to the LaTeX Repairer.

```csharp
public class LaTeXRepairerOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [LaTeXRepairerOptions](latexrepaireroptions/)() | Cretes a new instance. |

## Properties

| Name | Description |
| --- | --- |
| [GuessPackageCallback](../../aspose.tex.features/latexrepaireroptions/guesspackagecallback/) { get; set; } | Gets/sets the callback to externally guess a required package by command name. |
| [InputWorkingDirectory](../../aspose.tex.features/latexrepaireroptions/inputworkingdirectory/) { get; set; } | Gets/sets input working directory. |
| [OutputWorkingDirectory](../../aspose.tex.features/latexrepaireroptions/outputworkingdirectory/) { get; set; } | Gets/sets output working directory. |
| [RequiredInputDirectory](../../aspose.tex.features/latexrepaireroptions/requiredinputdirectory/) { get; set; } | Gets/sets the directory for the required input, e.g., packages that are beyond Aspose.TeX's LaTeX support. |
| [SearchCurrentDirectory](../../aspose.tex.features/latexrepaireroptions/searchcurrentdirectory/) { get; set; } | Gets/sets the flag that instructs the engine whether to look for input files with relative names in the process's current directory and in the directory of the main input file before looking in [`InputWorkingDirectory`](./inputworkingdirectory/), [`RequiredInputDirectory`](./requiredinputdirectory/) and [`OutputWorkingDirectory`](./outputworkingdirectory/). Files with absolute names are opened directly regardless of this setting. Default value is `true`. |

### See Also

* namespace [Aspose.TeX.Features](../../aspose.tex.features/)
* assembly [Aspose.TeX](../../)


