---
title: XpsDevice
second_title: Aspose.TeX för .NET API-referens
description: Implementerar gränssnittet för utmatning av text och grafiskt innehåll till XPSdokument.
type: docs
weight: 440
url: /sv/net/aspose.tex.presentation.xps/xpsdevice/
---
## XpsDevice class

Implementerar gränssnittet för utmatning av text och grafiskt innehåll till XPS-dokument.

```csharp
public class XpsDevice : Device, IFragmentRasterizer, IInteractiveDevice
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)() | Skapar ny instans. Utdatafilen kommer att skrivas till katalogen output working med jobbnamnet som ett filnamn. |
| [XpsDevice](xpsdevice#constructor_1)(Stream) | Skapar ny instans. Utdatafilen kommer att skrivas till angiven ström. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [DestinationName](../../aspose.tex.presentation.xps/xpsdevice/destinationname) { get; } | Hämtar destinationsnamn: utdatafilnamn eller enhetsbeskrivning. |
| override [Fill](../../aspose.tex.presentation.xps/xpsdevice/fill) { get; set; } | Hämtar/ställer in den aktuella fyllningen. |
| override [FillOpacity](../../aspose.tex.presentation.xps/xpsdevice/fillopacity) { get; set; } | Hämtar/ställer in aktuell fyllningsopacitet. |
| override [IsReady](../../aspose.tex.presentation.xps/xpsdevice/isready) { get; } | Visar om enheten är redo för utmatning. |
| override [PageCount](../../aspose.tex.presentation.xps/xpsdevice/pagecount) { get; } | Hämtar antalet sidor. |
| override [Stroke](../../aspose.tex.presentation.xps/xpsdevice/stroke) { get; set; } | Hämtar/ställer in det aktuella strecket. |
| override [StrokeOpacity](../../aspose.tex.presentation.xps/xpsdevice/strokeopacity) { get; set; } | Hämtar/ställer in aktuell slagopacitet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddBookmark](../../aspose.tex.presentation.xps/xpsdevice/addbookmark)(string, PointF) | Lägger till bokmärket som identifieras av namnet. |
| override [AddHyperlink](../../aspose.tex.presentation.xps/xpsdevice/addhyperlink)(RectangleF, Pen, string) | Ställ in hyperlänken med en URI som mål. |
| override [Create](../../aspose.tex.presentation.xps/xpsdevice/create)() | Skapar en kopia av den här enheten. |
| override [Dispose](../../aspose.tex.presentation.xps/xpsdevice/dispose)() | Kasserar denna enhetsinstans. Slutför denna enhetsinstanss grafiktillstånd, dvs växlar APS-komponeringskontext tillApsCanvas av nivån högre än denna enhets grafiktillståndApsCanvas . |
| override [DrawPath](../../aspose.tex.presentation.xps/xpsdevice/drawpath)(GraphicsPath) | Ritar en bana. |
| override [DrawString](../../aspose.tex.presentation.xps/xpsdevice/drawstring)(string, float, float, List&lt;GlyphData&gt;) | Ritar en textsträng. |
| override [EndDocument](../../aspose.tex.presentation.xps/xpsdevice/enddocument)() | Slutför hela dokumentet. |
| [EndFragment](../../aspose.tex.presentation.xps/xpsdevice/endfragment)() | Avslutar ett fragment som ska rastreras. |
| override [EndPage](../../aspose.tex.presentation.xps/xpsdevice/endpage)() | Slutför en sida. |
| override [FillPath](../../aspose.tex.presentation.xps/xpsdevice/fillpath)(GraphicsPath) | Fyll en sökväg. |
| override [Init](../../aspose.tex.presentation.xps/xpsdevice/init)() | Initierar enheten. |
| override [SetClip](../../aspose.tex.presentation.xps/xpsdevice/setclip)(GraphicsPath) | Ställer in den aktuella klippvägen. |
| override [SetTransform](../../aspose.tex.presentation.xps/xpsdevice/settransform)(Matrix) | Ställer in den aktuella transformationen av koordinatutrymmet. |
| override [ShowImage](../../aspose.tex.presentation.xps/xpsdevice/showimage)(PointF, SizeF, byte[]) | Visar en rasterbild. |
| override [StartDocument](../../aspose.tex.presentation.xps/xpsdevice/startdocument)() | Startar hela dokumentet. |
| [StartFragment](../../aspose.tex.presentation.xps/xpsdevice/startfragment)() | Startar ett fragment att rastrera. |
| override [StartPage](../../aspose.tex.presentation.xps/xpsdevice/startpage)(float, float) | Startar en ny sida. |

### Se även

* class [Device](../../aspose.tex.presentation/device)
* interface [IFragmentRasterizer](../../aspose.tex.presentation/ifragmentrasterizer)
* interface [IInteractiveDevice](../../aspose.tex.presentation/iinteractivedevice)
* namnutrymme [Aspose.TeX.Presentation.Xps](../../aspose.tex.presentation.xps)
* hopsättning [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->