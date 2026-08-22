---
title: "System::Xml::XmlTextWriter::WriteDocType yöntemi"
linktitle: "WriteDocType"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextWriter::WriteDocType yöntemi. C++'ta belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar."
type: docs
weight: 2500
url: /tr/cpp/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType method


Belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | const String\& | DOCTYPE'un adı. Bu boş olmamalıdır. |
| pubid | const String\& | Eğer null değilse ayrıca PUBLIC "pubid" "sysid" yazar; burada **pubid** ve **sysid**, verilen argümanların değeriyle değiştirilir. |
| sysid | const String\& | Eğer **pubid** null ve **sysid** null değilse SYSTEM "sysid" yazar; burada **sysid**, bu argümanın değeriyle değiştirilir. |
| subset | const String\& | Eğer null değilse [subset] yazar; burada subset, bu argümanın değeriyle değiştirilir. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
