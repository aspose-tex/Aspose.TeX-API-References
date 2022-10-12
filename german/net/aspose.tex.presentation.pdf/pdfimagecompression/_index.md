---
title: PdfImageCompression
second_title: Aspose.TeX für .NET-API-Referenz
description: Gibt den Komprimierungstyp an der auf Bilder in der PDFDatei angewendet wird.
type: docs
weight: 380
url: /de/net/aspose.tex.presentation.pdf/pdfimagecompression/
---
## PdfImageCompression enumeration

Gibt den Komprimierungstyp an, der auf Bilder in der PDF-Datei angewendet wird.

```csharp
public enum PdfImageCompression
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Wählt automatisch die am besten geeignete Komprimierung für jedes Bild aus. |
| None | `1` | Speichert Rohbild-Bytes, was zu größeren PDF-Dateigrößen führt. |
| Rle | `2` | Komprimierung der Lauflänge. |
| Flate | `3` | Flate-Komprimierung. |
| LzwBaselinePredictor | `4` | Die Prädiktorauswahl ist auf den PNG-Paeth-Prädiktor beschränkt, um den Prozess zu beschleunigen. In der Praxis schneidet überraschend gut ab. Besser alsLzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | Die Auswahl des Prädiktors ist komplizierter und sollte zu kleineren Bildgrößen führen, aber nimmt mehr Zeit in Anspruch. |
| Jpeg | `6` | JPEG-Komprimierung. Unterstützt keine Transparenz. |

### Siehe auch

* namensraum [Aspose.TeX.Presentation.Pdf](../../aspose.tex.presentation.pdf)
* Montage [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->