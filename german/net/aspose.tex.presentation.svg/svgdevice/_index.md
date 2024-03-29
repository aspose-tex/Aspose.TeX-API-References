---
title: SvgDevice
second_title: Aspose.TeX für .NET-API-Referenz
description: Implementiert die Schnittstelle zur Ausgabe von Text und Grafikinhalten in ein PDFDokument.
type: docs
weight: 420
url: /de/net/aspose.tex.presentation.svg/svgdevice/
---
## SvgDevice class

Implementiert die Schnittstelle zur Ausgabe von Text- und Grafikinhalten in ein PDF-Dokument.

```csharp
public class SvgDevice : Device, IFragmentRasterizer, IInteractiveDevice
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SvgDevice](svgdevice)() | Erstellt eine neue Instanz. Die Ausgabedatei wird in das Ausgabeverzeichnis working geschrieben, wobei der Jobname als Dateiname verwendet wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DestinationName](../../aspose.tex.presentation.svg/svgdevice/destinationname) { get; } | Ruft den Zielnamen ab: Ausgabedateiname oder Gerätebeschreibung. |
| override [Fill](../../aspose.tex.presentation.svg/svgdevice/fill) { get; set; } | Holt/setzt die aktuelle Füllung. |
| override [FillOpacity](../../aspose.tex.presentation.svg/svgdevice/fillopacity) { get; set; } | Ermittelt/setzt die aktuelle Deckkraft der Füllung. |
| override [IsReady](../../aspose.tex.presentation.svg/svgdevice/isready) { get; } | Zeigt an, ob das Gerät zur Ausgabe bereit ist. |
| override [PageCount](../../aspose.tex.presentation.svg/svgdevice/pagecount) { get; } | Ruft die Anzahl der Seiten ab. |
| override [Stroke](../../aspose.tex.presentation.svg/svgdevice/stroke) { get; set; } | Liest/setzt den aktuellen Strich. |
| override [StrokeOpacity](../../aspose.tex.presentation.svg/svgdevice/strokeopacity) { get; set; } | Liest/setzt die aktuelle Strichdeckkraft. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBookmark](../../aspose.tex.presentation.svg/svgdevice/addbookmark)(string, PointF) | Fügt das anhand des Namens identifizierte Lesezeichen hinzu. |
| override [AddHyperlink](../../aspose.tex.presentation.svg/svgdevice/addhyperlink)(RectangleF, Pen, string) | Legen Sie den Hyperlink mit einem URI als Ziel fest. |
| override [Create](../../aspose.tex.presentation.svg/svgdevice/create)() | Erstellt eine Kopie dieses Geräts. |
| override [Dispose](../../aspose.tex.presentation.svg/svgdevice/dispose)() | Verwirft diese Geräteinstanz. Schließt den Grafikzustand dieser Geräteinstanz ab, , dh schaltet den APS-Erstellungskontext auf den umApsCanvas des Levels höher als der Grafikzustand des Geräts this ApsCanvas . |
| override [DrawPath](../../aspose.tex.presentation.svg/svgdevice/drawpath)(GraphicsPath) | Zeichnet einen Pfad. |
| override [DrawString](../../aspose.tex.presentation.svg/svgdevice/drawstring)(string, float, float, List&lt;GlyphData&gt;) | Zeichnet eine Textzeichenfolge. |
| override [EndDocument](../../aspose.tex.presentation.svg/svgdevice/enddocument)() | Schließt das gesamte Dokument ab. |
| [EndFragment](../../aspose.tex.presentation.svg/svgdevice/endfragment)() | Beendet ein zu rasterndes Fragment. |
| override [EndPage](../../aspose.tex.presentation.svg/svgdevice/endpage)() | Schließt eine Seite ab. |
| override [FillPath](../../aspose.tex.presentation.svg/svgdevice/fillpath)(GraphicsPath) | Füllen Sie einen Pfad. |
| override [Init](../../aspose.tex.presentation.svg/svgdevice/init)() | Gerät initialisieren. |
| override [SetClip](../../aspose.tex.presentation.svg/svgdevice/setclip)(GraphicsPath) | Legt den aktuellen Clip-Pfad fest. |
| override [SetTransform](../../aspose.tex.presentation.svg/svgdevice/settransform)(Matrix) | Legt die aktuelle Koordinatenraumtransformation fest. |
| override [ShowImage](../../aspose.tex.presentation.svg/svgdevice/showimage)(PointF, SizeF, byte[]) | Zeigt ein Rasterbild an. |
| override [StartDocument](../../aspose.tex.presentation.svg/svgdevice/startdocument)() | Startet das gesamte Dokument. |
| [StartFragment](../../aspose.tex.presentation.svg/svgdevice/startfragment)() | Startet ein Fragment zum Rastern. |
| override [StartPage](../../aspose.tex.presentation.svg/svgdevice/startpage)(float, float) | Beginnt eine neue Seite. |

### Siehe auch

* class [Device](../../aspose.tex.presentation/device)
* interface [IFragmentRasterizer](../../aspose.tex.presentation/ifragmentrasterizer)
* interface [IInteractiveDevice](../../aspose.tex.presentation/iinteractivedevice)
* namensraum [Aspose.TeX.Presentation.Svg](../../aspose.tex.presentation.svg)
* Montage [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->
