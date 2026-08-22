---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method"
linktitle: "GetNameValueListLength"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method. Belirtilen indeksden başlayan bir dizeyi NameValueHeaderValue sınıfı örneklerinin koleksiyonuna dönüştürür ve C++'da ayrıştırılmış bir alt dize uzunluğunu döndürür."
type: docs
weight: 1000
url: /tr/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength method


Belirtilen indexten itibaren verilen bir dizeyi NameValueHeaderValue-class örneklerinin koleksiyonuna dönüştürür ve ayrıştırılan bir alt dize uzunluğunu döndürür.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | String | Analiz edilecek bir dize. |
| startIndex | int32_t | Analiz için bir başlangıç konumu. |
| ayraç | char16_t | Belirtilen dizedeki öğeleri ayırmak için kullanılan bir dize. |
| nameValueCollection | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | Ayrıştırılmış bir koleksiyonun atanacağı çıktı parametresi. |

### ReturnValue

Ayrıştırılmış bir alt dize uzunluğu.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PUB for C++](../../../)
