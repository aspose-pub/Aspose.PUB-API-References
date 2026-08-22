---
title: "System::Object sınıfı"
linktitle: "Nesne"
second_title: "Aspose.PUB için C++"
description: "System::Object sınıfı. C#'ta System.Object sınıfı için mevcut olan yöntemlerin kullanılmasını sağlayan temel sınıf. Çevrilmiş ortamda kullanılan tüm önemsiz olmayan sınıflar C++ içinde bundan türemelidir."
type: docs
weight: 4800
url: /tr/cpp/system/object/
---
## Object class


C#'ta [System.Object](./) sınıfı için mevcut olan yöntemlerin kullanılmasını sağlayan temel sınıf. Çevrilmiş ortamda kullanılan tüm önemsiz olmayan sınıflar bundan türemelidir.

```cpp
class Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Equals](./equals/)(ptr) | C# [Object.Equals](./equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static [Equals](./equals/)(float const\&, float const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static [Equals](./equals/)(double const\&, double const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| virtual [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [GetCounter](./getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [GetHashCode](./gethashcode/)() const | C# [Object.GetHashCode()](./gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [GetType](./gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](./gettype/) çağrısının analoğu. |
| virtual [Is](./is/)(const TypeInfo\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| [Lock](./lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| virtual [MemberwiseClone](./memberwiseclone/)() const | C# [Object.MemberwiseClone()](./memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](./object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](./object/)(Object const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [operator=](./operator=/)(Object const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static [ReferenceEquals](./referenceequals/)(ptr const\&, ptr const\&) | Nesneleri referansına göre karşılaştırır. |
| static [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| [ReferenceEquals](./referenceequals/)(String const\&, std::nullptr_t) | Dize ve nullptr durumu için [Object::ReferenceEquals](./referenceequals/) özelleştirmesi. |
| [ReferenceEquals](./referenceequals/)(String const\&, String const\&) | Dizeler durumu için [Object::ReferenceEquals](./referenceequals/) özelleştirmesi. |
| [RemovedSharedRefs](./removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) olarak ayarlayın. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| [SharedCount](./sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [SharedRefAdded](./sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [ToString](./tostring/)() const | C# [Object.ToString()](./tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static [Type](./type/)() | C# typeof([System.Object](./)) yapısını uygular. |
| [Unlock](./unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| [WeakRefAdded](./weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [WeakRefRemoved](./weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [~Object](./~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ptr](./ptr/) | Akıllı işaretçi türü için takma ad. |
## Açıklamalar


C# [System.Object](./) sınıfında mevcut olan yöntemlerin yanı sıra, çevrilen kod ortamına özgü bazı kavramlar için de destek sağlar. Bu, akıllı işaretçi sınıfları tarafından kullanılan referans sayımını ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) ve bellek yönetimi, hata ayıklama vb. ile ilgili diğer hizmetleri içerir.

Her [Object](./) iki referans sayacına sahiptir: paylaşılan referans sayacı ve zayıf referans sayacı. Zayıf referans sayacı, referans verilen nesnenin üzerine çıkabilen zayıf işaretçilere izin vermek için, her zaman [Object](./) içinde değil, ayrılmış bir veri yapısında depolanır. Akıllı referans sayacı, ENABLE_EXTERNAL_REFCOUNT makrosunun durumuna bağlı olarak nesnenin içinde ya da aynı ayrılmış yapıda depolanır. Varsayılan olarak, hata ayıklama derlemelerinde etkin, yayın derlemelerinde devre dışıdır. Akıllı işaretçi sayacı nesnenin içinde depolanıyorsa, ayrılmış veri yapısı yalnızca nesneye zayıf işaretçiler mevcut olduğunda oluşturulur. Aksi takdirde, nesneyle birlikte oluşturulur.

Tüm akıllı işaretçiler bu iki referans sayacını kullanır ve aynı tek sahiplik grubuna katkıda bulunur.

Eğer [Object](./) alt sınıfı yığında oluşturulursa, ona yönelik akıllı işaretçiler oluşturulamaz, aksi takdirde yığın silme sorunu ortaya çıkar.

Bu tip, değer türü olarak yığında ya da [System::MakeObject()](../makeobject/) işleviyle yığında tahsis edilebilir. Nesne tahsis edildikten sonra, bu iki kullanım durumunu asla karıştırmayın: yığında tahsis edilen nesnelere yönelik [SmartPtr](../smartptr/) işaretçileri kullanmak kesinlikle yasaktır.
## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
