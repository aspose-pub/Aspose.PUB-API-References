---
title: "System::Xml::XmlUrlResolver sınıfı"
linktitle: "XmlUrlResolver"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlUrlResolver sınıfı. C++'ta Birleşik Kaynak Tanımlayıcısı (URI) ile adlandırılan dış XML kaynaklarını çözer."
type: docs
weight: 4100
url: /tr/cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Bir Evrensel Kaynak Tanımlayıcısı (URI) tarafından adlandırılan harici XML kaynaklarını çözer.

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Temel ve göreli URI'lerden mutlak URI'yi çözer. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Temel WebRequest nesnesi için önbellek politikasını ayarlar. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Web isteklerini kimlik doğrulamak için kullanılan kimlik bilgilerini ayarlar. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Temel WebRequest nesnesi için ağ proxy'sini ayarlar. |
| [XmlUrlResolver](./xmlurlresolver/)() | [XmlUrlResolver](./) sınıfının yeni bir örneğini başlatır. |
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
