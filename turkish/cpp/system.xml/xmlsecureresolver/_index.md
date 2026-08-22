---
title: "System::Xml::XmlSecureResolver sınıfı"
linktitle: "XmlSecureResolver"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlSecureResolver sınıfı. XmlResolver nesnesini sarmalayarak ve temel XmlResolver'ın erişebileceği kaynakları kısıtlayarak başka bir XmlResolver uygulamasını güvenli hale getirmeye yardımcı olur C++'ta."
type: docs
weight: 3600
url: /tr/cpp/system.xml/xmlsecureresolver/
---
## XmlSecureResolver class


Temel [XmlResolver](../xmlresolver/) nesnesinin erişebileceği kaynakları kısıtlayarak ve [XmlResolver](../xmlresolver/) nesnesini sarmalayarak başka bir [XmlResolver](../xmlresolver/) uygulamasını güvenli hale getirmeye yardımcı olur.

```cpp
class XmlSecureResolver : public System::Xml::XmlResolver
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Temel [XmlResolver](../xmlresolver/) üzerinde **ResolveUri** metodunu çağırarak temel ve göreli URI'lerden mutlak URI'yi çözer. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Web isteklerini kimlik doğrulamak için kullanılan kimlik bilgilerini ayarlar. |
| [XmlSecureResolver](./xmlsecureresolver/)(const SharedPtr\<XmlResolver\>\&, const String\&) | Sağlanan [XmlResolver](../xmlresolver/) ve URL ile [XmlSecureResolver](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
