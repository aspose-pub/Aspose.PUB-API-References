---
title: "System::Xml::XmlReader::get_SchemaInfo Methode"
linktitle: "get_SchemaInfo"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlReader::get_SchemaInfo Methode. Gibt die Schemainformation zurück, die dem aktuellen Knoten als Ergebnis der Schemagültigkeitsprüfung in C++ zugewiesen wurde."
type: docs
weight: 2200
url: /de/cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Gibt die Schemainformation zurück, die dem aktuellen Knoten infolge einer Schemavalidierung zugewiesen wurde.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

Ein IXmlSchemaInfo‑Objekt, das die Schemainformation für den aktuellen Knoten enthält. [Schema](../../../system.xml.schema/)‑Informationen können an Elementen, Attributen oder an Textknoten mit einem nicht‑null [XmlReader::get_ValueType](../get_valuetype/) Wert festgelegt werden. Wenn der aktuelle Knoten keiner der oben genannten Knotentypen ist oder wenn die [XmlReader](../)‑Instanz keine Schemainformation meldet, gibt diese Methode **nullptr** zurück. Wenn diese Methode von einem [XmlTextReader](../../xmltextreader/) oder einem [XmlValidatingReader](../../xmlvalidatingreader/) Objekt aufgerufen wird, gibt sie stets **nullptr** zurück. Diese [XmlReader](../)‑Implementierungen stellen Schemainformationen nicht über die get_SchemaInfo‑Methode bereit.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
