---
title: "System::Net::WebRequest::RegisterPrefix metodu"
linktitle: "RegisterPrefix"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebRequest::RegisterPrefix yöntemi. Belirtilen URI için WebRequest türetilmiş sınıfını C++'ta kaydeder."
type: docs
weight: 600
url: /tr/cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Belirtilen URI için [WebRequest](../) türetilmiş sınıfını kaydeder.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | String | URI ya da URI öneki. |
| creator | System::SharedPtr\<IWebRequestCreate\> | [WebRequest](../) sınıfının yeni örneklerini oluşturur. |

### ReturnValue

Belirtilen URI için [WebRequest](../) türetilmiş sınıfı başarıyla kaydedildiğinde doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
