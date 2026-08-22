---
title: "System::Drawing::CopyPixelOperation enum"
linktitle: "CopyPixelOperation"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::CopyPixelOperation enum. Bir piksel kopyalama işleminde kaynak rengin, hedef renk ile nasıl birleştirildiğini ve C++'ta nihai renk elde edildiğini belirtir."
type: docs
weight: 3000
url: /tr/cpp/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Piksel kopyalama işleminde kaynak rengin hedef renk ile nasıl birleştirileceğini ve nihai rengi oluşturacağını belirtir.

```cpp
enum class CopyPixelOperation
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmap yansıtılmamıştır. |
| Blackness | 66 | Hedef bölge, fiziksel palet içinde indeks 0'da bulunan renk kullanılarak doldurulur. |
| NotSourceErase | 1114278 | Kaynak ve hedef renkler OR işlemine tabi tutulur ve ortaya çıkan renk daha sonra ters çevrilir. |
| NotSourceCopy | 3342344 | Kaynak bölge ters çevrilir ve ardından hedefe kopyalanır. |
| SourceErase | 4457256 | Hedef bölgenin ters çevrilmiş renkleri, kaynak bölgenin renkleriyle AND'lenir. |
| DestinationInvert | 5570569 | Hedef bölge ters çevrilir. |
| PatInvert | 5898313 | Hedef cihaz bağlamında şu anda seçili fırçanın renkleri, hedefin renkleriyle XOR'lanır. |
| SourceInvert | 6684742 | Kaynak ve hedef bölgelerin renkleri XOR'lanır. |
| SourceAnd | 8913094 | Kaynak ve hedef bölgelerin renkleri AND'lenir. |
| MergePaint | 12255782 | Ters çevrilmiş kaynak bölgenin renkleri, hedef bölgenin renkleriyle OR'lanır. |
| MergeCopy | 12583114 | Kaynak bölgenin renkleri, hedef cihaz bağlamında seçili fırçanın renkleriyle AND'lenir. |
| SourceCopy | 13369376 | Kaynak bölge doğrudan hedef bölgeye kopyalanır. |
| SourcePaint | 15597702 | Kaynak ve hedef bölgelerin renkleri OR'lanır. |
| PatCopy | 15728673 | Hedef aygıt bağlamında şu anda seçili fırça, hedef bitmap'e kopyalanır. |
| PatPaint | 16452105 | Hedef aygıt bağlamında şu anda seçili fırçanın renkleri, ters çevrilmiş kaynak bölgenin renkleriyle OR işlemine tabi tutulur. Bu işlemin sonucu, hedef bölgenin renkleriyle OR işlemine tabi tutulur. |
| Whiteness | 16711778 | Hedef bölge, fiziksel palet içinde indeks 1'deki renk kullanılarak doldurulur. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) uygulamanın penceresinin üzerine katmanlananlar sonuç görüntüsüne dahil edilir. |

## Ayrıca Bakınız

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
