---
title: "System::Collections::Generic::BaseDictionary sınıfı"
linktitle: "BaseDictionary"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::BaseDictionary sınıfı. Çeşitli sözlük benzeri veri yapılarına (ör. Dictionary, SortedDictionary) ortak kodu uygular. Doğrudan kullanılmamalıdır, yalnızca konteyner tanımlarken kalıtım için kullanılabilir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığında veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 500
url: /tr/cpp/system.collections.generic/basedictionary/
---
## BaseDictionary class


Çeşitli sözlük benzeri veri yapılarına (ör. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)) ortak kod uygular. Doğrudan kullanılmamalıdır, yalnızca kapsayıcılar tanımlanırken kalıtım için kullanılabilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```


| Parametre | Açıklama |
| --- | --- |
| Harita | Temel harita türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | C++'a özgü. |
| [Add](./add/)(const key_t\&, const mapped_t\&) override | Sözlüğe anahtar-değer çifti ekler. |
| [BaseDictionary](./basedictionary/)() | Boş veri yapısı oluşturur. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Temel harita yapıcısına argümanları iletmek için yönlendiren kurucu. |
| [BaseDictionary](./basedictionary/)(BaseType *, const Args\&...) | Kopyalama kurucusu. |
| [BaseDictionary](./basedictionary/)(BaseType *) | Kopyalama kurucusu. |
| [begin](./begin/)() const | Kapsayıcının anahtar-değer öğesi için KVPair sarmalayıcısına bir yineleyici döndürür. C# tarzında uygulanmıştır - yineleyici, get_Key() ve get_Value() arayüzüne sahip KVPair nesnesini döndürmelidir. Kapsayıcı boş ise, döndürülen yineleyici [end()](../ienumerable/end/) ile eşit olacaktır. |
| [cbegin](./cbegin/)() const | Kapsayıcının ilk öğesine bir yineleyici döndürür. STL tarzında uygulanmıştır. Kapsayıcı boş ise, döndürülen yineleyici [end()](../ienumerable/end/) ile eşit olacaktır. |
| [cend](./cend/)() const | Kapsayıcının son öğesini izleyen öğeye bir yineleyici döndürür. STL tarzında uygulanmıştır. Bu öğe bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [Clear](./clear/)() override | Tüm öğeleri siler. |
| [ContainsKey](./containskey/)(const key_t\&) const override | Anahtarın sözlükte bulunup bulunmadığını kontrol eder. |
| [ContainsValue](./containsvalue/)(const mapped_t\&) | Değerin sözlükte bulunup bulunmadığını kontrol eder. Değerleri karşılaştırmak için == operatörünü kullanır. |
| [data](./data/)() | Temel veri depolama erişicisi. |
| [data](./data/)() const | Temel veri depolama erişicisi. |
| [end](./end/)() const | Kapsayıcının son öğesini izleyen anahtar-değer öğesi için KVPair sarmalayıcısına bir yineleyici döndürür. C# tarzında uygulanmıştır - yineleyici, get_Key() ve get_Value() arayüzüne sahip KVPair nesnesini döndürmelidir. Bu öğe bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [get_Count](./get_count/)() const override | Öğelerin sayısını alır. |
| virtual [GetEnumerator](./getenumerator/)() | Enumerator örneği oluşturur, alt sınıf tarafından uygulanmalıdır. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Bulunursa değeri döndürür; aksi takdirde **Value()** döndürür. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Bulunursa değeri döndürür; aksi takdirde **defaultValue** döndürür. |
| [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Bulunursa değeri döndürür; aksi takdirde **null** döndürür. Yalnızca referans tipleri için anlamlıdır. |
| [idx_get](./idx_get/)(const key_t\&) const override | Anahtarlı alıcı işlev. |
| [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Anahtarlı ayarlayıcı işlev. Öğeyi değiştirir veya oluşturur. |
| virtual [operator[]](./operator[]/)(const key_t\&) | Erişimci işlev. |
| [Remove](./remove/)(const key_t\&) override | Sözlükten belirli anahtarı kaldırır. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Anahtarlı değeri arar ve bulunursa getirir. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Uygulanan arayüz. |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [iterator](./iterator/) | Yineleyici türü. |
| [KeyCollection](./keycollection/) | Temel depolama türüyle doğru ayırıcıyı kullandığımızdan emin olun. |
| [KVPair](./kvpair/) | Anahtar-değer çifti tipi. |
| [map_t](./map_t/) | İç harita türü. |
| [ValueCollection](./valuecollection/) | Değerlerin koleksiyonu. |

## Ayrıca Bakınız

* Class [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
