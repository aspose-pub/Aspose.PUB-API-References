---
title: "System::Globalization::DateTimeStyles enum"
linktitle: "DateTimeStyles"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::DateTimeStyles enum. Tarih ve saat biçimlendirme seçeneklerini tanımlar. C++'de bit bayrakları."
type: docs
weight: 3500
url: /tr/cpp/system.globalization/datetimestyles/
---
## DateTimeStyles enum


Tarih ve saat biçimlendirme seçeneklerini tanımlar. Bit bayrakları.

```cpp
enum class DateTimeStyles : int32_t
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Varsayılan. |
| AllowLeadingWhite | 1 | Baştaki beyaz boşlukları yok say. |
| AllowTrailingWhite | 2 | Sondaki beyaz boşlukları yok say. |
| AllowInnerWhite | 4 | İçteki beyaz boşlukları yok say. |
| AllowWhiteSpaces | n/a | Tüm beyaz boşlukları yok say. |
| NoCurrentDateDefault | 8 | Bir tarih/saat dizesi ayrıştırılırken, yıl/ay/gün tümü eksikse, varsayılan tarihi 0001/1/1 olarak ayarla, mevcut yıl/ay/gün yerine. |
| AdjustToUniversal | 16 | Bir tarih/saat dizesi ayrıştırılırken, bir saat dilimi belirteci ("GMT","Z","+xxxx","-xxxx" mevcutsa), ayrıştırılan zamanı GMT'ye göre ayarlayacağız. |
| AssumeLocal | 32 | Saat dilimi verilmezse, yerel saat dilimini kullan. |
| AssumeUniversal | 64 | Saat dilimi verilmezse, UTC'yi kullan. |
| RoundtripKind | 128 | Girişin belirtilmemiş, yerel veya UTC olup olmadığını korumaya çalışın. |

## Ayrıca Bakınız

* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
