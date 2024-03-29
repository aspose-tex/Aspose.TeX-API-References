---
title: Device
second_title: Справочник по API Aspose.TeX для .NET
description: Реализует интерфейс для вывода текстового и графического контента на абстрактное устройство. Рендеринг выполняется постранично.
type: docs
weight: 250
url: /ru/net/aspose.tex.presentation/device/
---
## Device class

Реализует интерфейс для вывода текстового и графического контента на абстрактное устройство. Рендеринг выполняется постранично.

```csharp
public abstract class Device
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Device](device)() | Создает новый экземпляр. |

## Характеристики

| Имя | Описание |
| --- | --- |
| abstract [DestinationName](../../aspose.tex.presentation/device/destinationname) { get; } | Получает имя назначения: имя выходного файла или описание устройства. |
| virtual [Fill](../../aspose.tex.presentation/device/fill) { get; set; } | Получает/устанавливает текущую заливку. |
| virtual [FillOpacity](../../aspose.tex.presentation/device/fillopacity) { get; set; } | Получает/устанавливает текущую непрозрачность заливки. |
| abstract [IsReady](../../aspose.tex.presentation/device/isready) { get; } | Показывает, готово ли устройство к выводу. |
| abstract [PageCount](../../aspose.tex.presentation/device/pagecount) { get; } | Получает количество страниц. |
| virtual [Stroke](../../aspose.tex.presentation/device/stroke) { get; set; } | Получает/устанавливает текущий штрих. |
| virtual [StrokeOpacity](../../aspose.tex.presentation/device/strokeopacity) { get; set; } | Получает/устанавливает текущую непрозрачность штриха. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AddHyperlink](../../aspose.tex.presentation/device/addhyperlink)(RectangleF, Pen, string) | Устанавливает гиперссылку с URI в качестве цели. |
| virtual [Create](../../aspose.tex.presentation/device/create)() | Создает копию этого устройства. |
| virtual [Dispose](../../aspose.tex.presentation/device/dispose)() | Удаляет устройство. |
| abstract [DrawPath](../../aspose.tex.presentation/device/drawpath)(GraphicsPath) | Рисует путь. |
| abstract [DrawString](../../aspose.tex.presentation/device/drawstring)(string, float, float, List&lt;GlyphData&gt;) | Рисует текстовую строку. |
| abstract [EndDocument](../../aspose.tex.presentation/device/enddocument)() | Завершает весь документ. |
| abstract [EndPage](../../aspose.tex.presentation/device/endpage)() | Завершает страницу. |
| abstract [FillPath](../../aspose.tex.presentation/device/fillpath)(GraphicsPath) | Заполняет путь. |
| abstract [Init](../../aspose.tex.presentation/device/init)() | Инициализирует устройство. |
| abstract [SetClip](../../aspose.tex.presentation/device/setclip)(GraphicsPath) | Устанавливает текущий путь клипа. |
| abstract [SetTransform](../../aspose.tex.presentation/device/settransform)(Matrix) | Устанавливает текущее преобразование координатного пространства. |
| abstract [ShowImage](../../aspose.tex.presentation/device/showimage)(PointF, SizeF, byte[]) | Показывает растровое изображение. |
| abstract [StartDocument](../../aspose.tex.presentation/device/startdocument)() | Запускает весь документ. |
| abstract [StartPage](../../aspose.tex.presentation/device/startpage)(float, float) | Начинает новую страницу. |

### Смотрите также

* пространство имен [Aspose.TeX.Presentation](../../aspose.tex.presentation)
* сборка [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->
