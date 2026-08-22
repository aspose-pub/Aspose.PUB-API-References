---
title: "System::Xml::XmlNamespaceManager sınıfı"
linktitle: "XmlNamespaceManager"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNamespaceManager sınıfı. Bir koleksiyona ad alanlarını çözer, ekler ve kaldırır ve bu ad alanları için C++'ta kapsam yönetimi sağlar."
type: docs
weight: 2300
url: /tr/cpp/system.xml/xmlnamespacemanager/
---
## XmlNamespaceManager class


Ad alanlarını bir koleksiyona çözer, ekler ve kaldırır ve bu ad alanları için kapsam yönetimi sağlar.

```cpp
class XmlNamespaceManager : public System::Xml::IXmlNamespaceResolver,
                            public System::Collections::Generic::IEnumerable<String>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [AddNamespace](./addnamespace/)(String, String) | Verilen ad alanını koleksiyona ekler. |
| virtual [get_DefaultNamespace](./get_defaultnamespace/)() | Varsayılan ad alanı için ad alanı URI'sını döndürür. |
| virtual [get_NameTable](./get_nametable/)() | Bu nesneyle ilişkili [XmlNameTable](../xmlnametable/) döndürür. |
| [GetEnumerator](./getenumerator/)() override | İsim alanları arasında yineleme yapmak için kullanılacak bir yineleyici döndürür [XmlNamespaceManager](./) içinde. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Şu anda kapsamda olan isim alanlarını sıralamak için kullanılabilecek, önek ile anahtarlanan isim alanı adlarının bir koleksiyonunu döndürür. |
| virtual [HasNamespace](./hasnamespace/)(String) | Sağlanan önek için mevcut itilen kapsamda tanımlı bir isim alanı olup olmadığını gösteren bir değer döndürür. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Belirtilen önek için isim alanı URI'sını döndürür. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Verilen isim alanı URI'si için bildirilen önek'i bulur. |
| virtual [PopScope](./popscope/)() | İsim alanı kapsamını yığından çıkarır. |
| virtual [PushScope](./pushscope/)() | İsim alanı kapsamını yığına ekler. |
| virtual [RemoveNamespace](./removenamespace/)(String, String) | Verilen önek için verilen isim alanını kaldırır. |
| [XmlNamespaceManager](./xmlnamespacemanager/)(const SharedPtr\<XmlNameTable\>\&) | Belirtilen [XmlNameTable](../xmlnametable/) ile yeni bir [XmlNamespaceManager](./) sınıfı örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
