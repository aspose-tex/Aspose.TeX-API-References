---
title: FigureRenderer
second_title: Aspose.TeX for Java API Reference
description: Implements rendering of some LaTeX compact content supposed to fit one page and then cropping it from the page.
type: docs
weight: 10
url: /java/com.aspose.tex/figurerenderer/
---
**Inheritance:**
java.lang.Object
```
public abstract class FigureRenderer
```

Implements rendering of some LaTeX compact content (supposed to fit one page) and then cropping it from the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [FigureRenderer()](#FigureRenderer--) | Creates a new instance. |
## Methods

| Method | Description |
| --- | --- |
| [render(String latexBody, OutputStream stream, FigureRendererOptions figureRendererOptions)](#render-java.lang.String-java.io.OutputStream-com.aspose.tex.FigureRendererOptions-) | Renders some LaTeX code. |
### FigureRenderer() {#FigureRenderer--}
```
public FigureRenderer()
```


Creates a new instance.

### render(String latexBody, OutputStream stream, FigureRendererOptions figureRendererOptions) {#render-java.lang.String-java.io.OutputStream-com.aspose.tex.FigureRendererOptions-}
```
public Size2D render(String latexBody, OutputStream stream, FigureRendererOptions figureRendererOptions)
```


Renders some LaTeX code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latexBody | java.lang.String | The LaTeX fragment. |
| stream | java.io.OutputStream | The stream to write the output to. |
| figureRendererOptions | [FigureRendererOptions](../../com.aspose.tex/figurerendereroptions) | The rendering options. |

**Returns:**
[Size2D](../../com.aspose.tex/size2d) - The output image size.
