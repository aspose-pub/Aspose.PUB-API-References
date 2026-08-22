---
title: "System::Xml::Schema::XmlSchemaCollectionEnumerator sınıfı"
linktitle: "XmlSchemaCollectionEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaCollectionEnumerator sınıfı. Bir koleksiyon üzerinde basit yinelemeyi destekler. Bu sınıf C++'ta kalıtılamaz."
type: docs
weight: 1600
url: /tr/cpp/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator class


Bir koleksiyon üzerinde basit yinelemeyi destekler. Bu sınıf kalıtılamaz.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| [Dispose](./dispose/)() override | Hiçbir şey yapmaz. |
| [get_Current](./get_current/)() const override | Koleksiyondaki mevcut [XmlSchema](../xmlschema/) döndürür. |
| [MoveNext](./movenext/)() override | Yineleyiciyi koleksiyondaki bir sonraki şemaya ilerletir. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
