---
title: "Класс Coord"
second_title: "Справочник API Aspose.PUB для .NET"
description: "Класс Aspose.Pub.Utils.Coord. Этот класс предназначен для представления данных, связанных с координатами полей PUB. Каждый поле в PUB содержит координаты, имеющие 2 пары координат: координаты верхнего левого угла XLeft YTop и координаты нижнего правого угла XRight YBottom. Все координаты представлены в специальной метрической системе English Metric UnitEMUs. В этот класс добавлены дополнительные методы для преобразования значений координат из английских метрических единиц в дюймы."
type: docs
weight: 350
url: /ru/net/aspose.pub.utils/coord/
---
## Coord class

Этот класс предназначен для представления данных, связанных с координатами полей PUB. Каждый поле в PUB содержит координаты, имеющие 2 пары координат: координаты верхнего левого угла (XLeft, YTop) и координаты нижнего правого угла(XRight, YBottom). Все координаты представлены в специальной метрической системе — English Metric Unit(EMUs). В класс были добавлены дополнительные методы для преобразования значений координат из английских метрических единиц в дюймы.

```csharp
public class Coord : ICloneable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Coord](coord/#constructor)() | Конструктор |
| [Coord](coord/#constructor_1)(int, int, int, int) | Конструктор |

## Свойства

| Имя | Описание |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | X‑координата верхнего левого угла в EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | X‑координата нижнего правого угла в EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Y‑координата нижнего правого угла в EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Y‑координата верхнего левого угла в EMUs |

## Методы

| Имя | Описание |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Вычисляет высоту фигуры (текущий объект Coord) и возвращает результат в дюймах |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Вычисляет ширину фигуры (текущий объект Coord) и возвращает результат в дюймах |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Преобразует значение X‑координаты из естественной метрической системы PUB в дюймы |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Преобразует значение X‑координаты из естественной метрической системы PUB в дюймы |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Преобразует значение Y‑координаты из естественной метрической системы PUB в дюймы |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Преобразует значение Y‑координаты из естественной метрической системы PUB в дюймы |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Создана копия объекта |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Возвращает высоту текущего объекта Coord в естественных метриках PUB |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Возвращает ширину текущего объекта Coord в естественных метриках PUB |

### См. также

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


