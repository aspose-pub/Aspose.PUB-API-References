---
title: "System::Collections ad alanı"
linktitle: "System::Collections"
second_title: "Aspose.PUB için C++"
description: "C++'ta System::Collections ad alanını nasıl kullanılır."
type: docs
weight: 600
url: /tr/cpp/system.collections/
---



## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) indekse göre adreslenebilen bitlerden oluşur. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BitArrayPtr](./bitarrayptr/) | [BitArray](./bitarray/) işaretçisi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığına (stack) ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir. |
| [CollectionBase](./collectionbase/) | Güçlü tiplenmiş bir koleksiyon için soyut bir temel sınıf sağlar. |
| [ICollection](./icollection/) | Genel olmayan koleksiyon arayüzünü tanımlar. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) yinelemeye (enumerate) izin verilen tüm genel olmayan koleksiyonların temel arayüzüdür. |
| [IEnumerator](./ienumerator/) | Bazı öğeler üzerinde yineleme yapmak için kullanılabilen bir yineleyicinin arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Genel olmayan [IEnumerator](./ienumerator/) uygulamasını, genel Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) üzerine oluşturan sarmalayıcı - Referans Tipleri için sarmalayıcı. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Genel olmayan [IEnumerator](./ienumerator/) uygulamasını, genel Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) üzerine oluşturan sarmalayıcı - Değer Tipleri için sarmalayıcı. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) indeksle bireysel olarak erişilebilen nesnelerden oluşan genel olmayan bir koleksiyonu temsil eder. |
| [IListImplRefType](./ilistimplreftype/) | Referans tipleri için [System::Collections::Generic::List](../system.collections.generic/list/) nesnesi üzerinde [System::Collections::IList](./ilist/) arayüzünü uygulayan stub. |
| [IListImplValueType](./ilistimplvaluetype/) | Değer tipleri için [System::Collections::Generic::List](../system.collections.generic/list/) nesnesi üzerinde [System::Collections::IList](./ilist/) arayüzünü uygulayan stub. |
| [IListWrapper](./ilistwrapper/) | Genel bir koleksiyondan genel olmayan bir koleksiyona dönüştürmeyi destekleyen arayüz. |
| [Invalidatable](./invalidatable/) | [InvalidatableTracker](./invalidatabletracker/) nesneleri aracılığıyla türevlerinin durumunu izlemeyi mümkün kılan sınıf. |
| [InvalidatableTracker](./invalidatabletracker/) | [Invalidatable](./invalidatable/) nesnelerinin izleyicilerini uygulayan sınıf. |
