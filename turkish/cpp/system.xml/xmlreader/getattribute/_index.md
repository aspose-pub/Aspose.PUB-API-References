---
title: "System::Xml::XmlReader::GetAttribute metodu"
linktitle: "GetAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::GetAttribute metodu. Türetilmiş bir sınıfta geçersiz kılındığında, C++'da belirtilen indeksle özniteliğin değerini alır."
type: docs
weight: 2800
url: /tr/cpp/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(int32_t) method


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeksle özniteliğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | int32_t | Özniteliğin indeksi. İndeks sıfır tabanlıdır. (İlk öznitelik indeks 0'a sahiptir.) |

### ReturnValue

Belirtilen özniteliğin değeri. Bu metod okuyucuyu hareket ettirmez.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::GetAttribute(String) method


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../get_name/) değeriyle özniteliğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Niteliğin nitelikli adı. |

### ReturnValue

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa veya değer [String::Empty](../../../system/string/empty/) ise, **nullptr** döndürülür.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::GetAttribute(String, String) method


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerleriyle özniteliğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Özniteliğin yerel adı. |
| namespaceURI | String | Özniteliğin ad alanı URI'si. |

### ReturnValue

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa veya değer [String::Empty](../../../system/string/empty/) ise, **nullptr** döndürülür. Bu metod okuyucuyu hareket ettirmez.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
