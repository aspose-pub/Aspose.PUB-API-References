---
title: "System::Nullable class"
linktitle: "Nullable"
second_title: "Aspose.PUB için C++"
description: "System::Nullable class. C++'ta ileri bildirim."
type: docs
weight: 4600
url: /tr/cpp/system/nullable/
---
## Nullable class


İleri bildirim.

```cpp
template<typename T>class Nullable
```


| Parametre | Açıklama |
| --- | --- |
| T | Temel değer türü, [Nullable](./) sınıfı tarafından genişletilir |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(const T1\&) const | Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesne tarafından temsil edilen değere eşit olup olmadığını belirler. |
| [get_HasValue](./get_hasvalue/)() const | Geçerli nesnenin herhangi bir değeri temsil edip etmediğini belirler. |
| [get_Value](./get_value/)() const | Geçerli nesne tarafından temsil edilen değerin bir kopyasını döndürür. |
| [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu döndürür. |
| [GetValueOrDefault](./getvalueordefault/)(T) | Geçerli nesne tarafından temsil edilen değeri, eğer bu değer null ise belirtilen değeri döndürür. |
| [GetValueOrDefault](./getvalueordefault/)() |  |
| [IsNull](./isnull/)() const | Geçerli nesnenin null değeri temsil edip etmediğini belirler. |
| [Nullable](./nullable/)() | Null değeri temsil eden bir örnek oluşturur. |
| [Nullable](./nullable/)(std::nullptr_t) | Null'ı temsil eden bir örnek oluşturur. |
| [Nullable](./nullable/)(const T1\&) | [Nullable](./) sınıfının, belirtilen değeri temel tür T'nin değerine (gerekirse) dönüştüren bir örnek oluşturur. |
| [Nullable](./nullable/)(const Nullable\<T1\>\&) | Belirtilen [Nullable](./) nesne tarafından temsil edilen bir değeri temsil eden bir örnek oluşturur. Belirtilen nullable nesne, oluşturulan örneğin temel türünden farklı bir türde değer temsil edebilir; bu durumda temsil edilen değer, T türüne dönüştürülür. |
| [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<bool()>\&, bool) const | Bu ve **other**'ın ikisinin de null olmamasını kontrol eden ve böyleyse bir lambda çağıran yardımcı işlev. Uygulamalarda kullanılır. |
| [operator const T &](./operatorconstt&/)() const | Geçerli nesne tarafından temsil edilen değere sabit bir referans döndürür. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Geçerli nesne tarafından temsil edilen değerin null olmadığını belirler. |
| [operator!=](./operator!=/)(const T1\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen değere eşit olmamasını belirler. |
| [operator!=](./operator!=/)(const Nullable\<T1\>\&) const | Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesne tarafından temsil edilen değere eşit olmamasını belirler. |
| [operator&=](./operator&=/)(bool) | Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere [operator&=()](./operator&=/) uygular. |
| [operator+](./operator+/)(std::nullptr_t) const | Nullable<T> sınıfının varsayılan olarak oluşturulmuş bir örneğini döndürür. |
| [operator+](./operator+/)(const T1\&) const | Nullable ve non-nullable değerleri toplar. |
| [operator+](./operator+/)(const Nullable\<T1\>\&) const | Nullable değerleri toplar. |
| [operator+=](./operator+=/)(std::nullptr_t) | Geçerli nesneyi, null değeri temsil edecek şekilde sıfırlar. |
| [operator+=](./operator+=/)(const T1\&) | Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere [operator+=()](./operator+=/) uygular. |
| [operator+=](./operator+=/)(const Nullable\<T1\>\&) | Belirtilen [Nullable](./) nesne tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere [operator+=()](./operator+=/) uygular. |
| [operator-](./operator-/)(T1) const | Nullable ve null işaretli değerleri çıkarır. |
| [operator-](./operator-/)(const T1\&) const | Nullable ve non-nullable değerleri çıkarır. |
| [operator-](./operator-/)(const Nullable\<T1\>\&) const | Nullable değerleri çıkarır. |
| [operator-=](./operator-=/)(T1) | Null değeri temsil eden [Nullable](./) sınıfının bir örneğini döndürür. |
| [operator-=](./operator-=/)(const T1\&) | Belirtilen değeri sağ taraf argümanı olarak kullanarak, mevcut nesne tarafından temsil edilen değere [operator-=()](./operator-=/) uygular. |
| [operator-=](./operator-=/)(const Nullable\<T1\>\&) | Belirtilen [Nullable](./) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak, mevcut nesne tarafından temsil edilen değere [operator-=()](./operator-=/) uygular. |
| [operator<](./operator_/)(std::nullptr_t) const | Her zaman false döndürür. |
| [operator<](./operator_/)(const T1\&) const | Bu değerler üzerine [operator<()](./operator_/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değerden küçük olup olmadığını belirler. |
| [operator<](./operator_/)(const Nullable\<T1\>\&) const | Bu değerler üzerine [operator<()](./operator_/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değerden küçük olup olmadığını belirler. |
| [operator<=](./operator_=/)(std::nullptr_t) const | Her zaman false döndürür. |
| [operator<=](./operator_=/)(const T1\&) const | Bu değerler üzerine [operator<=()](./operator_=/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değere küçük veya eşit olup olmadığını belirler. |
| [operator<=](./operator_=/)(const Nullable\<T1\>\&) const | Bu değerler üzerine [operator<=()](./operator_=/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere küçük veya eşit olup olmadığını belirler. |
| [operator=](./operator=/)(std::nullptr_t) | Mevcut nesneye null atar. |
| [operator=](./operator=/)(const T1\&) | Nesnenin şu anda temsil ettiği değeri belirtilen değerle değiştirir. |
| [operator=](./operator=/)(const Nullable\<T1\>\&) | Nesnenin şu anda temsil ettiği değeri belirtilen değerle değiştirir. |
| [operator==](./operator==/)(std::nullptr_t) const | Mevcut nesne tarafından temsil edilen değerin null olup olmadığını belirler. |
| [operator==](./operator==/)(const T1\&) const | Mevcut nesne tarafından temsil edilen değerin belirtilen değere eşit olup olmadığını belirler. |
| [operator==](./operator==/)(const Nullable\<T1\>\&) const | Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesne tarafından temsil edilen değere eşit olup olmadığını belirler. |
| [operator>](./operator_/)(std::nullptr_t) const | Her zaman false döndürür. |
| [operator>](./operator_/)(const T1\&) const | Bu değerler üzerine [operator>()](./operator_/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değerden büyük olup olmadığını belirler. |
| [operator>](./operator_/)(const Nullable\<T1\>\&) const | Bu değerler üzerine [operator>()](./operator_/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değerden büyük olup olmadığını belirler. |
| [operator>=](./operator_=/)(std::nullptr_t) const | Her zaman false döndürür. |
| [operator>=](./operator_=/)(const T1\&) const | Bu değerler üzerine [operator>=()](./operator_=/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere büyük veya eşit olup olmadığını belirler. |
| [operator>=](./operator_=/)(const Nullable\<T1\>\&) const | Bu değerler üzerine [operator>=()](./operator_=/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere büyük veya eşit olup olmadığını belirler. |
| [operator | =](./operator_=/)(bool) | Uygular [operator | =()](./operator_=/) mevcut nesne tarafından temsil edilen değere, belirtilen değeri sağ taraf argümanı olarak kullanarak. |
| [reset](./reset/)() | Mevcut temsil edilen değeri null olarak ayarlar. |
| [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen değeri stringe dönüştürür. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | Bu sınıf tarafından temsil edilen değerin bir türü için bir takma addır. |
## Açıklamalar


Belirtilen türde, null atanabilen bir değeri temsil eder. Bu tür yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referans olarak geçirilmelidir. Bu tür nesneleri yönetmek için asla [System::SmartPtr](../smartptr/) sınıfını kullanmayın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
