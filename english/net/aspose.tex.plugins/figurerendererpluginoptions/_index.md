---
title: Class FigureRendererPluginOptions
second_title: Aspose.TeX for .NET API Reference
description: Aspose.TeX.Plugins.FigureRendererPluginOptions class. The options for the FigureRendererPlugin
type: docs
weight: 420
url: /net/aspose.tex.plugins/figurerendererpluginoptions/
---
## FigureRendererPluginOptions class

The options for the [`FigureRendererPlugin`](../figurerendererplugin/).

```csharp
public abstract class FigureRendererPluginOptions : FigureRendererOptions, IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.tex.features/figurerendereroptions/backgroundcolor/) { get; set; } | Gets/sets the background color. |
| [ErrorReport](../../aspose.tex.features/figurerendereroptions/errorreport/) { get; } | Gets the error report. |
| [InputDataCollection](../../aspose.tex.plugins/figurerendererpluginoptions/inputdatacollection/) { get; } | Gets the collection of data sources. |
| [LogStream](../../aspose.tex.features/figurerendereroptions/logstream/) { get; set; } | Gets/set the stream to write log output to. |
| [Margin](../../aspose.tex.features/figurerendereroptions/margin/) { get; set; } | Gets/sets the margin width. |
| virtual [OperationName](../../aspose.tex.plugins/figurerendererpluginoptions/operationname/) { get; } | Returns operation name. |
| [OutputDataCollection](../../aspose.tex.plugins/figurerendererpluginoptions/outputdatacollection/) { get; } | Gets collection of added targets for saving operation results. |
| [Preamble](../../aspose.tex.features/figurerendereroptions/preamble/) { get; set; } | Gets/sets LaTeX document preamble. |
| [RequiredInputDirectory](../../aspose.tex.features/figurerendereroptions/requiredinputdirectory/) { get; set; } | Gets/sets the directory for the required input, e.g., packages that are beyond Aspose.TeX's LaTeX support. |
| [Scale](../../aspose.tex.features/figurerendereroptions/scale/) { get; set; } | Gets/set the scale. 1000 means 100%, 1200 means 120%, etc. |
| [ShowTerminal](../../aspose.tex.features/figurerendereroptions/showterminal/) { get; set; } | The flag that controls terminal output. If `true` then terminal output is written to console. |

## Methods

| Name | Description |
| --- | --- |
| [AddInputDataSource](../../aspose.tex.plugins/figurerendererpluginoptions/addinputdatasource/)(IDataSource) | Adds a new data source to the collection. |
| [AddOutputDataTarget](../../aspose.tex.plugins/figurerendererpluginoptions/addoutputdatatarget/)(IDataSource) | Adds a new input data target to the collection. |

### See Also

* class [FigureRendererOptions](../../aspose.tex.features/figurerendereroptions/)
* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.TeX.Plugins](../../aspose.tex.plugins/)
* assembly [Aspose.TeX](../../)


