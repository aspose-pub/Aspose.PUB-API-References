---
title: "System::Diagnostics::PerformanceCounter sınıfı"
linktitle: "PerformanceCounter"
second_title: "Aspose.PUB için C++"
description: "System::Diagnostics::PerformanceCounter sınıfı. PerformanceCounter kullanan çevrilmiş kodun derlenebilmesi için sahte sınıf. Bu sınıfın nesneleri yalnızca System::MakeObject() işleviyle ayrılmalıdır. Bu türden bir örnek asla yığında veya operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'de fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 200
url: /tr/cpp/system.diagnostics/performancecounter/
---
## PerformanceCounter class


PerformanceCounter kullanan çevrilmiş kodun derlenebilmesi için sahte sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işleviyle ayrılmalıdır. Bu türden bir örnek asla yığında veya operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class PerformanceCounter : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Close](./close/)() | Tüm performans sayma işlemlerini durdurur. |
| [NextValue](./nextvalue/)() | Sonraki ölçülen değeri alır. |
| [PerformanceCounter](./performancecounter/)() | Performans sayacı oluşturur. |
| [PerformanceCounter](./performancecounter/)(const String\&, const String\&) | Belirli kategori için performans sayacı oluşturur. |
| [PerformanceCounter](./performancecounter/)(const String\&, const String\&, const String\&, const String\&) | Belirli kategori ve örnek adı için performans sayacı oluşturur. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
