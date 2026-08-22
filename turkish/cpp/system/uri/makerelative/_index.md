---
title: "System::Uri::MakeRelative yöntemi"
linktitle: "MakeRelative"
second_title: "Aspose.PUB için C++"
description: "System::Uri::MakeRelative yöntemi. C++'ta iki Uri örneği arasındaki farkı belirler."
type: docs
weight: 3000
url: /tr/cpp/system/uri/makerelative/
---
## Uri::MakeRelative method


İki [Uri](../) örneği arasındaki farkı belirler.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| toUri | const SharedPtr\<Uri\>\& | Mevcut URI ile karşılaştırılacak URI |

### ReturnValue

Eğer mevcut nesne ve **toUri** tarafından temsil edilen URI'ların ana bilgisayar adı ve şeması aynı ise, bu yöntem mevcut URI örneğine eklendiğinde **toUri** sonucunu veren, göreli bir [String](../../string/) döndürür. Eğer ana bilgisayar adı veya şema farklı ise, bu yöntem **uri** parametresini temsil eden bir [String](../../string/) döndürür.

## Ayrıca Bakınız

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
