---
title: "System::Drawing::Point sınıfı"
linktitle: "Nokta"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Point sınıfı. 2 boyutlu bir düzlemdeki bir noktanın tam sayı X ve Y koordinat çiftini temsil eder. Bu tür yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. C++'ta bu tür nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1700
url: /tr/cpp/system.drawing/point/
---
## Point class


2 boyutlu bir düzlemdeki bir noktanın tam sayı X ve Y koordinat çiftini temsil eder. Bu tür yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tür nesneleri yönetmek için [System::SmartPtr](../../system/smartptr/) sınıfını asla kullanmayın.

```cpp
class Point
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Add](./add/)(const Point\&, const Size\&) | Belirtilen [Size](../size/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [Point](./) nesnesinin X ve Y koordinat değerlerine sırasıyla ekler. |
| static [Ceiling](./ceiling/)(const PointF\&) | Belirtilen [PointF](../pointf/) nesnesinin X ve Y koordinat değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Point](./) nesnesi oluşturur. |
| [Equals](./equals/)(const Point\&) const | Geçerli nesne ile belirtilen nesnenin eşit olup olmadığını belirler, yani aynı X ve Y koordinat değer çiftini temsil edip etmediklerini. |
| [get_IsEmpty](./get_isempty/)() const | Hem X hem de Y koordinat değerlerinin 0'a eşit olup olmadığını belirler. |
| [get_X](./get_x/)() const | Geçerli nesne tarafından temsil edilen X koordinat değerini döndürür. |
| [get_Y](./get_y/)() const | Geçerli nesne tarafından temsil edilen Y koordinat değerini döndürür. |
| [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu döndürür. |
| [getStdHash](./getstdhash/)() const | Geçerli nesne için bir karma (hash) değeri döndürür. |
| [IsNull](./isnull/)() const | Her zaman false döndürür. |
| [Offset](./offset/)(int, int) | Geçerli nesne tarafından temsil edilen X ve Y koordinat değerlerini belirtilen değerlerle kaydırır. |
| [Offset](./offset/)(Point) | Geçerli nesne tarafından temsil edilen X ve Y koordinatlarını, belirtilen [Point](./) nesnesinin X ve Y koordinat değerleriyle sırasıyla kaydırır. |
| [operator PointF](./operatorpointf/)() const | Bir [PointF](../pointf/) nesnesi örneği oluşturur ve onu geçerli [Point](./) nesnesinin X ve Y koordinat değerleriyle başlatır. |
| [operator Size](./operatorsize/)() const | Bir [Size](../size/) nesnesi örneği oluşturur ve onun genişlik ve yükseklik değerlerini geçerli nesne tarafından temsil edilen X ve Y koordinat değerleriyle sırasıyla başlatır. |
| [Point](./point/)() | Yeni bir [Point](./) nesnesi oluşturur ve onun X ve Y koordinat değerlerini 0 ile başlatır. |
| [Point](./point/)(int, int) | Yeni bir [Point](./) nesnesi oluşturur ve onu belirtilen değerlerle başlatır. |
| [Point](./point/)(const Size\&) | Yeni bir [Point](./) nesnesi oluşturur ve onun X ve Y koordinat değerlerini belirtilen [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerleriyle sırasıyla başlatır. |
| [Point](./point/)(int) | Yeni bir [Point](./) nesnesi oluşturur ve onun X koordinat değerini belirtilen 32-bit tam sayının yüksek 16 bitiyle, Y koordinat değerini ise düşük 16 bitiyle oluşturulan bir değerle başlatır. |
| static [Round](./round/)(const PointF\&) | Belirtilen [PointF](../pointf/) nesnesinin X ve Y koordinat değerlerini en yakın tam sayıya yuvarlayarak bir [Point](./) nesnesi oluşturur. |
| [set_X](./set_x/)(int) | Geçerli nesne tarafından temsil edilen X koordinatının değerini ayarlar. |
| [set_Y](./set_y/)(int) | Geçerli nesne tarafından temsil edilen Y koordinatının değerini ayarlar. |
| static [Subtract](./subtract/)(const Point\&, const Size\&) | Belirtilen [Size](../size/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [Point](./) nesnesinin X ve Y koordinat değerlerinden sırasıyla çıkarır. |
| [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen X ve Y koordinat değerlerinin çiftinin dize temsiliğini döndürür. |
| static [Truncate](./truncate/)(const PointF\&) | Belirtilen [PointF](../pointf/) nesnesinden [Point](./) nesnesi oluşturur ve [PointF](../pointf/) nesnesinin X ve Y koordinat değerlerini bir sonraki daha düşük tam sayıya kırpar. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | X ve Y koordinat değerleri 0 olan [Point](./) sınıfının boş bir örneği. |
## Ayrıca Bakınız

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
