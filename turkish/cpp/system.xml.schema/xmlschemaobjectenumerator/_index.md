---
title: "System::Xml::Schema::XmlSchemaObjectEnumerator sınıfı"
linktitle: "XmlSchemaObjectEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaObjectEnumerator sınıfı. C++'da XmlSchemaObjectCollection için yineleyiciyi temsil eder."
type: docs
weight: 5200
url: /tr/cpp/system.xml.schema/xmlschemaobjectenumerator/
---
## XmlSchemaObjectEnumerator class


[XmlSchemaObjectCollection](../xmlschemaobjectcollection/) için yineleyiciyi temsil eder.

```cpp
class XmlSchemaObjectEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| [Dispose](./dispose/)() override | Hiçbir şey yapmaz. |
| [get_Current](./get_current/)() const override | Koleksiyondaki mevcut [XmlSchemaObject](../xmlschemaobject/) döndürür. |
| [MoveNext](./movenext/)() override | Koleksiyondaki bir sonraki öğeye geçer. |
| [Reset](./reset/)() override | Yineleyiciyi koleksiyonun başına sıfırlar. |
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
