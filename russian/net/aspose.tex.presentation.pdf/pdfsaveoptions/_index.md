---
title: PdfSaveOptions
second_title: Справочник по API Aspose.TeX для .NET
description: Класс представляющий варианты сохранения в PDF.
type: docs
weight: 390
url: /ru/net/aspose.tex.presentation.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Класс, представляющий варианты сохранения в PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [EncryptionDetails](../../aspose.tex.presentation.pdf/pdfsaveoptions/encryptiondetails) { get; set; } | Получает или задает сведения о шифровании. Если не установлено, то шифрование выполняться не будет. |
| [ImageCompression](../../aspose.tex.presentation.pdf/pdfsaveoptions/imagecompression) { get; set; } | Определяет тип сжатия, который будет использоваться для всех изображений в документе. Значение по умолчанию:Auto . |
| [JpegQualityLevel](../../aspose.tex.presentation.pdf/pdfsaveoptions/jpegqualitylevel) { get; set; } | Категория «Качество» указывает уровень сжатия изображения. Доступные значения от 0 до 100. Чем меньше указанное число, тем выше степень сжатия и, следовательно, ниже качество изображения. Значение 0 приводит к изображению самого низкого качества, а 100 — к самому высокому. |
| [OutlineTreeExpansionLevel](../../aspose.tex.presentation.pdf/pdfsaveoptions/outlinetreeexpansionlevel) { get; set; } | Указывает, до какого уровня должна быть расширена структура документа при просмотре PDF-файла. 1 - отображаются элементы структуры только первого уровня, 2 - отображаются элементы структуры только первого и второго уровня, и т. д. По умолчанию 1. |
| [OutlineTreeHeight](../../aspose.tex.presentation.pdf/pdfsaveoptions/outlinetreeheight) { get; set; } | Определяет высоту дерева структуры документа для сохранения. 0 - дерево структуры не будет преобразовано, 1 - будут преобразованы только элементы структуры первого уровня, и т.д.. |
| [RasterizeFormulas](../../aspose.tex.presentation/saveoptions/rasterizeformulas) { get; set; } | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [RasterizeIncludedGraphics](../../aspose.tex.presentation/saveoptions/rasterizeincludedgraphics) { get; set; } | Получает/устанавливает флаг, позволяющий растеризовать включенную графику PS/EPS и/или XPS/OXPS. |
| [SubsetFonts](../../aspose.tex.presentation/saveoptions/subsetfonts) { get; set; } | Получает/устанавливает флаг, указывающий, следует ли поднабор шрифтов в выходном файле или нет. |
| [TextCompression](../../aspose.tex.presentation.pdf/pdfsaveoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всех потоков контента, кроме изображений. По умолчанию:Flate . |

### Смотрите также

* class [SaveOptions](../../aspose.tex.presentation/saveoptions)
* пространство имен [Aspose.TeX.Presentation.Pdf](../../aspose.tex.presentation.pdf)
* сборка [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->
