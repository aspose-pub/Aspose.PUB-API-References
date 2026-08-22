---
title: "System::Xml::Xsl::XsltArgumentList sınıfı"
linktitle: "XsltArgumentList"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XsltArgumentList sınıfı. C++'ta XSLT parametreleri veya uzantı nesneleri olabilen değişken sayıda argüman içerir."
type: docs
weight: 400
url: /tr/cpp/system.xml.xsl/xsltargumentlist/
---
## XsltArgumentList class


XSLT parametreleri veya uzantı nesneleri olabilen değişken sayıda bağımsız değişken içerir.

```cpp
class XsltArgumentList : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddExtensionObject](./addextensionobject/)(const String\&, const SharedPtr\<Object\>\&) | Yeni bir nesneyi [XsltArgumentList](./) içine ekler ve onu namespace URI'siyle ilişkilendirir. |
| [AddParam](./addparam/)(const String\&, const String\&, const SharedPtr\<Object\>\&) | Bir parametreyi [XsltArgumentList](./) içine ekler ve onu namespace nitelikli adıyla ilişkilendirir. |
| [Clear](./clear/)() | [XsltArgumentList](./) içindeki tüm parametreleri ve uzantı nesnelerini kaldırır. |
| [GetExtensionObject](./getextensionobject/)(const String\&) | Verilen namespace ile ilişkilendirilmiş nesneyi döndürür. |
| [GetParam](./getparam/)(const String\&, const String\&) | Namespace nitelikli adıyla ilişkili parametreyi döndürür. |
| [RemoveExtensionObject](./removeextensionobject/)(const String\&) | Namespace URI'sine sahip nesneyi [XsltArgumentList](./) listesinden kaldırır. |
| [RemoveParam](./removeparam/)(const String\&, const String\&) | [XsltArgumentList](./) listesinden parametreyi kaldırır. |
| [XsltArgumentList](./xsltargumentlist/)() | Yeni bir [XsltArgumentList](./) örneği oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PUB for C++](../../)
