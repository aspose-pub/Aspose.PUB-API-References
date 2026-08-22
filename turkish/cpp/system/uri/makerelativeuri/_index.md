---
title: "System::Uri::MakeRelativeUri yöntemi"
linktitle: "MakeRelativeUri"
second_title: "Aspose.PUB için C++"
description: "System::Uri::MakeRelativeUri yöntemi. Geçerli ve belirtilen Uri nesneleri tarafından temsil edilen URI'lar arasındaki farkı belirler (C++)."
type: docs
weight: 3100
url: /tr/cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri method


Geçerli ve belirtilen [Uri](../) nesneleri tarafından temsil edilen URI'lar arasındaki farkı belirler.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | Karşılaştırılan değer |

### ReturnValue

Eğer geçerli nesne tarafından temsil edilen URI'ların ana bilgisayar adı ve şeması **toUri** ile aynıysa, bu yöntem geçerli URI örneğine eklendiğinde **toUri** elde edilen bir göreli [Uri](../) döndürür. Ana bilgisayar adı veya şema farklıysa, bu yöntem **uri** parametresini temsil eden bir [Uri](../) nesnesi döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
