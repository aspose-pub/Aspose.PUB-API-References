---
title: "System::Xml::XmlDocument::CreateXmlDeclaration yöntemi"
linktitle: "CreateXmlDeclaration"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDocument::CreateXmlDeclaration yöntemi. Belirtilen değerlerle bir XmlDeclaration düğümü oluşturur C++'da."
type: docs
weight: 1600
url: /tr/cpp/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration method


Belirtilen değerlerle bir [XmlDeclaration](../../xmldeclaration/) düğümü oluşturur.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sürüm | const String\& | Sürüm "1.0" olmalıdır. |
| encoding | const String\& | Encoding özniteliğinin değeri. Bu, [XmlDocument](../) bir dosyaya veya akışa kaydettiğinizde kullanılan kodlamadır; bu nedenle, [Text::Encoding](../../../system.text/encoding/) sınıfı tarafından desteklenen bir dizeye ayarlanmalıdır, aksi takdirde "XmlDocument::Save(String)" başarısız olur. Bu değer **nullptr** veya [String::Empty](../../../system/string/empty/) ise, [XmlDocument::Save](../save/) yöntemi XML bildiriminde bir encoding özniteliği yazmaz ve bu yüzden varsayılan kodlama, UTF-8, kullanılır. |
| standalone | const String\& | Değer "yes" ya da "no" olmalıdır. Bu değer **nullptr** veya [String::Empty](../../../system/string/empty/) ise, [XmlDocument::Save](../save/) yöntemi XML bildiriminde bir standalone özniteliği yazmaz. |

### ReturnValue

Yeni [XmlDeclaration](../../xmldeclaration/) düğümü.
## Açıklamalar



Not: Eğer [XmlDocument](../) bir TextWriter ya da bir [XmlTextWriter](../../xmltextwriter/) üzerine kaydedilirse, bu kodlama değeri göz ardı edilir. Bunun yerine, TextWriter'ın ya da [XmlTextWriter](../../xmltextwriter/)’ın kodlaması kullanılır. Bu, dışa yazılan XML'in doğru kodlamayla tekrar okunabilmesini sağlar.
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
