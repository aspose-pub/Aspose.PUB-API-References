---
title: "System::Xml::XmlReader::ReadElementString yöntemi"
linktitle: "ReadElementString"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::ReadElementString yöntemi. Yalnızca metin içeren bir öğeyi okur. Ancak, C++'ta bu işlemi daha basit bir şekilde ele almasını sağladığı için XmlReader::ReadElementContentAsString yönteminin kullanılması önerilir."
type: docs
weight: 6400
url: /tr/cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde ele almasını sağladığı için [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yönteminin kullanılması önerilir.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Bulunan öğenin [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini, yalnızca metin içeren bir öğeyi okumadan önce kontrol eder. Ancak, bu işlemi daha doğrudan bir şekilde ele almasını sağladığı için yerine [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yönteminin kullanılması önerilir.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yerel ad | String | Kontrol edilecek yerel ad. |
| ns | String | Kontrol edilecek ad alanı URI'si. |

### ReturnValue

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::ReadElementString(String) method


Bulunan öğenin [XmlReader::get_Name](../get_name/) değerinin verilen dizeyle eşleştiğini, yalnızca metin içeren bir öğeyi okumadan önce kontrol eder. Ancak, bu işlemi daha doğrudan bir şekilde ele almasını sağladığı için yerine [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yönteminin kullanılması önerilir.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Kontrol edilecek ad. |

### ReturnValue

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
