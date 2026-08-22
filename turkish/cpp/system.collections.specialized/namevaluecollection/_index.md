---
title: "System::Collections::Specialized::NameValueCollection sınıfı"
linktitle: "NameValueCollection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Specialized::NameValueCollection sınıfı. İlgili String anahtarları ve String değerlerinden oluşan koleksiyon, C++'ta anahtar ya da indeks ile erişilebilir."
type: docs
weight: 200
url: /tr/cpp/system.collections.specialized/namevaluecollection/
---
## NameValueCollection class


İlgili [String](../../system/string/) anahtarları ve [String](../../system/string/) değerlerinden oluşan koleksiyon, anahtar ya da indeks ile erişilebilir.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const String\&) override | Geçersiz kıl [ICollection](../../system.collections/icollection/) metodu - uygulanmadı. |
| [Add](./add/)(const System::SharedPtr\<NameValueCollection\>\&) | Belirtilen [NameValueCollection](./) içindeki girişleri mevcut nesneye kopyalar. |
| virtual [Add](./add/)(const String\&, const String\&) | Belirtilen ad ve değerle bir giriş ekler. |
| [Clear](./clear/)() override | Tüm öğeleri siler. |
| [Contains](./contains/)(const String\&) const override | Öğenin koleksiyonda bulunup bulunmadığını kontrol eder. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override | Koleksiyon öğelerini mevcut dizi öğelerine kopyalar. |
| virtual [Get](./get/)(const String\&) | Belirtilen anahtara ilişkin değerleri alır. |
| virtual [get_AllKeys](./get_allkeys/)() | Tüm anahtarları alır. |
| [get_Count](./get_count/)() const override | Anahtar/değer çiftlerinin sayısını alır. |
| virtual [get_Keys](./get_keys/)() | Tüm anahtarları alır. |
| [GetEnumerator](./getenumerator/)() override | Koleksiyon içinde yineleme yapmak için bir enumerator alır. |
| virtual [GetValues](./getvalues/)(const String\&) | Belirtilen anahtara ilişkin değerleri alır. |
| [HasKeys](./haskeys/)() | [NameValueCollection](./) içinde null olmayan anahtarların bulunup bulunmadığını gösteren bir değer alır. |
| [idx_get](./idx_get/)(const String\&) | Belirtilen dizindeki değeri alır. |
| [idx_set](./idx_set/)(const String\&, const String\&) | Bir girişin değerini ayarlar. |
| [NameValueCollection](./namevaluecollection/)() | Boş olan [NameValueCollection](./) sınıfının yeni bir örneğini başlatır. |
| [NameValueCollection](./namevaluecollection/)(const System::SharedPtr\<NameValueCollection\>\&) | Belirtilen [NameValueCollection](./) içindeki girişleri yeni bir [NameValueCollection](./) sınıfına kopyalar. |
| [Remove](./remove/)(const String\&) override | Belirli öğeyi kaldırır. |
| virtual [Set](./set/)(const String\&, const String\&) | Bir girişin değerini ayarlar. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Ayrıca Bakınız

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PUB for C++](../../)
