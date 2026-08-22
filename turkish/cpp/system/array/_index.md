---
title: "System::Array sınıfı"
linktitle: "Dizi"
second_title: "Aspose.PUB için C++"
description: "System::Array sınıfı. Bir dizi veri yapısını temsil eden sınıf. Bu sınıfın nesneleri yalnızca System::MakeArray() ve System::MakeObject() işlevleri kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 200
url: /tr/cpp/system/array/
---
## Array class


Sınıf, bir dizi veri yapısını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeArray()](../makearray/) ve [System::MakeObject()](../makeobject/) işlevleri kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ve operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class Array : public virtual System::Object,
                                  public System::Collections::Generic::IList<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Bir dizinin öğelerinin tipi |
## Nested classes

* Class [Enumerator](./enumerator/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const T\&) override | Desteklenmiyor çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okunur. |
| [Array](./array/)() | Boş bir dizi oluşturur. |
| [Array](./array/)(int, const T\&) | Doldurma yapıcı. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) | Doldurma yapıcı. |
| [Array](./array/)(int, const T) | Doldurma yapıcı. |
| [Array](./array/)(vector_t\&&) | Taşıma yapıcı. |
| [Array](./array/)(const vector_t\&) | Kopya yapıcı. |
| [Array](./array/)(const std::vector\<Q\>\&) | Bir [Array](./) nesnesi oluşturur ve değerlerini, değer tipinin **T** ile aynı ancak **UnderlyingType**'tan farklı olduğu bir std::vector nesnesinden kopyalanan değerlerle doldurur. |
| [Array](./array/)(std::vector\<Q\>\&&) | Bir [Array](./) nesnesi oluşturur ve değerlerini, değer tipinin **T** ile aynı ancak **UnderlyingType**'tan farklı olduğu bir std::vector nesnesinden taşınan değerlerle doldurur. |
| [Array](./array/)(std::initializer_list\<UnderlyingType\>) | Belirtilen **UnderlyingType** tipinde öğeler içeren başlatıcı listeden değerleri alarak bir [Array](./) nesnesi oluşturur ve doldurur. |
| [Array](./array/)(const std::array\<UnderlyingType, InitArraySize\>\&) | Belirtilen **UnderlyingType** tipinde öğeler içeren dizi üzerinden değerleri alarak bir [Array](./) nesnesi oluşturur ve doldurur. |
| [Array](./array/)(std::initializer_list\<bool\>, int) | Belirtilen bool tipinde öğeler içeren başlatıcı listeden değerleri alarak bir [Array](./) nesnesi oluşturur ve doldurur. |
| [begin](./begin/)() | Konteynerin ilk elemanına bir yineleyici döndürür. Eğer konteyner boşsa, döndürülen yineleyici [end()](./end/) ile eşit olacaktır. |
| [begin](./begin/)() const | Const nitelikli konteynerin ilk elemanına bir yineleyici döndürür. Eğer konteyner boşsa, döndürülen yineleyici [end()](./end/) ile eşit olacaktır. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const T\&) | Sıralı dizide ikili arama gerçekleştirir. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) | UYGULANMADI. |
| [cbegin](./cbegin/)() const | Konteynerin ilk const nitelikli elemanına bir yineleyici döndürür. Eğer konteyner boşsa, döndürülen yineleyici [cend()](./cend/) ile eşit olacaktır. |
| [cend](./cend/)() const | Konteynerin son elemanını takiben gelen elemana bir yineleyici döndürür. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [Clear](./clear/)() override | Desteklenmiyor çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okunur. |
| static [Clear](./clear/)(const ArrayPtr\<Type\>\&, int, int) | **startIndex** indeksinden başlayarak belirtilen dizideki **count** değerlerini varsayılan değerlerle değiştirir. |
| [Clone](./clone/)() | Diziyi klonlar. |
| static [ConstrainedCopy](./constrainedcopy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Belirtilen kaynaktan başlayarak bir [System.Array](./) içindeki öğe aralığını kopyalar. |
| [Contains](./contains/)(const T\&) const override | Belirtilen öğenin dizi içinde olup olmadığını belirler. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) | Yeni bir [Array](./) nesnesi oluşturur ve belirtilen dönüştürücü temsilcisi kullanılarak belirtilen dizinin öğelerini **OutputType** tipine dönüştürülmüş şekilde doldurur. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) | Yeni bir [Array](./) nesnesi oluşturur ve belirtilen dönüştürücü fonksiyon nesnesi kullanılarak belirtilen dizinin öğelerini **OutputType** tipine dönüştürülmüş şekilde doldurur. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Belirtilen sayıda öğeyi kaynak diziden hedef diziye kopyalar. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) | Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef diziye kopyalar. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) | Belirtilen sayıda öğeyi kaynak diziden hedef dizi görünümüne kopyalar. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) | Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef dizi görünümüne kopyalar. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Yığıt üzerindeki kaynak diziden hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) | Kaynak diziden yığıt üzerindeki hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) | Yığıt üzerindeki kaynak diziden yığıt üzerindeki hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak dizi görünümünden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak dizi görünümünden belirtilen sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak yığıt üzerindeki kaynak diziden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi yığıt üzerindeki hedef dizideki belirtilen konuma kopyalar. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak yığıt üzerindeki kaynak diziden yığıt üzerindeki hedef dizideki belirtilen konuma belirtilen sayıda öğeyi kopyalar. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Belirtilen indeksten başlayarak kaynak dizi görünümünden yığıt üzerindeki hedef dizideki belirtilen konuma belirtilen sayıda öğeyi kopyalar. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Geçerli dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, arrayIndex argümanı ile belirtilen indeksden başlayarak hedef diziye eklenir. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t) const | Geçerli dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, dstIndex argümanı ile belirtilen indeksden başlayarak hedef diziye eklenir. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t) const | Geçerli dizinin tüm öğelerini belirtilen hedef dizi görünümüne kopyalar. Öğeler, dstIndex argümanı ile belirtilen indeksden başlayarak hedef dizi görünümüne eklenir. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const | Belirtilen konumdan başlayarak geçerli diziden belirtilen sayıda öğeyi belirtilen hedef diziye kopyalar. Öğeler, dstIndex argümanı tarafından belirtilen indeksle hedef diziye eklenir. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const | Belirtilen konumdan başlayarak geçerli diziden belirtilen sayıda öğeyi belirtilen hedef dizi görünümüne kopyalar. Öğeler, dstIndex argümanı tarafından belirtilen indeksle hedef dizi görünümüne eklenir. |
| [Count](./count/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden bir sayı döndürür. |
| [crbegin](./crbegin/)() const | Ters çevrilmiş konteynerin ilk elemanına bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin son elemanına karşılık gelir. Eğer konteyner boşsa, döndürülen yineleyici [crend()](./crend/) ile eşit olacaktır. |
| [crend](./crend/)() const | Ters çevrilmiş konteynerin son elemanını takiben gelen elemana bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin ilk elemanından önceki elemana karşılık gelir. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [data](./data/)() | Dizi öğelerini depolamak için kullanılan iç veri yapısına bir referans döndürür. |
| [data](./data/)() const | Dizi öğelerini depolamak için kullanılan iç veri yapısına sabit bir referans döndürür. |
| [data_ptr](./data_ptr/)() | Dizi öğelerinin depolandığı bellek tamponunun başlangıcına ham bir işaretçi döndürür. |
| [data_ptr](./data_ptr/)() const | Dizi öğelerinin depolandığı bellek tamponunun başlangıcına sabit bir ham işaretçi döndürür. |
| [end](./end/)() | Konteynerin son elemanını takiben gelen elemana bir yineleyici döndürür. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [end](./end/)() const | Const nitelikli konteynerin son elemanını takiben gelen elemana bir yineleyici döndürür. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| static [Exists](./exists/)(ArrayPtr\<T\>, std::function\<bool(T)>) | Belirtilen [Array](./) nesnesinin, belirtilen koşulu sağlayan bir öğe içerip içermediğini belirler. |
| static [Find](./find/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Belirtilen dizide, belirtilen koşulun şartlarını sağlayan ilk öğeyi arar. |
| static [FindAll](./findall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Belirtilen koşul tarafından tanımlanan şartları karşılayan tüm öğeleri alır. |
| static [FindIndex](./findindex/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Belirtilen dizide, belirtilen koşulun şartlarını sağlayan ilk öğeyi arar. |
| static [ForEach](./foreach/)(const ArrayPtr\<T\>\&, System::Action\<T\>) | Belirtilen dizinin her bir öğesi üzerinde belirtilen eylemi gerçekleştirir. |
| [get_Count](./get_count/)() const override | Dizinin boyutunu döndürür. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Dizinin yalnızca okunur olup olmadığını gösterir. |
| [get_Length](./get_length/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden 32-bit tamsayı döndürür. |
| [get_LongLength](./get_longlength/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden 64-bit tamsayı döndürür. |
| [get_Rank](./get_rank/)() const | UYGULANMADI. |
| [GetEnumerator](./getenumerator/)() override | Geçerli nesne tarafından temsil edilen dizinin öğelerine IEnumerator arayüzü sağlayan [Enumerator](./enumerator/) nesnesine bir işaretçi döndürür. |
| [GetLength](./getlength/)(int) | Belirtilen boyuttaki öğe sayısını döndürür. |
| [GetLongLength](./getlonglength/)(int) | Belirtilen boyuttaki öğe sayısını 64-bit tamsayı olarak döndürür. |
| [GetLowerBound](./getlowerbound/)(int) const | Belirtilen boyutun alt sınırını döndürür. |
| [GetSizeTLength](./getsizetlength/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden bir std::size_t değişkeni döndürür. |
| [GetUpperBound](./getupperbound/)(int) | Belirtilen boyutun üst sınırını döndürür. |
| [idx_get](./idx_get/)(int) const override | Belirtilen indeksteki öğeyi döndürür. |
| [idx_set](./idx_set/)(int, T) override | Belirtilen değeri, belirtilen indeksteki dizi öğesi olarak ayarlar. |
| [IndexOf](./indexof/)(const T\&) const override | Dizide belirtilen öğenin ilk oluşumunun indeksini belirler. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Dizide belirtilen öğenin ilk oluşumunun indeksini belirler. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Belirtilen dizide, belirtilen indeks'ten başlayarak belirtilen öğenin ilk oluşumunun indeksini belirler. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında, belirtilen öğenin ilk oluşumunun indeksini belirler. |
| [Init](./init/)(const T) | Geçerli nesne tarafından temsil edilen diziyi, belirtilen diziden gelen değerlerle doldurur. |
| [Initialize](./initialize/)() | **T** tipinde varsayılan oluşturulmuş nesnelerle diziyi doldurur. |
| [Insert](./insert/)(int, const T\&) override | Geçerli nesne tarafından temsil edilen dizi yalnızca okunabilir olduğu için desteklenmez. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında, belirtilen öğenin son oluşumunun indeksini belirler. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Belirtilen dizide, belirtilen indeks'ten başlayarak belirtilen öğenin son oluşumunun indeksini belirler. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Belirtilen dizide belirtilen öğenin son oluşumunun indeksini belirler. |
| [Max](./max/)() const | Elemanları karşılaştırmak için [operator<()](../operator_/) kullanan dizideki en büyük öğeyi bulur. |
| [Min](./min/)() const | Elemanları karşılaştırmak için [operator<()](../operator_/) kullanan dizideki en küçük öğeyi bulur. |
| [operator[]](./operator[]/)(int) | Belirtilen indeksteki bir öğeyi döndürür. |
| [operator[]](./operator[]/)(int) const | Belirtilen indeksteki bir öğeyi döndürür. |
| [rbegin](./rbegin/)() | Ters çevrilmiş konteynerin ilk elemanına bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin son elemanına karşılık gelir. Eğer konteyner boşsa, döndürülen yineleyici [rend()](./rend/) ile eşittir. |
| [rbegin](./rbegin/)() const | Ters çevrilmiş konteynerin ilk elemanına bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin son elemanına karşılık gelir. Eğer konteyner boşsa, döndürülen yineleyici [rend()](./rend/) ile eşittir. |
| [Remove](./remove/)(const T\&) override | Desteklenmiyor çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okunur. |
| [RemoveAt](./removeat/)(int) override | Geçerli nesne tarafından temsil edilen dizi yalnızca okunabilir olduğu için desteklenmez. |
| [rend](./rend/)() | Ters çevrilmiş konteynerin son elemanını takiben gelen elemana bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin ilk elemanından önceki elemana karşılık gelir. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [rend](./rend/)() const | Ters çevrilmiş konteynerin son elemanını takiben gelen elemana bir ters yineleyici döndürür. Bu, ters çevrilmemiş konteynerin ilk elemanından önceki elemana karşılık gelir. Bu eleman bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| static [Resize](./resize/)(ArrayPtr\<Type\>\&, int) | Belirtilen dizinin boyutunu belirtilen değere değiştirir veya belirtilen boyutta yeni bir dizi oluşturur. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&) | Belirtilen dizideki öğeleri tersine çevirir. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&, int, int) | Belirtilen dizideki bir öğe aralığını tersine çevirir. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Dizinin saklanan işaretçileri zayıf olarak ele almasını sağlar (uygunsa). |
| [SetValue](./setvalue/)(const T\&, int) | Belirtilen indeksteki öğenin değerini ayarlar. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&) | Belirtilen dizideki öğeleri varsayılan karşılaştırıcıyı kullanarak sıralar. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, int, int) | Belirtilen dizideki bir öğe aralığını varsayılan karşılaştırıcıyı kullanarak sıralar. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Belirtilen dizideki öğeleri belirtilen karşılaştırıcıyı kullanarak sıralar. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) | UYGULANMADI. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) | Anahtarları içeren bir dizi ve diğer dizi - karşılık gelen öğeler - anahtarları içeren dizinin değerlerine göre, öğeleri operator< kullanılarak karşılaştırarak iki diziyi sıralar. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) | Anahtarları içeren bir dizi ve diğer dizi - karşılık gelen öğeler - anahtarları içeren dizinin değerlerine göre, öğeleri varsayılan karşılaştırıcıyı kullanarak karşılaştırarak iki diziyi sıralar. |
| static [TrueForAll](./trueforall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Belirtilen dizideki tüm öğelerin, belirtilen koşul tarafından tanımlanan koşulları sağlayıp sağlamadığını belirler. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [const_reverse_iterator](./const_reverse_iterator/) | Sabit ters yineleyici türü. |
| [EnumerablePtr](./enumerableptr/) | **T** tipinde öğeler içeren IEnumerable nesnesine işaret eden paylaşımlı işaretçi türü için bir takma addır. |
| [EnumeratorPtr](./enumeratorptr/) | **T** tipinde öğeler içeren IEnumerator nesnesine işaret eden paylaşımlı işaretçi türü için bir takma addır. |
| [iterator](./iterator/) | Yineleyici türü. |
| [reverse_iterator](./reverse_iterator/) | Ters yineleyici türü. |
| [UnderlyingType](./underlyingtype/) | Dizideki her öğeyi temsil etmek için kullanılan türün takma adı. |
| [ValueType](./valuetype/) | Dizinin öğelerinin tipi için takma ad. |
## Açıklamalar



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Diziyi oluştur ve doldur.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  // Dizi öğelerini artan sırayla sırala.
  Array<int32_t>::Sort(arrayPtr);

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  // Dizi öğelerinin sayısını yazdır.
  std::cout << arrayPtr->get_Length() << std::endl;

  // 4'e eşit olan öğenin indeksini yazdır.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Diziyi yeniden boyutlandır.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  return 0;
}
/*
This code example produces the following output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Ayrıca Bakınız

* Class [Object](../object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
