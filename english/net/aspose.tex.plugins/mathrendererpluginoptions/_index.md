---
title: Class MathRendererPluginOptions
second_title: Aspose.TeX for .NET API Reference
description: Aspose.TeX.Plugins.MathRendererPluginOptions class. The options for the MathRendererPlugin
type: docs
weight: 490
url: /net/aspose.tex.plugins/mathrendererpluginoptions/
---
## MathRendererPluginOptions class

The options for the [`MathRendererPlugin`](../mathrendererplugin/).

```csharp
public abstract class MathRendererPluginOptions : MathRendererOptions, IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.tex.features/figurerendereroptions/backgroundcolor/) { get; set; } | Gets/sets the background color. |
| [ErrorReport](../../aspose.tex.features/figurerendereroptions/errorreport/) { get; } | Gets the error report. |
| [InputDataCollection](../../aspose.tex.plugins/mathrendererpluginoptions/inputdatacollection/) { get; } | Gets the collection of data sources. |
| [LogStream](../../aspose.tex.features/figurerendereroptions/logstream/) { get; set; } | Gets/set the stream to write log output to. |
| [Margin](../../aspose.tex.features/figurerendereroptions/margin/) { get; set; } | Gets/sets the margin width. |
| virtual [OperationName](../../aspose.tex.plugins/mathrendererpluginoptions/operationname/) { get; } | Returns operation name. |
| [OutputDataCollection](../../aspose.tex.plugins/mathrendererpluginoptions/outputdatacollection/) { get; } | Gets collection of added targets for saving operation results. |
| [Preamble](../../aspose.tex.features/figurerendereroptions/preamble/) { get; set; } | Gets/sets LaTeX document preamble. |
| [RequiredInputDirectory](../../aspose.tex.features/figurerendereroptions/requiredinputdirectory/) { get; set; } | Gets/sets the directory for the required input, e.g., packages that are beyond Aspose.TeX's LaTeX support. |
| [Scale](../../aspose.tex.features/figurerendereroptions/scale/) { get; set; } | Gets/set the scale. 1000 means 100%, 1200 means 120%, etc. |
| [ShowTerminal](../../aspose.tex.features/figurerendereroptions/showterminal/) { get; set; } | The flag that controls terminal output. If `true` then terminal output is written to console. |
| [TextColor](../../aspose.tex.features/mathrendereroptions/textcolor/) { get; set; } | Gets/sets the formula text color. |

## Methods

| Name | Description |
| --- | --- |
| [AddInputDataSource](../../aspose.tex.plugins/mathrendererpluginoptions/addinputdatasource/)(IDataSource) | Adds a new data source to the collection. |
| [AddOutputDataTarget](../../aspose.tex.plugins/mathrendererpluginoptions/addoutputdatatarget/)(IDataSource) | Adds a new input data target to the collection. |

### See Also

* class [MathRendererOptions](../../aspose.tex.features/mathrendereroptions/)
* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.TeX.Plugins](../../aspose.tex.plugins/)
* assembly [Aspose.TeX](../../)


