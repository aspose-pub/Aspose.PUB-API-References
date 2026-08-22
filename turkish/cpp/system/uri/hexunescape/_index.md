---
title: "System::Uri::HexUnescape yöntemi"
linktitle: "HexUnescape"
second_title: "Aspose.PUB için C++"
description: "System::Uri::HexUnescape yöntemi. Belirtilen bir karakterin onaltılık temsilini C++'ta bir karaktere dönüştürür."
type: docs
weight: 4000
url: /tr/cpp/system/uri/hexunescape/
---
## Uri::HexUnescape method


Belirtilen karakterin onaltılık temsilini bir karaktere dönüştürür.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desen | const String\& | Bir karakterin onaltılık temsilini içeren bir dize |
| indeks | int32_t\& | **pattern** içinde bir karakterin onaltılık temsilinin başladığı konum |

### ReturnValue

**index** konumundaki onaltılık kodlamayla temsil edilen karakter. **index** konumundaki karakter onaltılık kodlanmamışsa, **index** konumundaki karakter döndürülür. **index** değeri, döndürülen karakterin ardından gelen karakteri gösterecek şekilde artırılır.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
