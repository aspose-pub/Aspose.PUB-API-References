---
title: "System::Drawing::SizeF sınıfı"
linktitle: "SizeF"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::SizeF sınıfı. Bir görüntünün genişlik ve yüksekliğini temsil eden tek duyarlıklı kayan nokta değerlerinden oluşan bir çift temsil eder. Bu tür, yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. C++'ta bu türün nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 2300
url: /tr/cpp/system.drawing/sizef/
---
## SizeF class


Bir görüntünün genişlik ve yüksekliğini temsil eden tek duyarlıklı kayan nokta değer çiftini temsil eder. Bu tip yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](../../system/smartptr/) sınıfını asla kullanmayın.

```cpp
class SizeF
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Add](./add/)(const SizeF\&, const SizeF\&) | Belirtilen [SizeF](./) nesnelerinin toplamı olan yeni bir [SizeF](./) nesnesi döndürür, yani genişlik değeri belirtilen nesnelerin genişlik değerlerinin toplamına, yükseklik değeri ise belirtilen nesnelerin yükseklik değerlerinin toplamına eşittir. |
| [Equals](./equals/)(const SizeF\&) const | Mevcut nesne ile belirtilen nesnenin eşit olup olmadığını belirler; yani aynı genişlik ve yükseklik değer çiftini temsil edip etmediklerini. |
| [get_Height](./get_height/)() const | Geçerli nesne tarafından temsil edilen yüksekliğin değerini döndürür. |
| [get_IsEmpty](./get_isempty/)() const | Genişlik ve yüksekliğin her ikisinin de 0'a eşit olup olmadığını belirler. |
| [get_Width](./get_width/)() const | Mevcut nesne tarafından temsil edilen genişliğin değerini döndürür. |
| [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu döndürür. |
| [operator PointF](./operatorpointf/)() const | Geçerli nesneyi, X ve Y koordinatlarını sırasıyla geçerli nesnenin genişlik ve yükseklik değerleriyle başlatarak bir [Point](../point/) nesnesi örneğine dönüştürür. |
| [operator+=](./operator+=/)(const SizeF\&) | Belirtilen [SizeF](./) nesnesinin genişlik ve yükseklik değerlerini, geçerli [SizeF](./) nesnesinin genişlik ve yükseklik değerlerine sırasıyla ekler. |
| [set_Height](./set_height/)(float) | Mevcut nesne tarafından temsil edilen yüksekliğin değerini ayarlar. |
| [set_Width](./set_width/)(float) | Mevcut nesne tarafından temsil edilen genişliğin değerini ayarlar. |
| [SizeF](./sizef/)() | Yeni bir [SizeF](./) nesnesi oluşturur ve genişlik ve yükseklik değerlerini 0 ile başlatır. |
| [SizeF](./sizef/)(const PointF\&) | Yeni bir [SizeF](./) nesnesi oluşturur ve genişlik ve yükseklik değerlerini, belirtilen noktanın X ve Y koordinat değerleriyle sırasıyla başlatır. |
| [SizeF](./sizef/)(float, float) | Yeni bir [SizeF](./) nesnesi oluşturur ve onu belirtilen değerle başlatır. |
| static [Subtract](./subtract/)(const SizeF\&, const SizeF\&) | Yeni bir [SizeF](./) nesnesi döndürür; bu nesne **size1**'den **size2**'nin çıkarılması sonucudur, yani genişlik değeri **size1's** genişlik değerinden **size2's** genişlik değerinin çıkarılmasıyla, yükseklik değeri ise **size1's** yükseklik değerinden **size2's** yükseklik değerinin çıkarılmasıyla elde edilir. |
| [ToPointF](./topointf/)() const | Geçerli nesneyi, X ve Y koordinatlarını sırasıyla geçerli nesnenin genişlik ve yükseklik değerleriyle başlatarak bir [Point](../point/) nesnesi örneğine dönüştürür. |
| [ToSize](./tosize/)() const | Geçerli [SizeF](./) nesnesinin genişlik ve yükseklik değerlerini bir alt tam sayı değerine kırparak bir [Size](../size/) nesnesi oluşturur. |
| [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen genişlik ve yükseklik değerleri çiftinin dize temsilini döndürür. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Genişlik ve yükseklik değerleri 0 olan [SizeF](./) sınıfının boş bir örneği. |
## Ayrıca Bakınız

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
