---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldValue yöntemi"
linktitle: "get_OldValue"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldValue yöntemi. Düğümün orijinal değerini C++'da döndürür."
type: docs
weight: 700
url: /tr/cpp/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue method


Düğümün orijinal değerini döndürür.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### ReturnValue

Düğümün orijinal değeri. Bu yöntem, düğüm bir öznitelik ya da metin düğümü değilse veya düğüm ekleniyorsa **nullptr** döndürür. **XmlDocument::NodeChanging** olayında çağrılırsa, **get_OldValue** değişiklik başarılı olursa değiştirilecek düğümün mevcut değerini döndürür. **XmlDocument::NodeChanged** olayında çağrılırsa, **get_OldValue** değişiklik öncesindeki düğüm değerini döndürür.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
