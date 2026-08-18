---
title: "System::Xml::XmlReaderSettings::get_NameTable Methode"
linktitle: "get_NameTable"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlReaderSettings::get_NameTable Methode. Gibt die XmlNameTable zurück, die für atomisierte Zeichenkettenvergleiche in C++ verwendet wird."
type: docs
weight: 1500
url: /de/cpp/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable method


Gibt die [XmlNameTable](../../xmlnametable/) zurück, die für atomisierte Zeichenkettenvergleiche verwendet wird.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ReturnValue

Die [XmlNameTable](../../xmlnametable/), die alle atomisierten Zeichenketten speichert, die von allen [XmlReader](../../xmlreader/)-Instanzen verwendet werden, die mit diesem [XmlReaderSettings](../)-Objekt erstellt wurden. Der Standardwert ist **nullptr**. Die erstellte [XmlReader](../../xmlreader/)-Instanz verwendet ein neues leeres [NameTable](../../nametable/), wenn dieser Wert **nullptr** ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
