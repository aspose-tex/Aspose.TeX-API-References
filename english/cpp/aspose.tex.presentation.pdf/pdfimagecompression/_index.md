---
title: Aspose::TeX::Presentation::Pdf::PdfImageCompression enum
linktitle: PdfImageCompression
second_title: Aspose.TeX for C++
description: 'Aspose::TeX::Presentation::Pdf::PdfImageCompression enum. Specifies the type of compression applied to images in the PDF file in C++.'
type: docs
weight: 700
url: /cpp/aspose.tex.presentation.pdf/pdfimagecompression/
---
## PdfImageCompression enum


Specifies the type of compression applied to images in the PDF file.

```cpp
enum class PdfImageCompression
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Automatically selects the most appropriate compression for each image. |
| None | 1 | Saves raw image bytes resulting in bigger PDF file sizes. |
| Rle | 2 | Run Length compression. |
| Flate | 3 | Flate compression. |
| LzwBaselinePredictor | 4 | Predictor selection is restricted to PNG Paeth predictor to speed-up the process. In practice performs surprisingly good. Better than [LzwOptimizedPredictor](./). |
| LzwOptimizedPredictor | 5 | Predictor selection is more complicated and should result in smaller image sizes but taking more time. |
| Jpeg | 6 | JPEG compression. Does not support transparency. |

## See Also

* Namespace [Aspose::TeX::Presentation::Pdf](../)
* Library [Aspose.TeX for C++](../../)
