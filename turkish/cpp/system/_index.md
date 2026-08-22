---
title: "System ad alanı"
linktitle: "System"
second_title: "Aspose.PUB için C++"
description: "System ad alanının C++'ta nasıl kullanılacağını."
type: docs
weight: 500
url: /tr/cpp/system/
---



## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Activator](./activator/) | Nesne türleri oluşturmak için yöntemler içerir. |
| [Array](./array/) | Dizi veri yapısını temsil eden sınıf. Bu sınıfın nesneleri yalnızca [System::MakeArray()](./makearray/) ve [System::MakeObject()](./makeobject/) işlevleri kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [ArraySegment](./arraysegment/) | Tek boyutlu dizinin bir segmentini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Attribute](./attribute/) | Özel nitelikler için bir temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BitConverter](./bitconverter/) | Bayt dizisinin bir değer tipine ve tersine dönüşümünü gerçekleştiren yöntemler içerir. Bu, örnek hizmeti olmayan statik bir tiptir. Onun hiçbir şekilde örneklerini oluşturmayın. |
| [Boolean](./boolean/) | [System.Boolean](./boolean/) .[Net](../system.net/) tipinin statik üyelerini tutan sınıf. |
| [BoxedEnum](./boxedenum/) | Kutu içine alınmış bir enum değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BoxedValue](./boxedvalue/) | Kutu içine alınmış bir değeri temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BoxedValueBase](./boxedvaluebase/) | Kutu içine alınmış bir değeri temsil eden türev sınıfın bazı temel yöntemlerini uygulayan ve bir arabirim tanımlayan temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Buffer](./buffer/) | Ham bayt dizilerini işleyen yöntemler içerir. Bu, örnek hizmeti olmayan statik bir tiptir. Onun hiçbir şekilde örneklerini oluşturmayın. |
| [Byte](./byte/) | İşaretsiz 8-bit tamsayıyla çalışmak için yöntemler içerir. |
| [Char](./char/) | UTF-16 kod birimleri olarak temsil edilen karakterlerin işlenmesi için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Onun hiçbir şekilde örneklerini oluşturmayın. |
| [Comparison](./comparison/) | Aynı tipte iki nesneyi karşılaştıran metoda işaretçi temsil eder. Bu tip yığına tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [Console](./console/) | Verileri standart çıktı akışına göndermek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Onun hiçbir şekilde örneklerini oluşturmayın. |
| [ConsoleOutput](./consoleoutput/) | Standart çıktı akışını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [DateTime](./datetime/) | Zaman continuumunda belirli bir tarih ve saat değerini temsil eder. Bu tip yığına tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [DateTimeOffset](./datetimeoffset/) | Koordinatlı Evrensel Zaman'a (UTC) göre tarih ve günün saatini içerir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [DBNull](./dbnull/) | Var olmayan bir değeri temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Decimal](./decimal/) | Ondalık bir sayıyı temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) sınıfı uygulaması. Ortak kodu çoğaltmadan BoxingValue özelleştirmelerinin ilan edilmesine izin verir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Bir fonksiyon, yöntem ya da fonksiyon nesnesine işaretçiyi temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [DynamicWeakPtr](./dynamicweakptr/) | Saklanan nesnenin şablon argümanlarının işaretçi modlarını izleyen ve her atamadan sonra güncelleyen akıllı işaretçi sınıfı. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığıt üzerinde ayrılmalı ve fonksiyonlara ya değer olarak ya da const referansla geçirilmelidir. |
| [EnumValues](./enumvalues/) | **E** enum tipinin sabitleri hakkında meta bilgi sağlar. |
| [EnumValuesBase](./enumvaluesbase/) | Enum tipinin meta bilgisini temsil eden sınıf için temel sınıf. |
| [EventArgs](./eventargs/) | Olay tetiklendiğinde olay abonelerine geçirilen bağlamı temsil eden sınıflar için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [ExceptionWrapper](./exceptionwrapper/) | Exception sınıfından türetilen istisnaların sarmalayıcısını temsil eden şablon. |
| [FlagsAttribute](./flagsattribute/) | Bir enumun bit alanı olarak ele alınabileceğini gösterir; yani bir küme. |
| [Func](./func/) | Fonksiyon temsilcisi. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [GC](./gc/) | Hiçbir şey yapmayan bir stub gibi davranan taklit bir Çöp Toplama'yı temsil eder. Bu, örnek hizmeti olmayan statik bir tiptir. Onun örneklerini hiçbir şekilde oluşturmayın. |
| [Guid](./guid/) | Genel Benzersiz Tanımlayıcıyı (GUID) temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [IAsyncResult](./iasyncresult/) | Asenkron işlemin durumunu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [ICloneable](./icloneable/) | Nesne kopyalama - bir nesnenin kopyasını oluşturma yeteneği sağlayan bir yöntemi tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [IComparable](./icomparable/) | İki nesneyi karşılaştıran bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [IConvertible](./iconvertible/) | Uygulayan referans veya değer tipinin değerini eşdeğer bir değere sahip ortak dil çalışma zamanı tipine dönüştüren yöntemler tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [ICustomFormatter](./icustomformatter/) | Belirtilen nesne tarafından temsil edilen bir değerin dize temsili üzerinde özel biçimlendirme yapan bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [IDisposable](./idisposable/) | Geçerli nesnenin sahip olduğu kaynakları serbest bırakan bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [IEquatable](./iequatable/) | İki nesnenin eşitliğini belirleyen bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [IFormatProvider](./iformatprovider/) | Biçimlendirme bilgisi sağlayan bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [IFormattable](./iformattable/) | Belirtilen biçim dizesi ve biçim sağlayıcıyı kullanarak geçerli nesnenin değerini biçimlendiren bir yöntem tanımlar. |
| [Int16](./int16/) | 16 bit tamsayıyla çalışmak için yöntemler içerir. |
| [Int32](./int32/) | 32 bit tamsayıyla çalışmak için yöntemler içerir. |
| [Int64](./int64/) | 64 bit tamsayıyla çalışmak için yöntemler içerir. |
| [LockContext](./lockcontext/) | C# lock() ifadesini uygulayan koruma nesnesi. |
| [MarshalByRefObject](./marshalbyrefobject/) | Uzak nesne iletişimi etkin uygulamalarda uygulama alanı sınırları arasında nesnelere erişim sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Delegate koleksiyonunu temsil eder. Bu tip yığına ayrılmalı ve işlevlere değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](./smartptr/) sınıfını asla kullanmayın. |
| [Nullable](./nullable/) | İleri bildirim. |
| [NullableUtils](./nullableutils/) | C# [System.Nullable](./nullable/) (tip argümanı olmadan) statik sınıfını temsil eder. C++'ta sınıf şablonlarını aşırı yükleyemediği için özgün adı kullanmak mümkün değildir. Null atanabilen bir değer tipini destekler. Bu sınıf türetilemez. |
| [Object](./object/) | Temel sınıf, C#'ta [System.Object](./object/) sınıfı için mevcut yöntemlerin kullanılmasını sağlar. Çevrilen ortamda kullanılan tüm basit olmayan sınıflar bundan türemelidir. |
| [ObjectExt](./objectext/) | C# [Object](./object/) yöntemlerini nesne olmayan C++ tipleri (dizeler, sayılar vb.) için taklit eden statik yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde onun örneklerini asla oluşturmamalısınız. |
| [ObjectType](./objecttype/) | Nesne türü alıcılarını uygulayan statik yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde onun örneklerini asla oluşturmamalısınız. |
| [OperatingSystem](./operatingsystem/) | Belirli bir işletim sistemini temsil eder ve onun hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Yığını (stack) üzerinde veya operator new kullanarak bu türün örneğini asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın. |
| [Random](./random/) | Yarı rastgele bir sayı üreteci temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işlevi kullanılarak ayrılmalıdır. Yığını (stack) üzerinde veya operator new ile bu türün örneğini asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın. |
| [ScopedCulture](./scopedculture/) | Kapsam içinde kullanılan bir kültürü temsil eder. |
| [SmartPtr](./smartptr/) | Yığıt (heap) üzerinde ayrılan tipleri saran bir işaretçi sınıfı. [Object](./object/) sınıflarını miras alan sınıfların belleğini yönetmek için kullanın. Bu işaretçi türü, içsel işaretçi (intrusive pointer) semantiğini izler. Referans sayacı ya [Object](./object/) içinde ya da [Object](./object/) örneğine sıkı bir şekilde bağlı sayaç yapısında depolanır. Her durumda, tüm [SmartPtr](./smartptr/) örnekleri, nasıl oluşturulurlarsa oluşturulsun tek bir sahiplik grubu oluşturur; bu, std::shared_ptr sınıfının davranışından farklıdır. Ham işaretçiyi [SmartPtr](./smartptr/)’e dönüştürmek, aynı nesneye ortak referanslar tutan başka [SmartPtr](./smartptr/) örnekleri olduğu sürece güvenlidir. [SmartPtr](./smartptr/) sınıfı örneği iki durumdan birinde olabilir: paylaşımlı işaretçi ve zayıf işaretçi. Nesnenin yaşamını sürdürmek için, ona olan paylaşımlı referans sayısının pozitif olması gerekir. Hem zayıf hem de paylaşımlı işaretçiler, işaret edilen nesneye (yöntem çağırmak, alanları okumak veya yazmak vb.) erişmek için kullanılabilir, ancak zayıf işaretçiler paylaşımlı işaretçi referans sayımına katılmaz. [Object](./object/), ona olan son 'paylaşımlı' [SmartPtr](./smartptr/) işaretçisi yok edildiğinde silinir. Bu nedenle, nesne oluşturulurken veya yok edilirken başka paylaşımlı [SmartPtr](./smartptr/) işaretçileri bulunmadığından emin olun. Bu sorunu gidermek için System::Object::ThisProtector gözetleme nesnelerini (C++ kodunda) veya CppCTORSelfReference ya da CppSelfReference özniteliğini (çevirilen C# kodunda) kullanın. Benzer şekilde, döngüsel referansları kırmak için [System::WeakPtr](./weakptr/) işaretçi sınıfını veya [System::SmartPtrMode::Weak](./smartptrmode/) işaretçi modunu (C++ kodunda) ya da CppWeakPtr özniteliğini (çevirilen C# kodunda) kullanın. İki veya daha fazla nesne, 'paylaşımlı' işaretçilerle birbirine referans verirse, hiçbir zaman silinmezler. İşaretçi türü (zayıf veya paylaşımlı) çalışma zamanında değiştirilmesi gerekiyorsa, [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) yöntemini veya [System::DynamicWeakPtr](./dynamicweakptr/) sınıfını kullanın. [SmartPtr](./smartptr/) sınıfı hiçbir sanal (virtual) yöntem içermez. Bunu yalnızca kendi bellek yönetimi stratejinizi oluşturuyorsanız miras almanız gerekir. Bu tür, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığını (stack) üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir. |
| [SmartPtrInfo](./smartptrinfo/) | Final tipini bilmeden [SmartPtr](./smartptr/)'in içeriğini test etmek ve değiştirmek için hizmet sınıfı. Çöp toplama ve döngü referansları tespiti vb. için kullanılır. Bunu 'pointer to pointer' (işaretçiden işaretçiye) gibi düşünün. [SmartPtr](./smartptr/)'in temel tipini kullanamıyoruz çünkü yok; bunun yerine bu 'info' sınıfını kullanıyoruz. |
| [String](./string/) | [String](./string/) sınıfı kütüphane genelinde kullanılır. Kod çevirirken C# [System.String](./string/) için bir ikame görevi görür. Optimizasyon nedenleriyle bir [Object](./object/) alt sınıfı olarak kabul edilmez. Bu tip yığıt (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipin nesnelerini yönetmek için asla [System::SmartPtr](./smartptr/) sınıfını kullanmayın. |
| [StringComparer](./stringcomparer/) | Farklı karşılaştırma modlarıyla dizeleri karşılaştırır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [StringHashCompiletime](./stringhashcompiletime/) | c-dizisinden (c-string) bir hash değeri üreten yardımcı sınıf. |
| [TimeSpan](./timespan/) | Bir zaman aralığını temsil eder. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipin nesnelerini yönetmek için asla [System::SmartPtr](./smartptr/) sınıfını kullanmayın. |
| [TimeZone](./timezone/) | Bir zaman dilimini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [TimeZoneInfo](./timezoneinfo/) | Belirli bir zaman dilimini tanımlayan bir bilgiyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Tuple](./tuple/) | Bir tuple veri yapısını temsil eden sınıf. Azami öğe sayısı 8'tir. |
| [TupleFactory](./tuplefactory/) | Tuple nesneleri oluşturmak için statik yöntemler sağlar. |
| [TypeInfo](./typeinfo/) | Belirli bir tipi temsil eder ve onun hakkında bilgi sağlar. |
| [Uri](./uri/) | Birleşik kaynak tanımlayıcı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [UriBuilder](./uribuilder/) | Birleşik kaynak tanımlayıcıları (URI'lar) oluşturmak ve değiştirmek için yöntemler sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [UriParser](./uriparser/) | Yeni bir URI şemasını ayrıştırmak için kullanılır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](./makeobject/) işleviyle tahsis edilmelidir. Yığıt üzerinde ya da operator new kullanarak bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](./smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [UriShim](./urishim/) | Hizmet sınıfı. |
| [ValueType](./valuetype/) | [Object](./object/) kalıtımı performans nedenleriyle kesilmiş değer tipleri için temel sınıf. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipin nesnelerini yönetmek için asla [System::SmartPtr](./smartptr/) sınıfını kullanmayın. |
| [Version](./version/) | Bir sürüm numarasını temsil eder. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için asla [System::SmartPtr](./smartptr/) sınıfını kullanmayın. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Yapılandırma sırasında kendisini zayıf (weak) moda ayarlayan [System::SmartPtr](./smartptr/) alt sınıfı. Lütfen bu sınıfın, örneğinin her zaman zayıf modda kalacağını garanti etmediğini, çünkü [set_Mode()](./smartptr/set_mode/) hâlâ erişilebilir olduğunu unutmayın. Bu tip, diğer nesnelerin silinmesini yönetmek için bir işaretçidir. Yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer ya da sabit referans olarak geçirilmelidir. |
| [WeakReference](./weakreference/) | Bir nesneyi referans alırken aynı zamanda o nesnenin silinmesine izin veren zayıf bir referansı temsil eder. |
| [WeakReference< T >](./weakreference_t_/) | Bir nesneyi referans alırken aynı zamanda o nesnenin silinmesine izin veren zayıf bir referansı temsil eder. |
| [WeakReference<>](./weakreference__/) | Bir nesneyi referans alırken aynı zamanda o nesnenin silinmesine izin veren zayıf bir referansı temsil eder. |
## Enums

| Enum | Açıklama |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Base-64 kodlu verinin farklı formatlarını temsil eden değerleri içeren bir enum. |
| [DateTimeKind](./datetimekind/) | Tarih ve zaman türlerini temsil eden enum değerleri. |
| [DayOfWeek](./dayofweek/) | Haftanın bir gününü temsil eden enum. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Ortam değişkeni konumunu belirtir. |
| [MidpointRounding](./midpointrounding/) | Yuvarlama fonksiyonlarının davranışını belirtir. |
| [PlatformID](./platformid/) | Bir işletim sistemi platformunu temsil eder. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) işaretçi türü: zayıf veya paylaşılan. İşaretçinin nesneyi silip silmeyeceği kararı verilirken sayılıp sayılmayacağını tanımlar. |
| [StringComparison](./stringcomparison/) | Dize karşılaştırma stilini tanımlar. |
| [StringSplitOptions](./stringsplitoptions/) | Dize bölme davranışını belirler. |
| [TypeCode](./typecode/) | Bir nesnenin tipini temsil eder. |
| [UriComponents](./uricomponents/) | URI bileşenlerini temsil eder. |
| [UriFormat](./uriformat/) | URI'nin nasıl kaçış (escape) edildiğini belirtir. |
| [UriHostNameType](./urihostnametype/) | Ana bilgisayar adının tipini temsil eder. |
| [UriKind](./urikind/) | URI türlerini temsil eder. |
| [UriPartial](./uripartial/) | [Uri.GetLeftPart](./uri/getleftpart/) yöntemi için bir URI'nin bölümlerini temsil eder. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Action](./action/) | Dönüş değeri olmayan yöntemleri referans alan delege tipi. |
| [ArrayPtr](./arrayptr/) | 'Diziye işaretçi' tipinin takma adı. |
| [AsyncCallback](./asynccallback/) | Asenkron işlem tamamlandığında çağrılacak yöntemi temsil eden bir delege tipi. |
| [BadImageFormatException](./badimageformatexception/) | Dinamik bağlama kütüphanesi (DLL) veya çalıştırılabilir programın dosya görüntüsü geçersiz olduğunda fırlatılan istisna. BadImageFormatException sınıfı örneklerini asla [System::SmartPtr](./smartptr/) içine sarmalayın. |
| [ByteArrayPtr](./bytearrayptr/) | İmzalı olmayan 8-bit tamsayı dizisine işaret eden bir akıllı işaretçi nesnesinin takma adı. |
| [Converter](./converter/) | Çağrılabilir varlığa işaretçi temsil eder; bu varlık tek bir **TInput** tipinde argüman alır ve **TOutput** tipinde bir değer döndürür. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) sınıfının bir örneğine işaret eden bir akıllı işaretçi için takma ad. |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::DecoderFallback](../system.text/decoderfallback/) sınıfının bir örneğine işaret eder. |
| [DecoderPtr](./decoderptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::Decoder](../system.text/decoder/) sınıfının bir örneğine işaret eder. |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) sınıfının bir örneğine işaret eder. |
| [DirectoryInfoPtr](./directoryinfoptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IO::DirectoryInfo](../system.io/directoryinfo/) sınıfının bir örneğine işaret eder. |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) sınıfının bir örneğine işaret eder. |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::EncoderFallback](../system.text/encoderfallback/) sınıfının bir örneğine işaret eder. |
| [EncoderPtr](./encoderptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::Encoder](../system.text/encoder/) sınıfının bir örneğine işaret eder. |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) sınıfının bir örneğine işaret eder. |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) sınıfının bir örneğine işaret eder. |
| [EncodingInfoPtr](./encodinginfoptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::EncodingInfo](../system.text/encodinginfo/) sınıfının bir örneğine işaret eder. |
| [EncodingPtr](./encodingptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::Text::Encoding](../system.text/encoding/) sınıfının bir örneğine işaret eder. |
| [Event](./event/) | Bir olayı temsil eder - abonelerin, ilgi duyulan bir olay gerçekleştiğinde bir temsilci çağrısı yoluyla bilgilendirildiği bir mekanizma. |
| [EventArgsPtr](./eventargsptr/) | Bir [EventArgs](./eventargs/) sınıfının örneğine ortak işaretçi. |
| [EventHandler](./eventhandler/) | Bir olaya tepki veren ve işleyen bir yöntemi temsil eder. Bu tür, yığına tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tür nesneleri yönetmek için asla [System::SmartPtr](./smartptr/) sınıfını kullanmayın. |
| [Exception](./exception/) | Details::Exception yerine kullanılacak takma ad. |
| [ExceptionPtr](./exceptionptr/) | İstisna sarmalayıcıları tarafından kullanılan tür takma adı. |
| [FileInfoPtr](./fileinfoptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IO::FileInfo](../system.io/fileinfo/) sınıfının bir örneğine işaret eder. |
| [FileStreamPtr](./filestreamptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IO::FileStream](../system.io/filestream/) sınıfının bir örneğine işaret eder. |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IO::FileSystemInfo](../system.io/filesysteminfo/) sınıfının bir örneğine işaret eder. |
| [IAsyncResultPtr](./iasyncresultptr/) | [IAsyncResult](./iasyncresult/) için ortak işaretçi. |
| [IFormatProviderPtr](./iformatproviderptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IFormatProvider](./iformatprovider/) sınıfının bir örneğine işaret eder. |
| [MakeConstRef_t](./makeconstref_t/) | [MakeConstRef](./makeconstref/) değiştiricisi için yardımcı tür. |
| [MemoryStreamPtr](./memorystreamptr/) | Bir akıllı işaretçiye işaret eden takma ad, [System::IO::MemoryStream](../system.io/memorystream/) sınıfının bir örneğine işaret eder. |
| [Predicate](./predicate/) | Bir koşul fonksiyonuna işaretçi temsil eder - tek bir argüman kabul eden ve bool değer döndüren çağrılabilir bir varlık. |
| [SharedPtr](./sharedptr/) | Kütüphanede yaygın olarak kullanılan akıllı işaretçi için takma ad. |
| [StreamPtr](./streamptr/) | Bir akıllı göstericinin, [System::IO::Stream](../system.io/stream/) sınıfının bir örneğine işaret ettiği takma ad. |
| [StreamReaderPtr](./streamreaderptr/) | Bir akıllı göstericinin, [System::IO::StreamReader](../system.io/streamreader/) sınıfının bir örneğine işaret ettiği takma ad. |
| [StreamWriterPtr](./streamwriterptr/) | Bir akıllı göstericinin, [System::IO::StreamWriter](../system.io/streamwriter/) sınıfının bir örneğine işaret ettiği takma ad. |
| [StringComparerPtr](./stringcomparerptr/) | Bir paylaşımlı göstericinin, [StringComparer](./stringcomparer/) sınıfının bir örneğine işaret ettiği takma ad. |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | [TimeZoneInfo](./timezoneinfo/) sınıfının bir örneğine işaret eden paylaşımlı gösterici için takma ad. |
| [TimeZonePtr](./timezoneptr/) | [TimeZone](./timezone/) sınıfının bir örneğine işaret eden paylaşımlı gösterici. |
## Functions

| Fonksiyon | Açıklama |
| --- | --- |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CheckedCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| const_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConstCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Discard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| dynamic_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForceStaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForEachMemberGVName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| get_pointer | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_vp_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNegativeInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPattern | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPositiveInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeScopeGuard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MemberwiseClone | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| SafeInvoke | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| static_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
