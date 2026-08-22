---
title: "System::SmartPtr sınıfı"
linktitle: "SmartPtr"
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr sınıfı. Yığın üzerinde tahsis edilen tipleri sarmalayan bir işaretçi sınıfı. Object sınıfını miras alan sınıfların belleğini yönetmek için kullanın. Bu işaretçi türü, iç içe işaretçi semantiğini izler. Referans sayacı, ya Object içinde ya da Object örneğine sıkı sıkıya bağlı sayaç yapısında depolanır. Her durumda, tüm SmartPtr örnekleri, nasıl oluşturulurlarsa oluştursunlar tek sahiplik grubu oluşturur; bu, std::shared_ptr sınıfının davranışının aksine bir durumdur. Ham işaretçiyi SmartPtr'ye dönüştürmek, aynı nesneye ortak referanslar tutan diğer SmartPtr örnekleri bulunduğu sürece güvenlidir. SmartPtr sınıfı örneği iki durumdan birinde olabilir: paylaşımlı işaretçi ve zayıf işaretçi. Nesneyi canlı tutmak için, ona olan paylaşımlı referans sayısının pozitif olması gerekir. Hem zayıf hem de paylaşımlı işaretçiler, işaret edilen nesneye (metot çağırmak, alanları okumak veya yazmak vb.) erişmek için kullanılabilir, ancak zayıf işaretçiler paylaşımlı işaretçi referans sayımına katılmaz. Nesne, ona olan son ''shared'' SmartPtr işaretçisi yok edildiğinde silinir. Bu nedenle, nesneye başka paylaşımlı SmartPtr işaretçisi bulunmadığı zaman, örneğin nesne oluşturulurken veya yok edilirken, bunun gerçekleşmediğinden emin olun. Bu sorunu çözmek için System::Object::ThisProtector koruma nesnelerini (C++ kodunda) veya CppCTORSelfReference ya da CppSelfReference özniteliğini (C# kodunda) kullanın. Benzer şekilde, döngüsel referansları kırmak için System::WeakPtr işaretçi sınıfını veya System::SmartPtrMode::Weak işaretçi modunu (C++ kodunda) ya da CppWeakPtr özniteliğini (C# kodunda) kullanın. İki veya daha fazla nesne ''shared'' işaretçileriyle birbirine referans verirse, hiç silinmezler. Çalışma zamanında işaretçi türü (zayıf veya paylaşımlı) değiştirilmesi gerekiyorsa, System::SmartPtr<T>::set_Mode() metodunu veya System::DynamicWeakPtr sınıfını kullanın. SmartPtr sınıfı hiçbir sanal metot içermez. Kendi bellek yönetimi stratejinizi oluşturuyorsanız yalnızca onu miras almanız gerekir. Bu tip, diğer nesnelerin silinmesini yönetmek için bir işaretçidir. C++'da yığıt (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir."
type: docs
weight: 5400
url: /tr/cpp/system/smartptr/
---
## SmartPtr class


Yığın üzerinde tahsis edilen tipleri saran Pointer sınıfı. [Object](../object/) sınıfından türeten sınıfların belleğini yönetmek için kullanın. Bu gösterici türü, içsel gösterici (intrusive pointer) semantiğini izler. Referans sayacı ya [Object](../object/) içinde ya da [Object](../object/) örneğine sıkı sıkıya bağlı bir sayaç yapısında depolanır. Her durumda, tüm [SmartPtr](./) örnekleri, nasıl oluşturulduklarından bağımsız olarak tek sahiplik grubunu oluşturur; bu, std::shared_ptr sınıfının davranışından farklıdır. Ham göstericiyi [SmartPtr](./) içine dönüştürmek, aynı nesneye ortak referanslar tutan başka [SmartPtr](./) örnekleri olduğu sürece güvenlidir. [SmartPtr](./) sınıfı örneği iki durumdan birinde olabilir: ortak (shared) gösterici ve zayıf (weak) gösterici. Nesneyi canlı tutmak için ortak referans sayısının pozitif olması gerekir. Hem zayıf hem de ortak göstericiler, işaret edilen nesneye (metot çağırmak, alanları okumak ya da yazmak vb.) erişmek için kullanılabilir, ancak zayıf göstericiler ortak gösterici referans sayımına katılmaz. [Object](../object/) son 'shared' [SmartPtr](./) göstericisi yok edildiğinde silinir. Bu yüzden, nesne oluşturulurken ya da yok edilirken başka ortak [SmartPtr](./) göstericisi bulunmadığında bunun gerçekleşmediğinden emin olun. Bu sorunu düzeltmek için System::Object::ThisProtector koruma nesnelerini (C++ kodunda) veya CppCTORSelfReference ya da CppSelfReference özniteliğini (çevirisi yapılan C# kodunda) kullanın. Benzer şekilde, döngüsel referansları kırmak için [System::WeakPtr](../weakptr/) gösterici sınıfını veya [System::SmartPtrMode::Weak](../smartptrmode/) gösterici kipini (C++ kodunda) ya da CppWeakPtr özniteliğini (C# kodunda) kullanın. İki ya da daha fazla nesne, 'shared' göstericilerle birbirine referans verirse, hiç silinmezler. Gösterici türü (zayıf ya da ortak) çalışma zamanında değiştirilecekse, [System::SmartPtr<T>::set_Mode()](./set_mode/) metodunu veya [System::DynamicWeakPtr](../dynamicweakptr/) sınıfını kullanın. [SmartPtr](./) sınıfı hiçbir sanal metoda sahip değildir. Kendi bellek yönetim stratejinizi oluşturuyorsanız yalnızca o zaman miras almanız gerekir. Bu tür, diğer nesnenin silinmesini yönetmek için bir göstericidir. Yığını üzerinde (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.

```cpp
template<class T>class SmartPtr
```


| Parametre | Açıklama |
| --- | --- |
| T | İşaret edilen nesnenin tipi. Ya [System::Object](../object/) ya da onun alt sınıfı olmalıdır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [begin](./begin/)() | [begin()](./begin/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [begin()](./begin/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [begin](./begin/)() const | [begin()](./begin/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [begin()](./begin/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [Cast](./cast/)() const | Göstericiyi kendi tipine dönüştürür. |
| [Cast](./cast/)() const | Göstericiyi static_cast kullanarak temel tipe dönüştürür. |
| [Cast](./cast/)() const | Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| [Cast](./cast/)() const | Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| [cbegin](./cbegin/)() const | [cbegin()](./cbegin/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [cbegin()](./cbegin/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [cend](./cend/)() const | [cend()](./cend/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [cend()](./cend/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [const_pointer_cast](./const_pointer_cast/)() const | Gösterilen nesne üzerinde const_cast kullanarak göstericiyi farklı bir tipe dönüştürür. |
| [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Gösterilen nesne üzerinde dynamic_cast kullanarak göstericiyi farklı bir tipe dönüştürür. |
| [end](./end/)() | [end()](./end/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [end()](./end/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [end](./end/)() const | [end()](./end/) metoduna erişim sağlayan bir alt koleksiyon erişicisi. Yalnızca SmartPtr_ [end()](./end/) metoduna sahip bir özelleştirme tipi ise derlenir. |
| [get](./get/)() const | İşaret edilen nesneyi alır. |
| [get_Mode](./get_mode/)() const | Gösterici kipini alır. |
| [get_shared](./get_shared/)() const | İşaret edilen nesneyi alır, ancak göstericinin ortak (shared) kipte olduğunu doğrular. |
| [get_shared_count](./get_shared_count/)() const | Referans verilen nesneye mevcut olan ortak göstericilerin sayısını (geçerli olan dahil) alır. Geçerli göstericinin ortak kipte olduğunu doğrular. |
| [GetHashCode](./gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](./gethashcode/) metodunu çağırır. |
| [GetObjectNotNull](./getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır veya bir istisna fırlatır. |
| [GetObjectOrNull](./getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](./get/) ile aynı. |
| [GetObjectOwner](./getobjectowner/)() const | Referans verilen nesneyi alır. |
| [GetPointer](./getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](./get/) ile aynı. |
| [Is](./is/)(const System::TypeInfo\&) const | İşaret edilen nesnenin belirli bir tipte ya da onun alt tipinde olup olmadığını denetler. C# 'is' semantiğini izler. |
| [IsAliasingPtr](./isaliasingptr/)() const | Göstericinin, sahip olduğu nesne dışında başka bir nesneye (aliasing yapıcı ile oluşturulan) işaret edip etmediğini denetler. |
| [IsShared](./isshared/)() const | Göstericinin ortak (shared) kipte olup olmadığını denetler. |
| [IsWeak](./isweak/)() const | Göstericinin zayıf (weak) kipte olup olmadığını denetler. |
| explicit [operator bool](./operatorbool/)() const | Göstericinin null olmadığını denetler. |
| [operator!](./operator!/)() const | Göstericinin null olduğunu denetler. |
| [operator*](./operator_/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmadığını doğrular. |
| [operator->](./operator-_/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| [operator<](./operator_/)(Y *) const | [SmartPtr](./) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [operator<](./operator_/)(SmartPtr\<Y\> const\&) const | [SmartPtr](./) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [operator=](./operator=/)(SmartPtr_\&&) | [SmartPtr](./) nesnesine taşıma ataması yapar. x kullanılamaz hale gelir. |
| [operator=](./operator=/)(const SmartPtr_\&) | [SmartPtr](./) nesnesine kopya ataması yapar. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | [SmartPtr](./) nesnesine kopya ataması yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [operator=](./operator=/)(Pointee_ *) | Ham işaretçiyi [SmartPtr](./) nesnesine atar. |
| [operator=](./operator=/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| [operator==](./operator==/)(std::nullptr_t) const | İşaretçinin nullptr olup olmadığını kontrol eder. |
| [operator[]](./operator[]/)(IdxType) const | Dizi elemanları için erişimci. Yalnızca SmartPtr_ [System::Array](../array/) özelleştirmesi ise derlenir. |
| [RemoveAliasing](./removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı tarafından oluşturulan) kaldırır, işaret ettiği aynı nesneyi (paylaşılıyorsa yönetir) ya da (zayıfsa izler) emin olur. |
| [reset](./reset/)(Pointee_ *) | İşaret edilen nesneyi ayarlar. |
| [reset](./reset/)() | İşaretçiyi nullptr'ye işaret edecek şekilde yapar. |
| [set_Mode](./set_mode/)(SmartPtrMode) | İşaretçi modunu ayarlar. Referans verilen nesnenin referans sayısını değiştirebilir. |
| [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(uint32_t) const | İşaret edilen nesnede (varsa) SetTemplateWeakPtr() metodunu çağırır. |
| [SmartPtr](./smartptr/)(SmartPtrMode) | Gerekli modda [SmartPtr](./) nesnesi oluşturur. |
| [SmartPtr](./smartptr/)(std::nullptr_t, SmartPtrMode) | Gerekli modda null-pointer [SmartPtr](./) nesnesi oluşturur. |
| [SmartPtr](./smartptr/)(Pointee_ *, SmartPtrMode) | Belirtilen nesneyi işaret eden [SmartPtr](./) oluşturur veya ham işaretçiyi [SmartPtr](./) tipine dönüştürür. |
| [SmartPtr](./smartptr/)(const SmartPtr_\&, SmartPtrMode) | [SmartPtr](./) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. |
| [SmartPtr](./smartptr/)(const SmartPtr\<Q\>\&, SmartPtrMode) | [SmartPtr](./) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapar. |
| [SmartPtr](./smartptr/)(SmartPtr_\&&, SmartPtrMode) | [SmartPtr](./) nesnesini taşıma yapıcı ile oluşturur. Etkili olarak, iki işaretçi aynı moddaysa takas eder. Çağrıdan sonra x kullanılamaz olabilir. |
| explicit [SmartPtr](./smartptr/)(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) | Referans verilen dizinin tipini farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta faydalı olabilir. |
| explicit [SmartPtr](./smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
| [SmartPtr](./smartptr/)(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) | ptr'nin başlangıç değeriyle sahiplik bilgisini paylaşan ancak alakasız ve yönetilmeyen p işaretçisini tutan bir [SmartPtr](./) oluşturur. |
| [static_pointer_cast](./static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [ToObjectPtr](./toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../object/) işaretçisine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static [Type](./type/)() | Pointee_ tipi için [System::TypeInfo](../typeinfo/) nesnesini almanın kısayolu. |
| [~SmartPtr](./~smartptr/)() | [SmartPtr](./) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ArrayType](./arraytype/) | Pointee_ ile aynı, eğer [System::Array](../array/) özel bir türse, aksi takdirde void. |
| [Pointee_](./pointee_/) | İşaret edilen tip. |
| [SmartPtr_](./smartptr_/) | Özelleştirilmiş akıllı işaretçi türü. |
| [ValueType](./valuetype/) | İşaret edilen dizinin depolama tipi. Yalnızca T, [System::Array](../array/) özel bir türse anlamlıdır. |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
